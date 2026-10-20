---
title: Model a season instead of calling it noise
tags: [practices, time-series]
status: verified
updated: 2026-10-19
---

# Model a season instead of calling it noise

A repeating seasonal pattern is structure, and folding it into the residual makes the remaining model look noisier than the process is.

The NIST/SEMATECH e-Handbook states: "The seasonal subseries plot does an excellent job of showing both the seasonal differences (between group patterns) and also the within-group patterns." ([Seasonality](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc443.htm), checked 2026-10-19.)

## What to do

- Show the pattern across seasons before you remove it.
- State the season length in the units of the series.
- A deseasoned residual is not the original series. Say which one you are forecasting.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Model dependence in a time series](101-model-time-series-dependence.md).
