---
title: Search index
tags: [retrieval, search]
status: verified
updated: 2026-10-17
---

# Search index

Phase 1 retrieval is keyword search over the markdown in this repo. It uses the Python standard library and does not need a database, an embedding model, or a running server.

A later shared search belongs with the MCP service in Phase 2. See [MCP-Server/README.md](../MCP-Server/README.md).

## Commands

From the repo root:

```powershell
python Search-Index/search.py --list
python Search-Index/search.py "keywords"
python Search-Index/search.py --tag evaluation
python Search-Index/search.py --status verified "leakage"
```

`--list` prints every document's path, status, title, and tags. A query requires every keyword to appear in the file. `--tag` and `--status` filter YAML frontmatter.

The script skips `.git`, `.venv`, `__pycache__`, and this `Search-Index` folder.

## How to think about a miss

A miss means no page used those words. Try the terms from the analysis (`leakage`, `target`, `uncertainty`, `split`) or list the catalog and open the closest title. Add the missing words to the page that should have matched, or write the page if the topic is new.

## What this search will not do

- It does not search the AI knowledge base or other domain repos.
- It does not search the web or official docs.
- It does not rank by meaning. A synonym that never appears in the file will not hit.
