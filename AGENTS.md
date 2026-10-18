---
title: Agent rules for this repository
tags: [agents, governance, data-science]
status: verified
updated: 2026-10-17
---

# Agent rules

You are in the data-science knowledge base. Other projects consult this repo for analysis and modeling practices. AI tooling, application development, data engineering, and CI/CD have their own repos.

## While editing this repo

- Add or update data-science knowledge only. Read [SCOPE.md](SCOPE.md) before creating a document.
- Put stable guidance in `Best-Practices/`. Put findings from real analyses in `Lessons-Learned/`.
- Give every markdown document YAML frontmatter with `title`, `tags`, `status`, and `updated`.
- Lessons also include `id`, `environment`, `scope`, and `superseded_by`.
- Keep one canonical copy of a practice. Link to it from agent-specific files.
- Do not commit secrets, credentials, confidential datasets, customer extracts, copyrighted books, or verbatim official documentation.
- Do not present an unchecked result as `verified`. Use the lifecycle in [Lessons-Learned/README.md](Lessons-Learned/README.md).
- When a newer document replaces an older one, set the old document to `superseded` and point `superseded_by` at the replacement. Do not delete it.
- Do not commit or push unless the task explicitly asks for that.

## Status values

`candidate` → `tested` → `verified`

Use `superseded` when a newer document replaces this one. Keep the old file so past references still resolve.

## Knowledge maintenance

- A data-science topic this repo does not yet cover: `.cursor/skills/add-uncovered-data-science-topic/SKILL.md`
- Whether pages already here still match their official sources: `.cursor/skills/review-covered-data-science-topics/SKILL.md`

## Before you finish a documentation change

Search for an existing page on the same topic:

```powershell
python Search-Index/search.py --list
python Search-Index/search.py "your topic"
```

Update the existing page when the topic already exists. Questions about how an agent should brief, search, compare, verify, or record work belong in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base), not in a new page here.
