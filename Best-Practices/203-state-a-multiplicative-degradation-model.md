---
title: State a multiplicative degradation model when damage multiplies
tags: [practices, reliability, degradation]
status: verified
updated: 2026-10-19
---

# State a multiplicative degradation model when damage multiplies

A multiplicative degradation model says damage accumulates by multiplication, and an additive fit on the raw measure is a different mechanism.

The NIST/SEMATECH e-Handbook states: "In other words, the increase in the amount of degradation from one instant to the next is a small random multiple of the total amount of degradation already present." ([Multiplicative degradation argument](https://www.itl.nist.gov/div898/handbook/apr/section2/apr213.htm), checked 2026-10-19.)

## What to do

- Say why multiplication matches the mechanism.
- Fit on the scale the model names, and show the path against the failure threshold.
- Do not add a linear trend on the raw measure and call it the multiplicative model.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Model degradation when the failure is a threshold on a measured drift](199-model-degradation-when-failures-are-rare.md).
