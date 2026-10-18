---
title: Condition on a factor before pooling
tags: [practices, eda, conditioning, subgroups]
status: verified
updated: 2026-10-17
---

# Condition on a factor before pooling

A conditioning plot shows a relationship inside levels of another factor.

The NIST/SEMATECH e-Handbook states: "Software Conditioning plots are becoming increasingly common in general purpose statistical software programs, including R and Dataplot." ([Conditioning Plot](https://www.itl.nist.gov/div898/handbook/eda/section3/eda33qc.htm), checked 2026-10-17.)

## What to do

- If the relationship changes across levels, the pooled fit is an average of different stories.
- That is an interaction, even when you did not plan an experiment.
- Report the relationship inside the levels the decision will actually use.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Check for an interaction](17-check-for-an-interaction.md).
