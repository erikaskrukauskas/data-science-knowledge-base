---
title: Read a partial autocorrelation before you set an autoregressive order
tags: [practices, time-series]
status: verified
updated: 2026-10-19
---

# Read a partial autocorrelation before you set an autoregressive order

The partial autocorrelation is what you look at to choose an autoregressive order, and the ordinary autocorrelation alone confuses that order with longer echoes.

The NIST/SEMATECH e-Handbook states: "If the sample autocorrelation plot indicates that an AR model may be appropriate, then the sample partial autocorrelation plot is examined to help identify the order." ([Partial Autocorrelation Plot](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc4463.htm), checked 2026-10-19.)

## What to do

- Use the partial autocorrelation to see how many lags still matter after nearer lags are accounted for.
- State the order you chose and what the plot did past that lag.
- Do not pick the order from a software default.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Check autocorrelation](27-check-autocorrelation.md).
