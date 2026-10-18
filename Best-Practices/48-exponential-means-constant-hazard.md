---
title: An exponential model means a constant hazard
tags: [practices, distribution, exponential, reliability]
status: verified
updated: 2026-10-17
---

# An exponential model means a constant hazard

The exponential model says the chance of the event in the next interval does not depend on how long the unit has already lasted.

The NIST/SEMATECH e-Handbook states: "The exponential distribution is used to model data with a constant failure rate (indicated by the hazard plot which is simply equal to a constant)." ([Exponential Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3667.htm), checked 2026-10-17.)

## What to do

- Use it only when that memoryless claim is plausible.
- If older units fail faster or slower, the model is the wrong one.
- Say that a constant hazard was assumed whenever you quote an exponential mean life.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Match a Weibull model to lifetime data](47-weibull-for-lifetimes.md).
