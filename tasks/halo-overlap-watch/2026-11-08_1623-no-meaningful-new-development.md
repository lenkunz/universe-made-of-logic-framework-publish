# Halo Overlap Watch — 2026-11-08 16:23

- **Task:** Halo Overlap Watch
- **Run timestamp:** 2026-11-08 16:23:57 Asia/Bangkok
- **Repository:** `lenkunz/universe-made-of-logic-framework-publish`
- **Branch:** `main` (default branch)
- **Fixed discriminator:** `observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution → positive residual`
- **Status:** No meaningful new development
- **Framework status:** **Candidate Correspondence** (unchanged)

## Framework source check

Read the current default-branch semantic sources before assessing the literature:

- `source/README.md`
- `source/a-universe-made-of-logic.md`, especially “Overlap without simple superposition”
- `source/where-the-framework-stands.md`
- `source/evidence-and-interpretation.md`
- `source/changes/2026-09-08-budget-warped-perception-gravity-and-cosmology.md`
- `source/changes/2026-09-11-ontology-conditioned-evidence.md`
- `source/changes/2026-09-11-seated-relation-attention-and-stage-resolution.md`

The stable source keeps the empirical target fixed: if overlap requires additional shared seating beyond simple additive superposition, then observed overlap minus halo A, halo B, and ordinary baryonic contribution should leave a positive overlap-correlated residual. The same source says the existence and size of that excess are not established. `source/where-the-framework-stands.md` lists the halo-overlap prediction as a candidate and records its magnitude/detectability as pending. The evidence guardrail also says that a possibility permitted by the ontology is not enough to establish that it caused an observation.

No source revision was found that changes the prediction or justifies moving the empirical goalposts.

## Search scope and queries/themes checked

Checked current astronomy/astrophysics literature through 2026-11-08, using the latest available arXiv new-submission listings (Friday 2026-11-06 for `astro-ph.CO` and `astro-ph.GA`), recent journal publication records, and targeted searches.

Themes:
- merging-cluster weak- and strong-lensing mass maps;
- convergence peaks in inter-clump / overlap regions;
- fitted multi-halo profiles and post-fit residuals;
- ordinary ICM gas, stellar, and other baryonic mass accounting;
- stacked merger residual maps and mass bridges;
- shear-plus-flexion reconstruction and substructure sensitivity;
- cluster-centering, member/interloper contamination, and mass-model systematics.

Representative queries:
- `merging cluster weak lensing overlap convergence residual halo subtraction`
- `cluster merger strong lensing residual map baryonic mass decomposition`
- `inter-clump convergence peak fitted NFW halos superposition`
- `stacked merging clusters lensing residual mass bridge`
- `weak lensing flexion new method cluster substructure November 2026`
- `galaxy cluster lensing mass reconstruction November 6 2026`

## Findings

### Previously recorded relevant work rechecked, not new in this run

#### Sun, Zhang & Futamase — *GradFlex: a Gradient-Based Method for Weak Lensing Flexion Measurement*

- **Preprint:** arXiv:2611.07824
- **Submission date:** 2026-11-05
- **Prior watch record:** 2026-11-07 archive
- **Classification retained:** **4. Methodological advance (early-stage)**, already surfaced in the previous run.
- **What it does:** Estimates first and second flexion from galaxy surface-brightness gradient statistics. Validation uses simulated regular and irregular galaxies, PSF convolution, noise, and an NFW cluster lens.
- **Additive halo/baryonic accounting:** None. It is a measurement-method paper, not a merger mass decomposition.
- **Caveat:** The authors state that first-order perturbative approximations omit higher-order terms such as `gamma^2` and `gamma F`, which become important in high-shear cluster centers. Calibration and foreground/neighbor-source contamination remain future work.
- **Assessment this run:** No new version or observational merger application was found after the previous watch. It remains a promising but unvalidated input method for the specific overlap test, not a new development today.

#### Shpiece & Goldberg — *Adaptive Reconstruction of Cluster Halos (ARCH): Integrating Shear and Flexion for Substructure Detection*

