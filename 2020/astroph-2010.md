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