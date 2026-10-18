---
title: Compare distributions with a quantile plot
tags: [practices, distribution, quantiles]
status: verified
updated: 2026-10-17
---

# Compare distributions with a quantile plot

A quantile-quantile plot compares two distributions across their range.

The NIST/SEMATECH e-Handbook states: "Case Study The quantile-quantile plot is demonstrated in the ceramic strength data case study." ([Quantile-Quantile Plot](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33o.htm), checked 2026-10-17.)

## What to do

- A straight line supports a shared shape. A bend means they differ in the tails or the center.
- A mean comparison can miss a difference that lives in the tails.
- Use this plot when the decision cares about more than the average.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Compare two means on the same footing](52-compare-two-means.md).
