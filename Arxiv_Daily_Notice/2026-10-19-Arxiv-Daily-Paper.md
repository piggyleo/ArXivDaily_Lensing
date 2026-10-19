# Showing new listings for Monday, 19 October 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 4papers 
#### Primordial Power Spectrum from the Lensed CMB Temperature Spectrum using Iterative Delensing and Fourier Denoising
 - **Authors:** Rajorshi Sushovan Chandra, Debarshi Mukherjee, Tarun Souradeep
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.22648

 - **Pdf link:** https://arxiv.org/pdf/2610.22648

 - **Abstract**
 The CMB power spectra are a strong probe of the primordial power spectrum (PPS) of the initial inflationary scalar perturbations. There are many proposed models, from the simpler power law form to various well motivated physical models that predict features in the PPS beyond the power law. Given the large parameter space of possible models, it is necessary to have model independent searches for such features. Weak gravitational lensing alters the CMB temperature power spectrum and can bias free form reconstructions of the primordial power spectrum (PPS) if not accounted for precisely, such as when using estimators like the Richardson-Lucy (RL) deconvolution algorithm. We build on our design of the Non linear Iterative Richardson Lucy (NIRL) estimator that updates the lensing contribution using the freeform PPS recovered at the previous iteration, making it truly model independent in the PPS domain while accounting for lensing. Inspired by signal processing and Fourier filtering techniques from radio interferometry, we also design a Fourier space iterative low pass filter (FLIP) to suppress noise overfitting in NIRL reconstructions. We demonstrate the performance of NIRL-FLIP on a range of simulated PPS models with bootstrap estimates of reconstruction uncertainty obtained from simulated realizations, and show that both our estimator and regularization are robust, accurate and precise, and are able to both reduce lensing induced reconstruction bias and suppress noise overfitting by a significant factor in Fourier space. We provide a detailed description of these results and recommend its utility for future model independent searches for hints of novel physics in the form of deviations from a power law PPS. This can further assist in precise and accurate testing of inflation models, in conjunction with joint cosmological parameter estimation.
#### A New AI/ML Based Image Reconstruction Technique for Hard X-ray Coded Aperture Imagers
 - **Authors:** Shayla Sharmin, Branden Allen
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2610.22709

 - **Pdf link:** https://arxiv.org/pdf/2610.22709

 - **Abstract**
 Here we demonstrate a new AI/ML based image reconstruction method for coded-aperture instruments that provides a pathway for embedded real-time use on-board spaceflight missions. Using the Swift Burst Alert Telescope (BAT) for our initial simulated demonstration, we used our new technique to replace the standard Fast Fourier Transform (FFT) based image reconstruction pipeline. In our alternative approach, we have created a neural network that maps detector counts directly to source positions using simulated responses from selected Swift Burst Alert Telescope (BAT) observations. The network combines convolutional feature extraction with attention and is trained at around 900 source counts. Under zero background noise, it achieves over 93\% exact-pixel localization accuracy with 400 detected source photons. The model maintains at least 90\% exact-pixel localization accuracy with up to 8{,}500 added background counts for sources with 900 detected photons. Within the evaluated region of BAT's field of view, these results show that source position can be recovered from sparse coded-aperture measurements in a wide-field instrument. A key feature of this technique is that explicit inclusion of the mask pattern is not required. This allows us to train the algorithm to "see" using data accumulated from an imaging system. These new non-traditional imaging techniques show substantial promise in enabling efficient imaging using non-planar geometries, which will enable new classes of hard X/$\gamma$-ray imaging systems and simultaneously improve imaging capability for currently operating instruments.
#### Gaia in Technicolor. I. A Simple Variability-Encoded Color-Magnitude Diagram
 - **Authors:** Brad N. Barlow, Bennett C. Kirby
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2610.22804

 - **Pdf link:** https://arxiv.org/pdf/2610.22804

 - **Abstract**
 The Hertzsprung-Russell diagram is one of the most important tools in stellar astrophysics. In its modern, empirical form as the Gaia color-magnitude diagram (CMD), each star is represented with a point determined from its time-averaged brightness and color. However, many stars are intrinsically variable, and the fixed-point representation ignores the variety of ways in which a star can vary. As a system pulsates, eclipses, is irradiated, erupts, or otherwise varies, it moves through the CMD along a trajectory whose size, slope, and shape are determined by the physics driving the brightness and color variability. Here we exploit the near-simultaneous, three-band, multi-epoch photometry (MEP) released for ~11.7 million sources in Gaia DR3 to construct a variability-encoded CMD (VECMD). In this updated take on the traditional CMD, each star is represented not by a point but by a linear segment approximating the path it traces in absolute magnitude and color as it varies. Because these trajectories are built from the raw epoch data, they are agnostic to period and do not require phase-folding. We show that radial-mode pulsators trace looped, Lissajous-like trajectories that can encode the phase lag between radius and temperature. The Hertzsprung bump is even visible in the CMD loops of some Cepheids. Variable binary systems can trace tight color-correlated lines and/or hooked paths. Accreting and dust-obscured systems trace long, high-amplitude tracks aligned with the outburst or reddening vector. Distinct regions of the VECMD are dominated by distinct trajectory morphologies. We argue that these trajectories are period-independent fingerprints well suited to machine learning classification, which we will pursue on the much larger epoch-photometry sample expected in Gaia DR4. Finally, we present a free app called IVECMD for finding, classifying, and analyzing variable stars in the VECMD.
#### A Neural Network - Based Tool for Rapid Orbital Solution of Contact Binary Systems
 - **Authors:** Li-Heng Wang, Kai Li, Ya-Ni Guo
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2610.23410

 - **Pdf link:** https://arxiv.org/pdf/2610.23410

 - **Abstract**
 With the rapid growth of large-scale time-domain surveys, vast amounts of photometric and spectroscopic data are continuously being released. A substantial number of contact binaries have been identified, accompanied by both light curves and radial velocity observations. Traditional modeling of these datasets relies on computationally intensive physical models, which limits their applicability to large-scale analyses. To this end, this paper proposes the use of a fully connected neural network and a SIREN (Sitzmann et al. 2020) model to rapidly generate radial velocity curves. After training, the models can rapidly generate radial velocity curves with high accuracy, significantly reducing computational costs and enabling efficient large-scale studies. This method was further integrated with the light curve computation framework developed by Li et al. (2025), allowing simultaneous fitting of radial velocities and light curves. To assess the reliability of the proposed model, synthetic observational datasets were constructed and used for parameter estimation. The deviations between the derived parameters and the ground-truth values were analyzed quantitatively, enabling a comprehensive evaluation of the model's accuracy.


by olozhika (Xing Yuchen). 


2026-10-19
