---
title: Compare spreads with a resistant check
tags: [practices, comparison, variance]
status: verified
updated: 2026-10-17
---

# Compare spreads with a resistant check

A claim that groups differ in spread needs its own check. A mean comparison does not answer it.

The NIST/SEMATECH e-Handbook states: "We conclude that there is insufficient evidence to claim that the variances are not equal." ([Levene Test for Equality of Variances](https://www.itl.nist.gov/div898/handbook/eda/section3/eda35a.htm), checked 2026-10-17.)

## What to do

- Levene's check is built for that question and is less tied to a normal shape than a classic variance-ratio test.
- Say whether you compared centers, spreads, or both.
- Unequal spreads also change how a mean comparison should be read.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Do not assume fixed variation](25-changing-variation.md).
