# Showing new listings for Wednesday, 8 July 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 8papers 
#### Uncertainty-Aware Deep Learning for the Ly$α$ Forest: CNN-Based Absorber Detection and Characterization
 - **Authors:** Paryag Sharma, Vikram Khaire, Ting-Yun Cheng, Hum Chand, Prakash Gaikwad
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.05494

 - **Pdf link:** https://arxiv.org/pdf/2607.05494

 - **Abstract**
 The Ly$\alpha$ forest is a powerful probe of the intergalactic medium and small-scale matter distribution, but deriving absorber properties traditionally requires computationally expensive Voigt-profile fitting. We present a convolutional neural network (CNN) that identifies and characterizes H I Ly$\alpha$ absorbers directly from quasar spectra. The model is trained on synthetic spectra generated from the IllustrisTNG simulation and fitted with the VIPER Voigt-profile fitting code to provide training labels. The network simultaneously predicts absorber presence, column density ($N_{\rm HI}$), Doppler parameter ($b_{\rm HI}$), and line centroid. On simulated spectra, the CNN achieves an F1 score of $\sim$0.8, with mean absolute errors of $\sim$0.18 in $\log N_{\rm HI}$ and $\sim$0.10 in $\log b_{\rm HI}$. It accurately reproduces the H I column density distribution function (CDDF) and the $b_{\rm HI}$--$N_{\rm HI}$ relation, recovering CDDF slopes consistent with VIPER and a lower-envelope relation with an RMS difference of only 0.36 km s$^{-1}$. Applied to high-resolution UVES spectra, performance decreases to an F1 score of $\sim$0.5, with mean absolute errors of $\sim$0.34 in $\log N_{\rm HI}$ and $\sim$0.21 in $\log b_{\rm HI}$. Latent-space analysis reveals a significant domain shift between the simulated and observational spectra, contributing to the reduced performance. Nevertheless, the CNN preserves the observed CDDF and $b_{\rm HI}$--$N_{\rm HI}$ distributions, yielding CDDF slopes consistent with VIPER and a lower-envelope RMS difference of 2.96 km s$^{-1}$. Monte Carlo dropout is implemented during inference to quantify predictive uncertainties. Together with its computational efficiency, the method provides a scalable and uncertainty-aware framework for Ly$\alpha$ forest analysis in upcoming spectroscopic surveys.
#### The tidal features of the classical Milky Way satellites: Expected in MOND but inconsistent with cold dark matter models
 - **Authors:** Elena Asencio, Indranil Banik, Pavel Kroupa
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.05502

 - **Pdf link:** https://arxiv.org/pdf/2607.05502

 - **Abstract**
 Most classical satellites of the Milky Way are known to display signs of tidal disturbance (e.g. tidal tails, substructures, and distorted shapes). This cannot be explained by the standard model of cosmology due to its prediction that the dark matter haloes of the classical satellites confer them with very strong self-gravity and make them resilient to the Milky Way's gravitational tides. In this work, we estimate the tidal susceptibility of the classical satellites by comparing their half-mass radius with their theoretical tidal radius at pericentre in both the standard model and in the Milgromian dynamics (MOND) model. With this approach, we demonstrate that most classical satellites are expected to be tidally perturbed in MOND, so their observed tidal features are generally in good agreement with MOND expectations. Since gravitational tides can also enhance the velocity dispersion of the satellites, we argue that MOND can plausibly explain the unusually high velocity dispersions reported for some of the classical satellites.
