---
title: ChatGPT
tags: [agents, chatgpt]
status: verified
updated: 2026-10-17
---

# ChatGPT

ChatGPT uses the same practices and lessons. The connection method differs.

## Now

Work that starts in ChatGPT can still use this library:

- Retrieve the relevant page locally with `Search-Index/search.py`.
- Paste the relevant section into the ChatGPT task, with the file path.
- Ask ChatGPT to follow that section.

That keeps one canonical copy. A summary pasted into a chat is not a second source of truth.

## Later

Remote use needs an approved connection and an explicit decision about which documents are exposed. Confidential datasets and customer extracts stay out of this repo either way. Do not assume a local MCP config on this PC is visible to ChatGPT.

How ChatGPT connectors work is documented in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base).

## Same rules

ChatGPT output that will be reused is still subject to [Report uncertainty, then record](../Best-Practices/05-report-uncertainty-then-record.md). A suggestion becomes a lesson after the named check, not when the chat ends.
