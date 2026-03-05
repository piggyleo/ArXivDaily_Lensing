# Showing new listings for Thursday, 5 March 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 6papers 
#### Mature but Still Growing: JWST Detection of the Earliest Intracluster Light at z ~ 2
 - **Authors:** Hyungjin Joo, M. James Jee, Kyle Finner, Zachary P. Scofield, Sangjun Cha, Jinhyub Kim, Ranga-Ram Chary, Andreas Faisst, Bomee Lee
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2603.03427

 - **Pdf link:** https://arxiv.org/pdf/2603.03427

 - **Abstract**
 We present a JWST analysis of intracluster light (ICL) in XLSSC 122 at z = 1.98, currently the most distant known strong lensing galaxy cluster with an evolved member population. Using deep JWST imaging complemented by HST data and careful control of systematics, we robustly detect diffuse emission extending to several hundred kpc from the brightest cluster galaxy (BCG) down to about 29 mag arcsec^-2. Multi component PSF convolved Sersic modeling separates the surface brightness profiles into three components: a BCG core, a BCG envelope, and an ICL component, with stable Sersic indices across wavelengths. Nearly flat color profiles indicate minimal radial variation in the stellar populations of the BCG envelope and the ICL. The median ICL fraction measured across seven bands is about 17 percent, demonstrating that the buildup of intracluster stars in massive halos was already well underway by z about 2. The ICL fraction peaks near 5000 Angstrom in the rest frame, resembling the behavior observed in dynamically active clusters. We also detect a southern excess of ICL relative to the best fit Sersic model and quantify it using wavelet based modeling, providing additional support that this system is dynamically active. The BCG + ICL light distribution and strong lensing mass map show strong morphological agreement within about 100 kpc. These findings establish the ICL as an early forming and dynamically informative component of massive halos.
#### Cosmology with the line-of-sight shear of strong gravitational lenses
 - **Authors:** Pierre Fleury, Daniel Johnson, Théo Duboscq, Natalie B. Hogg, Julien Larena
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); General Relativity and Quantum Cosmology (gr-qc)
 - **Arxiv link:** https://arxiv.org/abs/2603.03441

 - **Pdf link:** https://arxiv.org/pdf/2603.03441

 - **Abstract**
 Stage-IV photometric galaxy surveys are designed to measure the position and shapes of billions of galaxies. Their aim is to characterise the large-scale distribution of matter in the Universe using galaxy clustering and weak gravitational lensing. As a byproduct, stage-IV surveys are expected to detect more than a hundred thousand strong gravitational lenses. In this article, we propose the use of weak-lensing perturbations to strong lenses, specifically their line-of-sight (LOS) shear, as a cosmological probe. This new observable allows us to define three new correlation functions: the LOS shear with itself, with galaxy positions, and with galaxy shapes, thereby promoting the standard $3\times 2$pt correlation method to a $6\times 2$pt scheme. We design estimators for these new correlation functions and determine their expectation values as a function of the matter power spectrum. We then derive the analytical expression for the full covariance matrix of the $6\times 2$pt correlation scheme. Considering various scenarios for the stage-IV strong-lensing samples, we demonstrate that the cosmological information carried by the LOS shear of strong lenses will be detectable with a very high signal-to-noise ratio, even in the most pessimistic of cases. Strong lenses are thus extremely promising cosmological probes, whose synergy with galaxy positions and shapes should also contribute to mitigating systematics in stage-IV surveys.
#### Autoencoder-based framework for anomaly detection in stellar spectra: application to the MaNGA Stellar Library
 - **Authors:** Akihiro Suzuki
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2603.03734

 - **Pdf link:** https://arxiv.org/pdf/2603.03734

 - **Abstract**
 A machine-learning-based method is developed to identify objects with unusual stellar spectra. The method employs an autoencoder, a neural network trained to compress spectral data into a low-dimensional representation and subsequently reconstruct it. Spectra that deviate significantly from the dominant patterns in the training dataset are identified using the reconstruction error as an anomaly score. The models are applied to selected datasets from the MaNGA Stellar Library, an empirical library of stellar spectra. Several spectra are flagged as anomalous: an object with likely instrumental and/or reduction issues, two carbon stars, and an oxygen-rich thermally pulsating asymptotic giant branch star. The sources of the large reconstruction errors are examined, and the effectiveness and limitations of autoencoder-based approaches for detecting anomalous stellar spectra are discussed.
