---
title: Compare a spread with a standard value
tags: [practices, comparison, variance]
status: verified
updated: 2026-10-19
---

# Compare a spread with a standard value

A nominal standard deviation is a stated requirement on spread, and meeting a requirement on the mean does not speak to it.

The NIST/SEMATECH e-Handbook states: "For two-sided tests, critical values are required for both tails of the distribution." ([Are the data consistent with a nominal standard deviation?](https://www.itl.nist.gov/div898/handbook/prc/section2/prc23.htm), checked 2026-10-19.)

## What to do

- State the nominal spread and the shape assumption.
- Report the estimated spread beside the nominal value.
- Use a resistant description as well when the shape assumption is doubtful.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Test a spread against a named standard](174-test-a-spread-against-a-named-standard.md).
