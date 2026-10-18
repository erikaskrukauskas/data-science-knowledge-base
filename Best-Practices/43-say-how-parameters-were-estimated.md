---
title: Say how the parameters were estimated
tags: [practices, estimation, likelihood]
status: verified
updated: 2026-10-17
---

# Say how the parameters were estimated

Maximum likelihood is one rule for estimating a distribution's parameters. It is not the only rule, and it favors the sample in hand.

The NIST/SEMATECH e-Handbook states: "The drawback is that you have to specify the maximum likelihood equations to the software." ([Maximum Likelihood](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3652.htm), checked 2026-10-17.)

## What to do

- Say that this was the rule.
- Check the fitted distribution against the measurements.
- A likelihood fit on the same data you use as proof is not a held-out check.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Leakage and held-out data](04-leakage-and-held-out-data.md).
