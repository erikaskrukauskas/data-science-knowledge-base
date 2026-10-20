---
title: Plot the cumulative hazard before you pick a life model
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Plot the cumulative hazard before you pick a life model

A cumulative-hazard plot is a picture of how risk accumulates with age, and the life distribution should match that picture.

The NIST/SEMATECH e-Handbook states: "Advantages of Cumulative Hazard Plotting It is much easier to calculate plotting positions for multicensored data using cumulative hazard plotting techniques." ([Hazard and cum hazard plotting](https://www.itl.nist.gov/div898/handbook/apr/section2/apr222.htm), checked 2026-10-19.)

## What to do

- Say whether the hazard is flat, rising, or falling.
- Pick the distribution from that pattern.
- Do not choose a distribution first and then ignore a hazard plot that contradicts it.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Choose a life distribution from the failure pattern](116-choose-a-life-distribution-from-the-failures.md).
