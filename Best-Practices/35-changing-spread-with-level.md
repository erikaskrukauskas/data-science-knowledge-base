---
title: Treat spread that depends on level as part of the model
tags: [practices, eda, heteroscedasticity, variation]
status: verified
updated: 2026-10-17
---

# Treat spread that depends on level as part of the model

When the spread of the response changes with the level of the factor, the relationship has two parts: the center and the spread.

The NIST/SEMATECH e-Handbook states: "Heteroscedasticity complicates the analysis somewhat, but its effects can be overcome by proper weighting of the data with noisier data being weighted less, or by performing a transformation to achieve homoscedasticity." ([Scatter Plot: Variation of Y Does Depend on X (heteroscedastic)](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33q9.htm), checked 2026-10-17.)

## What to do

- Do not stop at a mean function.
- Say how the uncertainty changes across the range the decision will use.
- A transformation or a weighted fit is a response to that pattern, not a default.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Require constant spread when the method assumes it](34-constant-spread.md).
