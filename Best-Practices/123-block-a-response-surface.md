---
title: Block a response surface when the runs will not fit in one session
tags: [practices, design, blocking]
status: verified
updated: 2026-10-19
---

# Block a response surface when the runs will not fit in one session

A response-surface design that spans sessions needs blocks, or the session effect is mixed into the surface.

The NIST/SEMATECH e-Handbook states: "Blocked designs are better designs if the design allows the estimation of individual and interaction factor effects independently of the block effects." ([Blocking a response surface design](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3364.htm), checked 2026-10-19.)

## What to do

- Name the block before the runs start: day, batch, operator, or instrument.
- Check that the block arrangement still lets you estimate the surface terms you claimed.
- Do not treat block differences as if they were factor effects.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Block a known nuisance](14-block-a-known-nuisance.md).
