# Showing new listings for Thursday, 9 April 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 6papers 
#### Learning the Stellar Structure Equations via Self-supervised Physics-Informed Neural Networks
 - **Authors:** Manuel Ballester, Santiago Lopez-Tapia, Seth Gossage, Patrick Koller, Philipp M. Srivastava, Ugur Demir, Yongseok Jo, Almudena P. Marquez, Christoph Wuersch, Souvik Chakraborty, Vicky Kalogera, Aggelos Katsaggelos
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM); Artificial Intelligence (cs.AI)
 - **Arxiv link:** https://arxiv.org/abs/2604.06255

 - **Pdf link:** https://arxiv.org/pdf/2604.06255

 - **Abstract**
 Stellar astrophysics relies critically on accurate descriptions of the physical conditions inside stars. Traditional solvers such as \texttt{MESA} (Modules for Experiments in Stellar Astrophysics), which employ adaptive finite-difference methods, can become computationally expensive and challenging to scale for large stellar population synthesis ($>10^9$ stars). In this work, we present an self-supervised physics-informed neural network (PINN) framework that provides a mesh-free and fully differentiable approach to solving the stellar structure equations under hydrostatic and thermal equilibrium. The model takes as input the stellar boundary conditions (at the center and surface) together with the chemical composition, and learns continuous radial profiles for mass $M_r(r)$, pressure $P(r)$, density $\rho(r)$, temperature $T(r)$, and luminosity $L_r(r)$ by enforcing the governing structure equations through physics-based loss terms. To incorporate realistic microphysics, we introduce auxiliary neural networks that approximate the equation of state and opacity tables as smooth, differentiable functions of the local thermodynamic state. These surrogates replace traditional tabulated inputs and enable end-to-end training. Once trained for a given star, the model produces continuous solutions across the entire radial domain without requiring discretization or interpolation. Validation against benchmark \texttt{MESA} models across a range of stellar masses yields a Mean Relative Absolute Error of $3.06\%$ and an average $R^2$ score of $99.98\%$. To our knowledge, this is the first demonstration that the stellar structure equations can be solved in a fully self-supervised and data-free fashion employing PINNs. This work establishes a foundation for scalable, physics-informed emulation of stellar interiors and opens the door to future extensions toward time-dependent stellar evolution.
#### Collisional Dynamics of Stars and Dark Matter in Ultra-Faint Galaxies
 - **Authors:** Raphaël Errani, Nicolas Esser, Jorge Peñarrubia, Matthew G. Walker
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2604.06304

 - **Pdf link:** https://arxiv.org/pdf/2604.06304

 - **Abstract**
 We use controlled N-body simulations to study the collisional exchange of energy between stars and dark matter in ultra-faint galaxies. We find that dynamical friction between stars and subsolar-mass dark matter particles results in the depletion of dark matter from the galaxies' centers, thereby transforming dark matter cusps into constant-density cores. The process is particularly effective in tidally limited galaxies with low stellar velocity dispersion. As high-mass stars sink toward the center of the dark matter halo, the dynamical-to-stellar mass ratio within the stellar half-light radius decreases monotonically. The stellar population of a dark matter-dominated galaxy is thereby compacted into a dense, baryon-dominated cluster, surrounded by a dark matter halo. Such a cluster would share the chemical composition of an ultra-faint galaxy, yet would be virtually dark matter-free within its half-light radius. We moreover find that the collisional cooling with dark matter particles provides an efficient pathway for the formation of stellar binaries in the contracting cluster. The contraction is eventually slowed down due to the decreasing central dark matter densities and the formation of stellar binaries. Our models highlight that the dynamical processes governing the faintest galaxies give rise to a rich phenomenology, blurring the line between the dynamics of globular clusters and galaxies.
#### Introducing sapphire: Towards Hybrid Physics-Informed, Data-Driven Modeling of Galaxy Formation
 - **Authors:** Viraj Pandya, Greg L. Bryan, T. Lucas Makinen, Austen Gabrielpillai, Christopher Carr, Drummond B. Fielding, Lars Hernquist, Matthew Ho, Kartheik Iyer, Christian Kragh Jespersen, Sophie Koudmani, Marta Laska, Pablo Lemos, Christopher C. Lovell, Lucia A. Perez, William F. Robinson Jr., Rachel S. Somerville, Tjitske K. Starkenburg, Richard Stiskalek, Bryan Terrazas, G. Mark Voit
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2604.06318

 - **Pdf link:** https://arxiv.org/pdf/2604.06318

 - **Abstract**
 Semi-analytic models (SAMs) have been treating galaxy populations as dynamical systems for $\gtrsim50$ years, but their evolution equations remain poorly constrained. We introduce sapphire, a modular, automatically differentiable, GPU-accelerated SAM written from scratch in JAX. For the first time, we compute exact Jacobian matrices of our nonlinear differential equations and show that they have interpretable, non-random structures, using the Pandya et al. (2023) physical model as an initial example. Both local and global sensitivity analyses reveal that supernova energy loading is a key astrophysical parameter for galaxy evolution. We use gradient descent and Hamiltonian Monte Carlo (HMC) to perform comprehensive mock parameter recovery tests. These indicate that the z=0 stellar-to-halo-mass relation alone does not contain enough information to infer many astrophysical parameters. Using observations of star-forming galaxies from the MaNGA survey and the Behroozi et al. (2019) empirical model as one baseline, we derive multiple posteriors assuming different combinations of data, including z=0 interstellar medium gas fractions and metallicities. The inferred physical parameters suggest that galaxies self-regulate their star formation primarily through preventative rather than ejective feedback. Both Fisher and HMC forecasts demonstrate the potential of sapphire to enable precision inference for galaxy formation, but more work is needed to expand its library of models. We discuss how our unique blend of differentiability, massive GPU parallelization, numerical robustness and principled Bayesian methods sets the stage for hybrid physics-informed, data-driven discovery of galaxy formation astrophysics and cosmology. We make sapphire publicly available at this https URL.
