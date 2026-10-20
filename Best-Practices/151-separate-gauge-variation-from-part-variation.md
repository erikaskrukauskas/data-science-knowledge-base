---
title: Separate gauge variation from part variation
tags: [practices, measurement, variance]
status: verified
updated: 2026-10-19
---

# Separate gauge variation from part variation

A gauge study splits the observed spread into variation from the measurement and variation from the parts, and the two answer different questions.

The NIST/SEMATECH e-Handbook states: "The gauge study gathers the data and estimates standard deviations for sources that contribute to the uncertainty of the measurement result." ([Quantifying uncertainties from a gauge study](https://www.itl.nist.gov/div898/handbook/mpc/section4/mpc46.htm), checked 2026-10-19.)

## What to do

- Say what was repeated: the same part, the same operator, the same gauge.
- Use the gauge component when you are judging the measurement, and the part component when you are judging the process.
- Do not quote the total spread as the process spread when the gauge is a large part of it.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Separate variance components](111-separate-variance-components.md).
