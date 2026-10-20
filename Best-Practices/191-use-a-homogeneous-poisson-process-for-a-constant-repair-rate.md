---
title: Use a homogeneous Poisson process for a constant repair rate
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Use a homogeneous Poisson process for a constant repair rate

A homogeneous Poisson process is the repair model in which the rate does not change with time, and it is the wrong model when repairs are getting more or less frequent.

The NIST/SEMATECH e-Handbook states: "The HPP is the only model that applies to that portion of the curve, so it is the most popular model for system reliability evaluation and reliability test planning." ([Homogeneous Poisson Process (HPP)](https://www.itl.nist.gov/div898/handbook/apr/section1/apr171.htm), checked 2026-10-19.)

## What to do

- Look at the inter-repair times, or a trend plot, before you adopt a constant rate.
- Say that a constant rate is an assumption, not a finding, until you have checked the trend.
- Switch to a non-homogeneous model when the rate is changing.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [An exponential model means a constant hazard](48-exponential-means-constant-hazard.md).
