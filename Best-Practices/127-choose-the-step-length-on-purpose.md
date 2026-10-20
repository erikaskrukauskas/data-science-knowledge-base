---
title: Choose the step length on the ascent on purpose
tags: [practices, design, optimization]
status: verified
updated: 2026-10-19
---

# Choose the step length on the ascent on purpose

The step length along a search path is a design choice, and a step that is too long leaves the region where the plane holds.

The NIST/SEMATECH e-Handbook states: "The most common procedure for selecting a step length is based on choosing a step size in one factor and then computing step lengths in the other factors proportional to their parameter estimates." ([Single response: Choosing the step length](https://www.itl.nist.gov/div898/handbook/pri/section5/pri5313.htm), checked 2026-10-19.)

## What to do

- State the step in the original factor units, not only in coded units.
- Shorten the step when a trial point falls outside the process you can run or the response stops matching the plane.
- Record the points you actually ran, including the ones that did not improve the response.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Climb with steepest ascent only inside a local plane](126-climb-with-steepest-ascent.md).
