---
title: Privacy and secrets
tags: [practices, privacy, security, governance]
status: verified
updated: 2026-10-17
---

# Privacy and secrets

This library is for reusable analysis knowledge. It is not a dataset store and it is not a secrets store.

## Never commit

- Raw confidential datasets, customer extracts, or row-level records from a private source.
- API keys, tokens, passwords, connection strings, or private certificates.
- Live `.env` files.
- Copyrighted books, full PDFs, or verbatim copies of official manuals.

`.gitignore` ignores `.env` files and `*.pdf` so a local export is harder to commit by accident. The ignore rule is a backstop. The rule is still: do not add those files.

A lesson may describe a data problem in general terms: the unit, the time order, and the kind of field that leaked. It does not include the extract.

## Where those things go

| Kind of information | Store |
| --- | --- |
| Reusable practices and verified analysis lessons | This repo |
| A project's dataset names, labels, and thresholds | That project, under its own access rules |
| Credentials | The project's secret manager or a local ignored env file |
| Proprietary extracts | An approved store with the right permissions |

Point to the dataset's name and the approved place it is loaded from. Do not paste the rows into a lesson so the next session can "just rerun it."

## Before a result leaves the project

Confirm the write-up still makes sense with the confidential fields removed. If the lesson needs those fields to be understood, it belongs in the project, not here.
