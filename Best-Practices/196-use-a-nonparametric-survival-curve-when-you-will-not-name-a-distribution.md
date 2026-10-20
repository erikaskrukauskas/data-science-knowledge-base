---
title: Use a nonparametric survival curve when you will not name a distribution
tags: [practices, reliability, censoring]
status: verified
updated: 2026-10-19
---

# Use a nonparametric survival curve when you will not name a distribution

A Kaplan-Meier curve estimates the proportion still surviving without naming a life distribution, and it does not by itself produce a physical parameter.

The NIST/SEMATECH e-Handbook states: "Better estimates for graphical plotting can be obtained by modifying the K-M estimates so that they reduce to the median rank estimates for plotting Type I censored life test data." ([Empirical model fitting - distribution free (Kaplan-Meier) approach](https://www.itl.nist.gov/div898/handbook/apr/section2/apr215.htm), checked 2026-10-19.)

## What to do

- Include the censored units at the times they were censored.
- Read the curve as a step function of the data you have. The tail is thin when few units remain.
- Fit a named distribution only when you are willing to state it.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Treat censored lifetimes as incomplete, not as failures](114-censored-lifetimes-are-incomplete.md).
