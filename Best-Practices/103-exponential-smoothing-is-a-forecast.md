---
title: Treat exponential smoothing as a forecast
tags: [practices, time-series, forecasting]
status: verified
updated: 2026-10-17
---

# Treat exponential smoothing as a forecast

Exponential smoothing is a way to forecast a series by weighting recent points more than old ones.

The NIST/SEMATECH e-Handbook states: "Single , double and triple Exponential Smoothing will be described in this section." ([What is Exponential Smoothing?](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc43.htm), checked 2026-10-17.)

## What to do

- The smoothing constant is a choice. Compare it on forecast error, not on how smooth the picture looks.
- A forecast that was tuned on the whole series is not a fair check of the last stretch.
- Hold out the last period and score the forecasts there.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Give a prediction its own uncertainty](87-prediction-has-its-own-uncertainty.md).
