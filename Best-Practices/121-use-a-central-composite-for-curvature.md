---
title: Use a central composite design when the surface may curve
tags: [practices, design, response-surface]
status: verified
updated: 2026-10-19
---

# Use a central composite design when the surface may curve

A central composite design adds axial points to a factorial so the fitted surface can include curvature.

The NIST/SEMATECH e-Handbook states: "The star points represent new extreme values (low and high) for each factor in the design." ([Central Composite Designs (CCD)](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3361.htm), checked 2026-10-19.)

## What to do

- Start from the factorial that estimates the first-order effects, then add the axial points the curvature question needs.
- Put the axial points where the region you can actually run them is the region you will interpret.
- Center points still belong in the design so pure error is visible.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Add center points to see curvature](92-add-center-points-for-curvature.md).
