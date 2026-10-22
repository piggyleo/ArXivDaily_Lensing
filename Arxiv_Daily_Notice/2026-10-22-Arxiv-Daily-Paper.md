# Showing new listings for Thursday, 22 October 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 11papers 
#### A Hybrid Neural Network Emulator for M1 Neutrino Reaction Rates in Binary Neutron Star Merger Simulations
 - **Authors:** Yi Qiu, David Radice, Raffaele Ferrari, Albino Perego
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2610.28740

 - **Pdf link:** https://arxiv.org/pdf/2610.28740

 - **Abstract**
 We present a neural network emulator for the bns_nurates library, which computes neutrino reaction rates used in binary neutron star merger simulations. Following a hybrid strategy, we emulate only the computationally dominant two-dimensional reactions---pair processes, bremsstrahlung, and inelastic neutrino-electron scattering---while evaluating the inexpensive one-dimensional processes still with bns_nurates. We find that the emulator reproduces the opacities to within a few percent across the relevant thermodynamic conditions and accelerates their evaluation by roughly an order of magnitude. When deployed in a global Athenak binary neutron star merger simulation, it recovers the remnant structure, neutrino luminosities, and ejecta composition of a reference run using the full bns_nurates library, at approximately half the overall cost
#### Gravothermal Evolution of Self-Interacting Dark Matter Halos across Knudsen Numbers
 - **Authors:** James Gurian, Suroor Seher Gandhi, Neal Dalal, Simon May
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.28745

 - **Pdf link:** https://arxiv.org/pdf/2610.28745

 - **Abstract**
 If the dark matter self-interacts elastically via a light mediator, then at relative velocities above a scale $w$ dictated by particle physics parameters, the cross section scales as $\sigma \propto v^{-4}$. Depending on the value of $w$, the self-interaction cross section in low-mass halos could be (much) larger than has been previously studied extensively. We perform kinetic simulations of isolated self-interacting dark matter halos using the code KiSS-SIDM for a wide range of halo masses, concentrations, and cross sections from $50 \,\mathrm{cm}^2 \, \mathrm{g}^{-1}$ to $250{,}000 \, \mathrm{cm}^2 \, \mathrm{g}^{-1}$, including several velocity-dependent and fully differential (anisotropic) cross sections. We demonstrate that for idealized NFW halos the collapse time can be predicted from the Knudsen number at the scale radius of the halo. We perform similar calculations for halos extracted from cosmological simulations using either $N$-body (collisionless) or SPH (strongly collisional) dynamics, and then evolve cutouts with KiSS-SIDM. For these halos, the collapse times differ from the idealized NFW simulations by up to a factor of a few. Further, we calibrate a hydrostatic fluid model to these results, which solves the structure equations as a boundary value problem via two-point shooting. The fluid calculation predicts that for velocity-independent cross sections, a convective region of the halo develops late in the collapse. The collapse times agree well between the kinetic simulations and the fluid code, especially in the velocity-independent case. The density profiles agree well in some cases, which include all of the velocity-dependent cross section runs.
