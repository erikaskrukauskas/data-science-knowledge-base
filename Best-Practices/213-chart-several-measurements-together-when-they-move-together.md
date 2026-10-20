---
title: Chart several measurements together when they move together
tags: [practices, control-chart, multivariate]
status: verified
updated: 2026-10-19
---

# Chart several measurements together when they move together

Hotelling's chart looks at several related measurements as one vector, so a shift that is small on each chart can still be a shift of the vector.

The NIST/SEMATECH e-Handbook states: "The Hotelling T-squared distance is a measure that accounts for the covariance structure of a multivariate normal distribution." ([Hotelling Control Charts](https://www.itl.nist.gov/div898/handbook/pmc/section3/pmc341.htm), checked 2026-10-19.)

## What to do

- Name the measurements in the vector and why they belong together.
- A signal on the joint chart is not yet a diagnosis of which measurement moved.
- Do not run a stack of univariate charts and ignore their correlation.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Scale variables before a principal-component summary](104-principal-components-need-a-scale.md).
