---
title: Use a rank test when you will not assume a shape
tags: [practices, comparison, ranks]
status: verified
updated: 2026-10-19
---

# Use a rank test when you will not assume a shape

Kruskal-Wallis compares several groups by their ranks when you will not assume a common shape, and it does not estimate a difference of means.

The NIST/SEMATECH e-Handbook states: "The KW test determines whether these sums of ranks are so different by sample that they are not likely to have all come from the same population." ([How can we compare several populations with unknown distributions (the Kruskal-Wallis test)?](https://www.itl.nist.gov/div898/handbook/prc/section4/prc41.htm), checked 2026-10-19.)

## What to do

- Use it when the question is whether the groups share a common location and the distributional assumption is not one you will stand behind.
- Report that the comparison is on ranks.
- If you need the size of a mean difference, this test does not provide it.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Compare several groups as one question](53-one-factor-anova.md).
