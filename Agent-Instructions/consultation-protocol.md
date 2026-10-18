---
title: Consultation protocol
tags: [agents, retrieval, workflow, data-science]
status: verified
updated: 2026-10-17
---

# Consultation protocol

Paste this into a project's `AGENTS.md` or `CLAUDE.md`. Adjust the paths.

On this machine, `<path-to-data-science-knowledge-base>` is `C:\Users\erika\Cursor Projects\data-science-knowledge-base` and `<path-to-ai-knowledge-base>` is `C:\Users\erika\Cursor Projects\ai-knowledge-base`.

```markdown
## Data science knowledge base

Shared data-science practices live in `<path-to-data-science-knowledge-base>`.
Shared AI working practices live in `<path-to-ai-knowledge-base>`.
Application development, data engineering, and CI/CD live in their own repos.
Dataset names, labels, thresholds, environment names, credentials, and local modeling choices stay in this project.

1. Data-science questions are searched in `<path-to-data-science-knowledge-base>`:
   `python "<path-to-data-science-knowledge-base>\Search-Index\search.py" "<keywords>"`
2. Questions about briefing, searching, comparing, verifying, or recording AI-assisted work are searched in `<path-to-ai-knowledge-base>`.
3. Application development, data engineering, and CI/CD questions go to those repos.
4. Significant analysis choices name the options, then implement one.
5. The named check is run before the result is called done.
6. A reusable data-science lesson is written in `<path-to-data-science-knowledge-base>`. An AI-tooling lesson is written in `<path-to-ai-knowledge-base>`.
```

Significant means a choice of target, population, metric, split, or model class, or a change to the claim the analysis will stand behind. A narrow check with one obvious next step can proceed from the notes at hand.

Apply a lesson only when its status is `verified` and its population and measurement setting still match. Confirm a method or a library feature against the current official page when a lesson and that page disagree.
