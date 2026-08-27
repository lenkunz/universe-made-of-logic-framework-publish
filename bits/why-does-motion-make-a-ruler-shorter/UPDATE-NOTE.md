# Update Note — V4 Anchor-Closed Budget Comparison

V4 preserves the v3 resolution-synchronization mechanism and corrects what `B_r` and `B_l` mean.

## New framework-wide rule

> **Before comparing budgets, close the anchors.**

A bare `B_x` is shorthand for a budget whose consequential anchor relations are already included, absorbed, or known to be common-mode.

If ambient anchor `a` matters, use explicit closures such as:

- `B_ra`
- `B_la`
- `B_lr ↔ B_a`

or another equivalent decomposition that preserves the same consequential relations.

## Common-anchor cancellation

A common anchor may disappear from the explicit formula only when it creates no consequential distinction at the chosen grain.

## Closure invariance

Different grouping orders should resolve to the same result only when they preserve the same consequential relations.

If grouping changes the result, inspect what relation was lost or changed.

## Ruler mechanism after correction

`unequal anchor-closed source/receiver support`
→ `different source resolution per receiver Cut`
→ `binding keeps one coherent relation`
→ `projection reconciles the mismatch`
→ `length/detail/frequency reading`

The v3 distinction remains:

- budget mismatch explains why reconciliation is required;
- projection geometry explains the clean simple contraction amount.

Suggested commit message:

`Add anchor-closure rule and update ruler Bit`
