# Project Workflow Memory

Updated: 2026-08-23
Status: CONTINUITY MEMORY / NOT FRAMEWORK GROUND

This file explains how to continue the project after a chat migration without rebuilding the process from memory.

## Source roles

### `source/`

Stable current semantic sources. These are the files to edit when the framework itself changes.

### `source/changes/`

Foundational semantic change maps. Use them to understand why a current source differs from older wording and to prevent accidental rollback.

### `source/internal/`

Non-canonical project memory such as Working Notes, publication queues, URL lists, and Bits-topic tracking.

### `memory/`

Conversation continuity. This is for active frontier, semantic traps, reasoning history, and workflow. It should make a new chat usable without a giant handoff prompt.

## Authority order

1. User's current correction/instruction.
2. Current stable source under `source/`.
3. `source/where-the-framework-stands.md` and change maps.
4. `memory/` continuity files.
5. `source/internal/` exploratory/editorial notes.
6. Older Git history.

If memory disagrees with source, source wins unless the user is explicitly making a new correction.

## New-chat startup

For ordinary framework reasoning, load only what is needed:

1. `memory/current-context.md`
2. `memory/semantic-guardrails.md`
3. the canonical article(s) relevant to the question
4. `source/where-the-framework-stands.md` if status matters

Only then, if needed:

5. `memory/reasoning-history.md`
6. `source/internal/working-notes.md`

Do not ingest the whole repo by default.

## When the user says “sync this into the framework”

1. Fetch the current GitHub versions of the likely affected files.
2. Determine whether the new point is:
   - a rephrasing;
   - a semantic correction;
   - a new derived consequence;
   - a candidate correspondence;
   - completion pending;
   - unresolved mechanism;
   - or personal/speculative material.
3. Audit dependencies before editing.
4. Update only files whose meaning actually changes.
5. Update `source/where-the-framework-stands.md` if claim status changes.
6. Create/update a change map for foundational corrections.
7. Update `memory/current-context.md` if the active frontier changed.
8. Update `memory/reasoning-history.md` when an earlier interpretation is concluded, narrowed, redirected, superseded, or proven against.
9. Commit with a short semantic message.

Do not rewrite unrelated sources merely for wording consistency unless the user requests a publication rebuild.

## Semantic update vs publication rebuild

Keep these separate.

### Semantic update

Changes the source meaning or status.

`discussion`
→ `audit`
→ `canonical source update`
→ `status/change map`

### Publication rebuild

Takes already-settled source meaning and rebuilds reader-facing presentation.

`canonical source`
→ `Work / article rebuild`
→ `image-slot audit`
→ `generate needed images`
→ `public QA`
→ `publish`

Never use presentation prose as the authority for later semantic deduction if a newer canonical source exists.

## Image workflow for publication rebuilds

When a Work prompt rebuilds an article:

1. Preserve semantic image slots or create only slots that genuinely help understanding.
2. For every final hero/inline slot, specify a **Visual Intent** before generating.
3. Generate a copy-ready Flow/image prompt for each slot.
4. Prefer one strong editorial conceptual relationship over decorative complexity.
5. Avoid text, labels, equations, UI diagrams, generic cosmic-AI imagery, or visuals that silently add ontology.
6. Use 16:9 framing for article hero images unless the publication context says otherwise.
7. Images must not imply stronger physical claims than the source text earns.

## Publication source order

The main maintained reader-facing framework set is:

1. Basics I — Resolution costs
2. Basics II — Coarse is not blurry, weak, or absolute
3. Basics III — One and one make three
4. The Index of the Framework
5. A Universe Made of Logic
6. The Possibility Lane
7. The Lane and the Rung
8. Where the Framework Currently Stands

The Hope is separate personal/metaphysical context, not framework authority.

## Status discipline

Current-position labels:

- Derived
- Consequence
- Candidate correspondence
- Completion pending
- Unresolved mechanism
- Not established
- Guardrail

Resolution-history labels:

- Rephrased
- Reframed
- Concluded
- Narrowed
- Redirected
- Superseded
- Proven against

Do not use “open” as a catch-all. A missing number is not the same kind of problem as a missing mechanism.

## Deduction cadence

Preferred project rhythm from Working Notes:

- work through one major unresolved frontier at a time;
- after a meaningful resolution, sync status/source before opening several new branches;
- preserve side branches in Working Notes rather than letting them become accidental active ground.

## Bits workflow

Before preparing a new Bits topic:

1. read `source/internal/bits-topic-checklist.md`;
2. read the latest published/RSS list if available;
3. search the repo for the topic and close synonyms;
4. compare against high-overlap families and prepared-but-unpublished topics;
5. only then research and draft.

A repeated framework concept is allowed, but the external topic/question should make genuinely new work happen.

## Short Notes workflow

`source/internal/short-notes-queue.md` is publication planning, not reasoning authority.

A branch should move there only when it has one clear standalone question/mechanism that can be explained without requiring the whole framework first.

## Research workflow

For empirical comparisons:

- keep observed measurements and established equations as constraints;
- do not automatically import the conventional ontology used to interpret them;
- distinguish framework-native mechanism from candidate correspondence;
- prefer tests that could weaken or distinguish the framework rather than only examples that can be made to fit after the fact.

For the dark-sector branch, a particularly valuable discriminator is the predicted positive overlap-associated excess in merging halo overlap regions beyond simple additive superposition.

## Conversation migration rule

When a chat approaches its length limit, do **not** build a giant handoff prompt unless needed for something outside GitHub.

Instead:

1. sync any unsaved semantic changes;
2. update `memory/current-context.md` with the active frontier and newest unresolved question;
3. update reasoning history if a major correction occurred;
4. in the new chat, point to this repository and ask the assistant to load `memory/README.md` / `memory/current-context.md` first.

The goal is for migration to cost a few targeted reads, not a full reconstruction of the project.
