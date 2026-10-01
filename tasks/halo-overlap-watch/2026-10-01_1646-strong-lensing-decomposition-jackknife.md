# Halo Overlap Watch — 2026-10-01 16:46 ICT

## Task

Check current astronomy and astrophysics literature for genuinely new observational or methodological work bearing on the discriminator:

`observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution → positive residual`

The proposed physical correspondence remains that overlapping coarse anchored regions in merging galaxy clusters might produce additional shared seating beyond simple additive halo superposition.

## Framework source check

The current stable wording in `source/a-universe-made-of-logic.md` and the prior task ledger remains unchanged. An ordinary bridge, elongation, fitted displacement, or multi-halo superposition is not support. The target is a positive overlap-correlated mass-density or convergence residual after ordinary halo and baryonic contributions are accounted for.

Framework status before this run: **Candidate Correspondence**.

## Search scope

Checked the literature intake available on 2026-10-01, emphasizing:

- new arXiv astro-ph.CO and astro-ph.GA submissions;
- merging-cluster weak- and strong-lensing reconstructions;
- convergence and mass residual maps;
- explicit halo-profile subtraction or marginalization;
- baryonic decomposition;
- model-dependence and out-of-sample validation of residual structures;
- stacking or reconstruction methods that could test a non-additive overlap excess.

Primary search surfaces and themes:

- [arXiv astro-ph.CO recent submissions](https://arxiv.org/list/astro-ph.CO/recent)
- [arXiv astro-ph.GA recent submissions](https://arxiv.org/list/astro-ph.GA/recent)
- targeted searches for merging clusters, strong-lensing residuals, weak-lensing convergence maps, mass bridges, halo subtraction, overlap excesses, baryonic modeling, and regularized mass reconstruction;
- comparison against the 2026-09-30 archive to avoid duplicate reporting.

## Meaningful development

### Cha, Limousin & Jee, “Testing Offsets Between Cluster-Scale Halos and BCGs in Strong Lensing Models Using the Jackknife Method”

- [arXiv:2609.38310](https://arxiv.org/abs/2609.38310)
- Submitted 2026-09-29 18:00 UTC and surfaced in the 2026-10-01 arXiv intake.
- Targets: Abell 370, RX J1347.5-1145, and MACS J0416.1-2403.
- Data: 105, 123, and 303 spectroscopically confirmed multiple images, respectively.
- Method: the hybrid MrMARTIAN reconstruction combines analytic cluster-scale halo profiles and galaxy components with a regularized grid. The grid can carry positive or negative convergence not captured by the analytic profiles.
- Test: compare models with halo centers fixed on bright cluster galaxies against models with free halo centers, across five regularization weights. Jackknife reconstructions omit one multiply imaged source system at a time and test prediction of the omitted images.
- Result: fixed- and free-center models have comparable out-of-sample predictive accuracy. Total mass maps remain broadly similar, but fitted halo offsets change substantially with regularization. The split between analytic halos and the residual grid is therefore not unique.

**Classification: Methodological advance.**

## Why it matters for this discriminator

A positive overlap-region grid feature cannot automatically be interpreted as extra non-additive mass. The paper demonstrates that strong-lensing constraints can permit different internal decompositions between analytic halo profiles and a flexible grid while maintaining similar total mass distributions and predictive performance.

A credible test of the framework’s discriminator should therefore require that an overlap residual:

1. remains positive across materially different regularization strengths and halo-position assumptions;
2. survives out-of-sample or jackknife prediction tests;
3. is stable under alternative analytic halo parameterizations;
4. is not merely the grid compensating for a shifted or misspecified fitted halo;
5. remains after ordinary baryonic components are explicitly included.

This materially improves the validation design for future overlap-residual claims.

## Were additive components actually accounted for?

**Only partially, and not in the discriminator’s required sense.**

The reconstruction includes multiple analytic cluster-scale halos and large catalogs of cluster-member galaxy mass components. However:

- it does not subtract a fitted halo A + halo B + complete ordinary baryonic model from an independently reconstructed observed convergence map;
- it does not isolate an inter-halo overlap statistic;
- no dedicated intracluster-gas/ICM baryonic component is reported in the tested decomposition;
- it does not measure a positive shared-overlap residual or set an upper limit on one.

Accordingly, the paper is **not** a Direct match, Partial / suggestive correspondence, Constraint on magnitude, Weakening evidence, or Conventional explanation of a previously claimed overlap excess.

## Strongest caveat

The study tests halo-center freedom and regularization dependence in three strong-lensing cluster cores. It does not directly test the predicted non-additive overlap component, and strong-lensing constraints are spatially concentrated around multiple images rather than uniformly sampling the full merger-overlap region.

## Other intake checked

The remaining 2026-10-01 astro-ph.CO/GA entries and targeted search results did not report:

- a positive inter-halo residual after two-halo and baryonic subtraction;
- a new upper bound on such a component;
- a careful null detection with demonstrated sensitivity to the predicted effect;
- or a new conventional explanation for an already reported discriminator-level excess.

## Final status

**Status: Meaningful methodological advance**

The empirical goalposts are unchanged. The paper strengthens the required robustness standard but neither supports nor falsifies the predicted excess.

Framework status remains **Candidate Correspondence**.
