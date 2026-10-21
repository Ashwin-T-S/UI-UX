# Sprint 1 — Read First

**Weeks 1 to 4 · Visual craft and one complete flow**

---

## What you are building

You are rebuilding the **Kerala PSC apply-for-a-post journey**.
The client is a fictional digital services team inside a state recruitment body.
This is a fictional client, but a real public service.
One flow, done fully: every screen and every state.
It must work on a phone, in Malayalam and English.
It must pass a real accessibility check.
It must work for three users.
An anxious first-time applicant may miss a deadline.
A repeat applicant uses a cheap Android phone, has patchy data, and reads Malayalam first.
A low-vision candidate uses TalkBack (a screen reader on Android).

Not a concept. Not three pretty screens. A complete flow you can defend.

---

## Read these in this order

| # | File | When |
|---|---|---|
| 1 | `00-READ-FIRST.md` | now |
| 2 | `01-project-brief.md` | now, before the sprint starts |
| 3 | `02-week1.md` | when week 1 opens |
| 4 | `03-week2.md` | when week 2 opens |
| 5 | `04-week3.md` | when week 3 opens |
| 6 | `05-week4.md` | when week 4 opens |

Reference, open when a task points at them:
- `06-accessibility-gate.md` — the checklist that decides whether you shipped
- `07-critique-guide.md` — how the week's critique works and what a valid comment is
- `08-glossary.md` — every term used in this sprint, defined plainly

---

## The four weeks

| Week | Called | You learn | You produce |
|---|---|---|---|
| **1** | Frame | Hierarchy, type scales, spacing, colour ramps | A reframed brief, an audit of the live service, and your visual foundations |
| **2** | Build | Forms, validation, error messages, microcopy | The full flow at mid fidelity with every error message written |
| **3** | Test and fix | Every state a screen can be in | A usability test on 3 people, a states matrix, and fixes traced to findings |
| **4** | Ship and defend | Accessibility: WCAG AA, keyboard, screen readers | High fidelity flow, a passed accessibility gate, a handoff spec, and a defense |

---

## Every task

```
STUDY    LEARN     1 to 2 h    named source, then a committed summary
BUILD  DO        1 to 2 h    a task built on that day's LEARN reading
```

Week files give you the exact chapter, the exact page range, the exact video. Never "read about typography".

**How to read a task**

Every task has the same parts, in the same order. Read them from the top.

| Part | What it tells you |
|---|---|
| **What we are doing** | What you will make, in one or two short sentences |
| **Why we are doing it** | What goes wrong in a real job if you skip it |
| **Before you start** | What to have ready, and how long it takes |
| **Where to find help** | The exact page, link or file to look at |
| **How to think about it** | Questions to ask yourself while you work |
| **Learn first** | The part of today's reading the task uses |
| **Method** | The steps, one by one |
| **Worked example** | A finished answer for a different case, so you see the shape |
| **Common mistakes** | Mistakes beginners often make, and the quick fix |
| **Done when** | A checklist. Tick every box, then you can stop |

The last line of a task, the one that starts with an arrow, names the file you commit.

If a task is not clear, do not feel bad. Ask in the cohort channel. It means the task needs fixing.

---

## What you commit

```
students/UX{n}/week1/
  session1-learning.md          ← one per session
  session2-learning.md
  session3-learning.md
  session4-learning.md
  session5-learning.md
  P1-1-brief-questions.md   ← task outputs, task ID first
  C1-1-type-scale.md
  ...
```

One task, one commit with all files listed for that task. Commit message starts with the task ID:

```
git commit -m "C1.1 type scale with Malayalam test"
```

---

## The shared design system

`system/` is one design system that the whole cohort depends on, and it is the same system for all 24 weeks. In week 1 it is a type scale, a spacing scale, and a colour ramp. By Sprint 4 it is a real multi-brand token architecture.

Because it is shared, mistakes there block five people. It gets stricter review than your own folder.

The **system owner** for the week merges contributions. That role rotates.

---

## What ships at the end of week 4

- The full flow, high fidelity, at 390px and 1440px
- Every state designed, not described
- Every error message written
- A completed accessibility gate with evidence on every line
- A handoff spec an engineer could build from
- One decision record for the choice a client team member would question
- One post mortem on the mid-sprint failure
- 20 learning summaries
- A passed defense
- Two labs: AI as a source of options (L-AI1, week 2) and responsive behaviour (L-PR1, week 3)
- Your portfolio positioning, platform decision and asset checklist (JR1, week 4)

---

## What will be hard, and it is meant to be

**The brief is deliberately bad.** "Make applying simple, so we get fewer wrong applications and fewer calls to the office." Week 1 is about turning it into something answerable. If you start designing screens on the first task you will design the wrong thing.

**You cannot invent users.** Three users are described in the brief. One is an anxious first-time applicant. One is a repeat applicant on a cheap Android phone with patchy data and Malayalam first. One is a low-vision candidate using TalkBack. Each has a different failure mode. You design for all three, not the easiest one.

**Something will break in week 3.** A constraint will change. You will not know which one until it lands. You write a post mortem about what it cost you.

**The accessibility gate does not move.** Pretty work that fails the gate is not done. You will run a screen reader over your own flow, and the first time is unpleasant for everyone.

---

## Before the sprint starts

- [ ] Read `01-project-brief.md`
- [ ] Have Refactoring UI downloaded
- [ ] Figma set up, four Learn lessons done (see root `04-Tools-Setup.md`)
- [ ] axe DevTools installed
- [ ] Repo forked and cloned
- [ ] Open https://www.keralapsc.gov.in/ and read the safety rules in `01-project-brief.md` (section 12). Do not register, log in or submit anything.

Then open `02-week1.md`.
