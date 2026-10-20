---
title: An optimal design is optimal only for the model you named
tags: [practices, design, modeling]
status: verified
updated: 2026-10-19
---

# An optimal design is optimal only for the model you named

A design that is optimal for one model and one criterion is not automatically the right design for the question.

The NIST/SEMATECH e-Handbook states: "All optimal designs need a model; without a model, the optimal design-generation methodology cannot be used, and general design principles must be reverted to." ([I've heard some people refer to "optimal" designs, shouldn't I use those?](https://www.itl.nist.gov/div898/handbook/pmd/section3/pmd34.htm), checked 2026-10-19.)

## What to do

- State the model and the criterion the design optimizes.
- Check how the design behaves if the model is missing a term you might need later.
- A classical design you can interpret is often the better choice when it fits the region.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use an optimal design when a classical design does not fit](134-use-an-optimal-design-when-the-region-is-irregular.md).
