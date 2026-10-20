---
title: Test a spread against a named standard
tags: [practices, comparison, variance]
status: verified
updated: 2026-10-19
---

# Test a spread against a named standard

A comparison of an observed spread with a standard value needs a procedure for the standard deviation, and it assumes a shape.

The NIST/SEMATECH e-Handbook states: "A chi-square test can be used to test if the variance of a population is equal to a specified value." ([Chi-Square Test for the Standard Deviation](https://www.itl.nist.gov/div898/handbook/eda/section3/eda358.htm), checked 2026-10-19.)

## What to do

- State the standard value and where it came from.
- State the distributional assumption. A normal-based spread test is not a resistant check.
- Report the estimated spread next to the standard, not only the test result.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the distribution you are using](41-name-the-distribution.md).
