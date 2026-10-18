---
title: Use a runs test as a check on order
tags: [practices, eda, runs, randomness]
status: verified
updated: 2026-10-17
---

# Use a runs test as a check on order

A runs test asks whether high and low values clump beyond what a random order would produce.

The NIST/SEMATECH e-Handbook states: "A runs test was performed for 200 measurements of beam deflection contained in the LEW." ([Runs Test for Detecting Non-randomness](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35d.htm), checked 2026-10-17.)

## What to do

- Use it as a check on the sequence, alongside the plot.
- A significant clump means the order is informative.
- Do not treat the test as proof of a cause.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Plot the run sequence](31-run-sequence-plot.md).
