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
- `2026-08-27-anchor-closure-and-relational-budget-comparison.md`
- `2026-09-05-stage-projection-and-bits-source-sync.md`
- `2026-09-06-grain-sweep-and-repeated-comparison.md`
- `2026-09-07-recursive-compartments-and-relational-reach.md`
- `2026-09-08-budget-warped-perception-gravity-and-cosmology.md`
- `2026-09-11-seated-relation-attention-and-stage-resolution.md`

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

The last full-set source synchronization is **R20260905-2350-01 / 2026-09-05 23:50 +07:00**.

The latest scoped extension, **R20260906-0104-01**, adds [grain sweep and repeated comparison](source/changes/2026-09-06-grain-sweep-and-repeated-comparison.md) to the main source and status ledger. It records an exact conditional repeat sum with its physical identification still candidate. The new [Why Does Heat Draw a Curve?](bits/why-does-heat-draw-a-curve/00-manifest.md) package owns that spectral-shape question.

The latest semantic clarification, **R20260911-RHY-01**, records that a seated relation can remain consequential without continuous attention or fine rendering. It also separates immediate relational binding from budgeted Stage resolution and from any claim of controllable instantaneous signalling. See the [September 11 map](source/changes/2026-09-11-seated-relation-attention-and-stage-resolution.md).

The September 5 catch-up integrates Stage orientation, anchor closure, consequence-specific re-seating cost, scoped clock/ruler/twin deductions, the revised CMB spectrum question, and hosted participation/support-transfer architecture. The Cut/resolution and retained-history corrections remain foundational.

Read [the source-sync map](source/changes/2026-09-05-stage-projection-and-bits-source-sync.md) for the audit of all twelve current Bits, exact ownership, and candidate/completion boundaries. New exploratory action/perception and System discussion is preserved in [continuity](source/internal/2026-09-05-projection-hosting-and-system-continuity.md).

The weekly **Bits Source Check** reports future source gaps on Mondays around 09:00 Asia/Bangkok and archives results under `tasks/bits-source-check/`.

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
