---
title: Do not assume fixed variation
tags: [practices, eda, variation]
status: verified
updated: 2026-10-17
---

# Do not assume fixed variation

A single spread is the wrong summary when the measurements fan out or tighten.

The NIST/SEMATECH e-Handbook states: "The single variation estimate may be meaningless (if the process variation is drifting)." ([Consequences of Non-Fixed Variation Parameter](https://www.itl.nist.gov/div898/handbook/eda/section2/eda253.htm), checked 2026-10-17.)

## What to do

- Compare the spread in early and late stretches, and in low and high regions.
- If the spread changes, the uncertainty changes with it.
- Do not quote one standard deviation for a series whose spread moves.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
