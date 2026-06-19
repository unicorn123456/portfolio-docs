<img width="2056" height="1092" alt="bild" src="https://github.com/user-attachments/assets/09738a54-4cba-46ab-8542-219a574946a8" />

# VårdAI — Arabic Language Support (project plan)

**Tool:** Linear
**Author:** Ikbal Ismail
**Date:** June 2026

---

A scoped project plan for shipping full Arabic language support in VårdAI, built in Linear to demonstrate structured issue breakdown, prioritization, and status tracking — applying the same lesson from the [build retrospective](./Retrospective.md): give fuzzy, open-ended work (like AI behavior) a concrete checklist before starting, instead of treating it as one undifferentiated task.

## Issues

| ID | Issue | Priority | Status |
|---|---|---|---|
| VAR-5 | Arabic RTL UI rendering | High | In Progress |
| VAR-6 | Language auto-detection on first message | High | In Progress |
| VAR-7 | Arabic system prompt tuning for Groq | Medium | Todo |
| VAR-8 | Mixed-language input handling | Medium | Todo |
| VAR-9 | QA pass — Arabic edge cases | Low | Backlog |

## Why it's scoped this way

**RTL UI and language detection are sequenced first and prioritized highest** — without these, nothing else in the feature is testable end-to-end. They're foundational, not optional polish.

**Prompt tuning and mixed-language handling are Medium priority, sequenced second** — these depend on the foundational pieces being stable, and are the parts of the original build that took longer than expected (per the retrospective), so they're explicitly broken into separate, smaller issues rather than one large "build Arabic AI" ticket.

**QA pass is last and lowest priority on this board** — but not unimportant. It's the issue that operationalizes the edge case list from the PRD (mixed-language input, emergency keywords, knowledge base gaps) into an actual verification step before this feature ships.

## Screenshot

See attached: Linear project board showing 5 issues across In Progress, Todo, and Backlog states with priorities set.

