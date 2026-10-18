---
title: Look before fitting
tags: [practices, eda, assumptions]
status: verified
updated: 2026-10-17
---

# Look before fitting

Let the measurements show their structure before you commit to a model family.

The NIST/SEMATECH e-Handbook states: "EDA is an approach to data analysis that postpones the usual assumptions about what kind of model the data follow with the more direct approach of allowing the data itself to reveal its underlying structure and model." ([What is EDA?](https://www.itl.nist.gov/div898/handbook/eda/section1/eda11.htm), checked 2026-10-17.)

## What to do

- Plot sequence, spread, and shape before you choose a summary or a fitted form.
- A family chosen first will hide the structure that contradicts it.
- If the plots change the form, call that first look exploratory and name a new check.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Frame the decision](02-frame-the-decision.md).
