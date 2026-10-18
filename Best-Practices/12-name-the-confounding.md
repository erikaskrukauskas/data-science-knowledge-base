---
title: Name the confounding
tags: [practices, experiment, confounding, design]
status: verified
updated: 2026-10-17
---

# Name the confounding

If two effects are tied together by the design or by the way units arrive, the estimate is their sum. Do not report it as the effect of one factor alone.

The NIST/SEMATECH e-Handbook states: "Confounding means we have lost the ability to estimate some effects and/or interactions." In a fractional design, the computed main effect can be the main effect plus an interaction that shares its column. ([Confounding (also called aliasing)](https://www.itl.nist.gov/div898/handbook/pri/section3/pri3343.htm), checked 2026-10-17.)

## When it happens

- A fractional design aliases a main effect with an interaction. The handbook's \(2^{3-1}\) example estimates each main effect only as that main effect plus a two-factor interaction.
- Units that receive one condition also differ on something you did not assign: site, time, operator, or a trait that determined who was included.
- A factor you meant to hold still changed along with the factor you meant to study.

The design page tells you to choose a layout from the objective. This page tells you to write down which effects that layout cannot separate. See [Select an experimental design](09-select-an-experimental-design.md).

## What to state

State the alias, or the uncontrolled factor, that rides along with the effect you will quote. If the decision needs those effects separated, change the design or the comparison. Assuming the aliased interaction is negligible is an assumption. Name it.

An observational comparison has the same duty. If the groups differ on a factor that can move the response, the contrast is not yet the effect of the factor you named.

## What stays in the project

The factor names and the alias table stay in the project. The reusable rule is to refuse a single-factor claim when the estimate still contains another effect.
