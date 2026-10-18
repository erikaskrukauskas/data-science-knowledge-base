---
title: Treat the normal model as an assumption
tags: [practices, distribution, normality]
status: verified
updated: 2026-10-17
---

# Treat the normal model as an assumption

The normal distribution is a model with a location and a scale, symmetric and light in the tails.

The NIST/SEMATECH e-Handbook states: "The following is the plot of the standard normal probability density function." ([Normal Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3661.htm), checked 2026-10-17.)

## What to do

- Use it when the measurements look like that.
- Do not use it for strong skew, a hard boundary at zero, or counts.
- Say when a later interval depends on this model.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a normal probability plot](30-normal-probability-plot.md).
