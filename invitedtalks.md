# Invited talks

## Day 1
### Deep variational free energy for hydrogen systems 
Xinyang Dong (Institute of Physics Chinese Academy of Sciences, Beijing, China)

Hydrogen, being the first element in the periodic table, is the most abundant elements in the Universe. Dense hydrogen systems exhibit a variety of fascinating physical phenomena, including liquid-liquid transition and metallization. Accurate prediction of the phase diagram of dense hydrogen has long been a challenge for computational methods.

In this talk, I will present a neural network-based deep variational free energy approach to address the liquid-liquid phase transition problem in dense hydrogen systems. This method combines a deep generative model, normalizing flow, with a fermionic electron wave function neural network. The joint optimization of these two neural networks enables accurate calculation of the variational free energy. Using this approach, our results indicate that the phase transition point shifts to higher density comparing to those predicted by Deep Potential molecular dynamics simulations.

### Vision Transformer Neural Quantum States for Impurity Models
Yi Lu (Physics department of Nanjing University, China)

We employ an adapted Vision Transformer (ViT) to model quantum impurity models, optimizing it with a subspace expansion scheme in the natural-orbital representation that outperforms conventional variational Monte Carlo in both accuracy and efficiency. Benchmarks against matrix product states in single- and three-orbital Anderson impurity models show that ViT-based neural quantum states achieve comparable or superior accuracy with far fewer variational parameters. We also compute dynamical quantities using by introducing a restricted excitation space, yielding accurate core-level X-ray absorption spectra. These results highlight the potential of ViT-based neural quantum states for efficient and accurate modeling of quantum impurity models.

### Variational autoregressive networks and its applications in statistical physics and quantum error-correcting codes
Pan Zhang (Institute of Theoretical Physics, Chinese Academy of Sciences, China)

In this presentation, Pan Zhang will introduce the variational autoregressive network (VAN) and its applications in the field of statistical mechanics. VAN leverages autoregressive neural networks to construct a normalized variational distribution across numerous discrete variables, with the objective of minimizing the variational free energy through policy gradients. In the realm of equilibrium statistical physics, VAN demonstrates its prowess by closely approximating the target Boltzmann distribution and accurately estimating the free energy. When addressing non-equilibrium statistical mechanics, VAN adeptly simulates the temporal progression of the joint distribution governed by a master equation. Pan Zhang will also showcase a recent work, qecGPT, which adapts the VAN framework to tackle Bayesian inference challenges encountered in the decoding process of quantum error-correcting codes.


### Applications of quantum computation and tensor networks to lattice gauge theory
Etsuko Itou (YITP, Kyoto University, Japan)

In recent years, numerical analyses for lattice gauge theories using quantum computation and tensor network have attracted much attention among high-energy physicists as an alternative to lattice Monte Carlo methods. In this talk, I would like to discuss what kind of models and physical observables we aim to calculate and what we are now able to do.

### Theory to Enable Practical Quantum Advantage
Bálint Koczor (University of Oxford, UK)

Quantum computers are becoming a reality and current generations of machines are already well beyond the 50-qubit frontier. However, hardware imperfections still overwhelm these devices and it is generally believed the fault-tolerant, error-corrected systems will not be within reach in the near term: a single logical qubit needs to be encoded into potentially thousands of physical qubits which is prohibitive.

Due to limited resources, in the near term, hybrid quantum-classical protocols are the most promising candidates for achieving early quantum advantage and these need to resort to quantum error mitigation techniques. I will explain the basic concepts and introduce hybrid quantum-classical protocols are the most promising candidates for achieving early quantum advantage. These have the potential to solve real-world problems---including optimisation or ground-state search---but they suffer from a large number of circuit repetitions required to extract information from the quantum state. I will finally discuss areas where quantum computers may have the potential to deliver advantage in the near term.

### Electronic structure simulations beyond the reach of exact diagonalization with quantum-centric supercomputing
Mario Motta (IBM Research Almaden, USA)

We present [1] quantum computations of electronic structure that go beyond problem sizes amenable to current state-of-the-art exact diagonalization. Our results are obtained in a quantum-centric supercomputing architecture, using 6400 nodes of the Fugaku supercomputer to assist an IBM Heron quantum processor. We simulate the N2 triple bond breaking in a correlation-consistent cc-pVDZ basis set, and the active-space electronic structure of methyl-capped [2Fe–2S] and [4Fe–4S] clusters, using 58, 45 and 77 qubits respectively, with quantum circuits of up to 10570 (of which 3590 are 2-qubit gates) quantum gates.