#### A Novel Implementation of Self-Interacting Dark Matter in AREPO
 - **Authors:** Oliver Zier, Xuejian Shen, Vinh Tran, Martin Rosenlyst, Mark Vogelsberger, Rongrong Liu
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Astrophysical Phenomena (astro-ph.HE); High Energy Physics - Phenomenology (hep-ph); High Energy Physics - Theory (hep-th)
 - **Arxiv link:** https://arxiv.org/abs/2607.05504

 - **Pdf link:** https://arxiv.org/pdf/2607.05504

 - **Abstract**
 Self-interacting dark matter (SIDM) influences halo structure through collisional heat transport and may solve several small-scale puzzles in structure formation. SIDM creates thermalized cores in low-mass haloes, which may account for the observed cored dwarf galaxies. During late-time gravothermal core collapse, SIDM can produce dense low-mass DM haloes and substructures detected through perturbations to cold stellar streams and strong gravitational lenses. In this work, we present a new Monte-Carlo SIDM implementation in the moving-mesh code AREPO-2, designed for efficiency, scalability, and extensibility. The central feature of the implementation is a dedicated DM-only neighbour-search tree that decouples the scattering solver from gravity. This preserves compatibility with the hierarchical time integration used by AREPO-2 while leaving the optimized gravity solver unconstrained. A pairwise communication scheme between MPI tasks allows tracking multiple scattering events in a single timestep while conserving momentum and energy and maintaining parallel consistency by construction. This is complemented by a per-pair timestep criterion that significantly reduces unnecessary timestep restrictions. The implementation natively supports velocity-dependent cross-sections and inelastic interactions, while a compact interface is designed for additional SIDM physics to be implemented without knowledge of the parallelization layer. We validate the implementation for isotropic, elastic scattering using a suite of idealized and cosmological tests. We assess performance and scalability in isolated core-collapse simulations and in cosmological boxes, both DM-only and with baryons. Except during the late stages of gravothermal collapse, SIDM simulations incur only modest overhead relative to the corresponding CDM runs and are substantially faster than the previous SIDM implementation in AREPO-1.
#### The dark matter halo mass function in the $Λ\mathrm{CDM}$ cosmology at all times and over all scales -- from planetary to galaxy cluster masses
 - **Authors:** Haonan Zheng, Sownak Bose, Carlos S. Frenk, Liang Gao, Adrian Jenkins, Shihong Liao, Yizhou Liu, Volker Springel, Jie Wang, Simon D. M. White
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.05505

 - **Pdf link:** https://arxiv.org/pdf/2607.05505

 - **Abstract**
 The dark matter halo mass function is one of the most fundamental predictions of structure formation theory and cosmological simulations. We present the full halo mass function in the $\Lambda$ cold dark matter ($\Lambda\mathrm{CDM}$) model, ranging from a planetary mass ($10^{-6}\,\mathrm{M}_\odot$; the thermal cutoff in the initial power spectrum for a fiducial CDM particle mass of $100\,\mathrm{GeV}$) to the mass of a rich galaxy cluster ($10^{15.5}\,\mathrm{M}_\odot$), and from redshift, $z=30$ to the present. To span this very large dynamic range, we combine our earlier Voids-within-Voids-within-Voids (VVV) set of simulations (Wang et al) with large volume, lower resolution cosmological simulations. We develop a subsampling method to extract subvolumes from the original simulations, allowing us to reconstruct the global halo mass function from the biased underdense VVV regions. We show that the results agree reasonably well among the sets of simulations on different scales and environments. We provide a fitting formula for the dark matter halo mass function based on the work of Reed et al. calibrated with our simulations, such that it can be applied at all scales, all environments and all times, with deviations of $\sim2-3\%$ at $z < 2$ and $\sim 7\%$ at higher redshift $z \gtrsim 5$. This formula is also accurate at least for a restricted set of models we tested with modest deviations from $\Lambda\mathrm{CDM}$ in the values of some of the cosmological parameters. A python code is publicly available at this https URL.
