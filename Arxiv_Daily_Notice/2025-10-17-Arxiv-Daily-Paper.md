# Showing new listings for Friday, 17 October 2025
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 6papers 
#### Detecting Ca II Absorption Lines with a Fe II assisted Dual Neural Network
 - **Authors:** Lucas Wang, Jian Ge, Kevin Willis
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.13863

 - **Pdf link:** https://arxiv.org/pdf/2510.13863

 - **Abstract**
 Ca II absorbers, characterized by dusty and metal-rich environments, provide unique insights into the interstellar medium of galaxies. However, their rarity and weak absorption features have hindered comprehensive studies. In this work, we present a novel dual CNN approach to detect Ca II absorption systems, analyzing over 100,000 quasar spectra from the Sloan Digital Sky Survey (SDSS) Data Release 16. Our primary CNN identifies Ca II features, while a secondary CNN cross-verifies these detections using five Fe II absorption lines. This approach yielded 1,646 Ca II absorption systems, including 525 previously known absorbers and 1,121 new discoveries, nearly tripling the size of any previously reported catalog. Among our Ca II absorbers, 95 are found to show the 2175Å dust feature (2DA), corresponding to 22% of strong absorbers, 7% of weak absorbers, and $\sim$12% of the overall Ca II population at $0.8 < z_{\text{abs}} < 1.4$. Across the full redshift range of $0.36 < z_{\text{abs}} < 1.4$, $\sim$1.5% of Mg II absorbers host Ca II.
#### Dynamic SBI: Round-free Sequential Simulation-Based Inference with Adaptive Datasets
 - **Authors:** Huifang Lyu, James Alvey, Noemi Anau Montel, Mauro Pieroni, Christoph Weniger
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Cosmology and Nongalactic Astrophysics (astro-ph.CO); Machine Learning (cs.LG); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/2510.13997

 - **Pdf link:** https://arxiv.org/pdf/2510.13997

 - **Abstract**
 Simulation-based inference (SBI) is emerging as a new statistical paradigm for addressing complex scientific inference problems. By leveraging the representational power of deep neural networks, SBI can extract the most informative simulation features for the parameters of interest. Sequential SBI methods extend this approach by iteratively steering the simulation process towards the most relevant regions of parameter space. This is typically implemented through an algorithmic structure, in which simulation and network training alternate over multiple rounds. This strategy is particularly well suited for high-precision inference in high-dimensional settings, which are commonplace in physics applications with growing data volumes and increasing model fidelity. Here, we introduce dynamic SBI, which implements the core ideas of sequential methods in a round-free, asynchronous, and highly parallelisable manner. At its core is an adaptive dataset that is iteratively transformed during inference to resemble the target observation. Simulation and training proceed in parallel: trained networks are used both to filter out simulations incompatible with the data and to propose new, more promising ones. Compared to round-based sequential methods, this asynchronous structure can significantly reduce simulation costs and training overhead. We demonstrate that dynamic SBI achieves significant improvements in simulation and training efficiency while maintaining inference performance. We further validate our framework on two challenging astrophysical inference tasks: characterising the stochastic gravitational wave background and analysing strong gravitational lensing systems. Overall, this work presents a flexible and efficient new paradigm for sequential SBI.
#### Extracting latent representations from X-ray spectra. Classification, regression, and accretion signatures of Chandra sources
 - **Authors:** Nicolò Oreste Pinciroli Vago, Juan Rafael Martínez-Galarza, Roberta Amato
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2510.14102

 - **Pdf link:** https://arxiv.org/pdf/2510.14102

 - **Abstract**
 The study of X-ray spectra is crucial to understanding the physical nature of astrophysical sources. Machine learning methods can extract compact and informative representations of data from large datasets. The Chandra Source Catalog (CSC) provides a rich archive of X-ray spectral data, which remains largely underexplored in this context. This work aims to develop a compact and physically meaningful representation of Chandra X-ray spectra using deep learning. To verify that the learned representation captures relevant information, we evaluate it through classification, regression, and interpretability analyses. We use a transformer-based autoencoder to compress X-ray spectra. The input spectra, drawn from the CSC, include only high-significance detections. Astrophysical source types and physical summary statistics are compiled from external catalogs. We evaluate the learned representation in terms of spectral reconstruction accuracy, clustering performance on 8 known astrophysical source classes, and correlation with physical quantities such as hardness ratios and hydrogen column density ($N_H$). The autoencoder accurately reconstructs spectra with 8 latent variables. Clustering in the latent space yields a balanced classification accuracy of $\sim$40% across the 8 source classes, increasing to $\sim$69% when restricted to AGNs and stellar-mass compact objects exclusively. Moreover, latent features correlate with non-linear combinations of spectral fluxes, suggesting that the compressed representation encodes physically relevant information. The proposed autoencoder-based pipeline is a powerful tool for the representation and interpretation of X-ray spectra, providing a compact latent space that supports both classification and the estimation of physical properties. This work demonstrates the potential of deep learning for spectral studies and uncovering new patterns in X-ray data.
