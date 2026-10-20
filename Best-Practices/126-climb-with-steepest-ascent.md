---
title: Climb with steepest ascent only inside a local plane
tags: [practices, design, optimization]
status: verified
updated: 2026-10-19
---

# Climb with steepest ascent only inside a local plane

Steepest ascent moves along the fitted first-order slope, and it is a search path, not a proven optimum.

The NIST/SEMATECH e-Handbook states: "A first-order model will serve as a good local approximation in a small region close to the initial operating conditions and far from where the process exhibits curvature." ([Single response: Path of steepest ascent](https://www.itl.nist.gov/div898/handbook/pri/section5/pri5311.htm), checked 2026-10-19.)

## What to do

- Fit the local plane in the region you just ran, then step along that slope.
- Stop the climb when the response stops improving or the plane no longer fits.
- Do not report the path as the optimum once curvature shows up.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Keep the optimum inside the experimental region](93-keep-the-optimum-in-the-experimental-region.md).
