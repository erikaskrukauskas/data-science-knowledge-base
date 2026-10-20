---
title: Match a nested gauge study to the way the measurement is nested
tags: [practices, measurement, variance]
status: verified
updated: 2026-10-19
---

# Match a nested gauge study to the way the measurement is nested

Time-dependent measurement error is nested in time: repeats inside a run, runs inside a day. A crossed analysis invents interactions the study did not run.

The NIST/SEMATECH e-Handbook states: "Data collection and analysis are straightforward, and there is no reason to estimate interaction terms when dealing with time-dependent errors." ([2-level nested design](https://www.itl.nist.gov/div898/handbook/mpc/section4/mpc432.htm), checked 2026-10-19.)

## What to do

- Draw the nesting: repeats within runs, runs within days, or the levels this measurement actually has.
- Estimate the component at the level where the repeats occurred.
- Do not fit interactions among time layers that were nested rather than crossed.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Separate variance components](111-separate-variance-components.md).
