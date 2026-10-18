---
title: Cursor
tags: [agents, cursor]
status: verified
updated: 2026-10-17
---

# Cursor

Cursor is the day-to-day editor for this library and for projects that read it.

## This repo

`AGENTS.md` at the root tells agents how to maintain the library: data-science knowledge only, frontmatter, lesson status, and no secrets or copied books.

## Other projects

Add the [consultation protocol](consultation-protocol.md) to the project's `AGENTS.md`. That file is the durable place for project rules. A chat reminder disappears with the session.

Keep the protocol short. Link here for the full practice instead of pasting every best-practice page into the project.

## Search from a project

From any working directory:

```powershell
python "<path-to-data-science-knowledge-base>\Search-Index\search.py" "leakage"
```

Phase 2 can replace that command with an MCP tool. The protocol text can then say "call the knowledge search tool" without changing the practices.

## How the agent should work

Questions about Cursor rules, skills, and how an agent briefs or verifies its own work belong in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base). This page only covers how Cursor reaches the data-science library.

Create a Cursor rule in a project only when that project needs a repeated local behavior. If the guidance applies to every analysis, add it under `Best-Practices/` and link it.
