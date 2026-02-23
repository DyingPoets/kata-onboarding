# Employee Onboarding — Feature Decomp + WO Sequencing

> **Branch:** `skill/decomp-sequencing`
> **Skills:** A4 · W5 · T5
> **Audience:** PM · Eng

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 7: Employee Onboarding |
| **Session** | Feature Decomp + WO Sequencing |
| **Skills** | A4 · W5 · T5 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/f04w3i7d63m7zoq |
| **Miro Board** | https://miro.com/app/board/uXjVG8QBtWU%3D/ |

### Session Timing

| Time | Activity |
|------|----------|
| 0:00–0:15 | Concept framing — open the Gamma slide deck and walk through each slide |
| 0:15–0:30 | Orient to Miro board + this starting state |
| 0:30–1:05 | Step 1 exercise (Miro — Context frame) |
| 1:05–1:25 | Step 2 exercise (Miro — Exercise frame) |
| 1:25–1:30 | Step 3 wrap-up |
| 1:30–1:50 | Debrief — use Miro Debrief frame prompts |
| 1:50–2:00 | Extension brief — point to Extension Zone in Miro |

### What to Watch For

- Slices that aren't independently deployable — "this depends on X being done first" is the smell
- Critical path not identified — teams that sequence without looking at dependencies
- Acceptance criteria with AND — each criterion should test one thing

### Facilitation Tips

- For each slice: "Could this be demo'd to the HR manager independently?" If no, keep splitting
- Dependency map: post it in Miro, then ask "what would unblock the most work if done first?"
- For acceptance criteria: read them as Given/When/Then — does it fit?

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-onboarding
git checkout skill/decomp-sequencing
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/f04w3i7d63m7zoq
- **Miro Board:** https://miro.com/app/board/uXjVG8QBtWU%3D/

### What You'll Practice

- A4
- W5
- T5

### Your Starting State

You have:
- `approved-flows/onboarding-future-state.md` — approved user flow from Session 1
- `templates/work-order-template.md` — WO format

Your goal: decompose into vertical slices, draw the dependency map, and write acceptance criteria for the first 2 WOs.

### Step by Step

**Step 1:** Break the onboarding flow into vertical slices. Each slice must be: user-visible, testable, independently deployable.

**Step 2:** Draw the dependency map in Miro. What can start immediately? What is blocked? What is the critical path?

**Step 3:** Write acceptance criteria for WO 1 and WO 2. Happy path + 2 edge cases each.

### What Good Looks Like

Slices that a stakeholder could see working at the end of a single sprint. A dependency map that reveals the critical path at a glance.

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Add e2e test scenarios for the critical path slices in Gherkin format
- Estimate the critical path in hours — what's the earliest you could ship the first usable slice?
- Write a "definition of done" for this project — what must every WO have before it can be marked complete?

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.
