---
title: A gamma prior is a claim about the failure rate
tags: [practices, reliability, bayesian]
status: verified
updated: 2026-10-19
---

# A gamma prior is a claim about the failure rate

A gamma prior on a failure rate is a specific distributional claim, and its mean and weight decide how much the prior counts against the new test.

The NIST/SEMATECH e-Handbook states: "In general, Bayesian test times can be shorter, or longer, than the corresponding classical test times, depending on the choice of prior parameters." ([Bayesian gamma prior model](https://www.itl.nist.gov/div898/handbook/apr/section3/apr315.htm), checked 2026-10-19.)

## What to do

- State the prior mean and the prior strength in units you can explain.
- Show the posterior mean next to the data-only estimate.
- Do not use a gamma prior as a default because the update is convenient.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [State the prior in a Bayesian reliability claim](198-state-the-prior-in-a-bayesian-reliability-claim.md).
