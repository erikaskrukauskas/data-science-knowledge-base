---
title: Use a scatterplot matrix
tags: [practices, eda, scatter, multivariate]
status: verified
updated: 2026-10-17
---

# Use a scatterplot matrix

When several measurements are used together, look at each pair before fitting a joint model.

The NIST/SEMATECH e-Handbook states: "Although the basic concept of the scatterplot matrix is simple, there are numerous alternatives in the details of the plots." ([Scatterplot Matrix](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33qb.htm), checked 2026-10-17.)

## What to do

- A matrix shows which pairs move together and which pairs are driven by a point that sits apart.
- A coefficient list is not a substitute for that look.
- Drop or transform a pair whose plot contradicts the form you planned to fit.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read a scatter plot](32-read-a-scatter-plot.md).
