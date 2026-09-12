# Sources to Load into NotebookLM

## Required framework sources

- [ ] `source/evidence-and-interpretation.md`
  - Why NotebookLM needs it: canonical framework methodology for separating datum, interpretation, and evidential weight; defines `E_O(x) = <C,S,I,R,F^-1>` and the guardrail against promoting correspondence into a causal story.

- [ ] `source/changes/2026-09-11-ontology-conditioned-evidence.md`
  - Why NotebookLM needs it: records the status and reason for the new evidence methodology and what did not change.

## Bit-specific framework sources

- [ ] `source/evidence-and-interpretation.md`
  - Why NotebookLM needs it: supplies the exact framework-native hook: evidence as observation constraining available interpretations.

## External sources

- [ ] Stanford Encyclopedia of Philosophy, “Bayes’ Theorem” — https://plato.stanford.edu/entries/bayes-theorem/
  - Why NotebookLM needs it: authoritative conceptual treatment of conditional probability, likelihood, likelihood ratios, priors, and evidential support.
  - Established explanation supported: the same datum can support hypotheses differently depending on how well each predicts it and on prior/background probability.

- [ ] Stanford Encyclopedia of Philosophy, “Formal Epistemology” — https://plato.stanford.edu/entries/formal-epistemology/
  - Why NotebookLM needs it: concise treatment of theoretical fit, novel evidence, and prior plausibility.
  - Established explanation supported: fit to evidence and prior plausibility are distinct parts of updating belief.

- [ ] Stanford Encyclopedia of Philosophy, “Philosophy of Statistics” — https://plato.stanford.edu/entries/statistics/
  - Why NotebookLM needs it: broader context for Bayesian statistical inference and the distinction between likelihood and posterior probability.
  - Established explanation supported: Bayesian inference updates a prior distribution using likelihoods to obtain posterior probabilities.

## Episode-specific source

- [ ] `02-notebooklm-source.md`
  - This is the detailed narrative/research dossier for the episode and should normally be loaded into NotebookLM with the sources above.

## Source discipline

Keep Bayesian probability, philosophy of evidence, and framework interpretation separate. The framework profile is qualitative and must not be presented as a Bayes factor, posterior probability, or replacement for statistical inference.
