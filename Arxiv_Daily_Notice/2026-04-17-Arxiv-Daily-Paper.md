# Showing new listings for Friday, 17 April 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 8papers 
#### Cold vs. Hot Gas Accretion and Angular Momentum in FIRE Simulations: From Halo to Galaxy Scales
 - **Authors:** Imran Sultan, Claude-André Faucher-Giguère, Jonathan Stern, Guochao Sun
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2604.14273

 - **Pdf link:** https://arxiv.org/pdf/2604.14273

 - **Abstract**
 We present a systematic study of gas accretion and angular momentum in the circumgalactic medium (CGM) using high-resolution FIRE cosmological simulations. Our analysis includes halos spanning the critical $\sim 10^{12}\ \mathrm{M}_{\odot}$ scale where several transitions have been identified, including inner CGM virialization, the transition from bursty to steady star formation, and the emergence of thin disks. We find that the temperature of inflowing gas is correlated with the virialization of the inner CGM. CGM inflows are almost entirely cold ($T < 10^5$ K) in pre-virialized halos, while hot inflows ($T > 10^5$ K) dominate in virialized halos. When hot inflows dominate, cooling generally occurs simultaneously with circularization at galaxy radii. The dominance of hot inflows onto massive galaxies persists even at high redshift, where cold streams may coexist. Consistent with previous studies, cold inflows have higher specific angular momentum than dark matter and hot gas. However, in bursty, low-mass galaxies, cold inflows do not circularize prior to star formation, while in steady, massive galaxies, hot inflows circularize, cool, and form stars with disk-like kinematics. We additionally find that in bursty galaxies, accreted gas typically forms stars after residing in the galaxy for less than $\sim 5$ galaxy free-fall times, while in steady galaxies, gas can persist for up to $\sim 25$ free-fall times before forming stars. This highlights a key difference between star formation in bursty galaxies fed by cold accretion and steady equilibrium disks fed by hot accretion.
#### An Improved Fit for Linear Halo Bias at High Redshift
 - **Authors:** Kuan Wang, Julian B. Muñoz, L. Y. Aaron Yung
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2604.14312

 - **Pdf link:** https://arxiv.org/pdf/2604.14312

 - **Abstract**
 High- to ultrahigh-redshift clustering of halos provides a powerful tool to understand cosmology and galaxy formation. However, theoretical predictions are not firmly established in the first billion years, where current and upcoming surveys are beginning to reach percent-level precision. Here we measure dark matter halo biases at $z=6$ - 19 from simulation data, and find they are $\sim$ 3 - 4$\%$ higher than canonical results calibrated at low $z$. We provide an updated linear-bias fit at these early times, reducing the mean systematic offset to $< 1\%$. These results will enable robust interpretation of early-Universe galaxy clustering from JWST, Roman, and intensity-mapping surveys.
#### FAIR Universe Weak Lensing ML Uncertainty Challenge: Handling Uncertainties and Distribution Shifts for Precision Cosmology
 - **Authors:** Biwei Dai, Po-Wen Chang, Wahid Bhimji, Paolo Calafiura, Ragansu Chakkappai, Yuan-Tang Chou, Sascha Diefenbacher, Jordan Dudley, Ibrahim Elsharkawy, Steven Farrell, Isabelle Guyon, Chris Harris, Elham E Khoda, Benjamin Nachman, David Rousseau, Uroš Seljak, Ihsan Ullah, Yulei Zhang
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Data Analysis, Statistics and Probability (physics.data-an)
 - **Arxiv link:** https://arxiv.org/abs/2604.14451

 - **Pdf link:** https://arxiv.org/pdf/2604.14451

 - **Abstract**
 Weak gravitational lensing, the correlated distortion of background galaxy shapes by foreground structures, is a powerful probe of the matter distribution in our universe and allows accurate constraints on the cosmological model. In recent years, high-order statistics and machine learning (ML) techniques have been applied to weak lensing data to extract the nonlinear information beyond traditional two-point analysis. However, these methods typically rely on cosmological simulations, which poses several challenges: simulations are computationally expensive, limiting most realistic setups to a low training data regime; inaccurate modeling of systematics in the simulations create distribution shifts that can bias cosmological parameter constraints; and varying simulation setups across studies make method comparison difficult. To address these difficulties, we present the first weak lensing benchmark dataset with several realistic systematics and launch the FAIR Universe Weak Lensing Machine Learning Uncertainty Challenge. The challenge focuses on measuring the fundamental properties of the universe from weak lensing data with limited training set and potential distribution shifts, while providing a standardized benchmark for rigorous comparison across methods. Organized in two phases, the challenge will bring together the physics and ML communities to advance the methodologies for handling systematic uncertainties, data efficiency, and distribution shifts in weak lensing analysis with ML, ultimately facilitating the deployment of ML approaches into upcoming weak lensing survey analysis.
