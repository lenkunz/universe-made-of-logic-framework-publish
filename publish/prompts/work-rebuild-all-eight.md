# Work Prompt — Rebuild All Eight Published Framework Articles

Use this prompt for a full publication refresh after semantic source updates.

---

Work from the private GitHub repository:

`lenkunz/universe-made-of-logic-framework-publish`

Treat the repository as the source of truth.

## Required reads

Read first:

- `publish/README.md`
- `publish/manifest.md`
- `publish/guidelines.md`
- `memory/current-context.md`
- `memory/semantic-guardrails.md`
- `memory/workflow.md`
- `source/internal/url-list.md`
- all relevant files under `source/changes/`
- all eight maintained framework sources listed in `publish/manifest.md`

Use `source/where-the-framework-stands.md` as the live claim-status authority.

## Publication identity

All eight entries in `publish/manifest.md` are **already-published Substack articles**.

Do not treat this run as creating eight new publications.

Preserve each article's established publication identity and Substack URL, but rebuild its body and publication assets from the newest source semantics.

The established URLs are recorded in `publish/manifest.md` and `source/internal/url-list.md`.

## Task

Rebuild the complete eight-article publication set from the newest semantic sources.

For each article:

1. read its current canonical semantic source;
2. identify any recent semantic corrections affecting it;
3. rebuild the reader-facing article under the stable output path listed in `publish/manifest.md`;
4. preserve or add the correct article-slot comments using this exact form:
   - `<!-- Article Slot: URL: https://... -->`
5. use only the established URLs from `source/internal/url-list.md` / `publish/manifest.md`;
6. audit whether the article needs a hero image and/or inline conceptual images;
7. generate every image the final article actually needs;
8. save each generated image under the article's folder in `publish/assets/images/`;
9. embed each image directly in the article Markdown using a relative Markdown image link;
10. put an image-caption comment directly below each image using:
   - `<!-- Image Caption: ... -->`
11. update the article file in place under `publish/articles/`.

## Image rule

Do not leave image placeholders when the article needs an image.

Generate the actual image and commit it to the repository.

Images should be editorial conceptual illustrations that make one real relationship from the article easier to understand. Avoid generic cosmic/AI decoration and avoid visuals that imply stronger ontology than the source earns.

Prefer 16:9 for hero images unless the article requires another composition.

The article Markdown should already contain the image reference, for example:

`![Descriptive alt text](../assets/images/<article-slug>/<filename>.png)`

followed immediately by:

`<!-- Image Caption: concise caption text -->`

## Private repository note

The repo is private. Keep relative image links in the repository Markdown for durable project packaging.

Do not assume those private GitHub image URLs are public Substack hosting. The eventual Substack import/update must ingest the image itself.

The purpose of embedding the image in the Markdown is to make the repository package complete and let Work manage article-to-image relationships automatically, not to use private GitHub as public image hosting.

## Semantic rules

Do not:

- change primitive meanings;
- promote candidate physical correspondence to established framework ground;
- promote personal/Hope material into the canonical eight unless explicitly requested;
- collapse hosted, established/reusable, and independently seated into one condition;
- reintroduce primitive time, fixed-space container, force language, physical-energy-as-budget, or stale saturation language.

Use plain language and preserve the framework's own terms.

## Outputs

By the end of the run, the repository should contain:

- eight rebuilt Markdown files under `publish/articles/`;
- all required generated images under `publish/assets/images/<article-slug>/`;
- embedded Markdown image links already present in each article;
- image-caption comments;
- article-slot URL comments using the eight established Substack URLs;
- no temporary publication placeholders left behind.

## Final report

At the end, provide a concise report listing:

- the eight article files updated;
- image assets created or replaced per article;
- article-slot URLs used;
- any semantic issue that could not safely be resolved from the source.

Do not silently improvise around missing semantic authority.
