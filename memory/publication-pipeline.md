# Publication Pipeline Memory

Updated: 2026-08-23
Status: CONTINUITY MEMORY / NOT FRAMEWORK GROUND

This is the default publication workflow from this point forward.

## Core separation

Semantic work and publication work are separate.

### Semantic phase

`discussion / deduction`
→ `audit`
→ `update affected source files under source/`
→ `update status/change map if needed`
→ `update memory if the active frontier changed`

### Publication phase

`current source/`
→ `publish/manifest.md identifies existing publication target(s)`
→ `Work reads publish/guidelines.md + relevant source`
→ `Work rebuilds publication Markdown under publish/articles/`
→ `Work generates images under publish/assets/images/<slug>/`
→ `Work embeds those images into the Markdown`
→ `visible Article Slot / Image Caption production blockquotes are already present where needed`
→ `public QA / Substack update`

## Eight-article set

The maintained framework publication set is registered in `publish/manifest.md`.

All eight are existing published identities. Preserve their URLs and roles during rebuilds.

Do not treat a full refresh as eight new articles.

Do not pre-generate article bodies merely to mark them published. `publish/articles/` should hold actual Work-generated publication output.

## Full rebuild prompt

Use:

`publish/prompts/work-rebuild-all-eight.md`

for a complete rebuild of the framework publication set.

Use:

`publish/prompts/work-refresh-one-or-more.md`

for targeted refreshes.

## Image workflow

Publication images are repository assets, not separate manual handoff files.

Work should:

1. determine which images are actually needed;
2. generate the images;
3. commit them under `publish/assets/images/<article-slug>/`;
4. embed them directly in the generated Markdown;
5. use a visible labelled blockquote such as `> **Image Caption:** ...` directly below an image when a caption/manual production marker is needed.

Companion article references use visible labelled blockquotes:

`> **Article Slot:** URL: ...`

using the established URLs in `source/internal/url-list.md` / `publish/manifest.md`.

Do not use hidden `<!-- ... -->` HTML comments for production instructions that the user needs to see outside a particular Markdown renderer.

These production blockquotes are not ordinary quoted prose. At the final Substack step, perform the indicated action and remove/convert the production marker as appropriate.

## Private repo caveat

The repository is private.

Relative image Markdown is the durable package inside GitHub, but private GitHub image URLs are not public Substack hosting. The publication/import step must ingest the image binary rather than relying on a private hotlink.

## Authority

This file records workflow only.

For semantics, `source/` wins.
For publication behavior, `publish/guidelines.md` wins unless the user's current instruction overrides it.
