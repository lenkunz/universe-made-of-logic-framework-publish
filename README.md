# Universe Made of Logic Framework — Source Repository

This private repository is the durable source, continuity, and publication store for the **My GUT Deduction / Universe Made of Logic** project.

It is designed so the project can survive chat-length limits without rebuilding context from a giant handoff prompt, and so publication rebuilds can be driven directly from the repository.

## Active layout

### `source/`

Current stable semantic sources. These are the active files to edit when the framework itself changes.

Main maintained set:

- `source/basics-1-resolution-costs.md`
- `source/basics-2-coarse-is-not.md`
- `source/basics-3-one-and-one-make-three.md`
- `source/the-index-of-the-framework.md`
- `source/a-universe-made-of-logic.md`
- `source/the-possibility-lane.md`
- `source/the-lane-and-the-rung.md`
- `source/where-the-framework-stands.md`

The older partial `source/canonical/` directory is historical. Do not use it as the active sync target when a stable file exists directly under `source/`.

### `source/changes/`

Foundational semantic change maps. These preserve why definitions changed and prevent accidental rollback.

Current maps include:

- `relation-origin-and-composed-budget.md`
- `cut-resolution-and-open-remainder.md`

### `source/internal/`

Working/editorial/research memory that is useful but not automatically framework ground.

Includes:

- `working-notes.md` — index into the preserved split Working Notes source;
- `short-notes-queue.md` — index into the current split publication queue;
- `bits-topic-checklist.md` — duplication/selection guard for Bits;
- `url-list.md` — established publication URLs.

### `source/the-hope-behind-the-framework.md`

Personal metaphysical motivation kept explicitly separate from framework ground.

### `memory/`

Search-oriented conversation continuity.

Start a new framework chat with:

1. `memory/current-context.md`
2. `memory/semantic-guardrails.md`
3. the specific canonical source relevant to the question
4. `source/where-the-framework-stands.md` when claim status matters

Use `memory/conversation-index.md` to route “we discussed this before” questions without loading the whole repository.

Use `memory/reasoning-history.md` only when the older reasoning path matters.

Use `memory/workflow.md` for source sync, publication, image, Bits, and migration workflow.

### `publish/`

Standing downstream publication pipeline.

- `publish/manifest.md` — registry of the eight maintained already-published framework articles, their source paths, output paths, asset folders, and established Substack URLs.
- `publish/guidelines.md` — active publication/image rules.
- `publish/prompts/` — reusable Work prompts.
- `publish/articles/` — Work-generated publication-ready Markdown.
- `publish/assets/images/` — Work-generated publication images embedded by the Markdown.

The default publication workflow is now:

`source semantic update`
→ `publish manifest identifies affected article(s)`
→ `Work reads source + publish instructions`
→ `Work rebuilds Markdown`
→ `Work generates/commits images`
→ `Markdown embeds those images`
→ `public QA / Substack update`

For a complete refresh of the maintained framework set, use:

`publish/prompts/work-rebuild-all-eight.md`

## Authority order

When material conflicts:

1. the user's current correction / current discussion;
2. active stable semantic sources directly under `source/`;
3. `source/where-the-framework-stands.md` and `source/changes/`;
4. `publish/guidelines.md` for publication behavior only;
5. `memory/` continuity files;
6. `source/internal/` exploratory/editorial material;
7. older Git history.

Publication output is downstream and never outranks the semantic source.

The Hope remains personal/speculative even though this repository is private.

## Current semantic generation

The current source generation is based on the **2026-08-23 14:21 +07:00** Cut/Resolution clarification:

- **The Cut is relation.**
- A seated Cut/relation is already **resolution at that grain**.
- What the same relation does not make consequential remains the **open possibility remainder** relative to that ground.
- A real Aim is already seated relational constraint at its grain; the remaining debt is coarse-to-fine mapping, not an Aim-to-topology crossing.
- Budget is relational resolving participation / iteration capacity, not universal elapsed time.
- Relation composes effective capacity through already-seated structure.

## Revision discipline

Stable repository filenames should normally be updated in place. Internal revision headers plus Git history provide the revision archive.

When a semantic correction changes framework ground:

1. update only affected canonical sources;
2. update the live status ledger if claim status changes;
3. add/update a change map for foundational corrections;
4. update `memory/current-context.md` when the active frontier changes;
5. update reasoning history when an earlier interpretation is concluded, narrowed, redirected, superseded, or proven against;
6. then rebuild affected publication output through `publish/`.

For reader-facing publication, rebuild from current semantic sources rather than treating older public prose as semantic authority.