#### Link between the properties of circumgalactic outflows and the recent star formation history of their host galaxies
 - **Authors:** Ismael Pessa, Lutz Wisotzki, Constanza Muñoz López, Tanya Urrutia, Ramona Augustin, Thierry Contini, Yucheng Guo, Daria Kozlova, Haruka Kusakabe, Sowgat Muzahid, John Pharo
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.28752

 - **Pdf link:** https://arxiv.org/pdf/2610.28752

 - **Abstract**
 Galactic outflows play a key role in galaxy evolution, yet their connection to the star formation history of their host galaxies remains poorly constrained. Building on previous work modeling extended Mg II emission of galaxies observed with VLT/MUSE to infer outflow properties, we investigate how these properties depend on the recent SFH. We derive non-parametric SFHs by fitting spectroscopic and photometric data with linear combinations of single stellar population models, and compute star formation rates over different timescales sensitive to recent stochastic bursts. We find moderate correlations between these SFRs (and sSFRs) and the kinematic properties of the outflows, namely maximum velocity and radial acceleration rate. Such correlations are not recovered using SFR tracers based on [O II] luminosity or parametric SFHs, highlighting the importance of capturing bursty star formation on timescales consistent with the traveling time of ejected gas into the circumgalactic medium. Using the extent and kinematics of the Mg II halos, we estimate each galaxy's outflow launching time and compute the SFR averaged over the relevant timescale. We identify a correlation between this SFR and the maximum outflow velocity, although it is not significantly stronger than those obtained using fixed averaging timescales. This suggests that the properties of Mg II halos are shaped by a series of star formation events rather than by a single dominant burst. Lastly, we find faster outflows in galaxies whose recent star formation is dominated by one or a few concentrated episodes, whereas galaxies with star formation spread more evenly over time exhibit slower outflows. These results indicate that the circumgalactic medium acts as a dynamical archive of recent star formation, linking bursty galaxy growth to outflow kinematics and providing a direct observational constraint on feedback models.
#### PIANISTpy: A JAX-based Python package for velocity-anisotropic astrophysical equilibrium models
 - **Authors:** Barry T. Chiang, Frank C. van den Bosch, Hsi-Yu Schive
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO); Instrumentation and Methods for Astrophysics (astro-ph.IM); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2610.28758

 - **Pdf link:** https://arxiv.org/pdf/2610.28758

 - **Abstract**
 The hierarchical assembly of dark matter haloes and galaxies via mergers and anisotropic mass accretion naturally imprints non-trivial velocity anisotropy onto haloes and galaxies, an empirical fact emerging from cosmological simulations. However, dynamical studies based on idealised numerical simulations typically assume isotropic velocity distributions for the systems studied. This is mainly because no tools exist to construct anisotropic initial conditions with fully self-consistent (i.e., physical and instability-free) truncation boundary conditions for finite spatial extents. Here we present the first such analytical framework that performs truncation in phase space, with two distinct approaches to guarantee either the monotonicity of output distribution functions or identical truncated density profiles. We additionally present the open-source JAX-based GPU-accelerated Python package PIANISTpy (Particle Initial conditions with ANISoTropy) for constructing spherical, non-rotating initial conditions, supporting arbitrary double-power-law analytical radial density profiles and a library of analytical anisotropy profiles. This framework further permits the construction of systems with non-analytical anisotropy profiles via an arbitrary linear superposition of all implemented analytical anisotropy models as basis functions. PIANISTpy also outputs 3D velocity profiles and line-of-sight-integrated observables with end-to-end differentiability for rapid gradient-based Monte Carlo inference, and self-consistent local dark matter velocity distributions of anisotropic haloes beyond the unphysical Maxwell-Boltzmann simplification adopted in terrestrial detection experiments. We discuss use cases and demonstrate PIANISTpy's orders-of-magnitude higher numerical solver accuracy and superior dynamical stability of particle initial conditions relative to existing tools, including galpy and AGAMA.
#### Magnetic monopoles produced by first-order phase transition
 - **Authors:** Yuefeng Di, Ligong Bian, Rong-Gen Cai
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); General Relativity and Quantum Cosmology (gr-qc); High Energy Physics - Lattice (hep-lat); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2610.29349

 - **Pdf link:** https://arxiv.org/pdf/2610.29349

 - **Abstract**
 We present the first 3D lattice simulations of magnetic monopole production from a first-order phase transition, using the Press-Ryden-Spergel method, capturing the subsequent annihilation stage and the entry into the scaling regime in an expanding universe. We establish the quantitative relationship between the initial bubble number and the residual monopole abundance, and calculate the magnetic field and gravitational wave power spectra sourced by monopole dynamics. Crucially, we find that the magnetic field spectrum displays a steep $k^{-5}$ decline beyond the monopole size $w_M$, whereas the peak of the gravitational wave spectrum aligns with the scale of the mean monopole separation $d_M$, governed by $k^3$ and $k^{-3}$ scalings on the low- and high-wavenumber sides of the peak, respectively. However, since the resulting magnetic field strength is excluded by blazar observations, magnetic monopoles cannot be the origin of primordial cosmic magnetic fields. Finally, we determine the allowed monopole mass under the constraints of the Parker bound ($m_M\lesssim2.18\times10^{11}\,\mathrm{GeV}$) and dark matter abundance ($m_M\lesssim1.58\times10^{12}\,\mathrm{GeV}$).
