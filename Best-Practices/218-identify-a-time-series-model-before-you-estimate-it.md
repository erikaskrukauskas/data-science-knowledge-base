---
title: Identify a time-series model before you estimate it
tags: [practices, time-series]
status: verified
updated: 2026-10-19
---

# Identify a time-series model before you estimate it

Box-Jenkins identification picks a small class of models from the autocorrelation and partial autocorrelation, and estimation comes after that choice.

The NIST/SEMATECH e-Handbook states: "The sample partial autocorrelation function is generally not helpful for identifying the order of the moving average process." ([Box-Jenkins Model Identification](https://www.itl.nist.gov/div898/handbook/pmc/section4/pmc446.htm), checked 2026-10-19.)

## What to do

- Show the plots that led to the order.
- Difference or transform first if that was required for stationarity, and say so.
- Do not start with a large model and delete terms until the fit looks quiet.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read a partial autocorrelation before you set an autoregressive order](207-read-a-partial-autocorrelation-before-an-autoregression.md).
