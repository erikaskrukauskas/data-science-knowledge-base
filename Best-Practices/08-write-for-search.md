---
title: Write for search
tags: [practices, retrieval, writing]
status: verified
updated: 2026-10-17
---

# Write for search

Write so a later keyword search can find the page and a later analysis can apply it without the original session.

## Frontmatter

Every markdown document starts with:

```yaml
---
title: Short specific title
tags: [practices, leakage]
status: verified
updated: 2026-10-17
---
```

Lessons also include `id`, `environment`, `scope`, and `superseded_by`, as in the [lesson template](../Lessons-Learned/_template.md).

Tags are lowercase words a search would use: `leakage`, `evaluation`, `uncertainty`, `metrics`, `splits`, `target`, `privacy`.

## One topic per page

Split a note that answers two unrelated questions. A search hit should be something you can apply, not a journal of the whole analysis. Link to the canonical page instead of copying it.

## Shape

- Open with the rule or the result.
- Name the analysis situation where it applies.
- Give the decision test or the check.
- Name the evidence: the held-out comparison, the official source, or the review.
- Leave dataset names and thresholds in the project.

## Titles

Use the words a future search will use. "Leakage and held-out data" is retrievable. "Notes" is not.

## Maintenance

When you change guidance that depends on a method or a library, update `updated` and re-check the official page named in the document. Confirm the current page before relying on a feature. When you replace a page, mark the old one `superseded` and set `superseded_by` to the new path. Do not delete it.
