---
title: Name the distributional assumption
tags: [practices, eda, distribution, assumptions]
status: verified
updated: 2026-10-17
---

# Name the distributional assumption

Probability statements that assume a shape are unsupported when the measurements have another shape.

The NIST/SEMATECH e-Handbook states: "The single distribution estimate may be meaningless (if the process distribution is changing)." ([Consequences Related to Distributional Assumptions](https://www.itl.nist.gov/div898/handbook/eda/section2/eda254.htm), checked 2026-10-17.)

## What to do

- State the shape you assumed.
- Check it with a probability plot or a goodness-of-fit comparison, not with the fit summary alone.
- If the shape fails, change the summary or drop the probability claim.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
