---
title: "science_dump"
date: 2026-10-14
---


**Neural networks are universal approximators of continuous functions on bounded domains, provided they use a non-linear activation.** But in practice, universality does not imply practical tractability.
So, in essence they ARE, but not in practise.



**feed-forward networks**, where inputs flow one way through successive layers until the output. Other types of NN involve RNN (feedback loops), CNN (specialized FF nets with layers like pooling), Transformer (skip connections, attention). 



**Deep Sets** → Any function F can be broken down to $\rho$ times $\phi$, where $\phi$  acts on each variable:

![](/images/notes/Pasted image 20250916104608.png)

Permutative-free functions - sum, max, average etc.


Check **Boltzman's H-theorem** 



SM is built on local and global symmetries:
The **Standard Model (SM)** is built from a mixture of **local (gauge)** and **global** symmetries. The distinction is fundamental.

### **Local (gauge) symmetries — the backbone of the SM**

![](/images/notes/Pasted image 20250916105818.png)

The Higgs field and fermions are arranged in representations of these local symmetries; the principle of **local gauge invariance** determines their couplings.

---

### **Global symmetries — approximate or accidental**

In addition to the exact local gauge invariance, the SM Lagrangian has several **global symmetries**:

- **Baryon number (B)** and **lepton number (L):**  
    Classically conserved; not gauged. They are _accidental_ global symmetries of the renormalizable SM, but are broken by nonperturbative electroweak anomalies (sphalerons).
- **Flavor symmetries:**  
    In the absence of Yukawa couplings, the SM has a large global symmetry acting independently on each fermion flavor. Yukawas break these down, leaving only approximate global flavor symmetries.
- **Custodial symmetry:**  
    An approximate global SU(2)SU(2) symmetry in the Higgs sector, protecting the ρ\rho parameter.
- **Discrete symmetries:**  
    CP, C, and P are not fundamental global symmetries of the SM—they are violated in the weak sector.

---

### **Summary**

- **Local symmetries:** the gauge group SU(3)C×SU(2)L×U(1)Y. These are exact and define the interactions.
- **Global symmetries:** baryon number, lepton number, flavor rotations, custodial symmetry, etc. These are either accidental, approximate, or emergent at certain limits.



Under gauge transformations, Lagrangian is invariant.
Quantization of the gauge field gives rise to gauge bosons.

In QFT, each field - fermion, gauge, scalar - can be quantized to a harmoic oscillator, with modes. Each mode can have a ground state, like $\hslash$ w/2. Summing over all modes leads to $\inf$ vacuum energy.


**Physical insight:**

- Fields everywhere do have ground state energy.
- In lab physics we don’t see it because we can only measure changes.
- In cosmology, we _should_ see its gravitational effect, but we don’t — or rather, we see only a tiny remnant (dark energy) → cosmological constant problem.
The huge infinite energy from the fields should give a huge curvature to spacetime, something which doesn't happen.
"**Supersymmetry (SUSY)** is one famous idea: fermion and boson zero-point energies cancel almost exactly. But since SUSY is broken in nature, the cancellation is only partial." 

Bosonic oscillator: ![](/images/notes/Pasted image 20250916112728.png)


Fermionic oscillator: ![](/images/notes/Pasted image 20250916112742.png)

![](/images/notes/Pasted image 20250916112754.png)


![](/images/notes/Pasted image 20250916112846.png)


SUSY gets broken because we have never found any squarks, selectrons, sgluons etc. 


GTR has T = $\rho_{vacuum}$ $\times$ g, for vacuum, where $\rho$ is vacuum energy density. 
As the universe expands, you don’t “dilute” it — the vacuum energy density stays the same per unit volume → this comes from the relation above, directly. 



### Books for reading for semiconductors:

1. Chapter 9, Detectors in Particle physics - Georg Viehhauser, Tony Weidberg
2. Chapter 7-8, Introduction to Solid State Physics - Charles Kittel
3. Chapters 28-30, Solid state physics, Ashcroft & Mermin
4. Chapter 13 , Quantum physics of atoms, molecules, solids, nuclei and particles - Eisberg & Resnick
5. Chapter 11, Radiation detection and measurement - Knoll



-----

## Collider physics:

Need to put some things in perspective - especially the terms and techniques. 

Questions can also be asked w.r.to H->yy
![](/images/notes/Pasted image 20250919100631.png)




Read  on H-theorem #needsresearch 

Brazilian plot → yellow and green comes from colours of flag.

