---
title: "physics_foundations"
date: 2026-10-15
---


## Things to add:
**PhD templates:** 
https://git.hep.physik.uni-siegen.de/latex/phd-thesis-template - by niko
https://git.hep.physik.uni-siegen.de/latex/thesis-generator - most up to date?
https://gitlab.cern.ch/bmondal/thesis - BD's

## Contents (adapted from the INT note):
- Introduction - SM and ttyy process
  - SM 
      - Brief QFT and Lagrangian
      - top and photon (ttyy motivation)
         - anomalous couplings and motivation for analysis (ratio) 
-  LHC and ATLAS
     - Detector and collider physics, 
     - QT stuff
- Simulation part 
	 - how monte carlo simulations take place (maybe a bit from MC contact times)
	 - overflow/workflow, probably adapted from pythia8 manual
	 - what simulations are being used in the analysis
	 - madgraph and pythia studies, maybe a short part on sim. Check Amu Da's thesis for that, he had done some stuff.
	 - Dataset and sample overlap
	 - 
- Event selection
	-  what and how? 
	- This is gonna be my weakest part, so not sure how to put things together. 
	- Description of events and stuffs.
	- SR 
- Background estimation
	- efakes
	- hfakes
	- lepton fake studies with ttbar all had
- Signal Background discrimination
	- Introduce BDTs
	- Little bit about XGBoost. Little bit about gradient descent maybe first, or the traditional tools
	- Results from BDT training
	- Appendix? Studies with different BDT WP, 3-class etc. Negative weight studies abs and all. Other studies? Check gdoc comments and suggestions from Knut over last years
- Sources of Systematic uncertainties
	-  experimental, modelling etc. (from INT)
- Measurement results
	- Brief discussion of likelihood and profile likelihood
	- ttyy results
	- ratio results
	- Tests with different k-factors, no k-factor, systematic checks? SF checks?
- Results and conclusions
Appendix:

 - Studies with other variables based solely on cut-based → starting with HT maybe? Photon conversion type, leading photon etc. 
- Correlation matrices in bdt (and how they are calculated)
- Checks with MVA trainer (traditional boosting technique)
- scale_pos_weights studies, negative weight studies etc.

---
## Time breakdown of thesis writing:
Writing speed - $284/7=$ 40 words per minute. 
Given my thesis will have ~150 pages, and each page has like 200 words, I will be writing 
150 * 200 = 30,000 words. 
But maybe there will be multiple iterations as well, so let's say a good number would be 50,000 words. So according to my writing speed, if 40 words take me 7mins, 50,000 words will take me 
50000/40 = 1250 minutes = 21 hours? Are you kidding me? 
Of course it's just writing. Thinking will take much more than that. 
Okay tentative it would be like just 5-6 days of uninterrupted writing (including sleep, bath, food etc.)
So
<span style="color:#e87878">
    writing- 6-7 days<br>
     formatting - 3-4 days<br>
     producing results - not sure, 4-5 days<br>
     reading and thinking - 10-15 days, maybe more<br>
     More editing and stuff - 3-4 days</span>
     
So on average, the thesis should take me 30-40 days or so, so almost a month of uninterrupted work. Then in between there will be times of re-evaluation, working on paper, comments, blue days etc. 
Things are gonna slow me down drastically. 


---

## Quotes:

Here are a few real “pearls” from very different corners of literature and science that subtly nod toward the spirit of Monte Carlo–style modeling, randomness, and data‐driven inference:

- **John von Neumann** (on over-fitting models):
    
    > “With four parameters I can fit an elephant, and with five I can make him wiggle his trunk.”  
    > _Los Alamos Report, c. 1955_  
    > _(A wry reminder that throwing free parameters at a problem can always reproduce almost any data—just as a naïve Monte Carlo fit might.)_
    
- **Arthur Conan Doyle** (Sherlock Holmes in _A Study in Scarlet_, 1887):
    
    > “It is a capital mistake to theorize before one has data. Insensibly one begins to twist facts to suit theories.”  
    > _(Monte Carlo simulations exist to generate—objectively—what the “data” would look like under your model before you ever see it.)_
    
- **Louis Pasteur** (lecture at University of Lille, 1854):
    
    > “In the fields of observation chance favors only the prepared mind.”  
    > _(Random sampling only becomes insight if you know how to interrogate it.)_
    
- **Leonardo da Vinci** (notebook aphorism):
    
    > “Learn to see. Realize that everything connects to everything else.”  
    > _(A nice cue that, in a multivariate Monte Carlo, every output bin is tied—through physics and detector effects—to every input parameter.)_
    
- **Zhuāngzǐ** (《莊子》, 4th century BCE):
    
    > “The frog in the well knows nothing of the ocean.”  
    > _(Reminds us that sampling only a tiny region of “phase-space” can blind you to the full behavior of your simulation.)_
    
- **Richard Feynman** (Caltech Commencement, 1974):
    
    > “The first principle is that you must not fool yourself—and you are the easiest person to fool.”  
    > _(Perhaps the most on-point admonition when you’re running thousands of pseudo-experiments.)_
    

**Finding obscure quotes**

The user wants quotes on specific concepts from less famous sources, so I need to find quotes that touch on unity, diversity, and simplicity, especially related to the Standard Model. I could go beyond famous figures like Dirac and Einstein and turn to literary figures like Goethe or Blake. For example, "To see a World in a Grain of Sand" from Blake is a great fit for exploring underlying unity. The quote should be both real and relevant, but I want to keep things "low-key" obscure.

**Selecting quotes for topics**

I’m going with William Blake's line: "To see a world in a grain of sand, And a heaven in a wild flower." It fits as a subtle way to evoke unity and the structure of the universe, which could connect nicely to the Standard Model. As for the LHC and ATLAS, a quote about large-scale collaboration could work well, though I might go for something from Jules Verne instead of the original attribution to Bulwer-Lytton. This focuses on the ambition behind big scientific endeavors.

**Finding a solid quote**

I was initially thinking of quotes from famous sources, like Feynman's or Galileo’s work, but they're already widely known. Galileo’s line, “Measurement is the foundation of knowledge,” stands out as fitting for experiments and emphasizing measurement, though it's not super obscure. It works well for the topic, even if it's moderately known. I think Galileo is the best choice here, after ruling out other options. The quote highlights the importance of measurement, a key part of experiments.

**Selecting quotes on measurement, selection, and rejection**

I’m considering several quotes to highlight themes of measurement and scientific selection. Galileo’s “Measure what you can and cannot” fits the bill, emphasizing the experimental process. For boundaries in selection, I think Tukey’s “An approximate answer to the right question…” is good for defining areas like fiducial regions. Huxley’s “Sit down before fact as a little child…” also works for accepting facts and evolving our understanding. I’ll propose using these two for clarity in the context of cross-sections and measurements.

Thought for 19 seconds

**1. Standard Model (Theory of Everything)**

- _William Blake_, “Auguries of Innocence” (1803)
    
    > “To see a World in a Grain of Sand,  
    > And a Heaven in a Wild Flower…”  
    > _(Hints that the vast and the minute share the same underlying pattern.)_
    
- _Paul Dirac_, interview with _Physics Today_ (1963)
    
    > “It is more important to have beauty in one’s equations than to have them fit experiment.”  
    > _(Reflects the SM’s mathematical elegance driving discovery.)_
    

---

**2. LHC & ATLAS (The Experiments)**

- _Galileo Galilei_, _The Assayer_ (1623)
    
    > “Measure what can be measured, and make measurable what cannot.”  
    > _(A call to push instrumentation beyond its known limits.)_
    
- _Max Planck_, address at University of Berlin (1889)
    
    > “Experiment is the only means of knowledge at our disposal. Everything else is poetry, imagination.”  
    > _(Underscores that machines like ATLAS turn theory into tangible data.)_
    

---

**3. Monte Carlo Simulation**  
_(As before—any of these subtle, real-world gems)_

- John von Neumann:
    
    > “With four parameters I can fit an elephant, and with five I can make him wiggle his trunk.”
    
- Arthur Conan Doyle (Sherlock Holmes):
    
    > “It is a capital mistake to theorize before one has data.”
    
- Louis Pasteur:
    
    > “In the fields of observation chance favors only the prepared mind.”
    

---

**4. Cross-Section & Fiducial Definition**

- _Thomas Huxley_, letter to Charles Darwin (1860)
    
    > “Sit down before fact as a little child, be prepared to give up every preconceived notion…”  
    > _(On choosing exactly which events to accept or reject.)_
    
- _John Tukey_, _The Future of Data Analysis_ (1962)
    
    > “Far better an approximate answer to the right question… than an exact answer to the wrong question.”  
    > _(Captures the art of defining a meaningful fiducial region.)_
    
- _George E. P. Box_, _Robustness in the Strategy of Scientific Model Building_ (1979)
    
    > “All models are wrong, but some are useful.”  
    > _(A reminder that your acceptance cuts still rest on simplifications.)_
    

---

**5. Background Estimates**

- _Charles Baudelaire_, “Les Épaves” (1857)
    
    > “The greatest trick of the devil is to persuade you that he does not exist.”  
    > _(Backgrounds can hide perfectly as signal.)_
    
- _Donald Rumsfeld_, U.S. DoD briefing (2002)
    
    > “There are known knowns… known unknowns… and unknown unknowns.”  
    > _(Signal-mimicking background often lives in the ‘unknown’.)_
    
- _Sherlock Holmes_, _The Sign of Four_ (1890)
    
    > “When you have eliminated the impossible, whatever remains, however improbable, must be the truth.”  
    > _(An analysis mantra for teasing out irreducible backgrounds.)_
    

**Finding subtle quotes for topics**

The user wants quotes related to specific topics like boosted decision tree (BDT), systematic uncertainties, fit and measurement, and results interpretation. These quotes should be drawn from known works, subtly related to the topics, and include proper citations. I’m thinking of possible sources like Carl Friedrich Gauss, Donald Knuth, or even Stephen King or George Box for interesting and relevant, yet subtle references. I’ll make sure I find quotes that resonate with those topics in a nuanced way.

**Exploring quotes for decision trees**

I’m looking for a relevant, subtle quote for decision trees. Robert Frost’s “Two roads diverged in a yellow wood” fits the theme of branching, but it’s a bit well-known. Nietzsche’s "He who has a why to live can bear almost any how" seems deep, but not quite right for this. Hmm… maybe Descartes, with “To live without philosophizing...”? Still not perfect. I’m leaning toward something like Borges' idea of libraries, but it’s tricky finding the right fit. A decision tree is quite the puzzle!

Thought for 14 seconds

Here are a few real “pearls” for each:

---

### 6. Boosted Decision Tree

> “Two roads diverged in a yellow wood,  
> And sorry I could not travel both…”  
> — Robert Frost, _The Road Not Taken_ (1916)  
> _(A gentle nod to branching choices and finding the optimal path.)_

---

### 7. Systematic Uncertainties

> “If a man will begin with certainties, he shall end in doubts;  
> but if he will be content to begin with doubts, he shall end in certainties.”  
> — Francis Bacon, _Novum Organum_ (1620)  
> _(On embracing and quantifying the unknowns in your measurement.)_

---

### 8. Fit & Measurement

> “What we observe is not nature itself, but nature exposed to  
> our method of questioning.”  
> — Werner Heisenberg, _Physics and Philosophy_ (1958)  
> _(A reminder that your likelihood fit reflects both data and the model you bring to it.)_

---

### 9. Results & Interpretation

> “Nature’s imagination is so much greater than man’s;  
> she is never tired of surprising us.”  
> — Richard Feynman, _The Pleasure of Finding Things Out_ (1998)  
> _(Leaves the door open for new physics beyond your measured result.)_

Or, for a touch of the dramatic:

> “There are more things in heaven and earth, Horatio,  
> than are dreamt of in your philosophy.”  
> — Shakespeare, _Hamlet_ (I.v)  
> _(Even a carefully extracted cross-section may hint at surprises.)_


Thought for a couple of seconds

Here’s another batch—each topic gets a fresh set of real quotations that hint at its spirit without spelling it out:

---

## 6. Boosted Decision Tree

- **Jorge Luis Borges**, _“The Garden of Forking Paths”_ (1941)
    
    > “In an infinite series of times and places, I chose one and another I did not choose.”  
    > _(Branching possibilities echo the splits in your tree.)_
    
- **Henry David Thoreau**, _Walden_ (1854)
    
    > “If a man does not keep pace with his companions, perhaps it is because he hears a different drummer.”  
    > _(Each branch “drums” its own path through the data.)_
    
- **Shel Silverstein**, “The Crocodile’s Toothache” (1974)
    
    > “Which way should I go? Nobody knows!”  
    > _(A playful nod to decision boundaries.)_
    

---

## 7. Systematic Uncertainties

- **John Stuart Mill**, _On Liberty_ (1859)
    
    > “He who knows only his own side of the case knows little of that.”  
    > _(Recognizing bias in every model.)_
    
- **Rene Descartes**, _Discourse on the Method_ (1637)
    
    > “If you would be a real seeker after truth, it is necessary that at least once in your life you doubt, as far as possible, all things.”  
    > _(The root of systematic error estimation.)_
    
- **Dante Alighieri**, _Inferno_ (c. 1308)
    
    > “In His will is our peace.”  
    > _(But escaping Hell’s circles—quantifying what you don’t know—takes careful mapping.)_
    

---

## 8. Fit & Measurement

- **Claude Bernard**, _An Introduction to the Study of Experimental Medicine_ (1865)
    
    > “Experiment is the sole judge of scientific truth.”  
    > _(Your likelihood fit is that judge.)_
    
- **Michelangelo**, (on sculpture)
    
    > “I saw the angel in the marble and carved until I set him free.”  
    > _(Fitting data “frees” the underlying parameter.)_
    
- **Mary Shelley**, _Frankenstein_ (1818)
    
    > “Learn from me… how dangerous is the acquirement of knowledge.”  
    > _(Beware overfitting when you “animate” your fit.)_
    

---

## 9. Results & Interpretation

- **T. S. Eliot**, “Little Gidding” (1942)
    
    > “We shall not cease from exploration / And the end of all our exploring / Will be to arrive where we started…”  
    > _(Each result points you to the next question.)_
    
- **Thomas Jefferson**, letter (1813)
    
    > “The earth belongs to the living.”  
    > _(Your findings live on only if they spur new discovery.)_
    
- **Mary Oliver**, _Dog Songs_ (2013)
    
    > “Instructions for living a life: Pay attention. Be astonished. Tell about it.”  
    > _(Interpretation is the final, human-facing step.)_
    

---

Pick your favorites, mix sources, or use these as springboards. Happy quoting!

------------------

## Words/phrases:
- tackle the bull by the horns
- 

---


# Tips and nuggets of information here and there (box-formed):

- Decision trees are deterministic.
- ## What is a cross section?

At its core, the **cross section** σ\sigmaσ of a process in particle physics quantifies the **likelihood** of that process occurring during an interaction. It has units of area (e.g., barn, picobarn), but it doesn’t represent a literal geometric area — instead, it's a _normalized probability_ per unit flux and per target density.

The conceptual origin comes from classical scattering: a bigger target has a bigger probability of being hit. In quantum field theory, we extend this idea: more “probable” processes have larger cross sections.
**Inherent Physical Meaning:**

- **Yes**, in that the cross section is **derived from the underlying quantum field theory**. It's computed from matrix elements via Feynman rules, and includes all interference and quantum effects.
    
- It reflects the **amplitude squared** of the process, integrated over allowed phase space, constrained by conservation laws.
xsec encapsulates the **structure of the Lagrangian**, the masses and couplings of the particles involved, and the accessible kinematics of the collider.
![](/images/notes/Pasted image 20250603140001.png)
Here : https://physics.info/qcd/practice.shtml

- **Both pQCD and non-pQCD processes are unobservable at the parton level**.
    
- But **pQCD is predictive and testable** via indirect observables.
    
- **Hadronisation is descriptive and model-dependent**, inferred by matching data with simulations.
---

2025-05-26
No need to reinvent the wheels. Let's start now.

hmm..

## Chapters:
- Introduction - brief (1-2 pages)
- SM and top quark 
   Rare SM processes and ratio maybe 
   CP violation
- LHC and ATLAS - experimental setup 
- Pixel work - QT
- Events simulation - physics (Detectors to physics analysis)
- Data and MC - at ALTAS chapter 3 of int and include OR
  categorisation of processes
  Fiducial region defn
- Event selection - chapter 4 
- Background estimates ??
- BDT - neural network for Sig-Bkg discrimination
- Systematic uncertainties
- Measurement and bit about ratio - include cross section definition
  explain cross-section, likelihood, bit of statistics of course
- Results and interpretation
- Appendix - extra stuffs


### Amu Da's thesis: https://www.hep.physik.uni-siegen.de/pubs/diss/rej-dr.pdf
- A bit about photon idenitification - radiative Z, matrix method, electron extrapolation method.


### BD's thesis: https://www.hep.physik.uni-siegen.de/pubs/diss/mondal-dr.pdf


### Read Mervin's thesis as well - from Wuppertal?  

## Citations:
#citations 
- h-fake ABCD method: https://journals.aps.org/prd/abstract/10.1103/PhysRevD.103.035021 
- snomass report of 2013:  https://arxiv.org/pdf/1311.0299
## Quotes per chapter:





### Breakdown of processes at the LHC:
![](/images/notes/Pasted image 20250307091029.png)


# Chapter 2: SM
### List of things-

![](/images/notes/Pasted image 20250307091719.png)
So maybe add some descriptions here as well:


![](/images/notes/Pasted image 20250307091735.png)



## ML learning things:


### Normalizing Flow NN:

A **normalizing flow neural network** is a technique for transforming a simple probability distribution (like a Gaussian) into a complex one using a series of invertible transformations.

### **Key Idea:**

- Start with a **simple distribution** (e.g., Gaussian noise).
- Apply a **series of invertible transformations** (parameterized by a neural network).
- The result is a **more complex distribution** that can model real data.

### **Why Use It?**

- It allows **exact likelihood evaluation** (unlike GANs).
- It provides **efficient sampling and density estimation** (unlike VAEs).
![](/images/notes/Pasted image 20250310151147.png)

### **Use Cases**

- Generative modeling (like VAEs and GANs).
- Density estimation.
- Bayesian inference.
The overall tech is a ... i don't know what the hell i'm writing right now.


## https://arxiv.org/pdf/2503.04289
### Machine learning in top quark physics at ATLAS and CMS

#### About Top reconstruction 
Normalizing flow as above.
Also SPANET to reconstruct decay particles.
![](/images/notes/Pasted image 20250311144116.png)

#### Analysis
For background rejection, in ABCD methods, there's DISCO
"The DISCO method introduces an NN classifier to construct suitable observables that are uncorrelated and simultaneously separate the signal from background processes...  <mark style="background: #FFB8EBA6;">by introducing an additional penalty term during the training to suppress distance correlations</mark> either between the scores of two NN classifiers or between one score and an auxiliary
observable."

Also, CMS used auto-regressive normalizing flows:
![](/images/notes/Pasted image 20250311144552.png)
### Statistical inferences:

"In physics, the solution of Fredholm integral equations allows for experimental spectra to be related to various underlying distributions, for instance the mass distribution of polymers in a polymeric melt,..."

####  OMNIFOLD:
differences between simulation and data are learned via a classifier and subsequently reweighted to match the distributions in the simulated signal sample to data.
As of now, used only for DrellYan and min. bias events.


---



![](/images/notes/Pasted image 20250320140400.png)

---

![](/images/notes/photonConversionDrawing.svg)The above is jan's vector-graphic for conv. and unconv. with inner detector rings in place and to scale (only id rings, not ecal).

## Software used: 
Athena and TDAQ
#### reference from tty paper

![](/images/notes/Pasted image 20250326092704.png)


# Luminosity
## Lumi levelling:

Luminosity levelling is a technique used at the LHC (Large Hadron Collider) to control and maintain the instantaneous luminosity delivered to detectors such as ATLAS, CMS, LHCb, and ALICE, within optimal or acceptable limits over time during a fill.

### Purpose

The primary goal of luminosity levelling is **to ensure a stable data-taking environment** and **to protect the detectors** from excessive particle rates or pile-up. High instantaneous luminosity can lead to too many overlapping proton-proton collisions (pile-up), which complicates event reconstruction and can stress both the detector hardware and the trigger/data acquisition systems.

### How It's Done

Several methods can be used to achieve luminosity levelling, including:

