---
title: Do not correct a bias you cannot estimate
tags: [practices, measurement, bias, uncertainty]
status: verified
updated: 2026-10-17
---

# Do not correct a bias you cannot estimate

A bias suggested by a handful of comparisons may be real and still too poorly estimated to subtract.

The NIST/SEMATECH e-Handbook states: "The strategy for a significant bias is to apply a 'zero' correction." ([Bias with sparse data](https://www.itl.nist.gov/div898/handbook/mpc/section5/mpc5333.htm), checked 2026-10-17.)

## What to do

- The handbook's approach for that case is to apply no correction and to carry the uncertainty of that choice.
- Subtracting a noisy correction can move the result the wrong way.
- Say that you saw a possible shift and did not remove it.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Separate bias from accuracy](66-separate-bias-and-accuracy.md).
