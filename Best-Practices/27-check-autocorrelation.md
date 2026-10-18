---
title: Check autocorrelation
tags: [practices, eda, autocorrelation, dependence]
status: verified
updated: 2026-10-17
---

# Check autocorrelation

Neighboring measurements that move together are not independent replicates.

The NIST/SEMATECH e-Handbook states: "If the autocorrelation plot is being used to test for randomness (i." ([Autocorrelation Plot](https://www.itl.nist.gov/div898/handbook/eda/section3/eda331.htm), checked 2026-10-17.)

## What to do

- Plot the autocorrelation before you treat each point as a fresh draw.
- Positive dependence makes the uncertainty look smaller than it is if you ignore it.
- A time-ordered split is the matching check when neighbors are dependent.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Leakage and held-out data](04-leakage-and-held-out-data.md).
