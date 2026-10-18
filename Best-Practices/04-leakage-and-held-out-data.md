---
title: Leakage and held-out data
tags: [practices, evaluation, leakage, validation, splits]
status: verified
updated: 2026-10-17
---

# Leakage and held-out data

Check two failures before calling a result done: leakage into the fitting step, and a result that looks strong on the fitting data and fails on data that step did not see.

## Leakage

Leakage is information that would not be available at decision time, or information from the outcome, entering the inputs used to fit.

Look for:

- A feature built from the target, or from a near-copy of the target.
- A measurement timestamp that falls after the decision.
- An aggregate, encoding, or imputation fit on the full sample, including the rows held out for the check.
- The same entity, site, or time window appearing on both sides of the split when the claim is about a new entity, site, or period.
- A selection rule that uses the outcome to decide which rows are kept.

If any of these are true, the fitting step has seen more than the decision will see. Fix the inputs or the split and rerun the check.

## Held-out failure

A fit can agree with the data it was shown and still miss the population you claimed. The check named in [Frame the decision](02-frame-the-decision.md) uses data excluded from fitting, from preprocessing fit on that data, and from any choice that was tuned on that data.

When you use the held-out result to change the metric, the features, or the model class, that data is no longer a clean check. Set aside a further portion, or say that the reported figure is exploratory.

## What to report

State the split unit, what was fit only on the fitting portion, and the metric on the excluded data. A training score alone does not define done. Pair the held-out number with uncertainty. See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
