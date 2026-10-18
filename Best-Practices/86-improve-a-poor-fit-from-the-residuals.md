---
title: Improve a poor fit from the residuals
tags: [practices, residuals, modeling]
status: verified
updated: 2026-10-17
---

# Improve a poor fit from the residuals

When a model fits poorly, change the part the residual plot identifies: the function, the spread, or the error distribution.

The NIST/SEMATECH e-Handbook states: "Fortunately, however, there are also techniques and tools to remedy many of the problems uncovered using residual analysis." ([If my current model does not fit the data well, how can I improve it?](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd45.htm), checked 2026-10-17.)

## What to do

- Do not add terms at random.
- Each change uses the data that revealed it, so the revealing data are no longer a clean confirmation.
- Hold out a further check, or call the revised fit exploratory.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Analyze residuals](11-analyze-residuals.md).
