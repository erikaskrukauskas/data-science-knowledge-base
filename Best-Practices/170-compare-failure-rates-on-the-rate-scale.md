---
title: Compare failure rates on the rate scale
tags: [practices, comparison, reliability]
status: verified
updated: 2026-10-19
---

# Compare failure rates on the rate scale

Two lifetime processes are compared on their failure rates or mean times to failure, and a comparison of raw means ignores the lifetime model.

The NIST/SEMATECH e-Handbook states: "In this case, comparing two exponential distributions is equivalent to comparing their means (or the reciprocal of their means, known as their hazard rates)." ([Assuming the observations are failure times, are the failure rates (or Mean Times To Failure) for two distributions the same?](https://www.itl.nist.gov/div898/handbook/prc/section3/prc34.htm), checked 2026-10-19.)

## What to do

- State the life distribution or the constant-rate assumption.
- Account for censored units in both groups.
- Report the rates, or the mean times, and an interval for the comparison.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [An exponential model means a constant hazard](48-exponential-means-constant-hazard.md).
