---
title: Project-start checklist
tags: [agents, workflow, retrieval, analysis]
status: verified
updated: 2026-10-17
---

# Project-start checklist

The consultation protocol asks for a search. This checklist is the stronger version: run it at the start of a project and again before a significant analysis.

## Checklist

- [ ] Project agent instructions include the [consultation protocol](consultation-protocol.md) and the correct path to this repo.
- [ ] The AI knowledge base is linked for questions about how an agent should work.
- [ ] Domain repos for application development, data engineering, and CI/CD are linked when this project has that work.
- [ ] Searched this repo for practices that match the analysis (`target`, `leakage`, `evaluation`, `uncertainty`).
- [ ] Searched `Lessons-Learned/` for verified lessons in a similar measurement setting.
- [ ] Stated the decision, the population, the target, and the check that defines done.
- [ ] Stated where new lessons will go: data science here, AI tooling in the AI knowledge base, project facts in the project.

## After the analysis

- [ ] The named check was run on data the fitting step did not see.
- [ ] The result includes uncertainty, and the write-up says what that uncertainty is over.
- [ ] A lesson was added only if a later analysis would otherwise repeat the same investigation.
- [ ] No secrets, confidential datasets, customer extracts, or copyrighted sources were copied into this repo.
