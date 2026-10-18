---
title: Choose a life distribution from the failure pattern
tags: [practices, reliability, distribution]
status: verified
updated: 2026-10-17
---

# Choose a life distribution from the failure pattern

Choose a life distribution by how failures accumulate: constant hazard, increasing, or decreasing, and by the shape of the censored sample.

The NIST/SEMATECH e-Handbook states: "Note that physical/statistical arguments for choosing a life distribution model are typically based on individual failure modes ." ([How do you choose an appropriate life distribution model?](https://www.itl.nist.gov/div898/handbook/apr/section2/apr21.htm), checked 2026-10-17.)

## What to do

- Plot the data on the matching scale.
- A distribution chosen only because software offers it is not a check.
- The choice is part of the claim about use life.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [An exponential model means a constant hazard](48-exponential-means-constant-hazard.md).
