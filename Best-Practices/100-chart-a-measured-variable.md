---
title: Chart a measured variable with limits from a stable period
tags: [practices, monitoring, control-chart]
status: verified
updated: 2026-10-17
---

# Chart a measured variable with limits from a stable period

A variables control chart tracks a measured amount, often through the mean and the spread of small groups.

The NIST/SEMATECH e-Handbook states: "Control limits are used to determine if the process is in a state of statistical control (i.e., is producing consistent output)." ([What are Variables Control Charts?](https://www.itl.nist.gov/div898/handbook/pmc/section3/pmc32.htm), checked 2026-10-17.)

## What to do

- The limits come from a stable period.
- A change in the measurement method is a new process and needs new limits.
- Do not use specification limits as control limits. They answer different questions.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Stop when the process leaves control](94-stop-when-the-process-leaves-control.md).
