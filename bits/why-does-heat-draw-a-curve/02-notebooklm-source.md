# Why Does Heat Draw a Curve?

*Episode dossier. A general-interest explanation of thermal spectra followed by one candidate grain-comparison mechanism.*

## Start with the glow

A heating element does not light up every colour equally. A thermal camera can detect a warm object long before our eyes see it glow. With enough heating, visible light becomes part of the picture too.

Now imagine separating the radiation into narrow ranges and measuring the contribution from each range. Plot those readings. Instead of one colour or a flat line, an ideal thermal source gives a curve that rises, reaches a peak, and falls.

What gives that curve its shape?

Keep the question local and concrete. This episode is about the spectrum made by a thermal comparison. The cosmic microwave background is a related application, not the opening subject.

## What ordinary physics already explains

Use an ideal blackbody in thermal equilibrium as the clean case. Real materials can differ in how effectively they emit at particular wavelengths. A cavity with a small opening is a useful way to approach the ideal thermal source. [MIT's black-body radiation notes](https://ocw.mit.edu/courses/12-815-atmospheric-radiation-fall-2006/a4ea2da52e05800b5782a91b96f54322_thermo.pdf) supply the ordinary physical setting.

The measurement is a distribution of radiance over frequency or wavelength. It is not the instantaneous shape obtained by piling sine waves on one another.

In the frequency form, Planck's law is:

`B_nu(nu,T) = (2 h nu^3 / c^2) / [exp(h nu / (k_B T)) - 1]`.

The standard account combines the available radiation modes, energy per quantum, and thermal occupation. The number of modes and the cost of occupying them compete across the spectrum. That competition produces a peak and a high-frequency decline. [NRAO's radiation chapter](https://www.cv.nrao.edu/~sransom/web/Ch2.html#S4.SS2) gives the equation and its derivation.

The existence of a good standard explanation is part of the episode. The framework enters as a proposal about a more general relational operation that might reproduce the same result; it must preserve the measured constraints.

NIST's [spectral-emittance facility](https://www.nist.gov/laboratories/tools-instruments/system-infrared-spectral-emittance-materials) compares material radiance with a blackbody reference. This is a concrete reminder that the source, reference, and material response are meaningful parts of measurement. It does not establish the framework's ontology.

## First answer in ordinary language

The detector asks a similar question across a range:

How much contribution is available here?

Then here?

Then at the next comparison range?

The resulting curve records how the answers change. A peak means the factors that increase the contribution and the factors that restrict it balance differently on either side.

This is the provisional answer to reach before introducing framework vocabulary.

## The framework's proposed contribution

The current source treats a spectrum as the result of a receiver/target comparison sweep. A selected periodic comparison grain was previously called `B_x`, with target support called `B_t`, inside a shared anchor closure. These are contextual quantities, not isolated allowances that objects own outside every relation.

The current extension says:

> **A spectral curve traces how much relation can resolve as the participating grains are brought through a range of comparisons.**

The comparison ratio changes during that sweep. There is no need to assume one multiplier valid at every grain.

Introduce only two ideas initially: the selected comparison, and the supported contribution at that comparison. Stage, budget, and anchor can remain in the background until a precise misunderstanding requires them.

“Grain” does not mean blurry vision. It means which distinctions the encounter requires. A broad or coarse relation remains real and supported.

## One local ratio is compatible with a changing curve

This is the central distinction to make slowly.

At one selected comparison, suppose the next repeated contribution carries one-half the weight of the previous level. The contributions are:

`1/2 + 1/4 + 1/8 + ... = 1`.

Move to another selected comparison. Suppose its local factor is one-quarter instead:

`1/4 + 1/16 + 1/64 + ... = 1/3`.

The rule is still repeated proportional contribution. The ratio differs between the selected comparisons. Connecting the results across a continuous range makes a curve.

There are two different questions:

- Does the factor stay the same over repeats at this selected grain?
- How does that factor change when the selected grain changes?

The first can be yes while the second varies continuously. This is what a universal fixed-multiplier reading would miss.

The fractions above are weights in a model. They are not measured absorption probabilities, pieces of an actual photon, or established physical persistence-loop counts.

## Why an exponential appears naturally in repeated proportions

Multiply by the same positive factor repeatedly and the result is a power of that factor. Any such factor can be written as an exponential. For a local factor `q`, define `chi = -ln(q)`; then `q^n = exp(-n chi)`.

That exponential is in the repeat index. It does not by itself say how `chi` depends on the grain ratio or on measured frequency.

The geometric picture has a related structure. If a scalar length changes proportionally to its current length along a relational continuation, integration gives an exponential of accumulated proportional change. A constant proportional rate gives the simple `L/L0 = exp(-s)` illustration. A changing rate can be included in the accumulated exponent.

`s` is a dimensionless accumulated comparison quantity, not time supplied by an outside clock. The base `e` does not specify the rate or a gravitational distance law. The source must provide what changes and by how much.

Shared factors can cancel. If a target and its local ruler acquire exactly the same factor, their ratio remains unchanged. A comparison between differently conditioned grounds can expose a difference. This is where the framework's common-anchor rule is useful.

## The exact denominator

At one selected comparison, assume that weighted contributions can be added and that each further repeat has the same local ratio `q`, with `0<q<1`. The geometric sum is:

`q + q^2 + q^3 + ... = q/(1-q)`.

Using `q = exp(-chi)` gives:

`1 / [exp(chi)-1]`.

This is an exact mathematical identity. The minus one follows from adding the continuing proportional sequence.

A candidate response can therefore be written:

`G_A(rho) = W_A(rho) / [exp(chi_A(rho))-1]`.

`rho` labels the selected grain comparison, `A` carries its consequential anchor setting, and `W` carries the weighting needed for the observable. No automatic scalar formula for arbitrary relational budgets is being asserted.

If the local factor changes from repeat to repeat, the terms instead contain products of different factors. The simple geometric denominator then need not survive. This is a substantive model condition, not a wording detail.

Likewise, additive weights are an assumption about the measured contribution. Raw coherent wave amplitudes require their phase relations and cannot be substituted for these weights.

## What the earlier picture actually constructed

The earlier comparison image plotted:

`x^3 [exp(-x) + exp(-2x) + exp(-3x) + ...]`.

Its total is exactly `x^3/[exp(x)-1]`.

For the standard frequency spectrum, `x = h nu/(k_B T)`. At fixed temperature the dimensional coefficient factors out. This gives the normalized Planck frequency shape shown in the image.

That picture supplied the standard argument and the `x^3` weighting. The framework has not independently identified either with its native grain variables. The exact sum is available; the physical identification of supported repeats and observable weights remains a candidate under development.

The colour bands in the figure are terms in that sum. They are not distinct incoming colours, physical layers of space, or proof that each thermal photon is a compressed persistence loop.

This is a clearer position than either “only a vague hump exists” or “Planck's law has now been derived from the ontology.” Preserve the actual intermediate result.

## A constant multiplier does not settle every comparison

An overall amplitude can be fixed while the grain coordinate varies. A change in target/receiver setting can alter that amplitude and a characteristic scale. It can also alter the shape if the continuation or weighting changes with grain.

There is another subtlety: “per unit frequency” and “per unit wavelength” divide the same radiation into different-width bins. The density must change with the bin width. Their peaks are not obtained by a simple axis relabeling. Per logarithmic frequency interval, the dimensionless numerator is `x^4`. See the corresponding density formulas in [NRAO](https://www.cv.nrao.edu/~sransom/web/Ch2.html#S4.SS2).

For the audio, say this plainly: changing the width of the buckets changes the height of the pile per bucket, even when the total material being sorted is the same. Do not imply the radiation itself is created by changing a plotting convention.

## Where the Fourier intuition fits

A logarithmic coordinate turns a wavelength ratio into a shift. For example, multiplying all wavelengths by the same amount slides their pattern along a log ruler.

The Mellin transform is related to Fourier analysis in this logarithmic coordinate after the appropriate weighting. [NIST's transform definition](https://dlmf.nist.gov/1.14#iv) supports this mathematical connection.

It is useful language for comparing scale patterns. It does not force the thermal spectrum. The original image did not actually perform a Fourier transform.

This is optional audio material. If the name becomes a distraction, keep the picture of equal ratio steps on a log ruler and move on.

## One informative diagnostic

Under the illustrated Planck choices, low comparison ratios receive contributions from many repeat terms. At high ratios, later terms become very small and the first term dominates.

If the mathematical sum is cut off at a finite repeat count `N`, the very low-`x` response changes: it behaves as `N x^3` instead of the infinite sum's `x^2`. The high end still approaches `x^3 exp(-x)`.

This is a diagnostic within the candidate family. It is not a newly observed result, and finite resolving budget does not automatically justify a hard cap on the repeat index.

The productive challenge for the hosts is therefore: which part of the curve changes if we change the rule? That contributes understanding without turning the episode into an assignment to solve all of blackbody physics.

## Return to the heating element

Return to the initial spectral sweep. Each plotted reading belongs to a selected comparison. The proposed repeat rule determines what contributes there, and changing the grain traces the changing response.

The ordinary thermal explanation remains intact. The framework contribution is an explicit candidate for how a repeated relational operation could supply a distribution-generating rule, with its physical mapping still identified as further work.

End with the heating element and the measurement, not a recap of cosmology:

> **The sweep makes the curve. The continuation rule gives it a shape.**