#### Morphologies for DECaLS Galaxies through a combination of non-parametric indices and machine learning methods: A comprehensive catalog using the Galaxy Morphology Extractor (galmex) code
 - **Authors:** V. M. Sampaio, Y. Jaffé, C. Lima-Dias, S. Véliz Astudillo, M. Martínez-Marín, H. Méndez-Hernández, R. Herrera-Camus, A. Monachesi
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2603.04040

 - **Pdf link:** https://arxiv.org/pdf/2603.04040

 - **Abstract**
 Galaxy morphology encodes key information about formation and evolution. Large imaging surveys require automated, reproducible methods beyond visual inspection. Non--parametric indices provide an useful framework, but their performance must be quantitatively assessed. We present a homogeneous catalog of non--parametric morphological indices for DECaLS galaxies with effective radii larger than 2 arcsec. Our goal is to evaluate the reliability of indices in separating spirals and ellipticals, test their consistency with existing classification schemes, and establish their applicability for the upcoming surveys focused in the southern hemisphere. We developed galmex, a modular Python package for preprocessing images and measuring a variety of non--parametric indices. Using bona-fide spirals and ellipticals as control samples, we assessed the discriminatory power of each index, and compared them with CNN-based T-Types and Galaxy Zoo DECaLS labels. We use the indices as input for a Light Gradient Boosted Machine (LightGBM) to obtain probabilistic classifications. Concentration is the most reliable parameter from the Concentratiom + Asymmetry + Smoothness system (CAS), while asymmetry--based indices (A and S) are limited to detecting disturbed morphologies. MEGG indices (M20, Entropy, Gini, G2) provide stronger separation and trace a gradient with T--Type. By using a simple binary (0/1) label for ellipticals/spirals, classifiers trained on non--parametric indices achieve high accuracy and well--calibrated probabilities, dominated by entropy, concentration, and Gini. We release the first public catalog of CA[A_S]S+MEGG indices for DECaLS, together with galmex. We combine the non-parametric indices with machine learning framework to derive spiral/elliptical separation for galaxies below z~0.15 through a probabilistic approach.
#### Hierarchical cosmological constraints through strong lensing distance ratio
 - **Authors:** Shuaibo Geng, Shuo Cao, Marek Biesiada, Xinyue Jiang, Yalong Nan, Chenfa Zheng
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2603.04279

 - **Pdf link:** https://arxiv.org/pdf/2603.04279

 - **Abstract**
 Strong gravitational lensing provides an independent and powerful probe of cosmic expansion by directly linking observables to cosmological distances. Upcoming surveys such as LSST will discover large number of galaxy-galaxy strong lensing systems, offering a new route to precise cosmological constraints. In this paper, we propose a Fisher-like sensitivity factor to map how the cosmological information of strong-lensing distances changes across the lens-source redshift plane. Applying such factor to the distance ratio $D_{ls}/D_s$, the time-delay distance $D_{\Delta t}$, and the double-source-plane ratio, we determine the ``sensitivity valleys'' where an observable becomes insensitive to a given parameter. The realistically simulated LSST lens population, which largely lies outside the distance-ratio valleys, covers the most sensitive region for $(w_0,w_a)$ parameter space. We then develop a new hierarchical framework, which could calibrate the redshift evolution of lens mass-density slopes and constrain cosmological parameters simultaneously. Focusing on the LSST mock data, we demonstrate that ignoring mass-profile evolution can bias $\Omega_m$ by up to $\sim 10\sigma$, while modeling the lens evolution could perfectly recovers the fiducial cosmology and yield stringent cosmological constraints (e.g., $\Delta\Omega_m \simeq 0.01$ and $\Delta w \simeq 0.1$ for $\sim 10^4$ lenses).
#### Post-inflationary axion constraints from the Lyman-$α$ forest
 - **Authors:** Olga Garcia-Gallego, Vid Iršič, Matteo Viel, Martin G. Haehnelt, James S. Bolton
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Physics - Phenomenology (hep-ph); High Energy Physics - Theory (hep-th)
 - **Arxiv link:** https://arxiv.org/abs/2603.04401

 - **Pdf link:** https://arxiv.org/pdf/2603.04401

 - **Abstract**
 Among the most compelling cold dark matter candidates, the axion has recently been subject to a wide range of astrophysical studies aiming to constraints its properties. We present updated bounds on the isocurvature fraction, $f_{\rm{iso}}$, which parameterizes the contribution of isocurvature perturbations induced by post-inflationary produced axion-like particles (ALPs) to the ordinary power spectrum. We use new simulations based on the Sherwood-Relics suite to fit high-resolution Lyman-$\alpha$ forest flux power spectrum data. With the published noise model of the Lyman-$\alpha$ forest data, we find a tentative detection of $f_{\rm{iso}}$ = ${0.0064^{+0.0012}_{-0.0014}}$ (68% C.L), after accounting for the degenerate effect of IGM thermal evolution. With a more conservative modelling of the residual noise in the data, the upper bound is weakened to $f_{\rm{iso}}< 0.0084$ (95% C.L), which translates into an ALP temperature-independent mass $m_a > 1.73 \times 10^{-18}$eV. Our constraints are stronger than bounds derived from large-scale structure probes at higher and lower redshifts and are competitive with those derived from UV luminosity function data. Interestingly, the best current Lyman-$\alpha$ forest data prefers a non-zero contribution from isocurvature modes.


by olozhika (Xing Yuchen). 


2026-03-05
