---
title: Match a Weibull model to lifetime data
tags: [practices, distribution, weibull, reliability]
status: verified
updated: 2026-10-17
---

# Match a Weibull model to lifetime data

A Weibull model is a lifetime model whose hazard can rise or fall.

The NIST/SEMATECH e-Handbook states: "The case where &mu; = 0 is called the 2-parameter Weibull distribution." ([Weibull Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3668.htm), checked 2026-10-17.)

## What to do

- Use it when the event is a time or a cycle to failure and the rate need not be constant.
- Check the fit on a Weibull plot before quoting a life percentile.
- Do not borrow an exponential model, which forces a constant hazard, when the plot curves.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the distribution you are using](41-name-the-distribution.md).
