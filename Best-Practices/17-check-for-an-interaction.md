---
title: Check for an interaction
tags: [practices, experiment, interaction, effects]
status: verified
updated: 2026-10-17
---

# Check for an interaction

A main effect is an average. Report it only after you have asked whether that effect changes with the level of another factor.

The NIST/SEMATECH e-Handbook defines an interaction as occurring "when the effect of one factor on a response depends on the level of another factor." ([A Glossary of DOE Terminology](https://www.itl.nist.gov/div898/handbook/pri/section7/pri7.htm), checked 2026-10-17.)

## When the average misleads

If factor A helps at one level of factor B and hurts at another, the average effect of A can look small or can point the wrong way for the level you will actually use. The decision then needs the interaction, not the main effect alone.

Choose a design that can estimate the interaction when the decision depends on it. A screening design aimed only at main effects will not answer this question. See [Select an experimental design](09-select-an-experimental-design.md). If the design aliases the interaction with a main effect, name that alias before quoting either one. See [Name the confounding](12-name-the-confounding.md).

## What to state

State the factors in the interaction and the direction of the effect at each level you care about. A significant interaction means the simple comparison for one factor is incomplete until the other factor is specified.

Look for the interaction in the residuals as well as in the planned contrast. Structure against a factor you left out is a sign the form is missing a term. See [Analyze residuals](11-analyze-residuals.md).

## What stays in the project

The factor names and the estimated effects stay in the project. The reusable rule is to refuse a single average when the effect changes across a factor the decision will actually set.
