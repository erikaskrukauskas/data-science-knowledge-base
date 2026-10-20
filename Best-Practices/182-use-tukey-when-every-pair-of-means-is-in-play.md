---
title: Use Tukey when every pair of means is in play
tags: [practices, comparison, multiple-comparisons]
status: verified
updated: 2026-10-19
---

# Use Tukey when every pair of means is in play

Tukey's method compares every pair of means as one family, and it is the wrong adjustment when you only intended a few comparisons.

The NIST/SEMATECH e-Handbook states: "The Tukey procedure for unequal sample sizes is sometimes referred to as the Tukey-Kramer Method ." ([Tukey's method](https://www.itl.nist.gov/div898/handbook/prc/section4/prc471.htm), checked 2026-10-19.)

## What to do

- Say whether every pair was of interest, or only comparisons with a control.
- Report the intervals, not only which pairs were flagged.
- Do not apply a pairwise adjustment and then describe it as a single preplanned contrast.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Account for multiple comparisons](112-account-for-multiple-comparisons.md).
