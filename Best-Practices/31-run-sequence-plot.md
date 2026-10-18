---
title: Plot the run sequence
tags: [practices, eda, sequence, drift]
status: verified
updated: 2026-10-17
---

# Plot the run sequence

Plot the measurements against the order they were collected before you pool them.

The NIST/SEMATECH e-Handbook states: "The run sequence plot is useful for checking for constant location and scale." ([Run-Sequence Plot](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33p.htm), checked 2026-10-17.)

## What to do

- A shift, a trend, or a sudden jump is a change in the process, not a larger sample.
- The order is part of the evidence.
- A random-looking sequence is what an independent-error claim needs.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat a non-random sequence as structure](23-non-random-sequence.md).
