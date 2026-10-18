---
title: Codex
tags: [agents, codex]
status: verified
updated: 2026-10-17
---

# Codex

Codex should use the same data-science library as Cursor and Claude. Put the shared steps in Codex's global `AGENTS.md`, and point that file at this checkout.

## Global instructions

Include the [consultation protocol](consultation-protocol.md) in the global agent instructions so every new project inherits the search habit.

Add the [project-start checklist](project-start-checklist.md) in projects that need a required search before an analysis.

## What Codex reads

- This repo for framing, metrics, splits, leakage, uncertainty, and analysis lessons.
- The AI knowledge base for how to brief, search, compare, verify, and record AI-assisted work.
- The domain knowledge repo for application, pipeline, or release practices.
- The project for dataset names, thresholds, and local decisions.

Codex should not copy this repo into each project.

## How the agent should work

Product behavior for Codex belongs in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base). Do not copy those notes here.

## MCP

When the local MCP server from [MCP-Server/README.md](../MCP-Server/README.md) exists, register it in the global Codex configuration. Until then, run `Search-Index/search.py`.
