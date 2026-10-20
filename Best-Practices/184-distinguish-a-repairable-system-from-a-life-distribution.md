---
title: Distinguish a repairable system from a life distribution
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Distinguish a repairable system from a life distribution

A repairable system produces a sequence of repairs, and a life distribution describes units that fail once, so the two analyses are not interchangeable.

The NIST/SEMATECH e-Handbook states: "A non-repairable population is one for which individual items that fail are removed permanently from the population." ([Repairable systems, non-repairable populations and lifetime distribution models](https://www.itl.nist.gov/div898/handbook/apr/section1/apr121.htm), checked 2026-10-19.)

## What to do

- Say whether the unit is repaired and returned, or removed at failure.
- Use a rate of occurrence for a repairable system and a lifetime model for a non-repairable unit.
- Do not fit a lifetime distribution to successive repair times of the same system.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat reliability growth as a changing rate](117-reliability-growth-is-a-changing-rate.md).
