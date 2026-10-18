---
title: Estimate life from censored data with a method that uses the censoring
tags: [practices, reliability, censoring, estimation]
status: verified
updated: 2026-10-17
---

# Estimate life from censored data with a method that uses the censoring

Parameter estimates from life data have to use the censored units as units that lasted at least until the censoring time.

The NIST/SEMATECH e-Handbook states: "Maximum likelihood estimation (except when the failure data are very sparse - i.e., only a few failures) is a more precise and flexible method." ([How do you estimate life distribution parameters from censored data?](https://www.itl.nist.gov/div898/handbook/apr/section4/apr41.htm), checked 2026-10-17.)

## What to do

- Say how many units failed and how many were still going.
- An estimate that uses only the failures is biased toward shorter life.
- Report the uncertainty. Small numbers of failures make the life percentile wide.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat censored lifetimes as incomplete, not as failures](114-censored-lifetimes-are-incomplete.md).
