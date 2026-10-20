---
title: Combine responses with a desirability you can state
tags: [practices, design, optimization]
status: verified
updated: 2026-10-19
---

# Combine responses with a desirability you can state

When several responses must be optimized together, a desirability function is an explicit trade among them, not a property of the data.

The NIST/SEMATECH e-Handbook states: "A useful class of desirability functions was proposed by Derringer and Suich (1980) ." ([Multiple responses: The desirability approach](https://www.itl.nist.gov/div898/handbook/pri/section5/pri5322.htm), checked 2026-10-19.)

## What to do

- Write down the target, the limits, and the weight for each response before you combine them.
- Show the separate responses at the chosen point, not only the combined score.
- A different weighting is a different decision. Do not hide that choice inside the software default.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Define the result you report](18-define-the-result-you-report.md).
