---
title: Plan for a test that may produce no failures
tags: [practices, reliability]
status: verified
updated: 2026-10-19
---

# Plan for a test that may produce no failures

A reliability test that produces no failures still has a result, and that result is an upper bound that depends on the model and the time on test.

The NIST/SEMATECH e-Handbook states: "In other words, a test where 5 fail out of a total of 10 on test gives more information than a test with 1000 units but only 2 failures." ([Lack of failures](https://www.itl.nist.gov/div898/handbook/apr/section1/apr132.htm), checked 2026-10-19.)

## What to do

- Say how much unit-time was accumulated and how many failures were possible.
- Report a bound under a named model rather than a failure rate of zero.
- Do not treat zero observed failures as a demonstration that the failure rate is zero.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Estimate life from censored data with a method that uses the censoring](118-estimate-life-from-censored-data.md).
