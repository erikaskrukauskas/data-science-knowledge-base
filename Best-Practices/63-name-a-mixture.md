---
title: Name a mixture instead of averaging two peaks
tags: [practices, eda, mixture, histogram]
status: verified
updated: 2026-10-17
---

# Name a mixture instead of averaging two peaks

Two peaks are evidence of two groups, not of one wide group.

The NIST/SEMATECH e-Handbook states: "Histogram from Mixture of 2 Normal Distributions Discussion of Unimodal and Bimodal The above is a histogram of the ZARR14." ([Histogram Interpretation: Bimodal Mixture of 2 Normals](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33e5.htm), checked 2026-10-17.)

## What to do

- Name the groups if you can. If you cannot, say the measurements are a mixture.
- A single mean falls between the groups and may describe no one.
- Do not force a normal model onto two peaks.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read the histogram](28-read-the-histogram.md).
