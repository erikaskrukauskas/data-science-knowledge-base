---
title: Model dependence in a time series
tags: [practices, time-series, dependence]
status: verified
updated: 2026-10-17
---

# Model dependence in a time series

A time series is an ordered sequence whose neighbors carry information.

The NIST/SEMATECH e-Handbook states: "Time Series Analysis is used for many applications such as: Economic Forecasting." ([Definitions, Applications and Techniques](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc41.htm), checked 2026-10-17.)

## What to do

- Model that dependence, or the forecasts and the intervals will be wrong.
- A shuffled series destroys the question.
- Say the time unit and what a step ahead means for the decision.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Check autocorrelation](27-check-autocorrelation.md).
