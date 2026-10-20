---
title: Randomize completely when there is no block
tags: [practices, design, randomization]
status: verified
updated: 2026-10-19
---

# Randomize completely when there is no block

A completely randomized design assigns every run independently, and it is the right default only when you have no nuisance to block on.

The NIST/SEMATECH e-Handbook states: "For completely randomized designs, the levels of the primary factor are randomly assigned to the experimental units." ([Completely randomized designs](https://www.itl.nist.gov/div898/handbook/pri/section3/pri331.htm), checked 2026-10-19.)

## What to do

- Use it when every run can be reset and no known nuisance groups the runs.
- If a nuisance appears after the fact, do not analyze the data as if the randomization removed it.
- Name the randomization unit. Randomizing the labels is not the same as resetting the process.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Randomize the assignment](15-randomize-the-assignment.md).
