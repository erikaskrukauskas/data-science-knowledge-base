---
title: State what reproducibility includes
tags: [practices, reproducibility, measurement, repeatability]
status: verified
updated: 2026-10-17
---

# State what reproducibility includes

Say which conditions were allowed to change before calling a measurement reproducible. Short-term agreement under fixed conditions is a different claim.

The NIST/SEMATECH e-Handbook uses "reproducibility" in a generic sense for variability across days, and it warns that standards do not define the word the same way. It also states: "The measurement process is not completely characterized until this source of variability is quantified." ([Variability](https://www.itl.nist.gov/div898/handbook/mpc/section1/mpc114.htm), checked 2026-10-17.)

## Two claims

- **Repeatability.** The same procedure, on the same item, under conditions held still for a short interval, does not return the same number. The handbook treats this as short-term variation.
- **Reproducibility.** The number moves when days, handling, operators, instruments, or sites change. Name the conditions that were actually varied. A claim that leaves them unnamed cannot be checked.

Repeating a calculation on the same recorded file is neither of these. That check shows the arithmetic can be run again. It does not show that a new measurement, under the conditions you care about, would agree.

## What to report

Report the spread across the conditions you named, not only the spread of repeats taken minutes apart. If the decision needs agreement across sites and you only repeated the measurement on one site, the reproducibility claim stops at that site. See [Characterize the measurement](10-characterize-the-measurement.md) and [Report uncertainty, then record](05-report-uncertainty-then-record.md).

## What stays in the project

Instrument names, operator lists, and the numeric standard deviation stay in the project. The reusable rule is to name the conditions inside the word "reproducible."
