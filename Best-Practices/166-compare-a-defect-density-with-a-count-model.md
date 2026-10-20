---
title: Compare a defect density with a count model
tags: [practices, comparison, counts]
status: verified
updated: 2026-10-19
---

# Compare a defect density with a count model

Defect density is a count per unit of opportunity, and it needs a count model rather than a proportion model when the numerator is not a fixed number of trials.

The NIST/SEMATECH e-Handbook states: "In order to determine a suitable area to examine for defects, you first need to choose an unacceptable defect density level." ([Does the defect density meet requirements?](https://www.itl.nist.gov/div898/handbook/prc/section2/prc25.htm), checked 2026-10-19.)

## What to do

- Define the opportunity: area, length, time, or number of units inspected.
- State the requirement as a rate on that opportunity.
- Do not treat a density as a binomial proportion when more than one defect can occur on the same unit.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Use a Poisson model for counts in an interval](50-poisson-for-unbounded-counts.md).
