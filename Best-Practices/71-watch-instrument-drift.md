---
title: Watch instrument drift during calibration
tags: [practices, measurement, drift, calibration]
status: verified
updated: 2026-10-17
---

# Watch instrument drift during calibration

Instrument drift during a calibration shifts later readings relative to earlier ones.

The NIST/SEMATECH e-Handbook states: "Representation of linear drift Linear drift for an even number of measurements is represented by ." ([Bias caused by instrument drift](https://www.itl.nist.gov/div898/handbook/mpc/section3/mpc3312.htm), checked 2026-10-17.)

## What to do

- A design that reverses or interleaves the order can separate drift from the values being calibrated.
- If you do not separate them, drift is aliased with the quantity you meant to measure.
- Say whether the calibration order could have produced the apparent differences.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the confounding](12-name-the-confounding.md).
