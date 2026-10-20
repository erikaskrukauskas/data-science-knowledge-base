---
title: Treat a mixture as a composition, not as independent factors
tags: [practices, design, mixture]
status: verified
updated: 2026-10-19
---

# Treat a mixture as a composition, not as independent factors

Mixture factors sum to a constant, so changing one component changes the others and an ordinary factorial misstates the experiment.

The NIST/SEMATECH e-Handbook states: "In a mixture experiment, the independent factors are proportions of different components of a blend." ([What is a mixture design?](https://www.itl.nist.gov/div898/handbook/pri/section5/pri54.htm), checked 2026-10-19.)

## What to do

- Write the constraint, usually that the components sum to one, before you choose the design.
- Interpret an effect as a change in composition, not as a change in one factor with the others held fixed.
- Do not report a mixture coefficient as if the components were independent knobs.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Select an experimental design](09-select-an-experimental-design.md).