#### Euclid Quick Data Release (Q1). AgileLens: A scalable CNN-based pipeline for strong gravitational lens identification
 - **Authors:** Euclid Collaboration: X. Xu (1 and 2), R. Chen (1), T. Li (1), A. R. Cooray (1), S. Schuldt (3 and 4), J. A. Acevedo Barroso (5), D. Stern (5), D. Scott (6), M. Meneghetti (7 and 8), G. Despali (9 and 7 and 8), J. Chopra (1), Y. Cao (1), M. Cheng (1), J. Buda (1), J. Zhang (1), J. Furumizo (1), R. Valencia (1), Z. Jiang (2), C. Tortora (10), N. E. P. Lines (11), T. E. Collett (11), S. Fotopoulou (12), A. Galan (13 and 14), A. Manjón-García (15), R. Gavazzi (16 and 17), L. Iwamoto (18), S. Kruk (19), M. Millon (20), P. Nugent (21), C. Saulder (22 and 23), D. Sluse (24), J. Wilde (25), M. Walmsley (26 and 27), F. Courbin (25 and 28 and 29), R. B. Metcalf (9 and 7), B. Altieri (19), A. Amara (30), S. Andreon (31), N. Auricchio (7), C. Baccigalupi (32 and 33 and 34 and 35), M. Baldi (36 and 7 and 8), A. Balestra (37), S. Bardelli (7), P. Battaglia (7), R. Bender (22 and 23), A. Biviano (33 and 32), E. Branchini (38 and 39 and 31), M. Brescia (40 and 10), S. Camera (41 and 42 and 43), V. Capobianco (43), C. Carbone (4), V. F. Cardone (44 and 45), J. Carretero (46 and 47), S. Casas (48 and 49), M. Castellano (44), G. Castignani (7), S. Cavuoti (10 and 50), A. Cimatti (51), C. Colodro-Conde (52), G. Congedo (53), C. J. Conselice (27), L. Conversi (54 and 19), Y. Copin (55), H. M. Courtois (56), M. Cropper (57), A. Da Silva (58 and 59), H. Degaudenzi (60), G. De Lucia (33), C. Dolding (57), H. Dole (61), F. Dubath (60), X. Dupac (19), S. Dusini (62), S. Escoffier (63), M. Farina (64), R. Farinelli (7), S. Farrens (65), S. Ferriol (55), F. Finelli (7 and 66), P. Fosalba (67 and 68), M. Frailis (33), E. Franceschi (7), M. Fumana (4), S. Galeotta (33), K. George (69), W. Gillard (63), B. Gillis (53), C. Giocoli (7 and 8), P. Gómez-Alvarez (70 and 19), J. Gracia-Carpio (22), A. Grazian (37), F. Grupp (22 and 23), S. V. H. Haugan (71), W. Holmes (5), F. Hormuth (72), A. Hornstrup (73 and 74), K. Jahnke (75), M. Jhabvala (76), B. Joachimi
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Computer Vision and Pattern Recognition (cs.CV)
 - **Arxiv link:** https://arxiv.org/abs/2604.06648

 - **Pdf link:** https://arxiv.org/pdf/2604.06648

 - **Abstract**
 We present an end-to-end, iterative pipeline for efficient identification of strong galaxy--galaxy lensing systems, applied to the Euclid Q1 imaging data. Starting from VIS catalogues, we reject point sources, apply a magnitude cut (I$_E$ $\leq$ 24) on deflectors, and run a pixel-level artefact/noise filter to build 96 $\times$ 96 pix cutouts; VIS+NISP colour composites are constructed with a VIS-anchored luminance scheme that preserves VIS morphology and NISP colour contrast. A VIS-only seed classifier supplies clear positives and typical impostors, from which we curate a morphology-balanced negative set and augment scarce positives. Among the six CNNs studied initially, a modified VGG16 (GlobalAveragePooling + 256/128 dense layers with the last nine layers trainable) performs best; the training set grows from 27 seed lenses (augmented to 1809) plus 2000 negatives to a colour dataset of 30,686 images. After three rounds of iterative fine-tuning, human grading of the top 4000 candidates ranked by the final model yields 441 Grade A/B candidate lensing systems, including 311 overlapping with the existing Q1 strong-lens catalogue, and 130 additional A/B candidates (9 As and 121 Bs) not previously reported. Independently, the model recovers 740 out of 905 (81.8%) candidate Q1 lenses within its top 20,000 predictions, considering off-centred samples. Candidates span I$_E$ $\simeq$ 17--24 AB mag (median 21.3 AB mag) and are redder in Y$_E$--H$_E$ than the parent population, consistent with massive early-type deflectors. Each training iteration required a week for a small team, and the approach easily scales to future Euclid releases; future work will calibrate the selection function via lens injection, extend recall through uncertainty-aware active learning, explore multi-scale or attention-based neural networks with fast post-hoc vetters that incorporate lens models into the classification.
