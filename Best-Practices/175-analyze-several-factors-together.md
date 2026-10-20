---
title: Analyze several factors together when they were varied together
tags: [practices, comparison, anova]
status: verified
updated: 2026-10-19
---

# Analyze several factors together when they were varied together

Factors that were varied in the same experiment are analyzed together, because one-factor analyses hide their interactions and misstate the error.

The NIST/SEMATECH e-Handbook states: "In the multi-factor model, there is a response (dependent) variable and one or more factor (independent) variables." ([Multi-factor Analysis of Variance](https://www.itl.nist.gov/div898/handbook/eda/section3/eda355.htm), checked 2026-10-19.)

## What to do

- List the factors and the interactions you are willing to estimate.
- Look at interactions before you quote a main effect as if the other factors were absent.
- Do not split a factorial into a stack of one-factor tests.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a two-way layout when two factors are crossed](172-use-a-two-way-layout-when-two-factors-are-crossed.md).
