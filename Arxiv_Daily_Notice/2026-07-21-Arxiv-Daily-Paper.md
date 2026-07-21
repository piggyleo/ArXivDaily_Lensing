# Showing new listings for Tuesday, 21 July 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 13papers 
#### Effective temperatures estimation of low-mass stars and identification of T Tauri stars in LAMOST DR10 using machine learning
 - **Authors:** C. D. Millan-Valderrama, J. Hernandez, B. Sabogal, J. Muñoz
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.16585

 - **Pdf link:** https://arxiv.org/pdf/2607.16585

 - **Abstract**
 We present effective temperature (Teff) estimates of low-mass stars and T Tauri stars (TTS) candidate detections derived from automated spectroscopic measurements and low-complexity machine-learning models applied to the LAMOST DR10 V2 survey. Equivalent widths of key diagnostic spectral features, including the atomic lines Halpha, LiI 6708 AA and TiO/VO molecular bands, are automatically measured for all stars within 1 kpc observed by LAMOST. Using nine spectral features as inputs, we train a Gradient Boosting Machine tree-based regression model, calibrated with synthetic spectra from the PHOENIX library, to predict Teff over the range 2,500 - 5,100 K. We apply a logistic regression model to the principal components derived from the measured spectral features, enabling efficient identification of TTS candidates. Both models exhibit strong performance in validation tests. Finally, a Monte Carlo framework is employed to propagate input uncertainties and estimate Teff and its associated uncertainties for low-mass stars from 1,733,802 spectra and to identify 2,534 candidate TTS from 3,121 spectra.
#### Predicting the unpredictable: binary--single scattering with machine learning
 - **Authors:** Ahmad Farhani Asl (1), David Fonseca Mota (2), Dennis Fremstad (2), Fatemeh Rahimi (1) ((1) Department of Physics, Institute for Advanced Studies in Basic Sciences (IASBS), Zanjan, Iran, (2) Institute of Theoretical Astrophysics, University of Oslo, Oslo, Norway)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.16763

 - **Pdf link:** https://arxiv.org/pdf/2607.16763

 - **Abstract**
 Binary--single encounters occur frequently in stellar systems, constitute a non-integrable chaotic three-body problem, and are computationally expensive when treated with N-body codes. We aim to construct an accurate and physically interpretable surrogate model for binary--single scattering final states (ionization, flyby, exchange, or hierarchical), evaluate the reliability of its probabilistic predictions, and trace its predictive failures to the underlying chaotic nature of the scattering problem. We trained an XGBoost multiclass classifier on a class-balanced dataset of numerically integrated binary--single scattering experiments, using physically motivated features. The model achieves a test accuracy of 88.32 percent and a top-2 accuracy of 98.77 percent. Feature importance indicates binary hardness as the dominant predictor. Misclassifications concentrate near the chaotic boundary separating exchange and hierarchical outcomes. Basin-entropy analysis reveals that such misclassifications are due to intrinsically ambiguous regions of parameter space. Therefore, a fast machine-learning surrogate can predict binary--single scattering final states with high accuracy, and residual errors arise from chaotic regions rather than model inadequacy.
