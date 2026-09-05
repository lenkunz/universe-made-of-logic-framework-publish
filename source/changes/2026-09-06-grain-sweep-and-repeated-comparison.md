# Grain sweep and repeated comparison

Date: 2026-09-06 Asia/Bangkok  
Base checkpoint: R20260905-2350-01  
Revision: R20260906-0104-01 / 2026-09-06 01:04 +07:00  
Status: **Candidate spectral mechanism with conditional mathematics**  
Scope: Extend the existing receiver/target spectrum account; preserve the distinction between a changing grain comparison, repetition at one selected comparison, and dimensional calibration.

## The contribution being retained

Len reads each smooth curve in the comparison illustration as the result of continuing the comparison across the participating grain ranges. The comparison ratio changes across that range. The picture must not turn this into one universal multiplier applied at every grain.

The retained proposal is:

> **A spectral curve traces how much relation can resolve as the participating grains are brought through a range of comparisons.**

This develops the existing `B_x` / `B_t` sweep. It does not make the graph a primitive object, require a human observer, or assume a past Stage transporting a finished curve.

Len's phrase about a constant multiplier is preserved through a distinction: an overall calibration factor can be constant within a specified comparison while the grain ratio varies. A claim about changing ratios does not itself determine that calibration, a repeated contribution's weight, or the spectral counting measure.

Continuity is a working approximation for the smooth thermal branch. This is not a claim that every spectrum, every target, or every possible relation must be smooth. Discrete lines and thresholds remain possible.

## Three different operations

| Operation | What changes | What can be held fixed for the calculation |
|---|---|---|
| Sweep through one spectrum | Selected comparison grain and its relation to the target | Declared target/receiver setting and measurement protocol, with consequential grain-dependent support still carried |
| Repeat at one selected comparison | Repeat index `n` | The selected grain and, in the simple case, its local continuation factor |
| Compare different spectra | Target/receiver condition, characteristic scale, and possibly amplitude or shape | The proposed family of measurement rules, if the new conditions actually preserve it |

These operations cannot be merged into one unexplained multiplier.

Let `rho` label a positive dimensionless grain comparison within a specified anchor closure `A`. It is a coordinate for this candidate model. Do not silently equate it with an intrinsic object's budget or assume arbitrary relational budgets already support scalar division.

The simple repeat factor may be written `q_A(rho)`. It can be constant with respect to `n` at one selected `rho` and still change across the spectral sweep.

> **A local repeat ratio can stay the same while the comparison ratio is held fixed, then change when the grain changes.**

This is the distinction the first picture did not make explicit enough.

## Proportional contraction can have a changing rate

For a scalar length comparison, assume a differentiable local proportional rule:

`d ln(L) / du = -kappa(u)`

Here `u` labels continuation through the chosen relational process. It is not universal clock time. Both the existence of this scalar description and the rate law are assumptions of the construction.

Then:

`L(u) / L(u0) = exp[-integral from u0 to u of kappa(v) dv]`.

Constant `kappa` gives the simplest exponential. A changing proportional rate gives an exponential of the accumulated rate. Writing the accumulated logarithmic contraction as `s` yields the earlier illustration's `L/L0 = exp(-s)`.

The base `e` does not select a physical rate. Every positive multiplier can be written using `e`; the independent content is the rule that fixes how the multiplier changes with the relevant relation.

Shared scalar scale factors cancel from a ratio only when they contribute equivalently to both sides. This is a scoped realization of common-anchor cancellation, not a replacement for the full anchor-closure rule. A common contraction can therefore be locally invisible while a difference between grounds remains measurable.

The picture specifies length. Isotropic area would carry the square of that length factor, and volume its cube. No new gravitational radial profile or equality between length contraction and spectral occupancy is supplied here.

## The conditional repeated-weight construction

At a selected `rho`, suppose:

1. Contributions can be aggregated as nonnegative weights at the measured grain. Any consequential interference must already be included; raw wave amplitudes cannot simply be counted this way.
2. Each additional repeat contributes the same local factor `q_A(rho)`, with `0 < q_A(rho) < 1`.
3. The repeat series extends as the geometric sum in this idealized calculation.
4. `W_A(rho)` supplies whatever state, energy, response, and measurement weighting the observable requires.

Then:

`G_A(rho) = W_A(rho) [q + q^2 + q^3 + ...]`

`= W_A(rho) q / (1 - q)`.

Define `chi_A(rho) = -ln q_A(rho)`. Equivalently:

`G_A(rho) = W_A(rho) / [exp(chi_A(rho)) - 1]`.

