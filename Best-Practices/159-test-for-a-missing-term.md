---
title: Test for a missing term instead of trusting a significant fit
tags: [practices, modeling, residuals]
status: verified
updated: 2026-10-19
---

# Test for a missing term instead of trusting a significant fit

A model can have a small residual and still be missing a term, so the check is whether a specific alternative improves the fit.

The NIST/SEMATECH e-Handbook states: "If the model-dependent estimate of the random variation is larger than the model-independent estimate, then significant terms probably are missing or misspecified in the functional part of the model." ([How can I test whether any significant terms are missing or misspecified in the functional part of the model?](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd446.htm), checked 2026-10-19.)

## What to do

- Name the term or the alternative function you are checking for.
- Use residual structure, a lack-of-fit comparison, or added points as the evidence.
- Do not stop at a high R-squared.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Improve a poor fit from the residuals](86-improve-a-poor-fit-from-the-residuals.md).
