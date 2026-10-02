# Showing new listings for Friday, 2 October 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 5papers 
#### Emulation of the Halo Mass Function with Neural Networks
 - **Authors:** Olive Ross, Nicholas Battaglia
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.00725

 - **Pdf link:** https://arxiv.org/pdf/2610.00725

 - **Abstract**
 The abundance of galaxy clusters as a function of mass --- the halo mass function (HMF) --- depends strongly on cosmological parameters. Large-scale simulations are computationally expensive, motivating emulators that interpolate simulation outputs. We present a neural network emulator that maps cosmological and astrophysical parameters, halo mass, and redshift directly to a cumulative count of halos above the input mass, avoiding the information loss inherent to binning and to the functional or PCA-based data reduction used in prior emulators. Each emulator prediction is accompanied by a self-estimated error, expressed in units of Poisson shot noise, that the network learns to predict alongside the halo count itself --- giving every output a built-in confidence metric. We validate the emulator with leave-one-out tests on three simulation suites --- the N-body MassiveNus suite and the hydrodynamical CAMELS IllustrisTNG and SIMBA suites --- spanning a range of box sizes, redshifts, sub-grid physics, and softwares. Of all the held-out predictions ($1.2\times 10^6$ in total), 88\% have model bias at or below shot noise and 99.9\% are within $3\times$ shot noise. The only significant high-error tail is in MassiveNus, where the predicted model bias flags 76\% of predictions exceeding $3\times$ shot noise; the remaining number of high error predictions is comparable to the number expected from shot noise alone. This emulator is publicly available and can be trained on other simulation suites making it a flexible HMF tool that can be used for cosmological and astrophysical inference.
#### LeoNet: A Machine Learning Method for Binary Pulsar Classification
 - **Authors:** Zhaocheng Gong, Jack White, Zeyu Yang, Jayanta Roy, Karel Adamek, Wesley Armour
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2610.00908

 - **Pdf link:** https://arxiv.org/pdf/2610.00908

 - **Abstract**
 Binary pulsars provide valuable laboratories for testing theories of gravity, but orbital Doppler shifts complicate their detection. Fourier-domain acceleration and jerk searches address this challenge via matched filtering, but at substantial computational cost. We present LeoNet, a convolutional neural network that uses ten learnable filters to extract features of signals affected by Doppler shifts. The resulting ten-channel feature map provides a compact, lower-dimensional alternative to an explicitly sampled acceleration-jerk response grid and is analysed by a convolutional classifier to identify candidate signals. For simulated observations lasting 500 s, LeoNet achieves a mean relative reduction in false negative rate of 55.5% across five sampling intervals compared with the evaluated PRESTO acceleration-search configuration. TensorRT-optimised LeoNet processes each 500 s observation in 3.44-4.37 ms in FP32 on an NVIDIA H100 PCIe GPU across eight sampling intervals, including preprocessing, inference, and postprocessing. At a sampling interval of 128 microseconds, its mean processing time is 3.54 ms, compared with 1.767 s for PRESTO FDAS on an AMD EPYC 9825 CPU with search-frequency limits of 96-1000 Hz, corresponding to an approximately 499-fold speedup in the measured processing time. These results suggest that LeoNet has the potential to improve detection performance, while its millisecond-scale processing time supports its use as a candidate-identification stage in real-time binary pulsar search pipelines.
#### Weak-Lensing Shear Response for Photometric Redshift-Based Tomographic Binning
 - **Authors:** Xiangchong Li, Tianqing Zhang, Rachel Mandelbaum, the LSST Dark Energy Science Collaboration
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.00999

 - **Pdf link:** https://arxiv.org/pdf/2610.00999

 - **Abstract**
 Dividing source galaxies into tomographic redshift bins is a cornerstone of modern weak gravitational lensing analyses, enabling measurements of the growth of cosmic structure and the nature of dark energy. In practice, these tomographic bins are defined using photometric redshift (photo-$z$) estimates. However, correlations between photo-$z$ estimates and weak lensing shear can introduce redshift-dependent selection biases in the measured shear signal; if left uncorrected, these biases distort the inferred amplitude and redshift evolution of the lensing signal, and in turn bias the measurement of the growth of cosmic structure across cosmic time. In this paper, we extend the analytical self-calibration for shear measurement (AnaCal) framework to account for photo-$z$-based selection biases in tomographic weak lensing analyses by propagating shear responses through the selection process. This approach eliminates the need for external image simulations to calibrate this correction. As a first sanity check on real data, we validate the photo-$z$ estimates derived from AnaCal fluxes on the Rubin Observatory Data Preview 1 dataset, and find that they reach photo-$z$ quality comparable to, and at high redshift slightly better than, the standard LSST estimates. We then validate the shear calibration on LSST-like image simulations with blending at the expected LSST Y10 depth, with two representative photo-$z$ algorithms -- a template-fitting method and a machine-learning method -- and show that the multiplicative shear bias induced by photo-$z$ selection remains within the LSST ten-year requirement $|m| < 3\times 10^{-3}$ across all five tomographic bins for both algorithms. These results establish AnaCal as a self-consistent pipeline for tomographic weak lensing science in upcoming LSST analyses.