This is **derived conditional mathematics**. The proposed identification of the weights with supported repeated resolution is a **candidate mechanism**.

The distinction is exact: constant ratio over repeats gives an exponential in `n`. It does not yet establish a particular dependence on frequency, wavelength, the sweep coordinate, or geometric contraction. Defining `chi = -ln(q)` is a useful representation, not independent evidence for a physical exponential law.

If the repeat factor changes with `n` even at a selected comparison, use:

`Q_n(rho) = product from j=1 to n of q_j(rho)`

`G_A(rho) = W_A(rho) sum over n>=1 of Q_n(rho)`.

That generally does not reduce to the same denominator. The varying-grain correction therefore does not entitle us to discard the condition that made the simple sum work.

The repeat index is a mathematical index in this candidate. It is not yet an identified photon count, chronological history, count of independent worlds, or claim that an infinite number of fine events must be physically rendered.

## Where Planck's law enters

For the established Planck spectrum per unit frequency, define `x = h nu / (k_B T)`. At fixed temperature, removing dimensional prefactors leaves:

`S_nu(x) = x^3 / [exp(x) - 1]`.

The standard derivation uses radiation-mode counting, energy per quantum, and equilibrium occupation. Its mode density supplies two powers of frequency; the energy quantum supplies another. See [NRAO, Essential Radio Astronomy, section 2.4.2](https://www.cv.nrao.edu/~sransom/web/Ch2.html#S4.SS2).

The comparison illustration reproduced that shape by choosing `chi = x` and `W = x^3`:

`x^3 [exp(-x) + exp(-2x) + exp(-3x) + ...] = x^3 / [exp(x) - 1]`.

The identity is exact. It was not an independently derived native Planck law. The outstanding physical identification is why the specified anchor-closed comparison supplies these particular weights, this argument, and the required observable normalization.

This updates the old status from an unspecified counting question to an explicit conditional construction whose physical inputs are identifiable. It does not promote blackbody physics or cosmology to completed framework deductions.

## What an overall multiplier can and cannot do

A context-dependent amplitude and characteristic scale can be represented schematically as:

`G_A(z) = C_A F(z / a_A)`.

That is a restricted family assumption. It is not guaranteed for an arbitrary change of receiver, target, or anchor. If `W`, `chi`, or the response changes in a grain-dependent way, the shape can change as well.

The measurement bin also matters. A density per frequency is not obtained as a density per wavelength by relabeling the horizontal axis alone:

`B_lambda = B_nu |d nu / d lambda|`.

Per logarithmic frequency interval, `B_log = nu B_nu`, giving a dimensionless shape proportional to `x^4 / [exp(x)-1]` at fixed temperature. The extra factor reflects what is counted per bin. It is not a new physical source of radiation.

Therefore a constant normalization is not a substitute for the grain-dependent counting rule or a Jacobian.

## The scale-transform connection

With `v = ln(lambda/lambda0)`, multiplication of wavelength by `a` becomes addition of `ln(a)` to `v`. Fourier analysis of an appropriately weighted function of this logarithmic coordinate is related to the Mellin transform. This follows by substituting a logarithmic coordinate in the [NIST Mellin-transform definition](https://dlmf.nist.gov/1.14#iv).

This supplies a mathematical language for comparing scales. Neither a Fourier nor a Mellin transform alone forces a Planck distribution. The earlier figure plotted scale comparisons and a sum; it did not perform a Fourier transform.

## A concrete diagnostic inside the model

If the repeat sum is truncated at `N`, its value is:

`q (1 - q^N) / (1 - q)`.

Under the illustrative Planck choices, when `x` is much smaller than `1/N`, the finite sum approaches `N`, so the spectrum goes as `N x^3`. The infinite sum instead gives the low-`x` behavior `x^2`. At large `x`, the first term dominates and gives `x^3 exp(-x)`.

This is a diagnostic for different repeat rules, not a new observed prediction. Finite resolving budget does not by itself establish a hard cutoff in this mathematical sum.

## Source and production ownership

- Main source: the spectrum section in [A Universe Made of Logic](../a-universe-made-of-logic.md#the-spectrum-must-follow-from-a-native-rule).
- Status: [Where the Framework Currently Stands](../where-the-framework-stands.md).
- Prior scope: [August 30 blackbody correction](../../bits/the-cmb-is-losing-the-resolution-race/06-revision-note-blackbody-audit.md).
- New Bit: [Why Does Heat Draw a Curve?](../../bits/why-does-heat-draw-a-curve/00-manifest.md).

The new Bit owns the curve-generating comparison and the local-repeat distinction. The earlier CMB Bit continues to own the relative-resolution cooling question.