#### Warped Disk Galaxies: Alignment with the Large-Scale Tidal Field
 - **Authors:** Yiheng Wang, Huiyuan Wang, Enci Wang, Xi Kang
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.05507

 - **Pdf link:** https://arxiv.org/pdf/2607.05507

 - **Abstract**
 A possible origin of disk galaxy warps is the misalignment between galactic disks and their host dark matter halos, the orientations of which are found to be statistically aligned with the large-scale tidal field. In this work, we test this scenario by examining the alignment between warped disk galaxies and the large-scale tidal field reconstructed from the ELUCID project. We find a statistically significant alignment signal between disk orientations and the $t_1$ direction, with warped and non-warped galaxies showing different alignment behaviors. Warped galaxies show an excess of intermediate angles and a preference for orientations slightly offset from perfect parallel and perpendicular alignments. In contrast, non-warped galaxies exhibit a deficit of intermediate angles relative to random expectations, which becomes more pronounced after matching to a control sample. We also find a clear mass dependence, with high-mass warped galaxies contributing the excess of intermediate-angle signal. No significant alignment signal in warped galaxies is detected with the $t_3$ direction.
#### A Face-on View of Interstellar Dust in the Galactic Plane
 - **Authors:** Lin Zhang, Bingqiu Chen, Fei Qin, Guangxing Li, Haibo Yuan, Yi Ren
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.06016

 - **Pdf link:** https://arxiv.org/pdf/2607.06016

 - **Abstract**
 Interstellar dust is a fundamental component of the Milky Way, influencing star formation, galactic evolution, and observations across the electromagnetic spectrum. Using red clump stars selected from near- and mid-infrared photometry, together with stellar catalogs from previous studies, we construct dust density maps of the Galactic plane ({$|Z|<25$}\,pc) covering the full $360^\circ$ in longitude and reaching distances up to $7$\,kpc. By applying a U-Net convolutional neural network to invert the line-of-sight extinction distribution, we obtain dust density maps at resolutions of $10$, $50$, and $100$\,pc, which reveal detailed structures including spiral arms, inter-arm spurs, and giant cavities. The dust distribution in the Galactic plane exhibits a morphology closely resembling that of the so-called Phantom galaxy M74. The derived exponential scale length of the Galactic dust disk is $2.90$\,kpc, slightly larger than that of the stellar thin disk. Our publicly available dust maps provide a new benchmark for extinction correction, studies of Galactic structure, and the investigation of the interplay between star formation and the interstellar medium.
#### Imprint of swampland-inspired coupled early dark energy
 - **Authors:** Hao Wang, Yun-Song Piao
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.06147

 - **Pdf link:** https://arxiv.org/pdf/2607.06147

 - **Abstract**
 Inspired by the Swampland Distance Conjecture, we investigate the cosmological implications of a fractional coupling between dark matter (DM) and early dark energy (EDE) in light of the recent DESI DR2 BAO data. We use a conditional normalizing flow network to efficiently sample the high-dimensional parameter space, and perform a joint analysis of Planck CMB data, DESI DR2 BAO, PantheonPlus supernovae and SH0ES. We find that the detailed construction of the EDE potential beyond the mere existence of an EDE component possibly alter cosmological constraints on late-time dark energy when the coupling between DM and EDE is considered.
#### One with HI: Modelling HI Intensity Mapping one-point statistics including systematics
 - **Authors:** Bernhard Vos-Gines, Cora Uhlemann
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.06526

 - **Pdf link:** https://arxiv.org/pdf/2607.06526

 - **Abstract**
 Neutral hydrogen (HI) traces the dark matter distribution of the Universe. Upcoming surveys such as the Square Kilometre Array Observatory (SKAO) will trace neutral hydrogen up to z < 6 using several detection techniques including Intensity Mapping, which offers a unique window to explore the post-reionization Universe. Beyond two-point statistics promise to extract additional non-Gaussian information but require an accurate modelling of observational systematics such as foregrounds and the telescope beam. This work develops a theoretical model for the HI one-point probability density function (PDF) in spherical cells based on large-deviation statistics and spherical collapse for dark matter along with a nonlinear tracer bias and stochasticity parameterisation. It incorporates foreground removal and telescope beam effects that are validated against high-resolution simulations. We show that, despite these observational systematics, the HI PDF is able to capture additional non-Gaussian information from HI intensity maps compared to the power spectrum and can thus tighten constraints on cosmological parameters, breaking the degeneracy between the linear bias and the clustering amplitude.


by olozhika (Xing Yuchen). 


2026-07-08
