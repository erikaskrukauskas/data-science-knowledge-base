---
title: Name the distribution you are using
tags: [practices, distribution, assumptions]
status: verified
updated: 2026-10-17
---

# Name the distribution you are using

A distribution is a model of how measurements vary.

The NIST/SEMATECH e-Handbook states: "Discrete Distributions The mathematical definition of a discrete probability function, p(x), is a function that satisfies the following properties." ([What is a Probability Distribution](https://www.itl.nist.gov/div898/handbook/eda/section3/eda361.htm), checked 2026-10-17.)

## What to do

- Name it, and name the measurements it is meant to describe.
- Do not import a distribution because a later formula requires it.
- If the measurements contradict it, the probabilities computed from it are not the result.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Name the distributional assumption](26-distributional-assumption.md).
