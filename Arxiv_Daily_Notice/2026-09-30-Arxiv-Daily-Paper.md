# Showing new listings for Wednesday, 30 September 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 7papers 
#### SIFARI: Self-Supervised Interferometric Fitting for Astronomical Radio Imaging
 - **Authors:** Shunyuan Mao, Andrea Isella, Paris Perdikaris, Li-Ta Lo, Hui Li
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Earth and Planetary Astrophysics (astro-ph.EP); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2609.35966

 - **Pdf link:** https://arxiv.org/pdf/2609.35966

 - **Abstract**
 Radio-interferometric images are reconstructed from sparsely sampled visibilities, and CLEAN-based imaging can struggle with spatial filtering, complex morphologies, and uncertainty quantification. Alternative methods that fit visibilities directly can address some of these limitations but often require manual choices of image priors and model hyperparameters. We present SIFARI (Self-Supervised Interferometric Fitting for Astronomical Radio Imaging), a self-supervised neural network workflow that represents sky brightness as a continuous function of position and fits measured visibilities without an external image training set or explicit spatial regularizer. An empirical rule sets the Fourier feature scale from the visibilities before training, controlling how readily the network fits fine structure. Sampling network weights with Stochastic Weight Averaging-Gaussian (SWAG) gives approximate brightness uncertainty estimates, which we combine with a thermal-noise floor to construct spatially resolved signal-to-noise maps. In synthetic ALMA tests, SIFARI yields an effective point-source response about eight times narrower than the natural-weighting CLEAN restoring beam and recovers more extended flux than CLEAN when short baselines are missing. It also achieves higher image fidelity than the restored CLEAN images in all three morphology benchmarks. Applied to ALMA observations of PDS 70, SIFARI recovers the bright outer ring together with faint compact emission in the central cavity. For long-baseline-only WISPIT 2 data, SIFARI supplies a sky model for phase self-calibration where the CLEAN model is inadequate. The restored, self-calibrated SIFARI image has approximately 30% lower RMS noise than the CLEAN image made from the original visibilities without self-calibration.
#### Probing Baryons with the Kinematic Sunyae Zel'dovich Effect and Machine Learning Derived Peculiar Velocities using DESI DR2 and ACT DR6
 - **Authors:** Yulin Gong, Rachel Bean, Patricio A. Gallardo, Boryana Hadzhiyska, Yun-Hsin Hsu, Jenna Moore, Eve M. Vavagiakis, Nicholas Battaglia, J. Aguilar, S. Ahlen, A. Aviles, F. Beutler, D. Bianchi, D. Brooks, A. Carnero Rosell, T. Claybaugh, A. de la Macorra, Arjun Dey, Biprateep Dey, P. Doel, A. Font-Ribera, J. E. Forero-Romero, E. Gaztañaga, G. Gutierrez, K. Honscheid, S. Juneau, T. Karim, R. Kehoe, D. Kirkby, A. Kremin, O. Lahav, M. Landriau, L. Le Guillou, M. Manera, A. Meisner, R. Miquel, S. Nadathur, J. A. Newman, H. E. Noriega, E. Paillas, N. Palanque-Delabrouille, W. J. Percival, F. Prada, I. Pérez-Ràfols, C. Ravoux, G. Rossi, L. Samushia, E. Sanchez, C. Saulder, D. Schlegel, M. Schubnell, H. Seo, J. Silber, M. Siudek, G. Tarlé, B. A. Weaver, R. Zhou
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2609.36355

 - **Pdf link:** https://arxiv.org/pdf/2609.36355

 - **Abstract**
 We present novel empirical constraints on average optical depths and gas density profiles from combining kinematic Sunyaev Zel'dovich effect (kSZ) measurements and nonlinear peculiar velocities, reconstructed using machine learning, for massive halos traced by DESI DR2 luminous red galaxies (LRG). The pairwise kSZ is measured using two ACT DR6 cosmic microwave background (CMB) temperature maps (ILC and 150 GHz maps) for seven luminosity-selected LRG samples. We find consistent results between the two maps and significant detections across the samples. We reconstruct LRG line-of-sight peculiar velocities in two cosmic epochs, centered on $z=$ 0.55 and 0.8, using a simulation-trained Transformer machine learning model to extend beyond the linear approximation. Average optical depths are inferred by comparing the kSZ pairwise correlation to the measured pairwise velocity correlation from the reconstructed velocity field and, separately, from a theoretical prediction using the best fit Planck cosmology, with the highest significance reaching SNR = 14.2 and 15.1 respectively. We also obtain velocity-weighted AP-filtered kSZ-stacked cluster density profiles, which show evidence of extended ionized gas around massive LRG groups and no strong redshift evolution within current measurement uncertainties. These results demonstrate the power of combining spectroscopic galaxy and CMB data, and employing machine learning methods, to probe diffuse baryons and coherent large-scale velocity fields. They open up new avenues to leverage upcoming galaxy survey data from Euclid, Roman and Rubin LSST, in tandem with multi-frequency CMB/sub-mm data from CCAT and Simons Observatory.
