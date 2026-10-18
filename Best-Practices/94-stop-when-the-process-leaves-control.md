---
title: Stop when the process leaves control
tags: [practices, monitoring, control-chart]
status: verified
updated: 2026-10-17
---

# Stop when the process leaves control

A point outside control limits, or a pattern the chart treats as a signal, means the process is not the stable process the limits describe.

The NIST/SEMATECH e-Handbook states: "Out-of-control refers to rejecting the assumption that the current data are from the same population as the data used to create the initial control chart limits." ([What to do if the process is "Out of Control"?](https://www.itl.nist.gov/div898/handbook/pmc/section1/pmc14.htm), checked 2026-10-17.)

## What to do

- Stop and look for a cause before you pool those measurements with the earlier ones.
- Recalculating the limits to include the shift hides the signal.
- The result after the shift is a result about a different process.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Establish stability before capability](76-establish-stability-first.md).
