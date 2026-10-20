---
title: Use a power-law process when the repair rate changes smoothly
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Use a power-law process when the repair rate changes smoothly

A power-law non-homogeneous Poisson process lets the repair rate rise or fall as a power of time, and the power is the claim about growth or deterioration.

The NIST/SEMATECH e-Handbook states: "This name is confusing and should be avoided, however, since it mixes a life distribution model applicable to the lifetimes of a non-repairable population with a model for the inter-arrival times of failures of a repairable population." ([Non-Homogeneous Poisson Process (NHPP) - power law](https://www.itl.nist.gov/div898/handbook/apr/section1/apr172.htm), checked 2026-10-19.)

## What to do

- State whether the rate is increasing or decreasing, and report the power with its uncertainty.
- Do not use this model for a sudden change in rate caused by one known repair to the system.
- Keep the repairable-system interpretation. This is not a lifetime distribution for single-use units.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat reliability growth as a changing rate](117-reliability-growth-is-a-changing-rate.md).
