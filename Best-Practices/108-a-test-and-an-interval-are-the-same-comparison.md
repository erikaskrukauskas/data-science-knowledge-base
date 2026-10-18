---
title: Read a test and an interval as the same comparison
tags: [practices, comparison, interval, tests]
status: verified
updated: 2026-10-17
---

# Read a test and an interval as the same comparison

For the same comparison, a test and a confidence interval agree: the interval excludes the claimed value exactly when the test rejects that value, at the matching level.

The NIST/SEMATECH e-Handbook states: "$$ Equivalent confidence interval In fact, all values bracketed by this interval would be accepted as null values for a given set of test data." ([What is the relationship between a test and a confidence interval?](https://www.itl.nist.gov/div898/handbook/prc/section1/prc15.htm), checked 2026-10-17.)

## What to do

- If they disagree, they are not the same comparison.
- Prefer the interval because it shows the size of the difference.
- Do not report a test that rejects equality and an interval that contains no practical difference without explaining the practical size.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Report the interval, not only whether a hurdle was cleared](106-report-the-interval-not-only-the-p.md).
