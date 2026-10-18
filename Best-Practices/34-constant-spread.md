---
title: Require constant spread when the method assumes it
tags: [practices, eda, variation, heteroscedasticity]
status: verified
updated: 2026-10-17
---

# Require constant spread when the method assumes it

Some fits treat the vertical spread as the same across the horizontal range.

The NIST/SEMATECH e-Handbook states: "Scatter Plot: Variation of Y Does Not Depend on X (homoscedastic) ." ([Scatter Plot: Variation of Y Does Not Depend on X (homoscedastic)](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33q8.htm), checked 2026-10-17.)

## What to do

- If the cloud is a wedge, that assumption has failed.
- Report the changing spread, or use a method that allows it.
- A single residual standard deviation misstates the uncertainty in the wide part of the wedge.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Do not assume fixed variation](25-changing-variation.md).
