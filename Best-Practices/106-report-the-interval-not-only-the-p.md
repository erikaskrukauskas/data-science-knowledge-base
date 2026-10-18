---
title: Report the interval, not only whether a hurdle was cleared
tags: [practices, comparison, p-value, interval]
status: verified
updated: 2026-10-17
---

# Report the interval, not only whether a hurdle was cleared

A p-value is the chance of a result at least this extreme if the stated claim were true.

The NIST/SEMATECH e-Handbook states: "The null hypothesis is rejected if the test statistic lies within this region which is often referred to as the rejection region." ([Critical values and p values](https://www.itl.nist.gov/div898/handbook/prc/section1/prc131.htm), checked 2026-10-17.)

## What to do

- It is not the probability the claim is true, and it is not the size of the effect.
- Report the estimate and the interval beside any such hurdle.
- A small p-value with a tiny effect can be irrelevant to the decision.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Pair a mean with an interval](51-interval-for-a-mean.md).
