# Preflight Deduction and Publication Audit

Date: 2026-09-06 Asia/Bangkok  
Episode: **Why Does Heat Draw a Curve?**  
Decision: **Prepare as a distinct user-selected Bit.**

## Publication check before preparation

Checked at 2026-09-05 17:46 UTC / 2026-09-06 00:46 +07:00.

- Preferred proxy `https://souta.me/rss/podcasts`: unavailable through the current live-access route.
- Upstream `https://api.substack.com/feed/podcast/10455398/s/443918.rss`: unavailable through the current live-access route.
- Required fallback: `resource/substack-bits-podcast.rss` at repository commit `ddc3ebd93ce8380a96a25e550fe64eb77ff3cdc2`.
- Snapshot status file reports a successful proxy refresh; no unsupported claim of a current live fetch is made.
- Parsed 32 complete items with titles, links, and publication times. The newest item is **What Is a Flame If Its Matter Never Stays?**, 2026-09-04 04:58:15 UTC.
- No exact title match for the new Bit.

The snapshot resolves stale metadata: Flame was published September 4, Snowflakes September 1, and the Hope-derived dream Bit August 23. Their records are synchronized to the exact feed entries. The spinning-top episode remains prepared/article-ready because no publication match is present.

## Nearby-topic audit

| Existing topic | Existing payoff | New work in this episode |
|---|---|---|
| The CMB Is Losing the Resolution Race | Relative fine/background density and cosmological cooling | How a local comparison sweep and repeated weighting generate a spectral response |
| Stage Is Where Light Meets Space | Measurement through relation and domain | Distinction between varying grain and repetition at fixed grain |
| Why Does Motion Make a Ruler Shorter? | Anchor-closed receiver comparison and scoped contraction | Exponential accumulation, spectral weighting, and a geometric-sum denominator |
| Air-conditioner episode | Heat transfer through a refrigeration cycle | Radiation distributed across frequency, with a peak and a tail |

The title is new, but the decision rests on the different question and mathematical payoff. Cosmological cooling is a brief downstream connection.

## Assumption audit

| Step | Needed assumption | Result and status |
|---|---|---|
| Integrate proportional length change | A scalar differentiable description and specified local proportional rate | Exponential of accumulated rate; conditional mathematics |
| Sum repeat weights | Additive nonnegative contributions; fixed local `q` over repeat index; `0<q<1` | `q/(1-q)`; exact mathematics |
| Let the sweep vary | `q` and the weighting may depend on selected grain and anchor closure | A family of comparison outcomes; no universal multiplier required |
| Use a factor that changes between repeats | Product of the actual factors | General sum; the same simple denominator is not automatic |
| Recover the plotted Planck shape | Conventional `chi=x=h nu/(k_B T)` and frequency factor `W=x^3` | Exact reference shape under imported physical inputs |
| Identify the native physical mechanism | Define the repeat contributions and their weights from the specified relation | Candidate identification; not yet derived |
| Change the spectral bin coordinate | Apply the density's Jacobian | Frequency, wavelength, and log-frequency plots are distinct measures |

The figure is a deterministic mathematical illustration. It is not data, a Fourier-transform calculation, or empirical confirmation of geometric contraction.

## Concrete checks

- Verify the geometric sum at multiple local ratios, including ratios that vary across the sweep.
- Verify that a changing repeat factor requires a product and does not generally equal a geometric series using the first factor.
- Verify the finite-repeat formula and the distinct low-`x` behavior.
- Confirm the standard frequency and wavelength density conversion preserves the same integrated radiance over matching intervals.
- Check new relative links, required package files, and consistency among source, status, dossier, and prompts.
- Keep the article, hero, and audio pending in the package manifest.

## Publication check after preparation

Checked again after drafting at 2026-09-05 18:05:46 UTC / 2026-09-06 01:05:46 +07:00. Both live endpoints remained unavailable. A fresh read of the repository snapshot was byte-identical to the first read: 32 complete items, newest Flame item on September 4, and no exact title match for this Bit. The package remains prepared and unpublished according to that snapshot. The fallback cannot rule out a publication newer than its contents.

Validation passed: geometric sums across six local ratios, the varying-repeat counterexample, finite-repeat formula, matching frequency/wavelength integrals, new relative links, and byte identity of the reference image. The main source after the owning spectrum section is unchanged.

## Remaining physical identification

The known identity tells us what a stationary local repeat rule would produce. It does not independently specify which native relations supply `q`, why their log equals the physical comparison argument, what observable weighting they supply, or how normalization changes across grounds.

The scoped result belongs in the maintained source as a candidate with exact mathematics. A full native Planck or cosmological derivation is not claimed.
