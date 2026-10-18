---
title: Frame the decision
tags: [practices, framing, target, measurement]
status: verified
updated: 2026-10-17
---

# Frame the decision

State four things before fitting anything: the decision the analysis supports, the population, the target, and the check that defines done.

## The four statements

- **Decision.** The action, claim, or comparison the result is meant to support. A model score is not a decision.
- **Population.** Who or what the result applies to, including who is left out. A result computed on a convenience extract does not automatically apply to a wider group.
- **Target.** The quantity being estimated or predicted: the unit, the outcome, and the time window. Say what would count as the outcome occurring.
- **Check.** The comparison that defines done. Name the data the fitting step will not see, the metric or contrast, and what result would change the decision.

Write these in the project notes. Dataset names, column labels, and numeric thresholds stay in the project. See [Reusable and project knowledge](06-reusable-and-project-knowledge.md).

## A usable target

A usable target is observable at the time the decision needs it, defined the same way for every unit, and independent of the fitting procedure. If the label is built from a field that will not exist at decision time, the target is not yet defined. That is a leakage problem. See [Leakage and held-out data](04-leakage-and-held-out-data.md).

## The check

The check is fixed before looking at the result you will report. Changing the metric or the slice after seeing the number is a new analysis, and it needs its own check.

Done means the named check was run and the result, with its uncertainty, is written down. See [Report uncertainty, then record](05-report-uncertainty-then-record.md).

## Size the question

Ask one decision at a time when the answers depend on each other. A request that mixes a new target, a new split, and a new model class is hard to interpret when the result moves.
