---
title: Judge the function apart from the noise
tags: [practices, modeling, residuals]
status: verified
updated: 2026-10-19
---

# Judge the function apart from the noise

The functional part of a model is sufficient when the residuals no longer carry a pattern the function should have explained.

The NIST/SEMATECH e-Handbook states: "It is important to plot the residuals versus every available variable to ensure that a candidate model is the best model possible." ([How can I assess the sufficiency of the functional part of the model?](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd441.htm), checked 2026-10-19.)

## What to do

- Look at residuals against the fitted values and against each predictor.
- A pattern that matches a missing curve or a missing factor means the function is not done.
- Noise around a flat residual plot is the variation the function does not claim to explain.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Analyze residuals](11-analyze-residuals.md).
