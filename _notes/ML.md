---
title: "ML options"
date: 2026-10-14
---



# Why parameterize model parameters?
 - reduce time taken for model inference
 - reduce file/model size

<!-- ![[Pasted image 20230724142836.png]]  --> 
For the above, we have 
 input = **Input**((**None**, **50**))  
 dense = **Dense**(**100**)(input)  
 dense = **Dense**(**1**)(dense)  
 dense = **Dense**(**100**)(dense)  
 output = **Dense**(**50**)(dense)  
 model = **Model**(input, output)

For any kind of NN, first thing is to make architecture, then build the model according to it. In an NN, the hyperparameters to tune are the number of neurons, activation function, optimizer, learning rate, batch size, and epochs. One can also tune # of layers.
### Keras 
A high-level API, in the context of deep learning, refers to an interface or library that provides a user-friendly and abstracted way to interact with the underlying deep learning framework. It simplifies the process of building, training, and evaluating deep learning models by hiding low-level implementation details and providing easy-to-use abstractions. Keras brings in simplicity with syntax and use, compatibility with backends, creating complex models etc. Transitions to other frameworks is also easier.
Keras, originally a separate deep learning library, is now integrated into TensorFlow as `tf.keras`, providing the high-level API functionality within the TensorFlow framework. Enjoy the ease of Keras while benefiting from the extensive capabilities and ecosystem of TensorFlow as the backend.

### Workflow of NN
An **activation function is a parameter in each layer**.
  Input data are fed to the input layer, followed by hidden layers, and the final output layer. The output layer contains the output value. 
     The input values moving from a layer to another layer keep changing according to the activation function. 
           **The activation function decides how to compute the input values of a layer into output values**. 
              The output values of a layer are then passed to the next layer as input values again.

Each activation function has its own formula (and graph) to compute the input values.

**Optimizer** - responsible to change the LR (learning rate) and weights of neurons in the NN to reach minimum loss fn.

 Trade off always between LR and epochs, less capacity and memory. More one is, others have to be less. 
      A higher learning rate makes the model learn faster, but it may miss the minimum loss function and only reach the surrounding of it. A lower learning rate gives a better chance to find a minimum loss function. As a tradeoff lower learning rate needs higher epochs, or more time and memory capacity resources.


**Batch size** - sub sets of total training set. If I have X = 100,000 images, i can train in sets of 10,000 ten times. But variance between batches is a major factor to train. However, such batching improves learning and size management. Huge batches/datasets means model building can take time.

After batching comes epoch, i.e. number of times a whole dataset is passed through the neural network model is called an epoch. One epoch means that the training dataset is passed forward and backward through the neural network once.

---

### Backpropagation
Passing a training dataset backward through a neural network is a fundamental step in the training process, known as "Backpropagation".
1. **Forward Pass**: In the forward pass, the input data (training dataset) is fed into the neural network, and the data propagates layer by layer through the network. At each layer, the input is transformed through a series of weighted transformations (linear operations) and activation functions (non-linear operations). Eventually, the network generates predictions or output.
2. **Loss Calculation**: After the forward pass, the output of the neural network is compared to the actual labels (ground truth) from the training dataset. This comparison is done using a loss function (e.g., Mean Squared Error, Cross-Entropy) that quantifies the discrepancy between the predicted values and the true values.
3. **Backpropagation**: Backpropagation is the process of computing the gradients of the loss function with respect to the model's parameters (weights and biases). It involves working backward through the layers of the neural network to calculate how much each parameter contributed to the overall error.
4. **Gradient Descent**: Once the gradients have been computed, the optimization algorithm (typically a variant of gradient descent) uses these gradients to update the model's parameters in a way that minimizes the loss function. This step is essential for "learning" in the neural network as it guides the model to improve its predictions. 
5. **Parameter Updates**: The computed gradients are used to update the model's parameters using an optimization algorithm (e.g., gradient descent or its variants). The optimization algorithm adjusts the model's parameters to minimize the loss function, effectively improving the model's performance on the training data.
6. **Iterative Process**: The forward pass, loss calculation, backpropagation, and parameter update are iteratively performed multiple times (across multiple epochs) during the training process. Each iteration helps the model adjust its parameters to reduce the prediction error and improve its performance on the training data.
In backpropagation, we pass the output of the neural network backward through the layers, but we do not pass it all the way back to the original input data (input dataset). Instead, we pass it back to the layers of the network to update the model's parameters (weights and biases) so that the network learns from the training data.

