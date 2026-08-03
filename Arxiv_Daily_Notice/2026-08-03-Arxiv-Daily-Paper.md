# Showing new listings for Monday, 3 August 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 7papers 
#### Single Frequency CMB Foreground Removal with Inter-scale Machine Learning
 - **Authors:** Helen Shao, Fiona McCarthy, Blake D. Sherwin, Miles Cranmer, Carlos Hervias-Caimapo
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.28712

 - **Pdf link:** https://arxiv.org/pdf/2607.28712

 - **Abstract**
 Accurate measurements of Cosmic Microwave Background (CMB) B-mode polarization, a key probe of inflationary physics, are hindered by complex Galactic dust foregrounds. Traditional foreground removal with Internal Linear Combination (ILC) fully preserves the primordial signal but requires multi-frequency data and is limited to two-point statistics. We present a novel way to estimate and remove foregrounds at single frequency using signal-preserving machine learning that leverages inter-scale correlations. Using the DustFilaments simulations, we train CNNs to reconstruct large-scale foregrounds ($\ell < 200$) from small-scales ($\ell > 200$). We quantify the effectiveness of foreground removal with the residual foreground power, $f_{\rm{resid}}$, which gives the fraction of foreground power remaining after removal. Predictions using only small-scale $B$-modes achieve $f_{\rm{resid}}\simeq 0.704$, while adding temperature and $E$-modes decreases it to $f_{\rm{resid}} \simeq 0.376$. These results are still higher than the spatial ILC, which leverages multi-frequency data at Simons-Observatory-like frequencies. However, a hybrid network that uses both multi-frequency and inter-scale correlations attains $f_{\rm{resid}}=4.71\times10^{-4}$ when using $B$-mode inputs alone, and $3.62\times10^{-4}$ when using temperature and $E/B$-mode inputs. This network achieves a residual power of $\sim 7\times$ lower than ILC, while inheriting ILC's signal-preserving property. This is $\sim 2$--$3\times$ lower than a network that only uses multi-frequency inputs, demonstrating that correlations across scale are not redundant with correlations across frequency and that our techniques are complementary to multi-frequency foreground removal. However, this is achieved only for DustFilments and network generalization across simulations remains a key challenge for robust ML-based foreground removal. (abridged)
#### Deep Learning-Based Classification and Analysis of Pulsar Candidates in Fermi-LAT Unassociated Sources
 - **Authors:** C. Pozo González, R. López-Coto, J. Méndez-Gallego, E. de Oña Wilhelm
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2607.28723

 - **Pdf link:** https://arxiv.org/pdf/2607.28723

 - **Abstract**
 The Large Area Telescope (LAT) has revolutionized our understanding of the high-energy sky, yet approximately one-third of the sources in the Fourth Fermi-LAT Source Catalog (4FGL) remain unassociated. Conventional machine learning, such as Decision Trees, often treat spectral features as independent tabular entries, neglecting the sequential topological information inherent in the Spectral Energy Distribution (SED). We aim to classify unassociated Fermi-LAT sources by exploiting the intrinsic shape of their spectra and variability features, avoiding the use of galactic coordinates as training features. Our primary objective is to generate a high-confidence list of PSRs candidates, further distinguishing between Young Pulsars (YPs) and Millisecond Pulsars (MSPs). We developed a hierarchical deep learning framework based on a 1D Convolutional Neural Network (1D-CNN), named TabularResCNN. This architecture treats the spectral data from the 4FGL catalog, allowing the model spectral shape. The classification is performed in two stages: first discriminating between AGNs and PSRs, and subsequently categorizing PSRs into YPs and MSPs. We implemented a cost-sensitive learning strategy to handle class imbalance and utilized Grad-CAM techniques to ensure the physical interpretability of the model's decisions. Applying this framework to 2563 unassociated sources, we identified 1136 AGNs and 202 high-confidence PSR candidates (166 YPs, 36 MSPs), increasing the pulsar population by more than 60%. They exhibit strong astrophysical consistency: YPs are confined to the Galactic plane, MSPs show a broader vertical distribution, and AGNs are isotropic. Furthermore, we identified 5 out of 5 PSRs recently confirmed by FAST. The proposed 1D-CNN framework isolates PSRs candidates based on intrinsic spectral and temporal properties, minimizing spatial bias.