#### Machine learning prediction of binary formation in three-body gravitational encounters
 - **Authors:** Ahmad Farhani Asl (1) ((1) Institute for Advanced Studies in Basic Sciences (IASBS), Zanjan, Iran)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.16776

 - **Pdf link:** https://arxiv.org/pdf/2607.16776

 - **Abstract**
 Three-body encounters are frequent events in stellar systems, intrinsically chaotic, and computationally costly to model with direct N-body integration. Predicting whether such encounters lead to binary formation is therefore challenging, particularly in large-scale simulations. We aim to develop an accurate and physically interpretable machine-learning model that predicts binary formation from the initial conditions of three-body encounters, to assess its reliability, and to identify the physical parameters that most strongly determine the outcome. We trained an XGBoost binary classifier on a balanced dataset of three-body scattering experiments computed with the REBOUND code and the IAS15 integrator. The input to the model consists of 30 physically motivated features describing the masses, energies, and kinematics of the initial configuration. The classifier achieves excellent performance on a balanced test set, with accuracy, precision, recall, and F1-score all above 0.94, and with ROC-AUC and PR-AUC values of 0.99. Feature-importance analysis shows that the outcome is governed primarily by the mass hierarchy and hardness ratio of the encounter, followed by velocity fraction and mass entropy. The predicted probabilities are well calibrated, with an expected calibration error (ECE) of 0.02. Inference is approximately 400 times faster than direct N-body integration. The model also generalizes well across encounter radii, although its performance decreases in the weak-interaction regime where binary formation becomes intrinsically rare. These results show that machine learning can provide fast, accurate, and physically interpretable predictions of binary formation in three-body encounters. Such models offer a practical complement to direct N-body simulations and may enable efficient probability estimates in large-scale simulations of stellar systems.
#### Temporal Correlations Between Fuzzy Dark Matter and Baryonic Matter in Virialized Core-Halo Structures
 - **Authors:** Ivan Alvarez-Rios, Francisco S. Guzman
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); General Relativity and Quantum Cosmology (gr-qc)
 - **Arxiv link:** https://arxiv.org/abs/2607.16917

 - **Pdf link:** https://arxiv.org/pdf/2607.16917

 - **Abstract**
 Fuzzy Dark Matter (FDM) predicts the existence of virialized halos with interference-driven granular structure generated by the wave nature of ultralight bosons. Since these fluctuations produce time-dependent gravitational fields, they can be proposed as a potential source of observable dynamical effects on baryonic matter. In this work we test whether such fluctuations generate measurable temporal correlations between FDM and a coupled gas component. We evolve coupled FDM-gas configurations with the Schrödinger-Poisson-Euler system in three dimensions. The FDM component is initialized through multimerger configurations that relax toward core-halo structures, while the baryonic component is modeled as an ideal gas. After virialization, we analyze the temporal fluctuations of both components through correlation functions and spectral diagnostics. The FDM density field shows fluctuations with significant high-frequency content, whereas the gas develops smoother and longer-lived coherent structures. Although the gas dynamically responds to the gravitational potential generated by the FDM halo, we find no strong temporal correlation between the interference-driven fluctuations of FDM and the gas dynamics. This behavior persists across the explored range of gas temperatures. Our results indicate that baryonic matter reacts to the global gravitational potential of the virialized halo rather than to the detailed phase-dependent granular structure of FDM. This weak temporal coupling may limit the possibility of directly detecting FDM granularity through local baryonic temporal fluctuations.
#### Unveiling dark energy properties with high-sensitivity cross-correlations of neutral hydrogen intensity mapping and galaxy surveys
 - **Authors:** Alessandro Marins, Chang Feng, Filipe B. Abdalla
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.17141

 - **Pdf link:** https://arxiv.org/pdf/2607.17141

 - **Abstract**
 The redshifted 21 cm line from the hyperfine structure of neutral hydrogen atoms is a promising tracer for the three-dimensional evolution of our universe. Its broad spatial and temporal coverage is crucial for understanding the complex nature of dark matter and dark energy. However, it is very challenging to directly detect the 21 cm signal due to the existence of radio foreground contaminants that are orders of magnitude brighter. Therefore, mitigating the foreground contamination becomes an indispensable task for detecting the 21 cm signal, which is also expected to be correlated with the dark-matter-dominated large-scale structure. The cross-correlations between the neutral hydrogen intensity mapping and galaxy surveys in the future can not only confirm a detection of the 21 cm signal but can also be a complementary probe for 21 cm cosmology. To meet the precision requirements for cosmological studies, it is important to investigate the complex features of the estimated cross-correlations using numerical simulations. In this work, we simulate the low-redshift HI observations and narrow-band optical surveys in the future and obtain the foreground- and bias-mitigated HI-galaxy cross-power spectra, with which we perform a Bayesian analysis to infer cosmological parameters of dynamical dark energy model. The method developed in this work will be important for cosmological studies with the 21 cm intensity mapping.
