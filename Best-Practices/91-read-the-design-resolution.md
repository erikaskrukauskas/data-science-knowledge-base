---
title: Read the design resolution before quoting effects
tags: [practices, experiment, resolution, confounding]
status: verified
updated: 2026-10-17
---

# Read the design resolution before quoting effects

Resolution says which effects are aliased.

The NIST/SEMATECH e-Handbook states: "Resolution and confounding The design resolution tells us how badly the design is confounded." ([Fractional factorial design specifications and design resolution](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3344.htm), checked 2026-10-17.)

## What to do

- A resolution III design ties main effects to two-factor interactions. Do not quote a main effect from it as if the interactions were absent, unless you state that assumption.
- Higher resolution costs more runs. That cost is the price of separating the effects.
- Write the alias before the conclusion.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the confounding](12-name-the-confounding.md).
