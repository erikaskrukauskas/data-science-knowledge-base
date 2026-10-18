---
title: Read a lag plot
tags: [practices, eda, lag, dependence]
status: verified
updated: 2026-10-17
---

# Read a lag plot

A lag plot shows whether this measurement is tied to the one before it.

The NIST/SEMATECH e-Handbook states: "Several common patterns for lag plots are shown in the examples below." ([Lag Plot](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33f.htm), checked 2026-10-17.)

## What to do

- A cloud with no slope supports treating neighbors as weakly tied.
- A slope, a curve, or a cycle means the order carries information.
- Do not claim independent errors when the lag plot has a pattern.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Check autocorrelation](27-check-autocorrelation.md).