#### Luminosity bit:

nU-235 scattering xsec is ~1b.
For pp scattering, xsec ~$Z^{-2/3}$ = $235^{-2/3}$ = 0.03 b = 30 mb. 

Energy-length conversion-equivalence:
200 MeV =  0.1 fm 
This says that the strong interaction scale of QCD, ΛQCD ∼200 MeV is the same as the “radius” of the proton, rp ∼ 1 fm. And 1 fm radius means area of pp scattering would be pi.r2 = 3fm^2 = 0.03 b.

Elastic scattering
Inelastic 
Diffractive 

![](/images/notes/Pasted image 20250923105734.png)

Integrated luminosity are quantities like 25 fb−1 indicating, for
example, that 25 events of a process with a 1 fb cross section should have been produced.

Instantaneous luminosity is what you integrate over time to get the integrated luminosity
Both detectors have the same basic design (see Fig. 2): an inner detector close to
the beam line to measure tracks of charged particles, followed by an electromagnetic calorimeter
(ecal) which measures (mostly) the energy of electrons and photons, then a hadronic calorimeter
(hcal) which measures the energies of neutrons and protons, then at the outside a muon detector

 For example, on ATLAS, the region
closest to the beam line has a set of silicon pixel detectors. Outside of this is a semiconductor
tracker, also made of silicon, followed by a a transition radiation tracker. 

![](/images/notes/Pasted image 20250923110436.png)

Bit on rapidity and pesudorapidity:
![](/images/notes/Pasted image 20250923111538.png)

![](/images/notes/Pasted image 20250923111554.png)

For massive particles, differences in pseudorapidities are not boost invariant.

Since most particles of interest are essentially massless, energy and angle are
enough to reconstruct the momentum. Most particles deposit all their energy within the central
calorimetry system. 

In Drell-Yan, one can factorize the xsec, just from the lepton momenta. Factorization scale being $\mu$.

![](/images/notes/Pasted image 20250923114351.png)

Top pair production and decay:

![](/images/notes/Pasted image 20250923115605.png)



Gauge couplings:
Because the **Z-pole** (mZ≈91m_Z \approx 91mZ​≈91 GeV) is where:
1. **Precision data exist** — LEP and SLC produced enormous statistics of e+e−→Z→ffˉe^+e^- \to Z \to f\bar fe+e−→Z→ffˉ​.
2. **Electroweak couplings are cleanly accessible** — cross sections, asymmetries, partial widths directly encode gauge couplings.
3. **Renormalisation scale choice** — by convention, couplings are quoted at a reference scale; mZm_ZmZ​ is natural since it lies well above hadronic thresholds but below new-physics scales.

At low energies, many electroweak effects are tiny corrections on top of QED.  
At the **Z-mass**, the weak interaction is maximally visible: the Z boson can be produced _on shell_, and its decays directly probe the couplings of quarks and leptons. 
![](/images/notes/Pasted image 20250923131213.png)
![](/images/notes/Pasted image 20250923131435.png)
![](/images/notes/Pasted image 20250923131658.png)


#### Free parameters in SM:
![](/images/notes/Pasted image 20250923130811.png)


####  EFT:
Effective field theory is a method used to describe physical theories when there is a hierarchy of scales.
In BCS theory of superconductivity, the lattice vibrations are fields and the quanta are phonons.
Effective field theories are consistent theories where corrections can be calculated in terms of some expansion parameter.

Property:
- **Renormalizable QFT (old sense):** finite number of parameters, valid to arbitrarily high energies.
- **EFT:** not renormalizable in that sense, but **renormalizable as an expansion**, perfectly consistent and predictive below the cutoff scale.

For Fermi theory, the num of dim is 6. 
![](/images/notes/Pasted image 20250923134354.png)
![](/images/notes/Pasted image 20250923134327.png)

For processes with energy E≪mass of W, higher-dimension terms are suppressed like (E/M_W)^2.
So keeping only the dimension-6 term is an excellent approximation. At higher energies, you need full renormalizable theory  (EW SM with W bosons(?)).

In EFT, all sets of gauge invariant, dimension d operators, all non-redundant, form a basis. 
All bases are equivalent. 

Core idea of EFT:
![](/images/notes/Pasted image 20250923150208.png)


![](/images/notes/Pasted image 20250923152146.png)


#### Analogy ↔ Taylor expansion
![](/images/notes/Pasted image 20250923153756.png)


