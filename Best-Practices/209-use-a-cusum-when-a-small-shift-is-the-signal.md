---
title: Use a cusum when a small persistent shift is the signal
tags: [practices, control-chart]
status: verified
updated: 2026-10-19
---

# Use a cusum when a small persistent shift is the signal

A cusum accumulates deviations from a target, so a small shift that a Shewhart chart misses can cross the cusum limit.

The NIST/SEMATECH e-Handbook states: "If the process mean shifts upward, the charted CUSUM points will eventually drift upwards, and vice versa if the process mean decreases." ([Cusum Control Charts](https://www.itl.nist.gov/div898/handbook/pmc/section3/pmc323.htm), checked 2026-10-19.)

## What to do

- State the target and the shift size you designed the cusum to catch.
- A cusum is slower to forget. A large one-point spike is still easier to see on a Shewhart chart.
- Do not replace a Shewhart chart with a cusum without saying which shift you are buying sensitivity for.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Chart a measured variable with limits from a stable period](100-chart-a-measured-variable.md).