#### The initial conditions and initial mass functions of Alpha Persei, Pleiades and Praesepe
 - **Authors:** L. Hobart, H. Baumgardt, S. Sweet
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.17300

 - **Pdf link:** https://arxiv.org/pdf/2607.17300

 - **Abstract**
 We have determined the initial mass function (IMF) and structural properties of the open clusters Alpha Persei, Pleiades and Praesepe using Gaia DR3 astrometry and photometry. Cluster members were identified using primarily Gaia astrometry, supplemented with near-infrared UKIDSS and optical HIPPARCOS survey data with stellar masses down to $0.10-0.17$ MSun. We measure and correct for unresolved binaries in each cluster using photometry and Monte Carlo simulations in a Bayesian framework, finding present-day fractions between ($20.0\pm0.8$)% and ($23.8\pm1.2$)%. Through a novel approach that combines N-body simulations with machine learning emulators and MCMC algorithms, we have also determined the most probable initial number of stars, binary fraction, half-mass radius and mass function under the assumption that early gas removal does not significantly influence the subsequent cluster evolution. We find a best-fitting initial mass function described by a three-stage broken power-law distribution with break masses in the ranges $0.24-0.50$ MSun and $0.91-1.20$ MSun and average slopes of $\alpha_{\rm med}=1.72\pm0.09$ and $\alpha_{\rm high}=2.98\pm0.22$. While the low-mass slope remains sensitive to the adopted mass-luminosity relation, this IMF reproduces the present-day clusters well once their dynamical evolution is taken into account. We find evidence of scatter in the high mass IMF between the individual clusters, as described by the measured dispersions in mass function slopes of ${\sigma}_{\rm high}=0.29\pm0.16$, whereas the intermediate mass slope shows no significant variation with ${\sigma}_{\rm med}=0.00\pm0.14$. Our findings provide additional evidence for a (compared to a Salpeter MF) top-light IMF and a cluster-to-cluster variation of the IMF. They therefore provide constraints on the universality of the IMF and its dependence on environmental conditions.
#### SpecFANN: Spectral Fitting via Artificial Neural Networks I. A deep learning based fastwind emulator and fitting suite
 - **Authors:** M. Abdul-Masih, C. Hawcroft, T. Lechien, S. Simon-Diaz, H. Sana, K. Deshmukh, J. Vrancken, J. I. Villaseñor, J. Müller-Horn, A. J. Kalita, B. Ludwig, J. Bodensteiner, D. M. Bowman, A. Escorza, G. Holgado, J. Puls, A. de Vicente
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.17348

 - **Pdf link:** https://arxiv.org/pdf/2607.17348

 - **Abstract**
 The importance of massive stars cannot be overstated: they are powerful probes of the early universe, play a vital role in the chemical and mechanical evolution of their host environments and their end products allow us to study the most extreme physics in the universe. Obtaining accurate stellar and surface parameters for large samples of massive stars is vital to our understanding of how they evolve, and how their births, lives and deaths affect their surroundings. With the large volume of data expected from upcoming spectroscopic surveys, computational limitations will likely be the most important bottleneck impeding our progress. To address this and dramatically decrease computing times, we aim to develop a robust emulator for the FASTWIND radiative transfer and spectral synthesis code. Additionally, we aim to explore alternative fitting methods that have not been feasible until now due to computational costs. We calculate a set of FASTWIND synthetic spectra of OB-type stars, and we train a collection of neural networks to emulate these models. We also develop the open-source python package SpecFANN, which provides users with a suite of fitting methods that can be used with these or other user-generated neural networks. The majority of the trained neural networks reach average accuracies of better than ~0.01-0.1% for photospheric lines and better than ~0.1-1% for wind lines. SpecFANN is able to obtain robust and accurate stellar parameters that are consistent with the literature for a sample of 52 early-type stars. Using SpecFANN we find that we can achieve the same fit in ~1/360,000 of the time when compared to alternative techniques that rely on on-the-fly FASTWIND computations. We have demonstrated that neural networks offer a viable path forward to address the computational limitations of our current atmosphere analysis and stellar parameter determination methods for hot stars.
