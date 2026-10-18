---
title: Separate variance components
tags: [practices, variation, components]
status: verified
updated: 2026-10-17
---

# Separate variance components

When units sit inside batches, labs, or days, the total spread is a sum of layers.

The NIST/SEMATECH e-Handbook states: "Restricted maximum likelihood estimates of variance components The restricted maximum likelihood (REML) estimates of the variance components are generally preferable to the method of moments estimates." ([What are variance components?](https://www.itl.nist.gov/div898/handbook/prc/section4/prc44.htm), checked 2026-10-17.)

## What to do

- Estimate those layers separately.
- A difference that is large next to the within-batch spread may be ordinary batch-to-batch movement.
- The layer that matches the decision is the one to quote.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Replicate to separate error](16-replicate-to-separate-error.md).
