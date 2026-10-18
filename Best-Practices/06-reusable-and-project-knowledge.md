---
title: Reusable and project knowledge
tags: [practices, scope, lessons, governance]
status: verified
updated: 2026-10-17
---

# Reusable and project knowledge

Write each fact at the level where it stays true.

## Reusable data-science knowledge

Lives in this repo when it still helps in another project:

- How to frame a decision, a population, a target, and a check.
- How to compare a metric, a split, or a model class.
- How to detect leakage and how to read a held-out failure.
- How to report uncertainty and how to record a lesson.
- Verified lessons that name their setting clearly enough to reuse, without that project's private data.

## Project knowledge

Lives in the project:

- Dataset names, labels, and column mappings.
- Thresholds, cutoff dates, and sample sizes that only make sense for that analysis.
- Environment names and where credentials are stored. Secret values stay out of git. See [Privacy and secrets](07-privacy-and-secrets.md).
- Local modeling choices that depend on that measurement process.
- The numeric result of that project's check.

## Other domains

| Topic | Where it lives |
| --- | --- |
| How an agent should brief, search, compare, verify, or record work | [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base) |
| Application development | Its own knowledge repo |
| Data engineering, pipelines, orchestration, and warehouse design | Its own knowledge repo |
| CI/CD and release automation | Its own knowledge repo |

## Promotion rule

A project solution becomes a page here only after you remove that project's data and constraints and the remaining statement is still useful. If nothing remains, keep it in the project.

## Application rule

Before applying a lesson from this repo, check its status, its environment, and its scope. A verified lesson about one population is a hypothesis for a different population until the named check is run again.
