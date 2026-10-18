---
title: Separate location from scale
tags: [practices, distribution, location, scale]
status: verified
updated: 2026-10-17
---

# Separate location from scale

Location says where the measurements sit. Scale says how widely they sit.

The NIST/SEMATECH e-Handbook states: "In contrast, the next graph has a scale parameter of 1/3 (=0." ([Location and Scale Parameters](https://www.itl.nist.gov/div898/handbook/eda/section3/eda364.htm), checked 2026-10-17.)

## What to do

- A change in scale is not a change in location.
- Report both when the decision cares about typical size and about risk in the tails.
- Do not describe a wider spread as a higher mean.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Prefer a resistant location when tails are long](37-resistant-location.md).