#### Repulsive dark matter from Hosotani mechanism
 - **Authors:** Philippe Brax, Patrick Valageas
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Physics - Phenomenology (hep-ph); High Energy Physics - Theory (hep-th)
 - **Arxiv link:** https://arxiv.org/abs/2607.17727

 - **Pdf link:** https://arxiv.org/pdf/2607.17727

 - **Abstract**
 We build an ultralight dark matter model with repulsive self-interactions, starting from a 5D action that only includes a $U(1)$ gauge field and several massive and charged free fermions. The dark matter scalar field corresponds to the fifth component of the gauge field, after compactification to 4D. Although the single-fermion case only leads to attractive self-interactions, two fermions can already give rise to repulsive self-interactions, thanks to a Scherk-Schwarz twist around the fifth dimension. We check the observational and theoretical self-consistency of this scenario, from the inflation stage to the current time. We find that large ranges of model parameters are allowed. For scalar masses below $10^{-12}$ eV the self-interactions are negligible and the model behaves as fuzzy dark matter. For higher masses the repulsive self-interactions govern the formation of solitons of astrophysical size. Larger sizes require a large initial misalignment or small masses in the fuzzy dark matter regime.
#### Structural and dynamical properties of Tidal dwarf galaxies in the tails and bridge of the Guitar galaxy Arp 105
 - **Authors:** Jyoti Prakash, Kanak Saha
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.17776

 - **Pdf link:** https://arxiv.org/pdf/2607.17776

 - **Abstract**
 We present a multi-wavelength (far-ultraviolet to infrared) analysis of two tidal dwarf galaxy (TDG) candidates and a tidal bridge in the interacting system Arp 105 at $z = 0.029$ in the Abell 1185 cluster. Far-ultraviolet observations obtained with the Ultraviolet Imaging Telescope onboard AstroSat reveal strong FUV emission from the tidal galaxies Arp~105N and Arp~105S, indicating recent star formation. In Arp~105N, strong nebular emission lines and large equivalent widths $EW(H\alpha)=77.6\pm1.3$ $\overset{\circ}{\mathrm {A}}$ and $EW(H\beta)=15.8\pm1.7$ $\overset{\circ}{\mathrm {A}}$ imply a dominant starburst age of $\sim$6 - 10~Myr under an instantaneous-burst assumption, while the FUV emission suggests star formation sustained over the past $\sim100 - 200$~Myr. The relatively high metallicity, $\sim2/3,Z_\odot$ (based on the strong-line method), is consistent with expectations for a tidal dwarf galaxy formed from material inherited from the host galaxy. Together, these results suggest that Arp~105N hosts a composite stellar population, consisting of older stars stripped from the host galaxy and younger stars formed in situ. Spectral energy distribution modeling yields stellar masses of $5.75\times10^{9}$, $0.8\times10^{9}$, and $6.8\times10^{9},\rm M_\odot$ for Arp~105N, Arp~105S, and the tidal bridge, respectively. Based on the dynamical mass estimate from VLA HI measurements for Arp~105N and based on CFHT H$\alpha$ kinematics for A105S, they have a dynamical-to-baryonic mass ratio of $\sim1.95$ and $\sim1.30$, respectively, indicating a deficiency of dark matter. Further observations, particularly integral field spectroscopy and high-resolution 21~cm observations, may provide better constraints into the kinematics and improve understanding of TDG formation.
