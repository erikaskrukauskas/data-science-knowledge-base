---
title: Read a half-normal plot of effects before keeping terms
tags: [practices, design, effects]
status: verified
updated: 2026-10-19
---

# Read a half-normal plot of effects before keeping terms

On an unreplicated two-level design, a half-normal plot is a way to see which effects stand away from the noise, not a proof that the small effects are zero.

The NIST/SEMATECH e-Handbook states: "The half-normal probability plot is a graphical tool that uses these ordered estimated effects to help assess which factors are important and which are unimportant." ([Half-normal probability plot](https://www.itl.nist.gov/div898/handbook/pri/section5/pri598.htm), checked 2026-10-19.)

## What to do

- Name the effects that leave the line, and the effects you are treating as noise.
- Do not drop an effect that the plot calls small if subject knowledge says it belongs in the model.
- Say that the plot uses the assumption that only a few effects are active.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read the design resolution before quoting effects](91-read-the-design-resolution.md).
