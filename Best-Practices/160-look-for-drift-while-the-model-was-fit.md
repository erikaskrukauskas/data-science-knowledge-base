---
title: Look for drift while the model data were collected
tags: [practices, modeling, stability]
status: verified
updated: 2026-10-19
---

# Look for drift while the model data were collected

Drift during data collection gets absorbed into the fitted function unless you look for it in time order.

The NIST/SEMATECH e-Handbook states: "Run sequence plots of the residuals are used to check for drift in the process." ([How can I tell if there was drift in the measurement process?](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd443.htm), checked 2026-10-19.)

## What to do

- Plot residuals in the order the runs were made.
- A trend in that order is a measurement or process change, not a reason to add a factor term, until you have checked the cause.
- Randomize or block time when you can still change the plan.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat a non-random sequence as structure](23-non-random-sequence.md).