#### Active galactic nucleus outflows accelerate when they escape the bulge
 - **Authors:** Kastytis Zubovas, Matas Tartėnas
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.14667

 - **Pdf link:** https://arxiv.org/pdf/2510.14667

 - **Abstract**
 Large-scale outflows driven by AGNs are an important element of galaxy evolution. Detailed analysis of their properties allows us to probe the activity history of the galactic nucleus and, potentially, other properties of the host galaxy. A recent paper presents detailed radial velocity profiles of outflows in ten AGN host galaxies and shows a common trend of approximately constant velocity in the centre followed by rapid acceleration outside $R_{\rm tr} \sim 1 - 3$ kpc. We show that this is a consequence of the AGN-driven outflows clearing the gaseous bulges of the host galaxies and beginning to expand into a region of negligible gas density. We used a 1D semi-analytical code to calculate outflow propagation in each of the ten galaxies, assuming a constant AGN luminosity and an isothermal bulge density profile, with a finite bulge radius, and leaving the gas fraction and total mass of the bulge as free parameters. We also considered the effect of different gas density profiles, variations in bulge velocity dispersion, AGN luminosity, and the effect of outflow fragmentation. Our simplest model can fit six outflow profiles essentially perfectly, while another can be fit if the bulge gas density profile is shallower than isothermal. A shallower density profile also improves the fit in the central regions of the remaining three outflows, but they accelerate faster than our models predict; this could be evidence of significant gas cooling and star formation that reduce the total mass of outflowing gas. We conclude that a simple AGN-driven wind feedback model can explain the detailed velocity profiles of real outflows in local AGN hosts. The free parameters of our model have values that fall well within reasonable ranges. This suggests that the simple scenario we envisioned is close to the true conditions governing the general trends of large-scale outflow expansion.
#### Search for exocomets transits in Kepler light curves: Ten new transits identified
 - **Authors:** Pierre Dumond, Alain Lecavelier des Etangs, Flavien Kiefer, Guillaume Hébrard, Vincent Caillé
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2510.14687

 - **Pdf link:** https://arxiv.org/pdf/2510.14687

 - **Abstract**
 The Kepler mission, despite its conclusion over a decade ago, continues to offer a rich dataset for uncovering new astrophysical objects and phenomena. In this study, we conducted a comprehensive search for exocometary transit signatures within the Kepler light curves, using a machine learning approach based on a neural network trained on a library of theoretical exocomet transit light curves. By analyzing the light curves of 201,820 stars, we identified candidate events through the neural network and subjected the output to filtering and visual inspection to mitigate false positives. Our results are presented into three catalogs of increasing ambiguity. The first-tier catalog includes 17 high-confidence exocometary transit events, comprising 7 previously reported events and 10 newly identified ones, each associated with a different host star. The second-tier catalog lists 30 lower-confidence events that remain consistent with possible exocometary transits. The third-tier catalog consists of 49 more symmetric photometric events that could be either exocometary transits, exoplanet mono-transits, or false positives due to eclipsing binaries mimicking transits. Contrary to previous studies, which suggested that the cometary activity was favored by stellar youth, we find a broad age distribution among candidate host stars, including several red giants. This challenges the general idea of a decline in cometary activity with stellar age and underlines the need for further investigation into the temporal evolution of exocometary activity in planetary systems.
#### Phantom Mirage from Axion Dark Energy
 - **Authors:** Rayne Liu, Yijie Zhu, Wayne Hu, Vivian Miranda
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2510.14957

 - **Pdf link:** https://arxiv.org/pdf/2510.14957

 - **Abstract**
 Supernova (SN) and baryon acoustic oscillation (BAO) distance measures have recently provided hints that the dark energy is not only dynamical but apparently evolves from normal to phantom dark energy between redshifts $0<z<1$. A normal axion dark energy component in the mass range just below the Hubble scale can mimic a phantom component by appearing as dark energy at $z=1$ and dark matter at $z=0$, raising the possibility of a phantom mirage. We show that there is a wide range of axion dark energy contributions that can resolve the SN-BAO tension as well as thawing quintessence does, leaving BAO tension with the cosmic microwave background (CMB) for the distance measures from $z\sim 1$ to recombination to be resolved at high redshifts. With axions, raising the optical depth to reionization to $\tau \approx 0.1$ works essentially as well as $w_0-w_a$ phantom dark energy for all but the lowE CMB data, with a remaining $\Delta\chi^2\sim -16$ compared with $\Lambda$CDM, whereas a small spatial curvature of $\Omega_K \sim 0.003$ can largely relax the full SN-BAO-CMB tension with a total $\Delta\chi^2 \sim -12$.


by olozhika (Xing Yuchen). 


2025-10-17
