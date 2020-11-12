# Astro-ph Notes

---- Song Huang ----

## 2020-November

----

### Nov 1

- [𝚍𝚎𝚎𝚙𝟸𝟷: a Deep Learning Method for 21cm Foreground Removal](https://arxiv.org/abs/2010.15843)
    - We demonstrate that a deep convolutional neural network (CNN) with a UNet architecture and three-dimensional convolutions, trained on simulated observations, can effectively separate frequency and spatial patterns of the cosmic neutral hydrogen (HI) signal from foregrounds in the presence of noise.
    - Our approach demonstrates the feasibility of analyzing 21cm intensity maps, as opposed to derived summary statistics, for upcoming radio experiments, as long as the simulated foreground model is sufficiently realistic.

- [Gaussian Process Foreground Subtraction and Power Spectrum Estimation for 21 cm Cosmology](https://arxiv.org/abs/2010.15892)
    - Recent works have claimed that Gaussian process regression (GPR) can robustly perform this separation, particularly at low Fourier k wavenumbers where the signal reaches its peak signal-to-noise ratio
    - We revisit this topic by casting GPR foreground subtraction (GPR-FS) into the quadratic estimator formalism, thereby putting its statistical properties on stronger theoretical footing. We find that GPR-FS can distort the window functions at these low k modes, which, without proper decorrelation, make it difficult to probe the EoR power spectrum.

- [Data Compression and Covariance Matrix Inspection: Cosmic Shear](https://arxiv.org/abs/2010.15986)
    - We investigate various compression mechanisms capable of vastly reducing the size of the covariance matrix in the context of cosmic shear statistics.
    - Massively Optimized Parameter Estimation and Data compression (MOPED) - only MOPED was able to replicate the original constraints in the 16-parameter space.
    - We apply a tolerance test to the elements of the compressed covariance matrix obtained with MOPED and confirm that the IA parameter A_IA is the most susceptible to inaccuracies in the covariance matrix.

- [Improving models of the cosmic infrared background using CMB lensing mass maps](https://arxiv.org/abs/2010.16405)
    - In measurements of the millimeter sky at frequencies higher than ∼300 GHz, the CIB and thermal emission from Galactic dust dominate. A limited understanding of the CIB contribution at lower frequencies on the other hand can hinder efforts to measure the kinetic Sunyaev-Zeldovich spectrum on small scales as well as new physics that affects the damping tail of the cosmic microwave background (CMB).
    - We show how significant improvements (20-100%) can be obtained on parameters of star formation models by cross-correlating the CIB (as measured from existing {\it Planck} maps or upcoming CCAT-prime maps) with upcoming mass maps inferred from gravitational lensing of the CMB.

- [The Evolution of Gas-Phase Metallicity and Resolved Abundances in Star-forming Galaxies at z≈0.6−1.8](https://arxiv.org/abs/2010.15847)
    - We define the stellar mass-metallicity relation at z≈0.6−1.0 and z≈1.2−1.8 and analyse the correlation between the scatter in the relation and fundamental galaxy properties
    - We find that for a given stellar mass, more highly star-forming, larger and irregular galaxies have lower gas-phase metallicities, which may be attributable to their lower surface mass densities and the higher gas fractions of irregular systems
    - A median, beam smearing-corrected, metallicity gradient of ΔZ/ΔR=0.002±0.004 dex kpc−1, indicating on average there is no significant dependence on radius.
    - [KMOS Galaxy Evolution Survey (KGES)](http://astro.dur.ac.uk/kmos/kges/)

- [BAT AGN Spectroscopic Survey-XX: Molecular Gas in Nearby Hard X-ray Selected AGN Galaxies](https://arxiv.org/abs/2010.15849)
    - We find that AGN in massive galaxies tend to have more molecular gas, and higher gas fractions, than inactive galaxies matched in stellar mass.
    - When matched in star formation, we find AGN galaxies show no difference from inactive galaxies with no evidence of AGN feedback affecting the molecular gas.
    - The likelihood of a given galaxy hosting an AGN (L_bol>10^44 erg/s) increases by ~10-100 between a molecular gas mass of 10^8.7 Msun and 10^10.2 Msun.
    - Higher Eddington ratio AGN galaxies tend to have higher molecular gas masses and gas fractions.

- [Connecting cosmological accretion to strong Lyman-alpha absorbers](https://arxiv.org/abs/2010.15857)
    - Performing simplified radiative transfer, we compute how the accreting gas turns increasingly neutral as it self-shields from the ionising background, and obtain the column density, NHI, as a function of impact parameter.
    - 关注点是柱密度分布函数,CDDF: The analytical expression elucidates (1) why halos over a large range in mass contribute about equally to the CDDF as well as (2) why the CDDF evolves so little with redshift in the range z=2→5.
    - CDDF的积分可以给出中性气体质量密度：ΩHI(z)  is nearly constant even though the accretion rate onto halos evolves. We show that this occurs because the fraction of time that the inflowing gas is neutral depends on the dynamical time of the halo, which is inversely proportional to the accretion rate.
    - 绝大多数的LLS和DLA都是正在吸积的气体：Most Lyman-limit system and damped Lyman-alpha absorbers are associated with the cosmological accretion of gas onto halos.

- [Galactic merger implications for eccentric nuclear disks: a mechanism for disk alignment](https://arxiv.org/abs/2010.15957)
    - 以M31中的nuclear disk为背景，看星系并合后，可能的second SMBH对盘的影响：We perform N-body simulations to study the disk under a range of different possible SMBH initial conditions. A second SMBH in the disk always disrupts it, but more distant SMBHs can shut off differential precession and stabilize the disk. This results in a more aligned disk, nearly uniform eccentricity profile, and suppression of tidal disruption events compared to the isolated disk.

- [The stellar mass function and evolution of the density profile of galaxy clusters from the Hydrangea simulations at 0<z<1.5](https://arxiv.org/abs/2010.16195)
    - **Relevant**
    - 24 massive galaxy clusters (>10^14M⊙ at z=0); 模拟中在z>1处有过多的<10^10 Msun星系
    - The NFW concentrations of cluster galaxies increase with redshift, in contrast to the decreasing dark matter halo concentrations
    - Quantitatively, we however find a discrepancy in that the simulations predict higher stellar concentrations than observed at lower redshifts (z<0.3), by a factor of ≈2.

- [Turbulent Gas in Lensed Planck-selected Starbursts at redshifts 1-3.5](https://arxiv.org/abs/2010.16231)
    - 关于高红移富气体星暴星系中ISM的激发状态：We analyze 162 CO rotational transitions (ranging from Jupper = 1 - 12) and 37 atomic carbon fine-structure lines ([CI]) in order to characterize the physical conditions of the gas in sample of LPs.
    - 用两个模型同时拟合CO+CI+连续谱：第一个模型是个双成分气体模型; The first model represents a two component gas density, while the second assumes a turbulence driven log-normal gas density distribution.
    - 模型描述了这些星系中湍动气体的性质：well-characterized by a high turbulent velocity dispersion (<ΔVturb>∼100 \kms) and gas kinetic temperature to dust temperature ratios <Tkin/Td>∼2.5, sustained on scales larger than a few kpc.

- [The effects of star formation history in the SFR-M relation of HII galaxies](https://arxiv.org/abs/2010.16296)
    - 看对HII星系，星暴矮星系等星系进行SED拟合时，假定不同SFH模型的影响
    - We modeled and fitted the SEDs with the code CIGALE adopting different descriptions of SFH. By adding information from different independent studies we find that HII galaxies are best described by episodic SFHs including an old (10 Gyr), an intermediate age (100-1000 Myr) and a recent population with ages < 10 Myr.
    - 在一定时标内平均的SFR上，矮星系也在M*-SFR的主序上；只有在使用当前SFR时才常位于这个关系的上方

----

### Nov 2

- [Quantifying the impact of baryon-CDM perturbations on halo clustering and baryon fraction](https://arxiv.org/abs/2011.01037)
    - Baryons and cold dark matter (CDM) did not comove prior to recombination. This leads to differences in the local baryon and CDM densities, the so-called baryon-CDM isocurvature perturbations δbc. 通常在LSS分析中被忽略
    - We further measure the cross-power spectrum between the halo field and δbc over a wide range of mass. This cross-correlation is nonzero and negative which shows that halo formation is impacted by δbc
    - This effect can be degenerate with the one of massive neutrinos for surveys like DESI.

- [SNEWS 2.0: A Next-Generation SuperNova Early Warning System for Multi-messenger Astronomy](https://arxiv.org/abs/2011.00035)
    - 和中微子探测器联动的早期预警设备; 包括了大亚湾的中微子实验

- [Radio Monitoring of the Tidal Disruption Event Swift J164449.3+573451. IV. Continued Fading and Non-Relativistic Expansion](https://arxiv.org/abs/2011.00074)
    - 9.4年的VLA和Chandra监测；We find that the X-ray emission has faded below detectable levels；while the radio emission continues to be detected and steadily fade.
    - Both are consistent with forward shock emission from a non-relativistic outflow, although we find that the radio spectral energy distribution is better fit at these late times with an electron power law index of p≈3 (as opposed to p≈2.5 at earlier times).
    - The energy scale of the blastwave is ≈1052 erg.

- [The scaling relations and clustering properties of central and satellite galaxies](https://arxiv.org/abs/2011.00014)
    - **Relevant**
    - While central and satellite galaxies display similar stellar mass - size relations, their halo mass - size relations differ significantly.
    - More massive haloes tend to host larger central galaxies. However, the size of satellite galaxies depends only slightly on halo virial mass.
    - We show that these results are compatible with a remarkably simple model in which the size of central and satellite galaxies scales as the cubic root of their host halo mass, with the normalization for satellites being ∼30 % smaller than that for central galaxies which can be attributed to tidal stripping.

- [A disk-dominated and clumpy circumgalactic medium of the Milky Way seen in X-ray emission](https://arxiv.org/abs/2011.00126)
    - **Interesting**
    - 基于HaloSat Cubesat的巡天：we report a survey of the southern Galactic sky with a soft X-ray spectrometer optimized to study diffuse soft X-ray emission. The X-ray emission is best fit with a disc-like model based on the radial profile of the surface density of molecular hydrogen, a tracer of star formation, suggesting that the X-ray emission is predominantly from hot plasma produced via stellar feedback.
    - Strong variations in the X-ray emission on angular scales of ∼10∘ indicate that the CGM is clumpy.

- [A proto-pseudobulge in ESO 320-G030 fed by a massive molecular inflow driven by a nuclear bar](https://arxiv.org/abs/2011.00347)
    - ALMA+Herschel H2O观测：Radiative transfer models indicate that 3 nuclear components are required to account for the H2O and continuum data. An envelope, a nuclear disk, and an extremely compact, warm, buried core component.
    - The nucleus is fed by a molecular inflow observed in CO 2-1 with ALMA, which is associated with the nuclear bar.
    - At lower r, the inflow is best probed by the far-infrared OH ground-state doublets, with an estimated inflow rate of ~30 Msun yr^{-1}. The short timescale of ~20 Myr for nuclear gas replenishment indicates quick secular evolution, and indicates that we are witnessing an intermediate stage (<100 Myr) proto-pseudobulge fed by a massive inflow that is driven by a strong nuclear bar.

- [A Method to Extract Spatially Resolved Polycyclic Aromatic Hydrocarbon Emission from Spitzer Spectra: Application to M51](https://arxiv.org/abs/2011.00405)
    - **Interesting**
    - We present a new approach of analyzing the spatial elements of the spectral datacube that simultaneously maximizes spatial resolution and spatial coverage, while yielding reliable measurements of the total, integrated 5−20μm PAH emission
    - We find that in M51 the PAH emission correlates tightly with the extinction-corrected far-ultraviolet, near-ultraviolet, and Hα emission, from scales∼0.4 kpc close to the nucleus to 6 kpc out in the disk of the galaxy, indicating that PAH serves as an excellent tracer of SFR over a wide range of galactic environments.
    - The spiral arms and the central star-forming region of the galaxy emit stronger 7.7 and 8.6 μm PAH features than the inter-arm regions.

- [A kpc-scale resolved study of unobscured and obscured star-formation activity in normal galaxies at z = 1.5 and 2.2 from ALMA and HiZELS](https://arxiv.org/abs/2011.00686)
    - ALMA连续谱观测：Four galaxies in our sample are detected at high significance by ALMA at a resolution of 0.25'' at rest-frame 355 μm.
    - We find that ALMA detection rates are higher for more massive galaxies (M∗>10^10.5 M⊙) and higher [Nii]/Hα ratios
    - The dust extends out to a radius of 8 kpc, with a smooth structure, even for those galaxies presenting clumpy Hα morphologies.

- [UV and NIR size of the HI selected low surface brightness galaxies](https://arxiv.org/abs/2011.00688)
    - **Relevant**
    - We select a sample of 381 HI bright LSBGs with both Far Ultraviolet (FUV) and Near Infrared (NIR) observation to investigate the star formation rate (SFR): most of the HI selected LSBGs have extended star formation structure.
    - The stellar mass distribution of LSBGs may have a similar structure as the disk galaxies at the same stellar mass bins, while the star-forming activity of LSBGs happens at a larger radius than the high surface density galaxies, which may help to select the LSBG sample from the wide-field deep u band image survey.
    - HI radius比UV radius大3倍左右

- [A population of galaxy-scale jets discovered using LOFAR](https://arxiv.org/abs/2011.01015)
    - **Interesting**
    - LoTSS研究低光度射电噪AGN的feedback：report on our discovery of a population of 195 radio galaxies and total radio emission no larger than 80 kpc.
    - 大部分host都是椭圆星系，但也有~9%是旋涡星系：Two of the spiral-hosted GSJ are highly unusual with low radio luminosities and FRII-like morphology
    - 大都是年轻的jet: The host properties of our GSJ show that they are ordinary AGN observed at a stage in their life shortly after the radio emission has expanded beyond the central regions of the host.
    - 能量可以影响星系整体的ISM性质：we find that about half of our GSJ have internal radio lobe energy within an order of magnitude of the ISM energy so that, even ignoring any possible shocks, GSJ are energetically capable of affecting the evolution of the host.
    - [`pysynch`: Python interface to synchrotron libraries](https://github.com/mhardcastle/pysynch)

- [Discovery of a new extreme changing-state quasar with 4 mag variation, SDSS J125809.31+351943.0](https://arxiv.org/abs/2011.01127)
    - SDSS J125809.31+351943.0 (J1258), which brightened in optical for 4 mag from 1983 to 2015, which is one of the largest quasar brightening events so far.
    - The results show that the continuum flux and the BEL flux decreased to about 50 % of its peak. This indicates that J1258 is causing two changing-states for the BEL flux and continuum flux.
    - We argue that J1258's variability, especially its brightening event, can be explained by the propagation of the heating front and the accretion disk state transitions based on the timescale and Eddington ratio variations.

----

### Nov 3

- [Constraining the Halo Mass of Damped Lyα Absorption Systems (DLAs) at z=2−3.5 using the Quasar-CMB Lensing Cross-correlation](https://arxiv.org/abs/2011.01234)
    - We study the cross correlation of damped Lyα systems (DLAs) and their background quasars, using the most updated DLA catalog and the Planck 2018 CMB lensing convergence field.
    - DLA bias bDLA is smaller than 3.1, corresponding to log(M/M⊙h−1)≤12.3 at a confidence of 90%.

- [Comparing Foreground Removal Techniques for Recovery of the LOFAR-EoR 21cm Power Spectrum](https://arxiv.org/abs/2011.01284)
    - We test the performance of removal techniques (FastICA, GMCA, and GPR) on 10 nights of LOFAR data and investigate the possibility of recovering the latest upper limit on the 21cm signal.
    - FastICA和GMCA在大尺度不够好：We find that no single instrumental effect, such as primary beam effects or mode-mixing, can explain the poorer recovery by FastICA and GMCA at larger \textit{k}-scales. 大尺度需要更多的成分：For larger scales (k≳0.1 hcMpc−1), more independent components are needed to fit the foregrounds.
    - Gaussian process regression (GPR) 是比较好的方法

- [Cosmological consequences of intrinsic alignments super-sample covariance](https://arxiv.org/abs/2011.01284)

- [Fast magnetic field amplification in distant galaxy clusters](https://arxiv.org/abs/2011.01628)
    - **Interesting**
    - We report LOFAR observations which reveal diffuse radio emission in massive clusters when the Universe was only half of its present age, with a sample occurrence fraction of about 50%. The high radio luminosities indicate that these clusters have similar magnetic field strengths to those in nearby clusters, and suggest that magnetic field amplification is fast during the first phases of cluster formation.

- [Two-point statistics without bins: A continuous-function generalization of the correlation function estimator for large-scale structure](https://arxiv.org/abs/2011.01836)
    - **Useful**
    - We present a new 2pcf estimator, the Continuous-Function Estimator, which generalizes LS to a continuous representation and obviates binning in separation or any other pair property
    - Our estimator, inspired by the mathematics of least-squares fitting, replaces binned pair counts with projections onto basis functions; it outputs the best linear combination of basis functions to describe the 2pcf.
    - We show that the Continuous-Function Estimator with a cubic-spline basis better represents the shape of the 2pcf compared to LS.

- [Massive black hole binary systems and the NANOGrav 12.5 year results](https://arxiv.org/abs/2011.01246)
    - **Interesting**
    - 关于NANOGrav最近看到的“the presence of a common stochastic signal across their array of pulsars.”的证据的
    - One of the possibilities is that it is due to a stochastic gravitational wave background (SGWB) in the ∼1−10nHz frequency region. This signal would be fully consistent with a SGWB produced by an unresolved population of in-spiralling massive black hole binaries (MBHBs) predicted by current theoretical models.
    - Regardless of the astrophysical details of MBHB assembly, this result would imply that a sufficiently large population of massive black holes pair up, form binaries and merge within a Hubble time.

- [Fast radio bursts: do repeaters and non-repeaters originate in statistically similar ensembles](https://arxiv.org/abs/2011.01339)
    - At present, over one hundred FRBs have been verified, classified into two groups: repeating bursts (20 samples) and apparently non-repeating bursts (91 samples)
    - Firstly, by taking the pulse width as a statistical variant, we found that the repeating samples do not follow the Gaussian statistics (may belong to a chi-square distribution), although the overall data and non-repeating group do follow the Gaussian
    - Secondly, we consider the FRB radio luminosity as a statistical variant, and find that both groups of samples can be regarded as the Gaussian distributions under the A-D test

- [Discovery of a Fast Iron Low-ionization Outflow in the Early Evolution of the Nearby Tidal Disruption Event AT2019qiz](https://arxiv.org/abs/2011.01593)
    - Our late-time host-dominated spectrum indicates that the host galaxy likely harbours a weak AGN.
    - The initial HST spectrum of AT2019qiz exhibits a iron and low-ionization broad absorption line (FeLoBAL) system that is seen for the first time in a TDE. 光谱和Gaia16apd，一个超亮的SN很像
    - In a time frame of 50 days, the UV spectra of AT2019qiz started to resemble previous TDEs with only high-ionization BALs. 外流速度也随之下降；从Halpha也能看出宽线在TDE外流中的形成
    - 复习：In a subclass of BALQSO, the low-ionization broad absorption line (LoBAL) QSOs have UV spectra imprinted by broad absorption of Mg ii λλ2796, 2803, Al III, and Al II at λrest > 1750˚A. In even rarer cases, absorption of iron lines are present in the QSO spectra and thus these QSOs are termed “FeLoBAL” QSOs.
        - FeLoBALs are particularly well-suited for photoionization modeling: 因为FeII和HeI线对电子密度和温度的依赖是正交的
        - 吸收线速度比常见的BAL高电离线要低，距离黑洞更远, 1-3 kpc; 结构很薄:  partial, cold thin shell
        - FeLoBALs can form in situ via interaction of a quasar blast wave with an interstellar gas clump
        - Radiative shock, cloud crushing model explains all the observed FeLoBAL properties

- [A low-frequency radio halo survey of the South Pole Telescope SZ-selected clusters with the GMRT](https://arxiv.org/abs/2011.01652)
    - We explore clusters with redshift z>0.3 in search of diffuse radio emission, at 325 MHz with the Giant Metrewave Radio Telescope (GMRT). This campaign has resulted in the discovery of 2 new radio halos (SPT-CL J0013-4906 and SPT-CL J0304-4401) along with 2 other detections (SPT-CL J2031-4037 and SPT-CL J2248-4431)

- [Evolution of the chemical enrichment and the Mass-Metallicity relation in CALIFA galaxies](https://arxiv.org/abs/2011.01229)
    - We find the expected results that the most massive galaxies got enriched faster, with the MZR getting steeper at higher redshifts. However, once we separate the galaxies into morphology bins this behaviour is not as clear, which suggests that morphology is a primary factor to determine how fast a galaxy gets enriched (??)
    - We also find that star-forming galaxies appear to be converging in their chemical evolution, that is, the metallicity of star-forming galaxies of different mass is very similar at recent times compared to several Gyr ago.

- [Investigating Clumpy Galaxies in SDSS Stripe82 using Galaxy Zoo](https://arxiv.org/abs/2011.01232)
    - We select a sample of 92 z<0.06 clumpy galaxies in SDSS Stripe82 galaxies. Within this sample, we identify 543 clumps using a contrast-based image analysis algorithm and perform photometry
    - The overall properties of our z<0.06 clump sample are comparable to the high-redshift clumps. However, contrary to the high-redshift studies, we find no evidence of a gradient in clump ages or masses as a function of their galactocentric distance

- [The Elephant in the Bathtub: when the physics of star formation regulate the baryon cycle of galaxies](https://arxiv.org/abs/2011.01235)
    - We assess the importance of dynamical suppression in the context of gas regulator models of galaxy evolution through hydrodynamic simulations of isolated galaxies, with gas-to-stellar mass ratios of 0.01-0.20 and a range of galactic gravitational potentials from disc-dominated to spheroidal.
    - We find that dynamical suppression becomes more effective at lower gas fractions and quantify its impact on the star formation rate as a function of gas fraction and stellar spheroid mass surface density.
    - We predict that the physics of star formation can limit and regulate the baryon cycle at low redshifts (z≲1.4) and high galaxy masses (M∗≳3×10^10 M⊙), where dynamical suppression can drive galaxies off the star formation main sequence.

- [Observational insights on the origin of giant low surface brightness galaxies](https://arxiv.org/abs/2011.01238)
    - **Relevant**
    - 长缝光谱观测一个比较随机的样本：six of seven galaxies sit on the high-mass extension of the baryonic Tully--Fisher relation.
    - In UGC 1382 we detected a global counter-rotation of the stellar high surface brightness (HSB) disc with respect to the extended LSB disc. In UGC 1922 with signatures of a possible merger, the gas counter-rotation is seen in the inner disc.
    - Six galaxies host active galactic nuclei, three of which have the estimated black hole masses substantially below those expected for their (pseudo-)bulge properties suggesting poor merger histories.
    - Three formation scenarios shape gLSBGs: (i) a two-stage formation when an HSB galaxy is formed first and then grows an LSB disc by accreting gas from an external supply; (ii) an unusual shallow and extended dark matter halo; (iii) a major merger with fine-tuned orbital parameters and morphologies of the merging galaxies.

- [Highly turbulent gas on GMC-scales in NGC 3256, the nearest luminous infrared galaxy](https://arxiv.org/abs/2011.01250)
    - We present the highest resolution CO (2-1) observations obtained to date (0.25") of NGC 3256
    - Mass surface densities range from 8 to 5500 M⊙ pc−2 and velocity dispersions from 10 to 200 km s−1. Peak brightness temperatures as large as 37 K are measured, indicating the gas in NGC 3256 may be hotter than all regions in nearby disc galaxies measured by PHANGS-ALMA.
    - Given the lack of significant trends in surface density, brightness temperature, and velocity dispersion with physical scale we argue the molecular gas is made up of a smooth medium down to 55 pc scales, unlike the more structured medium found in the PHANGS-ALMA disc galaxies.
    - 复习：As an estimate of the balance between the kinetic energy, K, and gravitational energy, Ug, within a molecular cloud, the virial parameter, αvir ≡ 2K/Ug, can indicate the likelihood of collapse and the ability to form stars (McKee & Zweibel 1992; Federrath & Klessen 2012; Krumholz et al. 2012; Padoan et al. 2017).

- [ALMA Resolves Giant Molecular Clouds in a Tidal Dwarf Galaxy](https://arxiv.org/abs/2011.01287)
    - ALMA观测Arp 94里的TDG：We find a remarkably high fraction of extended molecular emission (~80-90%), which is filtered out by the interferometer and likely traces diffuse gas.
    - GMC质量函数和MW差不多；GMCs follow the size-mass relation of the Milky Way, but their velocity dispersion is higher such that the size-linewidth and virial relations appear super-linear, deviating from the canonical values.
    - Overall, the organisation of the molecular ISM in this TDG is quite different from other types of galaxies on large scales, but the properties of GMCs seem fairly similar, pointing to near universality of the star-formation process on small scales. ISM的分布有差别，但具体到GMC上差别不大

- [Predicting Primordial Star Formation with Deep Convolutional Neural Networks](https://arxiv.org/abs/2011.01358)
    - 可以不需要halo finder就能预测原初SF的位置：The predictor consists of two deep neural networks: one predicts subvolumes of size 10^3 comoving kpc3 which host star forming regions, another predicts which voxels within the subvolume may be forming stars.
    - When applied to simulations with coarser mass resolution, we find that the method is capable of finding star-forming regions at later redshifts, but cannot completely overcome the delayed structure formation that is a consequence of lower mass and force resolution

- [Environmental processing of galaxies in HI-rich groups](https://arxiv.org/abs/2011.01438)
    - "Choirs" galaxies: HI-rich and LTG dominated group  galaxies
    - We find that the H i mass fraction of the Choir galaxies is dispersed around the Hipass median in the range
    - We show and discuss that the environmental processing in Choirs occurs via tidal stripping and galaxy mergers. Our analysis suggests that tidal stripping contributes to the loss of the HI, while galaxy mergers contribute to the enhancement of the HI
    - We conclude that the most likely evolution for the majority of Choir groups is that they will become more compact as their members undergo multiple H i-rich mergers.

----

### Nov 4

- [Reconciling galaxy cluster shapes, measured by theorists vs observers](https://arxiv.org/abs/2011.01945)
    - **Relevant**
    - 用BAHAMAS模拟看cluster的X-ray，强引力透镜，弱引力透镜mock观测，看cluster shape
    - 和模拟里常用的moments of inertia比较：Even when moments of inertia are projected into 2D and evaluated at matched radius, they overestimate ellipticity by 56% (compared to observable strong lensing) and 43% (compared to observable weak lensing).
    - In real clusters, the ellipticity and orientation angle at all radii are strongly correlated. In simulated clusters, the ellipticity of inner (< rvir/20) regions becomes decoupled: for example with greater misalignment of the central cluster galaxy. This may indicate overly efficient implementation of feedback from active galactic nuclei.

- [ForSE: a GAN based algorithm for extending CMB foreground models to sub-degree angular scales](https://arxiv.org/abs/2011.02221)
    - ForSE exploits the ability of generative adversarial neural networks (GANs) to learn and reproduce complex features present in a set of images, with the goal of simulating realistic and non-Gaussian foreground radiation at sub-degree angular scales.
    - Our results show how ForSE is able to generate small scale features (at 12 arc-minutes) having as input the large scale ones (80 arc-minutes). The injected structures have statistical properties, evaluated by means of the Minkowski functionals, in good agreement with those of the real sky and which show the correct amplitude scaling as a function of the angular dimension.

- [On the halo-mass and radial scale dependence of the lensing is low effect](https://arxiv.org/abs/2011.02377)
    - **Relevant**
    - 还是关于Lensing-is-low的结果：We present new measurements and modelling of galaxies in the BOSS LOWZ sample. We focus on the radial and stellar mass dependence of the lensing amplitude mis-match. We find an amplitude mis-match of around 35% when assuming ΛCDM with Planck Cosmological Microwave Background (CMB) constraints.
    - The observation that the offset is both mass and scale independent places important constraints on the degree to which astrophysical processes (baryonic effects, assembly bias) can fully explain the effect.
    - This scale independence also suggests that the "lensing is low" effect on small and large radial scales probably have the same physical origin. Resolutions based on new physics require a nearly uniform suppression, relative to ΛCDM predictions, of the amplitude of matter fluctuations on these scales.

- [LOFAR observations of galaxy clusters in HETDEX](https://arxiv.org/abs/2011.02387)
    - We characterize the presence of diffuse radio emission in known galaxy clusters in the HETDEX Spring Field, covering 424 deg
    - The fraction of Planck PSZ2 clusters with any diffuse radio emission apparently associated with the ICM is 73±17%.
    - We detect a total of 10 radio halos and 12 candidate halos in the HETDEX Spring Field. Five clusters host radio relics. The fraction of radio halos in Planck PSZ2 clusters is 31±11%, and 62±15% when including the candidate radio halos.

- [CMB lensing power spectrum estimation without instrument noise bias](https://arxiv.org/abs/2011.02475)
    - Measuring the lensing power spectrum involves the estimation of the connected trispectrum of the four-point function of the CMB map, which requires the subtraction of a large Gaussian disconnected noise bias
    - We propose a new estimator that makes use of at least four splits of the CMB maps with independent instrument noise. This estimator makes the CMB lensing power spectrum completely insensitive to any assumptions made in modeling or simulating the instrument noise.

- [Atomic data for the Gaia-ESO Survey](https://arxiv.org/abs/2011.02049)
    - **Useful, SSST**
    - We present an unprecedented effort to create a homogeneous line list, which was used by several abundance analysis groups to calculate synthetic spectra and equivalent widths.
    - Desirable improvements in atomic data were identified for a number of species, including Al I, S I, Cr II, Na I, Si I, Ca II, and Ni I.

- [Magnetic flux inversion in a peculiar changing look AGN](https://arxiv.org/abs/2011.01954)
    - We argue that the changing-look event in the active galactic nucleus 1ES 1927+654, followed by a dip of 3 orders of magnitude in the X-ray luminosity, is controlled by a change in the accretion rate and an inversion of magnetic flux in a magnetically arrested disk (MAD).
    - Before the changing-look event, strong magnetic flux on the black hole powers X-ray emission via the Blandford-Znajek process while the UV emission is produced by a radiatively inefficient magnetized disk. An advection event, bringing flux of the opposite polarity, propagates inward leading, first, to a rise in the UV/optical luminosity and, then, to a dip in the X-ray luminosity when it reaches the black hole.
    - Although flux inversion events might be rare due to the large ratio of flux-to-mass that is needed, we argue that AGN showing an unusually high ratio of X-ray to UV luminosity are prime candidates for such events

- [Dynamical structure of highly eccentric discs with applications to tidal disruption events](https://arxiv.org/abs/2011.02219)
    - 关于TDE事件中的吸积过程：highly eccentric disc must have a strong, non-hydrostatic variation of the disc scale height around each orbit.
    - We study the variation of physical quantities around each elliptical orbit, taking into account the dynamical vertical structure, as well as viscous dissipation and radiative cooling
    - We find that J074749+115352, with a SMBH mass of MSMBH≈1.8×10^9 M⊙ and an Eddington ratio of λEdd≈2.3, is extraordinarily X-ray bright.
    - We find evidence for the existence of the thermal instability in highly eccentric discs dominated by radiation pressure

- [Chandra Detection of Three X-ray Bright Quasars at z>5](https://arxiv.org/abs/2011.02358)
    - 观测三个高红移QSO，信噪比可以单独抽谱
    - J074749+115352 at z=5.26 is the X-ray brightest radio-quiet quasar at z>5. It may have a short timescale variation (on a timescale of ∼3800 s in the observer's frame, or ∼600 s in the rest frame) which is however largely embedded in the statistical noise.
    - We compare Γ of the three quasars to other samples at different redshifts, and do not find any significant redshift evolution based on the limited sample of z>5 quasars with reliable measurements of the X-ray spectral properties.

- [Hot and counter-rotating star-forming disk galaxies in IllustrisTNG and their real-world counterparts](https://arxiv.org/abs/2011.01949)
    - 研究低质量星系中的hot stellar disk结构：We find that being dynamically hot arises in most cases as an induced transient state, for example due to galaxy interactions and merger activities, rather than as an age-dependent evolutionary phase of star-forming disk galaxies.
    - Kinematically misaligned gas and stellar disks, and centrally concentrated on-going star formation 是常见特征
    - Observed galaxies from MaNGA with kinematic misalignment between gas and stars show remarkably similar general properties as the IllustrisTNG galaxies, and therefore are plausible real-world counterparts

- [Quasi-equilibrium models of high-redshift disc galaxy evolution](https://arxiv.org/abs/2011.01966)
    - We introduce a set of galaxy models that are based on a simple physical framework but incorporate more sophisticated models of feedback, star formation, and other processes
    - 能重现一些empirical模型的预研：the stellar mass--halo mass relation depends almost entirely on the physics of feedback (and is thus independent of the details of small-scale star formation) and the specific star formation rate is a simple multiple of the cosmological accretion rate.
    - The galaxy's gas mass is sensitive to the physics of star formation, although the inclusion of feedback-driven star formation laws significantly changes the naive expectations.

- [High-resolution imaging follow-up of doubly imaged quasars](https://arxiv.org/abs/2011.01971)
    - NIRC2确认观测：Out of these 57 candidates, 15 are confirmed as lenses. We form a sample of 20 lenses adding in a number of previously-known lenses
    - We compare the departure of the observed flux ratios from the smooth-model predictions between doubly and quadruply imaged quasar systems. We find that the departure is consistent between these two types of lenses if the modelling uncertainty is comparable.

- [The black hole mass of the z=2.805 multiply imaged quasar SDSS J2222+2745 from velocity-resolved time lags of the CIV emission line](https://arxiv.org/abs/2011.02007)
    - Reverberation mapping分析：黑洞质量10^8.63 Msun

- [The Accreted Nuclear Clusters of the Milky Way](https://arxiv.org/abs/2011.02042)
    - We combine a number of independent constraints, focusing on their internal abundances and overall kinematics, to find NSCs accreted by the Galaxy and trace them to their accretion event.
    - We find that the true NSCs accreted by the Galaxy are: M54 from the Sagittarius Dwarf, ω Centari from Gaia-Enceladus/Sausage, NGC 6273 from Kraken and (potentially) NGC 6934 from the Helmi Streams.
    - No NSC appears to be associated with Sequoia or other minor accretion events. Other claimed NSCs are shown not to be such. We also discuss the peculiar case of Terzan 5, which may represent a unique case of a cluster-cluster merger.

----

### Nov 5

- [Starburst galaxies strike back: a multi-messenger analysis](https://arxiv.org/abs/2011.02483)
    - Starburst galaxies, which are known as "reservoirs" of high-energy cosmic-rays, can represent an important high-energy neutrino "factory" contributing to the diffuse neutrino flux observed by IceCube.
    - 不是简单的假设power-law的中微子flux，采用了更真实的模型：erform a multi-messenger analysis considering the extragalactic gamma-ray background (EGB) measured by Fermi-LAT and different IceCube data samples: the 7.5-year High-Energy Starting Events (HESE) and the 6-year high-energy cascade data. 同时考虑了blazar和radio星系的贡献以及secondary gamma-rays from electromagnetic cascades的贡献
    - Differently from the highly-constrained prototype scenario, the spectral index blending allows starburst galaxies to account for up to 40% of the HESE events at 95.4% CL

- [The impact of astrophysical dust grains on the confinement of cosmic rays](https://arxiv.org/abs/2011.02497)
    - We argue that charged dust grains could significantly impact the confinement and transport of galactic cosmic rays. For sub-GeV to ~1000GeV cosmic rays, small-scale parallel Alfven waves, which isotropize cosmic rays through gyro-resonant interactions, are also gyro-resonant with charged grains
    - If the dust is nearly stationary, as in the bulk of the interstellar medium, Alfven waves are damped by dust. This will reduce the amplitude of Alfven waves produced by the cosmic rays through the streaming instability, thus enhancing cosmic-ray transport.
    - In astrophysical situations in which the dust moves through the gas with super-Alfvenic velocities, Alfven waves are rendered unstable, which could directly scatter cosmic rays. This interaction has the potential to create a strong feedback mechanism where dust, driven through the gas by radiation pressure, then strongly enhances the confinement of cosmic rays, increasing their capacity to drive outflows.

- [SOFIA/FIFI-LS Full-disk [CII] Mapping and CO-dark Molecular Gas across the Nearby Spiral Galaxy NGC 6946](https://arxiv.org/abs/2011.02498)
    - NGC 6946; The firework galaxy
    - We attribute 73% of the [CII] luminosity to arms, and 19% and 8% to the center and interarm region, respectively. [CII]/TIR, [CII]/CO, and [CII]/PAH radial profiles are largely constant, but rise at large radii (≳8kpc) and drop in the center ("[CII] deficit").
        - This increase at large radii and the observed decline with the 70μm/100μm dust color are likely driven by radiation field hardness
    - We find a near proportional [CII]-SFR scaling relation for beam-sized regions, though the exact scaling depends on methodology. [CII] also becomes increasingly luminous relative to CO at low SFR (interarm or large radii), likely indicating more efficient photodissociation of CO and emphasizing the importance of [CII] as an H2 and SFR tracer in such regimes

- [Bringing faint Active Galactic Nuclei (AGN) to light](https://arxiv.org/abs/2011.02501)
    - **Study** 适合学习不同模拟的AGN处理方式
    - 着眼于未来的X-ray设备，Athena, AXIS, Lynx等，看不同模拟里的低光度AGN
    - We analyze the population of faint AGN (L_x (2-10 keV) < 10^42 erg/s) in the Illustris, TNG100, EAGLE, and SIMBA large-scale cosmological simulations. We find that the properties of the faint AGN host galaxies vary from simulation to simulation. In Illustris and EAGLE, faint AGN of L_x (2-10 keV) ~ 10^38 erg/s are powered by low-mass BHs and they are typically located in low-mass star-forming galaxies. In TNG100 and SIMBA, they are mostly associated with more massive BHs in quenched massive galaxies.
    - While the AGN dominate the hard X-ray galaxy luminosity at high redshift (z>2), the X-ray binaries often dominate at low redshift (z<2). The X-ray luminosity of star-forming galaxies is often dominated by AGN emission, and of quenched galaxies by XRB emission.
    - AGN obscuration can affect by almost one order of magnitude the median AGN+XRB luminosity.
    - Some simulations reveal clear AGN trends as a function of stellar mass, which are less apparent in the current observations.

- [The Effect of Bi-conical Outflows on Lyα Escape From Green Peas](https://arxiv.org/abs/2011.02549)
    - 利用和cool & warm气体有关的低电离Si吸收线研究外流HI气体和Lya逃逸的关系：We find that outflow geometries which leave a portion of the source uncovered along the line of sight create the best conditions for Lyα escape and have narrow peak separations, while geometries which block the observer's view of the source create the worst conditions for Lyα escape and have large peak separations

- [The ALFALFA-SDSS Galaxy Catalog](https://arxiv.org/abs/2011.02588)
    - **Important, Useful**
    - HI-optical catalog of ~ 30,000 galaxies based on the 100% complete Arecibo Legacy Fast Arecibo L-band Feed Array (ALFALFA)
    - We also provide measures of stellar masses and star formation rates based on infrared and/or ultraviolet photometry for galaxies that are detected by the Wide-field Infrared Survey Explorer (WISE) and/or the Galaxy Evolution Explorer (GALEX).
    - ALFALFA galaxies typically have lower masses and bluer colors.

- [Evidence for galaxy quenching in the green valley caused by a lack of a circumgalactic medium](https://arxiv.org/abs/2011.02589)
    - **Interesting**
    - Edge-on星系G1547附近84kpc，距离盘主轴10度的QSO探测CGM，没有任何探测：G1547 does not have any detectable CGM absorption down to stringent limits, covering HI (EWr<0.02A, log(N(HI)/cm−2)<12.6) and a range of low and high ionisation absorption lines (OI, CII, NII, SiII, CIII, NIII, SiIII, CIV, SiIV, NV and OVI).
    - G1547有很低的SFR和sSFR，没有SF或者AGN引起的外流; in the green valley and has an above average metallicity with a negative gradient
    - We conclude that SSFR is a good indicator of the presence of HI CGM. Interestingly however, G1547 is the only galaxy with log(SSFR/yr−1)>−11 that has no detectable CGM.

- [Revealing the structure and internal rotation of the Sagittarius dwarf spheroidal galaxy with Gaia and machine learning](https://arxiv.org/abs/2011.02627)
    - 机器学习的推断过程可以参考一下
    - Our results show that Sgr has a bar structure ∼2.5 kpc long, and that tidal tails emerge from its tips to form what it is known as the Sgr stream. The main body of the galaxy, strongly sheared by tidal forces, is a triaxial (almost prolate) ellipsoid
    - Its external regions are expanding mainly along its longest principal axis, yet the galaxy conserves an inner core of about 500-330-300 pc that shows no net expansion

- [The complex multi-component outflow of the Seyfert galaxy NGC 7130](https://arxiv.org/abs/2011.02937)
    - AO-MUSE 观测：We performed a multi-component analysis of the main ISM lines and identified nine kinematic components, six of which correspond to the outflow.
    - We decompose the approaching side of the outflow into a Broad and a Narrow Component with typical velocity dispersions below and above ∼200kms−1, respectively. The Blueshifted Narrow Component has substructure, in particular a collimated plume aligned with the radio jet, indicating that it may be jet-powered. The redshifted lobe is composed of two Narrow Components and a Broad Component.

- [Spiral instabilities: Linear and nonlinear effects](https://arxiv.org/abs/2011.03041)
    - We present a study of the spiral responses in a stable disc galaxy model to co-orbiting perturbing masses that are evenly spaced around rings.
    - The amplitudes of the responses, or wakes, are proportional to the masses of the perturbations, and we find that the response to a low-mass ring disperses when it is removed -- behaviour that is predicted by linear theory. Higher mass rings cause nonlinear changes through scattering at the major resonances, provoking instabilities that were absent before the scattering took place.

- [The GALAH+ Survey: Third Data Release](https://arxiv.org/abs/2011.02505)
    - **Important**
    - We publish 678 423 spectra for 588 571 mostly nearby stars (81.2% of stars lie within 2 kpc), observed with the HERMES spectrograph at the Anglo-Australian Telescope. This release (referred to as GALAH+ DR3) includes all observations from GALAH Phase 1 (bright, main, & faint survey, 70%), the K2-HERMES (17%) & TESS-HERMES (5%) surveys, as well as additional GALAH-related projects (8%) including the bulge & observations of more than 75 stellar clusters.
    - We also derive abundance ratios [X/Fe] for 30 elements (11 of which based on non-LTE computations), that cover 5 nucleosynthetic pathways: Li, C, O, Na, Mg, Al, Si, K, Ca, Sc, Ti, V, Cr, Mn, Co, Ni, Cu, Zn, Rb, Sr, Y, Zr, Mo, Ru, Ba, La, Ce, Nd, Sm, Eu.
    - [The GALAH survey: tracing the Galactic disk with Open Clusters](https://arxiv.org/abs/2011.02533)
    - [The GALAH Survey: Accreted stars also inhabit the Spite Plateau](https://arxiv.org/abs/2011.02659)
    - [The GALAH survey: Milky Way disc metallicity and alpha-abundance trends in combined APOGEE-GALAH catalogues](https://arxiv.org/abs/2011.02783)

- [Kilonova Emission From Black Hole-Neutron Star Mergers. II. Luminosity Function and Implications for Target-of-opportunity Observations of Gravitational-wave Triggers and Blind Searches](https://arxiv.org/abs/2011.02717)
    - **SSST, Important**
    - We present KN luminosity function and discuss the detectability of KN and GRB afterglow in connection with GW detections, GW-triggered ToO observations, and blind searches in time-domain survey observations.
        - The predicted absolute magnitude of the BH-NS merger KNe at 0.5day after the merger falls in the range of [−10,−15.5].
    - The detectability of KN emission is sensitive to the BH spin. If primary BHs typically have a low spin, the EM counterpart of BH-NSs are hard to discover.
    - Follow up observations can in any case detect possible associated sGRB afterglows, from which KN signatures may be studied. For time-domain survey observations, a high-cadence search in redder filters is recommended to detect more BH-NS KNe and afterglows.

----

### Nov 8

- [Neutrino mass bounds from confronting an effective model with BOSS Lyman-alpha data](https://arxiv.org/abs/2011.03050)
    - **SSST**
    - We present an effective model for the one-dimensional Lyman-α flux power spectrum far above the baryonic Jeans scale; encode the impact of small, highly non-linear scales on the one-dimensional power spectrum on large scale
    - The model displays a degeneracy between the neutrino masses and the (unknown, in our formalism) normalization of the flux power spectrum.
    - This approach can be used to extract bounds on the sum of neutrino masses with comparably low numerical effort, while allowing for a conservative treatment of uncertainties from the dynamics of the intergalactic medium.

- [Illuminating the dark side of cosmic star formation two billion years after the Big Bang](https://arxiv.org/abs/2011.03051)
    - **Interesting**
    - 目前高红移的SFRD主要来自紫外亮的星系：We present a new approach to find dust-obscured star-forming galaxies based on their emission at radio wavelengths coupled with the lack of optical counterparts.
    - 很多都是在之前没有考虑在SFRD内的，影响可能比较大：The contribution of these elusive systems to the SFRD is substantial and can be as high as 40% of the previously known SFRD based on UV-luminous galaxies.

- [Dark Energy Survey Year 3 Results: Photometric Data Set for Cosmology](https://arxiv.org/abs/2011.03407)
    - **Important** A lot of useful notes in the appendix
    - Y3 Gold comprises nearly 5000 square degrees of grizY imaging in the south Galactic cap, including nearly 390 million objects, with depth reaching S/N ~ 10 for extended objects up to iAB∼23.0
    - Y3 Gold augments DES DR1 with simultaneous fits to multi-epoch photometry for more robust galaxy color measurements and corresponding photometric redshift estimates

- [Dark Energy Survey Year 3 Results: Weak Lensing Shape Catalogue](https://arxiv.org/abs/2011.03408)
    - **Important**
    - ~4143 deg^2; We describe our data analysis process and our self-calibrating shear measurement pipeline METACALIBRATION,
    - The DES Year 3 weak-lensing shape catalogue consists of 100,204,026 galaxies, measured in the riz bands, resulting in a weighted source number density of neff=5.59 gal/arcmin2 and corresponding shape noise σe=0.261.

- [Dark Energy Survey internal consistency tests of the joint cosmological probes analysis with posterior predictive distributions](https://arxiv.org/abs/2011.03410)
    - We find that the DES Y1 data have an acceptable goodness of fit to ΛCDM, with a probability of finding a worse fit by random chance of p=0.046.
    - we observe a small tension between large- and small-scale measurements. A small part (roughly 1.5%) of the data vector shows an unusually large departure from expectations; excluding this part of the data has negligible impact on cosmological constraints, but does significantly improve the p-value to 0.10.

- [Dark Energy Survey Year 3 Results: Optimizing the Lens Sample in Combined Galaxy Clustering and Galaxy-Galaxy Lensing Analysis](https://arxiv.org/abs/2011.03411)
    - **Important**
    - 看结合g-g lensing和clustering能带来多大改进：We explore easily reproducible selections based on magnitude cuts in i-band as a function of (photometric) redshift, zphot, and benchmark the potential gains against those using the well established redMaGiC sample
    - Our optimal selection, the MagLim sample, satisfies i<4zphot+18 and has ∼30% wider redshift distributions but ∼3.5 times more galaxies than redMaGiC. Assuming a wCDM model and equivalent scale cuts to mitigate nonlinear effects, this leads to 40% increase in the figure of merit

- [BICEP / Keck Array XII: Constraints on axion-like polarization oscillations in the cosmic microwave background](https://arxiv.org/abs/2011.03483)
    - A local axion field induces an all-sky, temporally sinusoidal rotation of CMB polarization.
    - 复习：Axion-like particles (sometimes abbreviated as ALPs), which are light, bosonic particles with couplings to the Standard Model (SM) that are similar to that of the QCD axion but with important differences
        - Very light axions can have astrophysically large deBroglie wavelengths, which have macroscopic consequences for the formation of structure. Such dark-matter candidates are sometimes referred to as fuzzy dark matter

- [Dark Energy Survey Year 3 Results: Point-Spread Function Modeling](https://arxiv.org/abs/2011.03409)
    - **Useful** 关于Piff的介绍
    - We describe the relevant details about the algorithms used by Piff to model the PSF, including how the PSF model varies across the field of view (FOV).
    - The systematic errors from the PSF modeling are significantly smaller than the corresponding results from the DES year one (Y1) analysis

- [Disentangling the AGN and star-formation contributions to the radio-X-ray emission of radio-loud quasars at 1<z<2](https://arxiv.org/abs/2011.03130)
    - Here we introduce a state-of-the-art AGN radio-to-X-ray spectral energy distribution fitting model (ARXSED).
    - At radio wavelengths, ARXSED accounts for radiation from the radio structures (e.g., lobes,jets). At near-infrared to far-infrared wavelengths, ARXSED combines a clumpy medium and a homogeneous disk to account for the radiation from the torus.
    - 应用在20个射电噪的1 < z < 2的3CRR类星体上：We find that a single power-law is unable to fit the radio emission when compact radio structures (core, hot spots) are present. We find that the non-thermal emission from the quasars' radio structures contributes significantly (>70%) to the submm luminosity in half the sample

- [The 60-pc Environment of FRB 20180916B](https://arxiv.org/abs/2011.03257)
    - 149Mpc处，有精确定位以及16.35-day burst的FRB: GTC+HST观测
    - 对FRB所在区域可能的HII区的Halpha流量给出上限：The constraint on Hα suggests that possible stellar companions to FRB 20180916B should be of a cooler, less massive spectral type than O6V.
    - FRB 20180916B is 250 pc away (in projected distance) from the brightest pixel of the nearest young stellar clump 如果假定这个恒星形成区是FRB前身的诞生地的话，考虑到移动出HII区到现在位置的时间与磁星不符合。 Rather, the inferred age and observed separation are compatible with the ages of high-mass X-ray binaries and gamma-ray binaries, and their separations from the nearest OB associations.

- [New Horizons Observations of the Cosmic Optical Background](https://arxiv.org/abs/2011.03052)
    - **Interesting**
    - New Horizons LORRI camera to measure the optical-band (0.4≲λ≲0.9μm) sky brightness within seven high galactic latitude fields.
    - The average raw level measured while New Horizons was 42 to 45 AU from the Sun is 33.2±0.5 nW m−2 sr−1. This is ∼10× darker than the darkest sky accessible to the {\it Hubble Space Telescope}
    - We remove newly identified residual zodiacal light from the IRIS 100μm all sky maps to generate two different estimates for the diffuse galactic light (DGL).
    - 对结果的解释：Explaining it with undetected galaxies requires the galaxy-count faint-end slope to steepen markedly at V>24 or that existing surveys are missing half the galaxies with V<30

- [Detection of faint stars near SgrA* with GRAVITY](https://arxiv.org/abs/2011.03058)
    - We used GRAVITY to observe SgrA* over a period of six months in 2019 and employed interferometric reconstruction methods developed in radio astronomy to search for faint objects near SgrA*. 主要科学动机是找到比S2更靠近银心黑洞的恒星
    - This revealed a slowly moving star of magnitude 18.9 in K band within 30mas of SgrA*. The position and proper motion of the star are consistent with the previously known star S62, which is at a substantially larger physical distance, but in projection passes close to SgrA*.

- [LeMMINGs. II. The e-MERLIN legacy survey of nearby galaxies. The deepest radio view of the Palomar sample on parsec scale](https://arxiv.org/abs/2011.03062)
    - e-MERLIN观测：high-resolution (≤0.2 arcsec) 1.5-GHz radio images of 177 nearby galaxies from the Palomar sample
    - This large program is the deepest radio survey of the local Universe
    - We detect radio emission ≳0.25 mJy beam−1 for 125/280 galaxies (44.6 per cent) with sizes of typically ≲100 pc. Of those 125, 106 targets show a core which coincides within 1.2 arcsec with the optical nucleus.
    - Around one third of the detected galaxies features jetted morphologies.
    - LINERs and Seyferts are the most luminous sources, whereas HII galaxies are the least. LINERs show FRI-like core-brightened radio structures, while Seyferts reveal the highest fraction of symmetric morphologies.

- [Molecular hydrogen in IllustrisTNG galaxies: carefully comparing signatures of environment with local CO & SFR data](https://arxiv.org/abs/2011.03226)
    - TNG100 predicts that satellites with m∗≥10^9M⊙ should have a median deficit in their H2 fractions of ∼0.6 dex relative to centrals of the same stellar mass. Once observational and group-finding uncertainties are accounted for, the signature of this deficit decreases to ∼0.2 dex. 与xGOLD GASS的观测相符
    - We further show that TNG100 and SDSS data exhibit continuous declines in the average star formation rates of galaxies at fixed stellar mass in denser environments
    - By tracking satellites from their moment of infall in TNG100, we directly show that atomic hydrogen (HI) is depleted at fractionally higher rates than H2 on average. 在xGOLD样本中也的确看到了satellite星系中H2/HI质量比相对于central的升高

- [A Virgo Environmental Survey Tracing Ionised Gas Emission (VESTIGE). VIII. Modeling ram pressure stripping of diffuse gas in the Virgo cluster spiral galaxy NGC 4330](https://arxiv.org/abs/2011.03437)
    - We introduce a new version of the dynamical model that includes the diffuse ionized gas and aim to reproduce the HI, Hα, UV distributions together with the star formation histories of the outer gas-free parts of the galactic disk.
    - The inclusion of diffuse gas stripping changes significantly the HI, UV, and Hα emission distributions. The simulations with diffuse gas stripping naturally lead to vertical low surface density filaments in the downwind region of the galactic disk.
    - 有助于解释不通波段的辐射形态和SED：结论就是加入弥散气体成分很重要
    - Our preferred model yields a time to peak ram pressure of 140 Myr in the future. The spatial coincidence of the radio continuum and diffuse Hα tails suggests that both gas phases are stripped together.

----

### Nov 9

- [Redshift-space distortions in simulations of the 21-cm signal from the cosmic dawn](https://arxiv.org/abs/2011.03558)
    - Using our suite of fully numerical radiative transfer simulations, we investigate the impact on the redshifted 21-cm from the CD from one of these processes, namely the redshift-space distortions (RSDs).
    - When RSDs are added, the resulting boost to the power spectra makes the signal more detectable for our models at all redshifts, further strengthening hopes that a power spectra measurement of the CD will be possible.
    - The inclusion of RSDs, however, decreases detectability of the non-Gaussianity of fluctuations from inhomogeneous X-ray heating measured by the skewness and kurtosis

- [Constraining Reionization in Progress at z=5.7 with Lyman-α Emitters: Voids, Peaks, and Cosmic Variance](https://arxiv.org/abs/2011.03559)
    - We construct models of the LAE distribution in (1 Gpc/h)3 volumes, spanning a range of neutral fractions at z=5.7 and 6.6. Models with a higher neutral fraction show an enhanced probability of finding holes in the LAE distribution.
    - When comparing models at fixed mean surface density, however, LAEs obscured by neutral gas in the voids must be compensated by visible LAEs elsewhere.
    - Compared to the widely used angular two-point correlation function (2PCF), we find that the void probability function (VPF) provides a more sensitive test of models during the latter half of reionization.

- [On the Non-detection of Circular Polarisation from Repeating Fast Radio Bursts](https://arxiv.org/abs/2011.03960)
    - We draw attention to the non-detection of circularly polarised radio emission from repeating FRBs, and suggest that this could be a key discriminant of the origin of repeating and non-repeating FRBs.
    - We argue that if repeating FRBs are powered by fast rotating (e.g., sub-second) pulsars with ultra-strong magnetic fields, circular polarisation cannot be produced by propagation effects in the magnetosphere.
    - Alternatively, if repeating FRBs originate from slow rotating (e.g., second) pulsars, we argue that the lack of circular polarisation suggests that the emission comes from relatively high altitudes in the magnetosphere.

- [MOSAIC on the ELT: high-multiplex spectroscopy to unravel the physics of stars and galaxies from the dark ages to the present-day](https://arxiv.org/abs/2011.03549)
    - MOSAIC has a high multiplex in the NIR and in the VIS, in addition to multi-Integral Field Units (Multi-IFUs) in NIR.
    - MOSAIC will enable detailed maps of the intergalactic medium at z=3, the evolutionary history of dwarf galaxies during a Hubble time, the chemistry directly measured from stars up to several Mpc.

- [CLEAR: The Gas-Phase Metallicity Gradients of Star-Forming Galaxies at 0.6 < z < 2.6](https://arxiv.org/abs/2011.03553)
    - 264个CANDELS场里的星系的气态丰度：The majority of galaxies (84%) in this sample are consistent with a zero or slightly positive metallicity gradient across the full mass range probed (8.5 < log M_*/M_sun < 10.5).
    - We measure the intrinsic population scatter of the metallicity gradients, and show that it increases with decreasing stellar mass. We find no evidence for a correlation with the galaxy properties we consider---including star-formation rates, sizes, star-formation rate surface densities, and star-formation rates per gravitational potential energy.

- [Void Probability Function of Simulated Surveys of high-redshift Lyman-Alpha Emitters](https://arxiv.org/abs/2011.03556)
    - The VPF measures the zero-point correlation function (i.e. places devoid of galaxies) and naturally connects to higher order correlation functions while being computationally simple to calculate.
    - At small radii the accuracy of the VPF is limited by galaxy density, while at large radii the VPF is limited by the number of independent volumes probed.
    - The negative binomial model (NBM) has been shown to best describe the scaling between the two point correlation function and VPF for low-redshift galaxy observations.
    - LAEs show higher order clustering terms similar to those of normal low redshift galaxies.
    - 复习：VPF：Sometimes called the ‘zero-point’ correlation function (the average distance where no galaxies exist), the VPF ties theoretically to the higher order correlation functions (White 1979).
        - The count-in-cells statistic includes the VPF and information about several averaged correlation function moments, and appears to follow a predictable pattern of scaling due to gravity.
        - The VPF and two-point and higher order correlation functions are theoretically connected through this "hierarchical scaling", the idea that the first galaxies to form trace the first structures to collapse, following the evolution of Gaussian density fluctuations due to gravitational instabilities (Coil 2013).
        - The hierarchical scaling between the count-in-cells measured VPF and volume-averaged correlation functions has been found to follow the negative binomial model (NBM) in z < 1 galaxy surveys (e.g., Croton et al. 2004a; Conroy et al. 2005; Tinker et al. 2008) and in simulations (e.g., Andrew et al. 2013).
        - The VPF was found to be sensitive to Halo Occupancy Distribution (HOD) models with different minimum host masses where the two-point angular correlation function was not (Tinker et al. 2006; Berlind & Weinberg 2002)

- [Centrally concentrated molecular gas driving galactic-scale ionised gas outflows in star-forming galaxies](https://arxiv.org/abs/2011.03566)
    - 主要是看哪些星系能产生很强的星风：We observed CO(1-0) at 1" resolution with ALMA in 16 edge-on galaxies
    - We find that the galaxies powering outflows do not possess significantly different global gas fractions or star-formation efficiencies when compared with a control sample 但这些强星风星系中的分子气体分布得更集中
        - For our outflow-type objects, molecular gas and star-formation is largely confined within their inner effective radius (reff)
    - We infer that outflows in normal star-forming galaxies may be caused by dynamical mechanisms that drive molecular gas into their central regions, which can result in locally-enhanced gas surface density and star-formation.

- [Mass-radius relation of intermediate-age disk super star clusters of M82](https://arxiv.org/abs/2011.03594)
    - 基于EMACSS半解析模型的幸存分析研究：99 intermediate-age Super Star Cluster (SSCs) in the disk of M82
    - The SSCs follow a power-law mass function with an index α=1.5, and a log-normal size function with a typical half-light radius, Rh=4.3 pc, which are both comparable with the values for clusters in the Magellanic Clouds, rather than in giant spirals
    - A dynamical analysis of M82 SSCs using EMACSS suggests that 23% of the clusters are tidally-limited, with the rest undergoing expansion at present. 大部分都会在2Gyr内瓦解
    - A group of four massive compact clusters, and another group of five SSCs at relatively large galactocentric distances, are found to survive for a Hubble time.

- [The Sami Galaxy Survey: stellar populations of passive spiral galaxies in different environment](https://arxiv.org/abs/2011.03736)
    - **Relevant**
    - Our sample consists of 52 cluster passive spirals and 18 group/field passive spirals, as well as a set of S0s used as a control sample.
    - 基于Lick指数：the field/group passive spirals with log(M⋆/M⊙)≳10.5 show decreasing [α/Fe] along with stellar mass, which is ∼0.1 dex smaller than that of the cluster passive spirals.
    - Spiral和S0的比较，有环境差别：In the clusters, we find that passive spirals show slightly younger age and lower [α/Fe] than the S0s over the whole mass range. In the field/group, stellar populations show a similar trend between passive spirals and S0s
    - We relate the age and [α/Fe] of passive spirals to their mean infall time in phase-space; we find a positive correlation, in agreement with the prediction of numerical simulations

- [A new observation-based clumpy torus model for activate galactic nuclei](https://arxiv.org/abs/2011.03851)
    - We perform a broadband X-ray spectral analysis of a large unbiased sample of obscured AGN in the nearby universe which have high-quality archival NuSTAR data, enabling us to accurately characterize the physical and geometrical properties of their obscuring tori
    - We find that different types of AGN may possess similar tori, which are on average Compton thick (NH,tor,ave~1.4x10^24 cm^-2 ) and are significantly clumpy (e.g., for >80% of sources in our sample, their torus average column densities are more than three times different from their line-of-sight column densities). 并构建一个新的clumpy torus的模型

- [Metal-THINGS: On the metallicity and ionization of ULX sources in NGC 925](https://arxiv.org/abs/2011.04302)
    - A BPT analysis demonstrates that most spaxels in NGC 925 are dominated by star-forming regions, including those associated with ULX-1 and ULX-3
    - Interestingly, ULX-1 shows a very low gas metallicity for its galactocentric distance, identified by two independent methods, while exhibiting a typical ionization. We find that such low gas metallicity is best explained in the context of the high-mass X-ray binary population

- [A study of the HI gas fractions of galaxies at z ~ 1](https://arxiv.org/abs/2011.04500)
    - 用光学代理估计HI和恒星质量的比例，用来估计DEEP2星系的HIMF：It is found that the high mass end of high-z HI mass function (HIMF) is quite similar to that of the local HIMF.
    - Massive star-forming galaxies do not dominate the neutral gas at z ~ 1.
    - We study the evolution of the HI mass to stellar mass ratio from z ~ 1 to today and find a steeper relation between HI gas mass fraction and stellar mass at higher redshifts.
    - Specifically, galaxies with M_* = 10^{11} M_solar at z ~1 are found to have 3-4 times higher neutral gas fractions than local galaxies, while the increase is as high as 4-12 times at M_* = 10^{10} M_solar. 高红移星系的HI比例更高

- [Absorption-selected galaxies trace the low-mass, late-type, star-forming population at z∼2−3](https://arxiv.org/abs/2011.04557)
    - Our analysis reveals complex, irregular hosts with multiple star-forming clumps.
    - 40% of our absorption-selected sample requires multiple Sersic components for an accurate modelling of the observed galaxy light distributions. We measure half-light radii in the range r_1/2 ~ 0.4 - 2.6 kpc based on the reddest band (F160W) to trace the oldest stellar populations, and stellar masses in the range log M*[Msun] ~ 8 - 10 derived from spectral energy distribution (SED)
    - 大部分都是低质量恒星形成星系：we find that an absorption-selection at high redshift extends known relations determined from deep luminosity-selected surveys to an order of magnitude less massive galaxies, primarily composed of star forming late-types.

- [Multiple Stellar Evolution: a population synthesis algorithm to model the stellar, binary, and dynamical evolution of multiple-star systems](https://arxiv.org/abs/2011.04513)
    - **Impressive**
    - We present the population synthesis code Multiple Stellar Evolution (MSE), designed to rapidly model the stellar, binary, and dynamical evolution of multiple-star systems
    - MSE includes a number of new features not present in previous population synthesis codes: 1) an arbitrary number of stars, as long as the initial system is hierarchical, 2) dynamic switching between secular and direct N-body integration for efficient computation of the gravitational dynamics, 3) treatment of mass transfer in eccentric orbits, which occurs commonly in multiple-star systems, 4) a simple treatment of tidal, common-envelope, and mass transfer evolution in which the accretor is a binary instead of a single star, and 5) taking into account planets within the stellar system.

----

### Nov 10

- [C3-Cluster Clustering Cosmology II. First detection of the BAO peak in the three-point correlation function of galaxy clusters](https://arxiv.org/abs/2011.04665)
    - 用SDSS的72563 clusters: providing the first detection of the baryon acoustic oscillations (BAO) peak in the three-point correlation function (3PCF) of galaxy clusters
    - The data show clear evidence of the BAO peak in different configurations, which appears more visible in the reduced 3PCF rather than in the connected one

- [The ROSAT Raster Survey in the North-Ecliptic Pole Field: X-ray Catalogue and Optical Identifications](https://arxiv.org/abs/2011.04718)
    - ROSAT pointed and survey observations within 40 deg2 around the NEP: X-ray catalogue of 805 sources with 0.5-2 keV fluxes >2.9E-15 cgs, a factor of three deeper than the ROSAT All-Sky Survey
    - We find a new population of luminous absorbed X-ray AGN at large redshifts, not recognized in previous X-ray surveys
    - We also use the WISE and Spitzer photometry to identify a sample of 185 AGN selected purely through mid-IR colours, most of which are not detected by ROSAT.
    - HEROES (Songaila et al 2018): optical and NIR survey of 120 deg^2 of NEP using `grizy` HSC and MegaPrime/MegaCam + WIRCAM

- [AMICO galaxy clusters in KiDS-DR3: Evolution of the luminosity function between z=0.1 and z=0.8](https://arxiv.org/abs/2011.05131)
    - **Relevant**
    - 基于cluster星系LF的研究：We found a passive evolution with z for the bright part of the LF for the red and total populations and no significant trends for the faint galaxies.
    - The mass/richness dependence is clear for the density parameter Φ⋆, increasing with richness, and for the total population faint end, which is shallower in the rich clusters.

- [Discovering Strongly-lensed QSOs From Unresolved Light Curves](https://arxiv.org/abs/2011.04667)
    - Present a new method of discovering galaxy-scale, strongly-lensed QSO systems from unresolved light curves using the autocorrelation function
    - Among simulated lens systems for which time delays can be successfully measured by current best algorithms, our method achieves an overall true positive rate of 28--58% for doubly-imaged QSOs (doubles) and 36--60% for quadruply-imaged QSOs (quads) while maintains ≲10% false positive rates.

- [SDSS-IV MaNGA: Modeling the Spectral Line Spread Function to Sub-Percent Accuracy](https://arxiv.org/abs/2011.04675)
    - **SSST**
    - We present a major revision of the MaNGA data pipeline architecture, focusing particularly on a variety of factors impacting the effective LSF (e.g., undersampling, spectral rectification, and data cube construction).
    - Through comparison with external assessments of the MaNGA data provided by substantially higher-resolution R ~ 10,000 instruments we demonstrate that the revised MPL-10 pipeline measures the instrumental line spread function sufficiently accurately (<= 0.6% systematic, 2% random around the wavelength of Halpha) that it enables reliable measurements of astrophysical velocity dispersions sigma_Halpha ~ 20 km/s for spaxels with emission lines detected at SNR > 50.

- [Extended X-ray emission around FR II radio galaxies: hotspots, lobes and galaxy clusters](https://arxiv.org/abs/2011.04668)
    - 看3CR FRII射电星系附近的X-ray延展辐射：We found statistically significant extended emission (>3σ confidence level) along the radio axis for ∼90%, and in the perpendicular direction for ∼60% of our sample. We confirmed the detection of 7 hotspots in the 0.5 - 3 keV.
    - In the cases where the emission in the direction perpendicular to the radio axis is comparable to that along the radio axis, we suggest that the underlying radiative process is thermal emission from ICM. Otherwise, the dominant radiative process is likely non-thermal IC/CMB emission from lobes 非热辐射机制更重要

- [Galaxy Sizes Since z=2 from the Perspective of Stellar Mass Distribution within Galaxies](https://arxiv.org/abs/2011.04656)
    - **Relevant**
    - HST pixel-by-pixel SED fitting stellar mass map: These maps are used to derive radii encompassing 20%, 50%, and 80% (r20, r50 and r80) of the total stellar mass from the best-fit Sersic models.
    - At fixed mass, the star-forming galaxies do not show significant changes in their r20, r50 and r80 sizes, indicating self-similar growth. 大质量SF星系的r80有增长，说明有outskirt build-up; Sersic index有变化
    - Massive quiescent galaxies show stronger size evolution at all radii, in particular the r20 sizes. For these massive galaxies, Sersic values remain almost constant since at least z∼1.3, indicating that the strong size evolution is related to the changes in the outer parts of these galaxies.

- [The Rapid Build-up of Massive Early-type Galaxies. Supersolar Metallicity, High Velocity Dispersion and Young Age for an ETG at z=3.35](https://arxiv.org/abs/2011.04657)
    - **Relevant**
    - LBT观测C1-23152, an ETG at redshift z=3.352：有AGN；恒星质量接近2x10^11 Msun; 有超高的恒星速度弥散度
    - The stellar population has a mean mass-weighted age 400+30−70 Myr and it is formed between ∼600 Myr and ∼150 Myr before the observed epoch, this latter being the time since quenching
    - The analysis points toward a supersolar metallicity, [Z/H]=0.25+0.006−0.10; 超高效率的恒星形成
    - 而且quenching非常有效：Quenching must have been extremely efficient to reduce the star formation to SFR<6.5 M⊙ yr−1 in less than 150 Myr. This could be explained by the presence of the AGN
        - **Thoughts**: what if it is not quenched, but just in a brief suppresed phase?

- [Formation of the largest galactic cores through binary scouring and gravitational wave recoil](https://arxiv.org/abs/2011.04663)
    - **Relevant, Interesting**
    - 用模拟看椭圆星系中大尺度的core的形成：we run a suite of dry galaxy merger simulations to explore three different scenarios for central core formation in massive elliptical galaxies: 'binary scouring', 'tidal deposition' and 'gravitational wave (GW) induced recoil'.
    - We find that we can only explain the large surface brightness core of A2261-BCG with a combination of a major merger that produces a small ~1kpc core through binary scouring, followed by the subsequent GW recoil of its SMBH that acts to grow the core size.
    - 重要的预测：这种情形下应该会有偏心的SMBH，且周围有致密的星团
    - 模拟技术：griffin Fast Multiple Method (Dehnen 2002, 2014).

- [L-GALAXIES 2020: The evolution of radial metallicity profiles and global metallicities in disc galaxies](https://arxiv.org/abs/2011.04670)
    - **Important**
    - 主要的改变是在CGM的增丰效率上：includes significantly increased direct metal enrichment of the circumgalactic medium (CGM) by supernovae (SNe). These more metal-rich outflows do not require increased mass-loading factors, in contrast to some other galaxy evolution models.
    - In addition, a lowered maximum SN-II progenitor mass of 25M⊙, reflecting recent theoretical and observational estimates, can also provide a good match to observed metallicity profiles at z=0

- [MAGNUM survey: compact jets causing large turmoil in galaxies -- Enhanced line widths perpendicular to radio jets as tracers of jet-ISM interaction](https://arxiv.org/abs/2011.04677)
    - **Interesting**
    - We study the relation between radio jets and ionised gas distribution and kinematics in IC 5063, NGC 5643, NGC 1068 and NGC 1386 之前有观测显示这些星系中低动能的jet (<10^44 erg/s)也可以产生外流
    - MUSE观测：We detect a strong (up to ≳800−1000 km/s), extended (≳1 kpc) and shock-excited emission-line velocity width enhancement perpendicularly to the AGN ionisation cones and jets in all the four targets 但和一般的外流不同，Such broad, symmetric line profiles are not associated with a single coherent net velocity of the gas
    - 更像是AGN jet扰动了星系盘上的气体：such extended line width enhancement perpendicular to AGN cones and jet is observed only in galaxies hosting a low-power jet whose inclination is low enough on the galaxy disc to strongly impact on its material, as also recent simulations predict.

- [Virial shocks are suppressed in cosmic ray-dominated galaxy halos](https://arxiv.org/abs/2011.04706)
    - 基于FIRE-II的模拟：In massive (Mhalo≳1011M⊙), low-redshift (z≲1−2) halos, which are expected to form "hot halos" with slowly-cooling gas in quasi-hydrostatic equilibrium (with a stable virial shock), our simulations without CRs do exhibit clear virial shocks.
    - With CRs, we previously argued that halos in this particular mass and redshift range build up CR-pressure-dominated gaseous halos. Here, we show that when CR pressure dominates over thermal pressure, there is no significant virial shock. Instead, inflowing gas is gradually decelerated by the CR pressure gradient and the gas is relatively subsonic out to and even beyond Rvir.

- [The SAMI Galaxy Survey: bulge and disk stellar population properties in cluster galaxies](https://arxiv.org/abs/2011.04873)
    - The analysis of the g−i colors reveals that bulges are redder than their surrounding disks with a median offset of 0.12±0.02 mag
    - We observe 23% of galaxies being characterized by bulges older and 34% by bulges younger with respect to the disks. The remaining 43% of galaxies have bulges and disks with statistically indistinguishable ages.

- [The properties of dwarf spheroidal galaxies in the Cen A group: Stellar populations, internal dynamics, and a heart-shaped Halpha ring](https://arxiv.org/abs/2011.04990)
    - We use MUSE spectroscopy to study the properties of 14 known or suspected dSph satellites of Cen A. 12个是group member
    - The 12 confirmed dSph members of the Cen A group have old and metal-poor stellar populations and follow the stellar metallicity-luminosity relation defined by the dwarf galaxies in the Local Group
    - 在三个最亮的矮星系中找到了球状星团
    - In the dwarf KK 203 we find an extended Halpha ring.

----

### Nov 11

- [CWITools: A Python3 Data Analysis Pipeline for the Cosmic Web Imager Instruments](https://arxiv.org/abs/2011.05444)
    - We present CWITools, a package written in Python3 for the analysis of PCWI and KCWI data. CWITools is designed to provide a pipeline between the output of the standard instrument data reduction pipelines and scientific products such as surface brightness maps, spectra, velocity maps, as well as a wide array of associated models and measurements.

- [ETHOS -- An Effective Theory of Structure Formation: Impact of Dark Acoustic Oscillations on Cosmic Dawn](https://arxiv.org/abs/2011.05333)
    - Focusing on the Effective Theory of Structure Formation (ETHOS) paradigm, we run a suite of simulations covering a broad range of DM microphysics, connecting the output of N-body simulations to dedicated 21-cm simulations to predict the evolution of the 21-cm signal across the entire cosmic dawn.
    - We find that observatories targeting both the global signal and the 21-cm power spectrum are sensitive to all ETHOS models we study, and can distinguish them from CDM if the suppression wavenumber is smaller than k≈300h/Mpc, even when accounting for feedback with a phenomenological model.

- [First detection of stacked X-ray emission from cosmic web filaments](https://arxiv.org/abs/2011.05343)
    - **Interesting**
    - 基于ROSAT和SDSS数据：We selected 15,165 filaments at 0.2< z<0.6 ranging from 30 Mpc to 100 Mpc in length
    - 扣除了星系团和有探测的点源后的叠加：The stacked signal results in the detection of the X-ray emission from the cosmic filaments at a significance of 4.2 sigma in the energy band of 0.56-1.21 keV.
    - We show that stacking the SRG/eROSITA data for ~2,000 filaments only would lead to a ~5 sigma detection of their X-ray signal, even with an average gas temperature as low as ~0.3 keV.

- [BeyondPlanck I. Global Bayesian analysis of the Planck Low Frequency Instrument data](https://arxiv.org/abs/2011.05609)
    - https://beyondplanck.science/ 

- [Testing the theory of gravity with DESI: estimators, predictions and simulation requirements](https://arxiv.org/abs/2011.05771)

- [Evidence for hierarchical black hole mergers in the second LIGO--Virgo gravitational-wave catalog](https://arxiv.org/abs/2011.05332)
    - Using a phenomenological population model, we infer the mass and spin distribution of first-generation black holes, while searching for hierarchical mergers. Considering a range of cluster masses, we see compelling evidence for hierarchical mergers for clusters with escape velocities ≳100 kms−1.
    - In this case, we find that 99% of black holes from the inferred total population are less than 48M⊙, and that this constraint is robust under our choice of prior on the maximum black hole mass.

- [Confrontation of Observation and Theory: High Frequency QPOs in X-ray Binaries, Tidal Disruption Events, and Active Galactic Nuclei](https://arxiv.org/abs/2011.05346)
    - We find that supermassive black holes occupy a separate region of parameter space than stellar, and further, that QPOs seen around tidal disruption events rather than Seyfert-type AGN occupy an entirely different space.
    - SMBH附近的QPO不能用解释恒星质量黑洞QPO的模型来描述，包括  orbital resonance, diskoseismic, warped disk, and disk-jet coupling theoretical models
    - Oscillations seen in tidal disruption events are consistent with oscillations near the frequency of the innermost stable circular orbit (ISCO), while QPOs in AGN are not accounted for by any of the physical models in consideration.

- [The galaxy-halo connection of emission-line galaxies in IllustrisTNG](https://arxiv.org/abs/2011.05331)

- [Outflows from Super Star Clusters in the Central Starburst of NGC253](https://arxiv.org/abs/2011.05334)

- [The COS Absorption Survey of Baryon Harbors: Unveiling the Physical Conditions of Circumgalactic Gas through Multiphase Bayesian Ionization Modeling](https://arxiv.org/abs/2011.05335)

- [Galaxy formation with L-GALAXIES: Modelling the environmental dependency of galaxy evolution and comparing with observations](https://arxiv.org/abs/2011.05336)

- [Fast rotating and low-turbulence discs at z≃4.5: dynamical evidence of their evolution into local early-type galaxies](https://arxiv.org/abs/2011.05340)

- [EMERGE: Constraining merging probabilities and timescales of close galaxy pairs](https://arxiv.org/abs/2011.05341)

- [INSPIRE: INvestigating Stellar Population In RElics -- I. Survey presentation and pilot program](https://arxiv.org/abs/2011.05347)

- [Dynamical masses of brightest cluster galaxies II: constraints on the stellar IMF](https://arxiv.org/abs/2011.05350)

- [The Evolution of the Low-Frequency Radio AGN Population to z≃1.5 in the ELAIS N1 Field](https://arxiv.org/abs/2011.05412)

- [Dust Temperature of Compact Star-forming Galaxies at z∼1−3 in 3D-{\it HST}/CANDELS](https://arxiv.org/abs/2011.05528)

- [The multiphase and magnetized neutral hydrogen seen by LOFAR](https://arxiv.org/abs/2011.05647)

- [Monitoring AGNs with Hβ Asymmetry. II. Reverberation Mapping of Three Seyfert Galaxies Historically Displaying Hβ Profiles with Changing Asymmetry: Mrk 79, NGC 3227, and Mrk 841](https://arxiv.org/abs/2011.05902)

- [SED Analysis of 47 Spectroscopically Confirmed Galaxies at z≃6 to Constrain Possible Relationships between UV Slope, Dust attenuation, and Escape Fraction](https://arxiv.org/abs/2011.05902)

- [X-ray redshifts for obscured AGN: a case study in the J1030 deep field](https://arxiv.org/abs/2011.05983)
