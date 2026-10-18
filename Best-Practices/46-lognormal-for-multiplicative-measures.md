---
title: Use a lognormal model for multiplicative measures
tags: [practices, distribution, lognormal]
status: verified
updated: 2026-10-17
---

# Use a lognormal model for multiplicative measures

A lognormal model fits measurements that become roughly symmetric on a log scale.

The NIST/SEMATECH e-Handbook states: "The case where &theta; equals zero is called the 2-parameter lognormal distribution." ([Lognormal Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3669.htm), checked 2026-10-17.)

## What to do

- Use it when the quantity grows by factors and stays positive.
- Report results on the scale the decision uses, and say that the model was fit on the log scale.
- A normal model on the raw scale will misstate the long upper tail.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the distribution you are using](41-name-the-distribution.md).