#### Data-driven characterisation of variable source light curves with multimodal representation learning
 - **Authors:** M. Madarász, G. Marton, M. Audard
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2610.29412

 - **Pdf link:** https://arxiv.org/pdf/2610.29412

 - **Abstract**
 Surveys such as the Zwicky Transient Facility (ZTF) and the Vera C. Rubin Observatory Legacy Survey of Space and Time (LSST) produce light curves for hundreds of millions of variables. Their characterisation traditionally relies on supervised classifiers with hand-crafted features and curated labels, limiting them to predefined taxonomies and individual surveys. We present a general, survey-agnostic framework that characterises variable sources without labelled training data, producing low-dimensional representations of light curve properties such as amplitude, periodicity, and asymmetry. A multimodal architecture combines two complementary views, a Transformer encoder on raw observations and a convolutional neural network on a generalised Lomb-Scargle periodogram. Each light curve is randomly split into two temporal halves as independent views, and the branches are trained jointly with VICReg to produce embeddings invariant across halves while keeping each dimension informative. We evaluate on 37 006 ZTF sources spanning 14 variable star classes in four broad physical categories. A linear classifier on the frozen 64-dimensional embeddings achieves 77.1% balanced accuracy for classes and 90.5% for broad categories. Combining both branches improves balanced accuracy by up to 14.9 percentage points over the best single modality, confirming their complementarity. Interpretable light curve properties are encoded on distinct dimensions, and within-class analysis reveals physical substructure unresolved by reference labels. Retraining on ZTF g and i bands without modification reproduces the main results, and concatenating multi-band embeddings improves balanced accuracy to 86.1%. The framework needs no labels, phase folding, or survey-specific preprocessing and applies directly to other surveys with different cadences and wavelength coverage.
#### Domain models of turbulent magnetic fields and the spectral shape of ensemble averaged axion-photon conversion
 - **Authors:** Oleksandr Khasai, Lidiia Zadorozhna, Denys Malyshev, Oleg Ruchayskiy
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2610.29541

 - **Pdf link:** https://arxiv.org/pdf/2610.29541

 - **Abstract**
 Axion-like particles are light pseudoscalars that appear in many extensions of the Standard Model and are candidates for dark matter. Through their mixing with photons, they imprint energy dependent modulations on the spectra of astrophysical sources shining through magnetised media. When a distant source shines through the turbulent magnetic field of an intervening galaxy cluster, these modulations are stochastic. It has recently been shown that averaging over an ensemble of such sources instead produces a smooth absorption-like feature. In this work we derive the analytic form of this ensemble averaged signal, previously known only numerically. We further relate the index $a$ of the magnetic field energy spectrum to the index $\beta$ of the domain size distribution that simulations use to describe the turbulent field. For $1<a<2$ the two indices obey the simple analytic relation $\beta=3-a$. Any distribution with $\beta<1$ instead mimics the spectral index $a=2$, which the sharp domain walls impose. For Kolmogorov turbulence, relevant for galaxy clusters, the relation gives $\beta=4/3$.
