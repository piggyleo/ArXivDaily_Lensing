# Showing new listings for Monday, 20 April 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['gravitational lensing', 'strong lensing', 'dark matter', 'machine learning', 'neural network', 'galaxy merge', 'galaxy evolution']


Excluded: ['black hole', 'ISM', 'WIMP', 'BH']


### Today: 6papers 
#### Probing the large-scale structure with 21cm-galaxy cross-bispectrum: Estimates from simulations and forecasts for upcoming cosmological surveys
 - **Authors:** Leon Noble, Suman Majumdar, Matteo Viel, Fabio Fontanot, Gabriella De Lucia, Abinash Kumar Shaw, Marta Spinelli, Mohd Kamran, Lizhi Xie, Michaela Hirschmann
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2604.15440

 - **Pdf link:** https://arxiv.org/pdf/2604.15440

 - **Abstract**
 The redshifted 21cm signal from the post-reionization epoch is highly non-Gaussian; thus, higher-order statistics, such as the bispectrum, are required to extract this non-Gaussian information. However, high-signal-to-noise ratio detection of the 21cm auto-bispectrum will be hindered by the presence of residual systematics. Cross-correlating the 21cm signal with galaxies offers a promising path to suppress this uncertainty from residual systematics and potentially increase the signal-to-noise ratio. We present a comprehensive analysis of the HI-galaxy cross-bispectrum using the predictions of theoretical galaxy evolution models defined on large cosmological volumes. Our analysis includes the cross-bispectrum for different triangle sizes and shapes, as well as for different combinations of the HI and galaxy fields. We forecast the detectability of the 21cm-galaxy cross-bispectrum at redshift $z\approx1$ with Euclid-like galaxy survey and SKA-Mid observations in both interferometric and single-dish modes of survey. We find that the 21cm-galaxy cross-bispectrum shows enhanced detectability compared to the 21cm auto-bispectrum for all unique triangles in the presence of instrumental noise for observations in interferometric mode. We forecast a 10$\sigma$ detection of cross-bispectrum for squeezed-limit triangles and a 100$\sigma$ detection for all shapes combined for scales $0.2~\text{Mpc}^{-1}\leq k_1 \leq 0.9~\text{Mpc}^{-1}$ with 100 hours of SKA-Mid observations per pointing. However, the detectability of the cross-bispectrum for large scales ($k_1 < 0.1~\text{Mpc}^{-1}$), which is accessible with the single-dish mode of survey, is limited by cosmic variance. Our analysis presents a first step towards an end-to-end analysis pipeline for the future observations of the 21cm-galaxy cross-bispectrum.
#### PISP: Projected-Space Inference of Stellar Parameters
 - **Authors:** Jun-Chao Liang, Yin-Bi Li, A-Li Luo, Shuo Li, Xiao-Xiao Ma, Hai-Ling Lu, Shu-Guo Ma, Ming-Hui Jia, Shuo Ye, Hao Zeng, Ke-Fei Wu, Zhi-Hua Zhong, Xiao Kong, Li-Li Wang, Hugh R. A. Jones
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2604.15855

 - **Pdf link:** https://arxiv.org/pdf/2604.15855

 - **Abstract**
 To improve the accuracy and efficiency of high-dimensional stellar parameter inference in large spectroscopic datasets, we propose a projection-assisted parameter-inference framework -- Projected-Space Inference of Stellar Parameters (PISP). PISP constructs an orthonormal basis and optimizes in the projected space, reducing the impact of parameter correlations on inference. The basis is constructed using either principal component analysis (PCA) or the active-subspace (AS) method and is combined with two inference strategies -- Non-L1, which optimizes the projection coefficients for a user-specified projected dimensionality, and L1, which introduces L1 regularization in the full projected space to adaptively select projection directions -- yielding four strategies: PCA-Non-L1, AS-Non-L1, PCA-L1, and AS-L1. For different computational scenarios, we implement two versions: PISP-CurveFit for fast single-spectrum inference and PISP-Adam for large-scale GPU-parallel inference. Using a fully connected neural network and a residual network as spectral emulators, we evaluate PISP on Kurucz synthetic spectra and on $722{,}896$ APOGEE DR$17$ observed spectra. Compared to the baseline strategy, PISP improves inference accuracy for multiple parameters across all emulator-optimizer combinations. In synthetic data, PCA-L1 performs best, reducing the standard deviation of differences ($\sigma(\Delta)$) by at least $0.01$ dex for $12$ of $20$ elemental abundances, with [N/H], [O/H], [Na/H], [Co/H], [P/H], [V/H], [Cu/H] showing $0.05$--$0.72$ dex reductions. In observed data, PCA-Non-L1 reduces $\sigma(\Delta)$ by $>30$ K for effective temperature and by at least $0.01$ dex for $9$ of $17$ elemental abundances, with [O/H], [Na/H], [V/H] showing $0.05$--$0.20$ dex reductions, while achieving a $\sim$$4\times$ efficiency gain, slightly outperforming PCA-L1.
