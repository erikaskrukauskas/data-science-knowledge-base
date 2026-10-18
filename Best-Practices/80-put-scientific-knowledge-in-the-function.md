---
title: Put subject knowledge in the function
tags: [practices, modeling, functions]
status: verified
updated: 2026-10-17
---

# Put subject knowledge in the function

Subject knowledge can require a form: a known curve, a boundary, a factor that must appear.

The NIST/SEMATECH e-Handbook states: "There are many cases, however, for which there is incomplete scientific information available." ([Incorporating Scientific Knowledge into Function Selection](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd421.htm), checked 2026-10-17.)

## What to do

- Use that knowledge before a purely empirical search.
- A flexible curve that contradicts a known constraint is the wrong function even if the residual is smaller.
- Say which constraint the function honors.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Select the function deliberately](79-select-the-function-deliberately.md).
