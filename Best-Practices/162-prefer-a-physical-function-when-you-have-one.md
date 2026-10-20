---
title: Prefer a physical function when you have one
tags: [practices, modeling]
status: verified
updated: 2026-10-19
---

# Prefer a physical function when you have one

A polynomial can approximate a curve inside the data, and a physical function is the one to fit when the mechanism supplies the form you will interpret.

The NIST/SEMATECH e-Handbook states: "In these cases we would want to fit physical models to our data." ([Fitting Physical Models](https://www.itl.nist.gov/div898/handbook/ppc/section4/ppc432.htm), checked 2026-10-19.)

## What to do

- Write the physical function and what each parameter means.
- Use a polynomial as an approximation, and say that its coefficients are not the physical parameters.
- Do not extrapolate the polynomial just because it fit inside the study.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Put subject knowledge in the function](80-put-scientific-knowledge-in-the-function.md).
