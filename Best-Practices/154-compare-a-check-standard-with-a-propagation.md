---
title: Compare a check standard with a propagation
tags: [practices, measurement, uncertainty]
status: verified
updated: 2026-10-19
---

# Compare a check standard with a propagation

A check standard and a propagation estimate uncertainty in different ways, and a disagreement between them is a finding about the budget.

The NIST/SEMATECH e-Handbook states: "The check standard measurements are undoubtedly sampling some sources of variability that do not appear in the formal propagation of error formula." ([Comparison of check standard analysis and propagation of error](https://www.itl.nist.gov/div898/handbook/mpc/section3/mpc3673.htm), checked 2026-10-19.)

## What to do

- Say which components the propagation includes.
- Treat a check-standard spread that is larger than the propagation as evidence that a component is missing.
- Do not average the two uncertainties to make the disagreement disappear.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Keep a check standard](64-keep-a-check-standard.md).
