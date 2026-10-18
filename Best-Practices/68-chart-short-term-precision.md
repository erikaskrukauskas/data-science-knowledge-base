---
title: Chart short-term precision separately
tags: [practices, measurement, precision]
status: verified
updated: 2026-10-17
---

# Chart short-term precision separately

Short-term precision can worsen while the average stays put.

The NIST/SEMATECH e-Handbook states: "The upper control limit above is then derived based on the standard F test for equal standard deviations." ([Control chart for standard deviations](https://www.itl.nist.gov/div898/handbook/mpc/section2/mpc231.htm), checked 2026-10-17.)

## What to do

- Chart the spread of repeats, not only the level of the check standard.
- A wider short-term spread means later differences are harder to see.
- Do not assume precision stays at the value measured on the first day.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [State what reproducibility includes](13-state-what-reproducibility-includes.md).