How the operators work? Operators are not arbitrary: they directly reflect  how the heavy thing would have interacted before you removed it from the theory.
Operators encode how the heavy particle would couple to the known SM fields.
- Example: a heavy boson that couples to two quarks and two leptons → after you integrate it out, you get a 4-fermion operator.
- Another heavy boson that couples to Higgs and gauge fields → you’d get a higher-dim operator modifying Higgs–gauge interactions.


Bringing it down to M scale:
![](/images/notes/Pasted image 20250923163454.png)

Dimensions:
![](/images/notes/Pasted image 20250923163528.png)

There's 1 dim-5 operator, and it violates lepton number conservation. 
So: _yes, an EFT can include operators that break conservation laws or symmetries — but then you are declaring those laws are only approximate._
Eg. - neutrino mass as dim-5 Weinberg operator, B# violation in GUTs, CP-violating phases beyond the CKM etc.

Okay this is kinda unrelated, but let's say:
Gauge invariance → internal labels don't matter.
Lorentz invarance → frame doesn't matter.

#### Forming the basis:
![](/images/notes/Pasted image 20250923164706.png)

Higgs actual, true, intrinsic width is about 4MeV, at mass 125 GeV. This is 100 times narrower than the reconstructed peaks, which have a resolution of about 1-2 GeV. 



####  Anomalous couplings:

In the SM, the strengths and forms of couplings (like photon–electron, W–quark, gluon–quark) are strictly fixed by gauge symmetry. If experiments saw deviations, we’d call them “anomalous couplings.”

They typically appear in **effective field theory (EFT)** descriptions of possible new physics. At low energies, heavy new particles are “integrated out,” leaving behind extra terms in the Lagrangian. These terms look like modified or extra couplings, suppressed by powers of the new-physics scale Λ.

So anomalous couplings are **signatures of physics beyond the SM**, not something the SM itself predicts.

![](/images/notes/Pasted image 20250926095057.png)

![](/images/notes/Pasted image 20250926095316.png)

In short:

- **CMDM** = anomalous magnetic-like coupling of top to gluons (CP-even).
- **CEDM** = anomalous electric-like coupling of top to gluons (CP-odd).  
    Both are clean probes of new physics and CP violation.


##### Relative equations:
![](/images/notes/Pasted image 20250926111523.png)

![](/images/notes/Pasted image 20250926111543.png)

![](/images/notes/Pasted image 20250926111611.png)

![](/images/notes/Pasted image 20250926111644.png)


####  CP violation
![](/images/notes/Pasted image 20250926161239.png)

###  Lamb shift:

the essence of the lamb shift is the small but
important energy difference between the 2S and 2P levels in
hydrogen atoms. according to the relativistic wave equation
of dirac these levels3 have exactly the same energy and hence
something new was needed. the experiment consisted of
observing directly, for the first time, the microwave induced
transitions from the 2S to the 2P state. in fact, due to the
virtual emission and reabsorption of photons, or alternatively
due to vacuum fluctuations as we discuss below, the electron
is not really a point particle. it is smeared out a bit and the
2S level is around 1000 mhz higher in energy (less tightly
bound) than is an electron in the 2P level.


![](/images/notes/Pasted image 20250928165356.png) 

Oh boy! There's so much to talk and write about... especially the things that people often refer to as knowledge definitely comes from something...

#####  Likelihood versus PLF: 
A simple likelihood treats these uncertainties as fixed and known, while the Profile Likelihood treats them as variables to be fitted, which is the "profiling mechanism."

##### Why NPs be Gaussian?
![](/images/notes/Pasted image 20250929115103.png)
Most measurements of systematics involve multiple cumulative effect of many small, independent sources of variation (e.g., detector component variations, calibration stability, beam conditions). The CLT states that the sum of a large number of independent random variables, regardless of the original distributions, will be approximately normally distributed.
- **In Practice:** By combining many small effects into one overall systematic uncertainty, the resulting error in the final model parameter is generally well-approximated by a **Gaussian constraint**.

Also, Gaussian has just 2 parameters, so it's simple for global likelihood function tracking.

In short, the Maximum Entropy Principle states that, given a set of known constraints (like the mean and the variance), the probability distribution you choose to model a system should be the one that is **maximally non-committal** or **least-biased** with respect to any other information.

![](/images/notes/Pasted image 20250929121015.png)

This term acts as a soft constraint, penalizing the total likelihood function if the fitted value of θ moves too far from the expected nominal value $θ_0$​, with the penalty governed by the Gaussian shape. This is precisely how a **Bayesian prior** functions to incorporate external knowledge.

