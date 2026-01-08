# Showing new listings for Thursday, 8 January 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 8papers 
#### Simulation-Based Inference for Probabilistic Galaxy Detection and Deblending
 - **Authors:** Ismael Mendoza, Derek Hansen, Runjing Liu, Zhe Zhao, Ziteng Pang, Axel Guinot, Camille Avestruz, Jeffrey Regier, the LSST Dark Energy Science Collaboration
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2601.03422

 - **Pdf link:** https://arxiv.org/pdf/2601.03422

 - **Abstract**
 Stage-IV dark energy wide-field surveys, such as the Vera C. Rubin Observatory Legacy Survey of Space and Time (LSST), will observe an unprecedented number density of galaxies. As a result, the majority of imaged galaxies will visually overlap, a phenomenon known as blending. Blending is expected to be a leading source of systematic error in astronomical measurements. To mitigate this systematic, we propose a new probabilistic method for detecting, deblending, and measuring the properties of galaxies, called the Bayesian Light Source Separator (BLISS). Given an astronomical survey image, BLISS uses convolutional neural networks to produce a probabilistic astronomical catalog by approximating the posterior distribution over the number of light sources, their centroids' locations, and their types (galaxy vs. star). BLISS additionally includes a denoising autoencoder to reconstruct unblended galaxy profiles. As a first step towards demonstrating the feasibility of BLISS for cosmological applications, we apply our method to simulated single-band images whose properties are representative of year-10 LSST coadds. First, we study each BLISS component independently and examine its probabilistic output as a function of SNR and degree of blending. Then, by propagating the probabilistic detections from BLISS to its deblender, we produce per-object flux posteriors. Using these posteriors yields a substantial improvement in aperture flux residuals relative to deterministic detections alone, particularly for highly blended and faint objects. These results highlight the potential of BLISS as a scalable, uncertainty-aware tool for mitigating blending-induced systematics in next-generation cosmological surveys.
#### An Enhanced Sample of Galactic Red Supergiants Reveals Spiral Structures
 - **Authors:** Zehao Zhang, Biwei Jiang, Yi Ren
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2601.03642

 - **Pdf link:** https://arxiv.org/pdf/2601.03642

 - **Abstract**
 Red supergiants (RSGs), representing a kind of massive young stellar population, have rarely been used to probe the structure of the Milky Way, mainly due to the long-standing scarcity of Galactic RSG samples. The Gaia BP/RP spectra (hereafter XP), which cover a broad wavelength range, provide a powerful tool for identifying RSGs. In this work, we develop a feedforward neural network classifier that assigns to each XP spectrum a probability of being an RSG, denoted as $\mathrm{P(RSG)}$. We perform ten independent runs with randomly divided training and validation sets, and apply each run to all XP spectra of stars with $G < 12$ mag. By selecting sources with $\mathrm{P(RSG)} \geq 0.9$, ten high-confidence candidate samples are obtained. A star is considered a ture Galactic RSG only if it appears in at least eight of these samples, yielding a final catalog of 2,436 objects. These RSGs show a clear spatial correlation with OB stars and trace the Galactic spiral arms well, confirming the reliability of our classification, and highlighting their potential to serve as powerful tracers of the Milky Way's structure.
#### Predicting dust temperature from molecular line data using machine learning
 - **Authors:** Tenta Dougome, Yoshito Shimajiri, Kazuya Saigo, Sanemichi Takahashi, Miyu Kido, Shu Ishibashi, Shigehisa Takakuwa
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2601.03680

 - **Pdf link:** https://arxiv.org/pdf/2601.03680

 - **Abstract**
 We conducted experiments with machine learning techniques to construct dust temperature maps from the CO isotopologue molecular line data in the Orion A molecular cloud. In the classical astrophysical methodology, multi-band continuum data are required to derive the dust temperature. The present study aims to investigate the capability and limitations of machine learning techniques to derive dust temperatures in regions without multi-band dust continuum data. We investigated how the number of pixels used for training influences prediction accuracy, and how the dust temperatures sampled in the training area influence prediction accuracy. We found that $\sim$5\% of the total number of pixels in the observational region is sufficient for training to obtain accurate predictions. Furthermore, a dust temperature sample within the training area should cover the whole temperature range and have a similar sample distribution to that of the entire observing region for an accurate prediction. The $^{12}$CO / $^{13}$CO ratio is often found to be the most important feature in predicting the dust temperature. As the $^{12}$CO / $^{13}$CO ratio is a tracer of PDR, the machine learning technique could connect the dust temperatures to the PDRs. We also found that the condition of thermal gas-dust coupling is not required for accurate prediction of the dust temperature from the molecular line data, and that machine learning is capable of capturing information more than classical astrophysical concepts.
