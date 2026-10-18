---
title: Bootstrap the sampling spread of a summary
tags: [practices, uncertainty, bootstrap]
status: verified
updated: 2026-10-17
---

# Bootstrap the sampling spread of a summary

A bootstrap plot shows how a summary changes across resamples of the data in hand.

The NIST/SEMATECH e-Handbook states: "The jacknife is a technique that is closely related to the bootstrap." ([Bootstrap Plot](https://www.itl.nist.gov/div898/handbook/eda/section3/eda334.htm), checked 2026-10-17.)

## What to do

- Use it to see the sampling spread of a summary whose usual formula is a poor match.
- It does not create information about a population the sample never represented.
- Say that the resamples reuse the same measurements.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Pair a mean with an interval](51-interval-for-a-mean.md).
