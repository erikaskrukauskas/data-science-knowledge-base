---
title: Model degradation when the failure is a threshold on a measured drift
tags: [practices, reliability, degradation]
status: verified
updated: 2026-10-19
---

# Model degradation when the failure is a threshold on a measured drift

When failure is defined as a measured characteristic crossing a threshold, the degradation path is the data, and waiting for failures can be the wrong experiment.

The NIST/SEMATECH e-Handbook states: "You can run low stress cells that are much closer to use conditions and obtain meaningful degradation data." ([Fitting models using degradation data instead of failures](https://www.itl.nist.gov/div898/handbook/apr/section4/apr423.htm), checked 2026-10-19.)

## What to do

- Define the failure threshold before you fit the paths.
- Model the paths, then infer the time at which they cross the threshold.
- Do not treat a unit that has not crossed the threshold as a failure, and do not ignore its path.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat censored lifetimes as incomplete, not as failures](114-censored-lifetimes-are-incomplete.md).
