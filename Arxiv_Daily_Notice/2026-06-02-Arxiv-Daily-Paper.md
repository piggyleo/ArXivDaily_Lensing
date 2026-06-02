# Showing new listings for Tuesday, 2 June 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 12papers 
#### 21cmEMUv3: a hybrid diffusion-LSTM emulator of 21cmFAST summary observables
 - **Authors:** Daniela Breitman, Andrei Mesinger, Steven G. Murray, Ivan Nikolic, Roberto Trotta
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2606.00219

 - **Pdf link:** https://arxiv.org/pdf/2606.00219

 - **Abstract**
 We are witnessing a surge in observations of the cosmic dawn (CD) and epoch of reionisation (EoR), driving an increasing demand for fast and robust theoretical interpretation frameworks. In response, machine learning (ML), and emulation in particular, has emerged as a powerful approach to accelerate and enhance inference pipelines. In this work, we present 21cmEMUv3, an emulator trained on 21cmFASTv3 simulations that model both atomically and molecularly cooling galaxies. 21cmEMUv3 is conditioned on $\sigma_8$ and ten astrophysical parameters to produce seven summary observables: (i) the cylindrical 21cm power spectrum (PS), emulated for the first time at such high resolution and accuracy across a wide redshift range of $z \sim$ 6--30; (ii) the spherically-averaged 21cm PS; (iii) the mean neutral fraction of the intergalactic medium (IGM); (iv) the mean 21cm spin temperature; (v) the global 21cm signal; (vi) the ultraviolet (UV) luminosity functions (LFs); and (vii) the Thomson scattering optical depth. Notably, the cylindrical 21cm PS is emulated via score-based diffusion, while the remaining six summaries are emulated via long-short term memory (LSTM) networks, all achieving sub-percent median accuracy. We use the emulator to reinterpret current 21cm PS upper limits from HERA, for the first time using state-of-the-art hydrodynamical simulations to inform priors on star formation inside molecularly cooling galaxies. We find that our inferred soft-band X-ray luminosity per unit star formation rate is consistent with extrapolations of high-mass X-ray binaries to the low-metallicity regimes expected in the first galaxies, excluding values below $10^{39.2}$ erg s$^{-1}M^{-1}_\odot \rm{yr}$ at $95\%$ confidence. Finally, we produce forecasts for the detection of the cosmic 21cm PS with the Square Kilometre Array for different array configurations. The 21cmEMU package is publicly available.
#### It's Not Just Star Formation: A trend of low dark matter densities in the Andromeda dwarf galaxy system
 - **Authors:** Connor S. Pickett, Michelle L. M. Collins, Justin I. Read, R. Michael Rich, Emily J. E. Charles, Erik Tollerud, Nicolas Martin, Scott Chapman, Alan McConnachie, Alessandro Savino, Daniel R. Weisz
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2606.00221

 - **Pdf link:** https://arxiv.org/pdf/2606.00221

 - **Abstract**
 Dynamical mass modeling of Andromeda (M31) dwarf spheroidal (dSph) galaxies has revealed a growing trend of lower central dark matter (DM) densities than predicted by pure DM structure formation in Lambda Cold Dark Matter ($\Lambda$CDM) cosmology simulations and lower than most Milky Way (MW) satellites. So far, however, only four of the 35 confirmed M31 dSphs have been successfully mass modeled. In this second paper of a series, we aim to better understand growing Local Group (LG) dSph patterns by mass modeling seven more M31 dSphs: Andromeda I, III, V, VII, IX, XXXI, and XXXII. We update the kinematics of each dwarf and estimate their central dark matter densities at 150 pc using the dynamical Jeans modeling tool, GravSphere. We also update their DM halo mass, $M_{\rm{200}}$, via abundance matching. We find Andromeda III and V to have central DM densities in line with $\Lambda$CDM expectations, resembling dSphs around the Milky Way. The remaining five dwarfs have anomalously low central densities, continuing a growing trend seen for M31 satellites. We investigate each dwarf's star formation history and find that star formation-induced `DM heating' is disfavored as the sole explanation of these lower central densities. We consider the effect of tides and halo concentration scatter on these systems and predict that they should be on more plunging orbits than their denser counterparts. If this prediction is misaligned with the data, it could necessitate new physics beyond the Standard Cosmological Model.
