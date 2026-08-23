# Work Prompt — Build This Bit for Substack

Use this Bit package as the production basis:

- `00-manifest.md`
- `01-sources-to-load.md`
- `02-notebooklm-source.md`
- `03-notebooklm-audio-prompt.md`
- relevant current framework source/status files already available in the Work

This is a **presentation-layer build**, not a semantic rewrite.

## Output

Create the publication-ready written companion article at:

`article/<slug>.md`

Also generate the actual editorial image for the article and store it in the same Bit package under:

`article/<generated-image-file>`

Embed the image in the Markdown using a relative link.

Do not create a separate Flow-prompt file unless explicitly requested.

## Article standard

Use the same reader-facing style as the current framework publication work:

- simple words;
- familiar question first;
- ordinary external explanation before framework interpretation when science is involved;
- clean conceptual pacing;
- enough white space;
- no jargon pile;
- no unnecessary recap of the entire framework;
- no claim inflation;
- strong final thought rather than a sales pitch.

The article is a companion to the audio, not a transcript of it.

A useful default shape is:

`ordinary mystery`
→ `standard explanation`
→ `remaining conceptual question`
→ `framework lens`
→ `test / boundary where useful`
→ `memorable closing thought`

## Semantic discipline

Preserve current framework meaning.

Keep external observations / established explanation distinct from framework-native interpretation.

Do not invent a numerical prediction, equation, or quantitative completion unless the source package actually contains it.

Do not import conventional ontology when doing so changes framework primitives.

Do not use older publication prose as semantic authority over newer source.

## Image generation

Work should generate the image directly.

Choose one strong conceptual relationship from the finished article and create an editorial conceptual image that helps the reader understand it.

Prefer 16:9 for the hero image unless the article clearly needs another format.

Avoid:

- embedded title text;
- labels or equations;
- infographic arrows;
- generic cosmic-AI decoration;
- visuals that silently turn candidate correspondence into established ontology.

Use descriptive alt text in the Markdown.

If a caption or manual publication note is needed, use a visible production blockquote directly below the image, for example:

> **Image Caption:** concise caption text

Do **not** use hidden HTML comment blocks for caption or placement instructions.

## Article cards / publication slots

When an article card or established Substack article handoff is needed, use a visible production blockquote:

> **Article Slot:** URL: https://...

Use only established URLs from the repository. Never invent one.

If the URL is not known:

> **Article Slot:** URL:

leave it empty for later completion.

Do **not** use `<!-- ... -->` HTML comment markers for production instructions.

## Final QA

Before finishing:

1. confirm the article matches the Bit dossier;
2. confirm external science and framework interpretation remain distinct;
3. confirm no new primitive or stronger status was invented;
4. confirm the article is readable without the audio;
5. confirm the image is generated and embedded;
6. confirm all production instructions use visible labeled blockquotes rather than HTML comments;
7. confirm the package manifest can be updated to `article-ready` or later.
