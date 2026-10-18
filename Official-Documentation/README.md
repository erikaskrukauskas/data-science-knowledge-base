---
title: Official documentation
tags: [documentation, sources, statistics]
status: verified
updated: 2026-10-17
---

# Official documentation

Methods and library behavior change. Link to the current official page and record the date you checked it. Do not paste manuals into this repo.

When a practice page and an official page disagree about a method or a library feature, the current official page wins. Update or supersede the practice page afterward. Confirm the current page before relying on a feature.

## Statistical methods and experimental design

| Source | Entry | Use for |
| --- | --- | --- |
| NIST/SEMATECH e-Handbook of Statistical Methods | https://www.itl.nist.gov/div898/handbook/ | Statistical methods, measurement, and designed experiments |

This is a starting URL, not a frozen specification. Open the section that matches the question and confirm it is the current page.

## Model evaluation

Model-evaluation details depend on the library in use. Add a row in the table below when a library is named. Until then, the evaluation rules in this repo stay stack-neutral: match the metric to the decision, hold out data the fitting step did not see, and report uncertainty. See [Compare before choosing](../Best-Practices/03-compare-before-choosing.md) and [Leakage and held-out data](../Best-Practices/04-leakage-and-held-out-data.md).

## Analysis libraries

Add a row when a library is named for a project. Record the official entry URL, the date checked, and the decision it supports.

| Library | Entry | Checked | Decision it supports |
| --- | --- | --- | --- |
| | | | |

Keep pipeline, warehouse, application, and CI vendor docs in the domain repo that owns that subject. Keep agent and MCP product docs in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base).

## Source review

`add-uncovered-data-science-topic` writes a topic this library does not yet cover. `review-covered-data-science-topics` rechecks the topics already here against the entry URLs on this page and the URLs cited on each page. A review writes its report under `Official-Documentation/updates/`.

## Local notes

If you need a short note about a documentation page, add a file next to this README:

- Name it for the topic, not the whole handbook.
- State the date checked.
- Quote only the minimum needed to support a decision, with the URL.
- Link the note from the practice or lesson that depends on it.
