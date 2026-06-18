# Showing new listings for Thursday, 18 June 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 7papers 
#### Reconstructing Galactic Gravitational Potentials from Stellar Kinematics with Physics-Informed Neural Networks
 - **Authors:** Charlotte Myers, Nathaniel Starkman, Lina Necib
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2606.18386

 - **Pdf link:** https://arxiv.org/pdf/2606.18386

 - **Abstract**
 The gravitational potential of a galaxy encodes its mass distribution, formation history, and dark matter halo structure. Accurate potential models are therefore critical for interpreting stellar kinematics, orbital dynamics, and the influence of satellite systems like the Large Magellanic Cloud. Analytic potential models offer interpretability and efficiency but struggle to capture complex, non-axisymmetric structure and time-dependent perturbations. Neural network-based methods can capture this complexity but offer little interpretability. We introduce a physics-informed neural network (PINN) framework that combines data-driven learning with embedded physical constraints, available as the open-source package GalactoPINNS. Trained on acceleration measurements, the framework captures complex, small-scale features while preserving global physical consistency. We test on systems of increasing complexity, from controlled analytic halos to cosmological simulations of Milky Way-like galaxies, achieving sub-percent acceleration errors with orbit reconstruction that consistently outperforms analytic baselines. Additionally, we implement a Bayesian neural network to provide spatially calibrated uncertainty estimates, and a time-dependent extension to capture smooth temporal evolution. By treating an analytic model as a structured prior and learning corrections on top of it, the method retains physical interpretability while gaining the flexibility to represent realistic galactic potentials, making it well suited for Milky Way modeling and dynamical inference in the era of current and upcoming large-scale surveys.
#### Impact of inhomogeneous curvature on growth rate measurements from magnitude fluctuations
 - **Authors:** Andrew Nguyen, Chris Blake, Hayley J. Macpherson
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2606.18437

 - **Pdf link:** https://arxiv.org/pdf/2606.18437

 - **Abstract**
 Our interpretation of current cosmological observations rests on the assumptions of homogeneity and isotropy, leading to uniform background curvature and expansion characterised by the Friedmann-Lemaître-Robertson-Walker (FLRW) spacetime metric. However, the large-scale structure of the Universe is non-uniform in detail, inducing inhomogeneous curvature and scale factor variations. In this paper, we use numerical cosmological simulations generated in full General Relativity to study the impact of inhomogeneous spacetime on the magnitude fluctuations of distant objects, focusing on their use as a probe of the growth rate of cosmic structure. We quantify the distortions in the magnitude correlation spectrum as a function of angular scale and redshift, and use these distortions to infer the systematic offset in the growth rate measurement. We find that at $z \lesssim 0.2$, the systematic offset in growth rate measurements between the full numerical relativity and FLRW treatments is sub-dominant to the statistical error of current datasets, confirming that FLRW modelling is adequate for current low-redshift peculiar velocity experiments. Future datasets extending to higher redshift may require theoretical models that additionally incorporate the contributions of gravitational lensing and inhomogeneous curvature.
#### Modeling Doppler Shifts in Radial-Velocity Data with Deep Learning toward Earth-mass Exoplanet Detection
 - **Authors:** Isidro Gómez-Vargas, Xavier Dumusque, Yinan Zhao, Khaled Al Moulla, Michael Cretignier
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Earth and Planetary Astrophysics (astro-ph.EP); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2606.18464

 - **Pdf link:** https://arxiv.org/pdf/2606.18464

 - **Abstract**
 Detecting the tiny Doppler shifts induced by Earth-mass planets in stellar radial-velocity measurements remains extremely challenging due to stellar activity. Many deep-learning methods performing well on simulated data remain difficult to apply reliably on real stellar spectra. The aim of this work is to develop a deep-learning framework that generalizes to real, unseen spectra and improves the detectability of Earth-mass planets in radial-velocity data. We train artificial neural networks on HARPS-N solar spectra with injected planetary signals, using physics-motivated spectral representations based on flux and line-formation temperature, together with their velocity gradients. Two training strategies are explored: hold-out testing and cross-validation. Model robustness is enhanced through genetic-algorithm-based hyperparameter optimization, and predictive uncertainty is quantified using Monte Carlo dropout. Our most precise neural network model reliably retrieves, under the cross-validation strategy, the amplitudes, phases, and orbital periods of planetary signals with amplitudes greater than or equal to 25 cm/s and periods between 10 and 550 days. In addition, in all cases tested here, the successfully recovered signals correspond to the most significant peaks in the periodograms of the Doppler-shift predictions. Temperature-based spectral-shell representations consistently outperform flux-based shells. We also release doppleriann, a Python package implementing the proposed framework. Our results demonstrate that combining physically motivated spectral representations with deep learning provides a promising pathway toward the detection of Earth-mass planets in radial-velocity data from real observations, supported by a modeling framework that is both physically grounded and statistically rigorous, incorporating uncertainty quantification and optimized training strategies.
#### PHANTOM: A MATLAB and Octave Toolbox Connecting Linear Field Statistics to Dark Matter Halo Observables
 - **Authors:** Mohammad Abu Thaher Chowdhury
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2606.19104

 - **Pdf link:** https://arxiv.org/pdf/2606.19104

 - **Abstract**
 We present phantom (Profile and Halo Analysis for Numerous Theoretical dark Matter Observables), a public MATLAB toolbox and Octave package for calculations that connect the linear density field to dark matter halo observables. The package combines a flexible cosmology module with linear power spectrum, variance, and correlation function solvers, and a halo module that covers mass functions, linear bias, density profiles, and concentration-mass relations for cold, warm, and fuzzy dark matter scenarios. All core routines are validated against the Python package colossus, hmf, and halomod, yielding sub-percent agreement for shared models across distances, power spectra, variance, correlation functions, halo mass functions, and density profiles. Phantom is organised around a cosmology structure that stores background expansion, growth, and linear power-spectrum handles; this object is constructed once and passed through the call graph, so that halo statistics and halo structure calculations remain consistent by design. From this single entry point, users can obtain field statistics (power spectrum, variance, correlation function), halo statistics (mass functions, linear bias), and halo observables (enclosed mass, circular velocity, projected density, and lensing convergence) on arbitrary user-defined grids. The toolbox targets users whose analysis pipelines are written in MATLAB or Octave, where a validated native implementation of these models has been absent. The code is released under the MIT licence at phantom(this https URL).
