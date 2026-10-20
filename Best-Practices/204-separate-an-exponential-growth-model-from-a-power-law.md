---
title: Separate an exponential growth model from a power law
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Separate an exponential growth model from a power law

An exponential non-homogeneous Poisson process and a power-law process describe different ways a repair rate can change, and they are not two names for one curve.

The NIST/SEMATECH e-Handbook states: "If that shows obvious lack of fit, try the Exponential Law model, estimating parameters using the formulas in the Analysis Section for the Exponential law ." ([NHPP exponential law](https://www.itl.nist.gov/div898/handbook/apr/section1/apr193.htm), checked 2026-10-19.)

## What to do

- Plot the rate and see which form it follows.
- State which model you fit and what the parameter means.
- Do not choose the exponential law only because it is familiar from single-unit lifetimes.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a power-law process when the repair rate changes smoothly](192-use-a-power-law-process-when-the-repair-rate-changes.md).
