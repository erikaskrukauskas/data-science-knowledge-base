---
title: Bin a chi-square fit check on purpose
tags: [practices, goodness-of-fit, counts]
status: verified
updated: 2026-10-17
---

# Bin a chi-square fit check on purpose

A chi-square goodness-of-fit check compares observed counts with a named distribution in bins you can describe.

The NIST/SEMATECH e-Handbook states: "The chi-square test is an alternative to the Anderson-Darling and Kolmogorov-Smirnov goodness-of-fit tests." ([Chi-Square Goodness-of-Fit Test](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35f.htm), checked 2026-10-17.)

## What to do

- Choose the bins from the question, not from the binning that makes the result look closest.
- Sparse bins make the check unstable.
- This check does not replace a plot of the shape.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read the histogram](28-read-the-histogram.md).
