---
title: Widen a calibration uncertainty where the curve bends
tags: [practices, measurement, calibration]
status: verified
updated: 2026-10-19
---

# Widen a calibration uncertainty where the curve bends

A curved calibration does not have one uncertainty everywhere, because the slope that propagates the error changes along the curve.

The NIST/SEMATECH e-Handbook states: "In this case, the uncertainty is reduced by including covariance terms, some of which are negative." ([Uncertainty for quadratic calibration using propagation of error](https://www.itl.nist.gov/div898/handbook/mpc/section3/mpc3671.htm), checked 2026-10-19.)

## What to do

- State the calibration function, including the quadratic term if you are using one.
- Report the uncertainty at the level where you will read the result.
- Do not quote the uncertainty from the middle of the curve at an end where the slope is different.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [A calibration inverts the fitted function](88-calibration-inverts-the-fit.md).
