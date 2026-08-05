# 🏃 Scrum-Simulator

### A hands-on Scrum lesson you can *run* — plan a backlog, commit a sprint, work a board day by day, watch the burndown, and close with review + retro. Agile learned by doing, not by memorizing definitions.

![Chain%20H](https://img.shields.io/badge/Chain%20H-06B6D4?style=for-the-badge) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](LICENSE-GPL) [![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue?style=for-the-badge)](LICENSE-AGPL)

[📖 Lesson Plan](docs/LESSON_PLAN.md) · [🧾 Cheat Sheet](docs/CHEATSHEET.md)

<!-- SCREENSHOT PLACEHOLDER: docs/screenshots/board.png -->

## Why This Was Built

Every team I want to work on runs some flavor of **Scrum**, and "I know Scrum" is easy to *say* and hard to *show*. So instead of another glossary, this is a **playable sprint**: an in-browser simulator where I estimate a backlog with planning poker, pull stories into a sprint by capacity, move cards across a **To Do → In Progress → Done** board, and watch a **burndown chart** react in real time. The lesson panel teaches the framework — roles, artifacts, events — and the practice panel makes me *use* it.

The goal is fluency with the mechanics **and** the intent: why the events exist, what each artifact is really for, and the anti-patterns (status-meeting standups, scope creep mid-sprint, a retro with no actions) that quietly kill agility.

## What you do in the tour

```
  Backlog            Planning poker         Sprint board            Burndown
  ───────            ──────────────         ────────────            ────────
  ordered by value ▶ estimate in points  ▶  To Do → Doing → Done  ▶  points remaining
        │                   │                      │                    │ vs the ideal line
        └─ PO owns order    └─ team estimates      └─ advance the day    └─ reveals over/under-commit
```

## Topics Covered

| Area | What the lesson + simulation cover |
|------|-----------------------------------|
| Framework | Scrum in one picture: pillars (transparency, inspection, adaptation) + values |
| Roles | Product Owner, Scrum Master, Developers — who owns what (and what they don't own) |
| Artifacts | Product Backlog, Sprint Backlog, Increment + their commitments (Goal, Sprint Goal, DoD) |
| Estimation | Story points vs hours, planning poker, velocity, capacity-based commitment |
| Events | Sprint, Planning, Daily Scrum, Review, Retrospective — timeboxes + purpose |
| Metrics | Burndown, velocity, and how to read them honestly |
| Anti-patterns | Standup-as-status, mid-sprint scope creep, actionless retros |

## How This Connects

Foundations chain (**Chain H**) — the *how teams actually deliver* companion to the CLI + CRM builds. Scrum here pairs with **Jira-Workflow** (the tool that operationalizes it) and underpins every later chain: you plan and ship the data, AI, and PropTech projects in sprints.

## License

Dual-licensed **GPL-3.0** / **AGPL-3.0** (see `LICENSE-GPL`, `LICENSE-AGPL`).
