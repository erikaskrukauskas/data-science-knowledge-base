---
title: Check that successive errors are independent
tags: [practices, residuals, dependence]
status: verified
updated: 2026-10-17
---

# Check that successive errors are independent

Independence means one residual does not predict the next.

The NIST/SEMATECH e-Handbook states: "How can I assess whether the random errors are independent from one to the next?" ([How can I assess whether the random errors are independent from one to the next?](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd444.htm), checked 2026-10-17.)

## What to do

- Plot residuals in run order and look at their autocorrelation.
- Dependence does not always bias the fitted mean. It does misstate the uncertainty and the effective sample size.
- A time-ordered held-out check is the matching confirmation.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Check autocorrelation](27-check-autocorrelation.md).