#### Intracluster light and dark matter halo shapes reflect common assembly, not mutual coupling: shape correspondence in CDM but not SIDM
 - **Authors:** G. Martin (1), N. A. Hatch (1), W. Cui (2, 3, 4), A. Fernandez (1), Y. M. Bahé (1, 5), M. S. Fischer (6), M. Montes (7), F. R. Pearce (1), C. G. Sabiu (8), G. Yepes (2, 3), J. Yoo (9) ((1) School of Physics &amp; Astronomy, University of Nottingham, (2) Departamento de Física Teórica, Universidad Autónoma de Madrid, (3) Centro de Investigación Avanzada en Física Fundamental (CIAFF), Universidad Autónoma de Madrid, (4) Institute for Astronomy, Royal Observatory, Edinburgh, (5) Laboratoire d'Astrophysique, EPFL, (6) Donostia International Physics Center (DIPC), (7) Institute of Space Sciences (ICE, CSIC), (8) Natural Science Research Institute (NSRI), University of Seoul, (9) Korea Astronomy and Space Science Institute (KASI))
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.17792

 - **Pdf link:** https://arxiv.org/pdf/2607.17792

 - **Abstract**
 The intracluster light (ICL) has been proposed as a luminous tracer of the dark matter (DM) halo shape in galaxy clusters, with recent observational studies and $\Lambda$CDM simulations suggesting close alignment between the two components. We test whether this correspondence holds in a self-interacting dark matter (SIDM) cosmology using matched CDM and SIDM ($\sigma_\mathrm{DM}/m = 0.1$ and $0.5\;\mathrm{cm^{2}\,g^{-1}}$) hydrodynamical cluster simulations from TheThreeHundred project. We measure 3D axis ratios and major-axis orientations as a function of radius for both the DM halo and the stellar (BCG+ICL) distribution, and quantify the spatial correspondence using the Weighted Overlap Coefficient. In the SIDM simulations, DM haloes become significantly rounder in their inner regions with increasing DM cross-section, while the stellar distribution retains the same elongated morphology in both CDM and SIDM. This decoupling is robust across two baryonic physics models and two resolution levels, and is detected at $>5\sigma$ for $\sigma_\mathrm{DM}/m = 0.5\;\mathrm{cm^{2}\,g^{-1}}$. It arises because the stellar shape is governed by the accretion geometry of tidally stripped satellites along the large-scale structure, which is identical in CDM and SIDM, whereas, in SIDM, halo shapes respond additionally to local self-interactions. The ICL-DM shape correspondence demonstrated in CDM therefore breaks down in an SIDM universe.
#### Comparing explicit likelihood and likelihood-free simulation-based inference for weak lensing cosmic shear
 - **Authors:** Simone Vinciguerra, Nicolas Martinet, Marco Gatti
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.17942

 - **Pdf link:** https://arxiv.org/pdf/2607.17942

 - **Abstract**
 Simulation-based inference (SBI) has become a major tool for extracting cosmological information from weak-lensing (WL) surveys, particularly from non-Gaussian observables. We compare its two main paradigms: explicit likelihood inference (ELI), based on a Gaussian likelihood built from an emulator and covariance matrix, and likelihood-free inference (LFI), which learns the likelihood directly from simulations using neural density estimators. Using Gaussian random field mocks representative of the non-tomographic final Euclid data release, we analyse shear two-point correlation functions (shear-2PCFs), compressed with linear or non-linear methods, together with a fundamentally different map-level convolutional neural network (CNN) statistic, focusing on $\Omega_{\rm m}$ and $S_8$. We deploy posterior calibration diagnostics developed for LFI, including the test of accuracy with random points (TARP), showing that ELI becomes strongly miscalibrated under emulation inaccuracies or likelihood non-Gaussianity, whereas LFI remains well calibrated. These effects drive substantial disagreement between ELI and LFI, which largely vanishes once addressed. We further show that the compression scheme can significantly degrade ELI while leaving LFI largely unaffected. Although shear-2PCFs should capture all the information in Gaussian fields, finite compression and non-Gaussian likelihoods cause ELI constraints to differ by up to a factor of two from those inferred with the CNN, while the discrepancy drops to $\approx 30\%$ for LFI, underscoring the robustness of the deep-learning probe. Overall, our results indicate that in our simple setup, which neglects systematic biases, LFI provides a more robust and better-calibrated framework, while highlighting accurate non-Gaussian likelihood modelling and posterior calibration diagnostics as essential for future ELI analyses.
#### Core-Halo Mass Relation in Cosmological Vector Dark Matter
 - **Authors:** Jiajun Chen, Yonghao Yao, David J. E. Marsh
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.18025

 - **Pdf link:** https://arxiv.org/pdf/2607.18025

 - **Abstract**
 We study the cosmological core-halo relation in vector dark matter using three-component Schrödinger-Poisson simulations. Starting from cosmological vector-field initial conditions, which due to the evolution of the vector field during inflation are enhanced on small scales, we find that nonlinear evolution begins almost immediately following matter-radiation equality and produces compact self-gravitating Proca-star condensates at the centers of halos. After confirming the central condensates through their radial density profiles, we find the empirical relation \(\widetilde M_\star\propto \widetilde M_{\rm h}^{0.6403}\) between the Proca star mass and halo mass, although interestingly we find that we are only able to confirm Proca stars in $\mathcal{O}(10\%)$ of halos. This serves as important input for future studies of the abundance and merger rates of Proca stars in models of vector dark matter. We also examine the vector-field structure of the objects through global longitudinal and transverse polarization fractions and local spin density inside halos, which increases over cosmic time.
#### Cosmological consequences of a dynamical dark matter in the light of DESI DR2 measurements
 - **Authors:** Abhijith Ajith, Utkarsh Kumar
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); General Relativity and Quantum Cosmology (gr-qc)
 - **Arxiv link:** https://arxiv.org/abs/2607.18234

 - **Pdf link:** https://arxiv.org/pdf/2607.18234

 - **Abstract**
 Recent DESI results exhibit preference for a Null Energy Condition violating dynamical dark energy, with early phantom behaviour. We explore an alternative interpretation in which this preference arises from unconventional dark matter dynamics rather than from dynamical dark energy. We propose a dynamical dark matter (DDM) model, with a non-zero equation of state (EoS) that smoothly interpolates between early time and late time asymptotes across a transition scale factor $a_t$, and study its consequences against cosmological datasets including CMB, DESI DR2 BAO, SNeIa (PantheonPlus, Union3, and DESY5) and growth rate data. We find the early time EoS to be consistent with zero, while the present day value is negative at a significance ranging from $0.42\sigma$ to $3.02\sigma$ depending on the dataset combination. The strongest preference occurs from the combination of CMB, DESI, and DESY5 giving the present day EoS to be $-0.060^{+0.013}_{-0.028}$ and $a_t = 0.41^{+0.088}_{-0.13}$ at 68\% CL. This preference for a non-zero, late time DM EoS persists when growth rate data are included and across all three SNeIa compilations considered, while the matter density $\Omega_m$ mildly shifts to higher values relative to $\Lambda$CDM. The model also predicts a lower $\sigma_8$ and $S_8$ than $\Lambda$CDM, in better agreement with weak-lensing data, while $H_0$ remains unchanged and in tension with local distance-ladder measurements. The DDM model is preferred over $\Lambda$CDM ($\Delta \chi^2_{\rm MAP} = -14.093$, $\Delta {\rm DIC} = -7.838$ for Planck+DESI+DESY5) but disfavored relative to the CPL parameterization of DE ($\Delta \chi^2_{\rm MAP} = 6.755$, $\Delta {\rm DIC} = 7.966$). This preference is consistent among other combination of datasets as well.


by olozhika (Xing Yuchen). 


2026-07-21
