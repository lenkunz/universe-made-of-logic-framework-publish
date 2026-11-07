# Halo Overlap Watch — 2026-11-07 16:10 Asia/Bangkok

- **Task:** Halo Overlap Watch
- **Run timestamp:** 2026-11-07 16:10:43 Asia/Bangkok
- **Repository:** `lenkunz/universe-made-of-logic-framework-publish`
- **Fixed discriminator:** `observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution → positive residual`
- **Final status:** Meaningful development; framework status unchanged.
- **Framework status:** **Candidate Correspondence**

## Framework source check

Read the current default-branch sources:

- `source/a-universe-made-of-logic.md`, section “Overlap without simple superposition”
- `source/where-the-framework-stands.md`
- `source/evidence-and-interpretation.md`
- `source/changes/2026-09-08-budget-warped-perception-gravity-and-cosmology.md`

The stable source says that if overlap requires additional shared seating beyond simple additive superposition, the observable target is a positive overlap-correlated residual after halo A, halo B, and ordinary baryonic contributions are accounted for. The existence and magnitude of that excess remain unestablished. No source change justifies moving the empirical goalposts.

## Search scope and queries/themes checked

Checked current astronomy/astrophysics literature, including arXiv new listings through Friday 2026-11-06 and recent journal records. Priority themes:

- merging galaxy clusters and multi-component merger cores;
- weak-lensing convergence maps and strong-lensing mass models;
- shear-plus-flexion reconstruction and small-scale substructure sensitivity;
- inter-clump / overlap-region convergence peaks;
- explicit multi-halo fits and post-fit residuals;
- X-ray / ICM and other baryonic component accounting;
- stacked merger residual maps and methods that could improve sensitivity to a non-additive excess.

Representative search themes included: `El Gordo flexion convergence central peak`, `cluster shear flexion substructure reconstruction`, `merging cluster overlap convergence residual halo subtraction`, `strong lensing X-ray baryon decomposition cluster merger`, and `weak lensing flexion method cluster density profile`.

## Meaningful findings

### 1. Shpiece & Goldberg — *Adaptive Reconstruction of Cluster Halos (ARCH): Integrating Shear and Flexion for Substructure Detection*

- **Publication:** *The Astrophysical Journal* 1003(2), 171; published 2026-06-01.
- **Preprint:** arXiv:2509.21686; v2 revised 2026-04-29.
- **DOI:** https://doi.org/10.3847/1538-4357/ae681a
- **What was measured:** ARCH combines weak-lensing shear with first and second flexion from JWST imaging, using staged candidate generation, local optimization, filtering, forward selection, and global strength refinement. It was applied to Abell 2744 and the merging cluster El Gordo. In El Gordo it recovers the familiar northwestern and southeastern clumps with masses around (2.6\times10^{14}) and (2.3\times10^{14},M_\odot h^{-1}), respectively. Flexion-inclusive reconstructions also show a weaker convergence peak roughly midway between the two dominant clumps.
- **Classification:** **2. Partial / suggestive correspondence**. The same paper is also a meaningful **4. Methodological advance** because it demonstrates that shear-anchored flexion can improve sensitivity to cluster substructure and produce stable cluster-scale mass recovery.
- **Why it matters:** The reported inter-clump peak is an overlap-associated feature in a real merging-cluster reconstruction, not merely a generic bridge mentioned in passing. It gives a concrete target for a stricter residual analysis and shows that adding flexion can expose structure that shear-only maps may not resolve as clearly.
- **Were additive halo/baryonic components accounted for in the required discriminator?** **No.** ARCH fits a sparse set of NFW/SIS lens candidates and reconstructs convergence maps, but it does not publish the required statistic `observed overlap − fitted NW halo − fitted SE halo − ordinary baryons`. It does not explicitly subtract an ICM/stellar baryon model from the central peak.
- **Strongest caveat:** The authors explicitly say the central El Gordo peak is ambiguous. It could be a genuine intra-cluster overdensity, but it could also be an artificial convergence maximum created by superposition of the shear and flexion signals from the NW and SE clumps. The paper calls for simulation comparison and additional observational constraints. This is therefore not evidence of a non-additive residual yet.

### 2. Sun, Zhang & Futamase — *GradFlex: a Gradient-Based Method for Weak Lensing Flexion Measurement*

