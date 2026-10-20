---
title: Separate control factors from noise factors
tags: [practices, design, robustness]
status: verified
updated: 2026-10-19
---

# Separate control factors from noise factors

A robustness experiment separates factors you can set in production from noise factors you cannot, and then looks at how the control settings change the effect of the noise.

The NIST/SEMATECH e-Handbook states: "Note that we could have used fractional factorials for either the inner or outer array designs, or for both." ([What are Taguchi designs?](https://www.itl.nist.gov/div898/handbook/pri/section5/pri56.htm), checked 2026-10-19.)

## What to do

- Label every factor as control or noise before the design is built.
- The result of interest is the response's sensitivity to noise, not only its average.
- A crossed noise array is one way to see that sensitivity. Name the design you actually ran.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Check for an interaction](17-check-for-an-interaction.md).
