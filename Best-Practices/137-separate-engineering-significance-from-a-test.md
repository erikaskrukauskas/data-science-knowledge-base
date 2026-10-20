---
title: Separate engineering significance from a statistical test
tags: [practices, design, decisions]
status: verified
updated: 2026-10-19
---

# Separate engineering significance from a statistical test

An effect can be statistically detectable and still too small to matter for the decision, or large enough to matter while the experiment was too small to detect it.

The NIST/SEMATECH e-Handbook states: "If upon reflection the analyst does not have such a value in mind, this "engineering significance" approach would be set aside." ([Engineering significance](https://www.itl.nist.gov/div898/handbook/pri/section5/pri5972.htm), checked 2026-10-19.)

## What to do

- Write the effect size that would change the decision before you look at the test.
- Report the estimated effect next to that threshold.
- Do not replace the threshold with a p-value.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [A test answers a pre-declared question](105-a-test-answers-a-predeclared-question.md).