#### NOMAI : A real-time photometric classifier for superluminous supernovae identification. A science module for the Fink broker
 - **Authors:** E. Russeil, R. Lunnan, J. Peloton, S. Schulze, P. J. Pessi, D. Perley, J. Sollerman, A. Gkini, Y. Hu, T.-W. Chen, E. C. Bellm, T. X. Chen, B. Rusholme
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); High Energy Astrophysical Phenomena (astro-ph.HE); Data Analysis, Statistics and Probability (physics.data-an)
 - **Arxiv link:** https://arxiv.org/abs/2604.14761

 - **Pdf link:** https://arxiv.org/pdf/2604.14761

 - **Abstract**
 Superluminous supernovae (SLSNe) are one of the most luminous stellar explosions known, yet they remain poorly understood. Because they are intrinsically rare, efficiently identifying them in the large alert streams produced by modern time-domain surveys is essential for enabling spectroscopic follow-up. We present NOMAI, a machine learning classifier designed to identify SLSN candidates directly from photometric alerts in the ZTF stream, using light curves accumulated over at least 30 days. It does not require any spectroscopic redshift and is running in real time within the Fink broker. ZTF light curves are transformed into a set of physically motivated features derived primarily from model-fitting procedures using SALT2 and Rainbow, a blackbody-based multi-band fitting framework. These features are used to train an XGBoost classifier on a curated dataset of labeled ZTF sources constructed using literature samples of SLSNe, along with TNS and internal ZTF labeled sources. The final training dataset contains 5280 unique sources, including 225 spectroscopically classified SLSNe. On the training sample, the classifier reaches 66% completeness and 58% purity. Deployed within the Fink broker, NOMAI has been running continuously since 18/12/2025 on the ZTF alert stream and publicly reports SLSN candidates every night by automatically posting them to dedicated communication channels. Based on this, we also report the first two-month as an evaluation period, where the classifier successfully recovered 22 of the 24 active SLSNe reported on the Transient Name Server. The achieved performances demonstrate that the classifier provides a valuable tool for experts to efficiently scan the alert stream and identify promising candidates. In the near future, NOMAI is intended to be adapted to operate on the Legacy Survey of Space and Time conducted by the Vera C. Rubin Observatory.
#### Do galaxy mergers increase star formation and turbulence at cosmic noon?
 - **Authors:** I. Kanowski, J. T. Mendel, E. Wisnioski, N. M. Förster Schreiber, A. Marchal, T. Tsukui
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2604.15002

 - **Pdf link:** https://arxiv.org/pdf/2604.15002

 - **Abstract**
 Mergers and interactions can significantly affect the morphological and dynamical properties of galaxies, however the impact of mergers on turbulence at $z > 1$ has not been observationally constrained. In this work we use the interaction strength parameter $Q_P$ to identify likely interacting and isolated galaxies at cosmic noon ($z \sim 1-2$) within the KMOS\textsuperscript{3D} integral field spectroscopy survey, utilising redshifts from the 3D-HST, CANDELS and UVCANDELS surveys. For $186$ galaxies, we measure deconvolved H$\alpha$ kinematics, including velocity dispersion, using a spatially non-parametric approach to account for observational effects in the dynamically diverse range of galaxies. We compare offsets in H$\alpha$ flux, star formation rate (SFR), dust attenuations, and velocity dispersion of likely interacting galaxies to isolated control galaxies matched in mass and lookback time. We find increased H$\alpha$ fluxes and SFRs in the likely interacting sample at the level of $\sim 0.1$ dex, a similar enhancement to studies of local pairs. In contrast, we find no significant increase in the level of velocity dispersion in interacting galaxies compared to their controls. The lack of increase in dispersion may reflect a combination of physical and observational factors, including limits to increasing turbulent motions in an already turbulent medium and spectral resolution limits.
