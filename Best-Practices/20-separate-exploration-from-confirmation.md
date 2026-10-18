---
title: Separate exploration from confirmation
tags: [practices, eda, confirmation]
status: verified
updated: 2026-10-17
---

# Separate exploration from confirmation

A pattern found by looking is not the same claim as a comparison declared in advance.

The NIST/SEMATECH e-Handbook states: "For EDA, the data collection is not followed by a model imposition; rather it is followed immediately by analysis with a goal of inferring what model would be appropriate." ([How Does Exploratory Data Analysis differ from Classical Data Analysis?](https://www.itl.nist.gov/div898/handbook/eda/section1/eda12.htm), checked 2026-10-17.)

## What to do

- Write down which summaries were chosen after seeing the data.
- Do not attach the probability statement of a pre-declared test to a pattern you hunted for.
- Confirm a hunted pattern on data that did not suggest it.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Leakage and held-out data](04-leakage-and-held-out-data.md).
