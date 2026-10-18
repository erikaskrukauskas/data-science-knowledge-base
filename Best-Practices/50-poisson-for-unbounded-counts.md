---
title: Use a Poisson model for counts in an interval
tags: [practices, distribution, poisson, counts]
status: verified
updated: 2026-10-17
---

# Use a Poisson model for counts in an interval

A Poisson model is for a count of events in an interval of time or space, with no fixed cap.

The NIST/SEMATECH e-Handbook states: "Percent Point Function The Poisson percent point function does not exist in simple closed form." ([Poisson Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda366j.htm), checked 2026-10-17.)

## What to do

- The mean and the variance are tied together under this model.
- If the counts vary more than their mean, the Poisson uncertainty is too small.
- Say the interval the count refers to.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a binomial model for bounded counts](49-binomial-for-bounded-counts.md).
