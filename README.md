---
title: Data Science Knowledge Base
tags: [overview, scope, data-science]
status: verified
updated: 2026-10-17
---

# Data Science Knowledge Base

This repository is the shared library for **data-science knowledge**: how to frame a question, design a comparison, measure a result, and say what the result does and does not support. Other projects consult it for practices that still hold after a project's data and constraints are removed.

The GitHub repository is [erikaskrukauskas/data-science-knowledge-base](https://github.com/erikaskrukauskas/data-science-knowledge-base). On this machine the checkout is `C:\Users\erika\Cursor Projects\data-science-knowledge-base`.

AI tooling, application development, data engineering, and CI/CD keep their own repositories. This repo stores the analysis method, not those domains.

## What belongs here

- Practices for question framing, experimental design, measurement, leakage, validation splits, metrics, uncertainty, model comparison, error analysis, reproducibility, and communicating a result.
- Lessons learned from real analyses, after they have been checked.
- Pointers to current statistical and evaluation documentation.
- Citations and original notes for references. Full copyrighted books and PDFs stay out of git.

## How another project uses it

1. Point that project's agent instructions at this checkout. Copy the snippet from [Agent-Instructions/consultation-protocol.md](Agent-Instructions/consultation-protocol.md).
2. Search before a significant analysis or modeling choice:

```powershell
python Search-Index/search.py "leakage split"
python Search-Index/search.py --tag evaluation
python Search-Index/search.py --list
```

3. Apply what is reusable. Leave dataset names, labels, thresholds, environment names, credentials, and local modeling choices in the project repo.
4. After a checked data-science lesson, add a file under `Lessons-Learned/` using the template.

Questions about how an agent should brief, search, compare, verify, or record work belong in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base). On this machine that checkout is `C:\Users\erika\Cursor Projects\ai-knowledge-base`.

## Layout

| Path | Role |
| --- | --- |
| `Best-Practices/` | Stable practices for analysis and modeling choices |
| `Lessons-Learned/` | Findings from real analyses and their validation state |
| `Agent-Instructions/` | Snippets for Cursor, Codex, Claude Code, and ChatGPT |
| `Official-Documentation/` | Links to current statistical and evaluation docs |
| `Books/` | Citation and notes policy for references |
| `Search-Index/` | Local keyword search over this repo |
| `MCP-Server/` | Design for a later shared retrieval service |
| `AGENTS.md` | Rules for agents editing this repo |
| `SCOPE.md` | Boundary between this repo and sibling repos |

## Roadmap

| Phase | Outcome | State |
| --- | --- | --- |
| 1. Foundation | Folder layout, practices, lessons template, keyword search | In this repo |
| 2. MCP | Local tools so an agent can search this library from another project | Designed, not built |
| 3. Lessons memory | Validation workflow, superseding, retrieval of verified lessons | Template and rules are in place |
| 4. Remote access | A way to consult this library from a session that cannot read the local checkout | Later, after a local workflow is proven |

## Principles

- Retrieve the page that can change the analysis. Do not load the whole library into a session.
- Report uncertainty with the result. Record a lesson after the named check has been run.
- Keep one copy of each practice. Agent-specific files link to it.
- Keep confidential datasets, credentials, and customer extracts out of git.
