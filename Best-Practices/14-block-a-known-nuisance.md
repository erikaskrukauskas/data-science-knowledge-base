---
title: Block a known nuisance
tags: [practices, experiment, blocking, design]
status: verified
updated: 2026-10-17
---

# Block a known nuisance

When a known change in materials, operators, machines, or time would otherwise sit on top of the comparison, group the runs so that change is separated from the effect you want.

The NIST/SEMATECH e-Handbook defines blocking as a schedule that concentrates those known changes into the levels of a blocking variable. "The reason for blocking is to isolate a systematic effect and prevent it from obscuring the main effects." ([A Glossary of DOE Terminology](https://www.itl.nist.gov/div898/handbook/pri/section7/pri7.htm), checked 2026-10-17.)

## When to block

Block when you can name the nuisance before the runs and you can arrange for each level of the treatment to appear inside the nuisance groups. A day, a batch, or an operator is a block when that is the change you are isolating.

Blocking restricts randomization: units are randomized inside the block, not freely across blocks. Say so. See [Select an experimental design](09-select-an-experimental-design.md).

## What to state

State the nuisance, the blocks, and whether the treatment effect is estimated within blocks. If the treatment and the block are the same split, the effects are confounded. See [Name the confounding](12-name-the-confounding.md).

If you notice the nuisance only after the runs, you can still report it as a limitation. You cannot call that arrangement a block you designed.

## What stays in the project

Batch names and the run schedule stay in the project. The reusable rule is to isolate a known systematic change instead of hoping the average washes it out.
