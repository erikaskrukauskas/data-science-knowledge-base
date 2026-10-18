---
title: Do not assume a fixed location
tags: [practices, eda, location, drift]
status: verified
updated: 2026-10-17
---

# Do not assume a fixed location

A mean computed over a drifting series describes no single period.

The NIST/SEMATECH e-Handbook states: "The single location estimate may be meaningless (if the process is drifting)." ([Consequences of Non-Fixed Location Parameter](https://www.itl.nist.gov/div898/handbook/eda/section2/eda252.htm), checked 2026-10-17.)

## What to do

- Split the series where the level changes and report each level.
- A trend is part of the result, not a nuisance to delete without saying so.
- If the decision needs one number, say which period it belongs to.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Define the result you report](18-define-the-result-you-report.md).