#### Galactic Rotation Curves from Full-Disk Newtonian Gravity: The Lost and Found Model
 - **Authors:** Adolfo Santa Fe Dueñas
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2604.06917

 - **Pdf link:** https://arxiv.org/pdf/2604.06917

 - **Abstract**
 The approximately flat outer parts of spiral galaxy rotation curves are commonly interpreted as evidence for a discrepancy between the observed baryonic mass and the dynamical mass inferred from the measured orbital velocities. In most standard analyses, this discrepancy is quantified using $v^2(R)=GM(<R)/R$, which is exact only under spherical symmetry. However, spiral galaxies are flattened disk systems, for which mass exterior to the galactocentric radius under consideration can contribute non-negligibly to the gravitational field. We introduce the Lost and Found (LF) model, a geometrically consistent Newtonian framework based on direct full-disk gravitational integration and a parametrized representation of the disk surface density. In this approach, the gravitational field is computed without imposing spherical symmetry, and the disk mass distribution is represented by two exponential components with a smooth outer truncation. We apply the LF model to a heterogeneous sample of disk galaxies spanning a broad range of masses and radial extents. The model reproduces the main observed features of the rotation curves, including the inner rise and the approximately flat outer behavior, without explicitly invoking a dark matter halo or modifying Newtonian gravity. Across the sample, the LF-inferred mass scales nearly linearly with the conventional dynamical mass, with a characteristic reduction factor $\eta_{LF}$ ~ 0.67. These results indicate that part of the inferred mass discrepancy may arise from the geometric treatment of gravitation in disk galaxies, and motivate a reassessment of mass inference in non-spherical systems.
#### Primordial magnetic fields in the light of upcoming post-EoR Lyman-$α$ and 21-cm observations
 - **Authors:** Arko Bhaumik, Sourav Pal, Supratik Pal
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Instrumentation and Methods for Astrophysics (astro-ph.IM); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2604.07327

 - **Pdf link:** https://arxiv.org/pdf/2604.07327

 - **Abstract**
 The Lorentz force exerted by a primordial magnetic field (PMF) on the coupled baryon-dark matter system may enhance total matter power at small scales after recombination. In the post-reionization (post-EoR) era, a weakly scale-dependent PMF of sub-nG strength is thus expected to influence the Lyman-$\alpha$ (Ly$\alpha$) power spectrum, the 21 cm power spectrum, and the Ly$\alpha$-21 cm cross-spectrum at scales $k\gtrsim 1\:h/\textrm{Mpc}$. We investigate the prospects of constraining the PMF sector via these three cosmological observables, by employing SNR estimation and Fisher forecast on the PMF amplitude $B_0$ and spectral index $n_{\rm B}$, for a next-generation DESI-like spectroscopic survey and two upcoming 21 cm facilities, namely SKA1-Mid and PUMA. Our results indicate the possibility of constraining both PMF parameters with $\lesssim10\%$ relative errors through the uncontaminated 21 cm auto-spectrum as well as the Ly$\alpha$-21 cm cross-spectrum probed with the DESI-like+SKA1-Mid combination. Indicatively, the Ly$\alpha$-21 cm cross-correlation via DESI-like+SKA1-Mid is predicted to constrain a fiducial scenario $B_0=0.8$ nG and $n_{\rm B}=-2.9$ with $1\sigma$ errors $\Delta B_0\approx 0.07$ nG and $\Delta n_{\rm B}\approx0.02$. The DESI-like+PUMA setup is predicted to fare relatively worse due to its restriction to larger scales, resulting in comparatively one order of magnitude relaxed error bounds for similar fiducials. Since the Ly$\alpha$-21 cm cross-signal is expected to be largely insensitive to foreground contamination (unlike the 21 cm auto-spectrum), it may serve as an optimal foreground-immune post-EoR probe to constrain a weakly scale-dependent sub-nG PMF via future DESI-like+SKA1-Mid observations.


by olozhika (Xing Yuchen). 


2026-04-09
