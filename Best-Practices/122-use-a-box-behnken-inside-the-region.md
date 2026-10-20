---
title: Use a Box-Behnken design to stay inside the region
tags: [practices, design, response-surface]
status: verified
updated: 2026-10-19
---

# Use a Box-Behnken design to stay inside the region

A Box-Behnken design estimates a curved surface without running the corner points of the cube.

The NIST/SEMATECH e-Handbook states: "In this design the treatment combinations are at the midpoints of edges of the process space and at the center." ([Box-Behnken designs](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3362.htm), checked 2026-10-19.)

## What to do

- Choose it when the corners of the factor space are unsafe, impossible, or outside the process you will run.
- Say which factors are in the design. The design does not estimate every higher-order interaction a full factorial would.
- Keep the reported optimum inside the points you actually ran.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Keep the optimum inside the experimental region](93-keep-the-optimum-in-the-experimental-region.md).
