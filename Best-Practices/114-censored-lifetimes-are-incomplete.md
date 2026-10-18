---
title: Treat censored lifetimes as incomplete, not as failures
tags: [practices, reliability, censoring]
status: verified
updated: 2026-10-17
---

# Treat censored lifetimes as incomplete, not as failures

A censored lifetime means the event had not happened by the time you stopped watching. The unit did not fail at that time.

The NIST/SEMATECH e-Handbook states: "Many special methods have been developed to handle censored data How do we handle censored data?" ([Censoring](https://www.itl.nist.gov/div898/handbook/apr/section1/apr131.htm), checked 2026-10-17.)

## What to do

- Dropping censored units makes life look shorter. Treating the censoring time as a failure does the same.
- Use a method that keeps the censoring information.
- Say how the watching stopped. Stopping because the unit was about to fail is a different bias.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Frame the decision](02-frame-the-decision.md).
