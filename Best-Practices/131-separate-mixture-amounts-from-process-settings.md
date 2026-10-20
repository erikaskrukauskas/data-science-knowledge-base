---
title: Separate mixture amounts from process settings
tags: [practices, design, mixture]
status: verified
updated: 2026-10-19
---

# Separate mixture amounts from process settings

A mixture amount and a process setting are different kinds of factors, and a design that treats them as one list confuses composition with how the process was run.

The NIST/SEMATECH e-Handbook states: "Another option might be to run a fractional factorial design at each vertex or point of the mixture design, with the same fraction run at each mixture design point." ([Treating mixture and process variables together](https://www.itl.nist.gov/div898/handbook/pri/section5/pri545.htm), checked 2026-10-19.)

## What to do

- Label each column as a component or a process factor.
- State which process factors were held fixed while the composition changed, and which were varied.
- Do not interpret a process coefficient as a change in the recipe.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat a mixture as a composition, not as independent factors](129-treat-a-mixture-as-a-composition.md).