#### Vision-Language Model Ensembles Achieve Human-Expert Accuracy for Galaxy Merger Classification
 - **Authors:** Marco Chiaberge, Elias Stengel-Eskin, Massimo Stiavelli, Colin Norman
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2606.00415

 - **Pdf link:** https://arxiv.org/pdf/2606.00415

 - **Abstract**
 We present a proof-of-concept study demonstrating that an ensemble of Vision--Language Models (VLMs) combined using a Bayesian statistical framework can classify galaxy merger morphologies with accuracy comparable to trained human experts. We deploy 15 VLM classifier configurations, spanning four model architectures (Gemma-4 E2B, Gemma-4 E4B, Qwen2.5-VL, and Qwen3-VL) tested with up to four prompt engineering strategies each. We evaluate their performance against a truth-known sample of 41 VELA+SUNRISE mock galaxy images from Lambrides et al. 2021. The VLM ensemble achieves 83.3\% accuracy on confident classifications (merger probability $p_{\rm M} \ge 0.8$ or $p_{\rm M} \le 0.2$), with 5 misclassified galaxies. The ensemble recovers the population merger fraction to within $0.66\sigma$ of the truth ($f_{\rm M} = 0.52 \pm 0.09$ vs.\ true value of 0.585). Bayesian weighting improves overall accuracy by 17.1 percentage points over simple majority voting, with sensitivity improving by 29.2 percentage points. The VLM ensemble produces 5 misclassified galaxies (2 false positives, 3 false negatives), comparable to the 6 misclassifications (5 false positives, 1 false negative) reported for human classifiers by Lambrides et al. 2021. The apparent differences in error profiles are not statistically significant given the sample size of 41 galaxies. VLMs also produce more moderate per-galaxy merger probability distributions (27\% uncertain) than the more polarized human distributions (15\% uncertain), though this difference is also consistent with statistical fluctuation. These results establish VLMs as scalable, reproducible alternatives to human classifiers within a Bayesian probabilistic merger-fraction framework, with direct applications to large galaxy samples from current and future surveys.
#### Decaying Dark Matter as a Possible Solution for Cosmological Tensions
 - **Authors:** Yaman Acharya, Ryan E. Johnson
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2606.00529

 - **Pdf link:** https://arxiv.org/pdf/2606.00529

 - **Abstract**
 Large-scale structure measurements have revealed persistent tensions between early- and late-time cosmological probes, most notably the long-standing discrepancy in the structure-growth parameter $S_8$. In this work, we explore how a model including decaying dark matter (DDM) can alleviate this tension by suppressing the growth of matter fluctuations at late times. Specifically, we consider a neutrinophilic decay channel in which a heavy dark matter particle $\chi$ slowly decays into a Standard Model neutrino and a light invisible fermion, $\chi \rightarrow \nu + \phi$, modifying both the background evolution and the clustering of structure. Using the DES Year~1 redshift distributions, we construct a baseline matter power spectrum and compute the galaxy-galaxy, shear-shear, and galaxy-shear angular power spectra under both $\Lambda$CDM and DDM-inspired scenarios. We find that slow dark matter decay produces a scale-dependent suppression of clustering that remains consistent with DES measurements while naturally shifting the predicted structure amplitude toward the lower values favored by weak lensing surveys. Our results suggest that decaying dark matter is a compelling and physically motivated framework for addressing the $S_8$ tension.
