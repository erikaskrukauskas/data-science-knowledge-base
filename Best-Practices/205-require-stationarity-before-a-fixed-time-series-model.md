---
title: Require stationarity before a fixed time-series model
tags: [practices, time-series]
status: verified
updated: 2026-10-19
---

# Require stationarity before a fixed time-series model

A fixed autoregressive model assumes the series' level and dependence do not change with time, and a drifting series violates that assumption.

The NIST/SEMATECH e-Handbook states: "Transformations to Achieve Stationarity If the time series is not stationary, we can often transform it to stationarity with one of the following techniques." ([Stationarity](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc442.htm), checked 2026-10-19.)

## What to do

- Look at the run sequence and the dependence before you fit.
- Difference, detrend, or narrow the window if that is the transformation you are willing to defend.
- Do not report constant coefficients for a series whose level is walking away.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Model dependence in a time series](101-model-time-series-dependence.md).
