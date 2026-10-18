---
title: A calibration inverts the fitted function
tags: [practices, calibration, modeling]
status: verified
updated: 2026-10-17
---

# A calibration inverts the fitted function

Calibration here means using a fitted function backwards: observing the response and inferring the factor.

The NIST/SEMATECH e-Handbook states: "As a result, there are no analogs of the prediction interval or tolerance interval in calibration." ([Calibration](https://www.itl.nist.gov/div898/handbook/pmd/section1/pmd133.htm), checked 2026-10-17.)

## What to do

- The uncertainty of that inference is not the uncertainty of the forward fit.
- Stay inside the calibrated range.
- Do not treat an inverted prediction as more precise than the forward scatter allows.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Calibrate before you interpret](69-calibrate-before-you-interpret.md).
