# Halo Overlap Watch — 2026-10-07 16:45 ICT

## Task

Check current astronomy and astrophysics literature for genuinely new observational or methodological work bearing on the fixed discriminator:

`observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution → positive residual`

The proposed correspondence remains that overlapping coarse anchored regions in merging galaxy clusters may produce additional shared seating beyond simple additive halo superposition.

## Framework source check

The current stable wording in `source/where-the-framework-stands.md` and `source/evidence-and-interpretation.md` was checked against the repository. The fixed-primitive and anti-drift guardrails remain in force. Ordinary halo overlap, a bridge, elongation, filament, or an extra subcluster does not count as support by itself. The physical mapping remains **Candidate Correspondence**, with magnitude and detectability still incomplete.

## Search scope and themes checked

Literature available through 2026-10-07 16:45 ICT was checked, emphasizing the Wednesday 2026-10-07 arXiv intake and material not present in the 2026-10-06 run.

Categories and themes screened:

- current `astro-ph.CO`, `astro-ph.GA`, `astro-ph.IM`, and `astro-ph.HE` listings;
- merging-cluster weak- and strong-lensing reconstruction;
- convergence and mass residual maps;
- two-halo subtraction or marginalization;
- overlap-region and mass-bridge analyses;
- explicit baryonic decomposition;
- line-of-sight, PSF, source-selection, and reconstruction systematics;
- stacked or multi-cluster methods that could improve sensitivity to non-additive overlap mass.

Queries/themes included:

- `site:arxiv.org/abs/2610 galaxy cluster weak lensing merger mass map`
- `site:arxiv.org/abs/2610 cluster strong lensing mass model JWST`
- `site:arxiv.org/abs/2610 intracluster filament weak lensing`
- `site:arxiv.org/abs/2610 merging galaxy cluster gravitational lensing`
- `galaxy cluster lensing merger residual mass bridge October 2026`
- direct title/abstract screening of the 2026-10-07 arXiv category listings.

Primary listings:

- [arXiv new astro-ph.CO submissions](https://arxiv.org/list/astro-ph.CO/new)
- [arXiv new astro-ph.GA submissions](https://arxiv.org/list/astro-ph.GA/new)
- [arXiv new astro-ph.IM submissions](https://arxiv.org/list/astro-ph.IM/new)
- [arXiv new astro-ph.HE submissions](https://arxiv.org/list/astro-ph.HE/new)

## Meaningful development

### Saha et al., “Lensing in the Blue IV: The First Weak Gravitational Lensing Maps from the Stratosphere”

- **arXiv:** [2610.07244](https://arxiv.org/abs/2610.07244)
- **Submitted:** 2026-10-05
- **Listed in the current intake:** 2026-10-07
- **Classification:** **Methodological advance**

### What was measured

The SuperBIT collaboration produced weak-lensing convergence maps from balloon-borne, near-space-quality imaging for six galaxy clusters selected from 30 observed targets:

- Abell 2384 (north);
- Abell 3411;
- Abell 1689;
- Abell S0592 / SPT-CLJ0638-5358;
- 1E 0657-56 / the Bullet Cluster;
- PLCK G287.0+32.9.

Most of the sample consists of merger or merger-candidate systems. The work includes the first published gravitational-lensing mass map of Abell S0592 and an independent map of the Bullet Cluster.

The pipeline:

- measures and metacalibrates background-galaxy shapes;
- separates foreground and background galaxies with three-band color information;
- reconstructs `κ_E` convergence through Kaiser–Squires inversion;
- generates 1,000 randomized-shape noise realizations per target;
- uses `κ_B` as a null test for residual observational systematics;
- compares the mass maps with Chandra X-ray emission and red-sequence cluster-member density.

Reported peak `κ_E` signal-to-noise values range from 5.35 to 7.06. For the Bullet Cluster the two lobes reach 5.43 and 4.69.

Full paper: [arXiv HTML](https://arxiv.org/html/2610.07244v1)

### Were additive halos and baryons accounted for?

**No.**

The paper reconstructs total projected convergence and compares it morphologically with X-ray gas and member-galaxy density. It does not:

1. fit and subtract halo A and halo B;
2. convert the X-ray or galaxy tracers into and subtract a complete ordinary baryonic mass model;
3. isolate a pre-defined overlap aperture;
4. measure a residual mass or convergence after those components;
5. report a residual significance, upper bound, or null constraint for the fixed discriminator.

No structure in these maps is therefore counted as a Direct match or Partial / suggestive correspondence.

### Why this materially advances the test

This is a new, independent weak-lensing dataset and validated reconstruction pipeline applied directly to several merging systems. It expands the pool of convergence maps on which a fixed two-halo-plus-baryon residual analysis could be run. Abell S0592 is especially useful because it now has its first lensing mass map, while the Bullet Cluster supplies a cross-instrument reconstruction of a benchmark merger.

The combination of `κ_E` maps, randomized-shape noise ensembles, `κ_B` null maps, X-ray comparisons, and member-galaxy maps provides several ingredients needed to distinguish a genuine overlap residual from shape noise, PSF leakage, or ordinary baryonic structure. The full 30-cluster SuperBIT sample now in preparation could later support a pre-registered stacked residual test.

### Strongest caveats

- The six clusters were selected for strong reconstructed `κ_E` signal, not as an unbiased merger sample.
- Selection cuts were tuned per target to maximize the `κ_E` peak while minimizing nearby `κ_B`, which is reasonable for proof-of-concept detection but must be handled carefully in any residual-significance analysis.
- The field was cropped to the central approximately 50% because roll instability produced elongated PSFs near the edges.
- The maps are smoothed and have modest source density, limiting sensitivity to low-amplitude, spatially localized residuals.
- No parametric halo decomposition, complete baryonic mass model, overlap aperture, or non-additivity estimator was applied.

## Other current entries screened

- **Ayromlou et al., “And Then There WEre Baryons (ATWEB),” arXiv:2610.07140.** This simulation study introduces baryon closure and compensation scales and relates them to recovery of the gravity-only matter distribution. It is relevant background for how baryons redistribute mass around halos, but it does not study merging-cluster overlap residuals or provide the required observational decomposition.
- Current `astro-ph.GA`, `astro-ph.IM`, and `astro-ph.HE` entries and replacements were screened for cluster lensing, convergence residuals, merger bridges, halo decomposition, and mass reconstruction. No second new result completed or directly constrained the fixed discriminator.

## Final status

**Status: Meaningful methodological advance**

SuperBIT has supplied a new independent set of weak-lensing convergence maps for six clusters, including multiple mergers, the first lensing map of Abell S0592, and a new Bullet Cluster map. This improves the observational substrate for the fixed test but does not itself execute it.

Classification: **Methodological advance**

Framework status: **Candidate Correspondence**

The empirical goalposts were not changed. No new Direct match, Partial / suggestive correspondence, Constraint on magnitude, Weakening evidence, or Conventional explanation was identified in this intake.
