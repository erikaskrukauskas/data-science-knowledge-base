---
title: Treat a non-random sequence as structure
tags: [practices, eda, sequence, dependence]
status: verified
updated: 2026-10-17
---

# Treat a non-random sequence as structure

If the order of the measurements has a pattern, the errors are not interchangeable noise.

The NIST/SEMATECH e-Handbook states: "Non-Randomness Due to Autocorrelation One specific and common type of non-randomness is autocorrelation." ([Consequences of Non-Randomness](https://www.itl.nist.gov/div898/handbook/eda/section2/eda251.htm), checked 2026-10-17.)

## What to do

- Look at the measurements in the order they were taken.
- A drift, a cycle, or a clump of similar neighbors changes both the uncertainty and the split.
- Do not shuffle away a time order that the decision will face later.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Leakage and held-out data](04-leakage-and-held-out-data.md).
