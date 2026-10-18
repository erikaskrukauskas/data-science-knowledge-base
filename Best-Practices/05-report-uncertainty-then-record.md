---
title: Report uncertainty, then record
tags: [practices, uncertainty, lessons, evaluation]
status: verified
updated: 2026-10-17
---

# Report uncertainty, then record

A result includes the uncertainty around it. A lesson is reusable when the named check has been run and the write-up says what that check showed.

## Report the result

With the point estimate or the chosen metric, report a range, an interval, or a sensitivity. Say what the uncertainty is over: a resample, a time period, a site, or a population slice. A single number with no range overstates how stable the result is.

Also say what the result does not support. If the check used one period or one site, the claim stops there until another check covers a wider population.

## Then record a lesson when

- The failure took real investigation, such as a leaked feature or a split that did not match the decision.
- An approach failed for a reason a later analysis would repeat.
- The working approach is still useful after this project's data and thresholds are removed.
- A practice page was wrong or incomplete for the method you checked.

Skip the lesson when the calculation was obvious and local to one project.

## What the lesson must contain

Follow [Lessons-Learned/_template.md](../Lessons-Learned/_template.md).

- The decision, population, target, and environment an analyst needs in order to tell whether the lesson applies.
- Approaches that failed, and the evidence.
- The working solution, written without this project's private data.
- The check you ran and what it showed, including the uncertainty.
- Links to practice pages or official sources.
- Scope: reusable data-science practice, or a pointer to the project or to the AI knowledge base when the lesson is about tooling.

## Lifecycle

| Status | Meaning |
| --- | --- |
| `candidate` | Captured, not yet re-checked |
| `tested` | Reproduced or reviewed against the named check |
| `verified` | Reliable enough for another analysis to apply |
| `superseded` | Replaced by a named newer document |

Move status forward with evidence. Do not delete a superseded lesson. Set `superseded_by` so old links still explain themselves.

Promote a repeated verified lesson into `Best-Practices/` when it has become a general rule. Leave the lesson in place as the evidence.

An AI-tooling lesson is written in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base), not here.
