---
title: Replicate to separate error
tags: [practices, experiment, replication, error]
status: verified
updated: 2026-10-17
---

# Replicate to separate error

Run the same treatment combination more than once when you need an estimate of random error that is not mixed with a missing term in the model.

The NIST/SEMATECH e-Handbook defines replication as performing the same treatment combination more than once, and states: "Including replication allows an estimate of the random error independent of any lack of fit error." ([A Glossary of DOE Terminology](https://www.itl.nist.gov/div898/handbook/pri/section7/pri7.htm), checked 2026-10-17.)

## What a replicate is

A replicate applies the same factor settings to more than one experimental unit, or repeats the treatment on a new execution of the process. Two rows that are copies of one recorded observation are not replicates. They repeat the number without repeating the experiment.

Repeating a measurement on one item under fixed conditions estimates short-term measurement variation. See [State what reproducibility includes](13-state-what-reproducibility-includes.md). That is a different repeat from a second experimental unit under the same treatment.

## Why it changes the check

Without replication, leftover variation mixes random error with lack of fit. A residual pattern can still show that the form is wrong. See [Analyze residuals](11-analyze-residuals.md). It cannot, by itself, show how large the random error is relative to that gap.

When you claim a factor matters, say whether the comparison used replicated runs or only one run at each setting. A difference that is large next to a single run can be ordinary run-to-run error.

## What stays in the project

The run count and the error estimate stay in the project. The reusable rule is to repeat the treatment, not the spreadsheet row, when the claim needs a pure error estimate.