[1] https://arxiv.org/abs/2405.05068"



## Day2

### Spectroscopy and complex-time correlations using minimally entangled typical thermal states
Alexander Wietek (Max Planck Institute for the Physics of Complex Systems, Germany)

Tensor network states have enjoyed great success at capturing aspects of strong correlation physics. However, obtaining dynamical correlators at non-zero temperatures is generically hard even using these methods.

Here, we introduce a practical approach to computing such correlators using minimally entangled typical thermal states (METTS). While our primary method directly computes dynamical correlators of physical operators in real time, we propose extensions where correlations are evaluated in the complex-time plane. The imaginary time component bounds the rate of entanglement growth and strongly alleviates the computational difficulty allowing the study of larger system sizes.

To extract the physical correlator one must take the limit of purely real-time evolution. We present two routes to obtaining this information (i) via an analytic correlation function in complex time combined with a stochastic analytic continuation method to obtain the real-time limit and (ii) a hermitian correlation function that asymptotically captures the desired correlation function quantitatively without requiring effort of numerical analytic continuation. We show that these numerical techniques capture the finite-temperature dynamics of the Shastry-Sutherland model - a model of interacting spin one-half in two dimensions.

### Quantum simulation of strongly correlated electrons through spin-coupled initial states
Daniel Marti-Dafcik (University of Oxford, UK)

The performance of quantum algorithms for eigenvalue problems, such as computing Hamiltonian spectra, depends strongly on the overlap of the initial wavefunction and the target eigenvector. This limits the power of quantum computers for solving challenging quantum chemistry problems, as typical initial states with a simple description have an overlap with the target Hamiltonian eigenstate that diminishes exponentially in the number of strongly correlated electrons.

In this talk, we present a framework for understanding and approximating the low-energy wave functions in strongly correlated molecular systems in terms of a few spin-coupled states that are highly entangled but highly structured. We also provide efficient quantum circuits for initial state preparation. Our approach avoids the need for expensive classical or quantum heuristics. Instead, we exploit symmetries to directly encode the dominant entanglement structure of the simulated system on quantum computers. For a range of popular quantum algorithms, including quantum phase estimation and several variational quantum algorithms, we demonstrate that using spin-coupled initial states drastically reduces the quantum resources required to compute strongly correlated ground and excited states.

### Computing solution space properties of combinatorial optimization problems via generic tensor networks
Jin-Guo Liu (Hong Kong University of Science and Technology, China)

We introduce a tensor network based framework to analyse the solution space of a broad class of combinatorial optimization problems and probabilistic inference problems. We show how these tools can help the scientific discovery in the field of quantum computation.


## Day3
### Recent Developments in Applications of Quantum Computing to Chemistry and Materials Science
Róbert Izsák（Riverlane, UK)

Riverlane focuses on quantum error correction and fault-tolerant algorithms, prioritizing the development of algorithms for chemistry, material science and fluid dynamics applications. This contribution will provide a summary of the most relevant of our papers published in the last three years, including those on embedding, the cost analysis of pharmaceutical and solid-state algorithms, electron correlation, the adaptation of classical techniques, such as the projector augmented wave method, to quantum computers, first-quantization-based methods and some of our work on early fault tolerant algorithms. If time allows, fluid dynamics applications will be mentioned. Finally, some conclusions will be drawn on the trends and prospects of quantum computing in these application areas.

### Discontinuous Galerkin Hartree-Fock calculations for predicting accurate electronic structures of mesoscopic-scale metal-semiconductor junctions with millions of atoms
Wei Hu (University of Science and Technology of China, China)

The evaluation of the exact Hartree-Fock exchange in hybrid density functional theory (DFT) is a crucial ingredient for accurately predicting electronic structures in molecules and solids. However, its application is currently limited to 5K atoms on leadership supercomputers due to its ultra-high computational complexity O(N4).

