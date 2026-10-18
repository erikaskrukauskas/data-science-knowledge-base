---
title: A moving average is a smoother, not a cause
tags: [practices, time-series, smoothing]
status: verified
updated: 2026-10-17
---

# A moving average is a smoother, not a cause

A moving average blends neighboring points so a trend is easier to see.

The NIST/SEMATECH e-Handbook states: "Smoothing data removes random variation and shows trends and cyclic components Inherent in the collection of data taken over time is some form of random variation." ([What are Moving Average or Smoothing Techniques?](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc42.htm), checked 2026-10-17.)

## What to do

- It is not a new measurement, and it creates dependence even when the raw series had little.
- Do not test the smoothed series as if the points were independent.
- Say the window. A longer window hides shorter changes.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Model dependence in a time series](101-model-time-series-dependence.md).
