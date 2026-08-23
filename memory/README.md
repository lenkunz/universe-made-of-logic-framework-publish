# Framework Memory

This folder preserves **conversation continuity and reasoning context** for the My GUT Deduction / Universe Made of Logic project.

It exists so a new chat does not have to reconstruct the project from a giant handoff prompt.

The repository is currently **private**, so this memory layer may preserve richer project-conversation continuity, including personal-origin intuitions when they directly shaped framework reasoning. It should still remain project-scoped and should never contain passwords, access tokens, credentials, or unrelated sensitive records.

## What memory is for

`memory/` answers questions such as:

- What distinctions did earlier discussions discover?
- Which tempting framings were corrected, and why?
- What terminology does the project mean in its own native sense?
- What is the active reasoning frontier right now?
- How should a new chat search and load context before continuing?
- Which personal/introspective origin ideas influenced a deduction without becoming framework ground?

It is **not** the semantic authority for the framework.

## Files

- `current-context.md` — active framework frontier and the minimum context a new reasoning chat should recover first.
- `semantic-guardrails.md` — fixed meanings and recurring interpretation traps.
- `reasoning-history.md` — important conversational corrections, dead branches, and why they resolved the way they did.
- `workflow.md` — source sync, semantic audit, publication rebuild, image, Bits, and migration workflow.
- `privacy-and-scope.md` — what is appropriate to preserve in the private memory layer.

## Authority order

When sources conflict, use this order:

1. **The user's current correction / current discussion**
2. **Active canonical sources under `source/`**
3. **`source/where-the-framework-stands.md` and semantic change maps under `source/changes/`**
4. **`memory/` continuity files**
5. **`source/internal/` working/editorial notes**
6. Older Git history

The separate Hope document remains explicitly personal/speculative and does not become framework ground merely because memory mentions it.

## Recommended new-chat load order

A future chat working on the framework should normally read:

1. `memory/current-context.md`
2. `memory/semantic-guardrails.md`
3. the specific canonical source relevant to the question
4. `source/where-the-framework-stands.md` when claim status matters
5. `memory/reasoning-history.md` only when the discussion refers to an older correction or abandoned route
6. `source/internal/working-notes.md` only when exploring unresolved branches

For publication or editorial tasks, also read `memory/workflow.md` and the relevant queue/checklist under `source/internal/`.

## Search rule

Do **not** load the whole repository by default.

Search by concept first, then open the few files that own that concept.

Examples:

- `Cut`, `resolution`, `Aim` → `memory/current-context.md`, `source/changes/cut-resolution-and-open-remainder.md`
- `budget`, `tick`, `CPU`, `relation composition` → `memory/current-context.md`, `source/changes/relation-origin-and-composed-budget.md`
- `Lane`, `Rung`, `hosted`, `independent seating` → `memory/semantic-guardrails.md`, `source/the-lane-and-the-rung.md`
- `gravity`, `dark matter`, `redshift`, `physical mapping` → `source/where-the-framework-stands.md`, then `source/internal/working-notes.md`
- old failed route / why wording changed → `memory/reasoning-history.md`
- publication candidate / old Short idea → `source/internal/short-notes-queue.md`
- Bits duplication check → `source/internal/bits-topic-checklist.md`

## Maintenance rule

When a conversation materially changes the framework:

1. update the affected canonical source(s);
2. update `source/where-the-framework-stands.md` if claim status changes;
3. add or update a semantic change map when the correction is foundational;
4. update `memory/current-context.md` if the active frontier changed;
5. update `memory/reasoning-history.md` if an old interpretation was concluded, narrowed, redirected, superseded, or proven against;
6. update the relevant `source/internal/` queue when the conversation changes publication or research planning.

Git history is the revision archive. Stable filenames should normally be updated in place.
