---
title: Use an optimal design when a classical design does not fit
tags: [practices, design]
status: verified
updated: 2026-10-19
---

# Use an optimal design when a classical design does not fit

An optimal design is a computed set of runs for a region or a model that a standard layout cannot match, and it is optimal only for the criterion and the model you named.

The NIST/SEMATECH e-Handbook states: "This optimality criterion results in minimizing the generalized variance of the parameter estimates for a pre-specified model." ([D-Optimal designs](https://www.itl.nist.gov/div898/handbook/pri/section5/pri521.htm), checked 2026-10-19.)

## What to do

- State the model the design was built to estimate, and the criterion.
- Changing the model changes which runs are optimal. Do not reuse the point list for a different model without saying so.
- Check the aliasing and the prediction variance in the region you care about, not only the optimality score.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Select an experimental design](09-select-an-experimental-design.md).
