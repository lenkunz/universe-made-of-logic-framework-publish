# Publication Guidelines

Updated: 2026-08-23
Status: ACTIVE PUBLICATION WORKFLOW

These are the standing rules for transforming current framework source into publication-ready Markdown.

## 1. Semantic discipline

Publication output must preserve the current framework meaning.

Always distinguish among:

- framework-native deduction;
- candidate physical correspondence;
- completion pending;
- unresolved mechanism;
- personal metaphysical / Hope material.

If a source/status page marks something as not established, publication prose must not present it as already established.

Use `source/where-the-framework-stands.md` whenever claim status matters.

## 2. Required reads

For a full framework publication refresh, read:

1. `publish/README.md`
2. `publish/manifest.md`
3. `publish/guidelines.md`
4. `memory/current-context.md`
5. `memory/semantic-guardrails.md`
6. `memory/workflow.md`
7. all eight maintained semantic source files listed in `publish/manifest.md`
8. `source/where-the-framework-stands.md`
9. relevant semantic change maps in `source/changes/`
10. `source/internal/url-list.md`

For a single-article refresh, load only the relevant subset plus the status/source files needed to preserve meaning.

## 3. Publication outputs

Publication-ready Markdown belongs under:

`publish/articles/<article-slug>.md`

Generated images belong under:

`publish/assets/images/<article-slug>/`

Use stable filenames and update them in place.

## 4. Existing-publication behavior

The eight primary articles in `publish/manifest.md` are existing publication identities.

A refresh should therefore preserve:

- article identity;
- established Substack URL where known;
- intended role in the framework set;
- article-slot relationships.

But the body should be rebuilt from current source semantics rather than blindly preserving stale publication prose.

## 5. Visible reader-facing callouts and production notes

Do **not** use hidden HTML comments such as `<!-- ... -->` for article slots, image captions, or other instructions the user needs to see outside a special Markdown renderer.

Use visible, explicitly labelled blockquotes.

Two of these forms are now part of the **final reader-facing article design** and should normally remain visible after publication:

### Article slots

Use:

`> **Article Slot:** URL: https://...`

Use URLs from `source/internal/url-list.md` / `publish/manifest.md`.

Do not invent a URL.

If the URL is not known, use:

`> **Article Slot:** URL:`

and leave it empty for later completion.

The blockquote itself is intentionally retained in the final Markdown / Substack article as a clean visible handoff to a related article. Do not replace it with a hidden slot marker merely to make the source cleaner.

### Image captions

Place directly below the image when a caption is useful:

`> **Image Caption:** concise caption text`

The caption blockquote is intentionally retained in the final article. It is part of the visual rhythm, not an internal placeholder.

### Internal-only notes

Use an explicit label such as:

`> **Publish Note:** ...`

or:

`> **Image Brief for Work:** ...`

These are production-only notes. Perform the indicated action and remove them from the public article when they are no longer useful.

### Why blockquotes are required

HTML comment blocks can disappear in rendered Markdown viewers and therefore fail as portable copy/paste instructions.

Visible labelled blockquotes remain readable in ordinary Markdown, GitHub, ChatGPT, copied source, and Substack.

Do not restore `<!-- Article Slot ... -->`, `<!-- Image Caption ... -->`, or other invisible forms in new publication output.

## 6. Image generation and embedding

If an article needs a hero or inline image, Work should produce the actual image during the rebuild.

For every final image:

1. determine the semantic purpose of the image;
2. generate an editorial conceptual image that supports that purpose;
3. save the generated asset under `publish/assets/images/<article-slug>/`;
4. embed it directly into the article Markdown;
5. place a visible `> **Image Caption:** ...` blockquote directly below it when a caption is useful, and keep that caption in the final article.

Preferred repository Markdown form:

`![Descriptive alt text](../assets/images/<article-slug>/<filename>.png)`

Use descriptive alt text rather than the filename.

## 7. Image design rules

Publication images should visualize one strong relationship or distinction from the article.

Prefer:

- editorial conceptual illustration;
- clear spatial/compositional relationship;
- 16:9 for hero images unless another format is needed;
- visual meaning that survives without embedded explanatory text.

Avoid:

- generic cosmic-AI decoration;
- unnecessary text, labels, equations, UI chrome, or diagrams unless the article genuinely calls for them;
- imagery that silently turns a candidate correspondence into established physical ontology;
- images that are only decorative and do not help the reader understand the article.

## 8. Private-repository image note

This repository is private.

Relative Markdown image links are the correct durable form inside the repository, and Work should keep them embedded in the generated Markdown.

However, a private GitHub raw/blob URL is not public image hosting for Substack. The Substack publication step must ingest/upload the image binary rather than depending on a private GitHub hotlink remaining visible to public readers.

Do not pretend otherwise in generated instructions.

## 9. Copy/paste readiness

The generated Markdown should be as close as possible to a complete publication package:

- article body already rebuilt;
- visible reader-facing article-slot blockquotes already placed and retained;
- image Markdown already embedded;
- visible image-caption blockquotes already placed and retained where useful;
- images already stored in the repo;
- internal-only `Publish Note` / `Image Brief for Work` markers removed once their job is done;
- no manual image-slot planning left to do.

The goal is to eliminate repeated drag-and-drop asset management while keeping the useful related-article and caption callouts as part of the article itself.

## 10. Tone and terminology

Use plain language.

Preserve the framework's own meanings for:

- relation;
- Cut;
- resolution;
- possibility;
- domain;
- point;
- budget;
- coarse/fine;
- anchor;
- Aim;
- Lane;
- Rung;
- hosted / established / independently seated.

Do not import familiar scientific language when doing so changes the primitive meaning.

## 11. Do not do these things

Do not:

- alter semantic meaning for smoother prose;
- promote Hope/personal speculation to framework ground;
- invent Substack URLs;
- leave image placeholders when a rebuild is expected to generate the image;
- create timestamped duplicate publication files when the stable article should be updated in place;
- use publication prose as semantic authority over newer source files;
- hide reader-facing article slots or image captions inside HTML comments;
- remove `Article Slot` or `Image Caption` blockquotes merely because publication is complete.
