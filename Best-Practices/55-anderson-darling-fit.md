---
title: Use Anderson-Darling as a fit check
tags: [practices, goodness-of-fit, distribution]
status: verified
updated: 2026-10-17
---

# Use Anderson-Darling as a fit check

The Anderson-Darling check asks whether measurements are consistent with a fully named distribution, with attention to the tails.

The NIST/SEMATECH e-Handbook states: "The Anderson-Darling test is an alternative to the chi-square and Kolmogorov-Smirnov goodness-of-fit tests." ([Anderson-Darling Test](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35e.htm), checked 2026-10-17.)

## What to do

- Use it after you have named the distribution, not as a search over many families.
- A failure means that distribution's probabilities are a poor description.
- Report the distribution you tested, not a vague claim of non-normality.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the distribution you are using](41-name-the-distribution.md).
