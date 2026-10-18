---
title: Lessons learned
tags: [lessons, index, data-science]
status: verified
updated: 2026-10-17
---

# Lessons learned

Lessons are findings from real analyses. Best-practice pages are the stable rules. A lesson graduates into a practice page only after it holds up beyond the original case.

## Lifecycle

`candidate` → `tested` → `verified`

| Status | Set it when |
| --- | --- |
| `candidate` | You wrote down the finding and it is not re-checked yet |
| `tested` | You reproduced the result or reviewed the evidence against the named check |
| `verified` | Another analysis can apply it without re-discovering the dead ends |
| `superseded` | A newer lesson or practice page replaces it |

Superseded files stay in the folder. Set `superseded_by` to the replacement path. Do not delete them.

## File names

`LL-0001-short-slug.md`

Increment the number. Do not reuse an id.

## What to record

Use [_template.md](_template.md). A useful lesson includes the decision and the target, the environment, the failed approaches, the working approach, and the check that showed it worked, including uncertainty.

Record a data-science lesson here. Record an AI-tooling lesson in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base). When one effort produces both, write both and link them.

Leave dataset names, labels, thresholds, and customer extracts in the project.

## Current lessons

| ID | Title | Status |
| --- | --- | --- |
| [LL-0001](LL-0001-data-science-only.md) | This repository is data science only | verified |
