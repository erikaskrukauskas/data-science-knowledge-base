---
name: review-covered-data-science-topics
description: >-
  Review the official sources cited by this knowledge base for changes to
  data-science topics it already documents, then update those pages. Use when
  the user asks to review covered topics, refresh existing practices against
  current statistical or library documentation, or check whether documented
  guidance is outdated.
---

# Review covered data-science topics

Start from the pages already in this repo. Check whether their official sources still agree with them. This is not a scan for new topics. New topics use [add-uncovered-data-science-topic](../add-uncovered-data-science-topic/SKILL.md).

## List the covered topics

```bash
python Search-Index/search.py --list
```

Review pages in `Best-Practices/`, verified files in `Lessons-Learned/`, and source notes under `Official-Documentation/` and `Books/`. Skip `Lessons-Learned/_template.md`, files with `status: superseded`, and files in `Official-Documentation/updates/`.

For each page, note the claim a source could invalidate: a definition, a recommended check, the meaning of a metric, or a library feature presented as current.

## Check sources for those claims

Read the entry URLs in [Official-Documentation/README.md](../../../Official-Documentation/README.md), including any analysis library added to that table later. Open the official page for the claim and read the section that matches it. Also open URLs already cited on the page under review.

A note in `Books/` is a lead. Confirm a change on the official page before editing a practice. A source that does not touch a covered claim is out of this review.

Confirm the current page before changing a rule that depends on a method or a library feature.

## Update the page

Edit the existing page when the official page contradicts or extends that claim. Set `updated` to today. Keep `status` unless the page is wrong enough to mark `superseded`, with `superseded_by` pointing at the replacement.

Do not add a new topic while reviewing. Do not paste a manual or a handbook chapter into the repo. Quote only the sentence needed, with the URL.

A source change is not a lesson. Add a lesson only when an analysis was checked against the change.

## Report

Write the report to `Official-Documentation/updates/YYYY-MM-DD-covered-topics.md` with frontmatter `title`, `tags: [documentation, updates]`, `status: verified`, and `updated`. Put the same report in the chat:

```markdown
# Covered topic review
Checked: YYYY-MM-DD

## Updated
- **Page** — what the source changed — [url](url)

## Still current
- Page — source checked

## Unconfirmed
- Page — claim that could not be checked, and which source failed
```