#### Generative Diffusion Priors for 3D Mapping of the Dark Universe
 - **Authors:** Brandon Zhao, Diana Scognamiglio, Olivier Doré, Katherine L. Bouman
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2606.00803

 - **Pdf link:** https://arxiv.org/pdf/2606.00803

 - **Abstract**
 Reconstructing the three-dimensional distribution of dark matter from weak-lensing observations is a central but highly ill-posed inverse problem in cosmology. Unlike standard 3D reconstruction with multiple viewpoints, we observe the universe from a single line of sight, through noisy shape distortions of galaxies with uncertain distances, so meaningful recovery of the 3D matter field requires strong prior assumptions. Existing methods either produce point estimates with handcrafted priors or use neural ensembles for approximate Bayesian uncertainty, and struggle to capture the non-Gaussian, filamentary structure of the cosmic web. With the advent of new high-resolution cosmological simulations, we now have an alternative source of prior knowledge that captures the nonlinear statistics of structure formation with far greater fidelity than analytic prescriptions. We leverage these simulations to build a new dataset $\texttt{Conicus3D}$, which enables us to learn a data-driven diffusion-model prior capturing the full 3D distribution of dark matter structure across cosmic time. Building on recent plug-and-play approaches, we modify a diffusion-based posterior sampling scheme to the 3D weak-lensing setting, combining the learned prior with a differentiable physical forward model. On realistic simulations targeting a modern weak lensing survey, our approach yields substantially improved 2D and 3D reconstruction accuracy over baseline methods. Moreover, it produces posterior samples whose statistics closely track the underlying simulations, while remaining robust to moderate shifts in cosmology.
#### JAXtronomy: A JAX port of lenstronomy
 - **Authors:** Alan Huang, Simon Birrer, Daniel Gilman, Natalie B. Hogg, Anowar J. Shajib, Aymeric Galan, Nan Zhang
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2606.01547

 - **Pdf link:** https://arxiv.org/pdf/2606.01547

 - **Abstract**
 Gravitational lensing is a phenomenon where light bends around massive objects, resulting in distorted images seen by an observer. Studying gravitationally lensed systems provides insights into cosmology and astrophysics, including constraints of the expansion rate of the Universe and the distribution of dark matter. Thus, we introduce JAXtronomy, a re-implementation of the gravitational lensing software package lenstronomy (Birrer, 2021; Birrer & Amara, 2018) using JAX (Bradbury et al., 2018). JAX is a Python library that uses an accelerated linear algebra (XLA) compiler to improve the performance of computing software. Our core design principle of JAXtronomy is to maintain an identical API to that of lenstronomy. The main JAX features utilized in JAXtronomy are just-in-time compilation, which can lead to significant reductions in execution time, and automatic differentiation, which allows for the implementation of gradient-based algorithms that were previously impossible. Additionally, JAX allows code to be run on GPUs or parallelized across CPU cores, further boosting the performance of JAXtronomy.
#### Possible High-Energy Neutrino Emission from Dark Matter Annihilation in the Disrupting Dwarf Galaxy Boötes~III
 - **Authors:** Shunhao Ji, Zhongxiang Wang (Yunnan University, China)
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2606.01853

 - **Pdf link:** https://arxiv.org/pdf/2606.01853

 - **Abstract**
 We report the first search for high-energy neutrino emissions from dark matter (DM) annihilation in stellar-stream cores. Motivated by a recent gamma-ray study that proposed these cores as a new class of indirect DM targets, we analyze three stream cores in the Northern Hemisphere using the public ten-year track-like neutrino data released by IceCube. Under the $\chi\chi\to\nu\bar{\nu}$ annihilation hypothesis, the most significant excess among the three targets is found at the position of the nearby dwarf galaxy Boötes~III, the core of the Styx stream, with a best-fit DM mass of 26.5\,TeV. The excess has a post-trial significance of $3.1\sigma$. Considering the existing IceCube dwarf-galaxy limit for the same channel, we obtain a limit on the J-factor $J_{\rm ann}$, $\log_{10}(J_{\rm ann}/{\rm GeV^2\,cm^{-5}})\gtrsim 19.1^{+0.3}_{-0.5}$. This limit is broadly consistent with empirical estimates of $J_{\rm ann}$ for Boötes~III. The results provide the first candidate target with a possible HE neutrino signal associated with DM annihilation. This neutrino excess and the general existence of DM-induced neutrino signals from other similar sources will be confirmed with the near-future large high-energy neutrino detectors, thus enabling us to probe the nature of DM particles.
