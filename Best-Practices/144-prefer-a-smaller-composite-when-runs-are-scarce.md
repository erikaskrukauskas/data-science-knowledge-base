---
title: Prefer a smaller composite only when you can say what it gives up
tags: [practices, design, response-surface]
status: verified
updated: 2026-10-19
---

# Prefer a smaller composite only when you can say what it gives up

A small composite design saves runs by estimating a curved surface with less precision or more aliasing than a full central composite.

The NIST/SEMATECH e-Handbook states: "It also provides poor interaction coefficient estimates and should not be used unless the error variability is negligible compared to the systematic effects of the factors." ([What are small composite designs?](https://www.itl.nist.gov/div898/handbook/pri/section5/pri58.htm), checked 2026-10-19.)

## What to do

- Say which terms the smaller design can still estimate.
- Compare the run savings with the precision you lose before you adopt it.
- Do not describe it as equivalent to a full central composite.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a central composite design when the surface may curve](121-use-a-central-composite-for-curvature.md).
