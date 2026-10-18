---
title: Handle outliers before a group comparison
tags: [practices, comparison, outliers]
status: verified
updated: 2026-10-17
---

# Handle outliers before a group comparison

Outliers can create or hide a difference between groups.

The NIST/SEMATECH e-Handbook states: "A point beyond an outer fence is considered an extreme outlier ." ([What are outliers in the data?](https://www.itl.nist.gov/div898/handbook/prc/section1/prc16.htm), checked 2026-10-17.)

## What to do

- Find them before the comparison, with a declared rule, and say what you did.
- A comparison that exists only because of one point is a comparison about that point.
- Do not silently drop the point that hurts the claim.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Screen outliers with a declared rule](40-screen-outliers-with-a-rule.md).
