---
title: State the least-squares assumptions
tags: [practices, estimation, least-squares, residuals]
status: verified
updated: 2026-10-17
---

# State the least-squares assumptions

Least squares estimates a mean function by minimizing squared errors.

The NIST/SEMATECH e-Handbook states: "Software Non-linear least squares fitting is available in many general purpose statistical software programs." ([Least Squares](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3653.htm), checked 2026-10-17.)

## What to do

- The usual uncertainty around it assumes errors that are independent, with stable spread.
- If those fail, the point estimate may still be useful and the usual interval may not.
- Say which assumption you checked.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Analyze residuals](11-analyze-residuals.md).
