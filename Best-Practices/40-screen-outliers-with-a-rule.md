---
title: Screen outliers with a declared rule
tags: [practices, eda, outliers]
status: verified
updated: 2026-10-17
---

# Screen outliers with a declared rule

An extreme point is not deleted because it is inconvenient.

The NIST/SEMATECH e-Handbook states: "It has the limitation that the number of outliers must be specified exactly." ([Detection of Outliers](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35h.htm), checked 2026-10-17.)

## What to do

- Declare the rule, such as a Grubbs screen, before you apply it.
- A point removed under that rule is reported as removed, with the reason.
- If the point is a real event the decision will see again, keep it and widen the description.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read a scatter plot](32-read-a-scatter-plot.md).
