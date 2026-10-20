---
title: Chart individuals when you cannot form a rational subgroup
tags: [practices, control-chart]
status: verified
updated: 2026-10-19
---

# Chart individuals when you cannot form a rational subgroup

An individuals chart is the variables chart to use when each plotted point is one measurement, and an average chart pretends you had subgroups.

The NIST/SEMATECH e-Handbook states: "Analogous to the Shewhart control chart, one can plot both the data (which are the individuals) and the moving range." ([Individuals Control Charts](https://www.itl.nist.gov/div898/handbook/pmc/section3/pmc322.htm), checked 2026-10-19.)

## What to do

- Use it when one measurement is all you get in each period.
- Estimate the short-term variation from a moving range, and say so.
- Do not compute control limits for averages from data that were never grouped.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Chart a measured variable with limits from a stable period](100-chart-a-measured-variable.md).
