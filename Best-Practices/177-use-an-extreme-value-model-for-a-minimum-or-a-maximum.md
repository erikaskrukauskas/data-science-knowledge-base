---
title: Use an extreme-value model for a minimum or a maximum
tags: [practices, distribution, reliability]
status: verified
updated: 2026-10-19
---

# Use an extreme-value model for a minimum or a maximum

An extreme-value model is for a minimum or a maximum, and a normal model of the raw observations answers a different question.

The NIST/SEMATECH e-Handbook states: "One is based on the smallest extreme and the other is based on the largest extreme." ([Extreme Value Type I Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda366g.htm), checked 2026-10-19.)

## What to do

- Say whether you are modeling the smallest value, the largest value, or a weakest-link lifetime.
- Check the fit on the extreme-value scale you claimed.
- Do not report a normal mean as the typical minimum.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Choose a life distribution from the failure pattern](116-choose-a-life-distribution-from-the-failures.md).
