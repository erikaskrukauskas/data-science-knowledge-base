---
title: Define the result you report
tags: [practices, communication, uncertainty, reporting]
status: verified
updated: 2026-10-17
---

# Define the result you report

The number in the write-up is a defined result, not a label for the whole analysis. State that definition before attaching an uncertainty or a recommendation.

The NIST/SEMATECH e-Handbook states: "The first step in the uncertainty evaluation is the definition of the result to be reported." The spread you attach to it depends on how many repetitions you made and on the conditions those repetitions covered. If the number is computed from other measurements, write the equation that combines them. ([Steps](https://www.itl.nist.gov/div898/handbook/mpc/section5/mpc521.htm), checked 2026-10-17.)

## What the write-up includes

- The result, in the units the decision uses, and the equation if it is computed from other quantities.
- The population and the conditions the repetitions actually covered. See [Frame the decision](02-frame-the-decision.md) and [State what reproducibility includes](13-state-what-reproducibility-includes.md).
- The uncertainty, and which sources of error it includes. See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
- The check that was run, including whether the fitting step saw that data. See [Leakage and held-out data](04-leakage-and-held-out-data.md).
- The claim you will not make. A result on one site, one period, or one instrument does not become a result for every site, period, or instrument by rounding.

## What to leave out of the lead claim

A fit summary, a residual plot, and a list of factors are support. They are not substitutes for the defined result. If the decision needs a comparison of two conditions, the reported result is that comparison, not the model that helped compute it.

## What stays in the project

Thresholds, dataset names, and the numeric table stay in the project. The reusable rule is that a reader can point to one defined number, the conditions it covers, and the claim it does not support.
