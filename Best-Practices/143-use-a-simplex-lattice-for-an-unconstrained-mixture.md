---
title: Use a simplex lattice for an unconstrained mixture
tags: [practices, design, mixture]
status: verified
updated: 2026-10-19
---

# Use a simplex lattice for an unconstrained mixture

A simplex lattice places the runs on the composition space so the mixture model you named can be estimated.

The NIST/SEMATECH e-Handbook states: "A {3,2} simplex-lattice design is used to study the blending process." ([Simplex-lattice designs](https://www.itl.nist.gov/div898/handbook/pri/section5/pri542.htm), checked 2026-10-19.)

## What to do

- Match the lattice degree to the mixture model you intend to fit.
- Use it when every component can range from zero to one. Constraints call for a different design.
- Interpret the fit in compositions, not in independent factor units.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat a mixture as a composition, not as independent factors](129-treat-a-mixture-as-a-composition.md).