#### Ab Initio Cosmological Simulations: From Inflation to Present-Day Structure Formation
 - **Authors:** Drew Jamieson, Angelo Caravano, Eiichiro Komatsu
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); General Relativity and Quantum Cosmology (gr-qc)
 - **Arxiv link:** https://arxiv.org/abs/2607.28800

 - **Pdf link:** https://arxiv.org/pdf/2607.28800

 - **Abstract**
 The cosmic web preserves a record of the physics that shaped the universe in its earliest moments, the period of exponential expansion known as cosmic inflation. However, if inflation involves significant nonlinear interactions, there are no direct theoretical predictions for the resulting cosmic web. We present the first simulation of the entire history of the universe, from deep in the inflationary epoch to the present-day cosmic structure. Applying this to axion-U(1) inflation, we find that early-universe interactions enhance small-scale structure at high redshift, imprinting the matter power spectrum and the mass function of dark matter halos with signatures of a modified primordial curvature power spectrum and non-Gaussianity. These signatures make high-redshift galaxy surveys, 21-cm observations, and line-intensity mapping promising probes of inflationary physics. More broadly, this ab initio approach provides a novel framework for mapping the signatures of nonlinear inflationary dynamics onto observable cosmic structures across cosmic time.
#### Direct shear $\times$ kSZ correlation: controlling baryons without modeling galaxies
 - **Authors:** Anoma Ganguly, Emmanuel Schaan, Elisabeth Krause, Tim Eifler
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.29091

 - **Pdf link:** https://arxiv.org/pdf/2607.29091

 - **Abstract**
 Baryonic feedback redistributes gas within and around dark matter haloes, suppressing the small-scale matter power spectrum at a level that is now the leading systematic for upcoming weak-lensing surveys. The kinetic Sunyaev-Zeldovich (kSZ) effect directly probes this redistributed gas, but existing measurements around galaxies are either tied to the properties of the chosen galaxy sample or are susceptible to biases from other extragalactic foregrounds. We address both by cross-correlating a kSZ template constructed from the tomographic weak-lensing convergence maps and the radial velocity maps reconstructed from galaxy surveys via the continuity equation, with the observed CMB temperature. We forecast the detectability for Rubin LSST Y10 and Roman kinematic lensing samples combined with ACT, SO, and CMB-HD, finding signal-to-noise ratios of $\sim$ 5-15 for current and upcoming CMB data and $\gtrsim 100$ for CMB-HD, corresponding to few-per-cent and sub-per-cent constraints, respectively, on the baryonic suppression of the matter power spectrum. This method should thus achieve sufficient statistical precision to model baryonic feedback effects for Rubin, without the systematic challenge of modeling any galaxy-matter connection.
#### Cosmological constraining power of the redshifts, heights, and angular clustering of weak gravitational lensing peaks
 - **Authors:** Jeger C. Broxterman, Matthieu Schaller, Ian G. McCarthy, Willem Elbers, John Helly, Henk Hoekstra, Konrad Kuijken, Jaime Salcido, Joop Schaye, Naomi Schutte, Elena Sellentin
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.29128

 - **Pdf link:** https://arxiv.org/pdf/2607.29128

 - **Abstract**
 Weak gravitational lensing (WL) peaks probe non-Gaussian information of the large-scale distribution of matter that is not captured by two-point lensing statistics. We study the cosmological potential of the height distribution, redshift distribution, and angular clustering of high-valued WL peaks using a Bayesian inference approach that mimics a $\textit{Euclid}$ analysis. We use a forthcoming dark-matter-only hypercube, which varies cosmology in a ten-dimensional space, including evolving dark energy, neutrino mass, decaying dark matter, and the running of the scalar spectral index. We find the individual WL peak statistics to be complementary, as the redshift distribution best constrains the matter density, $\Omega_\mathrm{m}$, and the dark energy equation-of-state parameters, $w_0$, and $w_a$; the height distribution and angular clustering are most sensitive to the amplitude of the primordial power spectrum, $\ln(10^{10}A_\mathrm{s})$; while combining the three statistics allows us to also probe the baryon density, $\Omega_\mathrm{b}$, and the Hubble parameter, $h$. A comparison to the shear two-point correlation function demonstrates that WL peaks alone outperform the commonly used statistics, while even tighter constraints are obtained when combining all. Considering the 2-dimensional $\Omega_\mathrm{m}-\ln(10^{10}A_\mathrm{s})$ and $w_0-w_a$ parameter planes, we find that the redshift distribution outperforms the angular clustering and peak-height distributions. We study the impact of the smoothing scale and find that, typically, the smallest scales yield the best results and the figure of merit improves by a factor $\approx2$ when combining multiple scales.
