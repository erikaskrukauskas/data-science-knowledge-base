---
title: Use an attributes chart for counts of events
tags: [practices, monitoring, attributes, counts]
status: verified
updated: 2026-10-17
---

# Use an attributes chart for counts of events

An attributes chart tracks counts: defectives in a sample, or defects per unit.

The NIST/SEMATECH e-Handbook states: "Types of attribute control charts Control charts dealing with the number of defects or nonconformities are called c charts (for count) ." ([What are Attributes Control Charts?](https://www.itl.nist.gov/div898/handbook/pmc/section3/pmc33.htm), checked 2026-10-17.)

## What to do

- Use it when the observation is a classification, not a measured amount.
- A variables chart on a made-up score is a different question.
- Changing sample size changes the limits. Say when the sample size changed.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a Poisson model for counts in an interval](50-poisson-for-unbounded-counts.md).
