---
name: add-uncovered-data-science-topic
description: >-
  Add a missing data-science topic to this knowledge base after confirming no
  page covers it. Use when the user asks to document, add, or update the data
  science knowledge base on a topic it does not yet cover, such as question
  framing, experimental design, measurement, leakage, validation splits,
  metrics, uncertainty, model comparison, error analysis, reproducibility, or
  communicating a result.
---

# Add an uncovered data-science topic

Add one new topic to this library. If a page already covers it, update that page instead of creating a second one.

## Decide where it goes

Read [SCOPE.md](../../../SCOPE.md). Add the topic here only when a future analysis in an unrelated project could reuse it after that project's data and constraints are removed.

Leave AI tooling, agent instructions, prompting, retrieval, and MCP to the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base). Leave application development, data engineering, and CI/CD to their own repos. Leave dataset names, labels, thresholds, environment names, credentials, and local modeling choices in the project. If the user asks for an out-of-scope topic, name the repo that should own it and stop.

## Confirm it is uncovered

```bash
python Search-Index/search.py --list
python Search-Index/search.py "topic words"
```

Search `Best-Practices/`, `Lessons-Learned/`, `Official-Documentation/`, and `Books/`. A hit that answers the question means the topic is covered. Edit that page, or follow [review-covered-data-science-topics](../review-covered-data-science-topics/SKILL.md) when the task is to refresh it from current sources.

A near match is still covered when the missing part is a paragraph, not a new decision. Add the paragraph there.

## Research before writing

Open the matching entry in [Official-Documentation/README.md](../../../Official-Documentation/README.md) and read the section that supports the rule. Statistical methods and experimental design start at the NIST/SEMATECH e-Handbook. A library feature uses the official page for a library already named in that file. Confirm the current page before relying on a feature.

Do not choose a library, language, or platform on a practice page. If the topic is a library feature, add the library row or a short note under `Official-Documentation/` and link the practice that depends on it.

Quote only the sentence needed, with the URL. Do not paste a manual, handbook chapter, book, or dataset into the repo.

## Write one page

Follow [Write for search](../../../Best-Practices/08-write-for-search.md).

| Kind of knowledge | Where to put it |
| --- | --- |
| Stable rule for later analyses | Next numbered file in `Best-Practices/`, and a row in its README |
| Official source entry | A row or a short note under `Official-Documentation/` |
| Citation and original notes | A catalog row in `Books/README.md`, plus `Books/notes/<slug>.md` when notes exist |
| Finding from a checked analysis | Next `LL-####` file, using `Lessons-Learned/_template.md` |

Set `status` to `verified` when an official page you opened supports the rule. Set `candidate` when that page was not opened or the rule is not yet checked. Do not mark a lesson `verified` unless the check named in the lesson was run.

One topic per page. Link related pages. Set `updated` to the day you write it.

## Report

```markdown
# Topic added
- Page:
- Why it was uncovered:
- Official source: [title](url)
- Status:
```

If you refused the topic, say where it belongs.
