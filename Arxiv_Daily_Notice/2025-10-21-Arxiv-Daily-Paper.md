# Showing new listings for Tuesday, 21 October 2025
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 7papers 
#### Ultracool dwarf Science with MachIne LEarning (USMILE). I. Scalable Tree-Based Models for Photometric Spectral Classification and New Discoveries from LSST Data Preview 1 and Euclid Quick Data Release 1
 - **Authors:** Zhoujian Zhang, Yanxia Li
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2510.16098

 - **Pdf link:** https://arxiv.org/pdf/2510.16098

 - **Abstract**
 We present the Ultracool dwarf Science with MachIne LEarning (USMILE), a program developing machine-learning tools for the discovery and characterization of ultracool dwarfs. We introduce USMILE Avocado, a spectral classification framework that uses broadband photometry from wide-field surveys -- Rubin Observatory LSST Data Preview 1, VISTA Hemisphere Survey, and CatWISE -- as input features. The framework has two gradient-boosted decision-tree models scalable to the massive data volumes of modern surveys: the classifier, which distinguishes ultracool dwarfs from stellar/extragalactic contaminants, and the regressor, which predicts spectral types. A key strength is its ability to natively handle missing photometric features, whereas earlier machine-learning approaches required complete multi-band detections or relied on imputation, thereby excluding genuine ultracool dwarfs or introducing bias. Trained on an augmented labeled dataset of >2 million sources built from known ultracool dwarfs, reddened early-type stars, and quasars, the models achieve strong performance: the classifier attains an ROC AUC of 0.976 and an F1 score of 0.92, while the regressor yields a mean-squared error of 0.88 subtypes. Applying these models, we carried out the first ultracool dwarf search with LSST DP1, cross-matched against VHS and CatWISE. Crucially, Euclid Quick Data Release 1 provided near-IR spectra for hundreds of candidates, enabling a rare, large-scale external spectroscopic validation. This confirmed 15 M6--L2 discoveries, verified USMILE performance, and clarified regimes where USMILE predictions are most reliable. Building on these insights, we identified 25 additional M6--L9 photometric candidates. These demonstrate the effectiveness of machine-learning methods in the data-rich era of wide-field surveys, highlighting the synergy between LSST and Euclid in expanding the ultracool dwarf census.
#### Neural Posterior Estimation for White Dwarf Spectroscopic Characterization
 - **Authors:** Olivier Vincent, Patrick Dufour, Pierre Bergeron
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2510.16261

 - **Pdf link:** https://arxiv.org/pdf/2510.16261

 - **Abstract**
 White dwarf spectroscopic characterization is entering a big data era, with the number of spectroscopically characterized white dwarfs expected to grow from $\sim$100,000 to over 300,000 in upcoming years. Traditional methods like least-squares fitting and Markov Chain Monte Carlo have become computationally prohibitive for large-scale analysis, requiring minutes to days per star. Furthermore, these methods impose fundamental limitations on model complexity by requiring explicit likelihood functions, typically restricting them to Gaussian assumptions. We present neural posterior estimation (NPE), a simulation-based inference technique that directly approximates posterior distributions through neural networks trained on simulated spectra. Our approach provides accurate parameter inference in milliseconds per star after upfront training costs, enabling statistical tests of the procedure's reliability. We demonstrate NPE's effectiveness on DA, DB, and carbon-atmosphere white dwarfs, validating its calibration with simulation-based calibration and tests of accuracy with random points. Application to SDSS data shows excellent agreement with previous studies, recovering parameters from previous work within 6.8% for effective temperature and 2.1% for surface gravity, on average. We also apply our technique on WD 1153+012, a hot DQ star with a carbon-oxygen-hydrogen atmosphere, using high-resolution spectroscopy. This methodology combines computational efficiency with the flexibility to model complex atmospheres, making it ideal for upcoming surveys. Our approach also integrates spectroscopic and photometric constraints through an iterative procedure, providing comprehensive characterization of white dwarfs.
#### Optical turbulence forecast for ground-based astronomy and free-space optical communication
 - **Authors:** Elena Masciadria, Alessio Turchia, Camilo Weinbergera, Marlene De Sepibusa, Luca Finia
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Atmospheric and Oceanic Physics (physics.ao-ph)
 - **Arxiv link:** https://arxiv.org/abs/2510.16845

 - **Pdf link:** https://arxiv.org/pdf/2510.16845

 - **Abstract**
 Forecasting optical turbulence in the Earth's atmosphere has been an ambitious challenge for the astronomical scientific community for several decades. While earlier research primarily focused on whether it was possible to predict optical turbulence and its vertical distribution, current efforts are more concentrated on the accuracy achievable at different timescales, the efficiency of various forecasting methods and the contributions of new statistical approaches, such as auto-regression and machine learning to this field. In this contribution, I will present the state of the art of the research conducted by our group, positioned within the international research scenery. Most of our past activity has been primarily focused on ground-based astronomy but recent advancements in space research opened new opportunities for applications in the free-space optical communication.
