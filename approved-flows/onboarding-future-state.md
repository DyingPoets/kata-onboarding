# Employee Onboarding — Future State Flow (Approved)
**Approved by:** [Session 1 output]
**Status:** Ready for decomposition

---

## Flow Overview

The digital onboarding checklist guides new hires through mandatory steps with clear priority, deadlines, and status.

## Screen 1: Onboarding Dashboard
- New hire sees: list of tasks grouped by priority (Urgent / This Week / Eventually)
- Each task shows: title, deadline (if any), estimated time, completion status
- "Start" button per task opens the task detail
- Progress bar (X of Y tasks complete)

## Screen 2: Task Detail
- Task title and instructions
- If the task requires external action (benefits portal, IT ticket), links to the external system
- "Mark complete" button
- Space for notes

## Screen 3: I-9 / Compliance Alert
- Urgent tasks (especially I-9) have a banner alert on the Dashboard
- Alert shows: task name, deadline, consequences if missed
- Dismissible only after task is marked complete

## Screen 4: Progress Notification (Manager View)
- Manager receives summary: new hire name, % complete, any overdue items
- Read-only — manager cannot complete tasks on behalf of new hire

## Screen 5: Completion Summary
- New hire: "Onboarding complete" confirmation with date
- HR: notification that onboarding is complete

---

## MVP Scope (Session 1 Decision)
Ship screens 1 + 2 + the I-9 alert first. This solves the 40% miss rate for the highest-risk items.
