---
title: Read a 4-plot
tags: [practices, eda, assumptions, graphics]
status: verified
updated: 2026-10-17
---

# Read a 4-plot

Check location, spread, and distribution on the same series before you trust a simple model.

The NIST/SEMATECH e-Handbook states: "If the run sequence plot is flat and non-drifting, the fixed-location assumption holds." ([Interpretation of 4-Plot](https://www.itl.nist.gov/div898/handbook/eda/section2/eda24.htm), checked 2026-10-17.)

## What to do

- Use a run-sequence view, a lag view, a histogram, and a normal probability view together when the handbook's 4-plot is the check.
- A failure on any one panel is a failed assumption, not a cosmetic defect.
- Do not repair one panel by ignoring the others.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Analyze residuals](11-analyze-residuals.md).
