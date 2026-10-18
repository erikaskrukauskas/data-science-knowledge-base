---
title: Give a prediction its own uncertainty
tags: [practices, prediction, uncertainty]
status: verified
updated: 2026-10-17
---

# Give a prediction its own uncertainty

A prediction of a new observation is wider than an estimate of the mean function.

The NIST/SEMATECH e-Handbook states: "The plot below shows a 99 % prediction interval produced using the original data." ([Prediction](https://www.itl.nist.gov/div898/handbook/pmd/section1/pmd132.htm), checked 2026-10-17.)

## What to do

- Report the prediction uncertainty, not only the uncertainty of the fitted coefficient.
- A prediction outside the range of the fitted data is an extrapolation. Say so.
- The held-out check is a set of such predictions.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