- **Submission:** 2026-11-05.
- **Preprint:** arXiv:2611.07824.
- **What was measured/developed:** A new flexion estimator derived from gradients of galaxy surface-brightness fields and spin-statistic ensemble averages. It aims to extract first and second flexion without assuming a specific PSF model or galaxy morphology. The paper tests simulated regular and irregular galaxies under PSF convolution and noise, using an NFW cluster lens.
- **Classification:** **4. Methodological advance (early-stage)**.
- **Why it matters:** Flexion probes local gradients of convergence/shear and can complement shear in resolving small-scale density structure. A more robust flexion estimator could eventually improve the spatial discrimination of an overlap-region residual.
- **Were additive halo/baryonic components accounted for?** **No.** This is a measurement-method paper, not a merger analysis or a halo-plus-baryon residual test.
- **Strongest caveat:** The validation is simulation-based, not an observed merging-cluster application. The authors state that their current perturbative approximations omit higher-order terms such as (gamma^2) and (gamma\mathcal{F}), which become important in high-shear cluster centers; calibration and contamination from foreground/neighboring sources remain future work. It is promising but not yet demonstrated as a reliable overlap-residual measurement.

## Other relevant work screened but not promoted

- **Iqbal et al.,** *Probing the baryonic–dark matter connection in galaxy clusters using X-rays with gated recurrent unit neural networks*, arXiv:2607.20721 (submitted 2026-07-22; surfaced as a replacement in the 2026-11-06 arXiv listing). The GRU predicts 3D total-mass profiles from spherically averaged ICM profiles, with about 5% scatter in simulation tests and applications to REXCESS/X-COP. This may help cluster mass calibration, but spherical averaging does not resolve a merging pair's 2D overlap geometry, and it does not subtract baryons from a lensing residual. **Not counted as a material advance for this specific discriminator.**
- **Limousin et al.,** *SLICE: Combining strong lensing and X-ray data of AC 114*, arXiv:2512.09512; A&A 711, A143, published 2026-07-08. Joint strong-lensing/X-ray modeling supports a late post-collisional merger and suggests the companion AC 114b has been stripped of hot gas. It does not measure a post-subtraction overlap residual. **Not counted as a direct or partial match.**
- **Kim et al.,** *Weak-lensing Analysis of the Galaxy Cluster A85*, ApJ 1003 (2026), article 16, published 2026-05-20. It fits a multihalo NFW model to the main, southern, and southwestern components. This is useful decomposition context, but no predefined post-subtraction overlap statistic is reported; it was already recorded in the 2026-11-04 watch archive.
- **Saha et al.,** *Lensing in the Blue III: Weak Lensing Shape Catalogs of 30 Merging Galaxy Clusters*, arXiv:2603.18376 / ApJ 1011 (2026), and **Shi & Cui**, *Nonlinear Weak Lensing Reconstruction for Galaxy Clusters*, arXiv:2601.02816 / PRD 113, 103514, were checked as previously known data/method resources. Neither is a new post-subtraction overlap result in this run.
- **Chen et al.,** *Mapping Dark Matter in Merging Clusters with Weak Lensing for CSST: Morphology and Filament Recovery*, arXiv:2610.17857, remains a previously recorded simulated halo-pair/filament reconstruction, not a post-subtraction non-additive residual.

## Additive-component accounting

No paper examined in this run computes the full required decomposition:
`observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution`.

ARCH's central El Gordo peak is visible in a flexion-inclusive reconstructed convergence map, but the authors themselves identify ordinary signal superposition as a possible explanation. No ICM/stellar subtraction or statistically defined residual remains after the two dominant halos are removed. GradFlex is a measurement method only.

## Final assessment

The most important development is the ARCH inter-clump peak in El Gordo, enabled by shear-plus-flexion reconstruction. It is **notification-worthy as a Partial / suggestive correspondence**, and the reconstruction pipeline is also a meaningful methodological advance. The new GradFlex preprint is an additional early-stage method that could improve future small-scale tests.

Neither result is a Direct match. The central peak may be a conventional superposition/reconstruction feature, and the required baryonic accounting is absent.

**Final status:** Meaningful methodological and partial/suggestive development; no direct confirmation.

**Framework status:** **Candidate Correspondence remains unchanged.** The original discriminator and empirical goalposts are preserved.