By choosing the Gaussian as the prior π(θ), you are adhering to the principle of maximum entropy: You use all the information you have (the ±1σ uncertainty) and _only_ that information, thus introducing the minimum amount of bias into your statistical model.


###  Studying different processes:
What processes focus on what sectors of SM?
EW processes are crucial for measuring fundamental couplings, testing the SM's symmetry structure, and characterizing the Higgs boson and massive vector bosons (W,Z). They typically involve final states with leptons (ℓ±,ν) and/or photons (γ).

(QCD) processes are necessary to understand the force carriers (**gluons**) and the internal structure of protons (PDFs).

Drell Yan (Z/gamma and W production) with Final state (FS) leptons, l \nu etc. good for EW mixing angle, PDFs etc. Standard candle for absolute xsec normalisations.
Diboson production (FS yy, Wy, Zy, WW, ZZ) help with non-abelian nature of SM by measuring triple gauge couplings etc. which might have new physics. Also, H to ffbar coupling (Yukawa), H to VV couplings which are directly proportional to the mass of the V, also VEV derived from measurements of  W/Z masses.
V-H coupling (with WH, ZH) measure EW symmetry breaking mechanism.
EW symmetry restoration by VBS (WWjj, ZZjj etc.) for Higgs mechanism fully restore EW symmetry.


Jet production (dijet, multijets FS) for $\alpha_s$ and PDFs.
V-jets (yj, Zj, Wj FS) for cleaner probe to constrain PDFs and gluon density.
HF production (ttbar, bbar etc.) for top dominated strong processes. Helps understand QCD predictions at very high energies.
QGP (high multiplicity collisions from pb-pb) for theory of confinement and de-confinement, confirming thermodynamic predictions of QCD.

SU2 $\times$ U1 is also non-abelian. The key to a gauge theory being **non-Abelian** is that its force carriers (gauge bosons) **interact with each other**.

![](/images/notes/Pasted image 20250929135217.png)

