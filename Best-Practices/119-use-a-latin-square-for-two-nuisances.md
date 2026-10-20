---
title: Use a Latin square when two nuisances both matter
tags: [practices, design, blocking]
status: verified
updated: 2026-10-19
---

# Use a Latin square when two nuisances both matter

When two known nuisances each have as many levels as the treatment, a Latin square removes both from the treatment comparison.

The NIST/SEMATECH e-Handbook states: "The Latin square model assumes that there are no interactions between the blocking variables or between the treatment variable and the blocking variable." ([Latin square and related designs](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3321.htm), checked 2026-10-19.)

## What to do

- Name both nuisance factors and confirm each has the same number of levels as the treatment.
- Randomize within the square. The square is not a full factorial of the two nuisances.
- Do not use it when a treatment-by-nuisance interaction is the question you need to answer.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Block a known nuisance](14-block-a-known-nuisance.md).
