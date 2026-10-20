---
title: Build system reliability from the failure modes
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Build system reliability from the failure modes

A bottom-up reliability figure combines component failure modes into a system result, and it is only as good as the structure and the component data you put in.

The NIST/SEMATECH e-Handbook states: "These models assume independence and "first failure mode to reach failure causes both the component and the system to fail"." ([How can you evaluate reliability from the "bottom-up" (component failure mode to system failure rate)?](https://www.itl.nist.gov/div898/handbook/apr/section1/apr18.htm), checked 2026-10-19.)

## What to do

- Draw the structure: which modes must all survive, and which are alternatives.
- Use component data at the conditions the system will see.
- Do not add failure rates across modes that are not in series.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Distinguish a repairable system from a life distribution](184-distinguish-a-repairable-system-from-a-life-distribution.md).