#### Inferring Halo Mass and Scale Radius of Galaxy Clusters Using Convolutional Neural Networks and Uchuu-UniverseMachine Catalogs
 - **Authors:** Hirobumi Tominaga, Asuka Nakamura, Tomoaki Ishiyama, Mohamed H. Abdullah
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2604.15932

 - **Pdf link:** https://arxiv.org/pdf/2604.15932

 - **Abstract**
 We investigate the ability of machine learning to infer the virial mass ($M_{\rm vir}$) and the scale radius ($r_{\rm s}$) of galaxy clusters from their observables. Using the Uchuu--UniverseMachine galaxy catalog at $z=0.093$, we generate mock cluster observations that include interlopers, and we encode each cluster as an image representing the two-dimensional joint probability distribution of member galaxies' projected position and line-of-sight velocity. We train two architectures: a baseline convolutional neural network (CNNb) following a previous approach, and an extended model (CNNr) that appends richness as an additional scalar input. We further compare the performance of networks trained on the all cluster sample and on a dynamically relaxed subsample. Across the test ranges $10^{13.7}\leq M_{\rm vir}\leq10^{15.3}$ Msun/h and $10^{1.7}\leq r_{\rm s}\leq10^{2.7}$ kpc/h, all configurations yield nearly unbiased absolute median residuals (within 0.01 dex). For the halo mass, adding richness narrows the residual distribution, reducing the standard deviation from 0.133 to 0.122 dex for the all sample, and from 0.124 to 0.111 dex for the relaxed sample. For the scale radius, restricting the training to relaxed clusters improves the performance more than adding richness. The standard deviation decreases from 0.180 to 0.154 dex for CNNb and from 0.175 to 0.148 dex for CNNr, while the inclusion of richness yields only a modest improvement of 0.005 dex. These results demonstrate that machine learning is a powerful tool to infer the mass and internal mass distribution of clusters, providing a new window for cosmological inferences and understanding galaxy formation processes.
