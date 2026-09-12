# Why Can the Same Evidence Mean Different Things?

*An observation can stay fixed while the explanations around it move.*

Slug: `why-can-the-same-evidence-mean-different-things`

## The ordinary puzzle

Imagine a medical test comes back positive. The result is real. The laboratory does not need to have made a mistake. Yet the question “How likely is the patient to have the disease?” still cannot be answered from the positive result alone.

We also need to know how often the test is positive when the disease is present, how often it is positive when the disease is absent, and how common the disease was before the test. This is the familiar terrain of conditional probability and Bayes’ theorem.

The same separation appears almost everywhere we reason from observations to explanations. A strange light in the sky is an observation. “Aircraft,” “planet,” “satellite,” “camera artifact,” and “unknown object” are interpretations. Recording the light more accurately improves the datum, but it does not magically collapse all those interpretations into one.

The central lesson is simple:

> **Evidence is not the same thing as the explanation of the evidence.**

## What Bayes’ theorem makes explicit

For a hypothesis `H` and evidence `E`, Bayes’ theorem can be written:

`P(H|E) = P(E|H) P(H) / P(E)`

The terms matter because they answer different questions.

- `P(H)` is the prior probability assigned to the hypothesis before this new evidence.
- `P(E|H)` is the likelihood: how expected the evidence would be if the hypothesis were true.
- `P(H|E)` is the posterior probability after conditioning on the evidence.

A common reasoning error is to confuse `P(E|H)` with `P(H|E)`. A test can be very likely to return positive when a disease is present without a positive result implying that disease is nearly certain, especially when the disease is rare and false positives exist.

For comparing two hypotheses, the likelihood ratio is especially revealing:

`LR = P(E|H1) / P(E|H2)`

The evidence favors `H1` over `H2` to the extent that `H1` makes the observation more expected than `H2` does. If both explanations make the observation equally unsurprising, the observation does little to distinguish them.

This is why “the evidence fits my explanation” is too weak. The important question is often:

> **Would this evidence also have been easy to get if my explanation were wrong?**

## Same observation, different background

Two people can agree completely about a datum yet disagree about its evidential force because they begin with different background assumptions or priors.

That does not make every interpretation equally good. Evidence can strongly discriminate between hypotheses. But its force is relational: it depends on what hypotheses are being compared and what each would have led us to expect.

The Stanford Encyclopedia of Philosophy’s treatment of Bayes emphasizes this separation between prior probability, likelihood, and posterior probability. Its formal-epistemology discussion likewise notes that evidence must be weighed together with prior plausibility. Bayesian statistics makes this explicit by updating a prior distribution using likelihoods to obtain a posterior distribution.

## Surprise is useful, but only comparatively

Suppose an observation would be extremely surprising under one hypothesis but ordinary under another. That asymmetry can make the observation powerful evidence between those hypotheses.

But “surprising” by itself is not enough. A rare event can be rare under every explanation. And after seeing an event, humans can often invent a story that makes it sound inevitable. This is why chronology and prediction matter. A specific expectation recorded before an event constrains interpretation more strongly than a flexible story assembled afterward.

This does not mean only numerical predictions count. It means the freedom to reinterpret after the fact matters when judging evidential strength.

## The framework connection

My GUT Deduction’s current evidence methodology was added precisely to preserve this distinction.

Its canonical statement is:

> **Evidence is observation becoming constraint on the available interpretations.**

It proposes the qualitative reference profile:

`E_O(x) = <C, S, I, R, F^-1>`

where:

- `C` = chronology constraint: was the relevant claim or structure recorded before the observation?
- `S` = specificity: how narrowly does the observation match the prior structure?
- `I` = independence: how little was the observation deliberately searched for, selected, constructed, or prompted?
- `R` = recurrence: does the same class of correspondence recur across separately encountered events or domains?
- `F` = interpretive freedom: how many comparably easy reinterpretations could manufacture a match?

This is deliberately **not a numerical probability score**. It is a bookkeeping vocabulary for asking why one correspondence may constrain interpretation more than another without pretending that uncertainty has already been reduced to a single number.

The framework also preserves an important guardrail: a correspondence can count as evidence relevant to an ontology without proving a specific causal story inside that ontology. A match does not by itself establish intention, a sender, a hidden mechanism, or a “tutorial.” Those require additional constraint.

## Where the analogy stops

The framework’s `C/S/I/R/F` profile is not Bayes’ theorem. It does not calculate posterior probabilities. It does not supply likelihoods. It does not solve model selection. It should not be dressed up as a statistical replacement.

The useful connection is narrower: both approaches resist treating a datum as if it carried one interpretation printed on its surface.

Bayesian inference asks how the datum changes comparative probability under explicit models and priors. The framework methodology asks, at a qualitative ontology level, how an observation constrains interpretations while guarding against semantic drift and post-hoc freedom.

## Why this matters outside statistics

The distinction is useful whenever people argue over unusual observations, historical evidence, scientific measurements, medical tests, forensic clues, or everyday coincidences.

Disagreement can hide in several places:

1. people may disagree about what actually happened;
2. they may agree on the observation but disagree about which hypotheses are live;
3. they may assign different background plausibility to those hypotheses;
4. they may disagree about how expected the observation would be under each hypothesis;
5. they may allow different amounts of interpretive flexibility after seeing the result.

Saying only “we disagree about the evidence” can blur all five together.

A cleaner conversation begins by freezing the observation first.

**What did we actually observe?**

Then:

**Which interpretations does that observation make harder to maintain, and which does it leave almost untouched?**

## Closing thought

A fact does not have to change for its meaning as evidence to change. Sometimes what changes is the set of explanations around it.

That suggests a useful final question:

> **When two people see the same fact and reach different conclusions, are they really disagreeing about the fact, or about the world in which that fact would be surprising?**

## External research references

- Stanford Encyclopedia of Philosophy, “Bayes’ Theorem”: https://plato.stanford.edu/entries/bayes-theorem/
- Stanford Encyclopedia of Philosophy, “Formal Epistemology”: https://plato.stanford.edu/entries/formal-epistemology/
- Stanford Encyclopedia of Philosophy, “Philosophy of Statistics”: https://plato.stanford.edu/entries/statistics/

## Status boundary

Bayesian probability and the cited philosophy of evidence are established external material. My GUT Deduction’s ontology-conditioned evidence profile is framework methodology. Similarity between them is interpretive structure, not proof of the framework and not a claim that the framework has independently derived Bayesian statistics.
