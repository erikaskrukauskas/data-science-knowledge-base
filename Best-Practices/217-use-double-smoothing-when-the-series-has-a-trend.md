---
title: Use double smoothing when the series has a trend
tags: [practices, time-series]
status: verified
updated: 2026-10-19
---

# Use double smoothing when the series has a trend

Single exponential smoothing lags a trend. Double smoothing is the forecast to consider when the series has a local slope you are willing to project.

The NIST/SEMATECH e-Handbook states: "The equation is similar to the basic form of single smoothing, but here applied to the updating of the trend." ([Double Exponential Smoothing](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc433.htm), checked 2026-10-19.)

## What to do

- Show the trend you are asking the method to follow.
- State both smoothing constants.
- A projected slope is still a forecast. Check it against later observations.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat exponential smoothing as a forecast](103-exponential-smoothing-is-a-forecast.md).
