---
title: Use proportional hazards when a factor multiplies the hazard
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Use proportional hazards when a factor multiplies the hazard

A proportional-hazards model says a factor multiplies the hazard and does not change its shape over time, which is a strong assumption.

The NIST/SEMATECH e-Handbook states: "The proportional hazard model assumes changing a stress variable (or explanatory variable) has the effect of multiplying the hazard rate by a constant." ([Proportional hazards model](https://www.itl.nist.gov/div898/handbook/apr/section1/apr167.htm), checked 2026-10-19.)

## What to do

- State the factors you believe multiply the hazard.
- Check that the curves stay proportional. Crossing hazards violate the model.
- Do not interpret a coefficient as a change in the mean life unless you have carried it through the model.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Define the hazard you are estimating](185-define-the-hazard-you-are-estimating.md).