### Optimizers 
Algorithms used to update parameters. There can be multiple, most famous being ADAM, Nadam etc.

# Parts of a DNN
_Nodes_ are individual units within a neural network that receive input from the previous layer and produce output for the next layer. Each node performs a weighted sum of the input data, applies an activation function to the result, and passes the output to the next layer.

_Activation functions_ are used within nodes to introduce nonlinearity into the network output. They are used to model complex relationships between the input and output data and ensure that the network output is bounded and can be easily interpreted.

_Dropout layers_ reduce overfitting in a neural network by randomly dropping out a percentage of nodes during training. This helps prevent the network from becoming too specialised in the training data and ensures that it can generalise to new data.

_Batch normalisation layers_ are used to normalise the input data to each layer of the network, improving the stability and performance of the network. They work by normalising the output of each layer to have a mean of 0 and a standard deviation of 1, making it easier for the network to learn the appropriate weights and biases for each layer.


---

##  Local Minima in a loss function (how to deal)
Dealing with multiple local minima in a loss function is a common challenge in training machine learning models. While techniques like k-fold cross-validation and sampling can help improve the model's performance, they may not directly address the issue of getting stuck in local minima. Here's how these techniques can play a role:

1. **K-Fold Cross-Validation:** K-fold cross-validation is a technique used to assess the model's performance by partitioning the dataset into k subsets. It helps in estimating the model's generalization ability and robustness. While k-fold cross-validation can provide a better understanding of the model's performance on different subsets of data, it doesn't directly address the issue of local minima during training.

2. **Sampling Techniques:**
   - **Random Sampling:** Randomly shuffling the training data or using random sampling for mini-batch training can help the optimization process escape from some local minima and explore different parts of the loss landscape. This is because random sampling introduces more variability in the gradient updates.
   - **Mini-Batch Gradient Descent:** Using mini-batch gradient descent instead of full-batch can help the model navigate out of local minima more effectively. The noise introduced by mini-batch updates can help the optimization process escape from flat regions of the loss landscape.
   - **Stochastic Gradient Descent (SGD):** In SGD, a single randomly chosen sample is used for each update, which introduces even more noise. While this noise can help escape local minima, it might also lead to slower convergence.

3. **Initialization:** Proper initialization of model parameters can also influence whether the optimization process gets stuck in a local minimum. Using techniques like Xavier/Glorot initialization or He initialization can help the optimization process start from a better point in the loss landscape.

4. **Learning Rate Scheduling:** Adjusting the learning rate during training can help the optimization process navigate around the loss landscape more effectively. Learning rate scheduling techniques like learning rate decay or adaptive learning rate methods can be beneficial.

5. **Regularization:** Regularization techniques like L1 or L2 regularization can have a smoothing effect on the loss landscape, potentially reducing the presence of sharp local minima.

6. **Network Architecture:** The architecture of the neural network itself can influence the presence of local minima. Complex architectures might have more complicated loss landscapes, but they can also increase the chances of finding good solutions.

7. **Optimization Algorithms:** Some optimization algorithms, like Adam and RMSProp, use adaptive learning rates and momentum, which can help navigate the loss landscape more effectively.

It's important to note that while these techniques can help the optimization process escape local minima, there's no guarantee that they will find the global minimum. Often, the choice of optimization algorithm, learning rate, and initialization strategy depends on empirical experimentation to find the best combination for a specific problem.

---