- **Preprint:** arXiv:2509.21686 (2025-09-25)
- **Journal:** The Astrophysical Journal 1003(2), 171; published 2026-06-01
- **DOI:** 10.3847/1538-4357/ae681a
- **Prior watch record:** 2026-11-07 archive
- **Classification retained:** **2. Partial / suggestive correspondence**, plus **4. Methodological advance** for shear-anchored flexion reconstruction; already surfaced in the previous run.
- **What it reports:** A weaker convergence peak approximately midway between El Gordo's NW and SE clumps, recurring in flexion-inclusive reconstructions.
- **Additive halo/baryonic accounting:** The required subtraction is not performed. The authors explicitly state that the peak could be a genuine intra-cluster overdensity or an artificial maximum caused by superposition of the NW/SE shear and flexion signals. No ordinary ICM/stellar baryonic model is subtracted from this feature.
- **Assessment this run:** Full-text recheck confirms the ambiguity. This is not a newly published result today and does not become a direct match.

### Newly surfaced adjacent work screened but not promoted

#### Wang et al. — *A Deep Learning Approach to Member Identification and Mass Estimation in Galaxy Clusters*

- **Preprint:** arXiv:2610.39546 (submitted 2026-10-29)
- **Journal publication:** Astronomy & Astrophysics 715, A185; published online 2026-11-06
- **DOI:** 10.1051/0004-6361/202662195
- **What it does:** Uses an LSTM to assign probabilistic galaxy membership in projected phase space and a Bayesian neural network to infer dynamical cluster masses. The reported membership weighting reduces the fiducial estimator's residual scatter by 19.5%; using the BCG rather than the gravitational center can lower inferred mass by up to 47.6%.
- **Additive halo/baryonic accounting:** No lensing convergence map, no merging-pair halo A/B fit, and no baryonic subtraction.
- **Category considered:** **4. Methodological advance** for dynamical member selection/mass estimation in its own domain, but it does not materially improve the specific two-dimensional lensing overlap-residual test. It is not promoted as a watch development.
- **Strongest caveat:** The reported method concerns dynamical mass estimation and does not demonstrate performance on merging-cluster lensing residuals.

#### *A New H0 Measurement with Supernovae Requiem and Encore Using Gravity.jl*

- **Journal publication:** Astronomy & Astrophysics, online 2026-11-06
- **What it does:** Presents a strong-lensing model of MACS J0138.0−2155 using 23 spectroscopically confirmed multiple images from eight background sources; the reported image-plane RMS is 0.15 arcsec.
- **Additive halo/baryonic accounting:** No target-specific merging-pair subtraction or overlap residual.
- **Assessment:** Strong-lensing modeling of a cluster lens, but not a merging-cluster overlap test or a method shown to materially improve this discriminator. Not promoted.

#### Other current-listing checks

- The latest `astro-ph.CO` and `astro-ph.GA` new-submission listings through Friday 2026-11-06 were reviewed. No newly listed merging-cluster paper reports a post-subtraction overlap convergence residual.
- The SuperBIT 30-merging-cluster weak-lensing catalog, the BUFFALO Abell 2744 subhalo-mass-function analysis, and previously recorded cluster reconstruction work were recognized as existing watch context, not counted as new developments in this run.
- The BUFFALO Abell 2744 substructure excess is a projected subhalo-abundance comparison against BAHAMAS simulations, interpreted by its authors as likely associated with the cluster's unusually disturbed merger state. It is not the pairwise residual after subtracting two fitted halos and baryons, and it was already archived on 2026-10-10.

## Additive-component accounting

**No newly identified study in this run computes the required decomposition:**

`observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution`

The previously recorded ARCH inter-clump peak remains ambiguous because ordinary shear/flexion signal superposition is explicitly offered as an explanation. GradFlex is a flexion estimator only. The new member-selection/mass-estimation paper is dynamical rather than lensing-based. No new result reports a statistically meaningful positive residual, a constraining null, or a magnitude bound after both fitted halos and ordinary baryons are accounted for.

## Final assessment

**Status: No meaningful new development**

The latest arXiv listings and recent journal records were checked. The only very recent directly relevant flexion method and the ARCH El Gordo inter-clump feature were already recorded in the 2026-11-07 run; rechecking them did not produce a new observation, validation, residual subtraction, or change in classification. Newly published adjacent cluster mass-estimation work does not materially improve the specified lensing discriminator.

**Framework status:** **Candidate Correspondence remains unchanged.** The original empirical discriminator is preserved.
