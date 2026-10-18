---
title: Compare before choosing
tags: [practices, evaluation, metrics, splits, models]
status: verified
updated: 2026-10-17
---

# Compare before choosing

Before choosing a metric, a validation split, or a model class, name the real options and the constraint that decides among them. Then implement one.

## When to compare

Compare when more than one choice could answer the decision and the wrong choice is expensive to unwind:

- A metric that does not match the decision cost.
- A split that does not match the unit you need to generalize to.
- A model class that cannot represent the structure the decision depends on.

Skip the comparison write-up for a calculation with one obvious formula.

## What a comparison contains

- Two or three options that could actually be computed from the available measurements.
- The constraint that matters for this decision: the cost of each kind of error, the unit of generalization, leakage risk, or the explanation the decision needs.
- The option you will implement.
- What you looked at: a practice page, a lesson, or a current official source.

## Metric

Match the metric to the decision. A ranking metric, an error metric, and a calibration summary answer different questions. If the decision cares about a rare outcome or an unequal cost, say so before picking the summary number. Report the chosen metric on data the fitting step did not see.

## Split

The split is a claim about what "new" means. New rows of the same entity, a later time period, and a new site are different claims. Choose the split that matches the population in [Frame the decision](02-frame-the-decision.md). Fit preprocessing on the fitting portion only. See [Leakage and held-out data](04-leakage-and-held-out-data.md).

## Model class

Name the class by the structure it can represent and the assumptions it makes, not by a library. A simple baseline belongs in the comparison. Implement the chosen class. Do not leave two half-finished models as if both were the result.

Record the comparison in the project when it depends on that project's measurements. Record it here only when the chosen practice still helps after those measurements are removed.
