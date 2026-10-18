---
id: LL-0001
title: This repository is data science only
tags: [lessons, scope, governance]
status: verified
updated: 2026-10-17
environment: "Cursor, Windows, data-science-knowledge-base repo"
scope: global
superseded_by:
---

# This repository is data science only

## Problem

A shared analysis library is easy to fill with neighboring subjects: how an agent should work, how a pipeline is built, how an application is structured, how a release is shipped, and one project's dataset names and thresholds. Those notes answer different questions. Mixed into this repo, they crowd search results and get applied outside the analysis they came from.

## Approaches that failed

- Approach: Keep agent instructions, pipeline design, and project-specific cutoffs in the same library as metric, split, and leakage guidance.
- Why it failed: Each of those subjects already has, or will have, its own repo. A future analysis cannot reuse a project's labels or an agent's product setting as if it were a measurement rule.
- Evidence: Scope decision for this repository, 2026-10-17.

## Working solution

Use this repository only for data-science knowledge: question framing, experimental design, measurement, leakage, validation splits, metrics, uncertainty, model comparison, error analysis, reproducibility, and communicating a result.

Put AI tooling in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base). Put application development, data engineering, and CI/CD in their own repos. Put dataset names, labels, thresholds, environment names, credentials, and local modeling choices in the project. When one effort produces both a data-science lesson and an AI-tooling lesson, write the data-science lesson here and link to the AI knowledge base for the tooling lesson. See [SCOPE.md](../SCOPE.md).

## Verification

- Check run: Scope review against the repository decision and the folder layout.
- Result: Root docs and best-practice pages describe analysis and modeling choices. Agent working methods, pipelines, applications, and release automation appear as subjects that belong elsewhere.
- Uncertainty: The boundary is a governance decision reviewed against the written scope. It is not a statistical estimate.

## Scope

`global` for any future project that consults this library.

## References

- [SCOPE.md](../SCOPE.md)
- [Reusable and project knowledge](../Best-Practices/06-reusable-and-project-knowledge.md)
