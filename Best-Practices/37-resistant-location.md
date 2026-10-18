---
title: Prefer a resistant location when tails are long
tags: [practices, eda, location, robust]
status: verified
updated: 2026-10-17
---

# Prefer a resistant location when tails are long

The mean is pulled by extreme measurements. A median or another resistant center is the fairer summary when the tails are long.

The NIST/SEMATECH e-Handbook states: "Therefore the mean and median do not provide similar estimates for the location." ([Measures of Location](https://www.itl.nist.gov/div898/handbook/eda/section3/eda351.htm), checked 2026-10-17.)

## What to do

- Say which location you report and why.
- Do not switch from mean to median after seeing which one favors the claim.
- Match the location to the decision: a total still needs a mean.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read the histogram](28-read-the-histogram.md).
