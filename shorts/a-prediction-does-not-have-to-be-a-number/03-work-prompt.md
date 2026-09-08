# Work Prompt — Build A Prediction Does Not Have to Be a Number for Substack

Use this Short package as the production basis:

- `00-manifest.md`
- `01-sources-to-load.md`
- `02-short-source.md`
- newest relevant framework source/status files in GitHub, especially `source/where-the-framework-stands.md`

This is a presentation-layer build, not a semantic rewrite.

## Output

Create the publication-ready Short at:

`article/a-prediction-does-not-have-to-be-a-number.md`

Generate the actual editorial hero image during the build and store it under this Short package at:

`article/<generated-image-file>`

Embed it in the Markdown using a relative link and descriptive alt text.

Do not create audio, NotebookLM source, or NotebookLM prompt files.

## Editorial target

Keep the prepared title unless a tiny punctuation correction is necessary. Preserve the Short's narrow question: **what makes a non-numerical prospective claim a genuine prediction rather than a post-hoc explanation?**

Keep the familiar box/object opening before framework vocabulary. Preserve the progression:

`commit before observation`
→ `direction can exclude outcomes`
→ `premise → expected structure → opposite/falsifier`
→ `framework connection`
→ `halo-overlap example with explicit status boundary`
→ `prediction can gain resolution`

Do not turn this into a general philosophy-of-science essay or a defense of the framework. The piece should work even for a reader who has never seen My GUT Deduction.

## Semantic discipline

Use the newest GitHub framework source and `source/where-the-framework-stands.md` as semantic authority. Preserve still-valid prepared prose, but correct anything newer source has superseded.

The framework currently describes its strongest prospective claim as structural rather than a promise to calculate every concrete future state. That supports the methodological framing, but it does not license vague hindsight matching.

Keep the halo-overlap example explicitly at **Candidate correspondence**. Do not claim confirmation, a derived amplitude, or a completed physical mapping. Preserve the requirement that ordinary additive halo contributions, baryonic structure, projection/reconstruction effects, and other conventional contributions must be accounted for before a residual can count toward the proposed discriminator.

Do not invent a new primitive, numerical completion, or stronger claim status.

## Image generation

Generate one 16:9 editorial image directly using the image concept in `02-short-source.md`.

Preferred concept: a restrained laboratory/editorial scene with two closed sample boxes or envelopes and a visible pre-commitment marker placed toward one before the reveal; one container is only beginning to open. The visual relationship is **commitment first, evidence second**. It should feel like experimental discipline, not gambling.

Leave useful negative space on the right when composition permits. No embedded title text, equations, infographic arrows, labels, generic cosmic/AI decoration, neon science motifs, or visuals that imply the framework's physical example is established fact.

Embed the generated image near the opening. When useful, retain a visible caption such as:

> **Image Caption:** A prediction takes a position before the result is opened.

## Related-article handoff

If an established public framework URL relevant to prediction/status is available in repository metadata, it may be surfaced as:

> **Article Slot:** URL: <established URL>

Never invent a URL. If none is clearly established, omit the slot or leave its URL empty.

## Final QA

Before finishing, confirm:

- the article still matches `02-short-source.md`;
- the opening is understandable without framework vocabulary;
- current semantic source wins over older wording;
- structural prediction is not confused with numerical completion;
- the halo example remains Candidate correspondence;
- the image has actually been generated, stored under this package, and embedded by relative link;
- useful reader-facing Image Caption / Article Slot blockquotes remain visible;
- no hidden HTML production markers were introduced;
- no audio or NotebookLM artifacts were created.
