---
title: Use a Plackett-Burman design only to screen
tags: [practices, design, screening]
status: verified
updated: 2026-10-19
---

# Use a Plackett-Burman design only to screen

A Plackett-Burman design is a screening layout for main effects, and it aliases those effects with interactions.

The NIST/SEMATECH e-Handbook states: "Plackett-Burman designs are very efficient screening designs when only main effects are of interest." ([Plackett-Burman designs](https://www.itl.nist.gov/div898/handbook/pri/section3/pri335.htm), checked 2026-10-19.)

## What to do

- Use it when many factors might matter and the goal is to drop the inert ones.
- Do not quote an interaction from this design. The interactions are mixed into the main-effect columns.
- Follow a screen with a design that can separate the effects you intend to keep.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Read the design resolution before quoting effects](91-read-the-design-resolution.md).