#### LUMA: A CNN for Strong Gravitational Lens Searches in Astronomical Imaging
 - **Authors:** Giovanni Vincenzo Donatiello, Achille A. Nucita, Francesco De Paolis, Antonio Franco, Francesco Strafella
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2609.36857

 - **Pdf link:** https://arxiv.org/pdf/2609.36857

 - **Abstract**
 We present LUMA, a convolutional neural network (CNN) pipeline for the automated detection of strong gravitational lenses in simulated astronomical imaging. The method combines a physically motivated preprocessing stage, which enhances faint arc and ring features, with a compact three-block CNN trained using class reweighting and modern learning-rate scheduling. On simulated data, the model reaches test accuracies of about $96$\% and receiver operating characteristic (ROC) area-under-the-curve (AUC) values of $\simeq 0.99$ for the non-trivial classes, while confusion-matrix analysis shows high completeness and purity for lens candidates. These results demonstrate that relatively lightweight CNN architectures can provide a competitive baseline for strong-lens searches, and they motivate future extensions toward real survey images and transformer-based models.
#### Detecting Extragalactic Exoplanets With Fast Radio Burst Nanolensing
 - **Authors:** Kenneth F. Olibrice, Dylan L. Jow
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP); Astrophysics of Galaxies (astro-ph.GA); High Energy Astrophysical Phenomena (astro-ph.HE); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2609.36988

 - **Pdf link:** https://arxiv.org/pdf/2609.36988

 - **Abstract**
 Fast Radio Bursts (FRBs) are spatially and temporally compact sources at cosmological distances. As background sources, they will be uniquely sensitive to the gravitational lensing of exoplanets outside of our own galaxy. We present a method to detect extragalactic exoplanets using planetary echo nanolensing-periodic, nanosecond-scale variations in the relative time of arrival (ToA) between an initial FRB and its microlensed echo as the planet orbits its host star. For a simple binary lens model, we demonstrate that measuring the amplitude and period of these ToA fluctuations enables a determination of the exoplanet mass and orbital parameters. FRBs will be most sensitive to echo nanolensing by lenses within ten megaparsecs of the Milky Way as well as within ten megaparsecs of the FRB host, opening the door to detections of planets at a range of redshifts. We estimate that at least one in a million FRBs will exhibit this phenomenon (i.e. an optical depth of $\tau_l = 10^{-6}$). While current burst rates and low repeating-FRB fractions make a detection challenging in the immediate term, upcoming high-volume surveys and next-generation arrays (such as the SKA Phase 2) will bring the unambiguous detection of extragalactic exoplanets across cosmological redshifts into possibility.
#### The ALPINE-CRISTAL-JWST Survey: Investigating the role of interstellar dust, gas and stars in high-z galaxies at kpc-scales
 - **Authors:** F. Lopez, M. Relano, I. De Looze, A. L. Faisst, R. Herrera-Camus, R. A. Jorgenson, E. Pérez-Montero, M. Palla, C. Accard, R. O. Amorin, M. Aravena, R. J. Assef, A. J. Battisti, M. Boquien, E. da Cunha, P. Dam, R. L. Davies, M. Dessauges-Zavadsky, A. Ferrara, S. Fujimoto, M. Ginolfi, N. Gutierrez-Vera, A. Hadi, E. Ibar, H. Inami, A. M. Koekemoer, L. L. Lee, J. Li, J. Molina, A. Nanni, D. Narayanan, F. Pozzi, F. Rizzo, M. Romano, D. B. Sanders, P. Sawant, L. Vallini, S. A. van der Giessen, V. Villanueva, G. Zamorani
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2609.37358

 - **Pdf link:** https://arxiv.org/pdf/2609.37358

 - **Abstract**
 A comprehensive understanding of galaxy evolution requires a detailed analysis of gas and dust, their distribution, and evolution within galaxies. We analyse spatially resolved (~kpc) rest-frame [CII] and dust continuum ALMA observations together with JWST/NIRSpec IFU data of a sample of galaxies at z~4-5. We focus on deriving the spatial distributions of atomic and molecular gas masses, dust and stellar masses, star formation rates (SFR), and metallicity. The oxygen abundance maps have values in the range of 12+log(O/H)~8.1-8.3 with variations of the order of 1dex within the same galaxy. The calibration used in this study to estimate the atomic gas mass in our galaxies seems to overestimate the atomic gas mass surface densities up to 1-2 orders of magnitude. However, a calibration based on a spatially resolved [CII] conversion factor gives a more robust estimation of the total gas mass. Galaxies exhibiting signatures of strong outflows have lower dust-to-stellar surface mass density ratio and lower gas mass fractions than the galaxies with no outflow signatures. While the latter is consistent with these galaxies ejecting part of their gas reservoir to the circumgalactic medium, the low dust-to-stellar surface mass density ratios also suggest that part of the dust content is expelled outside the galaxy, which reinforces previous theoretical suggestions of dust removal by stellar feedback or radiation pressure to explain the high UV luminosities in galaxies at very high-redshifts. Some galaxies of our sample have almost an order of magnitude higher dust-to-gas and dust-to-stellar surface mass density ratio than galaxies in the local Universe, suggesting that a large dust reservoir has been built up already at time scales of ~1 Gyr in these galaxies.
