# Halo Overlap Watch — 2026-10-04 16:15 ICT

## Task

Check current astronomy and astrophysics literature for genuinely new observational or methodological work bearing on the fixed discriminator:

`observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution → positive residual`

The proposed correspondence remains that overlapping coarse anchored regions in merging galaxy clusters may produce additional shared seating beyond simple additive halo superposition.

## Framework source check

The current stable repository wording under `source/`, the current `source/changes/` ledger, and the prior Halo Overlap Watch archives were checked. The empirical target was not changed.

The guardrail remains:

- ordinary halo overlap, a bridge, elongation, or filament is not support by itself;
- a relevant signal must survive modeling/subtraction of both ordinary halos, ordinary baryons, projection, and reconstruction systematics;
- the gravity/dark-sector mapping remains a **Candidate Correspondence**.

## Search scope

Checked literature available through 2026-10-04 16:15 ICT, with emphasis on material not previously archived:

- arXiv `astro-ph.CO` and `astro-ph.GA` recent submissions through the Friday 2026-10-02 intake;
- merging-cluster weak- and strong-lensing reconstruction;
- convergence and mass residual maps;
- two-halo subtraction or marginalization;
- overlap-region and mass-bridge analyses;
- explicit baryonic decomposition;
- line-of-sight and reconstruction systematics capable of producing false residuals;
- newly published or revised methodological work.

Queries/themes included:

- `cluster lensing merger residual convergence overlap October 2026`
- `galaxy cluster weak lensing bridge residual mass October 2026`
- `strong lensing cluster residual map merger submitted October 2026`
- `mass bridge cluster lensing 2026`
- recent `astro-ph.CO` and `astro-ph.GA` intake review

Primary sources:

- [arXiv recent astro-ph.CO submissions](https://arxiv.org/list/astro-ph.CO/recent)
- [arXiv recent astro-ph.GA submissions](https://arxiv.org/list/astro-ph.GA/recent)
- [Roche et al., arXiv:2605.30433v2](https://arxiv.org/abs/2605.30433v2)
- [Roche et al., Open Journal of Astrophysics](https://doi.org/10.33232/001c.171998)

## Meaningful development

### Roche et al. — “A Consistent Implementation of Cluster Strong Lensing in Cosmological Simulation Light Cones”

- Original submission: 2026-05-28.
- Revised version: 2026-09-30.
- Journal publication: 2026-10-01 in *The Open Journal of Astrophysics*.
- **Classification: Methodological advance.**

### What was actually measured

The authors construct strong-lensing images directly from IllustrisTNG hydrodynamical simulation light cones. The cluster lens, background sources, correlated structure, and intervening line-of-sight matter are drawn consistently from one simulated cosmological volume and propagated with multi-plane ray tracing.

Comparing full light cones with a primary-lens-plane-only calculation, they report that uncorrelated line-of-sight structure:

- shifts relative lensed-image positions by several arcseconds;
- introduces about **6% scatter** in the area of the primary critical curve;
- changes the total critical area within 100 arcseconds of the cluster potential minimum by a median **16%**, with reported 16th/84th-percentile excursions of `−14%` and `+20%`;
- can add, enlarge, shrink, merge, or break critical structures, including a simulated merging configuration connected by a thin critical-curve bridge.

The paper also notes that assuming line-of-sight effects can simply be absorbed into the cluster plane can bias inferred primary-lens properties.

### Were additive halo and baryonic components removed or modeled?

**Not in the discriminator’s required observational sense.**

This is a forward-simulation study, not an observed merging-cluster residual analysis. Its hydrodynamical light cones contain ordinary matter and dark matter self-consistently, and the comparison isolates the effect of uncorrelated line-of-sight matter by ray tracing either:

1. all lens planes, or
2. only the primary lens plane, which still includes the cluster and correlated structure within roughly ±35 Mpc.

It does **not** fit and subtract halo A, halo B, and the observed baryonic contribution from a real convergence map, and it does not report a positive inter-halo residual.

### Why this materially advances the discriminator

A claimed positive overlap residual can be created or distorted when line-of-sight mass is omitted or compressed into a single cluster lens plane. The reported several-arcsecond image shifts and percent-to-tens-of-percent critical-area changes provide a concrete scale for that systematic.

The method supplies a stronger ordinary-physics null baseline for future tests:

- inject or select merging two-halo systems in hydrodynamical light cones;
- reconstruct them with the same pipelines used on observations;
- fit/subtract halo A, halo B, and baryons;
- measure how often ordinary line-of-sight structure and reconstruction choices create an apparent positive overlap residual;
- require any observed excess to exceed that false-positive distribution.

### Strongest caveat

The study has only 14 light cones in the quoted line-of-sight comparison, does not model observational effects or detectability, uses finite-resolution IllustrisTNG300 data, approximates diffuse mass as a uniform sheet, and does not perform the target two-halo-plus-baryon residual statistic. The authors defer the effect on inferred cluster masses and detailed lens-model bias to future work.

## Other current intake checked

The 2026-10-02 arXiv intake included general weak-lensing calibration and galaxy-scale lensing papers, but no new merging-cluster analysis that performs the fixed discriminator. No new direct match, partial/suggestive positive residual, magnitude constraint, weakening null test, or conventional explanation of a previously claimed discriminator-level residual was identified.

## Final status

**Status: Meaningful methodological advance**

No direct observational evidence for the predicted overlap excess was found. The paper improves control of a major conventional contaminant—line-of-sight structure—but does not test the full subtraction.

The framework remains **Candidate Correspondence**.
