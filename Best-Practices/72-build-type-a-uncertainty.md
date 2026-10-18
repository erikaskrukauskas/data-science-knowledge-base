---
title: Build uncertainty from repeated measurements
tags: [practices, uncertainty, measurement]
status: verified
updated: 2026-10-17
---

# Build uncertainty from repeated measurements

Type A uncertainty comes from repeated measurements, not from a guess.

The NIST/SEMATECH e-Handbook states: "Instruments whose responses are not directly calibrated to the defined unit are candidates for type A evaluations." ([Type A evaluations of random components](https://www.itl.nist.gov/div898/handbook/mpc/section5/mpc531.htm), checked 2026-10-17.)

## What to do

- Include the conditions those repeats actually varied: time, operator, instrument.
- A repeat on one day under one operator misses the components you did not vary.
- Combine this component with the others you name. Do not report it as the whole uncertainty if other components matter.

## Where this stops

This page is the reusable rule. Dataset names, thresholds, and the numeric result stay in the project.

See [Report uncertainty, then record](05-report-uncertainty-then-record.md).
