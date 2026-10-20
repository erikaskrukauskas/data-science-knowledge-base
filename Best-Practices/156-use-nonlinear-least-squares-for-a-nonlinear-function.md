---
title: Use nonlinear least squares when the function is nonlinear in the parameters
tags: [practices, modeling]
status: verified
updated: 2026-10-19
---

# Use nonlinear least squares when the function is nonlinear in the parameters

A function that is nonlinear in its parameters needs a nonlinear fit, and transforming it into a straight line answers a different fitting problem.

The NIST/SEMATECH e-Handbook states: "These last two criteria are not essential parts of the definition of a nonlinear least squares model, but are of practical importance." ([Nonlinear Least Squares Regression](https://www.itl.nist.gov/div898/handbook/pmd/section1/pmd142.htm), checked 2026-10-19.)

## What to do

- Write the function and the parameters.
- Say what starting values you used and whether the fit reached a stable solution.
- A linear fit to a transformed response is not the same criterion as nonlinear least squares on the original response.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Select the function deliberately](79-select-the-function-deliberately.md).
