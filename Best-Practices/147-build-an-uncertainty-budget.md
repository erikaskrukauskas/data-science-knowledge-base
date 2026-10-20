---
title: Build an uncertainty budget before you combine components
tags: [practices, measurement, uncertainty]
status: verified
updated: 2026-10-19
---

# Build an uncertainty budget before you combine components

An uncertainty budget lists each component and how strongly the result depends on it, so a large sensitivity is not hidden inside a single combined number.

The NIST/SEMATECH e-Handbook states: "Uncertainty components are listed in a table along with their corresponding sensitivity coefficients, standard deviations and degrees of freedom." ([Uncertainty budgets and sensitivity coefficients](https://www.itl.nist.gov/div898/handbook/mpc/section5/mpc56.htm), checked 2026-10-19.)

## What to do

- List every component you are including and the ones you judged negligible.
- Report the sensitivity of the result to each component, not only the combined uncertainty.
- A component with a small standard uncertainty can dominate if the sensitivity is large.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [State a Type B uncertainty as a judgment, not as a repeat](146-state-a-type-b-uncertainty.md).
