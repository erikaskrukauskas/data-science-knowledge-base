---
title: Use a two-way layout when two factors are crossed
tags: [practices, comparison, anova]
status: verified
updated: 2026-10-19
---

# Use a two-way layout when two factors are crossed

Two factors that are crossed need a two-way analysis, because a one-way analysis of either factor pools the other factor into the error.

The NIST/SEMATECH e-Handbook states: "An experiment that utilizes every combination of factor levels as treatments is called a factorial experiment." ([The two-way ANOVA](https://www.itl.nist.gov/div898/handbook/prc/section4/prc437.htm), checked 2026-10-19.)

## What to do

- Name both factors and whether every combination was observed.
- Look at the interaction before you interpret a main effect.
- Do not average over a factor that changes the effect of the factor you are reporting.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Check for an interaction](17-check-for-an-interaction.md).