#### Detecting HI Self-Absorption using Neural Networks
 - **Authors:** Eric G. M. Muller, Naomi M. McClure-Griffiths, Hiep Nguyen, Matthew J. Alger, Frances Buckland-Willis, J. R. Dawson, Min-Young Lee, Antoine Marchal
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2609.38042

 - **Pdf link:** https://arxiv.org/pdf/2609.38042

 - **Abstract**
 Cold atomic hydrogen plays a crucial role in the life cycle of interstellar gas. It serves as the intermediary phase in the condensation and cooling processes that bridge the warm diffuse gas in and around galaxies, and the cold molecular gas that drives star formation. HI self-absorption in the 21-cm emission line is the most direct observational tracer of cold HI gas that does not require a continuum background source, yet its systematic extraction remains a long-standing challenge. Existing methods of self-absorption identification rely on subjective by-eye inspection or modelling of the underlying emission, making repeatable, thorough, and large-scale applications difficult. We present a lightweight convolutional neural network designed to detect self-absorption features and infer their velocities via a post-hoc process, without assumptions about the underlying emission or the use of ancillary data. Trained on synthetic emission spectra, the neural network achieves 96.5 per cent accuracy, 96.0 per cent precision, and 97.0 per cent recall on held-out synthetic data. Applied to observed 21-cm emission data from the Riegel--Crutcher cloud and giant molecular filament regions towards the Galactic Plane, the network recovers the spatial distributions and velocities of known self-absorption structures when compared to previous analyses and ancillary 13CO emission data. Crucially, the neural network is computationally efficient, processing detections for ~15,000 spectra per second on a single consumer laptop GPU, enabling real-time cold HI detection at the data rates anticipated by next-generation facilities such as the Square Kilometre Array.
#### LYRA: The formation and growth of nuclear star clusters in dwarf galaxies
 - **Authors:** Joaquin Sureda, Azadeh Fattahi, Sownak Bose, Mariya Lyubenova, Jessica E. Doppel, Thales Gutcke, Katja Fahrion, Rüdiger Pakmor
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2609.38179

 - **Pdf link:** https://arxiv.org/pdf/2609.38179

 - **Abstract**
 Nuclear star clusters (NSCs) are dense massive star clusters ubiquitous in galactic centres across various mass regimes, present in up to $\sim30$ per cent of dwarf galaxies with $M_\star<10^{7}\, \mathrm{M}_\odot$. Although their main growth pathways are well studied, there is still ongoing debate regarding their formation. We use the LYRA cosmological hydrodynamical simulations to study the formation and growth of NSCs in a sample of six dwarf galaxies, where we identify NSCs with masses $M_\mathrm{NSC} \sim 10^4 - 10^6 \, \mathrm{M}_\odot$ in all galaxies in our sample. The NSCs in our sample emerge at early times as a compact component, with the host galaxy growing around them. This is consistent with a scenario in which NSCs are among the earliest structures to form in a galaxy. We characterise the origin of the stars that constitute the NSCs and explore the properties of the stellar populations in each of these channels. We find that most of the NSC mass originates from in-situ star formation within the NSCs themselves. While this might appear at odds with current observations, the bulk of this star formation occurs at early times, resulting in a significant population of old and metal-poor stars, in agreement with an early NSC formation. We also identify galaxy-galaxy mergers as a significant contributor to the NSC mass, with usually one merger dominating this contribution. Our results highlight the complexity in the growth history of NSCs in dwarf galaxies and highlight the importance of considering additional growth channels for NSCs in dwarfs galaxies.


by olozhika (Xing Yuchen). 


2026-09-30
