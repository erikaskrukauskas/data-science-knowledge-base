---
title: Consult before an analysis
tags: [practices, retrieval, workflow, analysis]
status: verified
updated: 2026-10-17
---

# Consult before an analysis

Search this repo before a significant analysis or modeling choice. Search the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base) when the question is how an agent should work.

## Choose the library

| Question | Search |
| --- | --- |
| How should the question, metric, split, leakage check, or uncertainty be handled? | This repo |
| How should an agent brief, search, compare, verify, or record work? | AI knowledge base |
| How should an application, a pipeline, or a release be built? | That domain's knowledge repo |
| What did this project already measure or decide? | That project's docs and history |

A new project does not need a private copy of these practices. It needs a pointer to this checkout and a habit of searching it. The pasteable pointer is [consultation-protocol.md](../Agent-Instructions/consultation-protocol.md).

## Sequence

1. Name the decision the analysis supports, the population, the target, and the check that defines done. See [Frame the decision](02-frame-the-decision.md).
2. Search this repo for a data-science practice that applies.
3. Search the AI knowledge base when the open question is about the agent's working method.
4. Read the current official page when the answer depends on a statistical method or a library feature. See [Official documentation](../Official-Documentation/README.md).
5. Compare real options when the choice is a metric, a split, or a model class. See [Compare before choosing](03-compare-before-choosing.md).
6. Run the named check, report uncertainty, and record a lesson when the finding will help a later analysis. See [Report uncertainty, then record](05-report-uncertainty-then-record.md).

## What counts as significant

Search and compare when the work defines a target, chooses a population, picks a metric or a split, selects a model class, or changes the claim you will stand behind.

A narrow check with one obvious next step can proceed from the data and the notes already in front of you. Record a lesson afterward if the diagnosis was hard to find.

## Enforcement

The consultation protocol asks agents to do this. A project-start checklist is stronger because it is explicit. Use [project-start-checklist.md](../Agent-Instructions/project-start-checklist.md) when a project should require the search.
