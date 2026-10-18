---
title: Weight points when spread changes
tags: [practices, modeling, least-squares, variation]
status: verified
updated: 2026-10-17
---

# Weight points when spread changes

Weighted least squares gives less influence to observations that are known to be noisier.

The NIST/SEMATECH e-Handbook states: "Weighted least squares minimization is usually done analytically for linear models and numerically for nonlinear models." ([Weighted Least Squares](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd432.htm), checked 2026-10-17.)

## What to do

- Use it when the spread changes and you can say how.
- Weights chosen after looking at which points hurt the claim are not a method. They are an edit.
- Say the weight rule.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat spread that depends on level as part of the model](35-changing-spread-with-level.md).
