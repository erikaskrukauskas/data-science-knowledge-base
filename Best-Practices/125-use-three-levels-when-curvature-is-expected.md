---
title: Use three levels when curvature is the question
tags: [practices, design, curvature]
status: verified
updated: 2026-10-19
---

# Use three levels when curvature is the question

Two levels cannot show curvature. A three-level factorial can, at the cost of many more runs.

The NIST/SEMATECH e-Handbook states: "The reason that the three-level designs were proposed is to model possible curvature in the response function and to handle the case of nominal factors at 3 levels." ([Three-level full factorial designs](https://www.itl.nist.gov/div898/handbook/pri/section3/pri339.htm), checked 2026-10-19.)

## What to do

- Use three levels only for factors you already expect to curve, not for every factor in a first screen.
- Say what the middle level means in process units.
- If the run count is too large, move to a response-surface design instead of dropping the curvature question.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Add center points to see curvature](92-add-center-points-for-curvature.md).