1. **Transverse beam separation**: The colliding beams are intentionally misaligned slightly so that the overlap of the bunches is reduced. This lowers the collision rate.
    
2. **Crab cavity voltage tuning**: Modifying the RF phase and voltage in crab cavities can affect the overlap angle and thus the effective luminosity.
    
3. __Beta_ adjustment_*: The beta function at the interaction point (β∗\beta^*) can be changed to modify the beam focus. A larger β∗\beta^* means a less focused beam, reducing the collision rate.
    
4. **Crossing angle variation**: Altering the angle at which the beams cross can change the effective overlap region, influencing luminosity.
    
5. **Bunch population control**: In special cases, the intensity (number of protons per bunch) can be managed or tailored across fills, although this is generally set at injection.
    

### Benefits

- **Stable detector conditions**: Helps maintain a consistent pile-up level, which improves data quality and simplifies calibration.
- **Extended physics reach**: Allows long-duration runs at near-optimal luminosity instead of short bursts of very high luminosity followed by rapid drops.
- **Detector safety**: Prevents damage or rapid ageing of sensitive detector components due to high occupancy or radiation.

For experiments like LHCb and ALICE, which are not designed to handle the high pile-up levels seen in ATLAS or CMS, luminosity levelling is essential. In ATLAS and CMS, it is used strategically during periods when instantaneous luminosity would otherwise exceed manageable levels.



atlas link : https://atlas.cern/Updates/Briefing #physicsbriefings
#newresults


# Run3 upgrades - physics motivation:

## muon detector upgrade - 
Currently, limited pT resolution → higher trigger thresholds for single muons.
Impacts EW processes.
NSW - can sharpen L1 trigger resolution and store lower threshold results.

### NSW: 
Has Thin gap chambers-micromegas detectors for better resolution.
Faster readout for trigger because of small strip (?) 
Large-scale precision chambers require careful quality control.
Main aim of NSW - reduce the fake muon triggers in forward region, improve sharpness of trigger threshold. 


## LAr and L1 calo trigger - 
Goal is to increase trigger energy resolution and identification efficiency for e, \mu, \tau by increasing granularity.
Increase information from super cells (instead of coarse trigger towers) allows for shower shape measurements.
Improved jet rejection.
![](/images/notes/Pasted image 20250326103818.png)
monojets+ MET signature used for exotic searches
VB scattering - WW, ZZ, WZ etc.

LS2 upgrades for run3:
"
To improve the selectivity of the electron trigger, the amount of information used for the trigger decision will be drastically increased: until now, the very fine-grained information produced by the electromagnetic calorimeter is grouped in “trigger towers” to limit the number and hence cost of trigger channels, but advances in electronics and the use of optical fibres allows the transmission of a much larger amount of information at a reasonable cost. By replacing some of the components of the front-end electronics of the electromagnetic calorimeter, the level of segmentation available at the trigger level will be increased fourfold, improving the ability to reject jets and preserve electrons and photons. The ATLAS trigger and data-acquisition systems will also be upgraded during LS2 by introducing new electronics boards that can deal with the more granular trigger information coming from the detector.
"  - atlas upgrade in ls2, news briefing, 2019

![](/images/notes/Pasted image 20250326113239.png)
    Run 2                        Run 3


---

# Physics performance and results from run 2:

![](/images/notes/Pasted image 20250326113340.png)

You can see how much still remains to be explored.

### Plus points about ATLAS:

![](/images/notes/Pasted image 20250326113913.png)


"ATLAS is putting the Standard Model to the test"

ATLAS cross section measurements confirm predictive power of the Standard Model.
Important to understand all backgrounds to searches for new physics.

#### First Evidence for Three Vector Boson Production:

- evidence for WVV processes.
- involve triple and quartic gauge couplings.
- use of MVA to suppress bkg, 

#### Higgs interactions:
![](/images/notes/Pasted image 20250326130539.png)

![](/images/notes/Pasted image 20250326130608.png)

![](/images/notes/Pasted image 20250326131501.png)

---

"The **strong and weak forces** build the **nuclear skeleton**, and **gravity** sculpts the **cosmic canvas**, but **EM paints nearly everything in between**."


---

# Trigger operations:

#citation : https://arxiv.org/pdf/2007.12539

![](/images/notes/Pasted image 20250326165415.png)
### working of #trt :
#id #atlas
**how it distinguishes electrons from other charged particles** (like pions):

- The **TRT is filled with a special material** (radiators) that causes **high-energy electrons** to emit **transition radiation**—a type of X-ray photon—**when crossing boundaries between materials with different dielectric constants**.
- These X-ray photons get absorbed in the detector gas, producing **larger energy deposits** than usual ionization.
- The electronics of the TRT have a **high threshold setting**: if a hit exceeds this threshold, it's a candidate for **transition radiation**.
- **Electrons**, being light and relativistic, emit **more transition radiation** than heavier particles like pions.
- So, the **fraction of hits above this high threshold** is used to **identify electrons** statistically.

In short: **more high-threshold hits → more likely it's an electron**. The TRT uses this pattern to help ATLAS identify electrons among many charged tracks.
**Pixel** and **SCT** detectors in ATLAS also provide detailed tracking information, including **charge deposit**, and that all inner detector components sit inside the **magnetic field**, allowing **momentum measurements** from the curvature of tracks.

But when it comes to **electron identification**, particularly **separating electrons from charged hadrons** (like pions), the roles differ between the subsystems:

---

#### 1. **What Pixel and SCT contribute:**

- **Precise tracking**: Excellent spatial resolution helps in reconstructing track origin (vertex), impact parameter, and matching to electromagnetic calorimeter clusters.
- **Momentum measurement**: Track curvature in the magnetic field provides transverse momentum pTp_T, crucial for all particle identification.
- **Charge deposition (dE/dx)**: Yes, the **Pixel detector**, in particular, can measure the **amount of ionization charge** deposited per hit. This is sometimes used for **limited particle ID**, especially for **low-momentum particles**, where energy loss differs more clearly by particle type.

However:

- The **dE/dx resolution in Pixel and SCT is modest**, and not optimized for distinguishing electrons from minimum-ionizing hadrons at high energy.
- For **high-momentum electrons**, the **ionization loss** of electrons and pions becomes **very similar** (both near minimum ionizing), making dE/dx-based separation weak.

---

#### 2. **Why TRT is special for electron ID:**

- The **TRT is explicitly designed** to exploit **transition radiation**, which only electrons (due to their small mass and resulting high Lorentz gamma factor) produce efficiently.
- This gives the TRT a **distinctive handle** on electron ID that the Pixel and SCT simply don’t have access to.

So, in essence:

- **Pixel and SCT** help track the particle with high precision and provide momentum and limited dE/dx information.
- **TRT** provides **additional discrimination power** by detecting transition radiation, which is essentially a **signature unique to relativistic electrons**.

---


While Pixel and SCT contribute valuable tracking and kinematic info, they **lack the physical mechanism (transition radiation)** that gives TRT its electron ID capability. Electron identification in ATLAS is strongest when **combining information** from:

- **Inner detector tracks (Pixel + SCT + TRT)**
- **TRT high-threshold hits**
- **Calorimeter cluster shape and energy matching**

This combination is what enables robust **electron-vs-hadron separation**, particularly in dense environments like jets.


## Calorimeters:
#calo
### Ecal 
lead/liquid Argon LAr with high granularity.
### HCal 
steel/scintillator tile calorimeter.

## Muon spectrometer:
Separate trigger and high-precision tracking chambers to measure the deflection of muons in a magnetic field generated by the superconducting air-core toroids.
Contains CSC, TGC, RPCs.
![](/images/notes/Pasted image 20250326165437.png)
RPC → barrel
TGC → endcap

----



Coming to the Trigger part now:
 ATLAS TDAQ system is responsible for online processing, selecting and storing events of interest for offline analysis
### L1 → readout 100kHz
HW based, triggers on reduced gran- info from calo (L1calo → CP and JEP processors for identification and jet and MET calculations) and MS (L1Muon → uses RPC and TGC, coincides with tile calo info too).
L1 trig decision by CTP. 
CTP ← receives inputs from l1calo, l1muon, l1topo, mbts, and LUCID and ZDC.
RODs → initial preprocessing and fornatting
ROSs → buffer the data
The final data sent to **HLT**, only when requested with regions of interest ($\eta$, $\phi$).

### HLT → 1kHZ
SW based, decisions made on Processing Units (PUs).
Based on Athena, which is based on Gaudi.
Finally, data sent to SFO and then exported to Tier-0.



---

# XGBoost (versus Decision trees):

Reference: https://www.spiceworks.com/tech/artificial-intelligence/articles/xgboost-vs-random-forest-vs-gradient-boosting/


Random forest is a popular machine learning algorithm that merges the output of several [decision trees](https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-decision-tree/ "decision trees") to achieve a single output.
...
Each question is a step toward a final decision, denoted by a ‘leaf node’. Observations matching the set criteria will flow along the ‘Yes’ branch, while those that don’t will flow along the alternate path.

Decision trees are generally trained via the Classification and Regression Tree (CART) algorithm, and metrics such as information gain, mean square error (MSE), and Gini impurity can be used to evaluate split quality. Prone to bias and over-fitting.
...However, with multiple decision trees forming an ensemble in Random Forest, more accurate results can be predicted, especially when individual trees are uncorrelated.

XGBoost was developed to create an efficient distributed gradient boosting library. It achieves this goal well, using an optimized mix of ensemble learning and merging predictions from multiple weak models to produce stronger predictions. Its methodology involves the creation of sequential decision trees, with each tree correcting errors made by the previous tree. Weights are assigned to independent variables and adjusted based on the quality of the outcome prediction by the model. This iterative process results in an accurate, robust machine learning model.


Typical ensemble learning methods -  bootstrapping aggregates (bagging) and boosting.

Once numerous data samples are generated, models are trained independently, and depending on the type of task (regression vs. classification), the average or majority of the predictions give an outcome in the form of a more accurate estimate. This method helps reduce variance within a noisy dataset.

Random Forest is an extension of bagging, utilizing bagging and feature randomness to generate an uncorrelated forest of decision trees. Feature randomness, or feature bagging, creates a random subset of features, leading to low correlation among decision trees. This can be noted as a key difference between decision trees and Random Forests; decision trees consider all possible feature splits, while Random Forests select a limited subset of those features.


Now there's some difference between the concepts that i have introduced before. Let's clear them up.