#### Investigating the Effects of Point Source Injection Strategies on KMTNet Real/Bogus Classification
 - **Authors:** Dongjin Lee, Gregory S.H. Paek, Seo-Won Chang, Changwan Kim, Mankeun Jeong, Hongjae Moon, Seong-Heon Lee, Jae-Hun Jung, Myungshin Im
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2510.17053

 - **Pdf link:** https://arxiv.org/pdf/2510.17053

 - **Abstract**
 Recently, machine learning-based real/bogus (RB) classifiers have demonstrated effectiveness in filtering out artifacts and identifying genuine transients in real-time astronomical surveys. However, the rarity of transient events and the extensive human labeling required for a large number of samples pose significant challenges in constructing training datasets for RB classification. Given these challenges, point source injection techniques, which inject simulated point sources into optical images, provide a promising solution. This paper presents the first detailed comparison of different point source injection strategies and their effects on classification performance within a simulation-to-reality framework. To this end, we first construct various training datasets based on Random Injection (RI), Near Galaxy Injection (NGI), and a combined approach by using the Korea Microlensing Telescope Network datasets. Subsequently, we train convolutional neural networks on simulated cutout samples and evaluate them on real, imbalanced datasets from gravitational wave follow-up observations for GW190814 and S230518h. Extensive experimental results show that RI excels at asteroid detection and bogus filtering but underperforms on transients occurring near galaxies (e.g., supernovae). In contrast, NGI is effective for detecting transients near galaxies but tends to misclassify variable stars as transients, resulting in a high false positive rate. The combined approach effectively handles these trade-offs, thereby balancing between detection rate and false positive rate. Our results emphasize the importance of point source injection strategy in developing robust RB classifiers for transient (or multi-messenger) follow-up campaigns.
#### Heating and scattering of stellar distributions by ultralight dark matter
 - **Authors:** Andrew Eberhardt, Mateja Gosenca, Lam Hui
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA); High Energy Physics - Theory (hep-th)
 - **Arxiv link:** https://arxiv.org/abs/2510.17079

 - **Pdf link:** https://arxiv.org/pdf/2510.17079

 - **Abstract**
 Due to wave interference, an ultralight light dark matter halo has stochastic, granular substructures which can scatter stars, leading to the heating of stellar distributions. Studies of this phenomenon have placed lower bounds on the ultralight dark matter mass. In this paper we investigate a number of relevant systematic effects, including: (1) the heating by the central soliton, (2) the self-gravity of the stars, (3) the suppression of heating in a tidally stripped halo, and (4) the tidal field suppression of heating when the stellar cluster is much smaller than the de Broglie wavelength. The first three effects are quantified by studying the dynamics of stellar particles in Schrodinger-Poisson simulations of ultralight dark matter halos, while the last effect is studied using analytic approximations.
#### Estimating Orbital Parameters of Direct Imaging Exoplanet Using Neural Network
 - **Authors:** Bo Liang, Hanlin Song, Chang Liu, Tianyu Zhao, Yuxiang Xu, Zihao Xiao, Manjia Liang, Minghui Du, Wei-Liang Qian, Li-e Qiang, Peng Xu, Ziren Luo
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP); Astrophysics of Galaxies (astro-ph.GA); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2510.17459

 - **Pdf link:** https://arxiv.org/pdf/2510.17459

 - **Abstract**
 In this work, we propose a new flow-matching Markov chain Monte Carlo (FM-MCMC) algorithm for estimating the orbital parameters of exoplanetary systems, especially for those only one exoplanet is involved. Compared to traditional methods that rely on random sampling within the Bayesian framework, our approach first leverages flow matching posterior estimation (FMPE) to efficiently constrain the prior range of physical parameters, and then employs MCMC to accurately infer the posterior distribution. For example, in the orbital parameter inference of beta Pictoris b, our model achieved a substantial speed-up while maintaining comparable accuracy-running 77.8 times faster than Parallel Tempered MCMC (PTMCMC) and 365.4 times faster than nested sampling. Moreover, our FM-MCMC method also attained the highest average log-likelihood among all approaches, demonstrating its superior sampling efficiency and accuracy. This highlights the scalability and efficiency of our approach, making it well-suited for processing the massive datasets expected from future exoplanet surveys. Beyond astrophysics, our methodology establishes a versatile paradigm for synergizing deep generative models with traditional sampling, which can be adopted to tackle complex inference problems in other fields, such as cosmology, biomedical imaging, and particle physics.
#### Relics of High-redshift Compaction in our Backyard: The Most Metal-poor Stars in the Proto-Galaxy
 - **Authors:** Shenglan Sun, Yang Huang, Fangzhou Jiang, Huawei Zhang, Xiang-Xiang Xue, Timothy C. Beers, Chengye Cao, Qikang Feng, Ruizhi Zhang, Haiyang Xing, João A. S. Amarante
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.17693

 - **Pdf link:** https://arxiv.org/pdf/2510.17693

 - **Abstract**
 The earliest assembly of the Milky Way (MW) remains poorly understood, yet the spatial, chemical, and kinematic properties of its most metal-poor stars provide a unique fossil record of its proto-Galaxy phase. Understanding how this ancient component formed is essential for linking near-field Galactic archaeology to high-redshift galaxy evolution. We construct the currently largest 3-D map of inner-Galaxy metal-poor giants by combining several narrow/medium-band photometric surveys, reaching metallicities down to [Fe/H]$\sim-$3.5. Comparing observational data with Auriga 18 (Au18) from the Auriga cosmological simulations, we find that the proto-Galaxy population ([Fe/H]$\lesssim-$1.4) is highly centrally concentrated within the Galactocentric distance $r_{\rm gc}\lesssim$15 kpc, and forms a dispersion-supported structure with negligible rotation. The spatial and chemo-dynamical properties of observed proto-Galaxy population closely match those of the metal-poor stars in Au18. Considering Au18 as an analog of the MW, we propose a new scenario in which the formation of the proto-Galaxy is linked, for the first time, to episodes of high-z (z$\gtrsim$3) gas compaction, blue-nugget phases, and quenching processes. This framework provides a unified physical picture for the first $\sim$1-2 Gyr of the MW's evolution, bridging local fossil records with future studies of early star-forming galaxies.


by olozhika (Xing Yuchen). 


2025-10-21
