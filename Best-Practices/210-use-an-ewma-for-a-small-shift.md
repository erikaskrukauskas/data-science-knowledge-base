---
title: Use an EWMA when recent points should count more than old ones
tags: [practices, control-chart]
status: verified
updated: 2026-10-19
---

# Use an EWMA when recent points should count more than old ones

An exponentially weighted moving average chart gives more weight to recent points, and the weight is a decision about which shift you want to see.

The NIST/SEMATECH e-Handbook states: "As with all control procedures, the EWMA procedure depends on a database of measurements that are truly representative of the process." ([EWMA Control Charts](https://www.itl.nist.gov/div898/handbook/pmc/section3/pmc324.htm), checked 2026-10-19.)

## What to do

- State the weight. A weight near one is close to a Shewhart chart. A small weight smooths harder.
- Set the limits for that weight.
- Do not treat the EWMA value as the current measurement.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat exponential smoothing as a forecast](103-exponential-smoothing-is-a-forecast.md).
