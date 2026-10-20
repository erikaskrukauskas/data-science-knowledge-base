---
title: Respect the constraints on a mixture
tags: [practices, design, mixture]
status: verified
updated: 2026-10-19
---

# Respect the constraints on a mixture

When components have lower or upper limits, the design has to live inside that restricted region.

The NIST/SEMATECH e-Handbook states: "Note that the existence of lower bounds does not affect the shape of the mixture region, it is still a simplex region." ([Constrained mixture designs](https://www.itl.nist.gov/div898/handbook/pri/section5/pri544.htm), checked 2026-10-19.)

## What to do

- Write every component limit before you pick points.
- A design that ignores a limit will recommend compositions you cannot make.
- Say whether the reported optimum sits on a constraint boundary.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat a mixture as a composition, not as independent factors](129-treat-a-mixture-as-a-composition.md).
