---
title: Show the process is stable before experimenting on it
tags: [practices, design, stability]
status: verified
updated: 2026-10-19
---

# Show the process is stable before experimenting on it

Factor effects estimated on a drifting process are mixed with the drift, so stability is a precondition of the experiment.

The NIST/SEMATECH e-Handbook states: "A plot of the outcomes of these control runs will indicate if the underlying process itself has drifted or shifted during the experiment." ([Is the process stable?](https://www.itl.nist.gov/div898/handbook/pri/section2/pri22.htm), checked 2026-10-19.)

## What to do

- Chart the process, or otherwise show it is stable, before you attribute changes to the factors.
- If the process is not stable, the experiment's job may be to find the cause of the drift rather than to optimize a surface.
- Do not fit a design model across a period that is out of control and then treat the coefficients as process settings.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Establish stability before capability](76-establish-stability-first.md).
