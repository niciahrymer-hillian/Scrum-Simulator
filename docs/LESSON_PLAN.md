# 📖 Lesson Plan — Scrum-Simulator

> A playable Scrum lesson: learn the framework in the left panel, run a real sprint in the right.

## What This Project Is

An interactive, self-contained lesson on the **Scrum** framework. There's no backend and nothing to
install — the [interactive tour](interactive/index.html) opens in a browser and lets you drive a full
sprint: estimate a backlog, commit by capacity, work a board day by day, and read the burndown. The
lesson content is the *why*; the simulator is the *how*.

## Learning Objectives

By the end I can:

1. Explain Scrum's three pillars (transparency, inspection, adaptation) and why the events enforce them.
2. Name the three accountabilities (Product Owner, Scrum Master, Developers) and what each owns.
3. Distinguish the artifacts (Product Backlog, Sprint Backlog, Increment) and their commitments
   (Product Goal, Sprint Goal, Definition of Done).
4. Estimate work in **story points** with planning poker, and use **velocity** to commit realistically.
5. Read a **burndown chart** — recognize over-commitment, scope creep, and a healthy sprint.
6. Run each event (Planning, Daily Scrum, Review, Retrospective) for its actual purpose.
7. Spot the common anti-patterns that turn Scrum into waterfall-with-standups.

## Topics Covered

- **Framework:** empiricism, pillars, values (commitment, focus, openness, respect, courage).
- **Roles:** PO orders value; SM coaches the process; Developers own *how* and the estimate.
- **Artifacts & commitments:** Backlog → Sprint Backlog → Increment; Product Goal / Sprint Goal / DoD.
- **Estimation:** points vs hours, relative sizing, planning poker, capacity, velocity.
- **Events:** the Sprint container + Planning, Daily Scrum, Review, Retro (timeboxes and intent).
- **Metrics:** burndown (remaining work vs the ideal line), velocity trend.
- **Anti-patterns:** status-meeting standups, mid-sprint scope changes, retros with no follow-through.

## The Interactive Tour

`docs/interactive/index.html` — an 8-step split-panel tour:

1. **Scrum in one picture** — pillars + the empirical loop.
2. **The three accountabilities** — who owns what.
3. **Artifacts & commitments** — backlog, sprint backlog, increment.
4. **Estimation & planning poker** — size the backlog interactively.
5. **Sprint planning** — commit stories by capacity; build the Sprint Backlog.
6. **Run the sprint** — advance the board day by day; watch the burndown.
7. **Review & retrospective** — inspect the increment, commit to one improvement.
8. **Key objectives / cheat sheet** — the keep-forever summary + a quiz with Check-Your-Understanding.

The right panel is a live **sprint board + burndown**: estimate points, commit by capacity, move cards
To Do → In Progress → Done, and "Advance day" to see remaining points track (or diverge from) the ideal
line.

## Build Order

1. Read the lesson steps 1–3 (framework, roles, artifacts).
2. Estimate the backlog in step 4 (planning poker).
3. Commit a sprint within capacity in step 5.
4. Work the board and advance days in step 6; explain the burndown you produced.
5. Run review + retro in step 7; write one concrete retro action.
6. Take the quiz in step 8; keep the cheat sheet.

## Reflection Questions

- Why are estimates owned by the Developers, not the Product Owner?
- What does a burndown that stays flat for three days then drops on the last day tell you?
- A stakeholder asks to "just add one more story" mid-sprint. What's the Scrum-aligned response?
- What makes a retrospective effective vs. theater?

## How This Connects Forward

Pairs with **Jira-Workflow** (Chain H) — the tool that runs this process — and sets up how every later
chain is delivered: the data, AI, and PropTech projects are planned and shipped in sprints.

## Git Commit Checklist

- [ ] `README.md`, `docs/LESSON_PLAN.md`, `docs/CHEATSHEET.md`
- [ ] `docs/interactive/index.html` opens and the sprint simulation runs
- [ ] `LICENSE-GPL`, `LICENSE-AGPL`, `.gitignore`, `docs/screenshots/`
