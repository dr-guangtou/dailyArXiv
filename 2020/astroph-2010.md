# Astro-ph Notes

---- Song Huang ----

## 2020-October

----

### Oct 1

- [Can galaxy evolution mimic cosmic reionization?](https://arxiv.org/abs/2010.00023)
    - LAE在z>6的下降是否是再电离的影响。其中一个重要假设是星系本身在这阶段演化不大
    - 如果星系内的HI气体随红移增加，或者外流强度随红移下降，都可以模仿出这种效果；但可以通过Lya线的特征来区分
    - Using the CANDELSz7 survey measurements which indicate slightly broader lines at z∼6, we can rule out the scenario of a mere increase in the galactic column density towards higher z. We also show that a decrease in outflow velocity is not ruled out by existing data but leads to more prominent blue peaks at z>6.

- [Line confusion in spectroscopic surveys and its possible effects: Shifts in Baryon Acoustic Oscillations position](https://arxiv.org/abs/2010.00047)
    - Misidentifying Hβ emitter as [O III] emitter will cause a shift in the inferred radial position of the galaxy by approximately 90 Mpc/h. This length scale is similar to the Baryon Acoustic Oscillation (BAO) scale and could shift and broaden the BAO peak, possibly introduce errors in determining the BAO peak position.

- [Tightening weak lensing constraints on the ellipticity of galaxy-scale dark matter haloes](https://arxiv.org/abs/2010.00311)
    - **Relevant**
    - we combine data from five surveys (NGVSLenS, KiDS/KV450, CFHTLenS, CS82, and RCSLenS) in order to tighten observational constraints on galaxy-scale halo ellipticity for photometrically selected lens sample
    - fh , the average ratio between the aligned component of the halo ellipticity and the ellipticity of the light distribution, finding fh=0.303+0.080−0.079 for red lenses and fh=0.217+0.160−0.159 for blue lenses
    - Our measurements imply an average dark matter halo ellipticity for the studied red galaxy samples of ⟨|ϵh|⟩=0.174±0.046, where |ϵh|=(1−q)/(1+q) relates to the ratio q=b/a of the minor and major axes of the projected mass distribution.

- [Galaxy clustering in the Legacy Survey and its imprint on the CMB](https://arxiv.org/abs/2010.00466)
    - Cross-correlation of the tomographic galaxy maps with Planck maps of temperature and lensing convergence probe the growth of structure since z=0.8
    - Within ΛCDM, our low amplitude for the lensing cross-correlation requires a reduction either in fluctuation normalization or in matter density compared to the Planck results, so that Ω0.78mσ8=0.297±0.009.

- [A significant excess in major merger rate for AGNs with the highest Eddington ratios at z<0.2](https://arxiv.org/abs/2010.00022)
    - Using ESO VLT/FORS2 B-, V- and color images, we examine the morphologies of 17 galaxies hosting AGNs with Eddington ratios >0.3, and 25 mass- and redshift-matched control galaxies.
    - With a best estimate of 0.41 ± 0.12 for the AGN host galaxies and 0.08 ± 0.06 for the inactive galaxies our results imply that our AGN host galaxies have a significantly higher merger rate
    - We conclude that although major mergers are an essential mechanism to trigger local high Eddington ratio AGNs at z<0.2, the origin of >=50% of this specific AGN subpopulation still remains unclear.

- [A new high-precision strong lensing model of the galaxy cluster MACS J0416.1-2403](https://arxiv.org/abs/2010.00027)
    - MUSE观测：We spectroscopically identify 182 multiple images from 48 background sources at 0.9< z<6.2, and 171 cluster member galaxies.
    - 能更好的给出SF clumps的位置：By defining a new metric, which is sensitive to the gradients of the deflection field, we show that we can accurately reproduce the positions of these star-forming knots despite their vicinity to the model critical lines.
    - The high signal-to-noise spectra of the MDLF enables the measurement of the internal velocity dispersion of 64 cluster galaxies, down to m(F160W)=22. This allows us to independently estimate the contribution of the subhalo mass component of the lens model from the measured Faber-Jackson scaling relation

- [A novel black-hole mass scaling relation based on Coronal lines and supported by accretion predictions](https://arxiv.org/abs/2010.00075)
    - 用发射线比： [Si VI] 1.963 micron/Brγbroad 建立黑洞质量的标度关系; 和黑洞质量有反相关
    - we believe that a key parameter driving this anti-correlation is the effective temperature of the accretion disc, this being effectively sampled by the coronal line gas. 吸积盘温度与黑洞质量的-1/4次方成比例

- [The Faint End of the Quasar Luminosity Function at z∼5 from the Subaru Hyper Suprime-Cam Survey](https://arxiv.org/abs/2010.00481)
    - HSC-Wide中用Lyman-break挑选的z~5 QSO：we derived the quasar luminosity function at z∼5 covering a wide luminosity range of −28.76<M1450<−22.32 mag.
    - The inferred number density of low-luminosity quasars is lower, and the derived faint-end slope, −1.22+0.03−0.10, is flatter than those of previous studies at z∼5.

----

### Oct 4

- [Self-calibration of weak lensing systematic effects using combined two- and three-point statistics](https://arxiv.org/abs/2010.00614)
    - We investigate the prospects for using the weak lensing bispectrum alongside the power spectrum to control systematic uncertainties in a Euclid-like survey.
    - Varying all three systematics simultaneously, a joint power spectrum and bispectrum analysis reduces the area of credible regions for the cosmological parameters Ωm and σ8 by a factor of 90
    - We also demonstrate that including the bispectrum self-calibrates all three systematic effects to the stringent levels required by the forthcoming generation of weak lensing surveys, thereby reducing the need for external calibration data.

- [The CAMELS project: Cosmology and Astrophysics with MachinE Learning Simulations](https://arxiv.org/abs/2010.00619)
    - CAMELS is a suite of 4,233 cosmological simulations of (25 h−1Mpc)3 volume each: 2,184 state-of-the-art (magneto-)hydrodynamic simulations run with the AREPO and GIZMO codes 重子物理采用了TNG和SIMBA的模型
    - We show that the IllustrisTNG and SIMBA suites produce roughly similar distributions of galaxy properties over the full parameter space but significantly different halo baryon fractions and baryonic effects on the matter power spectrum.
    - 对探索ML在宇宙学里的应用很有帮助

- [Pix2Prof: fast extraction of sequential information from galaxy imagery via deep learning](https://arxiv.org/abs/2010.00622)
    - **Relevant, Useful**
    - "Pix2Prof", a deep learning model that eliminates manual steps in the measurement of galaxy surface brightness (SB) profiles.
    - 把从星系图像中获取profile的过程与给图片加caption等同起来，在SDSS图像上测试，效率很高

- [Wide-field ultra-narrow-bandpass imaging with the Dragonfly Telephoto Array](https://arxiv.org/abs/2010.00686)
    - Dragonfly Filter-Tilter, a device which places ultra-narrow bandpass interference filters (Δλ≈1 nm) in front of each of the lenses that make up the array.
    - The filters are at the entrance pupil of the optical system, rather than in a converging beam, so their performance is not degraded by a converging light cone.
    - By tilting the filters, the central wavelength of the transmission curve can be tuned over a range of 7 nm, corresponding to a physical distance range of about 20 Mpc of extragalactic targets.

- [The Lyman Continuum Escape Survey: Connecting Time-Dependent [OIII] and [OII] Line Emission with Lyman Continuum Escape Fraction in Simulations of Galaxy Formation](https://arxiv.org/abs/2010.00592)
    - 模拟研究：we find that the largest fesc values occur at elevated O32∼3−10 and that the combination of high fesc and low O32 is extremely rare. 但是O32和fesc之间并不一定有因果联系,large O32 does not necessarily imply efficient Lyman continuum escape.
    - Large O32 values fluctuate on short (∼1 Myr) timescales during the Wolf-Rayet-powered phase after the formation of star clusters, while channels of low absorption are established over tens of megayears by collections of supernovae.

- [Space Telescope and Optical Reverberation Mapping Project. XII. Broad-Line Region Modeling of NGC 5548](https://arxiv.org/abs/2010.00594)
    - We find an extended disk-like Hβ BLR with a mixture of near-circular and outflowing gas trajectories, while the C IV and Lyα BLRs are much less extended and resemble shell-like structures.
    - 三条线给出的SMBH质量是一致的；且V  band is a suitable proxy for the ionizing continuum when exploring the BLR structure and kinematics.

- [HOLISMOKES -- IV. Efficient Mass Modeling of Strong Lenses through Deep Learning](https://arxiv.org/abs/2010.00602)
    - We train a CNN on images of galaxy-scale lenses to predict the parameters of the SIE mass model (x,y,ex,ey, and θE).
    - Our CNN is able to predict the SIE parameters in fractions of a second on a single CPU and with the output we can predict the image positions and time delays in an automated way, such that we are able to process efficiently the huge amount of expected lens detections in the near future.

- [Biases and Cosmic Variance in Molecular Gas Abundance Measurements](https://arxiv.org/abs/2010.00609)
    - 目前的mm-波高红移CO巡天的视场都很小：fields ≲10 arcmin2 alter the recovered shape of the luminosity function, causing underestimates of the number of bright objects. Our models suggest that current surveys are sensitive enough to detect sources responsible for approximately half of the cosmic molecular gas density at high redshift.
    - As a result, the field size needed to detect redshift evolution in the molecular gas at high confidence may be more than an order of magnitude larger than what current surveys

- [Tracing Dark Matter Halos with Satellite Kinematics and Central Stellar Velocity Dispersion of Galaxies](https://arxiv.org/abs/2010.00693)
    - **Relevant**
    - SDSS中挑选的isolated和satellite星系，分成red和blue，看速度弥散度的标度关系：The central stellar velocity dispersions of the primary galaxies are proportional to the luminosities and stellar masses of the same galaxies. Stacking the sample based on the central velocity dispersion of the primary galaxies, we derive velocity dispersions of their satellite galaxies, which trace dark matter halo mass of the primary galaxies.
    - 星系周围的卫星星系的运动学与中心星系的速度弥散度关系很好: his tight relation suggests that the central stellar velocity dispersion of galaxies is indeed an efficient and robust tracer for dark matter halo mass.

- [RAiSERed: radio continuum redshifts for lobed AGNs](https://arxiv.org/abs/2010.00790)
    - 未来射电巡天发现的大部分射电星系都没有红移，本文提出一种只需要射电数据测红移的方法：our algorithm uses the lobe flux density, angular size and width, and spectral shape to derive probability density functions for the most likely source redshift based on the Radio AGN in Semi-analytic Environments (RAiSE) dynamical model.
    - We find that upper bounds on the angular size, as expected for unresolved sources, are sufficient to yield accurate redshift measurements at z > 2.

- [Deep Learning for Line Intensity Mapping Observations: Information Extraction from Noisy Maps](https://arxiv.org/abs/2010.00809)
    - 以SPHEREx为目标进行的模型训练：We develop conditional generative adversarial networks (cGANs) that extract designated signals and information from noisy maps.
    - The overall reconstruction performance depends on the pixel size and on the survey volume assumed for the training data.

- [Spectral energy distributions of dust and PAHs based on the evolution of grain size distribution in galaxies](https://arxiv.org/abs/2010.00922)
    - Based on a one-zone evolution model of grain size distribution in a galaxy, we calculate the evolution of infrared spectral energy distribution (SED), considering silicate, carbonaceous dust, and polycyclic aromatic hydrocarbons (PAHs).
    - 模型的主要参数是星际辐射场强度，恒星形成时标，以及ISM中致密气体的比例
    - 星系演化早期的尘埃颗粒尺寸较大，SED中的MIR成分较弱；At an intermediate stage (t∼1 Gyr for τSF=5 Gyr), the MIR emission grows rapidly because the abundance of small grains increases drastically by the accretion of gas-phase metals.
    - We find that small ηdense (i.e. the ISM dominated by the diffuse phase) is favoured to reproduce the 8 μm intensity dominated by PAHs both for the nearby and the z∼2 samples.

- [Mass-Velocity Dispersion Relation in HIFLUGCS Galaxy Clusters](https://arxiv.org/abs/2010.00992)
    - **Relevant**
    - HIghest X-ray FLUx Galaxy Cluster Sample (HIFLUGCS): measure the spatially resolved, line-of-sight velocity dispersion profiles of these clusters, which we find to be mostly flat at large radii, reminiscent of the rotation curves of galaxies.
    - Discover a tight empirical relation between the baryonic mass Mbar and the flat velocity dispersion σ of the member galaxies, i.e. MVDR
    - The residuals of the MVDR are uncorrelated with other cluster properties like temperature, cluster radius, baryonic mass surface density, and redshift.

----

### Oct 5

- [Dark Energy Survey Year 1 Results: Cosmological Constraints from Cluster Abundances, Weak Lensing, and Galaxy Correlations](https://arxiv.org/abs/2010.01138)
    - **Important**
    - 联合宇宙学限制： From a joint analysis of cluster abundances, three cluster cross-correlations, and auto correlations of galaxy density, we obtain Ωm=0.305+0.055−0.038 and σ8=0.783+0.064−0.054.
    - We thus combine cluster abundances and all two-point correlations from three cosmic tracer fields and find improved constraints on cosmological parameters as well as on the cluster observable--mass scaling relation.

- [On the "Lensing is Low" of BOSS Galaxies](https://arxiv.org/abs/2010.01143)
    - **Relevant**
    - Halo Occupation Distribution (HOD) modelling of the SMF, clustering, and lensing of BOSS LOWZ and CMASS samples at Planck cosmology. 对central和satellite星系用不同方式处理
    - The best-fitting HOD successfully describes all three observables without over-predicting the small-scale lensing signal. This indicates that the model places BOSS galaxies into dark matter halos of the correct halo masses, thereby eliminating the discrepancy in the one-halo regime where the signal-to-noise of lensing is the highest. 1Mpc/h以内的lensing is low可以被正确的模型解决
    - The observed lensing amplitude above 1 Mpc/h remains inconsistent with the prediction, which is however firmly anchored by the large-scale galaxy bias measured by clustering at Planck cosmology.

- [Determination of the Local Hubble Constant from Virgo Infall Using TRGB Distances](https://arxiv.org/abs/2010.01364)
    - A new determination of H0 using velocities and Tip of the Red Giant Branch (TRGB) distances to 33 galaxies located between the Local Group and the Virgo cluster. We obtain H0= 65.9 ± 3.5(stat) ± 2.4(sys) km s−1 Mpc−1

- [Statistical modelling of the cosmological dispersion measure](https://arxiv.org/abs/2010.01560)
    - 基于TNG300的：The free-electron power spectrum turns out to be consistent with the dark matter power spectrum at large scales, but it is strongly damped at small scales (≲1Mpc) owing to the stellar and active galactic nucleus feedback.
    - We have also obtained the probability distribution of source redshift for a given DM, which helps in identifying the host galaxies of FRBs from the measured DMs

- [IQ Collaboratory II: The Quiescent Fraction of Isolated, Low Mass Galaxies Across Simulations and Observations](https://arxiv.org/abs/2010.01132)
    - **Interesting**
    - 比较EAGLE, TNG, SIMBA: All three simulations show a decrease in the number of quiescent, isolated galaxies in the mass range M∗=109−10 M⊙, in broad agreement with observations.
    - 但是，None of the simulations reproduce the observed absence of quiescent field galaxies below 10^9-10 Msun, 都高估了

- [The clustering of submillimeter galaxies detected with ALMA](https://arxiv.org/abs/2010.01133)
    - **Interesting**
    - 利用ALESS巡天测量SMG的clustering：We constrain upper limits for the median mass of halos hosting SMGs at 1< z<3, finding Mhalo ≤2.4×10^12M⊙ for SMGs with flux densities S870≥4.0mJy 比之前单镜观测得到的成团性要低很多
    - 说明之前对SMG的halo质量也过高估计了：We conclude that only the brightest (S870≳5−6mJy) SMGs would trace massive structures at z∼2 and only SMGs with S870≳6mJy may be connected to massive local elliptical galaxies, quasars at intermediate redshifts and high-redshift star-forming galaxies, whereas fainter SMGs are unlikely linked to these populations.

- [Dust Attenuation Curves at z ∼ 0.8 from LEGA-C: Precise Constraints on the Slope and 2175Å Bump Strength](https://arxiv.org/abs/2010.01147)
    - We find that the attenuation curves in the rest-frame 3000−4500A range are typically almost twice as steep as the Milky Way, LMC, SMC, and Calzetti attenuation curves
    - The attenuation at 4500A and the slope strongly correlate with the galaxy inclination: face-on galaxies show less attenuation and steeper curves compared to edge-on galaxies 星系盘的指向对消光的影响最大
    - 在260/485个星系里看到了2175 bump，bump的强度似乎和星系性质关系不大；但bump确实多在低质量，正向星系里面出现

- [The dependence of the galaxy stellar-to-halo mass relation on galaxy morphology](https://arxiv.org/abs/2010.01186)
    - **Relevant**
    - SDSS:
        - At fixed halo mass in the mass range 10^11.7−10^12.9M⊙, the median stellar masses of SDSS disc galaxies are up to a factor of 1.4 higher than the median masses of their elliptical counterparts. 但这个结论与采用的恒星质量估计有关
        - For halo masses larger than 10^13M⊙, discs are less massive than ellipticals in same-mass haloes, regardless of whose stellar mass estimates we use.
    - EAGLE:
        - The EAGLE simulation predicts that discs are up to a factor of 1.5 more massive than elliptical galaxies residing in same-mass haloes less massive than 10^13M⊙ 这些质量不大，host盘星系的halo比同样质量host Elliptical的halo的assembly time要早
        - This suggests that the discs are more massive because they had more time for gas accretion and star formation.

- [Dust and gas in the central region of NGC 1316 (Fornax A) -- Its origin and nature](https://arxiv.org/abs/2010.01606)
    - HST color map; MUSE NaD absorption and velocity measurements: The velocity field of the ionised gas (and thus of the dust) is characterised by small-scale turbulent movements that indicate short lifetimes. At the very centre, a bipolar velocity field of the ionised gas is observed, which we interpret as an outflow
    - Our findings are strongly suggestive of a dusty outflow. Nuclear outflows may be important dust-producing machines in galaxies.

- [ALMaQUEST -- IV. The ALMA-MaNGA QUEnching and STar formation (ALMaQUEST) Survey](https://arxiv.org/abs/2010.01751)
    - ALMA观测46个sSFR分布很宽的MaNGA星系：the sSFR depends on both the star formation efficiency (SFE) and the molecular gas fraction (fH2), although the correlation with the latter is slightly weaker.
    - On kpc scales, the variations in both SFE and fH2 within individual galaxies can be as large as 1-2 dex thereby demonstrating that the availability of spatially-resolved observations is essential to understand the details of both star formation and quenching processes.

- [A Virgo Environmental Survey Tracing Ionised Gas Emission. VESTIGE VIII. Bridging the cluster-ICM-galaxy evolution at small scales](https://arxiv.org/abs/2010.02202)
    - VESTIGE Hα, Herschel SPIRE far-infrared, and VIVA HI data: We measure FIR emission from tails of stripped dust following the ionised and atomic gas components in galaxies undergoing ram pressure stripping
    - Along the stripped component, the dust distribution closely follows the HI and Hα emitting gas, all extending beyond the optical disc. 这些区域的Dust-to-gas mass ratios (DGRs)比星系盘上要低很多
    - We also find a negative trend in the DGR as a function of the metallicity that can be explained in terms of a dust component more centrally concentrated in more metal-rich systems.
    - Our results support an outside-in stripping scenario of the galaxy interstellar medium.

----

### Oct 6

- [Listening to the BOSS: the galaxy power spectrum take on spatial curvature and cosmic concordance](https://arxiv.org/abs/2010.02230)
    - Planck似乎限制Omega_K < 0; 但BAO支持Omega_K = 0;
    - Using measurements of the full-shape (FS) galaxy power spectrum, P(k), from the Baryon Oscillation Spectroscopic Survey DR12 CMASS sample. By combining Planck data with FS measurements, we break the geometrical degeneracy and find ΩK=0.0023±0.0028.
    - However, as with BAO, the overall increase in the best-fit χ2 suggests a similar level of tension between Planck and P(k) under the assumption of a curved Universe.

- [Fast analytical random pair counts calculation for realistic survey geometry](https://arxiv.org/abs/2010.02793)
    - Because pair counting scales as O(N2), where N is the number of points, the computational time to measure random pair counts cn be very expensive for large surveys.
    - We present an alternative approach for estimating those counts that does not rely on the use of a random catalogue. We derive an analytical expression for the anisotropic random-random pair counts that accounts for the galaxy radial distance distribution, survey geometry, and possible galaxy weights.

- [Overdensities of Submillimetre-Bright Sources around Candidate Protocluster Cores Selected from the South Pole Telescope Survey](https://arxiv.org/abs/2010.02909)
    - We find a total of 98 sources above a threshold of 3.7 sigma in the observed area of 1300 square arcminutes, where the bright central cores resolve into multiple components.
    - The large overdensities of bright submm sources surrounding these fields suggest that they could be candidate protoclusters undergoing massive star-formation events.

- [How the Population III Initial Mass Function Governs the Properties of the First Galaxies](https://arxiv.org/abs/2010.02212)
    - ENZO模拟：We find that a top-heavy Pop III IMF results in earlier star formation but dimmer galaxies than a more conventional Salpeter-type IMF because explosions of massive Pop III stars produce more turbulence that suppresses high-mass second-generation star formation

- [Dark-matter-deficient dwarf galaxies form via tidal stripping of dark matter in interactions with massive companions](https://arxiv.org/abs/2010.02219)
    - NewHorizon模拟：sustained stripping of dark matter, in tidal interactions between a massive galaxy and a dwarf satellite, naturally produces dwarfs that are dark-matter deficient, even though their initial dark-matter fractions are normal.
    - The process of dark matter stripping is responsible for the large scatter in the stellar-to-halo mass relation in the dwarf regime. The degree of stripping is driven by the closeness of the orbit of the dwarf around its massive companion

- [Galaxies with kinematically distinct cores in Illustris](https://arxiv.org/abs/2010.02222)
    - Illustris模拟里面KDC星系的分析：KDCs can be long-lived features, with their formation epochs roughly uniformly distributed in look-back times 0-11.4 Gyr, and they can survive even major or multiple subsequent mergers.
    - 没有单一的形成渠道，并合占60%，大质量星系中主要来自major merger
    - The mean mass-weighted stellar age inside the KDC radius is either about the same as the look-back time of the KDC formation or older.

- [Exemplary Merging Clusters: Weak-lensing and X-ray Analysis of the Double Radio Relic Merging Galaxy Clusters MACS 1752.0+4440 and ZWCL 1856.8+6616](https://arxiv.org/abs/2010.02226)
    - Our weak-lensing mass estimates show that each cluster is a major merger with approximately 1:1 mass ratio.
    - 尽管质量差别很大，但是WL和X-ray特征很相近
    - From the likeness of the X-ray morphologies and the remarkable symmetry of the radio relics, we propose that both systems underwent nearly head-on collisions.

- [Creating a galaxy lacking dark matter in a dark matter dominated universe](https://arxiv.org/abs/2010.02245)

- [An ALMA survey of the S2CLS UDS field: Optically invisible submillimetre galaxies](https://arxiv.org/abs/2010.02250)
    - **Interesting, Relevant**
    - We estimate that K>25.3 submillimetre galaxies represent 15+/-2 per cent of the total population brighter than S870=3.6mJy, with an expected surface density of ~450/deg^2 above S870>1mJy. 但只是Submm星系分布的tail；只是和K<25.3 mag的比，红移分布更高，尘埃消光更高; 消光高可能与其compact size有关
    - 可能成为高红移quiescent星系和LBG搜索的contamination
    - The concentrated, intense star-formation activity in these systems is likely to be associated with the formation of spheroids in compact galaxies at high redshifts, but as a result of their high obscuration these are completely missed in UV, optical and even near-infrared surveys.

- [Is there enough star formation in simulated protoclusters?](https://arxiv.org/abs/2010.02259)
    - **Relevant**
    - 现代模拟和SAM中的proto-cluster中没有足够的SF，比观测低了一个量级
    - 认为和模拟分辨率有关：We show that a large part of the discrepancy can be attributed to a dependence of SFR on the numerical resolution of the simulations, with a roughly factor of 3 drop in SFR when the spatial resolution decreases by a factor of 4.
    - 可以用proto-cluster的模型校准来限制星系演化模型，确保z=0的大质量星系的模型是正确的

- [Probing the Warm-Hot Circumgalactic Medium with broad OVI and X-rays](https://arxiv.org/abs/2010.02312)
    - OVI吸收线中的窄线成分指示的是logT=5.5的较冷的成分，而宽OVI吸收指示的是占CGM大部分的warm-hot成分
    - About 800ks of XMM-Newton observations will detect the expected absorption lines of OVII and OVIII unequivocally. Future missions like XRISM, Arcus and Athena will revolutionize the CGM science.

- [Investigating the Effect of Galaxy Interactions on AGN Enhancement at 0.5<z<3.0](https://arxiv.org/abs/2010.02710)
    - COSMOS+CANDELS: While we see a slight increase in AGN fraction with decreasing projected separation, overall, we find no significant enhancement relative to the control sample at any separation.

- [Scaling relations and baryonic cycling in local star-forming galaxies: II. Gas content and star-formation efficiency](https://arxiv.org/abs/2010.02919)
    - A sample of 392 galaxies (dubbed MAGMA, Metallicity and Gas for Mass Assembly)
    - We find the metallicity (Z) dependence of alpha_CO to be shallower than previous estimates
    - Molecular gas mass MH2 is found to be strongly correlated with Mstar and star-formation rate (SFR), enabling predictions of MH2 good to within ∼0.2 dex.
    - If Mgas is considered to depend on MHI, together with Mstar and SFR, we obtain a relation that predicts Mgas to within ∼0.05 dex.
    - Dwarf galaxies tend to be overwhelmed by (HI) accretion, while for galaxies in the intermediate Mstar "gas-equilibrium" bin, star formation proceeds apace with gas availability. In the most massive "gas-poor, bimodality" galaxies, HI does not apparently participate in star formation, although it generally dominates in mass over H2

----

### Oct 7

- [Learning effective physical laws for generating cosmological hydrodynamics with Lagrangian Deep Learning](https://arxiv.org/abs/2010.02926)
    - 针对生成模拟方法在高维度空间的不足：we propose Lagrangian Deep Learning (LDL) for this purpose, applying it to learn outputs of cosmological hydrodynamical simulations -- The model uses layers of Lagrangian displacements of particles describing the observables to learn the effective physical laws.
    - The displacements are modeled as the gradient of an effective potential, which explicitly satisfies the translational and rotational invariance.
    - The computational cost of LDL is nearly four orders of magnitude lower than the full hydrodynamical simulations, yet it outperforms it at the same resolution.

- [A Self-Calibrating Halo-Based Group Finder: Application to SDSS](https://arxiv.org/abs/2010.02946)
    - **Useful, Important** https://www.galaxygroupfinder.net/catalogs
    - This algorithm introduces new freedom to assign halos to galaxies that is self-calibrated by comparing the catalog to complementary data. These include galaxy clustering data and measurements of the total satellite luminosity from deep imaging data.
    - The transition halo mass scale, where half of halos contain quiescent central galaxies, is at M_h~10^12.4 Msol/h, significantly higher than other constraints.
    - Quiescent central galaxies in low-mass halos are significantly more massive than star-forming centrals at the same halo mass, but this difference reverses above the transition halo mass.
    - We find that the scatter in logM* at fixed M_h is ~0.2 dex for massive halos, in agreement with previous estimates, but rises sharply at lower halo masses.

- [The eROSITA X-ray telescope on SRG](https://arxiv.org/abs/2010.03477)
    - **Important**
    - By the end of 2023, eight complete scans of the celestial sphere will have been performed, each lasting six months
    - eROSITA all-sky survey in the soft X-ray band (0.2--2.3,keV) will be about 25 times more sensitive than the ROSAT All-Sky Survey, while in the hard band (2.3--8,keV) it will provide the first ever true imaging survey of the sky.

- [The Lyman Alpha Spectral Database (LASD)](https://arxiv.org/abs/2010.02927)
    - **Useful** 适合学习peak detection算法和复杂光谱的测量; https://gist.github.com/sixtenbe/1178136
    - We have compiled a large sample of Lyα spectra, at both low and high redshift, and created a publicly available online database, at: http://lasd.lyman-alpha.com/
    - 不仅包括光谱，还有大量谱线和运动学测量

- [Stellar splashback: the edge of the intracluster light](https://arxiv.org/abs/2010.02937)
    - **Relevant, Important, Interesting**
    - C-EAGLE模拟：the stellar distribution (or intracluster light, ICL) also has a well-defined edge, which is directly related to the splashback radius of the halo.
    - We show that these caustics can also be seen in the projected density profiles, but care must be taken to account for the influence of substructures and other non-diffuse material, which can bias and/or weaken the signal of the steepest slope.
    - We show that the "stellar splashback" feature is located beyond current observational constraints on the ICL, but these large projected distances (>>1 Mpc) and low surface brightnesses (mu >> 32 mag/arcsec^2)

- [How well can we determine ages and chemical abundances from spectral fitting of integrated light spectra?](https://arxiv.org/abs/2010.02940)/
    - **Useful**
    - WAGGS + Schiavon et al. (2005) GGCLib
    - Starlight拟合GC：
        - (1) The inferred parameters change with the wavelength range used;
        - (2) The method in general retrieves good reddening estimates, specially when a wider wavelength range is fitted;
        - (3) The ideal spectral regions for determination of age, [Fe/H], and [alpha/Fe] are: 4170-5540A, 5280-7020A, and 4828-5364A, respectively;
        - (4) The retrieved age values for old metal-poor objects can be several Gyr younger than those resulting from isochrone fitting.

- [Morphological and Rotation Structures of Circumgalactic Mg II Gas in the EAGLE Simulation and the Dependence on Galaxy Properties](https://arxiv.org/abs/2010.02944)
    - MgII指示的是logT~4的冷CGM气体；低红移气体的CGM中的MgII冷气体中可能有很高的角动量
    - 用EAGLE模拟进行研究：Mg II gas has an axisymmetric instead of a spherical distribution, and the axis of symmetry aligns with that of the Mg II gas rotation. 在Quiescent星系周围旋转则不多见
    - 实际观测中用视向速度cut可能会包含virial radii以外的气体：While the corotating Mg II gas generally extends beyond 0.5rvir, the Mg II gas outside of the virial radius contaminates the corotation signal and makes observers less likely to conclude that gas at large impact parameters (e.g., ≳0.25rvir) is corotating.

- [The AGN-galaxy-halo connection: The distribution of AGN host halo masses to z=2.5](https://arxiv.org/abs/2010.02957)
    - 传统的用AGN clustering估算其halo质量的方法可能受到AGN fraction随恒星质量变化等选择效应影响，而且从clustering的推断方法可能产生bias
    - We use AGN specific accretion rate distribution functions determined as a function of stellar mass and redshift for star-forming and quiescent galaxies separately, combined with the latest galaxy-halo connection models, to determine the parent and sub-halo mass distribution function of AGN
    - 平均质量 2x10^12 Msun; 随AGN吸积率，光度，红移的变化不大
    - While the AGN satellite fraction rises with increasing parent halo mass, we find that the central galaxy is often not an AGN.
    - We further show that AGN clustering is most easily interpreted and understood in terms of the relative bias to galaxy samples, not from absolute bias measurements alone.

- [Mysterious Globular Cluster System of the Peculiar Massive Galaxy M85](https://arxiv.org/abs/2010.03041)
    - **Relevant**
    - 89 GCs at 8 kpc <R< 160 kpc using the MMT/Hectospec: 按颜色分成red, green, blue，都很年老，但金属丰度不同
    - Red GCs有很明显的旋转：We find that the inner GC system exhibits a strong overall rotation that is entirely due to a disk-like rotation of the RGC system. Blue GC基本无旋转，不同population的运动学差异很大，可能是最近并合的结果
    - The GGCs show kinematic properties clearly distinct among the GC subpopulations, having higher mean velocities than the BGCs and RGCs and being aligned along the major axis of M85.

- [Unravelling the enigmatic ISM conditions in Minkowski's Object](https://arxiv.org/abs/2010.03139)
    - NGC541的jet路径上的dwarf星系：Minkowski's Object primarily consists of a young stellar population ∼10 Myr old, confirming that the bulk of the object's stellar mass formed during a recent jet interaction.
    - 发射线基本可以用SF解释；气体金属丰度变化范围很大：Strong-line diagnostics reveal a significant variation in the gas-phase metallicity within the object, with log(O/H)+12 varying by ∼0.5 dex
    - We hypothesise that Minkowski's Object either (a) was formed as a result of jet-induced star formation in pre-existing gas clumps in the stellar bridge, or (b) is a gas-rich dwarf galaxy that is experiencing an elevation in its star formation rate due to a jet interaction 能形成类似UDG的星系吗？

----

### Oct 8

- [Comparing different mass estimators for a large subsample of the {\it Planck}-ESZ clusters](https://arxiv.org/abs/2010.03582)
    - **Relevant**
    - The mean ratio between our X-ray masses and the weak-lensing masses in the LC2-single catalog is 1-b=0.74±0.06. However, the mean mass ratios inferred from the WL masses of different projects vary by a large amount, with APEX-SZ showing a bias consistent with zero (1-b=1.02±0.12), LoCuSS and CCCP/MENeaCS showing a significant difference (1-b=0.76±0.09 and 1-b=0.77±0.10, respectively), and WtG pointing to the largest deviation (1-b=0.61±0.12)
    - 动力学质量估计和X-ray质量估计符合得更好

- [Exploring the hydrostatic mass bias in MUSIC clusters: application to the NIKA2 mock sample](https://arxiv.org/abs/2010.03634)
    - **Relevant**
    - We analyzed a set of 260 synthetic clusters from the MUSIC simulation project, at redshifts 0≤z≤0.82.
    - The biases are of the order of 20%. We find that using the temperature instead of the pressure leads to a smaller bias, although the two values are compatible within 1σ.
    - We also present a study of the correlation between the mass bias and the dynamical state of the clusters. A clear correlation is shown between the relaxation state of the clusters and the bias factor.

- [Peculiar Velocity Estimation from Kinetic SZ Effect using Deep Neural Networks](https://arxiv.org/abs/2010.03762)
    - We simplify the calculation of peculiar velocities of galaxy clusters using deep learning frameworks trained on numerical simulations to avoid the estimation of the optical depth.
    - The deep learning algorithm displays robustness in estimating peculiar velocities from kinetic SZ effect by an improvement in accuracy of about 17% compared to the analytical approach.

- [Why reducing the cosmic sound horizon can not fully resolve the Hubble tension](https://arxiv.org/abs/2010.04158)
    - 解决H0 tension：Many of them introduce new physics, such as early dark energy, modifications of the standard model neutrino sector, extra radiation, primordial magnetic fields or varying fundamental constants, with the aim of reducing the sound horizon at recombination r⋆.
    - We demonstrate here that any model which {\it only} reduces r⋆ can never fully resolve the Hubble tension while remaining consistent with other cosmological datasets. We show explicitly that models which operate at lower matter density Ωmh2 run into tension with the observations of baryon acoustic oscillations, while models operating at higher Ωmh2 develop tension with galaxy weak lensing data.

- [Simulating cosmic structure formation with the GADGET-4 code](https://arxiv.org/abs/2010.03567)
    - **Useful**
    - The new version offers improvements in force accuracy, in time-stepping, in adaptivity to a large dynamic range in timescales, in computational efficiency, and in parallel scalability through a special MPI/shared-memory parallelization and communication strategy, and a more-sophisticated domain decomposition algorithm.
    - Two different flavours of smoothed particle hydrodynamics, a classic entropy-conserving formulation and a pressure-based approach, are supported for dealing with gaseous flows.
    - The GADGET-4 code is publicly released to the community and contains infrastructure for on-the-fly group and substructure finding and tracking, as well as merger tree building, a simple model for radiative cooling and star formation, a high dynamic range power spectrum estimator, and an initial conditions generator based on second-order Lagrangian perturbation theory.

- [MMT Spectroscopy of Lyman-alpha at z≃7: Evidence for Accelerated Reionization Around Massive Galaxies](https://arxiv.org/abs/2010.03566)
    - To better understand why Lyα is anonymously strong in a subset of massive z≃7−9 galaxies, we have initiated an MMT/Binospec survey targeting a larger sample (N=22) of similarly luminous (≃1−6 L∗UV) z≃7 galaxies
    - We confidently (>7σ) detect Lyα in 78% (7/9) of galaxies with strong [OIII]+Hβ emission (EW>800 A˚) as opposed to only 8% (1/12) of galaxies with more moderate (EW=200−800 A˚) [OIII]+Hβ.
    - We argue that the higher Lyα EWs of the strong [OIII]+Hβ population likely reflect enhanced ionizing photon production efficiency owing to their large sSFRs
    - 大质量星系的Lya透过率演化较小，可能居住在较大的电离区域内

- [From haloes to galaxies -- II. The fundamental relations in star formation and quenching](https://arxiv.org/abs/2010.03579)
    - We show the integrated MH2-SFR, SFR-M∗ and MH2-M∗ relation can be simply transformed from the μ-sSFR, SFE-μ and SFE-sSFR relation; μ是分子气体与恒星质量比；这三个关系的scatter更小
    - We propose the sSFR-μ-SFE relation as the Fundamental Formation Relation (FFR), which governs the star formation and quenching process, and provides a simple framework to study galaxy evolution.

- [The QuaStar Survey: Detecting Hidden Low-Velocity Gas in the Milky Way's Circumgalactic Medium](https://arxiv.org/abs/2010.03610)
    - **Interesting**
    - The content of the Milky Way's circumgalactic medium (CGM) is poorly constrained at |vLSR| ≲ 150 km s−1
    - The QuaStar Survey applies a spectral differencing technique using paired quasar-star sightlines to measure the obscured content of the Milky Way's CGM for the first time.
    - We present measurements of the CIV doublet (λλ 1548 \r{A}, 1550 \r{A}), a rest-frame UV metal line transition detected in HST/COS spectra of 30 halo-star/quasar pairs evenly distributed across the sky at Galactic latitudes |b|>30∘
    - We argue that the difference in absorption between the quasar and stellar sightlines originates primarily in the Milky Way's extended CGM beyond ∼10 kpc.

- [HI Deficiencies and Asymmetries in HIPASS Galaxies](https://arxiv.org/abs/2010.03720)
    - Previous studies of galaxy HI deficiency using HIPASS were sensitive to galaxies that are extremely HI rich or poor. We use an updated binning statistic for measuring the global sky distribution of HI deficiency that is sensitive to the average deficiencies.
    - Galaxies residing in denser environments, such as Virgo, are on average more HI deficient than galaxies at lower densities.
    - Many other individual groups and clusters are not found to be on average significantly HI poor
    - We also investigate the correlation between HI asymmetry and deficiency, but find no variation in the mean asymmetry of galaxies that are HI rich, normal or poor.

- [Resolving the Disc-Halo Degeneracy II: NGC 6946](https://arxiv.org/abs/2010.03991)
    - This mismatch between the scale height and the velocity dispersion can lead to underestimates of the disc surface density and a misleading conclusion of the sub-maximality of galaxy discs.
    - We present the study of the stellar velocity dispersion of the disc galaxy NGC 6946 using integrated star light and individual planetary nebulae as dynamical tracers. We demonstrate the presence of two kinematically distinct populations of tracers which contribute to the total stellar velocity dispersion.
    - We find the disc of NGC 6946 to be closer to maximal with the baryonic component contributing most of the radial gravitational field in the inner parts of the galaxy (Vmax(bar) = 0.76(±0.14)Vmax).

- [More insights into bar quenching. Multi-wavelength analysis of four barred galaxies](https://arxiv.org/abs/2010.04005)
    - We found that for three galaxies, the region between the nuclear or central sub-kiloparsec region and the end of the bar (bar region) is devoid of neutral and molecular hydrogen.
    - While the detected neutral hydrogen is very negligible, we note that molecular hydrogen is present abundantly in the nuclear or central sub-kiloparsec regions of all four galaxies.
    - The study presented here supports a scenario in which gas redistribution as a result of the action of stellar bar clears the bar region of fuel for further star formation and eventually leads to star formation quenching in the bar region.

- [Sustained formation of progenitor globular clusters in a giant elliptical galaxy](https://arxiv.org/abs/2010.04046)
    - **Relevant**
    - We show that many thousands of compact and massive (~5×103−3× 106M⊙) star clusters have formed at an approximately steady rate over, at least, the past ~1Gyr around NGC 1275
    - Their number distribution exhibits a similar dependence with luminosity and mass as the GCs, whereas their spatial distribution resembles a filamentary network of multiphase gas associated with cooling of the intracluster gas.
    - The progenitor GCs have minimal masses well below the maximal masses of Galactic open star clusters, affirming a common formation mechanism for star clusters over all mass scales irrespective of their formative pathways.

----

### Oct 11

- [Mitigating the effects of undersampling in weak lensing shear estimation with metacalibration](https://arxiv.org/abs/2010.04164)
    - **CSST**
    - We investigate the accuracy of shear measured with metacalibration from fitting elliptical Gaussians to undersampled galaxy images. In this case, metacalibration introduces aliasing effects leading to an ensemble multiplicative shear bias about 0.01 for Euclid, and even larger for the Roman Space Telescope
    - 克服的方法: computing shapes from weighted moments with wider Gaussians as weight functions, thereby trading bias for a slight increase in variance of the measurements

- [Super-sample covariance of the thermal Sunyaev-Zel'dovich effect](https://arxiv.org/abs/2010.04174)
    - **Interesting**
    - The statistical errors in the tSZ power spectrum measurements are dominated by the presence of massive clusters in a survey volume that are easy to identify on individual cluster basis. tSZ功率谱中最大的统计误差来源：最大质量的星系团
    - The sample variance is dominated by the connected non-Gaussian (cNG) covariance arising mainly from Poisson number fluctuations of massive clusters in the survey volume. 移除这些能被单独探测到的大质量星系团能降低variance
    - The power spectrum measured from the remaining, diffuse tSZ effects can be used to obtain tight constraints on cosmological parameters as well as the hydrostatic mass bias parameter.

- [Elucidating Galaxy Assembly Bias in SDSS](https://arxiv.org/abs/2010.04176)
    - **Relevant, SSST**
    - SDSS加ELUCID模拟：we develop an extended HOD model that includes the assembly bias of central and satellite galaxies
    - We discover that in many cases the level of cosmic variance between the two simulations can produce biased constraints that lead to an erroneous detection of galaxy assembly bias if the non-constrained simulation is used.
    - Our fiducial ELUCID constraint, for galaxies above a stellar mass threshold M∗=10^10.2h−1M⊙, is Qcen=−0.06±0.09 and Qsat=0.08±0.12, indicating no evidence for a significant galaxy assembly bias in the local Universe probed by SDSS.

- [Accounting for object detection bias in weak gravitationallensing studies](https://arxiv.org/abs/2010.04178)
    - We study the impact of object detection for a Euclid-like survey and show that it leads to biases that exceed requirements for the next generation of cosmic shear surveys. In realistic scenarios, blending of galaxies is an important source of detection bias.
    - We find that MetaDetection is able to account for blending, leading to average multiplicative biases that meet requirements for Stage IV surveys, provided a sufficiently accurate model for the point spread function is available.

- [Evidence for galaxy assembly bias in BOSS CMASS redshift-space galaxy correlation function](https://arxiv.org/abs/2010.04182)
    - **Relevant**
    - Recent studies have found that halo concentration by itself cannot capture the full galaxy assembly bias effect and that the local environment of the halo can be an excellent indicator of galaxy assembly bias. 建立了一个HOD模型包含了这两个因素
    - 观测上基于BOSS CMASS：We find that the inclusion of both assembly bias terms is strongly favored by the data and the standard 5-parameter HOD is strongly rejected. 并且能解决Lensing is low问题
    - We also showcase a consistent 3-5sigma preference for a positive environment-based assembly bias that persists over variations in the fit.

- [From "universal" profiles to "universal" scaling laws in X-ray galaxy clusters](https://arxiv.org/abs/2010.04192)
    - **Relevant**
    - We use a semi-analytic model based on a "universal" pressure profile in hydrostatic equilibrium within a cold dark matter halo with a defined relation between mass and concentration to reconstruct the scaling laws between the X-ray properties of galaxy clusters.
    - We also quantify any deviation from the self-similar predictions in term of temperature dependence of few physical quantities like the gas mass fraction, the relation between spectroscopic temperature and its global value, and, if present, the hydrostatic mass bias.
    - By combining these results with the constraints on the observed YSZ−T relation, we show how we can quantify the level of gas clumping affecting the studied sample, estimate the clumping-free gas mass fraction, and suggest the average level of hydrostatic bias present.

- [Cross-Correlation of Planck CMB Lensing with DESI-Like LRGs](https://arxiv.org/abs/2010.04698)
    - We detect a cross-correlation between DESI-like luminous red galaxies (LRGs) selected from DECaLS imaging and CMB lensing maps reconstructed with the Planck satellite at a significance of S/N=27.2 over scales ℓmin=30, ℓmax=1000
    - 利用 LRG cumulative magnitude function at the faint limit进行放大效应改正
    - We fit the large-scale galaxy bias at the effective redshift of the cross-correlation zeff≈0.68 using two different bias evolution agnostic models: a HaloFit times linear bias model where the bias evolution is folded into the clustering-based estimation of the redshift kernel, and a Lagrangian perturbation theory model of the clustering evaluated at zeff

- [Did Sgr cause the vertical waves in the solar neighbourhood?](https://arxiv.org/abs/2010.04165)
    - We find that we are unable to reproduce the observed asymmetry in the vertical number counts and its concomitant breathing mode in velocity space for any plausible combination of Sgr and Milky-Way properties.

- [The critical dark matter halo mass for Population III star formation: dependence on Lyman-Werner radiation, baryon-dark matter streaming velocity, and redshift](https://arxiv.org/abs/2010.04169)
    - Pop III形成的临界Halo质量：能包含足够多致密分子气体的最小halo质量，The presence of Lyman-Werner (UV) radiation, which can dissociate molecular hydrogen, and the baryon-dark matter streaming velocity both delay the formation of Pop III stars by increasing Mcrit
    - 基于Enzo模拟给出Mcrit对LW流量和Baryon-DM streaming，以及红移的模型; 综合几种依赖的效应比较复杂

- [The Hα Dots Survey. II. A Second List of Faint Emission-Line Objects](https://arxiv.org/abs/2010.04252)
    - The second catalog of serendipitously discovered compact extragalactic emission-line sources - Hα Dots
    - The sample includes Hα-detected blue compact dwarf galaxies at low redshift, [\ion{O}{3}]-detected Seyfert 2 and Green Pea-like galaxies at intermediate redshifts, and QSOs detected via one of several UV emission lines, including Lyα.

- [Changing-look active galactic nuclei: close binaries of supermassive black holes in action](https://arxiv.org/abs/2010.04417)
    - We demonstrate the extreme case that close binaries of supermassive black holes (CB-SMBHs) with high eccentricities are able to trigger the CL transition through one orbit. 用双黑洞解释CL-AGN
    - Binary black holes build up their own mini-disks via peeling gas off inner edges of the circumbinary disk during the apastron phase after then they tidally interact with the disks during the periastron phase to efficiently exchange angular momentum (AM) within one orbital period.
    - For mini-disks with rotation retrograde to the orbit, the tidal torque rapidly squeezes the tidal parts of the mini-disks into much smaller radius, resulting in an elevated accretion rapidly and short flares before declining into type-2 AGNs. In case of prograde mini-disks, they gain AM from the binary and rotate outward, giving rise to a rapid turn-off from type-1 to -2.

- [The Impact of Disturbed Galaxy Clusters on the Kinematics of Active Galactic Nuclei](https://arxiv.org/abs/2010.04498)
    - 33个BAX clusters，进行member sub-structure分类：8 dynamically active (merging) and 25 dynamically relaxed (non-merging) states.
    - 用WHAN diagram挑选AGN：70 merging and 225 non-merging AGN sub-populations.
    - AGN-hosting cluster galaxies have recently coalesced onto a common potential7
    - Non-merging AGN-hosting sub-populations have, on average, already been accreted and predominantly lie within backsplash regions of the projected phase-space.

- [Evaluating Galaxy Dynamical Masses From Kinematics and Jeans Equilibrium in Simulations](https://arxiv.org/abs/2010.04629)
    - **Useful**
    - 基于VELA模拟：We find that Jeans or hydrostatic equilibrium is approximately valid for galaxies of stellar masses above M⋆∼10^9.5M⊙ out to 5 effective radii (Re).
    - 给出了用旋转速度和视向速度弥散度结合测动力学质量的方法，对Spheroid和Disc不太一样，需要不同的改正系数 alpha；在Spheroid里，alpha和Sersic index反相关；在盘星系里，alpha和半径正相关
    - The correction in α for the stars due to the gradient in σr(r) is roughly balanced by the effect of the aspherical potential, while the effect of anisotropy is negligible.

- [The AGN fuelling/feedback cycle in nearby radio galaxies III. 3D relative orientations of radio jets and CO discs and their interaction](https://arxiv.org/abs/2010.04685)
    - 11 low-excitation radio galaxies (LERGs)的研究：JVLA+ALMA，a full 3D analysis of the relative orientations of jet and disc rotation axes in six FR I LERGs.
    - This analysis shows (albeit with significant uncertainties) that the relative orientation angles span a wide range (≈30∘−60∘). There is no case where both axes are accurately aligned and there is a marginally significant tendency for jets to avoid the disc plane.
    - 在NGC 3100中看到了Jet和CO气体相互作用的证据

- [Spatially resolved CIII\]λ1909 emission in Haro 11](https://arxiv.org/abs/2010.04685)
    - CIII\]1909半禁线，是除了Lya之外最强的紫外发射线 It is thought that C III\] emission is strongest in galaxies with subsolar metallicity and low mass, however, spectral observations of numerous such galaxies at high and low redshift produce inconclusive or even contradictory results.
    - STIS对Haro11的观测：Cluster parameters like stellar mass, dust fraction and dust attenuation, and ionization parameter, obtained through spectral energy distribution fitting, show no correlation with the CIII\] equivalent width (EW), which may be due to a combination of the limitation of the models and the age-homogeneity of the cluster population
    - We find that the clusters with the highest EW(C III\]) can be reconciled only with Cloudy models with an extremely high C/O ratio of ≥ 1.4(C/O)⊙ for an ionizing population of single stars, binary stars, or a mixture of binary stars and active galactic nuclei.

----

### Oct 12

- [A Novel Estimator for the Equation of State of the IGM by Lyα Forest Tomography](https://arxiv.org/abs/2010.05606)
    - 根据QSO光谱观测估计ISM的状态方程： Our estimation is based on a full tomographic inversion of the line of sight.
    - We model the temperature-density relation with a power law and observe for the temperature at mean density T0=13000+1300−1200K and for the slope of the power-law (polytropic index) γ=1.44±0.09 for the power-law parameters
    - We invert the data with two different inversion algorithms, the iterative Gauss-Newton method and the regularized probability conservation approach, which depend on different priors and compare the inversion results in flux space and in density space.

- [The HectoMAP Redshift Survey: First Data Release](https://arxiv.org/abs/2010.05817)
    - **Useful**
    - 55 deg^2; r=21.3 mag; 只释放了一部分： 17,313 redshifts in a first data release covering 8.7 square degrees.
    - 8117 constitute a 79% complete red-selected subsample with r≤20.5 and an additional 4318 constitute a 68\% complete red-selected subsample with 20.5 < r <21.3.

- [The Number Densities and Stellar Populations of Massive Galaxies at 3 < z < 6: A Diverse, Rapidly Forming Population in the Early Universe](https://arxiv.org/abs/2010.04725)
    - **Relevant**
    - UltraVista中M>10^11 Msun的高红移星系：≈100  and ≈20 high-confidence candidates at 3<z<4 and 4<z<6
    - The 3< z <4 population is comprised of post-starburst, UV star-forming and dusty-star forming galaxies in roughly equal fractions, while UV-star-forming galaxies dominate at 4< z<6
    - 在SED拟合中考虑发射线很重要
    - z~4是大质量星系出现的关键时期，这些星系的形成可以追溯至z~7; 星系都很compact
    - ≈15−25% of the population showing evidence of suppressed star-formation rates

- [Galaxy evolution across environments as probed by the ages, stellar metallicities and [alpha/Fe] of central and satellite galaxies](https://arxiv.org/abs/2010.04733)
    - **Relevant**
    - 基于Yang catalog；color-M/L based stellar mass; Lick index-based stellar population
    - Below log(Mstar/Msun)=10.5 satellites are older and metal-richer than equally-massive central galaxies. 但alpha/Fe没有区别
    - We also find that the differences in the median age and metallicity of satellites and centrals at stellar mass below 10^{10.5}Msun are largely due to the higher fraction of passive galaxies among satellites and as a function of halo mass.
    - When accounting for the varying quiescent fraction, small residual excess in age, metallicity and [alpha/Fe] emerge for satellites dominated by old stellar populations and residing in halos more massive than 10^{14}Msun, compared to equally-massive central galaxies. This excess in age, metallicity and [alpha/Fe] pertain to ancient infallers, i.e. satellites that have accreted onto the current halo more than 5 Gyr ago.

- [SQuIGGLE Survey: Massive z∼0.6 Post-Starburst Galaxies Exhibit Flat Age Gradients](https://arxiv.org/abs/2010.04734)
    - **Relevant**
    - Gemini观测，质量大于10^11 Msun: Using HδA absorption as a proxy for stellar age, we constrain five of the galaxies to have young (∼600 Myr) light-weighted ages at all radii and find that the sample on average has flat age gradients.
    - Find that galaxies with flat HδA profiles are inconsistent with formation via a central secondary starburst. This implies that the mechanism responsible for shutting off this dominant episode of star formation must have done so uniformly throughout the galaxy.

- [Investigating The Growing Population of Massive Quiescent Galaxies at Cosmic Noon](https://arxiv.org/abs/2010.04741)
    - **Relevant**
    - 28,469 massive (M⋆≥10^11M⊙) galaxies at redshifts 1.5< z<3.0, drawn from a 17.5 deg2 area
    - 通过三种方法估计Quiescent fraction：
        - 在1.5 < z < 2.0: 三个方法结果一致；quiescent fraction随恒星质量增加
        - 在2.0 < z < 3.0: 不同方法结果出现差别；UVJ给出的最高，sSFR给出的最低
        - 在z~2: the universe has quenched ∼25% of M⋆=10^11M⊙ galaxies and ∼45% of M⋆=10^12M⊙ galaxies
    - 和模拟比较：The quiescent fraction from IllustrisTNG is higher than our empirical result by a factor of 2−5, while those from SIMBA and the three SAMs are lower by a factor of 1.5−10 at 1.5< z< 3.0.

- [The environmental dependence of X-ray AGN activity at z∼0.4](https://arxiv.org/abs/2010.04832)
    - 0.35< z<0.45的7个大质量星系团中的Chandra X-ray确认的AGN
    - Studying the subset of AGN with 0.5-8 keV luminosities >6.8×10^42 erg s−1, within r≤2r500
    - The cluster AGN space density scales with cluster mass as ∼M−2.0+0.8−0.9 基本能确认有环境依赖
    - The cluster AGN fraction is significantly suppressed relative to the field when considering the brightest galaxies with V<21.5.
    - No evidence for enhanced X-ray obscuration of cluster member AGN.

- [All the PAHs: an AKARI-Spitzer Cross Archival Spectroscopic Survey of Aromatic Emission in Galaxies](https://arxiv.org/abs/2010.05034)
    - AKARI-Spitzer Extragalactic Spectral Survey (ASESS): 113个SF星系的2.5-38 micron的PAH研究
    - 3.3 micron PAH:
        - We find LPAH3.3/LIR ∼ 0.1% and the 3.3 μm PAH feature contributes ∼1.5-3% to the total PAH power
        - 可以trace SFR；但是在高光度和低金属丰度时不可靠
        - 3.3 μm is susceptible to attenuation, leading to a factor of ∼ 3 differences in the inferred star formation rate at high obscuration
        - The smallest PAHs are better able to survive under intense radiation fields than presumed, or that PAH emission is shifted to shorter wavelengths in intense and high energy radiation environments.

- [YZiCS: On the Mass Segregation of Galaxies in Clusters](https://arxiv.org/abs/2010.05304)
    - **Relevant**
    - Using deep optical observations of 14 Abell clusters (KYDISC) and a set of hydrodynamic simulations (YZiCS), we find in some cases a hint of mass segregation inside the virial radius. 通过大质量星系比例可以看出；在模拟里更明显
    - Satellites that get accreted at earlier epochs or galaxies in more massive clusters go through more tidal stripping. These effects in combination result in a correlation between the host halo mass and the degree of stellar mass segregation.

- [On the origin of X-ray oxygen emission-lines in obscured AGN](https://arxiv.org/abs/2010.05412)
    - 基于XMM archive的：Catalog of High REsolution Spectra of Obscured Sources (CHRESOS)
    - We concentrate on the soft X-ray OVII(f) and OVIII Ly_alpha emission；看和AGN以及SF的关系
    - 和其他线，以及模型比较：[OIII]5007A, [OIV]25.89mic emission lines, and MIR-12mic, FIR-60mic, FIR-100mic, 2-10 keV and 14-195 keV continuum bands, we conclude that the AGN radiation field is mainly responsible of the soft X-ray oxygen excitation.

- [Global HI asymmetries in IllustrisTNG: a diversity of physical processes disturb the cold gas in galaxies](https://arxiv.org/abs/2010.05422)
    - 基于TNG100：more than 50% of the sample has at least a 10% difference in integrated flux between the high- and low-velocity half of the spectrum, thus the typical TNG100 galaxy has an HI profile that is not fully symmetric.
    - 卫星星系的HI比centrals的更不对称；this trend appears to be driven by the satellite population within the virial radius of haloes more massive than 10^13M⊙, typical of medium/large groups.
    - Ram pressure stripping很重要，但是有同时作用于中心和卫星星系物理机制导致了不对称

- [The host galaxy of OJ 287 revealed by optical and near-infrared imaging](https://arxiv.org/abs/2010.05487)
    - z=0.3; 有12年周期性爆发，被认为可能有双黑洞的BL Lac
    - 很深的GTC光学和NOT NIR观测：We find the broad-band photometry of the host to be consistent with an early type galaxy with M_R = -22.5 and M_K = -25.2
    - The central supermassive black hole is clearly overmassive for a host galaxy of that luminosity, but not unprecedented

- [The infrared-radio correlation of star-forming galaxies is strongly M⋆-dependent but nearly redshift-invariant since z∼4](https://arxiv.org/abs/2010.05510)
    - qTIR == L_TIR/L_1.4Ghz; infrared-radio correlation (IRRC)
    - We re-calibrate qTIR as a function of both stellar mass (M∗) and redshift, starting from an M∗-selected sample of >400,000 star-forming galaxies in the COSMOS field, identified via (NUV-r)/(r-J) colours, at redshifts 0.1< z<4.5.
    - We find that the IRRC evolves primarily with M∗, with more massive galaxies displaying systematically lower qTIR. 对红移也有依赖，但是较弱
    - Adding the UV dust-uncorrected contribution to the IR as a proxy for the total SFR, would further steepen the qTIR dependence on M∗.
    - The lower IR/radio ratio in more massive galaxies could be possibly linked to higher SFR surface density, which induces larger cosmic-ray scale heights. 不是因为大质量星系的SFR变弱

- [Does NGC 6397 contain an intermediate-mass black hole or a more diffuse inner sub-cluster?](https://arxiv.org/abs/2010.05532)
    - MUSE观测和建模：We consider different priors on velocity anisotropy and on the size of the central mass, and also separate stars into components of different mean mass to allow for mass segregation.
    - 作者认为可以排除IMBH：The velocity ellipsoid is very isotropic throughout the cluster, and we argue that this must have been acquired early on. The data prefer the existence of a dark component in this cluster center of 0.8 to 2 percent of the total mass of the cluster 而是一个diffuse dark cluster
    - We argue that stellar-mass black holes should dominate the mass of this diffuse dark component.

- [Individual optical variability of Active Galactic Nuclei from the MEXSAS2 sample](https://arxiv.org/abs/2010.05624)
    - Multi-Epoch XMM Serendipitous AGN Sample 2 (MEXSAS2)
    - 基于单独AGN的统计：We find a significant decrease of variability amplitude with increasing bolometric, optical and X-ray luminosity.
    - When comparing optical to X-ray variability properties, we find that X-ray variability amplitude is approximately the same for those AGNs with larger or smaller variability amplitude in the optical.

- [The Infrared Medium-deep Survey. VIII. Quasar Luminosity Function at z∼5](https://arxiv.org/abs/2010.05859)
    - UKIRT WFCam: Infrared Medium-deep Survey (IMS), a near-infrared imaging survey covering an area of 85 deg2
    - 统计z~5的较暗的QSO；这些QSO可能对再电离之后的电离背景比较重要
    - We find that the faint-end slope of the QLF is very flat：imply that quasars are responsible for only 10-20% (up to 50% even in the extreme case) of the photons required to completely ionize the IGM at z∼5, disfavoring the idea that quasars alone could have ionized the IGM at z∼5.

----

### Oct 13

- [The LSST DESC DC2 Simulated Sky Survey](https://arxiv.org/abs/2010.05926)
    - **Useful, Important, CSST**
    - This effort encompasses a full end-to-end approach: starting from a large N-body simulation, through setting up LSST-like observations including realistic cadences, through image simulations, and finally processing with Rubin's LSST Science Pipelines.
    - The simulated DC2 sky survey covers six optical bands in a wide-fast-deep (WFD) area of approximately 300 deg^2 as well as a deep drilling field (DDF) of approximately 1 deg^2.

- [Active learning with RESSPECT: Resource allocation for extragalactic astronomical transients](https://arxiv.org/abs/2010.05941)
    - **SSST**
    - The Recommendation System for Spectroscopic follow-up (RESSPECT) project aims to enable the construction of optimized training samples for the Rubin Observatory Legacy Survey of Space and Time (LSST)
    - Our experiment takes into account the evolution of training and pool samples, different costs per object, and two different sources of budget. 比random sampling效率要高

- [Star-Galaxy Separation via Gaussian Processes with Model Reduction](https://arxiv.org/abs/2010.06094)
    - **Useful**
    - We present a novel approach to the star-galaxy separation problem that uses GPs and reap their benefits while solving many of the issues traditionally affecting them for classification of high-dimensional celestial image data.
    - We greatly improve the accuracy of the classification over a basic application of GPs while improving the computational efficiency and scalability of the method.

- [Imprint of baryons and massive neutrinos on velocity statistics](https://arxiv.org/abs/2010.05911)
    - 在TNG, EAGLE, OWLS里看重子物理过程对moments of pairwise velocity的影响
    - 假设 “mean pairwise velocity of the gas component follows that of the dark matter” 在10-20Mpc的尺度上是有bias的
    - Large scale velocity bias is mainly driven by stellar rather than AGN feedback; 如果不考虑，会影响kSZ效应的宇宙学限制
    - we examine how the first and the second moment of the pairwise velocity are affected by both the baryonic and the neutrino free-streaming effects for both the matter and gas components. 能够区分出来

- [DES Y1 results: Splitting growth and geometry to test ΛCDM](https://arxiv.org/abs/2010.05924)
    - To constrain a cosmological model where a subset of parameters -- focusing on Ωm -- are split into versions associated with structure growth (e.g. Ωgrowm) and expansion history (e.g. Ωgeom).
    - 用DES Year 1 (Y1) galaxy clustering and weak lensing来检验Lambda-CDM：We find no significant disagreement with Ωgrowm=Ωgeom.

- [Two Candidate High-Redshift X-ray Jets Without Coincident Radio Jets](https://arxiv.org/abs/2010.06535)
    - 两个高红移的radio QSO的延展X-ray探测：The extended X-ray emission is located along the line connecting the core to a radio knot or hotspot, favoring the interpretation of X-ray jets.
    - In the scenario of inverse Compton scattering of the cosmic microwave background (CMB), X-ray jets without a coincident radio counterpart may be common, and should be readily detectable to redshifts even beyond 3.2 due to the (1+z)4 increase of the CMB energy density compensating for the (1+z)−4 cosmological diminution of surface brightness.

- [Weighing Milky Way Satellites with LISA](https://arxiv.org/abs/2010.05918)
    - 利用LISA探测的双白矮星产生的引力波信号：Numerous and widespread DWDs have the potential to probe shapes, masses and formation histories of the stellar populations in the Galactic neighbourhood
    - Using a fiducial binary population synthesis model we find that for large satellites the stellar masses can be recovered to within 1) a factor two if the star formation history is known and 2) an order of magnitude when marginalising over different star formation history models.

- [Dust evolution in zoom-in cosmological simulations of galaxy formation](https://arxiv.org/abs/2010.05919)
    - 盘星系形成模拟中的尘埃演化：We couple an improved version of our previous treatment of dust evolution, which adopts the two-size approximation to estimate the grain size distribution, with the MUPPI star formation and feedback sub-resolution model.
    - Metal depletion and dust cooling affect the evolution of the system, causing substantial variations in its stellar, gas and dust content.

- [LoCuSS: The splashback radius of massive galaxy clusters and its dependence on cluster merger history](https://arxiv.org/abs/2010.05920)
    - **Relevant**
    - 用cluster member的stacked luminosity density profile探测到了SP特征
    - 看SP特征与星系团形成历史的相关：the most significant dependence of the splashback feature location and scale according to the presence or absence of X-ray emitting galaxy groups in the cluster infall regions.
    - Cluster that do not show massive infalling groups present the splashback feature at a smaller clustercentric radius rsp/r200,m=1.158±0.071 than clusters that are actively accreting groups rsp/r200,m=1.291±0.062, suggesting a correlation between the properties of the cluster potential and its accretion rate and merger history.
    - Clusters that are classified as old and dynamically inactive present stronger signatures of the splashback feature, with respect to younger, more active clusters.

- [Associations of dwarf galaxies in a ΛCDM Universe](https://arxiv.org/abs/2010.05922)
    - 在SMDP中看只有dwarf的星系系统，by applying the semi-analytic model of galaxy formation SAG
    - We analyse three different samples defined by log10(Mmax[M⊙h−1])=8.5,9.0 and 9.5. On average, our systems have typical sizes of ∼0.2Mpch−1, velocity dispersion of ∼30kms−1 and estimated total mass of ∼10^11M⊙h−1
    - Such large typical sizes suggest that individual members of a given dwarf association reside in different dark matter haloes and are generally not substructures of any other halo. 不是一个结构
    - Λ CDM model can naturally reproduce the existence and properties of dwarf galaxies associations without much difficulty.

- [Constraining the formation of NGC1052-DF2 from its unusual globular cluster population](https://arxiv.org/abs/2010.05930)
    - We apply a theoretical model that predicts the initial cluster mass function as a function of the galactic environment to investigate the origin of DF2's peculiar GC system
    - We predict that the GCs formed in an environment with very high gas surface density, 和现在的diffuse形态对比强烈
    - we propose that the GCs plausibly formed during a major merger at z∼1.3. The merger remnant must have undergone significant expansion of its stellar (and perhaps also its dark matter) component to reach its low present surface brightness

- [Spectroscopic classification of a complete sample of astrometrically-selected quasar candidates using Gaia DR2](https://arxiv.org/abs/2010.05934)
    - **Relevant**
    - We have built a complete candidate sample including 104 Gaia-DR2 point sources brighter than G<20 mag within one degree of the north Galactic pole (NGP), all with proper motions consistent with zero within 2σ uncertainty.
    - 其中大概60%是真的QSO：The selection efficiency of the zero-proper-motion criterion at high Galactic latitudes is thus ≈60%.
    - We find that the surface density of quasars is 20 deg−2, the redshift distribution peaks at z∼1.5, and that only eight systems (13+5−3%) show significant dust reddening.
    - Finally, we discuss how the astrometric selection can be improved to an efficiency of ≈70% by including an additional cut requiring parallaxes of the candidates to be consistent with zero within 2σ.

- [The parsec-scale HI outflows in powerful radio galaxies](https://arxiv.org/abs/2010.05996)
    - 射电星系中的HI吸收可能反应了AGN反馈的外流，也可能是喷流和ISM的相互作用
    - VLBI+VLA+WSRT观测：we find evidence for a clumpy structure of both the outflowing and the quiescent gas, consistent with predictions from numerical simulations.
    - The outflows include at least a component of relatively compact clouds (10^4-10^5Msun) often observed already at a few tens of pc (in projection) from the core

- [The End of Galaxy Surveys](https://arxiv.org/abs/2010.06064)
    - **Interesting**
    - Using an exposure time calculator, we define nominal surveys for extracting the useful information for three science cases: dark energy cosmology, galaxy evolution, and supernovae.
    - For optimistic assumptions, a 280m telescope with a marginally resolved focal plane of 20 deg2 operating at L2 could potentially exhaust the cosmological information content of galaxies in a 10 year survey.
    - We present scaling relations that show how we can progress toward the goal of exhausting the information content encoded in the shapes, positions, and colors of galaxies.

- [A catalog of broad morphology of Pan-STARRS galaxies based on deep learning](https://arxiv.org/abs/2010.06073)
    - We describe the design and implementation of a data analysis process for automatic broad morphology annotation of galaxie
    - Our analysis shows that a CNN combined with several filters is an effective approach for annotating the galaxies and removing unclean images

- [Effects of spin on constraining the seeds and growth of ≳10^9M⊙ supermassive black holes in z>6.5 Quasars](https://arxiv.org/abs/2010.06128)
    - We use the observations of 14 Quasars at z>6.5 with mass estimates to constrain their seeds and early growth, by self-consistently considering the spin evolution and the possibility of super-Eddington accretion.
    - If the accretion is coherent with single (or a small number of) episode(s), leading to high spins for the majority of accretion time, then the SMBH growth is relatively slow; and if the accretion is chaotic with many episodes and in each episode the total accreted mass is much less than the SMBH mass, leading to moderate/low spins, then the growth is relatively fast.

- [Double-peaked Lyman-α emission at z=6.803: a reionisation-era galaxy self-ionising its local HII bubble](https://arxiv.org/abs/2010.06241)
    - 红蓝峰的速度差距：suggests an extremely high escape fraction of ionising photons >59(51)%(2σ).
    - 非常年轻的星族，50Myr，有显著的[OIII]+Hbeta线；自身的电离辐射就可以产生一个可以解释蓝峰的电离泡
    - 可能在高红移有一定代表性

----

### Oct 14

- [AI-assisted super-resolution cosmological simulations](https://arxiv.org/abs/2010.06608)
    - 借鉴机器学习技术：Neural networks have been developed to learn from high-resolution (HR) image data, and then make accurate super-resolution (SR) versions of different low-resolution (LR) images
    - We are able to enhance the simulation resolution by generating 512 times more particles and predicting their displacements from the initial positions.
    - Furthermore, the generation process is stochastic, enabling us to sample the small-scale modes conditioning on the large-scale environment.

- [Targeted Likelihood-Free Inference of Dark Matter Substructure in Strongly-Lensed Galaxies](https://arxiv.org/abs/2010.07032)
    - We present here a new analysis pipeline that tackles these diverse challenges by bringing together many recent machine learning developments in one coherent approach, including variational inference, Gaussian processes, differentiable probabilistic programming, and neural likelihood-to-evidence ratio estimation
    - 可以实现：(a) fast reconstruction of the source image and lens mass distribution, (b) variational estimation of uncertainties, (c) efficient optimization of source regularization and other hyperparameters, and (d) marginalization over stochastic model components like the distribution of substructure.

- [Globular clusters as tracers of the dark matter content of dwarfs in galaxy clusters](https://arxiv.org/abs/2010.06590)
    - Dwarf中的GC未必满足球对称和动力学平衡的假设
    - 在Illustris模拟中找到9个星系团，进行particle tagging研究：Our results indicate that mass estimates are, on average, quite accurate in systems with GC numbers NGC≥10 and where the uncertainty of individual GC line-of-sight velocities is smaller than the inferred velocity dispersion, σGC. 但如果GC数量<10，bias就会比较常见
    - 也找到了一下 NGC1052-DF2 analogs: These DF2 analogs correspond to relatively massive systems at their infall time which have retained only 3-17 GCs and have been stripped of more than 95% of their dark matter.

- [Tracing the evolution of dust-obscured activity using sub-millimetre galaxy populations from STUDIES and AS2UDS](https://arxiv.org/abs/2010.06605)
    - STUDIES 450-μm SMG样本和AS2UDS 850-micron挑选的SMG的比较
    - The fainter 450-μm sample has ∼14 times higher space density than the brighter 850-μm sample at z ≲2, and a comparable space density at z = 2-3, before rapidly declining, suggesting LIRGs are the main obscured population at z ∼ 1-2, while ULIRGs dominate at higher redshifts
    - Using far-infrared luminosity, dust masses and an optically-thick dust model, we suggest that higher-redshift sources have higher dust densities due to inferred dust continuum sizes which are roughly half of those for the lower-redshift population at a given dust mass, leading to higher dust attenuation.

- [HI 21-centimetre emission from an ensemble of galaxies at an average redshift of one](https://arxiv.org/abs/2010.06617)
    - uGMRT观测：z=0.74-1.45 DEEP2 feild的观测; 叠加了7,653 blue, star-forming galaxies
    - We report a measurement of the average HI mass of star-forming galaxies at a redshift z≈1, by stacking their individual HI 21 cm emission signals. We obtain an average HI mass similar to the average stellar mass of the sample.
    - We also estimate the average star-formation rate of the same galaxies from the 1.4 GHz radio continuum, and find that the HI mass can fuel the observed star-formation rates for only ≈1−2 billion years in the absence of fresh gas infall.
    - Gas accretion onto galaxies at z<1 may have been insufficient to sustain high star-formation rates in star-forming galaxies. This is likely to be the cause of the decline in the cosmic star-formation rate density at redshifts below 1.

- [A Fully General, Non-Perturbative Treatment of Impulsive Heating](https://arxiv.org/abs/2010.06632)
    - **Interesting**
    - Impulsive encounters between astrophysical objects are usually treated using the distant tide approximation (DTA) for which the impact parameter, b, is assumed to be significantly larger than the characteristic radii of the subject, rS, and the perturber, rP. The perturber potential is then expanded as a multipole series and truncated at the quadrupole term.
    - 但当b很小，和subject的尺度差不多时，这个方法会高估交汇引起的速度变化, impulse.
    - This paper presents a fully general, non-perturbative treatment of impulsive encounters which is valid for any impact parameter

- [A correlation between the dark content of elliptical galaxies and their ellipticity](https://arxiv.org/abs/2010.06692)
    - **Relevant**
    - 14年一篇文章的详细内容；关于椭圆星系椭率和暗物质晕质量的关系
    - Such a correlation is either spurious --in which case it signals an ubiquitous systematic bias in elliptical galaxy observations or their analysis-- or genuine --in which case it implies in particular that at equal luminosity, flattened medium-size elliptical galaxies are on average five times heavier than rounder ones, and that the non-baryonic matter content of medium-size round galaxies is small

- [Clustering of red and blue galaxies around high-redshift 3C radio sources as seen by the Hubble Space Telescope](https://arxiv.org/abs/2010.06752)
    - Galaxy surface density maps reveal the clustering of red and blue galaxies around 3C radio galaxies and quasars at 1< z<2.5.
    - At z<1.5, the overdensity is dominated by red galaxies, while blue galaxies are more frequent in the periphery. With a few exceptions, the fainter galaxies contributing to the overdensity are bluer than the brighter galaxies
    - This and the brightness and color segregation of candidate cluster member galaxies leads us to conclude that at 1 < z < 1.5 the 3C sources are not just becoming galaxy groups. Rather we suggest that the foundation of a galaxy cluster with luminous red galaxies has largely been set, and the formation of the red sequence is still going on from a reservoir of blue galaxies in the periphery.
    - At z>1.5, overdensities are less frequent and progressively composed of blue galaxies.

- [The X-SHOOTER/ALMA sample of Quasars in the Epoch of Reionization. I. NIR spectral modeling, iron enrichment and broad emission line properties](https://arxiv.org/abs/2010.06902)
    - 有ALMA CII观测的38 luminous (M1450=−29.0 to −24.4) quasars at 5.78< z<7.54
    - The measured FeII/MgII flux ratio suggests that the broad line regions of all quasars in the sample are already enriched in iron. 和CII线比，MgII线有蓝移的证据
    - While we find all other broad emission line properties not to be evolving with redshift, the median CIV-MgII blueshift is much larger than found in low-redshift, luminosity-matched quasars

----

### Oct 15

- [Mixture Models for Photometric Redshifts](https://arxiv.org/abs/2010.07319)
    - **Useful**
    - We aim at estimates of the full photo-z probability distributions, and their uncertainties. We perform a probabilistic photo-z determination using Mixture Density Networks (MDN).
    - 基于SDSS-WISE观测：We use Infinite Gaussian Mixture models to classify the objects in our data-set as stars, galaxies or quasars, and to determine the number of MDN components to achieve optimal performance.
    -  Infinite Gaussian Mixture Models:
        - The IGMM is the GMM case with an undefined number of components, which will be optimised by the model itself, depending on the photometric data-set used
        - The IGMM describes a mixture of Gaussian distributions on the data population with an infinite (countable) number of components, using a Dirichlet process
    - Mixture Density Network
        - MDNs are a form of ANNs, which are capable of arbitrarily accurate approximation to a function and its derivatives based on the Universal Approximation Theorem

- [Probing dark energy with tomographic weak-lensing aperture mass statistics](https://arxiv.org/abs/2010.07376)
    - We forecast and optimize the cosmological power of various weak-lensing aperture mass (Map) map statistics for future cosmic shear surveys, including peaks, voids, and the full distribution of pixels 主要优点是可以探测质量分布的non-Gaussian区域
    - We develop a new tomographic formalism which exploits the cross-information between redshift slices (cross-Map) in addition to the information from individual slices (auto-Map) probed in the standard approach.
    - This demonstrates that the complementary cosmological information explored by non-Gaussian Map map statistics not only offers the potential to improve the constraints on the recent σ8 - Ωm tension, but also constitutes an avenue to understand the accelerated expansion of our Universe.

- [Removing the giants and learning from the crowd: a new SZ power spectrum method and revised Compton y-map analysis](https://arxiv.org/abs/2010.07797)
    - We devise a new method for analysing the y-map by introducing the survey completeness function, conventionally only used in the CNC analysis, in the yy-PS modeling 做两个分析，一个是包含了单独探测到的clusters的，一个是排除的
    - We carefully propagate the effect of completeness cuts on the non-Gaussian error contributions in the yy-PS analysis, highlighting the benefits of masking massive clusters.
    - Our analysis of the Planck yy-PS for the unresolved component yields a mass bias of b=0.15±0.04, consistent with the standard value (b≈0.2), in comparison to b=0.4±0.05 for the total yy-PS.
    - We find indications for this drift being driven by the CIB-tSZ cross correlation, which dominantly originates from clusters in the resolved component of the y-map.

- [The Effect of Impact Parameter on Tidal Disruption Events](https://arxiv.org/abs/2010.07318)
    - TDE数值模拟，用的代码叫MANGA: 改变碰撞参数beta，看fallback rate和peak光度如何变化
    - We show that the spread of energy in the debris and peak luminosity time (tpeak) are both directly related to the impact parameter. In particular, we find a β1/2 scaling for the energy spread for β=2−10 and a frozen evolution for β≳10

- [Constraints on the [CII] luminosity of a proto-globular cluster at z~6 obtained with ALMA](https://arxiv.org/abs/2010.07302)
    - 被星系团放大的一个z=6.16的球状星团前身：identify a 4-sigma tentative detection of [CII] emission with intrinsic luminosity L_CII=(2.9 +/- 1.4) 10^6 L_sun, one of the lowest values ever detected at high redshift
    - Our weak detection indicates a deficiency of [CII] emission, possibly ascribed to various explanations, such as a low-density gas and/or a strong radiation field caused by intense stellar feedback, and a low metal content.

- [The Launching of Cold Clouds by Galaxy Outflows. IV. Cosmic-Ray-Driven Acceleration](https://arxiv.org/abs/2010.07308)
    - 2-D数值模拟：cosmic-ray (CR) driven, radiatively-cooled cold clouds embedded in hot material, as found in galactic outflows
    - Thus the CR ray pressure in the bottleneck region has sufficient time to accelerate the cold clouds efficiently. Furthermore, radiative cooling has relatively little impact on these interactions.

- [IllustrisTNG and S2COSMOS: possible conflicts in the evolution of neutral gas and dust](https://arxiv.org/abs/2010.07309)
    - 强行让模拟和观测在z=0符合，看尘埃的演化：We find a lack of evolution in the DMFs derived from the simulations, in conflict with the rapid evolution seen in empirically derived estimates of the low redshift DMF
    - 观测上尘埃质量和恒星质量的比例也有很强的演化，但是TNG中的演化很少；可能和TNG中中性气体成分的演化也不够有关

- [The Dragonfly Wide Field Survey. II. Accurate Total Luminosities and Colors of Nearby Massive Galaxies and Implications for the Galaxy Stellar Mass Function](https://arxiv.org/abs/2010.07310)
    - **Relevant, Useful**
    - We construct a sample of 1188 massive galaxies with logM∗/M⊙>10.75 based on the Galaxy Mass and Assembly (GAMA) survey and measure their total luminosities and g−r colors.
    - We find that galaxies are brighter in the r band by an average of ∼0.05 mag and bluer in g−r colors by ∼0.06 mag compared to the GAMA measurements. 对恒星质量估计的影响不同
    - The total luminosities are larger by 5% but the mass-to-light ratios are lower by ∼10%.

- [LYRA I: Simulating the multi-phase ISM of a dwarf galaxy with variable energy supernovae from individual stars](https://arxiv.org/abs/2010.07311)
    - 基于AREPO的模型：It forms individual stars sampled from the initial mass function (IMF), and tracks their lifetimes and death pathways individually. Single supernova (SN) blast waves with variable energy are followed within the hydrodynamic calculation to interact with the surrounding interstellar medium (ISM)
    - 模拟一个孤立的10^10 Msun的暗物质晕：We demonstrate that the majority of supernovae are Sedov-resolved at our fiducial gas mass resolution of 4M⊙. 能产生外流
    - Clustered SN play a major role in enhancing the effectiveness of feedback, because the majority of explosions occur in low density material.
    - Accounting for variable SN energy affects the metallicity distribution function by altering the efficiency of metal mixing. Additionally, it alters the outflow behaviour, reducing the mass loading by a factor of 2-3 with respect to fixed energy models, thus allowing the galaxy to retain a higher fraction of mass and metals.

- [Stellar Velocity Dispersion and Dynamical Mass of the Ultra-Diffuse Galaxy NGC 5846_UDG1 from the Keck Cosmic Web Imager](https://arxiv.org/abs/2010.07313)
    - **Relevant**
    - VEGAS中找到的一个有很多球状星团的UDG：KCWI给出GC速度弥散度分布：σGC  = 17 ± 2 km/s.
    - 较高的速度弥散度意味着比较高的DM贡献；We find no evidence that the galaxy is rotating and is thus likely pressure-supported.
    - A cored mass profile is favoured when compared to our dynamical mass. 暗物质晕质量在2x10^11 Msun, overly massive halo

- [A Complex Luminosity Function for the Anomalous Globular Clusters in NGC1052-DF2 and NGC1052-DF4](https://arxiv.org/abs/2010.07324)
    - **Relevant**
    - 新的Keck和HST观测：The new analysis shows that the peak of the combined GC luminosity function remains at MV≈−9 mag. In addition, we find a subpopulation of less luminous GCs at MV≈−7.5 mag, where the near-universal GCLF peak is located.
    - The updated total number of GCs in both galaxies is 37+11.08−6.54. The number of GCs do not scale with the halo mass in either DF2 or DF4, suggesting that NGC is not directly determined by the merging of halos.

- [An extremely metal-deficient globular cluster in the Andromeda Galaxy](https://arxiv.org/abs/2010.07395)
    - **Interesting**
    - We report a massive GC in the Andromeda Galaxy (M31) that is extremely depleted in heavy elements. Its iron abundance is about 800 times lower than that of the Sun, and about three times lower than in the most iron-poor GCs previously known. It is also strongly depleted in magnesium.

- [SUPER III. Broad Line Region properties of AGN at z∼2](https://arxiv.org/abs/2010.07443)
    - SINFONI巡天：a blind search for AGN-driven outflows on X-ray selected AGN at redshift z∼2 with high (∼2 kpc) spatial resolution
    - We estimate BH masses in the range Log(MBH/M⊙)=8.4-10.8 and Eddington ratios λEdd =0.04-1.3. We confirm that the CIV line width does not correlate with the Balmer lines and the peak of the line profile is blue-shifted with respect to the [OIII]-based systemic redshift. CIV更多指示的是BLR中的外流
    - We confirm the strong dependence of the BLR wind velocity with the UV-to-Xray continuum slope, LBol and λEdd. 质量外流率在0.005-3 Msun/yr
    - We found an anti-correlation between the equivalent width of the [OIII] line with respect to the CIV shift, and a positive correlation with [OIII] outflow velocity.

- [On the broad line region configuration of the supermassive binary black hole candidate PG1302-102 in the relativistic Doppler boosting scenario](https://arxiv.org/abs/2010.07512)
    - We investigate several broad emission lines of PG1302-102 using archived UV spectra obtained by IUE, GALEX, and Hubble, to reveal the broad line emission region (BLR) properties of this BBH system under the Doppler boosting scenario.
    - We find that the broad lines Lyα, NV, CIV, and CIII] all show Gaussian-like profiles, and none of these lines exhibits obvious periodical variation.
    - If the Doppler boosting interpretation is correct, then the BLR is misaligned with the BBH orbital plane by an angle ∼51∘, which suggests that the Doppler boosted continuum variation has little effect on the broad line emission and thus does not lead to periodical line variation.

- [Broad-band selection, spectroscopic identification, and physical properties of a population of extreme emission line galaxies at 3<z<3.7](https://arxiv.org/abs/2010.07545)
    - Extreme emission line galaxies (EELGs) at 3< z <3.7
    - 19个有极强[OIII]发射线，2个有极强Halpha发射线的EELG：show, on average, higher specific star formation rates (sSFR) than the star-forming main sequence, low dust attenuation of E(B−V)≲0.1 mag, and high [OIII]/[OII] ratios of ≳3. 有很高的电离效率
    - 很可能是LyC leaker：they are low metallicity galaxies with higher ionization parameters and harder UV spectra than normal SFGs

- [Link between radio-loud AGNs and host-galaxy shape](https://arxiv.org/abs/2010.07622)
    - **Relevant**
    - LoTSS DR1 + SDSS分析15000个宁静星系中RLAGN对星系形态的影响
    - 在固定恒星质量，速度弥散度等性质上，RLAGN比例和星系的椭率没有关系；在非常高的150MHz光度上。RLAGNs are more likely to be found in massive, round galaxies
    - We argue that our results support the picture that high-power RLAGNs are more easily triggered in galaxies with a merger-rich history, while low-power RLAGNs can be triggered in galaxies growing mainly via secular processes
    - 把星系团里面和外面的RLAGN比较，发现上面结论与环境关系也不大

- [The nature of sub-millimetre galaxies I: A comparison of AGN and star-forming galaxy SED fits](https://arxiv.org/abs/2010.07934)
    - WHDF中的12个 LABOCA/ALMA 870micron SMG: 7/12 SMGs are best fitted with an obscured quasar model, a further 3/12 show no preference between AGN and star-forming templates, leaving only a z=0.046 spiral galaxy and one unidentified source
    - The vast majority (10/12) of bright SMGs are at least as likely to fit an AGN as a star-forming galaxy template.