#### The Radial Acceleration Relation in Galaxies and Clusters from a Two-Component, Virial-Motivated Framework
 - **Authors:** Christine C. Dantas (INPE/Brazil), Andre L. B. Ribeiro (UESC/Brazil), Hugo V. Capelato (Universidade Cidade de Sao Paulo/Brazil)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.29314

 - **Pdf link:** https://arxiv.org/pdf/2607.29314

 - **Abstract**
 We present a comparative analysis of acceleration data for gravitational systems drawn from multiple observational sources, including: (i) early-type galaxies (ETGs) (Lelli et al. 2017); (ii) Brightest Cluster Galaxies (BCGs) and galaxy clusters (Tian et al. 2020, 2024); and (iii) weak gravitational lensing of isolated galaxies (Brouwer et al. 2021; Mistele et al. 2024). These data are interpreted within a framework motivated by the Two-component Virial Theorem (2VT), which defines a global baryon-dark matter (DM) coupling and sets a characteristic acceleration scale. This baseline is complemented by two models that account for the main empirical features of the Radial Acceleration Relation (RAR) over a broad range of masses and accelerations. The Constant-Interaction Approximation Model (CIA) reproduces the observed RAR trends for ETGs, BCGs, and galaxy clusters. It extends earlier results (Dantas et al. 2000, 2018), and accounts for both the small intrinsic scatter and the emergence of a characteristic acceleration scale. At the very low accelerations probed by weak-lensing data (below accelerations of order $10^{-14}~\mathrm{m\,s^{-2}}$), however, this model breaks down. In this regime, the Virial-Motivated Interaction Model (VIM) incorporates the radial structure of the baryon-DM interaction through a local, radius-dependent contribution to the acceleration. Taken together, the 2VT (global scale), the CIA and the VIM provide a physically motivated framework that captures the main empirical features of the RAR.
#### Recovering pattern speeds of simulated face-on barred galaxies via Schwarzschild modelling
 - **Authors:** Iliya S. Tikhonenko, Jens Thomas, Roberto P. Saglia
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.29406

 - **Pdf link:** https://arxiv.org/pdf/2607.29406

 - **Abstract**
 Stellar bars are a major driving force in the secular evolution of their host galaxies. To better understand the connections between the 3D bar density structure, its orbital composition, stellar populations, and underlying dark matter distribution, it is desirable to construct detailed dynamical models of barred galaxies. However, only a few external barred galaxies have been studied in this way so far. We present a new Schwarzschild orbit superposition code for triaxial potentials with figure rotation and test it extensively using mock data from an N-body simulation of a strongly barred galaxy. We investigate the recovery of model parameters in the nearly face-on case which was not previously considered. In particular, we demonstrate a 10% accuracy of both the pattern speed and mass-to-light ratio and a 20% accuracy for the dark matter halo mass scaling at the inclination 20°. Surprisingly, we obtain a similarly accurate result for the pattern speed in an exact face-on limit, where conventional methods such as Tremaine-Weinberg are no longer applicable. This result suggests that varying the pattern speed at fixed bar length, corresponding to the transition between slow and fast bars, alters the distribution function in a way that produces a systematic change in the vertical velocity distribution, which can not be compensated by the in-plane velocity components.


by olozhika (Xing Yuchen). 


2026-08-03
