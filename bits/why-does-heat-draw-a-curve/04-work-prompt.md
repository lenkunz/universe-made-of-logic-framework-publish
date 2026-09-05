# Work Prompt — Why Does Heat Draw a Curve?

Build the written Substack companion for `bits/why-does-heat-draw-a-curve/` using the current package. This prompt is for the later article/image production step; the package is ready for NotebookLM independently of that step.

## Required reads

1. `00-manifest.md`
2. `01-sources-to-load.md`
3. `02-notebooklm-source.md`
4. `03-notebooklm-audio-prompt.md`
5. `05-preflight-deduction-audit.md`
6. `reference/README.md` and its existing comparison figure
7. Current `source/a-universe-made-of-logic.md`, spectrum section
8. `source/changes/2026-09-06-grain-sweep-and-repeated-comparison.md`
9. Relevant entries in `source/where-the-framework-stands.md`
10. `publish/guidelines.md` and `bits/bits-podcast-production-guide.md`

Read the external references relevant to any scientific claims in the article. Use current source meaning if older CMB prose omits this extension.

## Deliverables

- `article/why-does-heat-draw-a-curve.md`
- An actual editorial hero image under `article/`, embedded with a relative Markdown path
- An optional precise explanatory figure under `article/` if the final prose benefits from it
- Manifest and production-index updates reflecting the actual completed state

The article should be readable without the audio. A transcript is not required, and there is no separate Flow-prompt deliverable.

## Reader experience

Use simple words and a clear chain of reasoning. Open with a heating element or thermal measurement, not framework terminology. Establish the ideal blackbody case and the ordinary explanation before introducing the candidate grain sweep.

The article's main new distinction is:

> A repeat ratio can be constant at one selected comparison and still change as the grain is swept.

Use the half/quarter repeat sums from the dossier before showing the exponential form. The reader should understand what is being repeated and what is being changed.

Show at most the equations needed to connect:

`q + q^2 + ...`

to:

`q/(1-q) = 1/[exp(chi)-1]`, where `chi=-ln(q)`.

If displaying the Planck frequency shape, state that `x=h nu/(k_B T)` and the `x^3` weighting are the conventional inputs used in the conditional construction. Keep their native physical identification distinct from the exact algebra.

Explain the role of bin width with a short concrete example. Different spectral measures can have different peak locations. Do not imply a detector's arbitrary settings create physical radiation or that all hot materials have identical spectra.

A possible final line is: “The sweep makes the curve. The continuation rule gives it a shape.” Return to the opening example instead of ending in a framework advertisement or a list of unfinished physics.

## Status discipline

Preserve the difference among:

- established thermal physics;
- exact conditional geometric-sum mathematics;
- the candidate interpretation of the weights as repeated resolution;
- the unfinished native argument, weighting, normalization, and cross-ground scaling.

Keep changes over the sweep separate from changes over repeats. If discussing a variable repeat factor, use the product-of-factors form. Do not retain the simple denominator while deleting its fixed-local-factor assumption.

The original square-root toy remains historical. The new sum does not retrospectively make it Planck's law.

Do not import an outside clock, a fixed cosmic budget, a saturation mechanism, a gravitational radial law, or a claim that ordinary neural/mental observations prove this spectrum mechanism.

## Images

Generate one 16:9 editorial hero with a clear conceptual relationship: the same thermal source encountered through a changing range of comparison. Keep it understandable without title text, equations, labels, UI decoration, or generic cosmic imagery. The image must not imply experimental confirmation of the ontology.

The existing PNG is a mathematical reference with text and equations. Inspect it before reuse. It documents the earlier simple contraction samples and the conditional repeat-weight sum. Do not present it as a measured dataset or as a newly derived native spectrum.

If the article needs a scientific plot, produce it with exact plotting tools and label its measure and assumptions. Use image generation for the conceptual hero, not for precise curves.

Embed the finished image and use a visible caption when useful:

> **Image Caption:** Explain the relationship shown without strengthening the scientific claim.

Keep reader-facing captions visible. Remove completed internal `Publish Note` or `Image Brief for Work` instructions from the public prose.

## Related article

The established CMB episode may be linked near the end as the cooling question that follows the curve question:

> **Article Slot:** URL: https://soutame.substack.com/p/the-cmb-is-losing-the-resolution

This is a visible reader-facing handoff. Do not convert it to an HTML comment or invent a URL for the new Bit.

## Final verification

Check that the article explains the local-ratio distinction without a glossary; equations retain their assumptions; axes and spectral bin measures match; sources support empirical claims; the hero exists and is embedded; captions and article slots remain visible; and production state records only finished deliverables.

Use the publication feed again before marking the new Bit published. An article or audio file existing in the repository is not publication evidence.