##### Testing the EW symmetry breaking paradigms and processes:
In VBS for instance,  if the W and Z bosons were just massive without the Higgs (i.e., mass terms added by hand, breaking EW symmetry), the probability (cross-section) for two vector bosons to scatter off each other (**e.g., W+W−→W+W−**) would **increase indefinitely** at high energies, violating the principle of **unitarity** (probability cannot exceed 1). SM requires the Higgs boson to have a specific coupling strength to the gauge bosons that exactly **cancels out this unbounded growth**. The **cross-section for VBS** processes (e.g., WWjj, where W's scatter and produce two high-rapidity jets j) is measured. Confirming that this cross-section is flat or grows slowly (i.e., remains **unitary**) at TeV energies confirms that the W and Z boson longitudinal polarization interactions are successfully "tamed" by the Higgs boson, verifying the EWSB mechanism.

##### Scattering:
The entire mathematical framework used to calculate the probability of any given collision outcome is called the **S-matrix** (S stands for Scattering). Whether you are calculating the probability of two quarks bouncing off each other (elastic) or annihilating into a new particle (inelastic), the probability amplitude is calculated using the same fundamental scattering matrix formalism. Since every calculation is framed as a **scattering matrix element**, the resulting physical process is a "scattering."

##### Normalisation:
Nobserved = Lumi X xsec X A X e
A is acceptance i.e. fraction of events falling into the detector region.
e is efficiency i.e. fraction of accepted events that are properly reconstructed.

Lumi uncertainty is a part of the normalisation uncertainty too, it's the largest common scale uncertainty for all the xsec measurements. 

Differential measurements often are normalised to "isolate shape from scale". How?
1. Luminosity cancellation: the overall luminosity uncertainty (the ΔL/L term) cancels exactly when you divide the differential measurement by the total inclusive cross-section (σ).
2. Many theoretical uncertainties (like those from the choice of factorization and renormalization scales) are largely correlated between the numerator (dX/dσ​) and the denominator (σ). Dividing by σ minimizes these scale uncertainties i.e. (1\σ) dX/dσ​.
3. Similarly for PDFs and QCD showering and fragmentation etc in the simulation, which can also be removed. 


### Current
#### Field theory currents:
![](/images/notes/Pasted image 20251001113702.png)
Stems from symmetries; conserve quantities.

#### Interaction and then Experimental:
Gauge bosons W+- and Z couple to charged (and neutral ) weak currents.
When experiments talk about _charged-current interactions_ (via W) or _neutral-current interactions_ (via Z), they mean actual scattering processes where these theoretical currents appear as the source of the bosons exchanged.

![](/images/notes/Pasted image 20251001113856.png)

### Semiconductors:

Here’s a compact but structured rundown of homogeneous vs. inhomogeneous semiconductors, tracing the concepts historically to modern use:

Homogeneous semiconductors

- Historical roots: Early semiconductor theory (1930s–50s) treated crystals like silicon and germanium as uniform, with band theory describing charge carriers in a perfect periodic lattice.
    
- Concept: Material properties (band gap, effective mass, mobility) are spatially uniform. Doping is evenly distributed, so carrier density is constant across the sample.
    
- Physics covered: band structure and Bloch states (Kronig–Penney, effective mass theory); intrinsic vs. extrinsic conduction (n-type, p-type); carrier statistics (Fermi–Dirac, density of states); transport (drift, diffusion, recombination, generation).
    
- Modern view: Homogeneous models still form the baseline for device physics, e.g. bulk semiconductors, high-purity wafers, basic pn-junction theory.


Inhomogeneous semiconductors

- Historical step: With devices, it became clear materials are rarely uniform — interfaces, defects, and gradients dominate. By the 1960s–70s, semiconductor physics shifted to non-uniformity.
    
- Concept: Spatial variations in doping, electric fields, strain, or composition create non-uniform carrier densities and potentials.
    
- Key types: junctions (pn-junctions, Schottky barriers, heterojunctions); doping gradients (graded band gaps, diffusion profiles); defects and disorder (traps, recombination centers, localized states); nanostructures (quantum wells, wires, dots).
    
- Physics covered: Poisson’s equation plus continuity → space-charge regions, depletion, diffusion currents; transport dominated by interfaces (surface states, tunneling); device physics: diodes, transistors, solar cells rely on inhomogeneous structures.
    
- Modern view: Inhomogeneity is now engineered deliberately — epitaxy, heterostructures (GaAs/AlGaAs, GaN/SiC), strain engineering, 2D materials with moiré patterns.


Summary ladder:  
Homogeneous → uniform bulk properties → foundation of band theory, intrinsic/extrinsic conduction.  
Inhomogeneous → spatial variation → basis of real devices and modern nano-/optoelectronics.

---


Look also into Chiral anomalies, gauge anomalies etc.

![](/images/notes/Pasted image 20251002100559.png)

![](/images/notes/Pasted image 20251002101047.png)

![](/images/notes/Pasted image 20251002102221.png)



**Global symmetry:** transformation is same everywhere.

$$\psi(x)\rightarrow e^{i\theta}\psi$$
**Local symmetry:** transformation varies from point to point.
$$\psi(x)\rightarrow e^{i\theta(x)}\psi$$

To make physics consistent under this freedom, you are _forced_ to introduce a gauge field that compensates for the local variation. **Local symmetry**: “Each player can choose their own local rules, but then a referee (gauge boson) must exist to ensure consistency.” → Leads to forces.
So: **global symmetries give you conservation laws; local symmetries give you forces.**

Unitary - given at a specific time, we have set of events with probabilities, we can add all sets of probabilities up and it should result in 1. Given another time, the events can scramble among each other to some other form, but the total probability of 1 is still conserved. $U^{\textdagger} U = 1$ 
So probability conservation is guaranteed if the evolution is controlled by the unity operator.

Poincare invariance, causality and locality - all of these should be conserved as well in physics.
**Particle** - minimal building block of any Poincare invariant phenomena. Mass, Spin, Charge...
> **Symmetry** - set of transformations under which physics does not change.
> Transformations → linear or anti AND unitary
> physics unchanged - invariant VS covariant
> Apart from time translation, spatial translation and rotational, there's the Lorentz invariance which takes into account frames. All of these can be encapsulated into the Poincaré invariance.
> Set of Poincaré transformations makes what is called a **Poincaré Group**.
> E.g. → Under any set of transformations, mass-squared and spin-squared do not change. 
> So a **particle**, which is minimal building block of Poincaré invariant phenomena, is irreducible representation of the Poincaré Group - minimal states with well-defined transformation properties.

So Poincaré invariance+Cauality+QM → **QFT** 
Under QFT, local fluctuations of a field are identified as the particles. 
![](/images/notes/Pasted image 20251002154527.png)
At around 200 MeV, the interaction just blows up → confinement.
![](/images/notes/Pasted image 20251002154837.png)
At higher E, the global symmetry G follows. The experimental observations of mesons also showed that they follow a SU(3) symmetry. 
The jump from G to confinement to only $SU(3)_{V}$ remaining there happens through something called the SSB → Higgs(?)...


"Global gauge invariance implies via Noether’s theorem the existence of a conserved current. Local gauge invariance requires the introduction of massless vector gauge bosons, fixes the form of the interactions of gauge bosons with sources and implies interactions among the gauge bosons in case of non-Abelian symmetries." 

The symmetry of a Lagrangian is called spontaneously broken if the Lagrangian is symmetric but the physical vacuum does not conserve the symmetry.

###  Energy to distance:

E (eV) = 1240 / $\lambda$ (nm)

For E = 12 TeV, $\lambda = 10^{-19}$ m = $\frac{1}{10,000}$ proton

![](/images/notes/Pasted image 20251002113604.png)

This quote I like - "Big bang is the parameterization of humanity saying I don't know what happened."

1 eV = 11,600 K

1 MeV = 11,600 X 1,000,000 = 11.6 $\times 10^9$ K 

### About ATLAS - from DK's expHEP book:
![](/images/notes/Pasted image 20251007100202.png)

![](/images/notes/Pasted image 20251007102018.png)

![](/images/notes/Pasted image 20251007121436.png)

Electromagnetic calorimeters measure the energy of electrons and photons as they interact with the electrically charged particles in matter. Hadronic calorimeters sample the energy of
hadrons as they interact with atomic nuclei. Calorimeters can stop most known particles except muons and neutrinos.

Jets: - Infrared safety means that the addition of a soft gluon should not change the results of the jet clustering. Collinear safety implies that splitting one parton into two collinear partons should not change the results of the jet clustering.

![](/images/notes/Pasted image 20251007142423.png)

Apart from the constituents mentioned above, **particle flow objects** are also used at inputs for jet forming, for example in the CMS experiment. The idea is to use (charged particle) tracks as they have better angular resolution. **The tracks are matched with energy clusters in the calorimeter, and calorimeter signal associated with tracks are fully (whole cluster) or partially (cells from cluster) removed.** Then the **inputs to jet forming are the charged (matched and unmatched tracks) and the neutral (original or modified clusters) particle flow objects.** Once constructed, jets are treated as any other physics objects present in an event. While the jet axis determines the direction of the jet, and the four-vector combinations during the jet clustering give its pT, a few other properties of jets are worth mentioning.
#### Steps of jets:
![](/images/notes/Pasted image 20251007162137.png)


For Ghost-matching, to know which tracks are inside a jet, **Ghost association** provides a correct matching of tracks to calorimeter jets. In this technique, tracks are treated as infinitesimally soft, low pT particles by scaling their pT by a very small number, such as 10−100. These tracks are then added to the list of inputs to the jet algorithm. The low scale implies that the tracks do not affect the reconstruction of jets. However, after the jets are formed, it is possible to identify which tracks were clustered into which jets.
**Ghost matching** is used when associating **tracks or truth particles** to **reconstructed jets** (e.g., for flavor tagging or efficiency studies).

So ghost matching doesn’t _detect_ anything — it’s a **classification tool** in simulation.
b-tagging is **a reconstruction and identification algorithm**, not a labeling method.

Calibration of jets:
![](/images/notes/Pasted image 20251007160734.png)

Isolation and identification:
Isolation usually done using sum of energy or pT in a cone around object with specific radius of 0..1 or 0.4.. - demanding the value to be smaller than a threshold. 
Calorimeter-based isolation is more sensitive to the surrounding particle activity because it measures the energy of both neutral and charged particles. Track-based isolation, on the other hand, can only protect against the charged particle component, but it is more robust against pile-up, as tracks can be associated with the primary vertex.
Identification comes from identifying objets, as below, ...
![](/images/notes/Pasted image 20251007161707.png)
... and then applying efficiencies and SFs.
 (SF = **eff_Data** (tag-probe of Z->l+l-) / **eff_MC** (truth-matching ))

##### Produced particles at LHC:
![](/images/notes/Pasted image 20251007164330.png)

Why ggF dominates in LHC? momentum is dominated by **gluons** at small Bjorken-x (higher energies). **gluon parton distribution functions** are large in this regime, so even though the QCD coupling is moderate, the **gg initial state overwhelmingly dominates** hard interactions. Essential for higgs, ttbar etc.
Inside the proton, as energy increases:
- The **gluon density** (number of gluons per unit xxx) rises steeply due to QCD radiation.
- Quarks still carry momentum, but are far fewer at low xxx.
At low x, g(x) is more. 
![](/images/notes/Pasted image 20251007170013.png)
![](/images/notes/Pasted image 20251007170759.png)


Check:
- BD, AMD, JH, AK's theses - chatllm
- guido bell lectures
- More about the Ratio, also maybe top review...
- SM theory 
- Particles Data group - feynman, BR, etc.
- Own thesis
- Statistical part
- BDTs
- Other experiments
- ~~YT videos - QCD, floathead physics~~
- General physics topics and processes 
- ATLAS lecture series
- Solid state and related things... 
- chatgpt chats
- Cross sections and luminosities...
- Check answers for comments on analysis.
- ~~Higgs discovery and feynman diagrams~~
- Revise everything
- ~~Z/ and gamma prime particles~~
- LO and NLO expansions...
- Correlation coefficients
- Think on the questions from katharina on slides,  Markus - bkg, how it will rise, how to cut it off, etc. 
- A bit of DM, cosmology, forbidden and sudakov conditions for CP-violation etc.
- CMS results, what can cms do differently for these processes - ttyy etc. 
- ~~Elisabeth asked - why not tyy studied?~~ 
-  check top-photon lagrangian for tty and ttyy(if exists in any paper) → check their relation with top-gluon eft
- check the meaning of all the MC parameters
- Lhc phy, top phys, bjorken scaling, pdf, bsm, lagrangian, fitting, systematic impacts, higgs, all formulae, ml and bdt, basic master ques, calculate xsec, relativistic stuff, sensors and stat. uncertainties etc. for pixel sensors.
- LHC beams and splashes etc. 
- sipm & unfolding

### renormalizability versus regularization:
![](/images/notes/Pasted image 20251009133631.png)

In short:
![](/images/notes/Pasted image 20251009134002.png)




#### CMS improvement on results:
CMS can approach or improve upon an ATLAS ttˉ+γγ search mainly through its **fine calorimetry and combined tracking-calorimeter reconstruction**, which give better **photon and lepton purity**, sharper **energy and angular resolution**, and hence a cleaner **rare-event signal** in a statistics-limited environment.
CMS also reconstructs **converted photons** (those that turn into e+e−e^+e^-e+e− pairs) efficiently, which helps categorize photons and improve purity.
CMS tracks and calorimeter clusters are **combined particle-by-particle** (“particle-flow”): this improves how photons are isolated from nearby hadronic activity and makes energy calibration more accurate in high pileup.
**CMS calorimeter (PbWO₄ crystals)** has **excellent energy resolution** for photons and electrons.  
This allows slightly sharper invariant-mass and transverse-momentum measurements for photons.
Misidentified jets (as photons) much better.
Jet→photon and electron→photon **misidentification rates** can be measured directly from control samples (e.g., Z→ee), thanks to good tracking and ECAL matching.
![](/images/notes/Pasted image 20251009134940.png)


### Types of particles:
![](/images/notes/Pasted image 20251009142331.png)

![](/images/notes/Pasted image 20251009182819.png)





--------------



2026-08-25 09:58

Forward modeling is the process of using theoretical equations and known system parameters to **simulate future behavior, predict system states, or generate synthetic observable data**. - astronomy, such as extraction of entended structures in space...
**Missing image:** Pasted image 20260825100152.png|319
https://iopscience.iop.org/article/10.3847/1538-4357/aaa1f2#apjaaa1f2s2
- Related to non-negative matrix factorization theorem 
  > W X H = V (non-negative numbers)
  > self modeling curve resolution (along the high-low edges)
  > NMF → basis of other special cases like PLSA (semantic document indexer), clustering algorithms etc. So NMf is general case.
  > **Missing image:** Pasted image 20260825100835.png|205

**Missing image:** Pasted image 20260825104643.png|378



Precision and Recall:
Based on **relevance**. Recall → same as sensitivity. 
**Missing image:** Pasted image 20260825111855.png|230

**Missing image:** Pasted image 20260825112146.png|139true positives over all positives/negatives
**Missing image:** Pasted image 20260825125947.png|250 true over all

**Missing image:** Pasted image 20260825130047.png|307

IA - **intelligence amplification** or **cognitive augmentation** → steps to improver overall cognitive accuracy (propensity of cognitive process to produce *desired* result) and cognitive precision (propensity of cognitive process to produce *same* result). #developing

Sense making  - coming up with frameworks
Thoughts influence memory 
Languages can help articulate thoughts (help with thinking through them), but can also obstruct them (let's say when you think you know a concept but can't find the right word for it).
**Missing image:** Pasted image 20260825131009.png|469

**Cohen's kappa** (no universal agreement on baselines standards) - used to measure interrelatedness of categorical data - say how much do reviewer 1 and reviewer 2 (independently) agree/not on candidates applying for a job.
**Missing image:** Pasted image 20260825134730.png|512
Augmented data - boostrapping methods - jackknife methods of replacing 1 data point at a time (linear form of bootstrapping).

**Missing image:** Pasted image 20260825135402.png|504
https://pmc.ncbi.nlm.nih.gov/articles/PMC6941312/#Sec2
**Missing image:** Pasted image 20260825135433.png|367

<mark style="background: #FFB8EBA6;">Moral of the story : confusion matrices are better suited to show actual correctness of the classifier/predictor over f1 scores, recall, precision etc. Lots of empirical evidences to support this.</mark>

#resources  https://www.geeksforgeeks.org/machine-learning/confusion-matrix-machine-learning/
![](/images/notes/Pasted image 20260825135720.png)


**Missing image:** Pasted image 20260826090834.png|524
**Shadowgraphy** - related to schlieren phtography.

### optimal transport in ML:
#developing  #needsresearch 
https://arxiv.org/pdf/2505.06589
Modern machine learning repeatedly manipulates probability measures: empirical datasets, generated samples, latent distributions, class-conditional laws, particle systems, parameter distributions of wide networks and attention patterns. **Optimal transport is useful in this setting because it compares such objects by asking how mass should move.** It combines a statistically meaningful discrepancy with a geometry of interpolation, dual certificates and variational dynamics, making OT a common language for losses, generative modeling, domain adaptation, robust learning, barycenters, gradient flows and mean-field descriptions of learning algorithms.  #maths 
OT - statistical discrepancies into learning algos. Finding **effective Distance**(s) between actual and predicted classes, tldr.
**Missing image:** Pasted image 20260826201714.png|355
transporting (T func) from red to blue distribution (two distinct masses at different x,y). The deal is to minimize the **cost** of transport.

<mark style="background: #ABF7F7A6;">At its core, machine learning focuses on making comparisons between complex objects. To properly measure these similarities, a metric is needed, which is a distance function. Optimal transport is a natural tool in this case, as it is concerned with efficient distance functions (e.g. the Wasserstein metric).</mark>

#limitations majorly of distances. OT provides broader, more general distinction functions.
**Missing image:** Screenshot 2026-08-26 at 20.20.50.png|525
https://alexhwilliams.info/itsneuronalblog/2020/10/09/optimal-transport/

**Missing image:** Pasted image 20260826202416.png|570**Missing image:** Pasted image 20260826202433.png|528

After applying constraints and BCs on T, integrate it across total amount and cost per unit of transport:
**Missing image:** Pasted image 20260826202532.png|531
> extensions involve into using shannon entropy (from principal of maximum entropy selection rule) into OT, which results in better (transport based) confusion matrices. 
> **Missing image:** Pasted image 20260826203722.png|316

Anomaly detection using repeated partitioning of dataset to find out the anomalies (which are few and different, therefore easy to spot), using **isolation** **trees** (faster than conventional profiling methods based on priors etc.). chep chep chep paritition maarooo!!
**Missing image:** Pasted image 20260826205121.png|172

numpy.ravel() convert to 1D flattened (more efficient than flatten() which creates a copy).
**Missing image:** Pasted image 20260826203250.png|375

---
2026-08-27 10:57

#### Semi supervised (weakly supervised):
Much of human **concept learning** involves a small amount of **direct** instruction (e.g. parental labeling of objects during childhood) combined with large amounts of **unlabeled** experience (e.g. observation of objects without naming or counting them, or at least without feedback).
Infants can infer more, depending on the strength of the thing shown. Show them a picture of dog, they can infer other unlabeled dogs and wolves maybe(?) in the real world. 


Infants and children take into account not only unlabeled examples, but the sampling process from which labeled examples arise.
#philosophy #Digression 
*transductive* - reasoning from observed **specific training** to **specific test** datasets.
*inductive* - reasoning from observed **specific training** to **general rules**.







