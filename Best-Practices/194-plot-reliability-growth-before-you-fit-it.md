---
title: Plot reliability growth before you fit a growth model
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Plot reliability growth before you fit a growth model

A Duane plot shows whether the cumulative failure rate is changing, and a growth model fit without that picture can impose a trend the repairs do not have.

The NIST/SEMATECH e-Handbook states: "Duane observed that when he plotted these cum MTBF estimates versus the times of failure on log-log paper, the points tended to line up following a straight line." ([Duane plots](https://www.itl.nist.gov/div898/handbook/apr/section1/apr192.htm), checked 2026-10-19.)

## What to do

- Plot the cumulative rate against time on the scales the plot calls for.
- Treat a bend or a flat stretch as a change in the growth story.
- Do not quote a growth slope from a plot that is flat.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat reliability growth as a changing rate](117-reliability-growth-is-a-changing-rate.md).
