---
title: Use a local smooth when you will not name a function
tags: [practices, modeling, exploration]
status: verified
updated: 2026-10-19
---

# Use a local smooth when you will not name a function

A local smooth is a description of the trend when you will not commit to a function, and it is not a substitute for a stated model once you need parameters.

The NIST/SEMATECH e-Handbook states: "In fact, given the results it provides, LOESS could arguably be more efficient overall than other methods like nonlinear least squares." ([LOESS (aka LOWESS)](https://www.itl.nist.gov/div898/handbook/pmd/section1/pmd144.htm), checked 2026-10-19.)

## What to do

- Say what the smooth is for: seeing the trend, or checking a fitted function.
- A smooth has a span. State it, because a different span is a different picture.
- Do not report a smooth's curve as if its bend were an estimated physical parameter.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Select the function deliberately](79-select-the-function-deliberately.md).
