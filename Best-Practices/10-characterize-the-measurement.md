---
title: Characterize the measurement
tags: [practices, measurement, bias, uncertainty]
status: verified
updated: 2026-10-17
---

# Characterize the measurement

Treat the measurement as a process whose output is the number you will analyze. Before interpreting a difference or a model score, state the errors that can move that number.

The NIST/SEMATECH e-Handbook states: "The 'goodness' of measurements is the issue, and goodness is characterized in terms of the errors that affect the measurements." It quantifies that goodness as bias, short-term variability, long-term variability, and uncertainty. ([What are the issues for characterization?](https://www.itl.nist.gov/div898/handbook/mpc/section1/mpc11.htm), checked 2026-10-17.)

## What to state

- **The quantity.** What the procedure is supposed to capture, in the same units the decision uses. This is the target in [Frame the decision](02-frame-the-decision.md) when the target is measured rather than assigned.
- **Bias.** A systematic shift: the procedure tends to read high or low, or it reads differently for one kind of unit.
- **Short-term variation.** Repeated measurements of the same unit, close together, do not agree.
- **Long-term variation.** The same procedure drifts across days, operators, instruments, or sites.
- **Uncertainty.** The range you will report with the measurement, and which of those errors it includes.

A difference smaller than the measurement error is not yet evidence of a change in the underlying quantity.

## When the measurement is the label

If a person or a rule assigns the outcome, the assignment procedure is the measurement. Record how disagreements are resolved. A target that changes when the rater changes is a different target.

## What stays in the project

Instrument names, calibration dates, and numeric tolerances stay in the project. The reusable rule is to name the bias and the variation before claiming a result. Report that uncertainty with the result. See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
