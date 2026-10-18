---
title: Detect non-constant variation in the residuals
tags: [practices, residuals, variation]
status: verified
updated: 2026-10-17
---

# Detect non-constant variation in the residuals

Plot residuals against fitted values to see whether the spread changes.

The NIST/SEMATECH e-Handbook states: "When the functional part of the model does not fit the data well, the residuals do not reflect purely random variations in the process." ([How can I detect non-constant variation across the data?](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd442.htm), checked 2026-10-17.)

## What to do

- A fan shape means one residual standard deviation is the wrong uncertainty.
- This is a separate failure from a curve in the mean.
- Fix or report the changing spread before quoting a single prediction band.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Analyze residuals](11-analyze-residuals.md).
