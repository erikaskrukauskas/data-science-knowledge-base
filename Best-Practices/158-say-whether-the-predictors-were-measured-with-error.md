---
title: Say whether the predictors were measured with error
tags: [practices, modeling, measurement]
status: verified
updated: 2026-10-19
---

# Say whether the predictors were measured with error

Ordinary regression treats the predictors as known, and predictor measurement error changes both the fit and the meaning of the coefficients.

The NIST/SEMATECH e-Handbook states: "This results in parameter estimators that are biased and will not approach the true parameter values no matter how much data are collected." ([The explanatory variables are observed without error.](https://www.itl.nist.gov/div898/handbook/pmd/section2/pmd216.htm), checked 2026-10-19.)

## What to do

- Say whether each predictor was set, like a design factor, or measured with its own uncertainty.
- If a predictor is measured with error large enough to matter, the ordinary coefficient is the wrong summary.
- Do not interpret a slope as a structural effect when the horizontal variable is as noisy as the response.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [State the least-squares assumptions](44-least-squares-needs-its-assumptions.md).
