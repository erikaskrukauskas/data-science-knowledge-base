---
title: Report skewness instead of forcing symmetry
tags: [practices, eda, skewness, distribution]
status: verified
updated: 2026-10-17
---

# Report skewness instead of forcing symmetry

Skewness and kurtosis describe shape that a mean and a standard deviation omit.

The NIST/SEMATECH e-Handbook states: "Skewness is a measure of symmetry, or more precisely, the lack of symmetry." ([Measures of Skewness and Kurtosis](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35b.htm), checked 2026-10-17.)

## What to do

- If the measurements are skewed, an interval that assumes symmetry will miss on one side.
- Say the direction of the skew.
- Do not delete the long tail only to restore a symmetric summary.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the distributional assumption](26-distributional-assumption.md).