[![Supervised Learning](https://tse3.mm.bing.net/th?id=OIP.kWC7yGKSgvAeEdW86lM6NAHaH2&cb=iwp1&pid=Api)](https://velog.io/%40protector_will/Supervised-Learning)

Here's a concise, structured explanation from simplest to more complex concepts, showing hierarchy, overlap, and distinctions.

---

### **1. Decision Tree**

- **Basic model**: A tree-like structure that splits data based on feature thresholds to make predictions.
    
- **Use**: Classification or regression.
    
- **Limitation**: Prone to overfitting.
    

---

### **2. Ensemble Learning**

- **Definition**: A method that combines multiple models (often weak learners) to improve performance.
    
- **Includes**: Bagging, Boosting, Stacking, etc.
    
- **Goal**: Better generalization and robustness.
    

---

### **3. Bagging (Bootstrap Aggregating)**

- **Subset of Ensemble Learning**.
    
- **Idea**: Train multiple models in **parallel** on different bootstrapped subsets of data.
    
- **Output**: Aggregate predictions (majority vote or average).
    
- **Purpose**: Reduces variance.
    
- **Example**: Random Forest.
    

---

### **4. Random Forest**

- **Subset of Bagging**.
    
- Ensemble of decision trees trained on:
    
    - **Bootstrapped samples**
        
    - **Random feature subsets** at each split
        
- **Benefit**: Lower overfitting than a single decision tree.
    

---

### **5. Boosting**

- **Subset of Ensemble Learning**, distinct from bagging.
    
- **Idea**: Train models **sequentially**, each focusing on errors of the previous one.
    
- **Purpose**: Reduces bias.
    
- **Models get weighted**, harder examples prioritized.
    
- **Examples**: AdaBoost, Gradient Boosting, XGBoost, LightGBM.
    

---

### **Overlap and Contrast**

|Concept|Built On|Parallel or Sequential|Reduces|Example Models|
|---|---|---|---|---|
|Decision Tree|Base learner|—|—|CART, ID3|
|Bagging|Ensemble method|Parallel|Variance|Random Forest|
|Boosting|Ensemble method|Sequential|Bias|AdaBoost, XGBoost|
|Random Forest|Bagging + Trees|Parallel|Variance|RandomForestClassifier|
### Basic generalizations:
- A **decision tree** is a rule-based model that makes **if-else splits** on features to classify or predict outcomes. It's a **single model**, prone to overfitting.
    
- **Ensemble learning** refers to combining **multiple models** (often weak learners like shallow decision trees) to form a **stronger predictive system**.
    
- **Bagging** is an ensemble method that builds **multiple independent models in parallel** on **bootstrapped data samples** and **aggregates** their outputs.
    
- A **random forest** is a **specific type of bagging ensemble** using **decision trees**, where each tree is trained not only on a bootstrapped dataset but also on a **random subset of features** at each split, introducing additional decorrelation.



### XGBoost versus traditional gradient boosting method:

|Feature/Aspect|scikit-learn Gradient Boosting|XGBoost|
|---|---|---|
|**Core Idea**|Basic gradient boosting with decision trees|Gradient boosting with major system optimizations|
|**Speed & Efficiency**|Slower, especially on large datasets|Much faster due to optimized C++ backend|
|**Regularization**|Minimal (only shrinkage via learning rate)|L1 and L2 regularization (like in linear models)|
|**Parallelization**|Weak or none|Built-in parallelization during tree construction|
|**Handling Missing Values**|Must pre-impute|Handles missing values automatically|
|**Tree Pruning**|Pre-pruning only (stops tree early)|Post-pruning using **max loss reduction**|
|**Sparsity Awareness**|Not supported|Yes — optimized for sparse data|
|**Early Stopping**|Supported (but more manual setup)|Built-in and seamless|
|**GPU Acceleration**|Not available|Supported|
|**Feature Importance**|Available|Available with more flexibility (gain, cover, etc.)|

**Use `XGBoost`** when:

- Working with large datasets
    
- Needing more speed and scalability
    
- Handling sparse data or missing values

More on this later. #more

---
# Standard Model:

## Introduction:
Throughout the ages, humankind has tried to put up an explanation of things to explain the inner workings of the universe. What is everything made of? What holds things together, and pulls them apart in some cases? Is the universe really governed by a set of laws which are simple, and intelligible? Why do particles have a mass? Are there parts of universe we can't observe, yet experience their presence?
Decades of theoretical developments to such curiosities and contemporaneous experimental observations have culminated into the development of something called the Standard model of particle physics. 
The SM is a comprehensive description of the fundamental particles that constitute matter and the forces through which they interact, encapsulating decades of experimental observations and theoretical developments into a single, internally consistent quantum field theory. 
The development over the years have been:
- **1928** – _Paul Dirac_ formulated a relativistic equation for the electron, predicting the existence of antimatter—the **positron**, discovered by _Carl Anderson_ in 1932.
    
- **1930s–40s** – The weak interaction’s strange properties (e.g. beta decay) puzzled physicists. _Enrico Fermi_ proposed a four-fermion theory of beta decay in 1933.
    
- **1940s–50s** – **Quantum Electrodynamics (QED)** was developed by _Richard Feynman_, _Julian Schwinger_, and _Sin-Itiro Tomonaga_—the first successful **quantum field theory (QFT)**, unifying special relativity with quantum mechanics for electromagnetism.
    
- **1954** – _Chen-Ning Yang_ and _Robert Mills_ introduced **non-abelian gauge theory** (Yang-Mills theory), laying the foundation for describing forces via local symmetry principles.
    
- **1960s** – _Murray Gell-Mann_ and _George Zweig_ independently proposed **quarks** as constituents of hadrons. Gell-Mann’s **Eightfold Way** explained the hadron spectrum.
    
- **1964** – _François Englert_ and _Robert Brout_, and independently _Peter Higgs_, proposed a mechanism of **spontaneous symmetry breaking** in gauge theories, predicting the **Higgs boson**.
    
- **1967–1968** – _Steven Weinberg_, _Abdus Salam_, and _Sheldon Glashow_ formulated the **electroweak theory**, unifying electromagnetism and the weak force using SU(2)L×U(1)YSU(2)_L \times U(1)_YSU(2)L​×U(1)Y​ symmetry. The Higgs mechanism gave mass to the W and Z bosons.
    
- **1973** – The electroweak theory was confirmed experimentally via **neutral currents** at CERN. That same year, _David Gross_, _Frank Wilczek_, and _David Politzer_ discovered **asymptotic freedom**, solidifying **Quantum Chromodynamics (QCD)** as the theory of the strong force, with gluons mediating interactions among quarks.
    
- **1974–1977** – The **charm quark** was discovered (J/ψ particle), validating the GIM mechanism. The **bottom** and later the **top** quarks were confirmed in 1977 and 1995, completing the three generations.
    
- **1983–84** – The **W** and **Z bosons** were discovered at CERN’s SPS collider, confirming the predictions of electroweak unification.
    
- **2012** – The **Higgs boson** was discovered at the LHC by the ATLAS and CMS collaborations, completing the Standard Model particle spectrum.

## SM overview:

### Lagrangian:

### SM as a gauge theory based on SU(3)X SU(2)XU(1)

### Particles involved: quarks and leptons

### Gauge bosons

## EW sector:
- Detail the electroweak unification: SU(2)L×U(1)Y→U(1)emSU(2)_L \times U(1)_Y \rightarrow U(1)_{\text{em}}SU(2)L​×U(1)Y​→U(1)em​
    
- Explain spontaneous symmetry breaking via the Higgs mechanism
    
- Describe the coupling structure of fermions to the EW bosons
    
- Emphasize how the photon emerges as the massless gauge boson of unbroken U(1)emU(1)_{\text{em}}U(1)em​

## Top quarks:

discovery, fundamental particle etc. 


## 4. Top-Photon Coupling

Explain why top processes (single top, top with photons) - radiative probe and sensitive to deviation from BSM?

## CEDM and CMDM:

### something about rare processes, and why investigate them?


## Why is SM incomplete?


----

# Figures/Diagrams:
https://commons.wikimedia.org/w/index.php?curid=59970304#/media/File:Standard_Model_of_Elementary_Particles.svg
SM pic

https://en.wikipedia.org/wiki/ATLAS_experiment#/media/File:ATLAS_Drawing_with_Labels.svg
ATLAS cut away

https://home.cern/science/accelerators/accelerator-complex CERN courier 
LHC complex

----

---

# BDT and other things - concepts:
### 🔹 **1. Core Concepts**

These are ideas used across multiple methods.

|Term|What it is|Key Idea|
|---|---|---|
|**Weak Learner**|Concept|A simple model (like a shallow decision tree) that performs just slightly better than random guessing.|
|**Ensemble Learning**|Concept|Combine multiple models (often weak learners) to get a better final model. Two main types: **bagging** and **boosting**.|

---

### 🔹 **2. Ensemble Methods**

These are strategies to combine models.

|Term|What it is|Key Idea|
|---|---|---|
|**Bagging**|Method|Train models independently on bootstrapped data; average (or vote) results to reduce variance.|
|**Boosting**|Method|Train models **sequentially**, where each tries to fix the errors of the previous one; reduces bias.|

---

### 🔹 **3. Tree-Based Ensemble Models**

These use decision trees with ensemble methods.

|Term|What it is|Key Idea|
|---|---|---|
|**Random Forest**|Algorithm (based on bagging)|Many decision trees trained on random subsets of data & features; results are averaged.|
|**Boosted Decision Trees**|Concept/Method|Decision trees as weak learners in a boosting setup. Multiple versions exist.|

---

### 🔹 **4. Boosting Algorithms**

These are specific implementations of boosting.

|Term|What it is|Key Idea|
|---|---|---|
|**AdaBoost**|Algorithm|Adjusts weights of samples after each weak learner; focuses more on wrongly predicted ones.|
|**Gradient Boosting**|Algorithm|Uses gradient descent to minimize the loss function; each new tree fits the residual errors.|
|**XGBoost**|Library/Algorithm|Optimized, regularized version of gradient boosting; fast, scalable, and widely used.|

---

### 🔹 **5. Miscellaneous**

|Term|What it is|Key Idea|
|---|---|---|
|**Trimming**|Concept (rare)|In ensemble context, sometimes refers to removing worst-performing models or outliers. Not a core ML method.|

---

### 🔄 **Overlaps & Relations**

- **Boosting** = General concept.
    
    - **AdaBoost**, **Gradient Boosting**, and **XGBoost** are all algorithms that implement boosting.
        
- **Boosted Decision Trees** = Trees used in any of the boosting algorithms.
    
- **Random Forest** = Bagging + Decision Trees.
    
- **Weak Learner** = The building block used in boosting and bagging (often a small tree).
    
- **XGBoost** ⊂ Gradient Boosting ⊂ Boosting.
    

---

### 🔍 Summary Table

|Term|Concept|Method|Algorithm|Uses Trees|Part of Boosting|Part of Bagging|
|---|---|---|---|---|---|---|
|Weak Learner|✅|||Often|✅|✅|
|Bagging||✅||✅ (RF)||✅|
|Boosting||✅||✅|✅||
|Random Forest|||✅|✅||✅|
|AdaBoost|||✅|✅|✅||
|Gradient Boosting|||✅|✅|✅||
|XGBoost|||✅|✅|✅||
|Boosted Decision Trees||✅||✅|✅||
|Trimming|✅|||❌|Rare|Rare|


----


# Notes on focussing:

This is a very common challenge when writing a thesis! It's easy to get overwhelmed by the sheer volume of information. Here's a comprehensive approach to help you efficiently manage your sources and craft a compelling thesis:

## I. Strategic Source Management: Prioritizing and Filtering

Before you even start writing, you need a system to evaluate and categorize your sources.

1. **The "Thesis Relevance" Matrix:**
    
    - **High Relevance, High Quality:** These are your core sources. They directly support your arguments, offer significant insights, and are from reputable, peer-reviewed publications. Read these thoroughly and extract key information.
    - **High Relevance, Moderate Quality:** These sources might be slightly less rigorous but still offer valuable data or perspectives directly related to your thesis. Skim for specific points, but prioritize your high-quality sources.
    - **General Background, High Quality:** These sources provide context, foundational theories, or broader understanding of your field.1 They're good for setting the stage in your introduction or literature review but might not need detailed inclusion in every chapter. Read selectively for overarching concepts.
        
    - **Low Relevance/Quality:** These sources are likely distractions. Unless you find a very specific, undeniable nugget of information, set them aside. Don't feel obligated to include everything you've read.
2. **The "Table of Contents" Filter:**
    
    - Before diving deep into any source, look at your thesis outline or tentative table of contents.
    - Ask yourself: "Where would this information _specifically_ fit in my thesis?" If you can't immediately identify a clear home for it, it might be less essential. This forces you to think about the _purpose_ of each piece of information.
3. **Active Reading with a Purpose:**
    
    - **Don't just read passively.** As you go through a source, have specific questions in mind related to your thesis.
    - **Highlight/Annotate Strategically:** Focus on:
        - Key arguments and findings
        - Methods if relevant to your discussion
        - Definitions of crucial terms
        - Direct quotes you _might_ use (but be selective)
        - Gaps in research identified by the authors (these might lead to your own research questions)
    - **Summarize Immediately:** After reading a section or an entire article, quickly summarize the main points in your own words. This aids comprehension and retention, and helps you identify the core takeaway.
4. **Reference Management Software (e.g., Zotero, Mendeley, EndNote):**
    
    - This is non-negotiable for thesis writing.
    - **Organize:** Tag sources by theme, chapter, or relevance level.
    - **Annotate:** Most software allows you to add notes directly to PDFs or source entries.
    - **Cite while you write:** Seamlessly insert citations and generate bibliographies. This saves immense time and reduces errors.

## II. Productive and Efficient Approaches to Writing

Once you have a handle on your sources, focus on efficient writing strategies.

1. **Start with Your Core Argument/Hypothesis:**
    
    - Every paragraph, every sentence, should ideally serve to prove, explain, or contextualize your central thesis. If it doesn't, question its inclusion.
    - Write a clear, concise thesis statement early on and keep it in mind as you write.
2. **Outline, Outline, Outline!**
    
    - A detailed outline is your roadmap. It helps you see the logical flow of your arguments and identifies where specific information needs to go.
    - Break down chapters into sections, and sections into sub-sections.
    - For each section, briefly note down the main point you want to make and which sources will support it.
3. **"Chunking" and Focused Work Sessions:**
    
    - Instead of thinking about the entire thesis, focus on one chapter, then one section, then one paragraph at a time.
    - **Pomodoro Technique:** Work for 25 minutes, then take a 5-minute break.2 Repeat. This helps maintain focus and prevents burnout.
        
    - **Dedicated Writing Time:** Schedule specific blocks of time for writing and protect them from distractions.
4. **Write Badly First (The "Ugly First Draft"):**
    
    - Don't aim for perfection in your first draft. Just get your ideas down. The goal is to get words on the page, even if they're clunky or disorganized.
    - Trying to perfect every sentence as you write leads to writer's block and inefficiency. Editing comes later.
5. **Separate Writing and Editing:**
    
    - When you're writing, focus solely on conveying your ideas.
    - When you're editing, focus on clarity, coherence, grammar, style, and flow. These are different cognitive tasks.
6. **Leverage Your Literature Review:**
    
    - Your literature review isn't just a summary; it's an argument. Identify gaps in existing research, synthesize different perspectives, and show how your work builds upon or challenges previous findings. This sets the stage for your own contribution.

## III. Communicating Well While Retaining Detail

This is the delicate balance: providing sufficient detail without overwhelming the reader.

1. **Clarity and Conciseness are Key:**
    
    - **Every word counts.** Eliminate jargon where simpler terms suffice.
    - **Avoid redundancy.** If you've made a point, don't re-state it unless for emphasis in a new context.
    - **Active Voice:** Generally, active voice is more direct and engaging. ("The study found..." vs. "It was found by the study...")
2. **Strategic Use of Summaries and Overviews:**
    
    - **Introductions to Chapters/Sections:** Start with a brief overview of what you will discuss in that section. This sets expectations.
    - **Concluding Paragraphs:** Summarize the main takeaways from a section before moving to the next.
3. **"Top-Down" Writing (General to Specific):**
    
    - Start with the main point or argument of a paragraph or section.
    - Then, provide the supporting details, evidence, and examples from your sources.
    - Conclude by linking back to your main point or transitioning to the next idea. This structure keeps the reader oriented.
4. **Integrate Sources Seamlessly:**
    
    - **Don't just drop quotes.** Introduce them, explain their relevance, and discuss their implications.
    - **Paraphrase and Synthesize:** Most of your source material should be paraphrased in your own words, demonstrating your understanding. Only use direct quotes when the original phrasing is particularly impactful or essential.
    - **Attribute Clearly:** Always give credit to your sources.
5. **Balance Breadth and Depth:**
    
    - **Breadth (General):** In your introduction and literature review, you might provide a broader overview of the field.
    - **Depth (Specific):** In your methodology, results, and discussion chapters, you'll delve into precise details relevant to your own research.
    - **Ask yourself:** "Is this detail essential for the reader to understand my argument, or is it merely interesting?" If it's the latter, consider if it truly belongs.
6. **Use Visuals (Tables, Figures, Graphs):**
    
    - Complex data, comparisons, or processes can often be communicated more effectively through visuals than through dense text.3
        
    - Ensure all visuals are clearly labeled, have concise captions, and are referenced in the text.
7. **Paragraph Structure:**
    
    - Each paragraph should ideally have one main idea (topic sentence).
    - The subsequent sentences should develop, explain, and support that idea with evidence from your sources.
    - Ensure smooth transitions between paragraphs to maintain flow.
8. **Get Feedback:**
    
    - Share drafts with your supervisor, peers, or trusted readers. They can offer an objective perspective on what's clear, what's confusing, and what needs more detail or less.
    - Specifically ask them: "Are there any points where I lose the thread?" or "Is there too much/too little detail here?"

By applying these strategies, you'll move from feeling overwhelmed by sources to confidently constructing a well-structured, clear, and detailed thesis that effectively communicates your research. Good luck!

---

# Use cases of BDTs:
Boosted Decision Trees (BDTs) have been a staple in high-energy physics (HEP) and astroparticle physics for many years, providing powerful classification capabilities to distinguish rare signal events from overwhelming backgrounds.1 Here are some key areas where they have been implemented to good use, along with relevant references:

## High Energy Physics (HEP)

BDTs have been widely used at accelerator experiments, particularly at the Large Hadron Collider (LHC), for various tasks:2

### 1. Higgs Boson Discovery and Characterization

One of the most prominent successes of BDTs in HEP is their contribution to the discovery and study of the Higgs boson at the LHC.3

- **H → b$\overline{\text{b}}$ decay channel:** The Higgs boson's most frequent decay mode is to a bottom-antibottom quark pair (H→bb). This channel is notoriously difficult to observe due to the immense background from multijet production. BDTs played a crucial role in separating the faint Higgs signal from this background, enabling its observation.
    - **Reference:** The ATLAS and CMS collaborations have used BDTs extensively in their analyses.4 While a single paper can't be cited for "the" discovery, their publications on the H→bb channel prominently feature BDTs. For example, see the ATLAS update "Higgs boson observed decaying to b quarks – at last!" (July 2018), which specifically mentions the use of a classic BDT architecture for classification.
        

### 2. Top Quark Physics

BDTs are essential for studying the top quark, the heaviest known fundamental particle, and for searches for physics beyond the Standard Model involving top quarks.

- **Single top quark production:** Experiments like CDF and D0 at the Tevatron, and later ATLAS and CMS at the LHC, used BDTs to isolate single top quark production from large backgrounds, enabling precise measurements of its properties.5
    
    - **Reference:** Early uses can be found in publications from CDF and D0 collaborations on single top quark production (e.g., D0:2008wma, CDF:2010eor).6 More recent applications at the LHC continue this trend.
        
- **Exotic top quark decays or production:** BDTs are used to search for new physics processes where top quarks are involved, such as those that might violate lepton flavor conservation.
    - **Reference:** The CMS experiment's news article "Does the top quark respect all the leptons equally?" (CMS Experiment, 2023) highlights the use of BDTs to distinguish unusual events with lepton flavor violation from standard top quark behavior.

### 3. Particle Identification (PID) and Event Classification

BDTs are widely used for general particle identification and classification of events as signal or background across various decay channels and new physics searches.7

- **Neutrino experiments:** Experiments like MiniBooNE at Fermilab have successfully applied BDTs for particle identification, such as distinguishing electrons from photons, and for optimizing signal selection in neutrino oscillation searches.8
    
    - **Reference:** "Boosted Decision Trees, a Powerful Event Classifier" (MiniBooNE experiment, 2005) discusses the application of BDTs for particle identification in MiniBooNE.
- **Searches for Beyond Standard Model (BSM) physics:** Many searches for new particles or phenomena at the LHC, such as supersymmetric particles (sparticles) or dark matter candidates, heavily rely on BDTs to enhance sensitivity by separating subtle signal signatures from overwhelming Standard Model backgrounds.9
    
    - **Reference:** Recent arXiv preprints like "Machine Learning Techniques for Intermediate Mass Gap Lepton Partner Searches at the Large Hadron Collider" (arXiv:2309.10197v2) and "Searches for the BSM scenarios at the LHC using decision tree based machine learning algorithms: A comparative study and review of Random Forest, Adaboost, XGboost and LightGBM frameworks"10 (arXiv:2405.06040v1) showcase ongoing applications in BSM searches at the LHC.

### 4. Trigger Systems

BDTs are even being explored for real-time applications in detector trigger systems to quickly identify and select events of interest, especially at the high luminosity LHC (HL-LHC).

- **Reference:** "Nanosecond machine learning with BDT for high energy physics" (CERN Indico, 2021) discusses novel implementations of BDTs on FPGAs for low-latency trigger decisions.11
    

## Astroparticle Physics

In astroparticle physics, BDTs are used for classifying astrophysical objects, distinguishing between different types of cosmic events, and rejecting background.12

### 1. Gamma-ray Astronomy (e.g., Fermi-LAT)

- **Classification of unassociated gamma-ray sources:** The Fermi Large Area Telescope (Fermi-LAT) detects thousands of gamma-ray sources, many of which lack clear associations with known astrophysical objects. BDTs have been used to classify these unassociated sources into categories like active galactic nuclei (AGNs) or pulsars based on their observed properties.
    - **Reference:** "Classifications of Fermi-LAT unassociated sources in multiple machine learning methods" (Oxford Academic, 2023) and "Optimizing neural network techniques in classifying Fermi-LAT gamma-ray sources" (Oxford Academic, 2019) discuss the use of BDTs (and other ML techniques) for this purpose.

### 2. Neutrino Astronomy (e.g., IceCube)

- **Astrophysical neutrino searches:** In neutrino telescopes like IceCube, distinguishing astrophysical neutrinos from the much more numerous atmospheric neutrinos and muons is a critical task.13 BDTs are often employed to achieve this separation by exploiting differences in event characteristics.14
    
    - **Reference:** While specific papers directly detailing BDTs for astrophysical neutrino _identification_ in IceCube might be embedded within broader analysis publications, the principle of using multivariate classifiers for background rejection is well-established. For example, "Multi-Messenger correlation study of Fermi-LAT blazars and high-energy neutrinos observed in IceCube" (2015, TUM) describes analysis aiming to identify cosmic neutrino sources.

### 3. Cosmic Ray Physics

- **Cosmic ray composition and origin studies:** BDTs can be used to distinguish between different types of cosmic ray primaries (e.g., protons, helium, heavier nuclei) or to identify rare cosmic ray events that could point to new physics.15
    

### 4. Dark Matter Searches

- **Background rejection in direct dark matter detection:** In experiments searching for direct interactions of dark matter particles with ordinary matter, background events (e.g., from cosmic rays or natural radioactivity) must be meticulously rejected.16 BDTs can be used to improve the signal-to-background ratio by learning the features that differentiate signal-like events from background.
    
    - **Reference:** The NEON experiment, searching for light dark matter, used BDTs to mitigate PMT-induced noise events, as described in "First Direct Search for Light Dark Matter Using the NEON Experiment at a Nuclear Reactor" (Phys. Rev. Lett., 2025). The CMS experiment also uses BDTs in its searches for dark matter, as mentioned in "Dark matter and pencil jets: The search for a low-mass Z' boson using machine learning" (CMS Experiment, 2025).17
        

BDTs remain a powerful and interpretable machine learning tool in high-energy and astroparticle physics, often complementing or being used in conjunction with more complex deep learning techniques.18 Their robustness and relatively straightforward interpretability make them a valuable asset in these fields.

----


# Toy experiments recipe:
#recipe #workflow #toys
Okay, here's a simple, short recipe-like workflow for how toy experiments are performed:

- 1. Prepare the Master Blueprint (The model):
    
    pyhf first loads your entire statistical description, which is like a master blueprint. This blueprint knows all about your expected signal and background events in every measurement bin, and how all your uncertainties (systematics) affect these expectations.
    
- 2. Create the "Background-Only" Recipe (bkg_pdf):
    
    pyhf then calculates the most likely scenario for your experiment if there were absolutely no signal present. It does this by setting the signal strength to zero and finding the "best fit" values for all the uncertainty parameters using your expected (MC) background data. This creates a specific, fixed "background-only recipe" for your experiment's expected results.
    
- 3. Generate a Single "Toy Data" Observation:
    
    From this fixed "background-only recipe" (bkg_pdf), pyhf randomly generates a new set of numbers for all your measurement bins. For each bin, it draws a count from a Poisson distribution centered around the expected background for that bin. This random set of counts is one simulated "toy experiment," showing what your detector might have seen purely due to random chance if only background was there.
    
- 4. Evaluate the "Toy Data":
    
    Your code then takes this generated "toy data" and calculates a statistical value (like q0). This value tells you how "unusual" this specific toy data set appears when compared to the pure background expectation.
    
- 5. Repeat for Many "Toys":
    
    Steps 3 and 4 are repeated many thousands or millions of times. For each repetition, a new set of random numbers is generated, leading to a new "toy data" set and a new statistical value. The seed is used to ensure these random numbers are independent for each toy and reproducible if you run the whole process again.
    
- 6. Build the Reference Chart:
    
    All these calculated statistical values from the many toy experiments are collected into a single chart (a histogram). This chart shows you the typical range and likelihood of seeing various statistical values if the experiment were truly seeing only background.
    
- 7. Compare to Real Observation (Implied):
    
    (This happens outside the given code, but it's the final goal.) You will then take the statistical value calculated from your actual collected data and compare it to this reference chart. If your real data's value is extremely rare in the "background-only" chart, it's strong evidence that something beyond just background (like a new signal) might be present.


Here is the distilled-down, direct workflow for toy experiments, as a terse recipe:

    Load the statistical model, which defines the likelihood function including signal strength and nuisance parameters.
    Fit this model to the expected background-only data (setting signal strength to zero) to determine the best-fit values for all nuisance parameters under that assumption.
    Create a specific background-only probability distribution function (PDF) using these determined best-fit parameter values.
    For each of the desired number of toy experiments:
        Generate a new synthetic "toy data" set by randomly drawing event counts (using Poisson statistics) from this background-only PDF for each bin.
        Calculate the chosen test statistic (e.g., q0) using this generated "toy data" set.
    Collect all the calculated test statistics to form their distribution.
    (This distribution is then used to evaluate the test statistic from your actual observed data).

----

Here I will dump physics stuffs. EFT or BSM

-   "Leading order" refers to the highest-order term in a perturbative expansion of a given quantity. In the context of Feynman diagrams, the leading order diagram is the one that involves the fewest number of loops. Loops represent quantum corrections to the classical interaction, and therefore diagrams with fewer loops are considered to be more accurate approximations of the actual physics.
    
-   "Tree level" diagrams are Feynman diagrams that contain no loops. They represent the classical, or tree-level, interaction between particles. The term "tree" comes from the fact that the diagram looks like a branching tree with particles as the branches.
    
-   "Born level" is another term used to describe tree-level diagrams, but specifically for particle scattering processes. In particular, the Born approximation is the leading term in a series expansion of the scattering amplitude, which is the probability of two particles scattering off each other. The Born level diagram, therefore, represents the lowest-order approximation of the scattering process.

In quantum field theory calculations, the perturbative expansion is usually carried out in powers of a small parameter, typically the coupling constant of the theory. The leading order (LO) term represents the contribution from the lowest power of this small parameter, while the next-to-leading order (NLO) term represents the contribution from the next power.

The LO term provides a good approximation to the physical process being studied, but it is not always accurate enough for precision measurements. In order to improve the accuracy of the calculation, one needs to include higher-order corrections, which correspond to diagrams with more loops and higher powers of the coupling constant.

The convergence of the perturbative expansion depends on the value of the coupling constant and the energy scale of the process being studied. At low energies, the coupling constant is typically small, and the perturbative expansion converges well. However, at higher energies, the coupling constant becomes larger, and the higher-order corrections become more important.

To account for these higher-order corrections, one can calculate the NLO contribution to the process being studied. The NLO term includes contributions from both LO and NLO diagrams, and it can significantly improve the accuracy of the calculation. However, the NLO term is typically more difficult to calculate than the LO term, as it involves more complicated diagrams and integrals.

Bias :
There are several types of bias that can occur in an experiment:

1.  Selection bias: This occurs when the sample chosen for the experiment is not representative of the population being studied. This can happen if the sample is chosen non-randomly or if certain groups are excluded from the study.
    
2.  Measurement bias: This occurs when the instruments or procedures used to make the measurements are inaccurate or imprecise, leading to a consistent over- or underestimation of the true value.
    
3.  Observer bias: This occurs when the researchers or observers involved in the experiment have preconceived ideas or expectations that influence the interpretation of the results.
    
4.  Confounding bias: This occurs when there is a variable that affects both the independent variable being studied and the outcome of interest, leading to a distorted or incorrect relationship between them.
    
5.  Reporting bias: This occurs when the results of the study are selectively reported, either by the researchers or by the media, in a way that distorts the true findings.
    

To minimize bias in an experiment, it is important to carefully design the study and control for potential sources of bias. This can involve using random sampling methods, blinding the observers or participants to the conditions of the study, using standardized and calibrated instruments, and reporting all results, regardless of whether they support the initial hypothesis or not.


----

# SM Lagrangian:
Absolutely, I'll rewrite the mathematical expressions with the Greek characters also enclosed in `$$` for proper Markdown formatting:

---

## Different Terms in the Standard Model Lagrangian

### 1. Gauge Field Terms

- **Electromagnetic Force (QED Lagrangian)**: 
  $$ \mathcal{L}_{\text{QED}} = -\frac{1}{4} F_{\mu\nu}F^{\mu\nu} $$
  where $$ F_{\mu\nu} $$ is the electromagnetic field strength tensor.

- **Weak Nuclear Force**: Part of the electroweak theory, includes the \( W \) and \( Z \) bosons.

- **Strong Nuclear Force (QCD Lagrangian)**: 
  $$ \mathcal{L}_{\text{QCD}} = -\frac{1}{4} G_{\mu\nu}^a G^{\mu\nu}_a $$
  where $$ G_{\mu\nu}^a $$ is the gluon field strength tensor.

### 2. Matter Field Terms (Fermions)

- **Leptons and Quarks**:
  $$ \mathcal{L}_{\text{fermions}} = \bar{\psi}(i\gamma^\mu D_\mu - m)\psi $$
  where $$ \psi $$ are the fermion fields, $$ \gamma^\mu $$ are the gamma matrices, $$ D_\mu $$ is the covariant derivative, and $$ m $$ is the mass term.

### 3. Higgs Field Term

- **Higgs Mechanism**:
  $$ \mathcal{L}_{\text{Higgs}} = |D_\mu \Phi|^2 - V(\Phi) $$
  where $$ \Phi $$ is the Higgs field, $$ D_\mu $$ is the covariant derivative, and $$ V(\Phi) $$ is the Higgs potential.

### 4. Yukawa Interactions

- **Mass Generation for Fermions**:
  $$ \mathcal{L}_{\text{Yukawa}} = -\sum_{\text{fermions}} y_f (\bar{\psi}_L \Phi \psi_R + \bar{\psi}_R \Phi^\dagger \psi_L) $$
  where $$ y_f $$ are Yukawa coupling constants, and $$ \psi_L, \psi_R $$ are the left-handed and right-handed components of the fermion fields.

---

Each term in the Standard Model Lagrangian is essential for describing the interactions and properties of fundamental particles and forces, except for gravity. This Lagrangian is a cornerstone of modern particle physics.

----



## Yukawa coupling  and other SM interactions :
The Yukawa coupling is a coupling constant that describes the strength of the interaction between a fermion and the Higgs field. It's represented by the symbol "y" in equations. Specifically, it determines how strongly a fermion field couples to the Higgs field and, consequently, how much mass the fermion acquires through this interaction.
Yukawa couplings describe the interaction between fermions (quarks and leptons) and the Higgs field. They determine how strongly these particles couple to the Higgs field, leading to mass generation.
he Yukawa coupling is considered a fundamental aspect of the Standard Model of particle physics, which is the prevailing theoretical framework describing the behavior of fundamental particles and their interactions. It's not a consequence of something more fundamental within the Standard Model; instead, it's one of the building blocks of the theory.

In the Standard Model, particles acquire mass through their interactions with the Higgs field, and the strength of these interactions is quantified by Yukawa coupling constants. These coupling constants are fundamental parameters of the theory, and they are determined experimentally for different types of particles, such as quarks and leptons.

- **Gauge Interactions:** These are associated with the exchange of gauge bosons, which are particles responsible for mediating the fundamental forces. There are three types of gauge interactions in the Standard Model:
    
    - Electromagnetic Interaction: Described by the electromagnetic coupling constant, denoted as "α" (alpha).
    - Weak Interaction: Described by the weak mixing angle (θw) and the weak coupling constants for charged (g_w+) and neutral (g_w) weak interactions.
    - Strong Interaction (Quantum Chromodynamics, QCD): Described by the strong coupling constant, denoted as "αs" (alpha_s).
- - **Higgs Interaction:** This interaction is associated with the self-interaction of the Higgs field itself. It plays a role in the dynamics of the Higgs field and the Higgs boson.
### Rise of bosons from fields:
Here's a simplified explanation of how a field gives rise to a boson:

1. **Field Concept:** In quantum field theory, fields are pervasive throughout space and time. These fields can be scalar fields (like the Higgs field), vector fields (like the electromagnetic field), or more complex fields, depending on the type of particle or force being described.
    
2. **Quantization:** When you quantize a field, you essentially divide it into tiny discrete units or quanta. Each of these quanta is associated with a particle. For example, in the case of the electromagnetic field, the quanta are called photons, which are massless bosons.
    
3. **Bosons:** Bosons are a type of particle that obeys Bose-Einstein statistics, which allow multiple bosons to occupy the same quantum state simultaneously. This is in contrast to fermions, which obey Fermi-Dirac statistics and have the Pauli exclusion principle, preventing multiple fermions from occupying the same quantum state.
    
4. **Higgs Mechanism:** In the case of the Higgs field, which is a scalar field, the quantization process leads to the emergence of a boson called the Higgs boson. The Higgs boson is the particle associated with the Higgs field. The Higgs mechanism is responsible for giving mass to other particles in the Standard Model, as we discussed earlier. The interaction between particles with spin (fermions) and the Higgs field involves the exchange of Higgs bosons.

## CP violating couplings
CP-violating anomalous couplings refer to interactions between particles that violate both the symmetries of charge conjugation (C) and parity (P) conservation, and involve deviations from the expected behavior of particles predicted by the Standard Model of particle physics.

In the Standard Model, particles and their interactions are described by quantum field theory, and the theory predicts the strengths of various interactions between particles, including their coupling strengths. The couplings between particles can be represented by coupling constants, which are typically assumed to be constants that do not vary with energy or other parameters.

However, in some extensions of the Standard Model, such as in theories that include extra dimensions or new particles, anomalous couplings can arise. These anomalous couplings can result in deviations from the expected behavior of particles and interactions, and can lead to CP violation, where the laws of physics appear to behave differently for particles and their antiparticles.

Anomalous couplings can be studied experimentally by colliding particles at high energies and observing the resulting interactions. By carefully measuring the properties of the final state particles, such as their energies, momenta, and spin, physicists can infer the presence and strength of anomalous couplings. These measurements can help test the predictions of the Standard Model and search for evidence of new physics beyond it.

![](/images/notes/Pasted image 20230401220511.png)

SUSY can solve mass hierarchy problem.
![](/images/notes/Pasted image 20230401220831.png)



GIM mechanism  and Interference :

Interference occurs when two or more Feynman diagrams contribute to the same final state of a particle interaction. The probability amplitude for the overall process is obtained by summing the probability amplitudes of each individual Feynman diagram.

Interference can be constructive or destructive, depending on the relative phases of the probability amplitudes. Constructive interference occurs when the probability amplitudes have the same phase and reinforce each other, leading to an enhanced overall amplitude. Destructive interference, on the other hand, occurs when the probability amplitudes have opposite phases and tend to cancel each other out, resulting in a reduced overall amplitude.

In the context of the GIM mechanism, interference refers to the interference between different quark mixing pathways or Feynman diagrams involving the charm quark. These pathways represent different possibilities for the flavor-changing transition to occur. The interference arises because the charm quark can propagate through multiple pathways, contributing to the overall amplitude.

By considering the interference effects between the different pathways, we can observe cancellations or enhancements in the overall probability amplitude for the flavor-changing process. In the case of the GIM mechanism, the destructive interference between specific mixing pathways involving the charm quark leads to a suppression of Flavor Changing Neutral Current (FCNC) processes. The interference effects depend on the masses and couplings of the particles involved in the processes.

The GIM mechanism introduces the charm quark as an additional quark to cancel out unwanted FCNC effects. The charm quark's mass is indeed lighter than the W boson mass, but that is not the primary reason for its inclusion in the mechanism.

The interference between different quark mixing pathways, involving both the charm quark and the W boson exchange, is what leads to the suppression of FCNC processes. The interference effects depend on the masses and couplings of the particles involved, as well as the relative phases of the probability amplitudes associated with the different pathways.

The charm quark plays a crucial role in the GIM mechanism because its presence introduces additional pathways that interfere with the direct FCNC transitions mediated by the W boson. Through interference, these pathways contribute in a way that cancels out the FCNC effects, leading to the suppression of FCNC processes.

![](/images/notes/Pasted image 20230620135716.png)

Buffer !

So FCNC is rare because :
1. GIM Mechanism: The Glashow-Iliopoulos-Maiani (GIM) mechanism, as we discussed earlier, plays a crucial role in suppressing FCNC processes. The interference effects between different quark mixing pathways, mediated by the GIM mechanism, lead to a cancellation or significant reduction of FCNC amplitudes.
    
2. Small Mixing Angles: The CKM matrix, which governs quark flavor mixing, contains small mixing angles. These angles represent the relative strengths of flavor-changing transitions. The small values of these mixing angles contribute to the suppression of FCNC processes, making them relatively rare compared to other interactions.
    
3. Loop Suppression: FCNC processes typically involve loop diagrams, which involve virtual particles running in loops. Loop processes are generally less likely to occur compared to tree-level processes due to the additional suppression factor associated with loop diagrams.
    
4. Weak Interaction Strength: The weak interaction itself is relatively weak compared to electromagnetic and strong interactions. This inherent weakness of the weak interaction contributes to the rarity of FCNC processes.



<mark style="background: #FFF3A3A6;">**While off-shell particles, which are virtual particles that can temporarily violate the mass-energy relation, can appear in intermediate states of Feynman diagrams, they still obey energy-momentum conservation laws when summed over all possible intermediate states.**
</mark>


### How are they all related after all?
1. Flavor Changing Neutral Current (FCNC): FCNC refers to processes in particle physics where a quark changes its flavor (type) without changing its electric charge. FCNC processes are highly suppressed in the Standard Model due to the Glashow-Iliopoulos-Maiani (GIM) mechanism.
    
2. Charged Lepton Flavor Violation (CLFV): CLFV refers to processes in which charged leptons (such as electrons or muons) change their flavor, violating the conservation of lepton flavor. CLFV is not allowed in the Standard Model but can occur in some theories beyond it.
    
3. GIM Mechanism: The GIM mechanism is a theoretical framework developed by Glashow, Iliopoulos, and Maiani. It introduces additional quark mixing pathways involving the charm quark to cancel out unwanted FCNC effects. The GIM mechanism achieves this through interference effects between different quark mixing pathways.
    
4. Charm Quark: The charm quark is the third lightest quark in the Standard Model, denoted as c. It plays a crucial role in the GIM mechanism by introducing additional quark mixing pathways that interfere with FCNC transitions. The presence of the charm quark helps suppress FCNC processes and ensures agreement with experimental observations.
    
5. Mass Suppression: Mass suppression refers to the reduction or suppression of FCNC processes due to interference effects between different quark mixing pathways. In the GIM mechanism, destructive interference between specific pathways involving the charm quark cancels out or reduces the contributions of FCNC processes, leading to their suppression.
    

These topics are interconnected, as the GIM mechanism, charm quark, and interference effects are all relevant to understanding and suppressing FCNC processes in particle physics. Additionally, CLFV processes, which involve violations of lepton flavor conservation, provide valuable insights into physics beyond the Standard Model.


CP violation is a phenomenon in particle physics where the laws of physics are not invariant under the combined operations of charge conjugation (C, which changes particles into their corresponding antiparticles) and parity transformation (P, which flips the spatial coordinates). Observations of CP violation indicate that the laws of nature distinguish between matter and antimatter, and this has profound implications for understanding the asymmetry between matter and antimatter in the universe.

One of the most compelling evidences of CP violation comes from the study of decays of B mesons, which are hadrons containing a bottom (or b) quark. The B factories, such as the experiments conducted at Belle (KEKB collider in Japan) and BaBar (PEP-II collider at SLAC in the US), were specifically designed to study CP violation in B meson systems. A classic example of CP violation is observed in the decay of neutral B mesons (\(B^0\) and \(\bar{B}^0\)).

### Example of CP Violation in B Meson Decays:

A well-studied process that exhibits CP violation involves the decay of \(B^0\) and \(\bar{B}^0\) mesons into a pair of charged pions (\(\pi^+\) and \(\pi^-\)). The \(B^0\) meson contains a bottom quark (\(b\)) and a down antiquark (\(\bar{d}\)), while its antiparticle, \(\bar{B}^0\), contains a bottom antiquark (\(\bar{b}\)) and a down quark (\(d\)).

The decay can proceed through several paths, including direct decay or decay after mixing. Mixing occurs when a \(B^0\) meson oscillates into its antiparticle \(\bar{B}^0\) before decaying, or vice versa. This mixing is a quantum mechanical effect unique to neutral mesons.

1. **Direct Decay**: 
   - $$\(B^0 \to \pi^+ \pi^-\)$$
   - $$\(\bar{B}^0 \to \pi^+ \pi^-\)$$

2. **Decay After Mixing**:
   - $$\(B^0 \to \bar{B}^0 \to \pi^+ \pi^-\)$$
   - $$\(\bar{B}^0 \to B^0 \to \pi^+ \pi^-\)$$

CP violation manifests as a difference in the rate of these processes for \(B^0\) and \(\bar{B}^0\), measured experimentally by comparing the number of \(B^0\) mesons decaying into \(\pi^+ \pi^-\) to the number of \(\bar{B}^0\) mesons decaying into the same final state. If CP symmetry were conserved, these rates would be identical. However, experiments have observed a difference, indicating CP violation.

### The Importance of the CP Violation Measurement:

The measurement of CP violation in B meson decays, particularly in processes like the one described, has been a critical test of the Standard Model of particle physics. The phenomenon of CP violation is incorporated into the Standard Model through the complex phase in the CKM (Cabibbo-Kobayashi-Maskawa) matrix, which describes quark mixing. The observations of CP violation in B meson decays have been in agreement with the predictions of the Standard Model, providing a powerful confirmation of its validity.

Furthermore, the study of CP violation helps to address one of the fundamental questions in cosmology: why the universe is composed predominantly of matter rather than an equal mixture of matter and antimatter. CP violation is a necessary condition for generating the matter-antimatter asymmetry in the early universe, according to the criteria outlined by Andrei Sakharov in 1967. However, the degree of CP violation observed in particle physics experiments to date is not sufficient to explain the current matter-antimatter asymmetry, suggesting that additional sources of CP violation may exist beyond the Standard Model.


The weak mixing angle, often denoted as \(\sin^2 \theta_W\), is a fundamental parameter in the Standard Model of particle physics that describes the mixing of the electromagnetic and weak forces. Here's how it's measured and its relation to parity violation:

## Measurement of the Weak Mixing Angle

#### Methods of Measurement
1. **Deep Inelastic Scattering**: Experiments like those at the SLAC (Stanford Linear Accelerator Center) involve scattering high-energy electrons off protons or neutrons. The differential cross-sections for neutral current interactions provide information about \(\sin^2 \theta_W\).
   
2. **Z Boson Properties**: Precision measurements at particle colliders, such as the LEP (Large Electron-Positron Collider) at CERN, where the properties of the Z boson (mass, width, and decay modes) are studied. The ratio of neutral current to charged current processes also gives \(\sin^2 \theta_W\).

3. **Parity-Violating Electron Scattering**: Experiments like the P2 experiment at JGU Mainz measure parity-violating asymmetries in electron scattering. The weak mixing angle can be extracted from the degree of parity violation observed.

4. **Atomic Parity Violation (APV)**: Precision measurements of parity-violating effects in atoms, where the interaction of electrons with the nucleus is affected by the weak force, also contribute to determining \(\sin^2 \theta_W\).

### Relation to Parity Violation

#### Parity Violation in the Weak Interaction
- **Weak Force and Parity**: The weak force is unique among the fundamental forces because it violates parity (P) symmetry, meaning it distinguishes between left-handed and right-handed coordinate systems.
  
- **Neutral Current Interactions**: Parity violation in neutral current interactions (mediated by the Z boson) provides a way to measure the weak mixing angle. The degree of parity violation observed in these processes is directly related to the value of \(\sin^2 \theta_W\).

#### Parity-Violating Asymmetry
- **Asymmetry Measurement**: In parity-violating electron scattering experiments, the asymmetry \(A_{PV}\) is measured, which is the difference in cross-sections for left-handed versus right-handed polarized electron beams.
  \[
  A_{PV} = \frac{\sigma_L - \sigma_R}{\sigma_L + \sigma_R}
  \]
  where \(\sigma_L\) and \(\sigma_R\) are the cross-sections for left-handed and right-handed electrons, respectively.

- **Dependence on \(\sin^2 \theta_W\)**: The parity-violating asymmetry is sensitive to the weak mixing angle, and precise measurements of \(A_{PV}\) allow for an accurate determination of \(\sin^2 \theta_W\).

### Example: P2 Experiment
- **Objective**: The P2 experiment aims to measure the weak mixing angle by examining parity-violating asymmetries in electron-electron (Møller) scattering.
  
- **Procedure**: Longitudinally polarized electrons are scattered off unpolarized electrons, and the parity-violating asymmetry in the scattering cross-section is measured. The degree of asymmetry provides a direct measurement of \(\sin^2 \theta_W\).

### Summary
- **Weak Mixing Angle**: A crucial parameter in the Standard Model, describing the mixing of the electromagnetic and weak forces.
- **Parity Violation**: The weak force's violation of parity symmetry allows for precise measurements of \(\sin^2 \theta_W\) through various experimental methods.
- **Experimental Relevance**: Parity-violating electron scattering, such as in the P2 experiment, provides a direct way to measure \(\sin^2 \theta_W\) by observing the asymmetry in scattering cross-sections for different polarizations.

These measurements are essential for testing the Standard Model and searching for possible signs of new physics beyond the Standard Model.


Detector 

# Cross sections
In the context of physics, particularly in particle physics experiments, the terms "absolute cross section" and "normalized cross section" refer to different ways of quantifying and presenting experimental measurements.

1. Absolute Cross Section: The absolute cross section represents the likelihood of a specific process or interaction occurring when particles (such as protons or electrons) collide with each other. It is measured in units of area, typically in barns (1 barn = 10^-28 square meters).
    
    Absolute cross section measurements provide the actual probability or rate of a particular interaction occurring, regardless of the experimental conditions or the intensity of the particle beams. These measurements are essential for understanding the underlying physics processes and for comparison with theoretical predictions.
    
2. Normalized Cross Section: The normalized cross section is obtained by dividing the measured cross section by a reference value. The reference value is typically chosen based on certain conditions or assumptions, such as a specific energy range, detector acceptance, or a well-understood process.
    
    Normalized cross section measurements are useful for comparing data across different experiments, colliders, or energy regimes. They help to remove the effects of experimental setup differences and can provide insights into the underlying physical phenomena without being dependent on absolute values.


# Development of PDFs for partons

Parton distribution functions (PDFs) are developed through a combination of theoretical calculations, experimental measurements, and statistical analysis. The construction of PDFs involves a multi-step process that incorporates various data sets and theoretical frameworks. Let's explore the general steps and touch upon the specific cases of NNPDF and CT10/CTEQ PDF sets.

1. Theoretical Framework: PDFs are typically calculated within the framework of Quantum Chromodynamics (QCD), the theory of the strong nuclear force. Perturbative QCD calculations provide the foundation for understanding the dynamics of partons and their interactions.
    
2. Initial Parametrization: An initial parametrization for the PDFs is chosen based on theoretical expectations and insights from previous studies. These parametrizations include functional forms with several free parameters that will be determined through fitting to experimental data.
    
3. Fitting to Data: Experimental data from a wide range of scattering experiments are used to constrain the free parameters of the PDF parametrization. These data sets include deep inelastic scattering, Drell-Yan processes, jet production, and other high-energy scattering processes. The goal is to find the best set of parameters that reproduce the experimental measurements.
    
4. Statistical Analysis: Statistical techniques, such as the method of least squares or maximum likelihood estimation, are employed to determine the best-fit values of the PDF parameters and to estimate the uncertainties associated with them.
    

Now, let's discuss the specific cases of NNPDF and CT10/CTEQ PDF sets:

NNPDF (part of the NNPDF Collaboration): The NNPDF approach uses a neural network methodology to determine the PDFs. Neural networks are trained on a large set of experimental data to directly extract the PDFs without assuming a specific functional form. The neural network framework provides flexibility in capturing complex PDF shapes and allows for a systematic estimation of uncertainties.

CT10/CTEQ (part of the CT Collaboration): The CT10/CTEQ PDF sets are obtained through global fits to experimental data. These fits involve a wide range of data sets and incorporate theoretical calculations within the framework of QCD. The CT10/CTEQ collaborations employ a specific parametrization form and perform iterative fitting procedures to determine the best-fit PDFs and uncertainties.

In both cases, NNPDF and CT10/CTEQ, the construction of PDF sets involves the combination of theoretical calculations, fitting procedures, and statistical analysis. These PDF sets are continuously updated as new data become available, allowing for improved precision and understanding of the proton's internal structure.

https://en.wikipedia.org/wiki/Parton_(particle_physics)#Parton_distribution_functions
https://en.wikipedia.org/wiki/DGLAP_evolution_equations

---
# Bjorken Scaling:
### The Basics:

Deep inelastic scattering experiments involve firing a high-energy lepton (like an electron) at a target proton or neutron. The lepton interacts with the quarks inside the proton or neutron via the exchange of a photon (the force carrier for the electromagnetic force). The goal is to probe the internal structure of the proton or neutron – to "see" the quarks inside.

### The Observation:

When experiments of this nature were conducted, scientists noticed something surprising. When they plotted the cross-section of the scattering as a function of certain variables, they found that the cross-section depended on the energy and momentum transfer but, surprisingly, not on the specific energy of the lepton beam. This energy independence is Bjorken scaling.

### Intuition:

Imagine you're trying to understand the details of a complex machine, like the inner workings of a clock. You could use a magnifying glass (representing low energy) to get a closer look. At low magnifications, you might just see the large gears and components.

However, if you use a microscope (representing high energy), you'll see much finer details, including smaller gears, springs, and perhaps even the texture of the material.

Bjorken scaling is like saying that the pattern or distribution of these details (small gears, springs, etc.) looks remarkably the same, whether you're using a 10x microscope or a 100x microscope. The relative distribution remains consistent.

### Example:

Consider a target proton moving at a very high speed. From the perspective of the incoming lepton, the proton's internal quarks are moving rapidly. As you increase the energy of the lepton beam (akin to increasing the magnification of a microscope), you're probing finer and finer details of the proton's structure.

Bjorken scaling suggests that the distribution of these quarks, when plotted against a certain scaled momentum variable, doesn't change. It's as if, no matter how hard you throw a baseball at a car (with the car representing the proton and the baseball the lepton), the way the baseball bounces off the tires versus the doors versus the windows remains the same. It's quite unexpected!

### Importance:

Bjorken scaling provided the first strong evidence for the parton model of hadrons, where hadrons (like protons and neutrons) are made up of point-like constituents called partons (which we now understand as quarks and gluons). The scaling phenomenon hinted that these partons were not interacting strongly with each other, paving the way for the development of Quantum Chromodynamics (QCD), the theory of the strong force.

---

### Good summary of the analysis process :
[answer](https://physics.stackexchange.com/posts/87218/timeline)

The experiments take many years. Using the Higgs boson search as an example, the reason it takes so long is because there is no "smoking gun" signature of a Higgs boson. You don't search for the Higgs boson directly, but for the Standard Model particles to which the Higgs decays. Since other Standard Model processes (called "backgrounds") can produce these particles, for any given collision at the LHC you cannot be sure that you have seen the Higgs boson. You have to produce thousands of Higgs bosons before you have a large enough statistical sample from which to draw any conclusions. And even then it can be a difficult process of comparing your observed rate of Higgs-like events to the predicted background rate. So finding the Higgs boson is not trivial; it corresponds to the experimental observation of a Higgs-like rate that is slightly larger than the predicted background rate. Since the background rate prediction has its own set of errors and assumptions, and statistical fluctuations are possible, it takes a long time to create enough Higgs bosons, and understand the detector well enough, to be confident that an observed excess of Higgs-like events is real.

---

# To be read: 
https://en.wikipedia.org/wiki/Category:Experimental_particle_physics
---
# Question about SM:

 Could all of the fundamental forces be of equal strength at very high energy, indicating a potential common origin? Could new, unknown interactions be modifying the strong force in certain processes or at certain energies?

---

#measurement

 Measurements and Analysis 


#Glossary
Smirnov transform : Smirnov transform of ee -> yy in MC. Used in yy bkg evaluation usually.
(inverse transform to go from pdf to data).

Observables and the significance (coming from h->yy ppr, ):
![](/images/notes/Pasted image 20231003004914.png)
![](/images/notes/Pasted image 20231003004931.png)
--

 Measurements and Analysis 
Also, for continuum bkg, we have :
"The background in the Higgs boson signal extraction fit is modelled analytically. The
functional form chosen for the background model is based on background templates built
using simulations and data control-regions, and these are also used in the estimation of
related systematic uncertainties. "

---

## Can $\sigma$  reduce with reduced cms $\sqrt{s}$  ?
Cross section is a measure of the likelihood of a specific process occurring when particles collide. The cross section typically depends on several factors, including the center-of-mass energy of the collision (often denoted as √s), the nature of the process, and the properties of the particles involved.

For many Standard Model processes, the cross section generally increases as the center-of-mass energy of the collision (√s) increases. This is because higher collision energies provide more available energy to produce massive particles, which may be involved in the process of interest.

However, there are scenarios where the cross section might decrease as the collision energy decreases, but these situations are relatively less common. Here are a couple of cases where this might occur:

1. **Threshold Effects**: Some particle reactions or decays have energy thresholds, below which they cannot occur. If the center-of-mass energy is reduced to a value below this threshold, the cross section for that particular process effectively drops to zero because there is not enough energy available to create the required particles or conditions.
    
2. **Resonance Behavior**: In certain cases, the cross section can exhibit resonance behavior. A resonance occurs when the energy is close to the mass of a specific particle. Near the resonance energy, the cross section can be significantly enhanced. However, as the energy moves away from the resonance, the cross section can drop rapidly.
    
    - For example, the cross section for producing the Z boson in proton-proton collisions at the Large Hadron Collider (LHC) increases as the collision energy approaches the Z boson's mass (about 91 GeV). At higher energies, the cross section decreases because the collision energy is far above the resonance peak.
        
    - Similarly, in electron-positron colliders, the cross section for producing the ϒ (Upsilon) mesons, which are resonances of the bottom quark-antiquark system, has a maximum at a specific energy that corresponds to the ϒ mass. At higher or lower energies, the cross section decreases.


---

---

## NWA
1. **Decay Width (Γ):** The decay width of a particle is a measure of how quickly it decays into other particles. It quantifies the probability of the particle decaying in a given time interval. Particles with a larger decay width are shorter-lived and tend to decay more quickly, while particles with a smaller decay width are longer-lived and decay more slowly.
    

Now, let's explain the narrow width approximation:

- When the decay width (Γ) of a particle is much smaller than its mass (M), it means that the particle is relatively long-lived compared to the time scale of the process being studied.
    
- In this approximation, one can treat the particle as if it were stable for the purposes of certain calculations. This simplification is particularly useful when studying resonance phenomena, where particles temporarily exist in excited states before decaying into other particles.
    
- Mathematically, the narrow width approximation can be expressed as Γ << M. This implies that the particle spends a relatively long time in its excited state before decaying, allowing it to interact with other particles and form a resonance peak in a scattering process.
---


## Why study prompt?
Prompt photons and prompt muons are two examples of such objects:

1. Prompt Photons: A prompt photon refers to a photon that is produced directly from the primary interaction vertex in a particle collision. It is not the result of the decay of other particles. Prompt photons can arise from various processes, such as quark-gluon interactions, annihilation processes, or the decay of other prompt particles. They are often used as a probe to study specific interactions or to search for new phenomena in high-energy collisions.
    
2. Prompt Muons: Similarly, a prompt muon is a muon that is produced directly from the primary interaction vertex. Muons are heavy leptons, and prompt muons can be produced in processes like Drell-Yan production, where a quark and an antiquark annihilate to produce a virtual photon or Z boson, which subsequently decays into a muon-antimuon pair. Prompt muons are crucial in precision measurements, such as the determination of the W boson mass or the search for rare processes.
---

# A map of particle physics 
Creating an extensive map of particle physics topics is a complex endeavor due to the vast scope and intricate history of the field. I'll provide a high-level map of key topics, developments, and experiments in particle physics to give you a broad understanding of its evolution. This map will be divided into several sections:

**Foundations and Early Discoveries (Late 19th and Early 20th Century):**

- **Discovery of the Electron (1897):** J.J. Thomson's experiments led to the discovery of the electron, the first subatomic particle.
- **Development of Quantum Mechanics (1920s):** Pioneered by Schrödinger, Heisenberg, and Dirac, quantum mechanics laid the groundwork for understanding subatomic particles.

**The Rise of the Standard Model (Mid-20th Century):**

- **The Strong Interaction (1950s):** The theory of Quantum Chromodynamics (QCD) emerged to describe the strong nuclear force.
- **Discovery of the Pion (1947):** The first meson was discovered, confirming the existence of these particles.
- **Electroweak Theory (1960s):** Glashow, Salam, and Weinberg proposed the unification of the electromagnetic and weak forces.

**The Higgs Boson and the Standard Model Completion (Late 20th Century - Early 21st Century):**

- **Higgs Mechanism (1964):** Higgs, Brout, and Englert postulated the Higgs field and Higgs boson.
- **LHC and Higgs Discovery (2012):** The Large Hadron Collider (LHC) at CERN discovered the Higgs boson, confirming the last missing piece of the Standard Model.

**Beyond the Standard Model (Late 20th Century - Present):**

- **Grand Unified Theories (GUTs):** Theories attempting to unify forces emerged.
- **Supersymmetry (SUSY):** Postulates the existence of supersymmetric particles (sparticles).
- **String Theory:** An ambitious theory aiming to unify all fundamental forces.
- **Dark Matter and Dark Energy:** Ongoing efforts to understand the nature of these cosmic components.
- **Neutrino Oscillations (2001):** Neutrinos were found to change flavor, implying they have mass.

**Experimental Efforts:**

- **Particle Colliders:** The LHC, Tevatron, and others conducted experiments to probe the fundamental particles.
- **Neutrino Experiments:** Experiments like Super-Kamiokande and IceCube studied neutrinos.
- **Cosmic Ray and Cosmic Microwave Background (CMB) Observations:** These provided insights into the early universe and cosmic ray sources.

**Technological Developments:**

- **Detectors:** Advancements in particle detectors (e.g., silicon detectors, calorimeters, and time-of-flight detectors).
- **Computing:** High-performance computing for data analysis and simulations.
- **Accelerators:** Advances in accelerator technology, such as the LHC.

**Unsolved Mysteries:**

- **Dark Matter:** Its nature remains unknown, with various candidates being explored.
- **Dark Energy:** The cause of the accelerated expansion of the universe is still a mystery.
- **Flavor Physics:** Exploring the properties of quarks and leptons to understand CP violation.
- **Hierarchy Problem:** Why is the Higgs boson's mass so much smaller than expected?
- **Grand Unification:** The quest to unify all fundamental forces.

----


## Nice view of SM by quanta :
https://www.quantamagazine.org/a-new-map-of-the-standard-model-of-particle-physics-20201022/#comments

![](/images/notes/Pasted image 20231019113718.png)

----

### LLPs : #llp    #measurement 
Long lived particles - something that has caught my attention. Please find more abou it here in this dedicated section : LLP

----

# BSM Naturalness :
**Naturalness** is the aesthetic property that the dimensionless ratios between free parameters or physical constants appearing in a physical theory should take values "of order 1" and that free parameters are not <span style="color:#00b0f0">fine-tuned.</span> 


----

# SM quantum numbers:
Understanding the relationships between chirality, isospin, helicity, spin, and handedness in the context of fundamental particles can indeed be challenging due to the abstract nature of these concepts. Here’s a breakdown that might help make these concepts more memorable:

1. **Spin**: 
   - Think of it as an intrinsic form of angular momentum that every fundamental particle possesses. It's a quantum property, meaning particles have a fixed spin value (like 1/2 for fermions).

2. **Chirality**:
   - Chirality, or handedness, is a property that does not have a classical analog. It's purely quantum mechanical. For massless particles, chirality is well-defined and corresponds to the direction of the spin relative to the direction of motion. For massive particles, chirality is defined by the particle's wavefunction and is invariant under Lorentz transformation (meaning it doesn't change if you go to a different inertial frame).
   - Remember: Chirality is crucial because it determines how a particle interacts with the weak force. Only left-chiral particles and right-chiral antiparticles interact with the weak force.

3. **Helicity**:
   - Helicity is the spin's projection along the direction of motion. It's like asking whether the particle is spinning clockwise or counterclockwise as it moves along. For a particle moving near the speed of light, if you can overtake it and look back, does the spin seem to be rotating with or against its motion? That's helicity.
   - Note: For massless particles, helicity and chirality are the same because you can't overtake a massless particle (it always moves at the speed of light).

4. **Isospin**:
   - This is a concept inspired by the proton and neutron being almost identical in strong interactions. Isospin is a quantum number that differentiates members of a particle family, like up and down quarks, or protons and neutrons.
   - Think of isospin as a label in a quantum doublet: for up quarks and down quarks, up has isospin +1/2, and down has isospin -1/2.

5. **Weak Isospin**:
   - Weak isospin is similar to isospin but specifically for weak interactions. It's related to chirality: left-chiral particles have weak isospin, while right-chiral particles do not.
   - In the Standard Model, left-chiral fermions are doublets under the weak isospin (they have weak isospin values), and right-chiral fermions are singlets (they don't have weak isospin values).

6. **Handedness**:
   - This term can be confusing because it's used interchangeably with chirality and sometimes with helicity. In general, "handedness" refers to whether a particle is left-chiral or right-chiral.
   - For a simple mnemonic, think: "Left-handed particles shake hands with the weak force; right-handed particles do not."

Remembering the differences can be aided by associating each property with a specific aspect of particle behavior or interaction. You can also think about these properties in pairs: spin is a fundamental characteristic like the particle's eye color, while chirality/helicity is more about behavior, like whether they write with their left or right hand. Isospin and weak isospin are about the particle's identity in the context of forces, like different badges they wear in specific scenarios.

---


# QCD - p or not:
**Perturbative Quantum Chromodynamics (pQCD):**

**Application:**
- pQCD is applied in scenarios where the strong coupling constant is small, typically at high energy scales (due to asymptotic freedom). This includes processes like high-energy particle collisions where quarks and gluons are involved.

**Strengths:**
- Predictive Power: Provides precise predictions for processes at high energies where the coupling is weak.
- Tested by Experiments: Many predictions of pQCD have been confirmed by experiments, especially in collider physics.
- Calculational Framework: Allows systematic calculations using Feynman diagrams and renormalization techniques.

**Shortcomings:**
- Limited to High Energies: Not effective at low energy scales where the strong force becomes too strong (non-perturbative).
- Infrared Divergences: Issues arise in calculations at low momenta, requiring careful handling.
- Complexity: Calculations can become extremely complex at higher orders.

**Non-perturbative Quantum Chromodynamics (non-pQCD):**

**Application:**
- Non-pQCD is necessary at low energy scales where the strong coupling constant is large, like in the study of hadron structure, quark-gluon plasma, and nuclear forces.

**Strengths:**
- Applicable to Low Energies: Essential for understanding phenomena where the strong force is strong, such as hadronization and confinement.
- Rich Phenomenology: Provides insights into complex phenomena not accessible to pQCD.

**Shortcomings:**
- Lack of a Systematic Calculational Framework: Unlike pQCD, it doesn’t have a universally applicable mathematical framework like Feynman diagrams.
- Reliance on Models and Numerical Methods: Often depends on phenomenological models or numerical simulations (like lattice QCD), which may have their own limitations.
- Computational Intensity: Techniques like lattice QCD require significant computational resources.

In summary, pQCD excels in high-energy regimes where the strong force is weak and allows for perturbative methods. In contrast, non-pQCD is vital for understanding low-energy strong interactions but often relies on less precise or computationally intensive methods.

----


# Spin:
The spin of a particle in quantum mechanics is a fundamental property like its mass or charge. It's a form of angular momentum, but unlike the familiar angular momentum from classical physics (which arises from an object's rotation), spin is an intrinsic property of a particle, meaning it's a built-in feature of the particle's identity.

1. **Photon's Spin 1:**
   - Photons, which are the quantum particles of light, have a spin of 1. This classifies them as "vector bosons."
   - Spin 1 implies that photons can have three polarization states. Unlike particles with half-integer spins (like electrons, which have spin 1/2 and can only be spin up or spin down), photons can be left-circularly polarized, right-circularly polarized, or linearly polarized.
   - This property of photons is deeply connected with their role as force carriers of the electromagnetic force in quantum field theory.

2. **Higgs Boson's Spin 0:**
   - The Higgs boson, discovered at the Large Hadron Collider in 2012, has a spin of 0.
   - A spin of 0 classifies it as a "scalar boson." This means the Higgs boson does not have any intrinsic angular momentum.
   - Being a scalar boson, the Higgs does not have any directionality associated with it, which is consistent with its role in providing mass to other particles through the Higgs mechanism.

**Stern-Gerlach Experiment:**
   - The Stern-Gerlach experiment is famous for demonstrating the quantization of angular momentum. In its classical form, it involves passing a beam of particles through a non-uniform magnetic field and observing their deflection.
   - If you were to pass photons through a Stern-Gerlach apparatus, you wouldn't observe any splitting based on their spin. This is because the experiment is designed to measure magnetic moments of particles, and photons, being neutral and having no magnetic moment, are not affected by the magnetic field in the apparatus.
   - Similarly, the Higgs boson, with a spin of 0, would not be expected to show any splitting in a Stern-Gerlach experiment. Moreover, the Higgs boson is extremely short-lived and would decay before it could be manipulated in such an experiment.

In conclusion, the spin values of particles like the photon and the Higgs boson are essential for understanding their behavior and interactions in the realm of quantum mechanics and particle physics. However, the Stern-Gerlach experiment is not a suitable method to probe the properties of these particular particles.

## Light polarizations:
Photon polarization describes the oscillation direction of the electromagnetic field associated with the photon. Since photons are quanta of light, which is an electromagnetic wave, their polarization refers to the orientation of the electric field vector. The different types of polarization - left-circular, right-circular, and linear - describe the various ways this vector can behave in space over time as the photon travels.

1. **Linear Polarization:**
   - In linear polarization, the electric field of the photon oscillates in a single plane as it moves forward. Imagine the electric field as a straight line that swings back and forth in a fixed direction while the photon travels along its path. This is the simplest form of polarization.
   - Linear polarization is often described by the angle that this plane makes with a reference axis. For example, you might have vertically or horizontally polarized light, depending on the direction of the electric field oscillation.

2. **Circular Polarization:**
   - Circular polarization is more complex. Here, the electric field of the photon rotates in a circle around the direction of motion. This rotation can occur in two ways, giving rise to left-circular and right-circular polarization.
   - In left-circular polarization, if you were to look at the photon coming towards you, the electric field would rotate counterclockwise. Conversely, in right-circular polarization, it would rotate clockwise.
   - This circular motion of the electric field vector creates a helical pattern in space. The direction of this helix (left-handed or right-handed) determines whether the polarization is left-circular or right-circular.

3. **Elliptical Polarization:**
   - As an additional note, there's also elliptical polarization, which is a general form encompassing linear and circular polarizations. In elliptical polarization, the tip of the electric field vector traces out an ellipse in the plane perpendicular to the direction of propagation.

The polarization of a photon is a crucial aspect in various fields of physics and technology. For example, in quantum mechanics, polarization is an essential property in understanding photon entanglement and quantum information. In everyday technology, polarized lenses in sunglasses use the property of linear polarization to reduce glare by blocking certain orientations of light. Circular polarization is significant in areas like 3D movie projection and the transmission of radio waves.



---

![](/images/notes/Pasted image 20231214111903.png)

From a terascale talk on m_top < https://indico.desy.de/event/41133/contributions/158285/attachments/87444/116796/Presentation.pdf >

---


---

## Dead cone effect:
The "dead cone effect" is a phenomenon observed in particle physics, particularly in the context of the behavior of heavy quarks (like charm and bottom quarks) when they radiate gluons. This effect is a consequence of quantum chromodynamics (QCD), the theory that describes the strong interaction, one of the four fundamental forces in nature.

### Explanation of the Dead Cone Effect:

1. **Gluon Radiation from Quarks**: In QCD, quarks radiate gluons, much like charged particles radiate photons in electromagnetism. This radiation process is an essential aspect of jet formation in high-energy particle collisions.

2. **Mass of the Radiating Quark**: The pattern of this gluon radiation depends on the mass of the radiating quark. For light quarks (like up, down, and strange quarks), the radiation is relatively uniform in all directions. However, for heavy quarks, the situation is different due to their larger mass.

3. **Suppression Near the Quark Direction**: For a heavy quark, there is a suppression of gluon radiation at small angles relative to the direction of the quark's motion. This suppression creates a region with reduced gluon radiation, known as the "dead cone."

4. **Angle of the Dead Cone**: The size of the dead cone (i.e., the angular region around the heavy quark where gluon radiation is suppressed) is inversely proportional to the mass of the quark. The heavier the quark, the larger the mass, and thus, the smaller the angle of the dead cone.

### Importance in Particle Physics:

- **Jet Structure Analysis**: The dead cone effect is important in the analysis of jets produced in high-energy collisions, such as those in the Large Hadron Collider (LHC). It provides a way to distinguish between jets initiated by heavy quarks and those initiated by light quarks or gluons.
- **Testing QCD Predictions**: Observing and measuring the dead cone effect serves as a test of QCD, particularly its predictions regarding the behavior of heavy quarks.
- **Identifying Heavy Quark Jets**: In practical terms, the dead cone effect can be used as a tool to identify jets that originate from heavy quarks, which is important in many analyses searching for new physics beyond the Standard Model.

In summary, the dead cone effect is a unique signature in the pattern of gluon radiation from heavy quarks, and it plays a significant role in our understanding of strong interactions and in the analysis of experimental data in particle physics.

![](/images/notes/Pasted image 20240111145508.png)

---


# CP Violation link :
https://www.britannica.com/science/Pauli-exclusion-principle


----


# Basics of QFT:
Quantum Field Theory (QFT) is a fundamental framework in theoretical physics that combines classical field theory, special relativity, and quantum mechanics to describe the interactions of particles. It plays a crucial role in understanding the fundamental forces of nature, including electromagnetism, weak and strong nuclear forces, and theorizing about gravity. Here are the basic principles of QFT:

1. **Quantization of Fields:** Unlike classical physics, which treats particles as distinct entities and fields as continuous, <mark style="background: #FFB8EBA6;">QFT quantizes both matter and force fields</mark>. Fields are viewed as the fundamental entities, with particles arising as excitations or quanta of these fields.

2. **Wave-Particle Duality:** Consistent with quantum mechanics, QFT embraces the principle that particles exhibit both wave-like and particle-like properties. This duality is encapsulated in the behavior of field quanta.

3. **Special Relativity:** QFT incorporates the principles of special relativity, ensuring that the theory respects the invariance of the speed of light and the laws of physics in all inertial frames. This leads to a consistent description of particles moving at or near the speed of light.

4. **Local Interactions:** Interactions in QFT are local, meaning that particles interact at specific points in space and time. This principle is crucial for the causality and locality in the theory, ensuring that effects cannot propagate faster than the speed of light.

5. **Gauge Symmetry:** A central concept in QFT is gauge symmetry, which underlies the Standard Model of particle physics. Gauge symmetry refers to the invariance of the laws of physics under certain continuous transformations. It leads to the prediction of gauge bosons, the carriers of fundamental forces.
   
```Symmetry:
Here's what gauge bosons actually preserve:
- 1. **Gauge Invariance:** Gauge bosons preserve gauge invariance, which means that the physical laws remain unchanged (invariant) under certain types of transformations. These transformations are called "gauge transformations," and they can be thought of as changes that you can make in the mathematical description of a system without altering its physical state or observable phenomena.    
- 2. **Force Interaction:** Each type of gauge boson is associated with a specific fundamental force and preserves the symmetry that corresponds to that force. By mediating interactions, gauge bosons ensure that the conservation laws associated with these symmetries are upheld. Specifically:    
  - **Photon (γγ)**: The gauge boson for electromagnetism, preserving U(1) gauge symmetry. It mediates the electromagnetic force between charged particles, ensuring the conservation of electric charge.       
  - **W and Z Bosons**: These gauge bosons are responsible for the weak nuclear force, associated with the SU(2) gauge symmetry. They play a crucial role in processes like nuclear fusion in stars and radioactive decay, ensuring the conservation laws related to weak charge (weak isospin) are upheld.       
  - **Gluons (gg)**: The carriers of the strong nuclear force, associated with the SU(3) gauge symmetry of quantum chromodynamics (QCD). Gluons mediate the interactions between quarks inside hadrons (like protons and neutrons), preserving the conservation of color charge.      
  - **Graviton (hypothetical)**: If gravity can be described by a gauge theory (an ongoing area of research), the graviton would be the gauge boson for gravity, associated with the symmetry of general covariance in the theory of general relativity. It would mediate gravitational interactions, ensuring the conservation of energy-momentum.

```


6. **Renormalization:** Many QFT calculations initially result in infinite quantities. Renormalization is a process that systematically removes these infinities to yield finite, physically meaningful results. It is essential for making accurate predictions in quantum electrodynamics (QED) and other field theories.

7. **Feynman Diagrams:** Developed by Richard Feynman, these diagrams provide a visual representation of the interactions between particles in spacetime, simplifying the calculation of probabilities for complex interactions.

8. **Quantum Entanglement:** QFT also predicts quantum entanglement, a phenomenon where particles become correlated in ways that are not possible classically, reflecting a deep and non-intuitive aspect of quantum reality.

9. **Spontaneous Symmetry Breaking:** This principle explains how symmetries in the laws of physics can appear to be broken in lower-energy states, leading to phenomena such as the Higgs mechanism, which gives particles mass.

10. **Unification of Forces:** One of the goals of QFT is to unify the different fundamental forces into a single framework. While it has been successful for electromagnetism, weak, and strong nuclear forces (via the Standard Model), incorporating gravity remains an open challenge.


---


# Mixing:

In the context of particle physics, "mixing" refers to the phenomenon where quantum states of particles, such as quarks or neutrinos, are not the same as their mass eigenstates, leading to a probability of one type of particle transforming into another over time. This concept is crucial for understanding many aspects of particle interactions, especially those involving the weak force. Let's break down some of the key concepts:

### 1. Quark Mixing and the CKM Matrix

Quark mixing occurs because the weak interaction eigenstates (the states that participate in weak interactions) are not aligned with the mass eigenstates (the states with definite mass). This is described by the Cabibbo-Kobayashi-Maskawa (CKM) matrix, a mathematical framework that predicts the likelihood of one type of quark transforming into another through the weak interaction. For example, a down quark in a proton could, during a weak interaction, transform into an up quark, turning the proton into a neutron.

The CKM matrix is a unitary matrix that contains complex elements, each representing the probability amplitude for a transition between quark flavors. The existence of these off-diagonal elements in the matrix signifies quark mixing, which is fundamental to processes such as beta decay and the generation of the matter-antimatter asymmetry in the universe.

### 2. Weak Mixing Angle (Weinberg Angle)

The weak mixing angle, also known as the Weinberg angle, is a parameter in the electroweak theory of the Standard Model that measures the mixing between the electromagnetic and weak forces. It defines the relationship between the W and Z bosons (the carriers of the weak force) and the photon (the carrier of the electromagnetic force). This angle determines the strength of the weak force and plays a crucial role in predicting the outcomes of various particle interactions involving the weak interaction.

The physical manifestation of this mixing can be seen in processes such as the decay of subatomic particles, where the weak mixing angle influences the decay rates and the patterns of particle production.

### 3. Neutrino Oscillations

A similar concept of mixing occurs for neutrinos, known as neutrino oscillations, described by the Pontecorvo-Maki-Nakagawa-Sakata (PMNS) matrix. Neutrinos are produced in specific flavor states (electron, muon, or tau neutrinos), but as they travel, they can oscillate between these flavors. This phenomenon implies that neutrinos have mass and that the flavor eigenstates are superpositions of the mass eigenstates. Neutrino oscillations are a direct consequence of mixing and have been experimentally observed, providing key insights into the properties of neutrinos and their role in the universe.

### Physical Implication

The concept of mixing in particle physics has profound implications, revealing the fundamental interconnectedness of particle states and forces at the quantum level. It challenges the classical notion of particles having fixed identities, showcasing the fluidity and dynamism of quantum states. Through the study of mixing, physicists have deepened their understanding of the weak interaction, CP violation (a difference in the behavior of particles and antiparticles), and the generation of mass for fundamental particles via the Higgs mechanism. These insights are essential for both explaining the observed phenomena in the universe and guiding the search for new physics beyond the Standard Model.

If the mass eigenstates align with the quantum states (flavor eigenstates) of particles, it means that the particles do not mix and there is no transformation between different flavors (or types) of that particle due to quantum mechanical effects. This scenario simplifies the understanding of particle interactions, as each particle type remains distinct and does not oscillate into another type over time. In particle physics, the alignment of mass eigenstates with quantum states means that the probability matrix (like the CKM matrix for quarks or the PMNS matrix for neutrinos) becomes an identity matrix, indicating no mixing and thus no oscillations between different flavors.

### Examples in Particle Physics:

#### 1. Photon
One of the simplest examples is the photon, the quantum of light and carrier of the electromagnetic force. Photons are massless particles and do not have different flavor states that could mix. Their quantum state is aligned with their "mass" eigenstate (though they are massless), meaning there's no concept of mixing or oscillations for photons.

#### 2. Gluons
Gluons are the force carriers of the strong nuclear force, responsible for holding quarks together inside protons, neutrons, and other hadrons. Gluons themselves come in eight types due to the color charge in quantum chromodynamics (QCD), but these types do not mix in the same way as the flavor eigenstates of quarks or neutrinos. Their behavior and interactions are dictated by the rules of QCD, and while they exhibit complex interactions like color confinement and gluon self-interaction, they do not have a mixing matrix like the CKM or PMNS matrices for quarks and neutrinos.

#### 3. Electron, Muon, and Tau (without Neutrino Mixing)
In a hypothetical world where neutrino masses were exactly aligned with their flavor states (electron neutrino with the electron, muon neutrino with the muon, etc.), there would be no neutrino oscillations. This would mean that an electron neutrino, for example, would always interact as an electron neutrino and could not be observed as a muon or tau neutrino at a later time. However, in reality, neutrino oscillation experiments have shown that neutrinos do indeed mix and oscillate between flavors, indicating that their mass eigenstates are not aligned with their flavor states.

### Physical Consequences
The alignment of mass and quantum states significantly affects the predictions and interpretations of particle physics. Mixing and oscillations provide crucial insights into the properties of particles, such as mass differences and the presence of CP violation. Without these phenomena, the understanding of particle mass hierarchies, flavor dynamics, and the asymmetry between matter and antimatter in the universe would be fundamentally different. The study of these mixing and oscillation effects has been central to many breakthroughs in particle physics, including the discovery of neutrino mass and the study of CP violation in the quark sector.

---
# No 4th gen:
The question of whether there is a fourth generation of fundamental particles is intriguing and has been explored through both theoretical considerations and experimental searches. As of the current understanding, several lines of evidence from particle physics experiments, particularly those involving the properties of the Higgs boson and precision measurements of the Standard Model parameters, suggest that a fourth generation of standard fermions (quarks and leptons) is highly unlikely. Here are some of the key arguments:

### 1. **Higgs Boson Production and Decay Rates**

The discovery of the Higgs boson at the Large Hadron Collider (LHC) provided critical insights into the structure of the Standard Model. The Higgs boson production and decay rates observed are consistent with the predictions of the Standard Model with three generations of fermions.

- **Enhanced Higgs Production**: A fourth generation would significantly enhance the production rate of the Higgs boson through gluon fusion, due to the additional heavy quarks. This enhanced rate has not been observed.
- **Higgs Decay into Photons**: The presence of a fourth generation would also affect the Higgs decay into two photons. The rate of this decay process, which is sensitive to loops of charged particles, including hypothetical heavy quarks and leptons, is consistent with three generations.

### 2. **Electroweak Precision Tests**

Electroweak precision tests involve measurements of the properties of the W and Z bosons (mass, width, and couplings to fermions) and other electroweak processes at high precision. These measurements are sensitive to the effects of virtual particles in quantum loops, and thus to the number of fermion generations.

- **Z Boson Width**: The decay width of the Z boson, measured very precisely, agrees with the predictions for three generations of neutrinos. A fourth generation of light neutrinos (with mass less than half the Z boson mass) would have increased the Z boson's decay width significantly, which is not observed.
- **Global Fits to the Standard Model**: Global fits of the electroweak precision data, which include a wide range of measurements, show excellent agreement with the predictions of the Standard Model with three generations. Adding a fourth generation would disturb this agreement, particularly because of the modifications it would imply for the loop corrections in various processes.

### 3. **Direct Searches**

Direct searches for fourth-generation quarks and leptons have been conducted at particle accelerators, including the LHC. No evidence has been found for the existence of such particles up to the highest masses explored by current experiments.

### 4. **Theoretical Considerations**

- **Stability of the Higgs Potential**: Theoretical studies suggest that the addition of a fourth generation could make the Higgs potential unstable at energies not much higher than the electroweak scale unless new physics comes into play.
- **Yukawa Couplings**: The Yukawa couplings of the fourth-generation fermions to the Higgs boson would have to be very large to account for their heavy masses, which leads to potential issues with perturbativity and vacuum stability.

----


# UV incompleteness of SM:

The Standard Model of particle physics, while highly successful in describing the fundamental particles and their interactions, is considered incomplete and does face issues with ultraviolet (UV) divergences.

1. **UV Incompleteness**: The Standard Model is deemed incomplete because it does not incorporate gravity at the quantum level. Gravity is described by general relativity, a classical theory, and integrating it into the quantum mechanics framework of the Standard Model remains a significant challenge. Additionally, the Standard Model does not explain dark matter, dark energy, or the matter-antimatter asymmetry in the universe, all of which are observations that the model does not account for.

2. **UV Divergences**: In terms of UV divergences, these occur in quantum field theories, including the Standard Model, when certain integrals over all possible energy scales lead to infinite results. These infinities appear in the calculations of various physical quantities, making them seemingly nonsensical without further intervention. However, a technique called renormalization is used to handle these divergences. By this method, the parameters of the theory (like masses and coupling constants) are adjusted to absorb these infinities, resulting in finite predictions that agree remarkably well with experimental data.

Thus, the Standard Model is both incomplete in its description of the universe and involves dealing with UV divergences through renormalization techniques. The search for a more complete theory, such as theories of quantum gravity or various extensions of the Standard Model like supersymmetry, continues to be a vibrant field of research in theoretical physics.

"UV" refers to "ultraviolet divergences," which is a technical term unrelated to the ultraviolet light in the electromagnetic spectrum. It refers instead to<mark style="background: #ABF7F7A6;"> problems in the mathematics of quantum field theories that arise at very high energy scales</mark> (short distances), metaphorically similar to the ultraviolet end of the spectrum which corresponds to high energy and short wavelengths in light.

**UV incompleteness** in particle physics, particularly in relation to gravity, means that the current theories, like the Standard Model, do not effectively handle the physics at these very high energy scales where gravitational effects become significant on quantum scales.

Gravity's role in this is crucial because:

1. **Quantum Gravity**: At extremely small scales, on the order of the Planck length (about \(10^{-35}\) meters), quantum effects of gravity are expected to become significant. The Standard Model does not include gravity in its framework, and at these scales, it is believed that a theory of quantum gravity would be required to properly describe interactions.

2. **Renormalization Issues**: In most parts of the Standard Model, divergences (infinite results) that appear in calculations can be managed by the process of renormalization. However, gravity, when attempted to be incorporated in a similar quantum field theoretical framework, leads to non-renormalizable divergences. This means that if gravity is treated like other forces within the quantum field theory, the infinity problems become unmanageable under the current renormalization techniques.

So, when discussing UV incompleteness in relation to gravity, it refers to the theoretical limitation where at very small (ultraviolet) scales, the current models (like the Standard Model) fail to account for gravitational effects and cannot predict phenomena accurately due to these unmanageable infinities. This is one of the reasons why physicists are searching for a unified theory, like string theory or loop quantum gravity, which hopes to integrate gravity with the quantum framework effectively.

----

# CP violation 

CP violation refers to the phenomenon where the laws of physics change when particles are replaced with their antiparticles (charge conjugation, C) and their spatial coordinates are inverted (parity transformation, P). This concept plays a crucial role in explaining why there is more matter than antimatter in the universe.

### Why Was CP Violation Proposed?

1. **Matter-Antimatter Asymmetry**:
   - One of the major unsolved problems in cosmology is the observed dominance of matter over antimatter in the universe. According to the Big Bang theory, matter and antimatter should have been created in equal amounts. However, if that were the case, they would have annihilated each other, leaving behind only radiation. The fact that the universe is filled with matter suggests an asymmetry in the laws governing particles and antiparticles.

2. **Sakharov Conditions**:
   - In 1967, Andrei Sakharov outlined three necessary conditions for baryogenesis (the process that produced an excess of baryons over antibaryons in the early universe):
     - Baryon number violation.
     - C and CP violation.
     - Departure from thermal equilibrium.
   - CP violation is essential because it allows processes that distinguish between matter and antimatter, leading to the observed asymmetry.

### Historical Context and Theoretical Development

1. **Parity Violation**:
   - In 1956, theoretical physicists Tsung-Dao Lee and Chen-Ning Yang proposed that parity (P) might not be conserved in weak interactions. This was a radical idea because parity conservation was assumed to be a fundamental symmetry of nature.

2. **Madame Wu's Experiment**:
   - In 1956-57, Chien-Shiung Wu conducted an experiment involving the beta decay of cobalt-60. She and her team found that parity was indeed violated in weak interactions, confirming the theoretical predictions of Lee and Yang. This discovery earned Lee and Yang the Nobel Prize in Physics in 1957.
     ![](/images/notes/Pasted image 20240924105204.png)

3. **CP Violation Prediction**:
   - After the discovery of parity violation, physicists began to question whether the combined symmetry of charge conjugation (C) and parity (P) might also be violated. In 1964, James Cronin and Val Fitch conducted experiments with neutral kaons (a type of meson) and observed CP violation. This discovery provided the first experimental evidence that CP symmetry is not conserved in certain weak interactions.


## Wu's experiment:
 The **Cobalt-60 (Co-60) experiment**, famously conducted by physicist **Chien-Shiung Wu** in 1956, provided the first experimental evidence of **parity violation** in the **weak interaction**. Here’s a brief rundown of the experiment:

- ### 1. **Setup**:
- **Cobalt-60** is a radioactive isotope that undergoes **beta decay**, where the nucleus emits an electron and an antineutrino.
- The **spins** of the cobalt nuclei were **aligned** by placing them in a strong magnetic field at low temperatures.

- ### 2. **Expected Parity Symmetry**:
- If **parity** (mirror symmetry) were conserved, the emitted electrons from the decaying nuclei should be equally likely to be emitted in any direction relative to the nucleus's spin.
- In the mirror image of the experiment, the behavior of the electrons should look the same.

- ### 3. **Observation**:
- What Wu and her team observed was that **more electrons were emitted in a direction opposite to the nuclear spin**, breaking the expected symmetry.
- In the mirror world (after a parity transformation), this behavior would not occur, showing that **parity was violated**.

- ### 4. **Conclusion**:
- This experiment demonstrated that the **weak force** (responsible for beta decay) does not treat left and right equally—**parity is violated** in weak interactions.
- It was a groundbreaking discovery, fundamentally changing how physicists understood symmetries in nature.

This experiment provided direct evidence that parity symmetry, long thought to be a universal principle, is **not conserved** in weak nuclear interactions.

![](/images/notes/Pasted image 20240924114348.png)

#### In Summary:

- **Co-60 nuclei** were aligned to have their spins pointing in the same direction.
- If parity were conserved, we would expect **symmetric electron emission** regardless of the nuclear spin direction.
- Instead, **more electrons were emitted in the opposite direction to the nuclear spin**.
- These electrons were found to be **left-handed**, meaning their spin was opposite to their motion.
- This observation showed that the weak force **violates parity**, preferring to interact with **left-handed particles**.

- **Most electrons** were emitted **opposite to the nuclear spin** and were **left-handed**, but not **all** of them. The weak interaction isn't 100% exclusive in producing only left-handed electrons in this case; there's a small probability that some **right-handed electrons** were produced.
    
- This is because electrons are **massive** particles, and their mass allows them to switch between **left-handed and right-handed states** under certain conditions. For massless particles (like neutrinos, as we understand them), they would strictly obey chirality (meaning neutrinos are **always left-handed** in weak interactions). But because electrons have mass, there’s a slight chance that some can still be emitted with **right-handedness**.

The weak interaction is very **biased** toward left-handed particles, but because the electron has mass, its **helicity (handedness)** can flip depending on the reference frame or due to small quantum effects. This explains why **most** of the emitted electrons were left-handed, but a small fraction were still emitted in the same direction as the nuclear spin, making them **right-handed**.

### Experimental Evidence and Importance

1. **Cronin and Fitch Experiment**:
   - Cronin and Fitch's 1964 experiment with neutral kaons demonstrated that the decay rates of kaons and antikaons were not identical, thus providing clear evidence of CP violation. This work earned them the Nobel Prize in Physics in 1980.

2. **Further Studies**:
   - Subsequent experiments have confirmed CP violation in other systems, such as B mesons. The study of CP violation has become an important part of particle physics, influencing the development of the Standard Model.

3. **Implications for Cosmology**:
   - CP violation is a critical ingredient in explaining the matter-antimatter asymmetry of the universe. Without CP violation, it would be impossible to account for the predominance of matter over antimatter.

### Summary

CP violation was proposed to address the problem of matter-antimatter asymmetry in the universe and was predicted as a necessary condition for baryogenesis. It was first experimentally observed by Cronin and Fitch in 1964, not by Chien-Shiung Wu, who earlier demonstrated parity violation. CP violation remains a fundamental aspect of particle physics and cosmology, helping to explain why the universe is composed predominantly of matter.

----


# Mass hierarchy problem:

### The Mass Hierarchy Problem Explained

The mass hierarchy problem is a significant issue in particle physics related to the vast difference in the masses of elementary particles, particularly focusing on the Higgs boson and other particles. Let's break down the problem in a detailed yet simple manner:

#### What is the Mass Hierarchy Problem?

1. **Elementary Particles and the Higgs Boson**:
   - **Elementary particles**: Fundamental particles like quarks, leptons (e.g., electrons, neutrinos), and gauge bosons (e.g., photons, W and Z bosons).
   - **Higgs boson**: A particle associated with the Higgs field, responsible for giving mass to other elementary particles through the Higgs mechanism.

2. **Hierarchy of Masses**:
   - In the Standard Model of particle physics, particle masses vary widely. For example, the electron is much lighter than the top quark, and the Higgs boson has a mass around 125 GeV (giga-electron volts).
   - The **Planck scale** (about \(10^{19}\) GeV) is a fundamental energy scale related to gravity, many orders of magnitude larger than the mass of the Higgs boson.

3. **The Core Issue**:
   - The mass of the Higgs boson should be subject to quantum corrections from interactions with other particles.
   - These corrections tend to be very large, potentially pushing the Higgs mass up to the Planck scale. However, the observed Higgs mass is relatively low (125 GeV).
   - The question arises: **Why is the Higgs boson mass so much lighter than the Planck scale?**

#### Why is This Considered an Issue?

1. **Naturalness Problem**:
   - According to the principle of naturalness, parameters in a theory should not be fine-tuned without a good reason. The large difference between the Higgs mass and the Planck scale suggests an unnatural fine-tuning.

2. **Quantum Corrections**:
   - In quantum field theory, the mass of the Higgs boson receives corrections from loops involving all other particles it interacts with. These corrections can be extremely large.
   - For example, if a particle interacts with the Higgs field, the Higgs boson mass should reflect contributions from the mass of that particle. Heavy particles like the top quark contribute significantly to these corrections.
   - Without some mechanism to counteract these corrections, the Higgs mass would naturally be very large.

3. **Fine-Tuning**:
   - To keep the Higgs mass at the observed value, one must precisely cancel out these large corrections, which seems highly improbable without a deeper reason.
   - This precise cancellation appears to be an unnatural fine-tuning, which many physicists find unsatisfactory.

#### Potential Solutions

1. **Supersymmetry (SUSY)**:
   - Supersymmetry proposes that every Standard Model particle has a corresponding superpartner with different spin characteristics.
   - These superpartners contribute opposite-sign corrections to the Higgs mass, potentially canceling out the large quantum corrections and stabilizing the Higgs mass at a lower value.
   - Despite being an elegant solution, direct experimental evidence for supersymmetry has not yet been found.

2. **Extra Dimensions**:
   - Some theories suggest the existence of extra spatial dimensions beyond the familiar three.
   - These extra dimensions could alter the effective scale at which gravity operates, potentially lowering the Planck scale and mitigating the hierarchy problem.

3. **Composite Higgs Models**:
   - In these models, the Higgs boson is not a fundamental particle but a composite of other, more fundamental particles.
   - This compositeness could explain why the Higgs mass is naturally lighter than expected.

4. **Technicolor**:
   - This is a theory that replaces the Higgs mechanism with a new strong interaction.
   - In technicolor theories, the Higgs boson is a bound state of new fermions, similar to how pions arise from the strong interaction in quantum chromodynamics (QCD).


## Real vs. Virtual Particles

1. **Real Particles**:
   - Real particles are those that we can observe directly and measure in experiments.
   - They satisfy the energy-momentum relation \(E^2 = p^2c^2 + m^2c^4\), meaning they are on-shell (i.e., their mass is well-defined).

2. **Virtual Particles**:
   - Virtual particles are internal particles in Feynman diagrams that exist temporarily during interactions.
   - They do not need to satisfy the energy-momentum relation exactly, meaning they are off-shell.
   - Their masses can deviate from the physical (on-shell) masses of the corresponding real particles.

### Virtual Particles in Loop Corrections

1. **Off-Shell Nature**:
   - Virtual particles can have a range of momenta and energies, which means their effective masses can vary during the interaction.
   - However, the virtual particles contribute to the loop corrections based on their coupling constants and the nature of the interaction.

2. **Effective Contributions**:
   - Even though virtual particles are off-shell, their contributions to loop corrections are influenced by their physical (on-shell) masses because the propagators (terms in the Feynman diagram calculations) still depend on these masses.
   - For example, the contribution of a virtual top quark to the Higgs boson mass correction will be influenced by the top quark's on-shell mass because the propagator involves terms like \(1/(p^2 - m_t^2)\), where \(m_t\) is the top quark mass.

### Higgs Mass Corrections and Heavy Particles

1. **Top Quark Contributions**:
   - The top quark has a large physical mass (~173 GeV), and this large mass significantly affects the loop corrections.
   - The heavy mass of the top quark enhances its contribution to the Higgs boson mass correction, even when the top quark is virtual.

2. **Why Heavy Virtual Particles Matter**:
   - The loop integrals that involve virtual top quarks will integrate over a range of momenta, but the integrand will still be heavily influenced by the physical mass of the top quark.
   - The heavier the physical mass of the particle, the larger its contribution to the loop corrections, due to the terms in the propagators and vertices.

### Simplified Picture

- Even though virtual particles are off-shell, the corrections to the Higgs boson mass are computed using integrals that take into account the physical masses of the particles involved.
- The effective mass corrections reflect the influence of these physical masses. For a heavy particle like the top quark, this means it has a large impact on the corrections, making the Higgs boson mass sensitive to the top quark's physical mass.

### Summary

- Virtual particles have undetermined, off-shell masses, but their contributions to loop corrections are influenced by their physical, on-shell masses.
- The heavy physical mass of the top quark leads to significant contributions to the Higgs boson mass correction because the terms in the loop integrals are sensitive to the top quark's mass.
- This is why, despite being virtual and off-shell, the top quark's large mass plays a crucial role in the quantum corrections to the Higgs boson mass.

By considering the above, we recognize that while virtual particles are off-shell, the physical properties of these particles, such as their mass, still play a critical role in determining the magnitude of their contributions to loop corrections. This is a fundamental aspect of quantum field theory and the calculations involved in understanding particle interactions.

----


# Understanding some concepts in SM :

#standardmodel

Absolutely! You're asking about some of the most fundamental concepts in particle physics, and understanding how they all fit together can be tricky. Let's walk through each concept, connecting the dots between them. I'll explain **scalar vs. pseudoscalar**, **chirality**, **handedness**, **parity**, **spin**, **hypercharge**, and more, and how they relate to each other.

### 1. **Scalar vs. Pseudoscalar**
- **Scalar**: A scalar is a quantity that has **magnitude** but **no direction** and remains unchanged under spatial transformations (like rotation or reflection). In particle physics, a **scalar field** is associated with particles that have **no spin** (spin 0), such as the **Higgs boson**.
- **Pseudoscalar**: A pseudoscalar is similar to a scalar in that it has no direction, but it **changes sign under parity transformations** (mirror reflection). An example of a pseudoscalar particle is the **neutral pion**.

#### Connection: Scalars and pseudoscalars both describe spin-0 particles, but a pseudoscalar flips its sign under parity, while a scalar does not.

### 2. **Chirality vs. Handedness**
- **Chirality**: Chirality refers to how a particle behaves under **weak interactions**. In the Standard Model, only **left-handed particles** and **right-handed antiparticles** participate in the weak force. Chirality is a more abstract concept than handedness and can be thought of as a fundamental property that determines how particles interact. 
- **Handedness**: Handedness refers to the **direction** of a particle's spin relative to its motion. A particle is:
  - **Right-handed** if its spin is aligned with its direction of motion.
  - **Left-handed** if its spin is opposite to its direction of motion.

![](/images/notes/Pasted image 20240924103228.png)

#### Key Detail:
- **Chirality** and **handedness** are not always the same for **massive particles**. For massless particles (like photons), chirality and handedness are identical. For massive particles (like electrons), they can differ depending on the frame of reference.
  
#### Connection: Chirality defines how particles interact with the weak force, while handedness refers to the actual direction of spin. Handedness can change based on the observer's motion, but chirality remains the same.

### 3. **Parity**
- **Parity** is a symmetry operation that involves **flipping the spatial coordinates** (like looking at a system in a mirror). If a system looks the same after flipping the spatial coordinates, it has **even parity**. If it looks different or changes sign, it has **odd parity**.
- **Example**: In the weak interaction, parity is **not conserved**. This is why weak interactions only involve left-chiral particles and right-chiral antiparticles. This is called **parity violation**, and it's one of the most important features of the weak force.

#### Connection: Parity involves flipping spatial coordinates, and how particles transform under parity is closely tied to whether they are scalars, pseudoscalars, or have certain chiralities.

### 4. **Spin**
- **Spin** is a fundamental property of particles, representing **intrinsic angular momentum**. It’s quantized in half-integer or integer units (like \(0\), \( \frac{1}{2} \), 1, etc.). For example:
  - **Electrons** have spin \( \frac{1}{2} \).
  - **Photons** have spin 1.
  - **Higgs boson** has spin 0 (a scalar particle).
  
- **Spin and Statistics**: Spin also determines whether a particle obeys **Fermi-Dirac** or **Bose-Einstein** statistics:
  - Particles with half-integer spin (fermions) obey the **Pauli exclusion principle** (no two fermions can occupy the same quantum state).
  - Particles with integer spin (bosons) do not follow the exclusion principle and can occupy the same state.

#### Connection: Spin is fundamental to classifying particles as either **fermions** or **bosons** and influences how they interact and behave under symmetry operations like parity or chirality.

### 5. **Hypercharge (Y)**
- **Hypercharge** is a quantum number related to the **electroweak interaction**. It’s a combination of electric charge and weak interaction properties. In the Standard Model, **hypercharge (Y)**, together with **weak isospin (T3)**, helps determine a particle’s electric charge:
  \[
  Q = T_3 + \frac{Y}{2}
  \]
  Where:
  - \( Q \) is the electric charge.
  - \( T_3 \) is the third component of weak isospin (related to weak force interactions).
  - \( Y \) is the hypercharge.

- Example: For an electron, \( T_3 = -\frac{1}{2} \) and \( Y = -1 \), giving \( Q = -1 \) (the electron’s charge).

#### Connection: Hypercharge is part of the **electroweak theory** and helps determine how particles interact via the electromagnetic and weak forces. It’s linked to electric charge and isospin.

### 6. **Right-Handed vs. Left-Handed**
- **Right-Handed and Left-Handed Particles** refer to how their **spin** is aligned relative to their **momentum**.
  - A **right-handed particle** has its spin aligned in the same direction as its motion.
  - A **left-handed particle** has its spin opposite to its direction of motion.

- **Weak Interactions**: The weak force only interacts with **left-handed particles** and **right-handed antiparticles**. This is a key feature of **parity violation** in the weak interaction.

#### Connection: Handedness is a property of particles that relates to their spin and motion. Chirality describes whether a particle can participate in weak interactions, which strongly prefer left-handedness.

### How These Concepts Relate:

- **Chirality and Handedness**: Chirality defines how particles interact with the weak force, while handedness describes the direction of a particle’s spin. For massless particles like the photon, they are the same, but for massive particles like the electron, chirality and handedness can differ depending on the observer’s frame of reference.
  
- **Parity and Spin**: Parity symmetry involves flipping spatial coordinates. How particles behave under parity is tied to their spin. For example, scalar particles (spin-0) have even parity, while pseudoscalars (spin-0 particles that change sign under parity) have odd parity.

- **Spin and Hypercharge**: Spin determines the particle’s intrinsic angular momentum, while hypercharge is a quantum number related to the particle’s interactions under the electroweak force. Together with weak isospin, hypercharge helps determine the particle’s electric charge.

### Summary of Connections:
- **Chirality** defines how particles interact with the weak force, while **handedness** describes the direction of spin.
- **Parity** tests how particles behave when their spatial coordinates are flipped.
- **Spin** describes the intrinsic angular momentum of a particle and determines its behavior under symmetry operations like parity.
- **Hypercharge** is linked to electroweak interactions and electric charge.

These concepts are all interconnected in particle physics and form the foundation of how particles interact and behave under the different fundamental forces.

----


# Cosmic sources of neutrinos:

 **Supernovae** and **stellar fusion** processes, which produce huge numbers of neutrinos, indeed involve **weak interactions**, meaning they are mediated by **W and Z bosons** at the fundamental level. These weak interactions are responsible for key processes that generate neutrinos in stars and supernovae. Let’s break it down step by step.

### 1. **Weak Interactions in Stellar Fusion (like in the Sun)**
Stars, including our Sun, generate energy through **nuclear fusion**, primarily through the **proton-proton chain reaction** (in stars like the Sun) or the **CNO cycle** (in larger stars). 


In these processes, **weak interactions** play a critical role in converting protons into neutrons and producing **neutrinos**.

#### Proton-Proton Chain (Sun):
The first step in the proton-proton chain involves a **weak interaction**:
- **p + p → d + e⁺ + ν_e**
  - Two protons fuse to form a deuteron (a proton and neutron bound together), a **positron**, and an **electron neutrino** (**ν_e**).
  - This is mediated by the **weak force**, specifically by the exchange of a **W⁺ boson**, which changes one of the protons into a neutron.

Here’s what's happening at the fundamental level:
- In the fusion reaction, one proton (a **uud** quark combination) transforms into a neutron (a **udd** quark combination). This transformation happens through the **weak interaction**, where a **down quark** is converted into an **up quark**, mediated by the **W⁺ boson**.
- The emitted **electron neutrino** (**ν_e**) is a direct result of this weak interaction.

#### Carbon-Nitrogen-Oxygen (CNO) Cycle (larger stars):
In the **CNO cycle**, which occurs in more massive stars, **neutrinos** are also produced through weak interactions in the cycle's steps:
- For example, in one reaction, a **proton** and a **carbon-12 nucleus** fuse, with the emission of a **positron** and a **neutrino**, mediated by the **W boson**.

![](/images/notes/Pasted image 20240924114946.png)

Thus, in both the **proton-proton chain** and the **CNO cycle**, weak interactions mediated by **W bosons** are responsible for the production of neutrinos in stars.

### 2. **Supernovae and Weak Interactions**
In a **supernova**, weak interactions are also crucial, especially during the **core-collapse phase** of massive stars. When a star runs out of nuclear fuel, its core collapses, leading to extreme conditions where weak interactions play a major role.

#### Core-Collapse Supernova:
- When the core of a massive star collapses, **neutrinos** carry away a significant portion of the star's energy. About **99% of the energy** released during a supernova explosion is emitted in the form of **neutrinos**.
- As the core contracts, the density becomes so high that **neutrons** are formed from **protons** via the capture of electrons in a weak interaction:
  - **p + e⁻ → n + ν_e**
    - A **proton** and an **electron** combine to form a **neutron** and emit an **electron neutrino** (**ν_e**). This process is mediated by the **W⁻ boson**.

At the fundamental level, this process involves the weak force:
- A **down quark** in the proton transforms into an **up quark** via the emission of a **W⁻ boson**, which decays into an electron and an electron neutrino.

#### Neutrino Emission in Supernovae:
- **Neutrino bursts**: As the core collapses, the resulting **neutrino burst** is mainly composed of electron neutrinos from the weak interactions in the dense core.
- In addition to the electron neutrinos produced in the core, **muon neutrinos** and **tau neutrinos** are produced in supernovae, mediated by weak interactions involving the **Z boson** (which can produce neutrino-antineutrino pairs).

The detection of **neutrinos from supernovae** (like those from **Supernova 1987A**) confirms that weak interactions mediated by W and Z bosons play a fundamental role in these events.

### 3. **Do We Know What’s Happening at Fundamental Levels?**
Yes, we have a pretty solid understanding of what happens at the **fundamental level** in both stellar fusion and supernovae:
- **W bosons** are responsible for the transformation of protons to neutrons and the emission of neutrinos.
- **Z bosons** mediate neutrino-antineutrino pair production.
- These weak interactions occur at the **quark level**, involving the transformation of **up quarks** and **down quarks** in the nucleons (protons and neutrons).

The processes of **neutron formation** and **neutrino emission** are well understood within the framework of the **Standard Model** of particle physics. These weak interactions are vital in both the **fusion reactions** that power stars and the **collapse mechanisms** that drive supernovae.

### Summary:
- **Stellar fusion** and **supernovae** involve **weak interactions** mediated by **W and Z bosons**, which result in the production of neutrinos.
- In stellar fusion (like the **proton-proton chain**), weak interactions convert protons to neutrons, emitting **electron neutrinos**.
- In **supernovae**, weak interactions are responsible for the formation of neutrons and the emission of a huge number of neutrinos, with the process mediated by **W bosons**.
- Our understanding of these processes at the fundamental level is grounded in the **Standard Model**, where the weak interaction governs the transformations and neutrino emissions that are crucial in these astrophysical events.

We observe **neutrinos** from the Sun and supernovae (for eg. 1987A) using detectors like **Super-Kamiokande**, which confirm the fusion and collapse processes predicted by models. We also measure **light and energy output** (like solar radiation and supernova light curves) with telescopes, matching the energy released in fusion and explosions. Additionally, we analyze the **chemical elements** produced in stars and supernovae through spectroscopy, which aligns with nucleosynthesis predictions. These observations consistently match the **Standard Model** and astrophysical theories. More on them later maybe.

----


![](/images/notes/Pasted image 20250320135224.png)

# Masses:
#mass

The **boosted top quark mass** and the **pole mass** are related concepts but represent different aspects of how we define or measure the mass of the **top quark**. The confusion often arises because these terms refer to different **contexts** or **methods** of defining and calculating mass in quantum field theory.

### 1. **Pole Mass**:
- The **pole mass** of the top quark is the **rest mass**, or the mass when the particle is on-shell (not interacting, and at rest). It’s essentially the conventional definition of mass that corresponds to the position of the **pole** in the propagator of the particle, which is why it's called the pole mass.
- The pole mass is theoretically well-defined but comes with certain challenges due to **QCD effects**.
- **QCD Infrared Sensitivity**: Due to the strong coupling constant (which grows at low energy scales), the pole mass suffers from an ambiguity of around **200-300 MeV**, making it less precisely defined for quarks like the top.

### 2. **Boosted Top Quark Mass**:
- The **boosted top quark mass** typically refers to the effective mass as observed in the context of **boosted kinematics**, where the top quark is produced with very high momentum relative to the observer. This is particularly common in high-energy environments, such as those involving **TeV-scale collisions** at the **LHC**.
- When the top quark is highly boosted, its **decay products** (like the W boson and b-quark) are collimated into a single **jet**. In this context, techniques such as **jet substructure** are used to reconstruct the mass of the boosted top quark.
- This "boosted" mass is more about reconstructing the mass from **observed final-state particles** using specific algorithms and corrections for detector effects, rather than being a fundamental definition of mass like the pole mass.

### 3. **Relation to Running Coupling and MS¯ Mass**:
- In quantum field theory, due to **running coupling**, the definition of mass changes depending on the **energy scale**. This means that the top quark mass can vary depending on the scale at which it’s probed.
- The **MS¯ (Modified Minimal Subtraction) mass**, also known as the **running mass**, is an energy-scale dependent mass that is calculated in the **renormalization scheme**. This mass decreases as the energy scale increases due to the effects of the strong coupling constant.
- The **boosted top quark** mass, in practice, is often closer to the **MS¯ mass** because it is defined at higher energies, whereas the **pole mass** is the low-energy, conventional definition.

### **Summary**:
- **Pole Mass**: The "true" rest mass of the top quark, defined in a way that is independent of its energy or momentum, but with some ambiguity due to QCD effects.
- **Boosted Top Quark Mass**: The mass of a top quark reconstructed from its highly energetic decay products in collider experiments. It’s influenced by jet reconstruction techniques and may correspond more closely to the **running mass** at higher energy scales.
- **Running Mass and Running Coupling**: Due to the strong interaction, the top quark’s mass is scale-dependent, with the **MS¯ mass** decreasing as the energy scale increases.

In high-energy experiments, such as those involving **boosted top quarks**, the top quark mass is affected by how it is reconstructed from its decay products, which can make it look different from its pole mass due to effects from running coupling and reconstruction techniques. This is why the boosted top quark mass may be more comparable to a running mass defined at a higher energy scale rather than the pole mass.


>>>

The **boosted top quark mass** is not simply the mass of the top quark "while it is moving"; rather, it is an important concept that arises when studying **high-energy collisions**, where the top quark is produced with a very large **momentum**. Understanding the boosted top quark mass has several significant benefits, especially in the context of experiments at colliders like the **Large Hadron Collider (LHC)**.

### 1. **Reconstructing Top Quarks in Boosted Regimes**:
- When top quarks are produced at very high energies, they become **highly boosted**. This means their decay products (a **W boson** and a **b-quark**) are emitted with high momentum and, as a result, are **collimated** (i.e., they travel very close together).
- This collimation makes it difficult to distinguish the individual particles in traditional analysis because the decay products can be reconstructed as a **single jet** (often called a "top jet").
- The **boosted top quark mass** is the mass reconstructed from this **single jet**, using advanced **jet substructure techniques** that disentangle the decay products from one another.

### 2. **Improved Signal Sensitivity**:
- **Boosted top quarks** are relevant in scenarios involving **very heavy particles**, such as searches for new physics beyond the Standard Model, where a new particle may decay into a pair of top quarks. In these cases, the top quarks are highly boosted due to the large mass of the parent particle.
- Analyzing the **boosted top mass** allows physicists to maintain high sensitivity to these events. The boosted regime is particularly useful because **backgrounds** are different compared to events with non-boosted tops, meaning that distinguishing signals from background can be optimized using specialized boosted reconstruction techniques.

### 3. **Jet Substructure Techniques**:
- The benefit of analyzing the **boosted top mass** is that it involves techniques that exploit the **substructure of jets**. This helps physicists determine whether a jet originated from a **single particle** (like a gluon or light quark) or from a **hadronically decaying top quark**.
- Reconstructing the boosted top mass accurately is crucial for applying **jet grooming techniques** (like **trimming**, **pruning**, or **filtering**) to reduce contamination from pile-up and other soft radiation. This leads to a more accurate identification of top quarks.

### 4. **Testing QCD and Mass Calibration**:
- In high-energy collisions, the boosted top quark mass helps in **testing QCD predictions** and understanding how quarks and gluons evolve into jets. The accurate reconstruction of the mass of highly boosted tops is important for tuning **Monte Carlo simulations** of QCD processes.
- Precise measurements of the top quark mass (even in boosted conditions) are essential for **calibrating** detectors and validating theoretical models. The top quark mass is a fundamental parameter of the Standard Model and has implications for the stability of the universe, electroweak symmetry breaking, and constraining other parameters in the Standard Model.

### 5. **Searches for New Physics**:
- The boosted top quark mass is especially useful for **searching for new physics**, such as **heavy resonances** that decay into top quarks. These new particles, which might exist at the **TeV scale**, would produce top quarks with high momentum, making them appear as boosted objects.
- Identifying a resonance through its decay products requires accurately reconstructing the boosted top mass. Without the correct boosted top mass reconstruction, it would be difficult to identify such signals over the background.

### Summary:
- The **boosted top quark mass** is important for reconstructing top quarks produced with **high momentum** at colliders, where their decay products merge into a single jet.
- It allows for **more efficient signal identification**, especially in searches for new, massive particles that decay to top quarks.
- Understanding the boosted top mass helps improve **background rejection** and ensures better sensitivity to potential **new physics**.
- **Jet substructure techniques** used to analyze boosted tops improve the reconstruction of the mass and help validate **QCD predictions** and models.

So, while the boosted top mass is indeed the mass of the top quark when it is produced with high energy, its significance lies in the unique reconstruction and analysis challenges and opportunities it provides in the context of high-energy particle physics experiments.

----


# Bell's inequalities:
#quantummechaincs 

Here’s a succinct explanation of **Bell's inequalities** and how they are violated, in simpler terms:
### Bell's Inequalities (Bullet Points):

- **Context**: Bell's inequalities were proposed by physicist **John Bell** in 1964 to test whether quantum mechanics or classical physics (specifically **local hidden variable theories**) can explain the behavior of particles in certain situations.
    
- **Local realism**: Bell formulated these inequalities under the assumption of **local realism**, which says that:
    
    1. **Locality**: Information or influences cannot travel faster than the speed of light (nothing can influence something else instantaneously).
    2. **Realism**: Particles have well-defined properties (like position or momentum) before we measure them, independent of our observations.
- **The experiment**: Bell's inequalities describe limits on correlations between measurements of two particles that were previously entangled (e.g., photons or electrons).<mark style="background: #FFB8EBA6;"> If the local realism model is true, these correlations should be bounded by certain mathematical limits (the inequalities).</mark>
    
- **Key result**: <mark style="background: #ABF7F7A6;">If these correlations are measured and found to exceed the predicted bounds of Bell's inequalities, then **local realism** (classical physics) must be wrong, and quantum mechanics must be correct in its predictions.</mark>
    

### Violation of Bell’s Inequalities:

- **Quantum mechanics** predicts that the correlations between measurements of entangled particles can **violate** Bell's inequalities.
    
- **Violation**: When experiments are conducted with entangled particles, the correlations often exceed the limits set by Bell’s inequalities, which **defies local realism**. This means that quantum mechanics is at play, and the outcomes of measurements on entangled particles seem to be **instantaneously linked**, no matter how far apart the particles are.
    

### Why it’s Important:

- The violation shows that **nature doesn’t follow classical intuition**. It suggests that **particles can be "entangled"**, meaning their properties are linked even when separated by vast distances, and the outcome of one measurement can instantaneously affect the outcome of the other, violating the principle of locality.
    
- **Conclusion**: The violation of Bell’s inequalities has been experimentally confirmed in many experiments, implying that **quantum mechanics** is correct and that **local hidden variables** (classical explanations) are not sufficient to explain quantum phenomena.
    

In simple terms, **Bell's inequalities** were a test to check if the behavior of particles could be explained by classical physics (where things have set properties before we measure them and can't affect each other instantly). Experiments showed that particles behave in a way that classical physics can't explain, showing the power of **quantum entanglement** and challenging our classical notions of reality.

---

# Higgs and Goldstone:

## 1. **Is the Higgs boson solely responsible for electroweak symmetry breaking (EWSB)?**

### Yes, as far as we currently know.

In the **Standard Model (SM)**:

![](/images/notes/Pasted image 20250326134219.png)
So currently, **the Higgs mechanism is the only known origin of EWSB**.

---

## 2. **Does the Higgs break any other symmetries?**

### Not within the Standard Model.

- The **Higgs field** is **not responsible** for:
    - **QCD confinement** or **chiral symmetry breaking** (that's dynamical and driven by strong interactions)
    - **Flavor symmetry breaking** (comes from Yukawa couplings, but these are inserted by hand)
    - **Grand Unified Theories (GUT)** symmetry breaking (if such exist, they'd need additional Higgs-like fields)

In **Beyond the Standard Model (BSM)** scenarios:

- Additional Higgs fields may break **extended gauge groups**, e.g., in:
    - **Left–Right symmetric models**
    - **GUTs** like SU(5), SO(10)
    - **Supersymmetry**, where there are **two Higgs doublets** H_u, H_d

But in the **minimal Standard Model**, the Higgs breaks only the electroweak symmetry.

---

## 3. **What is the difference between a _field_ and a _particle_?**

This is central. Here's the crisp distinction:

|Concept|Description|
|---|---|
|**Field**|A continuous entity that fills space and time; each kind of fundamental particle corresponds to a quantum field. E.g., the Higgs field, electron field, gluon field.|
|**Particle**|A quantized **excitation** (or ripple) in a field that has localized, detectable energy—what we see in detectors.|

### Analogy (without overusing water imagery):

- Think of a **guitar string**:
    - The **string itself** is the **field**.
    - The **note or vibration** you hear is the **particle**—a quantized mode of the field.

---

## 4. **So what exactly is the Higgs boson then?**

- The **Higgs field** permeates all space and acquires a non-zero vacuum expectation value (VEV).
- This VEV **breaks the electroweak symmetry** spontaneously.
- After symmetry breaking, **three components** of the Higgs field are "eaten" to give mass to W+,W−,ZW^+, W^-, Z via the **Higgs mechanism** (they become their longitudinal polarization modes).
- The **remaining degree of freedom** becomes a **physical scalar particle**: the **Higgs boson**.

So:

- **Higgs field**: the underlying quantum field responsible for mass generation.
- **Higgs boson**: a real, physical excitation of that field—what was discovered at the LHC in 2012.

---

## 5. **Where does interaction come in?**

Particles "interact" when their corresponding **fields are coupled** in the Lagrangian.

For example:

![](/images/notes/Pasted image 20250326134315.png)

These interactions define how particles talk to each other—how the **ripples of one field** influence or generate **ripples in another**.

---

## Summary

- The Higgs field is the sole source of electroweak symmetry breaking in the Standard Model.
- It gives rise to a physical Higgs boson: a quantized excitation of the field.
- Fields are the fundamental ingredients; particles are their observable excitations.
- Interactions are encoded in the **Lagrangian** through couplings between fields.

Before the electroweak symmetry is broken, the Higgs field contains **four real degrees of freedom**, and when it acquires a vacuum expectation value (VEV), **three of these degrees of freedom become Goldstone bosons**, which are then **"eaten" by the weak gauge bosons**.

![](/images/notes/Pasted image 20250326134348.png)

## 3. **Goldstone Bosons**

The Goldstone theorem says:

> For every broken **continuous global symmetry**, there's a **massless scalar mode**—a **Goldstone boson**.

In the **local gauge theory** (like the Standard Model), these **Goldstone bosons do not remain physical particles**. Instead, they are absorbed or "**eaten**" by the gauge bosons associated with the broken generators. This is the **Higgs mechanism**.

![](/images/notes/Pasted image 20250326134410.png)

![](/images/notes/Pasted image 20250326134420.png)

## Evolution of the universe along with the fields and EWSB:
#ewsb #higgs 


---

## Part 1: **What It Means to Attain a Vacuum Expectation Value (VEV)**

At its heart, a **VEV** is just the field settling into a **stable configuration**—a state of lowest energy. But in the case of the **Higgs field**, this state is not "empty"; it's **non-zero everywhere**, even in vacuum.

Here’s a visualization:

- Imagine a **field** as a landscape that stretches across all of space and time.
- At early times (e.g., at very high energies, right after the Big Bang), the field was sitting at a **symmetric point**, like a marble perfectly balanced on the top of a hill.
- This point—although symmetric—is **unstable**.
- As the universe cools down, the field "rolls down" the potential and **settles into a valley**—but this valley isn't at zero, it's at a **non-zero value** of the field.

That **settled, stable, non-zero value** is the **VEV** of the Higgs field.

---

## Part 2: **How This Breaks the Symmetry**

When the field was sitting at the top of the hill (before choosing a direction in the valley), the system had **full symmetry**—no direction was preferred.

But once it falls into a specific point in the valley (the vacuum state), **symmetry is broken**. The **laws** remain symmetric, but the **vacuum**—the field’s actual configuration—isn’t.

- Think of a circular table with pencils standing upright at every point (a symmetric configuration).
- But as soon as the first pencil tips and falls in a direction, **that direction becomes special**—the symmetry is broken, not by the laws, but by the state of the system.

---

## Part 3: **What Happens to the Gauge Bosons and Fermions**

Before symmetry breaking:

- **All particles are massless** in the electroweak theory.
- The gauge fields (W1,W2,W3,BW^1, W^2, W^3, B) are just four interacting force carriers.
- Fermions have **no mass** either; mass terms are forbidden by gauge invariance.

After symmetry breaking:

- The Higgs field’s non-zero VEV **interacts** with these fields.
- It essentially **“mixes”** with the gauge fields.
- Three components of the Higgs field become **Goldstone bosons**, and these are **absorbed** by the W+W^+, W−W^-, and Z0Z^0, giving them mass and an extra degree of freedom (a longitudinal polarization).

It’s as if the gauge bosons **swallowed** part of the Higgs field to become massive.

Meanwhile:

- The **fermions**, like the electron and quarks, couple to the Higgs field via **Yukawa interactions**.
- When the field takes on a VEV, those interactions become **mass terms**—the Higgs field “weighs” them down.

---

## Part 4: **Cosmic and GUT Picture**

Yes, in **Grand Unified Theories (GUTs)**, at extremely high energies (very early universe), **electroweak and strong forces were unified** into a larger symmetry group (like SU(5)SU(5) or SO(10)SO(10)).

In this era:

- All forces looked the same—no distinction between electromagnetism, weak, or strong.
- All gauge bosons were massless.
- Fermions were possibly part of higher multiplets.

As the universe cooled:

1. **GUT symmetry broke** (at ~101510^{15}–101610^{16} GeV):
    
    - Broken by some high-scale Higgs-like field.
    - Split the strong force off from the electroweak force.
2. **Electroweak symmetry broke** (at ~246 GeV):
    
    - Our familiar Higgs field took a VEV.
    - Split the weak and electromagnetic forces.
    - Gave mass to W±,Z0W^\pm, Z^0, and all fermions (except the photon and gluons).

The photon remains massless because **the electromagnetic U(1)EMU(1)_{\text{EM}} is unbroken**.

So, yes—**there was a hierarchy of symmetry breakings**. At each stage, the universe became less symmetric but more structured.

---

## Part 5: **Historical Progression of Understanding**

### 1. **1950s–60s:**

- The idea of **spontaneous symmetry breaking** came from **condensed matter physics** (e.g., superconductivity).
- **Goldstone’s theorem** (1961): whenever a continuous symmetry breaks, massless bosons appear.

### 2. **1964:**

- **Higgs**, **Brout–Englert**, and others proposed that **in gauge theories**, the Goldstone bosons can be **“eaten”** by gauge bosons to become massive. This was revolutionary.

### 3. **1970s:**

- **Weinberg, Salam, and Glashow** built the **electroweak theory** using this mechanism—Higgs field giving mass to W,ZW, Z while keeping the photon massless.

### 4. **1980s–2000s:**

- Indirect confirmation of the theory through precision electroweak measurements.
- But **no direct observation of the Higgs boson**—it remained hypothetical.

### 5. **2012:**

- **Higgs boson discovered at the LHC**.
- Confirmed the **central pillar** of the Standard Model: that the vacuum itself contains a **non-zero field** whose presence gives structure to everything.

---

## Final Picture

- The Higgs field is **not a rare ripple**, but a **cosmic background** present everywhere.
- The Higgs boson is a **localized excitation**—a ripple in that field.
- The fact that **mass arises** from interaction with this field means **mass is not inherent**, but **emergent**—it comes from **how particles relate to the vacuum**.
- This entire structure was built gradually—through theoretical insight, experimental hints, and finally discovery.


## 1. **What does it mean for the field to “roll down” if it stretches everywhere?**

Yes, the Higgs field stretches across all of space, but **its value at each point** determines the **energy state** of the system.

- "Rolling down" refers to the **field’s configuration** evolving with time.
- After the Big Bang, the field was sitting at a **high-energy, symmetric point** (like the top of a hill in its potential).
- As the universe cooled, the field **relaxed into its minimum energy configuration**—the bottom of the potential valley, but **not at zero**.
- So, the **value of the field everywhere changed**—like the entire landscape settled into a new shape.

It’s not that the field moved through space, but that its **uniform background value changed**—from zero (symmetric) to a non-zero constant (asymmetric vacuum).

## 2. **Why did the Higgs have four components? Could there be more?**

Yes, it had **four components** because it's a **complex scalar SU(2)LSU(2)_LSU(2)L​ doublet**:

- A complex doublet has 222 complex numbers → 444 real degrees of freedom.
- This structure was **chosen** to allow symmetry breaking in a way that gives mass to the W±W^\pmW±, Z0Z^0Z0, and fermions, **while keeping the photon massless**.

**Could there be more?** Yes—many extensions of the Standard Model (2 Higgs doublet models, supersymmetry, GUTs) have **additional Higgs fields** with **more components**. But the minimal choice with 4 d.o.f. is sufficient to break the electroweak symmetry correctly.


## 3. **What does it mean that EM symmetry is unbroken?**

"EM unitarity unbroken" really means:

- The **U(1)EMU(1)_{\text{EM}}U(1)EM​** symmetry—governing electromagnetism—**survives** after electroweak symmetry breaking.
- This means:
    - The **photon remains massless**.
    - **Charge conservation** remains exact.
    - There’s **only one kind of photon**—the unbroken gauge boson of U(1)EMU(1)_{\text{EM}}U(1)EM​.

If this symmetry were broken:

- The photon would acquire mass (no long-range EM force).
- Electric charge wouldn’t be conserved.
- The world would be **radically different**—atoms wouldn’t form, chemistry wouldn’t exist.

**You wouldn’t have two kinds of photons**, but rather **no well-defined photon at all**—the electromagnetic interaction as we know it would dissolve.

## 4. **What does “localized excitation” mean? How do fields and particles relate?**

You're close with your bedsheet analogy. Let’s make it even clearer:

- A **field** is like a **bedsheet stretched across the universe**—it has a value at every point in space.
- A **localized excitation** (a "bump") is like a **temporary disturbance**—a ripple, a wave packet.

When we observe a **particle**, what we’re really observing is:

> A **localized, quantized ripple** in the corresponding field.

- When an **electron interacts** with a **muon**, it's their fields that overlap and **exchange excitations**—in this case, a **photon**.
- The photon is a **ripple in the electromagnetic field**.
- We never interact with a field directly—only with its **excitations**, which we call **particles**.

Yes, **Feynman diagrams** show us **what can happen** (possible interactions), but they hide the **continuous presence** of the underlying fields.

So:

> Fields are **the fabric**; particles are **the patterns that ripple across it**.



![](/images/notes/Pasted image 20250326142354.png)

![](/images/notes/Pasted image 20250326142407.png)


----


# Bit on helicity and chirality:

1. **A top quark isn’t “just” left or right**
    
    - A massive fermion field (like the top) actually has **two internal pieces**—a “left-chiral” part and a “right-chiral” part.
        
    - Think of these like two gears inside the same engine. Both exist at once, but only the left-chiral gear can mesh with the WW boson.
        
2. **Chirality (gears) vs. helicity (which way you’re spinning)**
    
    - **Chirality** is that internal label (left-gear vs. right-gear) that dictates which gauge forces it feels.
        
    - **Helicity** is whether the top’s spin is aligned or anti-aligned with its direction of motion—more like “which way is the engine pointing.”
        
3. **Why you don’t see “100% left-helicity” tops in ttˉt\bar t at the LHC**
    
    - **Production** (gluon fusion in QCD) doesn’t care about chirality or helicity, so it makes tops pointing both ways (unpolarized).
        
    - **Decay** uses only the left-chiral gear, but that doesn’t force the engine to have a particular pointing direction.
        
4. **Net result**
    
    - In ttˉt\bar t → bW bˉWbW\,\bar bW, each top still has both left- and right-chiral parts inside it, and its spin (helicity) is random.
        
    - What’s guaranteed is that whichever way its spin is pointing, the **decay vertex** always grabs onto the left-chiral part to emit the WW.
        



**Bottom line:**

- **Chirality** = internal coupling-gear (left or right), only left interacts with WW.
    
- **Helicity** = external spin-direction, set by how it was produced (QCD makes it mixed).
    

----