# Integration Note — Anchor Closure

**Integration completed:** 2026-09-05 23:50 +07:00, maintained source revision `R20260905-2350-01`. See the [source-sync map](../changes/2026-09-05-stage-projection-and-bits-source-sync.md).

The guidance below records the original pending integration and is retained as history.

**Original purpose:** Manual integration guidance while the GitHub connector was unavailable.

The original package deliberately did **not** overwrite `source/where-the-framework-stands.md`, because the current repository version could not be fetched safely.

The authoritative new material for this update is:

`source/changes/2026-08-27-anchor-closure-and-relational-budget-comparison.md`

When updating the maintained framework summary, promote the following compact rules into the relevant budget / anchor / coarse-graining section.

## Suggested maintained-framework insertion

> **Budget is anchor-closed, not intrinsically isolated.** A budget comparison must include every consequential anchor relation participating in the question. A bare `B_x` is shorthand for a context whose relevant anchors have already been seated, absorbed, or shown to be common-mode.

> **Common anchor contributions may disappear from the explicit comparison only when they create no consequential distinction at the chosen grain.** This is coarse-graining, not absence.

> **Stable relations may be seated into composite budgets such as `B_lr`, `B_la`, or `B_ra` and compared again.** Different grouping orders are equivalent only when they preserve the same consequential relations.

> **If changing the grouping changes the result, inspect which relation was discarded, altered, or made consequential.**

## Files affected conceptually

This rule should be considered when future edits touch:

- budget/computational-support definitions;
- anchor definitions;
- clock comparison;
- gravity / gravitational redshift and blueshift;
- motion / projection;
- ruler contraction;
- cross-ground measurement;
- coarse-graining and “relation can participate as one”;
- any formula that compares bare `B_x` terms.

## Ruler Bit

The full v4 Bit package in this ZIP already incorporates the correction.

Do not apply the old v3 interpretation of `B_r` and `B_l` as context-free intrinsic budgets.

They are shorthand for the relevant anchor-closed source and receiver grounds.

## Suggested commit message

`Add anchor-closure rule and update ruler Bit`
