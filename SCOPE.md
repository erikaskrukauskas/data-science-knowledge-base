---
title: Scope of this repository
tags: [scope, governance, data-science]
status: verified
updated: 2026-10-17
---

# Scope

This repository is the data-science knowledge base. Other projects read it for practices and verified lessons about framing, measuring, and checking an analysis.

## In this repo

- How to state the decision an analysis supports, the population, the target, and the check that defines done.
- How to design a comparison and measure an outcome.
- How to choose a metric, a validation split, and a model class after naming real options.
- How to check for leakage and for a result that fails on data the fitting step did not see.
- How to report uncertainty, compare models, analyze errors, and reproduce a result.
- How to communicate what a result supports.
- Separation of reusable data-science practice from a project's data and thresholds.

## In other repos

| Topic | Where it lives |
| --- | --- |
| AI tooling, agent instructions, prompting, retrieval, and MCP | [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base) |
| Application development | Its own knowledge repo |
| Data engineering, pipelines, orchestration, and warehouse design | Its own knowledge repo |
| CI/CD and release automation | Its own knowledge repo |
| A single project's dataset names, labels, thresholds, environment names, credentials, and local modeling choices | That project |

On this machine the AI knowledge base checkout is `C:\Users\erika\Cursor Projects\ai-knowledge-base`.

When one effort produces both a data-science lesson and an AI-tooling lesson, write the data-science lesson here and link to the AI knowledge base for the tooling lesson.

## Where a new note goes

Ask what a future analysis in an unrelated project could reuse.

- If the answer is a way of framing, measuring, splitting, or checking a result, add it here.
- If the answer is how an agent should work, add it to the AI knowledge base.
- If the answer depends on a pipeline, an application, or a release process, add it to that domain repo.
- If the answer names this project's data, labels, or thresholds, keep it in the project.
- If both a data-science lesson and another kind of lesson are true, split the note and link them.

## Promotion rule

Do not copy a project decision into this repo to make it feel official. Promote it only after it is still useful with that project's data and constraints removed.