#### Cosmology of self-interacting ultralight dark matter: simultaneous shifts in the Hubble constant and structure growth
 - **Authors:** Seokcheon Lee, Jae-Weon Lee
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.29582

 - **Pdf link:** https://arxiv.org/pdf/2610.29582

 - **Abstract**
 We study the cosmology of self-interacting ultralight dark matter. The scalar field evolves from an early Hubble-frozen phase to a quartic-dominated radiation-like phase and finally to a quadratic matter-like phase. The intermediate phase increases the pre-recombination expansion rate and reduces the sound horizon, while the late phase allows the same field to contribute to dark matter. We implement the background and linear perturbations of a mixed cold-dark-matter and ultralight-dark-matter cosmology in CLASS. For $m=10^{-22}\,{\rm eV}$ and $\tilde m\simeq1\,{\rm eV}$, increasing the ultralight-dark-matter fraction raises the fixed-$\theta_*$ value of $H_0$, lowers the late-time clustering amplitude, strengthens the scale-dependent matter-power suppression, and produces a smooth CMB-temperature residual reaching about $9\%$ for the largest fraction considered. The model therefore generates simultaneous background and growth shifts in the directions relevant to the Hubble and structure-growth tensions. Establishing whether these shifts improve a joint fit requires a likelihood-level observational analysis.
#### Constraining Dynamical Dark Energy with Tomographic Galaxy and CMB Weak Lensing Through Higher-Order Statistics
 - **Authors:** Shu-Fan Chen, J. Colin Hill, Zoltán Haiman
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.29937

 - **Pdf link:** https://arxiv.org/pdf/2610.29937

 - **Abstract**
 Tomographic weak gravitational lensing probes cosmic structure growth and geometry, making it a powerful probe of dynamical dark energy. We forecast information beyond the lensing power spectrum from non-Gaussian statistics of tomographic galaxy and CMB lensing convergence maps. Using the $\texttt{DDELenS}$ suite of ray-traced $N$-body simulations, we build Gaussian process emulators for power spectra, Minkowski functionals, moments, peak and minima counts, and the wavelet scattering transform, varying $\Omega_m$, $\sigma_8$, $w_0$, and $w_a$. We consider Rubin-like galaxy lensing and Simons Observatory-like CMB lensing over $15{,}000\,\mathrm{deg}^2$, and validate the analysis using a withheld fiducial cosmology, analytical power-spectrum forecasts, and Gaussian random-field null tests. As an initial step, we neglect baryonic effects and intrinsic alignments and approximate galaxy sources as discrete redshift planes. Using all source redshifts at $z_s=\{0.5, 1, 1.5, 2, 2.5, 1100\}$, combining all five non-Gaussian statistics reduces uncertainties on $w_0$ and $w_a$ by $24.3\%$ and $28.0\%$, and on $\Omega_m$ and $\sigma_8$ by $41.9\%$ and $45.8\%$, relative to the power-spectrum-only baseline. The resulting $w_0$ and $w_a$ uncertainties are $34.7\%$ and $48.7\%$ smaller than current DESI+DES constraints. If the DESI+DES best-fit values remain unchanged, this precision would increase the significance of the departure from $\Lambda$CDM from $3.0\sigma$ to $5.2\sigma$, compared with $3.8\sigma$ from the power spectrum alone, assuming a Gaussian posterior and unchanged $w_0$--$w_a$ correlation. Minkowski functionals and moments provide comparable constraining power, while combining them with the other summaries gives the strongest constraints. Broad galaxy-lensing redshift coverage is particularly important for dynamical dark energy, while CMB lensing provides complementary information.