#### CSST large-scale structure analysis pipeline: IV. Cosmic Voids Identified from Galaxy Group Samples as Probes of the Large-scale Structure
 - **Authors:** Yingxiao Song, Xiaohu Yang, Yan Gong, Yizhou Gu, Qingyang Li, Hong Guo, Yunkun Han, Yipeng Jing, Cheng Li, Feng Shi, Jipeng Sui, Run Wen, Hu Zhan, Pengjie Zhang, Youcai Zhang, Gong-Bo Zhao, Xian Zhong Zheng, Xingchen Zhou, Hu Zou
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2606.01907

 - **Pdf link:** https://arxiv.org/pdf/2606.01907

 - **Abstract**
 Because groups are directly associated with halos, they allow for considerably simpler theoretical modeling than approaches based on individual galaxies. We therefore propose to use voids identified in galaxy group catalogs, referred to as group-voids, to investigate the cosmic large-scale structure (LSS). Using the reference mock galaxy redshift survey (MGRS) designed for the Chinese Space-station Survey Telescope (CSST), we build two galaxy group catalogs representing ideal and conservative scenarios, derived from galaxy samples with 100\% and roughly 30\% spectroscopic redshift completeness, respectively. We then identify voids in these two mock group catalogs, as well as in the underlying halo catalog, and measure two void statistics, the void size function (VSF) and the void density profile, within five redshift intervals spanning $z=0$ to $1.0$. We compare the statistics obtained from two kinds of voids: those defined by galaxy groups (group-voids) and those defined by dark matter halos (halo-voids). In the void-finding process, we adopt the brightest central galaxy (BCG) as the group center to improve the accuracy of the inferred void centers. Our analysis shows that void statistics derived from group-voids with spectroscopic redshift completeness of at least 40\% can faithfully reproduce the corresponding statistics from halo-voids. Even when the redshift completeness of galaxies falls to as low as 30\%, we can still reliably describe group-voids via halo-voids by incorporating a redshift error term. This indicates that group-voids are a promising tool for probing LSS and offer a valuable complement to standard void studies, which is especially advantageous for emulator-based methods.
#### Accurate inner stellar density slopes from projected surface densities in galaxies
 - **Authors:** Jorge Sanchez Almeida (1 and 2) ((1) Instituto de Astrofisica de Canarias, La Laguna, Tenerife, E-38200, Spain, (2) Departamento de Astrofisica, Universidad de La Laguna, Tenerife, Spain)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2606.01956

 - **Pdf link:** https://arxiv.org/pdf/2606.01956

 - **Abstract**
 The inner slope of the three-dimensional stellar density in dwarf galaxies (rho'[0]) is a sensitive probe of possible departures from the collisionless cold dark matter (CDM) paradigm, since cored stellar distributions (rho'[0]=0) cannot easily reside within the cuspy potentials CDM predicts for low-mass systems. Photometry alone offers an observationally inexpensive way to constrain rho'(0), making this approach particularly attractive for the faint galaxies most relevant to dark matter (DM) studies. Inferring volume densities, however, requires deprojecting the observed stellar surface density, Sigma(R), a procedure that is notoriously ambiguous in the presence of noise. To avoid explicit deprojection, we derive an expression (Eq.~[9]]) to obtain rho'(0) directly from the radial derivatives of Sigma(R), assuming spherical symmetry and smooth finite density profiles. All projected profiles are shown to have the same central functional form, independent of the underlying volume density (Eq.~[20]). As a result, the derivatives of Sigma(R) can be extrapolated to the center using constraints from larger radii, which in turn yields rho'(0). As an illustration, we apply the method to six ultra-faint dwarf (UFD) galaxies, finding that all of them have a surface density with the same shape, from which the presence of stellar cores is inferred (rho'[0] simeq 0). The technique also has the ability to diagnose rho'[0]>0, corresponding to galaxies with a central stellar mass deficit potentially linked to black-hole scouring, MONDian dynamics, or deviations from CDM.
