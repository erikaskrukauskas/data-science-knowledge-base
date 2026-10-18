---
title: Scale variables before a principal-component summary
tags: [practices, multivariate, components]
status: verified
updated: 2026-10-17
---

# Scale variables before a principal-component summary

Principal components summarize correlated measurements into fewer directions.

The NIST/SEMATECH e-Handbook states: "Principal Component Analysis is a dimension-reduction tool that can be used advantageously in such situations." ([Principal Components](https://www.itl.nist.gov/div898/handbook/pmc/section5/pmc55.htm), checked 2026-10-17.)

## What to do

- The directions depend on the scale of each measurement. Standardize when the units differ, or the largest unit dominates.
- A component is a summary, not automatically a cause.
- Say what fraction of the variation the components you keep actually represent.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a scatterplot matrix](33-scatterplot-matrix.md).