#### Filtering interlopers with photometry and diagnostic features: A machine learning framework validated with CSST slitless spectroscopy
 - **Authors:** Hui Peng, Yu Yu, Yiyang Guo, Yizhou Gu, Run Wen, Yunkun Han, Jipeng Sui, Hu Zou, Xiaohu Yang, Pengjie Zhang, Xian Zhong Zheng, Hong Guo, Yipeng Jing, Cheng Li, Hu Zhan, Gongbo Zhao
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2601.03883

 - **Pdf link:** https://arxiv.org/pdf/2601.03883

 - **Abstract**
 The slitless spectroscopic method employed by missions such as Euclid and the Chinese Space Station Survey Telescope (CSST) faces a fundamental challenge: spectroscopic redshifts derived from their data are susceptible to emission line misidentification due to the limited spectral resolution and signal-to-noise ratio. This effect systematically introduces interloper galaxies into the sample. Conventional strict selection not only struggles to secure high redshift purity but also drastically reduces completeness by discarding valuable data. To overcome this limitation, we develop an XGBoost classifier that leverages photometric properties and spectroscopic diagnostics to construct a high-purity redshift catalog while maximizing completeness. We validate this method on a simulated sample with spectra generated by the CSST emulator for slitless spectroscopy. Of the $\sim$62 million galaxies that obtain valid redshifts (parent sample), approximately 43% achieve accurate measurements, defined as $|\Delta z| \leq 0.002(1+z)$. From this parent sample, the XGBoost classifier selects galaxies with a selection efficiency of 42.3% on the test set and 42.2% when deployed on the entire parent sample. Crucially, among the retained galaxies, 96.6% (parent sample: 96.5%) achieve accurate measurements, while the outlier fraction ($|\Delta z|>0.01(1+z)$) is constrained to 0.13% (0.11%). We verified that simplified configurations which exclude either spectroscopic diagnostics (except the measured redshift) or photometric data yield significantly higher outlier fractions, increasing by factors of approximately 3.5 and 6.3 respectively, with the latter case also introducing notable catastrophic interloper contamination. This framework effectively resolves the purity-completeness trade-off, enabling robust large-scale cosmological studies with CSST and similar surveys.
#### Towards an optimal extraction of cosmological parameters from galaxy cluster surveys using convolutional neural networks
 - **Authors:** Iñigo Sáez-Casares, Matteo Calabrese, Davide Bianchi, Marina S. Cagliari, Marco Chiarenza, Jean-Marc Christille, Luigi Guzzo
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2601.03894

 - **Pdf link:** https://arxiv.org/pdf/2601.03894

 - **Abstract**
 The possibility to constrain cosmological parameters from galaxy surveys using field-level machine learning methods that bypass traditional summary statistics analyses, depends crucially on our ability to generate simulated training sets. The latter need to be both realistic, as to reproduce the key features of the real data, and produced in large numbers, as to allow us to refine the precision of the training process. The analysis presented in this paper is an attempt to respond to these needs by (a) using clusters of galaxies as tracers of large-scale structure, together with (b) adopting a 3LPT code (Pinocchio) to generate a large training set of $32\,768$ mock X-ray cluster catalogues. X-ray luminosities are stochastically assigned to dark matter haloes using an empirical $M-L_X$ scaling relation. Using this training set, we test the ability and performances of a 3D convolutional neural network (CNN) to predict the cosmological parameters, based on an input overdensity field derived from the cluster distribution. We perform a comparison with a neural network trained on traditional summary statistics, that is, the abundance of clusters and their power spectrum. Our results show that the field-level analysis combined with the cluster abundance yields a mean absolute relative error on the predicted values of $\Omega_{\rm m}$ and $\sigma_8$ that is a factor of $\sim 10 \%$ and $\sim 20\%$ better than that obtained from the summary statistics. Furthermore, when information about the individual luminosity of each cluster is passed to the CNN, the gain in precision exceeds $50\%$.
#### Cosmological constraints on viable $f(R)$ models using weak lensing
 - **Authors:** Leandro Pardo, Leonardo Castañeda
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2601.04048

 - **Pdf link:** https://arxiv.org/pdf/2601.04048

 - **Abstract**
 The accelerated expansion of the Universe remains one of the central open problems in modern cosmology. While the $\Lambda$CDM model successfully describes a wide range of observations, the physical nature of dark energy is still unknown, motivating the study of alternative theories of gravity. Among these, $f(R)$ models provide a well-established extension of General Relativity, capable of reproducing a $\Lambda$CDM-like background evolution without introducing an explicit dark energy component. However, they can induce deviations in the growth of cosmic structures, making them testable through observables sensitive to cosmological perturbations. In this work, we use weak gravitational lensing to constrain several viable $f(R)$ gravity models. We analyze their impact on the matter power spectrum, as well as on the convergence and cosmic shear power spectra. Our analysis is carried out within a Bayesian framework using the \textit{Cobaya} code and its modified gravity extension, \textit{MGCobaya}, which enables consistent theoretical predictions and their comparison with current weak lensing and CMB lensing data. We find that standard cosmological parameters remain consistent with the $\Lambda$CDM scenario for all models considered, as expected from their background degeneracy. Nevertheless, we obtain non-trivial and model-dependent constraints on the characteristic parameters of several $f(R)$ theories.