Herein, we propose a new discontinuous Galerkin Hartree-Fock (DGHF) method for large-scale hybrid functional electronic structure calculations. We present a massively parallel DGHF implementation on exascale supercomputers to reduce the high computational scaling of constructing the HFX matrix from O(N4) to O(N). We showcase how DGHF can be used to predict accurate electronic structures of complex metal-semiconductor junctions with 2.5M atoms (17.2M electrons) using 35.9M cores on exascale Sunway supercomputer. This is the first time high-accuracy hybrid functional electronic structure calculations enable us to simulate next-generation electronic devices at mesoscopic scale (200 nm).


### Recent progress with iPEPS: layered systems, incommensurate order, and spectral functions
Philippe Corboz (University of Amsterdam, Netherlands)

Infinite projected entangled-pair states (iPEPS) have become a state-of-the-art tool to study strongly correlated systems in 2D. In this talk, I report on recent progress in extending the iPEPS toolbox: (1) Simulation of weakly coupled 2D layers, with applications to SrCu2(BO3)2, (2) extensions to states with incommensurate spin-spiral order, enabling an unbiased study of the quantum spin liquid phase in anisotropic triangular lattice Heisenberg model, and (3) the computation of spectral functions based on the iPEPS excitation ansatz and real-time evolution.

### Decomposing imaginary time Feynman diagrams via sum-of-exponentials approximation
Jason Kaye (CCQ, Flatiron institute)

I will describe a new algorithm to evaluate imaginary time Feynman diagram integrals of low to intermediate order with controllable, high-order accuracy, and at low temperatures. The central idea is to approximate certain factors in the integrand as sums of exponentials, and use separation of variables to decompose the multiple integrals into sequences of nested one-dimensional products and convolutions, which can be computed efficiently using the discrete Lehmann representation. As a first application of the idea, I will focus on the bold hybridization expansion of a quantum impurity model. I will also discuss the AAA algorithm for rational approximation, which in this case is used to obtain compact sum-of-exponentials approximations of hybridization functions, but which may be more broadly useful in the problem of fitting spectral densities by sums of simple poles.

## Day4
### Numerical Effective Field Theory Approach to the Many-Electron Problem
Kun Chen (Institute of Theoretical Physics, Chinese Academy of Sciences, China)

We present a novel approach to the many-electron problem, combining effective field theory with advanced numerical techniques. Our method introduces renormalized perturbation theory from high-energy physics to establish a rigorous framework for describing low-energy electron physics in materials. Key algorithmic innovations, including a compact representation of imaginary-time Green's functions and efficient calculation of high-order renormalized Feynman diagrams, overcome computational challenges associated with Fermi surface field theories. This approach has yielded unprecedented accuracy in computing electron gas quasiparticle properties, particularly the two-electron scattering amplitude. We leverage these results to analyze the space-time structure of two-electron correlations, focusing on both particle-hole and particle-particle channels. The particle-hole channel analysis provides a precise parameterization of Fermi liquid quasiparticle interactions, crucial for understanding material transport properties. The particle-particle channel investigation yields accurate data for parameterizing the effective Coulomb interaction between Cooper pairs—the Coulomb pseudopotential in the Eliashberg equation—essential for computing transition temperatures of sub-Kelvin superconductors. Our work advances fundamental understanding of electron correlations and offers valuable new inputs for ab initio methods in real materials.


### Thermal pure matrix product state in 2D: tracking thermal equilibrium from paramagnet down to the Kitaev spin liquid state
Matthias Gohlke (Okinawa Institute of Science and Technology Graduate University, Japan)

We show that the matrix product state (MPS) provides a thermal pure quantum state (TPQ) representation in equilibrium in two spatial dimensions over the entire temperature range. We start off by illustrating TPQ-MPS on the Kitaev honeycomb model as a prominent, non-trivial example hosting a quantum spin liquid ground state. Our method is able to qualitatively capture the double-peak in the specific heat. Then, application to other two-dimensional quantum systems will be discussed.

### Purification-based quantum simulations via clustering property
Hideaki Hakoshima (Osaka University, Japan)

Quantum simulators are being built to surpass the classical computers in studying quantum many-body phenomena, yet current technology still suffers from experimental limitations such as insufficient cooling and external noise.

To overcome this issue, we propose localized virtual purification (LVP) which exploits the geometrical locality of target systems. We perform rigorous analysis for the cooling of thermal states and error mitigation of ground-state simulation, and show that the LVP breaks current limitations. Our work bridges fundamental concepts in quantum many-body physics and practical quantum simulation, and thus provides a significant impact in condensed matter physics, statistical physics, and quantum technology.