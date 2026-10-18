---
title: Use Kolmogorov-Smirnov for a continuous comparison
tags: [practices, goodness-of-fit, distribution]
status: verified
updated: 2026-10-17
---

# Use Kolmogorov-Smirnov for a continuous comparison

The Kolmogorov-Smirnov check compares the empirical distribution with a reference distribution through the largest gap between them.

The NIST/SEMATECH e-Handbook states: "The Kolmogorov-Smirnov (K-S) test is based on the empirical distribution function (ECDF)." ([Kolmogorov-Smirnov Goodness-of-Fit Test](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35g.htm), checked 2026-10-17.)

## What to do

- It does not need bins. It is less sensitive to tails than Anderson-Darling.
- Say whether the reference distribution was fully specified before seeing the sample.
- Estimating the reference from the same sample and then testing it as if it were known overstates the agreement.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use Anderson-Darling as a fit check](55-anderson-darling-fit.md).
