---
title: Honor restricted randomization
tags: [practices, design, randomization]
status: verified
updated: 2026-10-19
---

# Honor restricted randomization

When a hard-to-change factor is not rerandomized for every run, the experiment has two error layers and the ordinary residual is the wrong one for that factor.

The NIST/SEMATECH e-Handbook states: "In other words, the randomization of the treatment runs is restricted somewhat by the level of the solution concentration factor." ([How can I account for nested variation (restricted randomization)?](https://www.itl.nist.gov/div898/handbook/pri/section5/pri55.htm), checked 2026-10-19.)

## What to do

- Say which factors were reset for every run and which stayed put for a whole group of runs.
- Test a hard-to-change factor against the variation between those groups, not against the run-to-run residual.
- Do not claim a fully randomized experiment when the randomization was restricted.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Separate variance components](111-separate-variance-components.md).
