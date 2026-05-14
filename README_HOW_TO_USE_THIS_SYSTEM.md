# README — How to Use This AI Working System

This folder turns the portfolio `.md` documents into a cleaner AI working system.

Use it like this:

---

## 1. Always Start Here

Read:

```text
00_MASTER_SOURCE_OF_TRUTH.md
```

This file controls the project.

If anything conflicts, follow the Master file first.

---

## 2. Pick the Right File for the Task

| Task | Use These Files |
|---|---|
| Strategy / positioning | 00 + 01 |
| Homepage copy | 00 + 01 |
| Case study writing | 00 + 02 |
| Art direction / visual design | 00 + 03 |
| AI image generation | 00 + 03 + 05 |
| AI dev / Codex / Claude Code | 00 + 04 |
| Project continuity | 00 + 06 |

---

## 3. Recommended AI Handoff Prompt

```text
Please read the attached Markdown files before responding.

Read order:
1. 00_MASTER_SOURCE_OF_TRUTH.md
2. [task-specific file]

Follow 00_MASTER_SOURCE_OF_TRUTH.md as the highest-priority source.

Do not invent project details, metrics, client names, logos, or confidential information.
Do not change the project hierarchy.
Do not rewrite the core positioning unless explicitly asked.

Your task is:
[write the current task here]

Return:
1. Understanding summary
2. Proposed approach
3. Output
4. Risks / open questions
```

---

## 4. Recommended Workflow

### Phase 1 — Validate Direction

Use:

```text
00_MASTER_SOURCE_OF_TRUTH.md
01_STRATEGY_BRIEF.md
03_ART_DIRECTION_BRIEF.md
```

Output:

- homepage direction
- visual direction board
- copy tone check

### Phase 2 — Build Homepage Prototype

Use:

```text
00_MASTER_SOURCE_OF_TRUTH.md
04_DEV_IMPLEMENTATION_BRIEF.md
03_ART_DIRECTION_BRIEF.md
```

Output:

- single HTML prototype or Next.js prototype
- responsive homepage
- no full case pages yet

### Phase 3 — Create Case Studies

Use:

```text
00_MASTER_SOURCE_OF_TRUTH.md
02_CONTENT_AND_CASE_STUDY_BRIEF.md
```

Output:

- CDP case study
- Service Transaction POS case study
- sanitized visual plan

### Phase 4 — Generate Visual Assets

Use:

```text
00_MASTER_SOURCE_OF_TRUTH.md
03_ART_DIRECTION_BRIEF.md
05_IMAGE_PROMPT_LIBRARY.md
```

Output:

- master strategy board
- hero visual
- CDP thumbnail
- POS thumbnail
- case study system board
- motif library

### Phase 5 — Track Decisions

Use:

```text
06_DECISION_LOG.md
```

Update it whenever a major decision changes.

---

## 5. Important Reminder

This system is designed to reduce guessing.

Do not send every file to every AI every time.

Send:

- Master file always
- Task-specific file only
- Decision log only if continuity matters

This keeps the AI focused and prevents the project from becoming too broad.
