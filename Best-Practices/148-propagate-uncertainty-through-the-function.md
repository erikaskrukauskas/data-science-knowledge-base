---
title: Propagate uncertainty through the function you are using
tags: [practices, measurement, uncertainty]
status: verified
updated: 2026-10-19
---

# Propagate uncertainty through the function you are using

When a reported result is a function of several measured inputs, the uncertainty has to be propagated through that function.

The NIST/SEMATECH e-Handbook states: "Thus, the type B evaluation of uncertainty is computed using propagation of error." ([Evaluation of type B uncertainty and propagation of error](https://www.itl.nist.gov/div898/handbook/mpc/section6/mpc64.htm), checked 2026-10-19.)

## What to do

- Write the function. Propagation through a different function is a different uncertainty.
- Include the covariance when the inputs are not independent.
- Say whether the propagation is a linear approximation.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Build an uncertainty budget before you combine components](147-build-an-uncertainty-budget.md).
