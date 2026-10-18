---
title: Prefer a prediction that uses the factors that matter
tags: [practices, modeling, parsimony, prediction]
status: verified
updated: 2026-10-17
---

# Prefer a prediction that uses the factors that matter

A prediction that uses only the factors that change the response is easier to trust and to check.

The NIST/SEMATECH e-Handbook states: "Identify Important Factors The two problems discussed in the previous section (important factors and a parsimonious model) will be handled in parallel since determination of one yields the other." ([Important Factors and Parsimonious Prediction](https://www.itl.nist.gov/div898/handbook/pri/section6/pri618.htm), checked 2026-10-17.)

## What to do

- Extra factors that do not move the response add noise to the story.
- Keep a factor the decision must set even if its estimate is small, and say the estimate is small.
- Do not equate a short model with a correct one.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Drop terms that do no work](85-drop-terms-that-do-no-work.md).