#### Machine learning isotope shifts in molecular energy levels
 - **Authors:** Marco G. Barnfield, Oleg L. Polyansky, Sergei N. Yurchenko, Jonathan Tennyson
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP); Instrumentation and Methods for Astrophysics (astro-ph.IM); Chemical Physics (physics.chem-ph); Computational Physics (physics.comp-ph)
 - **Arxiv link:** https://arxiv.org/abs/2604.16073

 - **Pdf link:** https://arxiv.org/pdf/2604.16073

 - **Abstract**
 Recent advances in the use of High-Resolution Cross-Correlation Spectroscopy (HRCCS) to detect molecular species in exoplanet atmospheres, presents a new challenge for the accuracy of reference spectroscopic line lists. While parent isotopologues of key atmospheric tracers are often well-characterized, minor isotopologues, crucial for diagnosing planetary formation histories and evolution, suffer from a scarcity of experimental data, often leading to reliance on less accurate theoretical predictions. In this work, a comprehensive machine learning framework is designed to mitigate these inaccuracies by modelling the residual errors of the isotopologue extrapolation (IE) method used within the ExoMol project. A fully connected neural network architecture for carbon dioxide (CO$_2$) is shown to predict energy corrections with high fidelity, reducing the mean absolute error (MAE) relative to the original IE approach for more than 87\% of the levels when benchmarked against empirical (\Marvel) energies. Furthermore, development of a novel hybrid, molecule-aware transfer learning architecture is presented that successfully propagates correction patterns from the data-rich CO$_2$ system to the data-poor carbon monoxide (CO) system. This transfer learning approach yields MAE improvements in over 93\% of CO samples, demonstrating that physical correction factors related to isotopic substitution can be generalized across chemically related molecular systems. Updated and improved line lists are presented for 11 CO$_2$ isotopologues and energy levels for excited states of CO isotopologues are predicted. The methodology establishes a scalable, data-driven paradigm for refining molecular line lists, helping to bridge the gap between theoretical calculations and experimental precision.
#### Extending Galactic foreground emission with neural networks
 - **Authors:** Giuseppe Puglisi, Avinash Anand, Marina Migliaccio
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2604.16167

 - **Pdf link:** https://arxiv.org/pdf/2604.16167

 - **Abstract**
 We introduce an innovative approach employing Cycle Generative Adversarial Networks (Cycle-GANs) to accurately simulate Carbon Monoxide (CO) emissions by learning features identified in thermal dust emission maps from the Planck satellite alongside HI data from HI4PI survey. Our training dataset is complemented by the targets represented by the two rotational transition lines of CO (J:1-0, J:2-1) provided by the Planck satellite. We ensure the robustness of our dataset by focusing on regions with a signal-to-noise ratio (SNR) exceeding 8. The outcomes, assessed utilizing angular power spectra and Minkowski functionals, confirm that our algorithm proficiently achieves the set goals, indicating that the amplitudes of the generated emission accurately reproduce the angular correlations and share the statistical properties of the employed CO targets. We thus aim at improving the current models of CO emission specifically in the high-Galactic latitude areas that have been hardly observed by the most recent surveys, and, in doing so, to address and overcome the limitations affecting current models regions. This research lays the groundwork for creating transformative synthetic simulations, leveraging convolutional neural networks tied to data procured from latest observations.
#### Solar Cycle Prediction: Challenges, Progress, and Future Perspectives
 - **Authors:** Bidya Binay Karak
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Space Physics (physics.space-ph)
 - **Arxiv link:** https://arxiv.org/abs/2604.16183

 - **Pdf link:** https://arxiv.org/pdf/2604.16183

 - **Abstract**
 Reliable prediction of the solar cycle is a formidable challenge, yet it is increasingly vital in our technology-dependent society as solar activity drives space weather. Various methods, including precursors, nonlinear curve fitting and extrapolation, statistical and Machine Learning (ML) models, and dynamo and surface flux transport (SFT) models, were implemented to predict past cycles. Analysing about 100 predictions for Solar Cycle 24 and over 130 for Solar Cycle 25, we find that most methods largely failed to predict the peak correctly: Cycle 24 was statistically predicted to be a strong cycle, whereas Cycle 25 was predicted to be a weak cycle. By and large, predictions made only after the cycle began became closer to reality. ML-based models also produced discouraging results. The polar field and its proxy-based predictions are the most physically supported approach to prediction; however, applying them much earlier, before the solar minimum, may yield inaccurate results. Dynamo models are progressively improving both in understanding and in forecasting; however, they need to improve by accurately assimilating the observed polar field data and additional physics, such as meridional flow variations. Solar dynamo theory, complemented by the SFT model and observations, demonstrates that the prediction of a cycle before the time of its previous cycle's maximum is meaningless. The current solar cycle is declining, and the community is now preparing for the prediction of the next cycle. Thus, this review will guide future studies.


by olozhika (Xing Yuchen). 


2026-04-20
