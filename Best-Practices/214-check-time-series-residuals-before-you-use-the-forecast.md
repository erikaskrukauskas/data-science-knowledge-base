---
title: Check time-series residuals before you use the forecast
tags: [practices, time-series]
status: verified
updated: 2026-10-19
---

# Check time-series residuals before you use the forecast

A time-series model is not finished until its residuals look like noise, and a portmanteau check is one way to see leftover dependence.

The NIST/SEMATECH e-Handbook states: "If the autocorrelations are very small, we conclude that the model does not exhibit significant lack of fit." ([Box-Ljung Test](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc4481.htm), checked 2026-10-19.)

## What to do

- Plot the residual autocorrelations and state the check you used.
- Leftover dependence means the forecast intervals are wrong even when the point forecast looks smooth.
- Do not add lags until the residual plot is flat and then keep the largest model you tried without saying so.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Model dependence in a time series](101-model-time-series-dependence.md).
