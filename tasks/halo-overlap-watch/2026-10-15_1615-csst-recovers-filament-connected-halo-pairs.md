# Halo Overlap Watch — CSST reconstruction of filament-connected halo pairs

- **Run timestamp:** 2026-10-15 16:15 Asia/Bangkok
- **Task:** Halo Overlap Watch
- **Final status:** Meaningful methodological advance
- **Classification:** 4. Methodological advance
- **Framework status:** Candidate Correspondence unchanged

## Fixed discriminator

`observed overlap − fitted halo A − fitted halo B − ordinary baryonic contribution → positive residual`

The repository wording remains fixed: ordinary bridges, filaments, elongation, or additive halo superposition do not count as support. The relevant candidate is an overlap-associated excess beyond the ordinary modeled components.

## New result

Xinyue Chen et al., **“Mapping Dark Matter in Merging Clusters with Weak Lensing for CSST: Morphology and Filament Recovery,”** arXiv:2610.17857, submitted 2026-10-13 and accepted by ApJ on 2026-10-10.

The paper tests the MIU2Net deep-learning mass-reconstruction framework on mock reduced-shear maps from cosmological N-body simulations under CSST-like wide- and deep-field source densities. It explicitly studies filament-connected halo pairs and elongated halos.

Reported performance includes:

- halo centers recovered to about 0.1 h^-1 Mpc;
- stable recovery of connecting filament paths against shape noise;
- mean normalized filament-path instability around 0.037–0.051 depending on redshift/depth configuration;
- recovered filament morphology consistent with ground truth at the percent level;
- better preservation of low-contrast anisotropic structures than conventional Kaiser–Squires reconstruction while suppressing small-scale noise.

The halo-pair sample is large: several subsamples contain hundreds to more than a thousand pairs, separated into mass, redshift, and projected-separation bins. This makes the work particularly relevant for calibrating reconstruction bias in pair/overlap geometries rather than only isolated clusters.

## Additive components accounted for?

**No.** This is not the requested empirical subtraction test. The simulations are dark-matter N-body maps and the network reconstructs the total convergence field from mock reduced shear. The analysis does not independently fit halo A and halo B, subtract ordinary baryons, and then test a predefined overlap aperture for a positive residual.

The recovered connecting structures are ordinary cosmological filaments present in the simulation ground truth. They therefore cannot be counted as evidence for additional shared seating.

## Why this materially advances the discriminator

This paper supplies a new calibration route for the exact morphology most dangerous to the test: two massive halos connected by a low-contrast mass structure.

A future implementation of the discriminator can inject or select simulated halo pairs with known ordinary filamentary structure, reconstruct them through the same pipeline used on observations, fit/subtract the two halo components and baryons, and measure the distribution of apparent overlap residuals produced by ordinary structure plus reconstruction bias.

That allows a stronger null test:

`observed post-subtraction overlap residual`

versus

`ordinary simulated halo-pair + filament residual distribution after identical reconstruction and subtraction`.

The paper also shows why Kaiser–Squires-only residual work could be risky: the newer reconstruction preserves low-contrast anisotropic morphology more faithfully. A claimed residual should therefore be tested for stability across reconstruction methods rather than treated as physical merely because it appears in one convergence map.

## Strongest caveat

The method is simulation-trained and the demonstrated connecting structures are conventional cosmic-web filaments. Training-set priors could influence what morphology the network reconstructs. Any framework test would therefore need injection/recovery tests and preferably agreement with non-ML or differently regularized reconstructions before interpreting a positive overlap residual.

## Other literature checked

Fresh searches covered merging-cluster weak-lensing residuals, convergence maps, strong-lensing residual analyses, mass bridges, fitted-halo subtraction/marginalization, and October 2026 cluster-merger lensing work. No newer observational paper was found that performs the full `halo A + halo B + baryons` subtraction and reports a statistically meaningful positive residual in the overlap region.

## Assessment

**Meaningful development: Methodological advance.**

The result improves the ability to characterize and calibrate ordinary filament-connected halo-pair morphology, which is an important false-positive/control population for the discriminator. It is neither supporting nor weakening evidence for the predicted non-additive excess itself.

**Framework status remains Candidate Correspondence.**