#### Cosmology of Inelastic Self-Interacting Dark Matter: Linear Evolution and Observational Constraints
 - **Authors:** Xin-Chen Duan, Yue-Lin Sming Tsai, Ziwei Wang
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2604.15006

 - **Pdf link:** https://arxiv.org/pdf/2604.15006

 - **Abstract**
 We study the linear cosmological evolution of inelastic self-interacting dark matter in a two-component dark sector with a small mass splitting, assuming thermal initial conditions for the two species. We derive the coupled background and perturbation equations for inelastic conversion between the two species, considering both Power-law and Low-velocity saturation cross sections. Exothermic conversion injects kinetic energy into the light component, generating pressure support that suppresses small-scale structure and produces dark acoustic oscillations in the matter power spectrum. The resulting cutoff at scale $k > 1\,h\,\mathrm{Mpc}^{-1}$ depends on the normalization and velocity dependence of the cross section, the dark matter mass and the mass splitting. Using linear power spectra computed with a modified Boltzmann solver, we apply recast constraints from Lyman-$\alpha$ forest data and high-redshift UV luminosity functions, finding non-monotonic but closed exclusion regions driven by the competition between efficient conversion and rapid depletion of the heavy component. These results show that the internal thermodynamics of a secluded multi-component dark sector can leave observable imprints on structure formation, providing a complementary probe of dark matter beyond Standard Model interactions.
#### Localization and Confidence Region Estimation of Short GRBs with the COSI BGO Shield Using a HEALPix-Based Deep Learning Approach
 - **Authors:** N. Parmiggiani, A. Bulgarelli, G. Panebianco, E. Burns, E. Neights, V. Fioretti, I. Martinez-Castellanos, L. Castaldini, A. Ciabattoni, A. Di Piano, R. Falco, S. Gallego, G. Mustafa, P. Patel, A. Rizzo, E. A. Wulf, D. H. Hartmann, C. A. Kierans, J. A. Tomsick, A. Zoglauer
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2604.15119

 - **Pdf link:** https://arxiv.org/pdf/2604.15119

 - **Abstract**
 The Compton Spectrometer and Imager is a NASA satellite mission under development that will survey the entire sky in the 0.2-5 MeV range using a wide-field germanium detector array, surrounded on the sides and bottom by active shields (the Anticoincidence Subsystem, ACS). The ACS aims to suppress and monitor background events, as well as detect transient sources, such as Gamma-Ray Bursts (GRBs), through its onboard triggering algorithm. The data related to GRBs are sent to the ground and analyzed by an automated pipeline to localize the GRBs and share their positions with the community. In this work, we present a brief GRB localization method based on ACS data, utilizing deep learning (DL) techniques, which can estimate the 90\% confidence region, including cases where it is split into multiple areas. To address this, we developed a neural network classifier that predicts the GRB location as a probability distribution across the sky map following the HEALPix framework. The distribution can be used to compute the 90\% confidence regions. Future work will compare this DL-based localization approach with classical methods such as $\chi^2$ fitting and Maximum Likelihood Estimation.
#### Stellar nucleosynthesis in the era of large surveys: s-process polluted binaries in GALAH DR4
 - **Authors:** A. Escorza, S. Vitali, D. Godoy-Rivera, S. Shetye, H. Van Winckel, G. Bustos, S. Goriely, L. Siess, M. Abdul-Masih, T. Masseron, D. A. García-Hernández, A. Ardern-Arentsen, P. Jofré, S. Van Eck
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2604.15197

 - **Pdf link:** https://arxiv.org/pdf/2604.15197

 - **Abstract**
 Binary interactions during the AGB phase can lead to the formation of chemically peculiar stars with overabundances of s-process elements. Only a few hundreds of these stars have been subject to detailed chemical or dynamical studies. This work aims at compiling a systematic sample of s-process-polluted candidates using GALAH DR4. We also want to compare their properties with those of confirmed s-polluted stars to have stronger evidence of their nature. GALAH DR4 uses neural networks and automatic spectral analysis methods as well as data of a lower spectral resolution than normally used to characterise these objects. Because of this, we built a validation sample, for which we obtained UVES@VLT and HERMES@Mercator high-resolution spectra. We compare our stellar parameters and abundances with those of the survey and use this validation to define the thresholds that a star in GALAH DR4 must pass to be flagged as a good s-process-rich candidate. Based on our comparisons, we define thresholds on [s/Fe], [Y/Fe], [Zr/Fe], [Ba/Fe], and [La/Fe]. We identified 1073 stars in GALAH DR4 that are good candidates to be s-process polluted stars, covering a broad parameter space. They share many similarities with the samples of confirmed s-rich stars, especially their ratios of heavy over light s-elements ([hs/ls]), which strengthen our confidence in the purity of the sample. We find that only 7% of the candidates have measured orbital periods and eccentricities, limiting for now a full comparison with confirmed Ba and related stars. However, their binary fraction is, as expected, higher than the one we found for the full GALAH DR4 catalogue. Our sample of candidates is almost five times larger than the number of currently confirmed polluted stars. This and the fact that it has been homogeneously treated by GALAH open very interesting avenues to confront nucleosynthesis and binary evolution models.


by olozhika (Xing Yuchen). 


2026-04-17
