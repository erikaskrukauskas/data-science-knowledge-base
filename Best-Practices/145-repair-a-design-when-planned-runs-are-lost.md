---
title: Repair a design when planned runs are lost
tags: [practices, design]
status: verified
updated: 2026-10-19
---

# Repair a design when planned runs are lost

Lost or impossible runs change what the design can estimate, and the repair is a new design choice rather than a silent hole in the original one.

The NIST/SEMATECH e-Handbook states: "They can be used to repair a 'broken' standard classical design." ([Repairing a design](https://www.itl.nist.gov/div898/handbook/pri/section5/pri522.htm), checked 2026-10-19.)

## What to do

- List the runs that were not made and the terms they were supposed to support.
- Add replacement runs for the model you still need, or narrow the model to what the remaining runs can support.
- Do not analyze the incomplete grid as if it were the design you planned.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use an optimal design when a classical design does not fit](134-use-an-optimal-design-when-the-region-is-irregular.md).