#### PBR sensitivity to boosted dark matter explanation for the KM3-230213A event
 - **Authors:** M. H. Reno, T. Venters, M. Abrate, J. Adams, J. Alfaro, D. Allard, P. Alldredge, R. Aloisio, R. Ammendola, A. Anastasio, L. Anchordoqui, D. Badoni, J. Baláž, B. Baret, M. Battisti, R. Bellotti, M. Bertaina, M. Betts, S. Blin, M. Boezio, P. Bořil, I. Buckland, J. Burton Heibges, F. Cafagna, R. Caruso, M. Casolino, K. Černý, B. Chamanbahar, N. Cordrey, A. Creusot, A. Cummings, C. De Santis, P. Degarate, N. DeWitt Pierrat, A. Di Giovanni, A. Di Salvo, B. J. DiLella, J. Eser, S. Ferrarese, G. Filippatos, J. Ford, N. Gagalis, P. Gálvez Molina, S. Garbolino, D. Garg, R. Gargiulo, B. Gockel, A. Grelle, C. Guépin, A. Haungs, T. Heibges, J. Hinkel, A. K. Ikehara, J. Krizmanic, L. Kupari, E. H. Lenzing, F. Liberatori, S. Mackovjak, D. Mandát, M. Manfrin, A. Marcelli, L. Marcelli, G. Masciantonio, V. Masone, E. Mayotte, A. Meli, E. Mentzell, M. Mese, S. Meyer, M. Mignone, M. Miller, M. Mongelli, J. Moses, E. Msihid, R. Munini, M. Murdock, A. Novikov, A. V. Olinto, Y. Onel, G. Osteria, B. Panico, E. Parizot, G. Passeggio, T. Paul, M. Pech, K. Peñaló Castillo, F. Perfetto, C. Petta, P. Picozza, L. Piotrowski, Z. Plebaniak, H. Qureshi, E. Reali, F. Reynaud, E. Ricci, M. Ricci, A. Rivetti, A. Roy, F. Sarazin, V. Scherini
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2610.29942

 - **Pdf link:** https://arxiv.org/pdf/2610.29942

 - **Abstract**
 POEMMA-Balloon with Radio (PBR) is a hybrid fluorescence and optical Cherenkov telescope that is a pathfinder instrument for a future Probe Of Extreme Multi-Messenger Astrophysics (POEMMA), together with a radio instrument, to be flown on a super pressure balloon in Spring 2028. One of its science objectives is follow up of astrophysical event alerts via signals of tau decays in the atmosphere, sourced by Earth-skimming tau neutrinos. The recent report of the KM3NeT Collaboration's muon event with $ E_{\mu}=120^{+110}_{-60}$ PeV sparked searches for beyond the standard model (BSM) physics explanations. Using a specific, boosted dark matter scenario which together with the KM3NeT observation, sets a scale for the fluence of boosted dark matter in this energy range, we assess the capabilities of PBR to constrain or discover such a source for a boosted dark matter energy spectrum above $\sim 10^8$ GeV. PBR has discovery potential for dark matter energies above $10^9$ GeV, and depending on BSM input parameters, to dark matter energies as low as $1.5\times 10^8$ GeV. While the analysis is focused on one BSM example, the methodology is applicable to any BSM physics that affects tau production in the Earth.
#### Extended vs. thin screen approximation in astrophysical settings
 - **Authors:** Manuel Adlberger, Tobias Kramer
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2610.30093

 - **Pdf link:** https://arxiv.org/pdf/2610.30093

 - **Abstract**
 Context: In the context of radio wave propagation through plasma concentrations and for gravitational lensing, the thin screen approximation often provides a suitable approximation for scattering and deflections caused by three-dimensional spatial structures. For scattering of electromagnetic waves from an extended medium, stochastic theories provide analytical bounds on ensemble averaged quantities, such as the scintillation index. If neither the conditions for a stochastic treatment nor the thin screen approximation are fulfilled, fully numerical methods are required. Aims: For an extended structure, the applicability of the thin screen approximation needs to be verified by comparing it with the fully three-dimensional scattering solution. We discuss various exact solutions to simple lensing geometries and provide numerical results for the propagation in the branched-flow regime, which is also of relevance in astrophysical applications. Methods: We transfer several analytical results obtained in quantum mechanical scattering theory to astrophysical settings and complement them with different numerical methods to quantify the deviations of thin screen theories from an extended medium results. Results: We provide the analytical results for spherical waves scattered by a point source and show the emergence of branchef flow in the intermediate regime between thin screen physics and stochastic media results.


by olozhika (Xing Yuchen). 


2026-10-22
