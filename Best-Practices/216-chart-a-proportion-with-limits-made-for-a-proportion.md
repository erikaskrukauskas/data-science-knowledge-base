---
title: Chart a proportion with limits made for a proportion
tags: [practices, control-chart, proportions]
status: verified
updated: 2026-10-19
---

# Chart a proportion with limits made for a proportion

A proportion chart uses limits for a rate of events, and variables limits computed on the percentage as if it were a measured length are the wrong limits.

The NIST/SEMATECH e-Handbook states: "The fraction or proportion can be expressed as a decimal, or, when multiplied by 100, as a percent." ([Proportions Control Charts](https://www.itl.nist.gov/div898/handbook/pmc/section3/pmc332.htm), checked 2026-10-19.)

## What to do

- Define the event and the sample size that the plotted proportion uses.
- Let the limits depend on the sample size when the sample size changes.
- Do not copy limits from a variables chart onto a proportion.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use an attributes chart for counts of events](78-attributes-when-you-only-have-counts.md).