#### Modeling the Effect of C/O Ratio on Complex Carbon Chemistry in Cold Molecular Clouds
 - **Authors:** Alex N. Byrne, Christopher N. Shingledecker, Edwin A. Bergin, Martin S. Holdren, Gabi Wenzel, Ci Xue, Troy Van Voorhis, Brett A. McGuire
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2601.04103

 - **Pdf link:** https://arxiv.org/pdf/2601.04103

 - **Abstract**
 Elemental abundances, which are often depleted with respect to the solar values, are important input parameters for kinetic models of interstellar chemistry. In particular, the amount of carbon relative to oxygen is known to have a strong effect on modeled abundances of many species. While previous studies have focused on comparison of modeled and observed abundances to constrain the C/O ratio, the effects of this parameter on the underlying chemistry have not been well-studied. We investigated the role of the C/O ratio on dark cloud chemistry using the NAUTILUS code and machine learning techniques for molecular representation. We find that modeled abundances are quite sensitive to the C/O ratio, especially for carbon-rich species such as carbon chains and polycyclic aromatic hydrocarbons (PAHs). CO and simple ice-phase species are found to be major carbon reservoirs under both oxygen-poor and oxygen-rich conditions. The appearance of C3H4 isomers as significant carbon reservoirs, even under oxygen-rich conditions, indicates the efficiency of gas-phase C3 formation followed by adsorption and grain-surface hydrogenation. Our model is not able to reproduce the observed, gas-phase C/H ratio of TMC-1 CP at the time of best fit with any C/O ratio between 0.1 and 3, suggesting that the modeled freeze-out of carbon-bearing molecules may be too rapid. Future investigations are needed to understand the reactivity of major carbon reservoirs and their conversion to complex organic molecules.
#### Satellite-borne γ-ray astrophysics from coherent interactions in oriented crystals
 - **Authors:** Pietro Monti-Guarnieri, Gianfranco Paternò, Alexei Sytov, Elisabetta Cavazzuti, Luigi Costamante, Sara Cutini, Matteo Duranti, Pierluigi Fedeli, Richard J. Gaitskell, Vincenzo Guidi, Viktar Haurylavets, Savvas M. Koushiappas, Francesco Longo, Sofia Mangiacavalli, Andrea Mazzolari, Michela Prest, Marco Romagnoni, Alessia Selmi, Victor Tikhomirov, Valerio Vagelli, Erik Vallazza, Laura Bandiera
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2601.04129

 - **Pdf link:** https://arxiv.org/pdf/2601.04129

 - **Abstract**
 High-density and high-Z crystals are a key element of most space-borne $\gamma$-ray telescopes operating at GeV energies (such as Fermi-LAT). The lattice structure is usually neglected in the development of a crystalline detector, although its effects on the energy deposit development should be taken into account, since the interactions of a high energy ($\sim$~GeV) photon or e$^\pm$ impinging along the axis of an oriented crystal are different than the ones observed in a fully isotropic medium. Specifically, if the angle between a photon (e$^\pm$) trajectory and the crystal axis is smaller than $\sim$ 0.1$^\circ$, a large enhancement of the pair production (bremsstrahlung) cross-section is observed. Consequently, a photon-induced shower inside an oriented crystal develops within a much more compact region than in an amorphous medium. Moreover, for photon energies above a few GeV and incidence angles up to several degrees, the pair-production cross-section exhibits a pronounced dependence on the angle between the crystal axis and the photon polarization vector. \\ In this work we show that these effects could be exploited to develop a novel class of light-weight pointing space-borne $\gamma$-ray telescopes, capable of achieving an improved sensitivity and resolution, thanks to a better shower containment in a smaller volume with respect to non-oriented crystalline detectors. We also show that an oriented tracker-converter system could be used to measure the polarization of a $\gamma$-ray source above few GeV, in a regime that remains unexplorable through any other detection technique. This novel detector concept could open new pathways in the study of the physics of extreme astrophysical environments and potentially improve the detector sensitivity for indirect Dark Matter searches in space.


by olozhika (Xing Yuchen). 


2026-01-08
