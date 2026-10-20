---
title: Use a systematic effect order for a two-level factorial
tags: [practices, design, effects]
status: verified
updated: 2026-10-19
---

# Use a systematic effect order for a two-level factorial

Yates' order is a systematic way to turn a two-level factorial into effect estimates, and it estimates only the effects the design can support.

The NIST/SEMATECH e-Handbook states: "The Yates algorithm exploits the special structure of these designs to generate least squares estimates for factor effects for all factors and all relevant interactions." ([Yates Analysis](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35i.htm), checked 2026-10-19.)

## What to do

- Confirm the data are in the order the algorithm assumes.
- Read the aliases before you name an interaction.
- A spreadsheet column of effects is not evidence that every column is a real process effect.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read a half-normal plot of effects before keeping terms](136-read-a-half-normal-plot-of-effects.md).