#### Galaxy Protoclusters as Drivers of Cosmic Reionization: II. Te-Based Metallicities of Lyman-α Emitters
 - **Authors:** C. Moya-Sierralta, C. L. Martin, L. F. Barrientos, L. Infante, J. González-López, W. Hu, A. L. Faisst, Y. Harikane, A. M. Koekemoer, S. Malhotra, M. Ouchi, Z. Peng, J. Rhoads, J. Wang, J. R. Weaver, I. Wold, J. Yang, Z. Zheng
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.01811

 - **Pdf link:** https://arxiv.org/pdf/2610.01811

 - **Abstract**
 Context. Protoclusters at reionization are thought to host a significant fraction of the cosmic star formation rate density, making them crucial for the timing and topology of reionization. The gas-phase metallicity, a key tracer of galaxy evolutionary stage, can now be measured directly in the early Universe with JWST. Aims. We measure the gas-phase metallicity of Lyman-$\alpha$ emitters (LAEs) in the LAGER-z7OD1 protocluster at $z\approx6.93$ via the direct ($T_e$-based) method using the [O III]$\lambda$4363 auroral line, and combine it with stellar masses to constrain the mass-metallicity relation (MZR) in dense environments. Methods. We use JWST/NIRSpec MSA G395H spectroscopy, derive metallicities with self-consistent analytic prescriptions, and propagate the dust-extinction uncertainty into an asymmetric error budget via Monte Carlo simulations based on the observed Balmer decrements. Stellar masses come from BEAGLE SED fitting of JWST/NIRCam and UltraVISTA photometry. Results. We obtain five secure [O III]$\lambda$4363 detections and one upper limit, with 12+log(O/H) $\approx$ 7.2-8.0. The weighted spectral stack yields 12+log(O/H) = $7.76^{+0.06}_{-0.05}$, ~0.26 dex higher than stacks of LAEs at similar redshifts from JWST surveys. However, the MZR fit gives a slope $\gamma$ = 0.232 +/- 0.214 and normalization $Z_0$ = 7.888 +/- 0.199, placing our sources below the established MZR of normal galaxies and recent protocluster baselines at $z\sim5-7$. Conclusions. The higher metallicity relative to general LAEs suggests accelerated assembly driven by the overdensity, while the offset below the MZR points to a complex interplay between mass build-up and gas accretion. Since we target actively star-forming LAEs, we are likely capturing a phase of pristine gas inflow from the intergalactic medium that fuels star formation but dilutes the interstellar media of these protocluster members.
#### Cosmological inference from a joint DESI DR1 full-shape power spectrum and bispectrum analysis
 - **Authors:** Caroline Guandalin, Prakhar Bansal, Pedro Carrilho, Alejandro Aviles, Mike (Shengbo)Wang, Marcos Pellejero-Ibañez, Aaditya Sarma, Jaide Swanson, Marco Bonici, Florian Beutler, Arnaud de Mattia, Hee-Jong Seo
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.01836

 - **Pdf link:** https://arxiv.org/pdf/2610.01836

 - **Abstract**
 The galaxy bispectrum directly probes the non-linear gravitational evolution of large-scale structure (LSS) and can break parameter degeneracies that remain in power-spectrum analyses. We present a joint full-shape cosmological analysis of three luminous red galaxy (LRG) redshift bins and the quasar (QSO) sample from the first Data Release (DR1) of the Dark Energy Spectroscopic Instrument (DESI). We model the redshift-space power spectrum at one loop and the tree-level bispectrum within the Effective Field Theory of LSS. The bispectrum is decomposed in the Tripolar Spherical Harmonics basis, for which the convolution with the survey window function can be formulated as a direct linear transformation of the theoretical multipoles. Our power-spectrum constraints are in good agreement with the official DESI DR1 full-modelling results. We investigate the impact of including the bispectrum in the inference, finding that the monopole substantially improves the constraints on the cold dark matter density and amplitude of matter fluctuations by 9-18% and 8-20%, respectively, in the individual-tracer analyses. The corresponding reductions are 15% and 10% for the combined LRG sample, and 6% and 4% when all tracers are combined. In a restricted test using the first LRG bin, the bispectrum quadrupole changes the marginalised uncertainties by only a few percent. Extending the analysis to $w_0w_a$CDM substantially broadens the cosmological posteriors, while the bispectrum produces only a mild change in the allowed dark-energy parameter region, which remains sensitive to the adopted prior ranges. Our results demonstrate the potential of higher-order clustering statistics to improve cosmological constraints, while providing a framework for incorporating the bispectrum into full-shape analyses of current and future spectroscopic galaxy surveys.


by olozhika (Xing Yuchen). 


2026-10-02
