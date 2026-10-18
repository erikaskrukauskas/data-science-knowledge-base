---
title: An accelerated test is an extrapolation
tags: [practices, reliability, acceleration]
status: verified
updated: 2026-10-17
---

# An accelerated test is an extrapolation

Physical acceleration tests units under harsher conditions so failures arrive sooner.

The NIST/SEMATECH e-Handbook states: "In general, different failure modes will be affected differently by stress and have different acceleration factors." ([What is "physical acceleration" and how do we model it?](https://www.itl.nist.gov/div898/handbook/apr/section1/apr14.htm), checked 2026-10-17.)

## What to do

- The result at use conditions exists only through a model that converts stress to life.
- Name that model and the stress range you actually ran.
- A conversion past the tested stresses is an extrapolation. Say so.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Give a prediction its own uncertainty](87-prediction-has-its-own-uncertainty.md).
