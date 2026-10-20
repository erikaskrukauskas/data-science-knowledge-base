---
title: Read a bathtub curve as three regimes
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Read a bathtub curve as three regimes

A bathtub curve is a claim that early failures, a flat middle, and wear-out are different regimes, and one lifetime number erases that distinction.

The NIST/SEMATECH e-Handbook states: "Because of the shape of this failure rate curve, it has become widely known as the "Bathtub" curve." (["Bathtub" curve](https://www.itl.nist.gov/div898/handbook/apr/section1/apr124.htm), checked 2026-10-19.)

## What to do

- Say which regime the decision is about.
- Do not use early-life data to estimate wear-out, or the reverse.
- A constant-hazard model is a statement that you are in the flat middle, not a default.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Define the hazard you are estimating](185-define-the-hazard-you-are-estimating.md).
