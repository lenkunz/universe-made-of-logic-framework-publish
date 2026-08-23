# Framework Memory

This folder preserves **conversation continuity and reasoning context** for the My GUT Deduction / Universe Made of Logic project.

It exists so a new chat does not have to reconstruct the project from a giant handoff prompt.

## What memory is for

`memory/` answers questions such as:

- What distinctions did earlier discussions discover?
- Which tempting framings were corrected, and why?
- What terminology does the project mean in its own native sense?
- What is the active reasoning frontier right now?
- How should a new chat search and load context before continuing?

It is **not** the semantic authority for the framework.

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

## Public-repository guardrail

This repository is public. Keep this memory layer focused on project reasoning and publication continuity. Do not store unrelated private conversation history, credentials, account information, or sensitive personal material here.

## Maintenance rule

When a conversation materially changes the framework:

1. update the affected canonical source(s);
2. update `source/where-the-framework-stands.md` if claim status changes;
3. add or update a semantic change map when the correction is foundational;
4. update `memory/current-context.md` if the active frontier changed;
5. update `memory/reasoning-history.md` if an old interpretation was concluded, narrowed, redirected, superseded, or proven against.

Git history is the revision archive. Stable filenames should normally be updated in place.