#### Solitary dwarf galaxy groups as tracers of primordial dark matter halos in the local Universe
 - **Authors:** Z. S. Yuan, Z. L. Wen, J. L. Han
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2606.19193

 - **Pdf link:** https://arxiv.org/pdf/2606.19193

 - **Abstract**
 In $\Lambda$CDM cosmology, galaxies and clusters form within dark matter halos and merge in the hierarchical assembly paradigm to form massive systems. Using the released optical survey data, we searched for groups composed solely of dwarf galaxies, each with a stellar mass $M_*<10^{9.5}~M_{\odot}$. We identified 14 dwarf galaxy groups with at least 5 dwarf galaxies, all located within a projected radius of 200 kpc and with a line-of-sight velocity of $\pm$300 km~s$^{-1}$. We checked photometric and imaging data and found that these 14 dwarf galaxy groups are solitary, with no neighboring massive galaxies with $M_*>10^{10}~M_{\odot}$ within 500 kpc and within $\pm$1200 km s$^{-1}$. The stellar mass fractions of dwarf galaxy groups with $M_{\rm dyn}>10^{12}~M_{\odot}$ are much lower than predicted by the canonical stellar mass and halo mass relation. These dwarf galaxies are gravitationally bound within halos with a dynamical mass of around $M_{\rm dyn} \sim 10^{12}~M_{\odot}$ and a virial radius of less than 400 kpc. These dwarf galaxy groups, therefore, indicate primordial halos that host only a few newly formed dwarf galaxies.
#### A New Methodology for Classifying Eclipsing Binaries with Kepler Data and Deep Learning
 - **Authors:** Mousam Mondal, Patricia Cruz, Hugh R. A. Jones, M. C. Gálvez-Ortiz, John F. Aguilar
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2606.19295

 - **Pdf link:** https://arxiv.org/pdf/2606.19295

 - **Abstract**
 We present a new method for the automated classification of eclipsing binaries, into contact, detached, and semi-detached types using Kepler data. Phase-folded light curves are generated and chi-square vs. box size plots are constructed by comparing flux values to the median flux, revealing distinct class patterns. These patterns were first modelled using a polynomial damped sinusoidal function, whose period served as classification feature, achieving an overall accuracy of 86.5 percent. To capture more features and enhance accuracy, we trained a convolutional neural network, which improved the total accuracy to 90 percent, including 47 percent for the challenging semi-detached systems. However, several binaries displayed irregular chi-square signatures. To mitigate this, we incorporated simulated light curves generated with the PHOEBE modelling code, achieving 99 per cent accuracy in distinguishing contact and detached binaries. The resulting chi-square morphologies show a strong correlation with orbital period, and a subset of systems exhibit quarterly variability in their light curves and chi-square trends. We designate these as Temporally Varying systems. By measuring the normalized spread of the chi-square period across quarters, we define a statistical threshold that separates these systems from stable binaries. We reported four Temporally Varying systems not previously noted in the literature with magnetic activity that requires further investigation. Furthermore, cooler stars, namely late-F, G, K, and M types, display systematically higher variability than hotter stars. Cross-matching with catalogues of magnetically active stars indicates that stellar flares and starspots are the most likely causes of this enhanced variability.
#### The Chandra-Gaia Catalog of Counterparts: Resolving ambiguous Gaia matches to X-ray sources in the Chandra Source Catalog using Machine Learning
 - **Authors:** V. Samuel Pérez-Díaz, Vinay L. Kashyap, Joshua D. Ingram, David Fouhey, Juan Rafael Martínez-Galarza, Pavlos Protopapas, Jeremy J. Drake, Dong-Woo Kim, Cecilia Garraffo
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2606.19329

 - **Pdf link:** https://arxiv.org/pdf/2606.19329

 - **Abstract**
 We present a framework to cross-match sources from the Chandra Source Catalog (CSC v2.1) with optical sources from Gaia Data Release 3. Unlike purely spatial approaches, we use source properties such as magnitudes, colors, and distances to identify true counterparts, detect chance coincidences, and resolve ambiguities when multiple plausible candidates exist. We define a training set of high-confidence matches using NWAY, a Bayesian cross-matching framework that accounts for positional errors and source densities. We train a gradient-boosted classifier (LightGBM) on a variety of features from both catalogs. Of the ~$254$k unique X-ray sources, we find counterparts for ~$113$k sources, of which plausible multiple counterparts are found for ~$7$k. We find no counterparts for ~$20$k sources for which separation-based cross-matching does find a match, and attribute half of these to chance coincidences. We validate the pipeline on the Chandra Orion Ultradeep Project (COUP), where the machine-learning matches reproduce 95% of NWAY cross-matches without using any positional information. We release a catalog of the ~$113$k Chandra-Gaia counterparts, together with ~$7$k alternative matches and ~$20$k ambiguous NWAY associations, supporting future population studies of sources detectable by both Chandra and Gaia. We discuss limitations and provide a generalization of the framework that is applicable in other cross-matching scenarios.


by olozhika (Xing Yuchen). 


2026-06-18
