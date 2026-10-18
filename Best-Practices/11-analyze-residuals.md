---
title: Analyze residuals
tags: [practices, error-analysis, residuals, validation]
status: verified
updated: 2026-10-17
---

# Analyze residuals

A single fit summary does not show whether the model answers the question. Inspect the residuals: the observed response minus the fitted response for each unit.

The NIST/SEMATECH e-Handbook states: "Unfortunately, a high \(R^2\) value does not guarantee that the model fits the data well." It names graphical residual analysis as the primary check for most process models. ([How can I tell if a model fits my data?](https://www.itl.nist.gov/div898/handbook/pmd/section4/pmd44.htm), checked 2026-10-17.)

## What a residual check looks for

If the fitted form is adequate, residuals behave like leftover random error. Structure is evidence that the form is missing something. Look for:

- A curve or a trend against the fitted value or a factor, which means the functional form is short a term.
- Variation that grows or shrinks as the fitted value changes.
- A drift in time or run order.
- Residuals that track another recorded variable you left out of the fit.

A numerical summary can confirm a plot that is hard to read. It does not replace the plot when the plot shows a pattern.

## Where this sits in the analysis

Run this check on the data used to judge the form. If you then change the form because of what you saw, the data that revealed the gap are no longer a clean held-out check. See [Leakage and held-out data](04-leakage-and-held-out-data.md).

The held-out metric still answers whether the result fails on data the fitting step did not see. Residual structure answers whether the fitted form is an adequate description of the data it was shown. Report both when both affect the decision. See [Report uncertainty, then record](05-report-uncertainty-then-record.md).

## What stays in the project

Plots, unit identifiers, and the numeric residual summary stay in the project. The reusable rule is to look for non-random structure before treating a fit summary as evidence.