#### Hierarchical assembly in action: a galaxy tail from a disrupting group in the Virgo cluster outskirts
 - **Authors:** J. Alfonso L. Aguerri, Stefano Zarattini, Virginia Cuomo, Lorenzo Morelli
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2606.02074

 - **Pdf link:** https://arxiv.org/pdf/2606.02074

 - **Abstract**
 Group environments are thought to play a key role in shaping galaxy evolution prior to cluster accretion. However, direct observational evidence linking group--cluster interactions to the transformation of low-mass galaxies remains scarce. We reexamine the nature and origin of the W cloud, located in the southern outskirts of the Virgo cluster, to better understand the dynamical processes driving group accretion and galaxy transformation during cluster assembly. Using the spatial distribution, kinematics, and stellar population properties of galaxies in the W cloud and its surroundings, we characterize the three-dimensional structure and dynamical state of the system. We show that the W cloud is not a large-scale filament seen in projection, but is instead dominated by a compact galaxy group (the W group) currently interacting with Virgo. We also identify a previously unknown, dynamically coherent tail of galaxies (the W tail) connecting the W group to the cluster. The tail exhibits a continuous sequence in velocity, velocity dispersion, and three-dimensional distance. Its low-velocity component is already gravitationally bound to Virgo, whereas higher-velocity galaxies remain associated with the W group and are still infalling. The W tail forms a planar structure aligned with the orbital geometry of the W group, strongly supporting a tidal origin. The stellar masses and colours of its members indicate that the stripped population is dominated by low-mass, star-forming dwarf galaxies that remain in the blue cloud. The W group--W tail system provides a well-resolved example of an ongoing group--cluster interaction, illustrating how low-density groups can deliver largely unprocessed dwarf galaxies into clusters. This system provides important observational constraints on the hierarchical assembly of galaxy clusters and the buildup of their dwarf galaxy populations.
#### Redshift Duality with Pantheon+SH0ES in a Planck-anchored Flat $Λ$CDM Framework: Implications for Hubble Tension and Observational Inference
 - **Authors:** Tae-Kyoung Lee
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2606.02097

 - **Pdf link:** https://arxiv.org/pdf/2606.02097

 - **Abstract**
 We test an operationally defined redshift duality in which the observed redshift comprises the standard metric-expansion component together with an additional line-of-sight quantum contribution arising from the cumulative conversion of photon energy into effective mass as a function of path length and frequency. Fitting this hybrid model to the Pantheon+SH0ES compilation, we find that the metric-expansion Hubble constant, $H_\Lambda$, is recovered to a value consistent with the Planck baseline of $67.4~\mathrm{km\,s^{-1}\,Mpc^{-1}}$ within $\lesssim 0.33\sigma$. Redshift-binned analyses show that while the flat Lambda cold dark matter ($\Lambda$CDM) model produces an apparent drift in the inferred Hubble parameter across the Hubble flow, the hybrid model restores the constancy of $H_\Lambda$ across redshift bins. The correctional trends of cosmological physical quantities re-inferred under this framework further indicate the potential to alleviate anomalies associated with high-redshift galaxies. These results suggest that redshift duality warrants further consideration in observational processing and inference, while preserving consistency with a Planck-anchored flat $\Lambda$CDM baseline.
#### AstroSkyFlow: an astronomical sky image flow simulator for time domain survey validation and machine learning
 - **Authors:** Kexin Li, Yicheng Rui, Fabo Feng, Shuyue Zheng, Anton Pomazan, Yiyang Guo, Jie Zheng, Lin-Qiao Jiang
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2606.02140

 - **Pdf link:** https://arxiv.org/pdf/2606.02140

 - **Abstract**
 Modern time-domain optical surveys produce massive data volumes that require robust, high-fidelity simulated datasets for developing and validating automated pipelines and machine-learning models. We present AstroSkyFlow, a modular sky-image simulator that generates on-demand, time-dependent flux variations and models the full observing stack, from celestial sources and atmospheric effects to sensor response. Given a simulated observing schedule, AstroSkyFlow produces multi-epoch, time-series images with realistic noise and variability. Compared to real observational data, AstroSkyFlow reproduces noise characteristics and point spread function properties more accurately than the widely used SkyMaker simulator. In addition, AstroSkyFlow successfully recovers injected photometric and motion signals, such as exoplanet transits and asteroid trails. AstroSkyFlow enables the generation of labeled, high-fidelity datasets essential for training machine-learning pipelines and conducting rigorous injection-recovery tests for analysis pipelines for next-generation time-domain surveys.


by olozhika (Xing Yuchen). 


2026-06-02
