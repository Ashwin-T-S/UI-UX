# 05 - The Six Sprints

The whole 27 weeks on one page. Read it once so you know where you are going, then forget it and work one week at a time. Ten designers work in parallel, with codes UX1 to UX10.

Week 0 is not a sprint. It is one setup week that comes before everything else, and nothing creative is judged there.

---

## The map

| Sprint | Weeks | Project | Focus | What you leave with |
|---|---|---|---|---|
| **0** | 0 | Setup | Accounts, tools, repo, first commit, first page | A working fork, a first pull request, a first HTML page, accessibility tools installed (Z0.1 to Z0.8) |
| **1** | 1-4 | Kerala PSC, apply for a post, for a (fictional) state recruitment digital services team | Visual craft, one complete flow | One rebuilt high-stakes flow, every state, accessibility passing, a position and a portfolio started (JR1) |
| **2** | 5-8 | A skill scheme with a 38% drop inside its enrolment form | Research and framing | 5 interviews, a usability study, findings with confidence levels, case study 1 and a live skeleton (JR2) |
| **3** | 9-12, plus 12b | Sutra, a language-learning app and its subscription flow | Interaction, motion, metrics and ethics, then one coded screen | A state machine, a motion spec, an activation definition, an ethics position, a visual showpiece, a live portfolio, your first mock interview (JR3) and a small AI-assisted coded prototype published on GitHub Pages (L-AI6) |
| **4** | 13-16 | A health tech company with three products, three frameworks and two brands | Design systems, governance, adoption | A costed audit, a three-layer token set in the standard format, six documented components, a governance model, the system case study and mock interview 2 (JR4) |
| **5** | 17-20, plus 20b | Your choice of four (health appointments, gig worker disputes, school-to-work, loan console with an AI score), or your own | The capstone, then the agent lab | A project you scoped, researched, designed, tested and defended without scaffolding; an AI-feature lab; the capstone draft and mock interview 3 (JR5); a set of agent UX patterns from L-AI7 |
| **6** | 21-24 | You | Portfolio, interview, and getting hired | Three case studies, a live portfolio, ten applications, a full mock loop, and an honest external readiness check |

**Sprint 1 note (Kerala PSC).** Design a simulated application flow using public pages only. Never log in, register, apply, submit or open personal profile screens. Save public-page screenshots in week 1; if the site changes, note the date and continue from those screenshots.

---

## Why this order

**Week 0 is the floor.** You cannot work in a repo you have not forked. One week of installing Figma, Penpot, VS Code and Git, then one image and one Figma link in your first commit. It is boring and it is the week that stops later panic.

**Sprint 1 is craft, first, deliberately.** You cannot do research well if you cannot make a screen that works. Four weeks of type, colour, space, states, and accessibility comes before anything else because everything after it is built on top.

**Sprint 2 is research, second.** Now that you can build, you learn how to find out what to build. Sprint 1 gave you a flow you designed from a brief. Sprint 2 makes you go and check whether the brief was right.

**Sprint 3 is the product and the person.** Interaction, motion and the business meet in one consumer flow, and it is where you first have to say what your design does to money and to the user in the same sentence. It is also the sprint that asks where your line is, and the one that produces your visual showpiece.

**Week 12b is one extra week on top of that.** You take one screen from your showpiece, write a prompt and a spec, let an AI coding assistant build it, then read the code, fix it, check it with axe and the keyboard, and publish it on GitHub Pages. You do not learn to program. You learn to direct and to check. Use a free tier; check the free limit before use. Complete Y1.7, the AI note and log, after publishing.

**Sprint 4 is the invisible work.** Tokens, components, documentation, governance. Nobody compliments it. It is what holds products together, it is where design meets code, and it is a large share of the jobs available.

**Sprint 5 is the whole job.** Almost nothing new is taught. You choose a project and run it. One option contains an AI model whose output a human has to interpret without over-trusting it; every designer does a lab on that problem.

**Week 20b is the agent lab.** One extra week where you take your own capstone and add agent behaviour: intent preview (showing the planned action), an autonomy dial (choosing how much the agent may do), confirmation gates (approval before an action), undo, and escalation to a human (asking a human for help). AI products are moving from "answer me" to "act for me", and someone has to design the control.

**Sprint 6 is the evidence.** The work is done; now it has to convert into an interview. A portfolio is an argument made to a stranger in ninety seconds. You do not start it here, you finish it.

---

## What runs alongside every sprint

| Strand | What it is | Where |
|---|---|---|
| **Learn then do** | A named source in the morning, a task in the afternoon, a summary committed | Every week file |
| **The failure** | Something is injected mid-sprint and you write a post mortem | Sprints 1-5; in Sprint 6 it is the external review |
| **The gates** | States, accessibility, evidence. Checklists, not opinions. | `01-How-The-Program-Works.md` |
| **The defense** | 55 minutes in Sprints 1-2, 60 in 3-4, 75 in Sprint 5, 90 in Sprint 6 | Week 4 of each sprint. Week 0 has no defense |
| **AI in design** | Seven labs: five on using AI honestly (L-AI1 to L-AI5), L-AI6 in week 12b, L-AI7 in week 20b | `07-AI-In-Design.md` |
| **Prototyping and responsive** | Four labs (L-PR1 to L-PR4) | `08-Prototyping-And-Responsive.md` |
| **Job readiness** | Five tasks, three mock interviews, an external check | `06-Job-Readiness-Track.md` |
| **Current practice** | The standards, theory and tools of now, and where they are taught | `09-Modern-Practice-Map.md` |
| **Code corners** | 20 to 40 minutes of HTML, CSS or Git, inside a normal week | Weeks 0, 3, 6, 10, 12b, 15, 22. See `12-HTML-CSS-For-Designers.md` |
| **The repo** | One folder per week, one commit per task, one pull request per week | `10-GitHub-For-Designers.md` |
| **The team repo** | Folder rules, shared folders, who updates `delivery/` | `11-Team-Repo-And-Delivery.md` |

---

## One Figma file per sprint, one folder per week

**Figma.** You are on the free Starter plan. That means one team, one folder, 3 files, 30 days of version history, no libraries and no Dev Mode. So the rule is: ONE Figma file per sprint, named `SPRINT-N UX{n}`, with one page per week inside it. You also keep one spare file. The current sprint file and one spare use two of the three available files. Check the total before creating another sprint file; use Penpot if the limit blocks you.

If the 3-file limit blocks you, move that sprint's work to Penpot (https://penpot.app/, free and open source, in the browser: check the free limit before use). The Figma Education plan (https://www.figma.com/education/) may lift the limits, but you must be eligible and verified: ask the admin, do not assume.

The shared design system lives in ONE team library file only if the plan allows libraries. If it does not, it lives as tokens in `system/` (markdown and JSON), shared by view-only link plus exported tokens.

**The repo.** Fork https://github.com/StartwithDot/UI-UX, clone your fork, work on a branch, open a pull request. Include the task or week in your branch name, for example `ux1-week0-z0-5`. Your work goes in `Design-Sprint-N/students/UX{n}/weekX/`. The shared folders are `system/`, `delivery/` and `fundamentals/`. `delivery/` is updated only by the team leader.

**What you may commit.** Markdown, PNG or JPG under 2 MB (lowercase, hyphens, no spaces, for example `r1-1-home-page.png`), PDF under 10 MB, and a view-only Figma link written inside a markdown file. Small `.html`, `.css` and `.js` files and code folders are allowed for code corners. A view-only Penpot link in a markdown file is also allowed. Never .fig files, passwords, tokens, or real personal data. No real names, faces, phone numbers or IDs anywhere. People in your notes are P1, P2.

Tool setup for all of this is in `04-Tools-Setup.md`.

---

## What gets harder, sprint by sprint

| | S1 | S2 | S3 | S4 | S5 | S6 |
|---|---|---|---|---|---|---|
| Weeks | 1-4 | 5-8 | 9-12b | 13-16 | 17-20b | 21-24 |
| Scope | 1 flow | 1 flow | 1 consumer flow and 1 coded screen | 1 system, 3 products | 1 project, your scope, plus agent patterns | 3 case studies |
| Users you talk to | 1 observed | 5 interviewed, 5 tested | 2 prototype sessions | 3 teams | 5 interviewed twice, 1 person for the agent test | Hiring managers |
| Evidence required | heuristics | primary research | metrics and experiments | adoption data | research that changed the design | honest results |
| Who you argue with | a department | a mission | a founder with 16 months of runway | three engineering leads | an external reviewer | external interviewers |
| Guidance | step by step | step by step | step by step | step by step | **none** | self-directed |
| External eyes | critique, defense | JR2 review | live portfolio review, mock 1 | mock 2 | mock 3, presentation | panel, mock loop, check |

---

## The things that carry across all 27 weeks

**The design system.** Started in Sprint 1 week 1 with a type scale and a colour ramp. Each sprint's `system/` starts as a copy of the last, so every shortcut you take in week 2 is still there in week 20. By Sprint 4 it is a multi-brand token architecture with governance, and the next cohort inherits it.

**The fundamentals folders.** ~120 drill entries, a summary every week, 24 teardowns, 6 explainers, and every why session you presented. This is the only complete record of what you learned.

**The portfolio.** Case-study drafts from Sprint 1, a live site by week 12, a coded prototype from week 12b, and three recorded mock interviews. The portfolio is not a Sprint 6 task; Sprint 6 is where you finish it.

**The setup.** You install the tools once in week 0 and use the same setup to week 24: Figma free as the main tool, Penpot as the backup, VS Code and Git for the code corners, one repo, one branch per week.

---

## What you have at the end

- 3 portfolio-grade case studies, each with a failure in it
- A live, accessible portfolio
- A design system you helped build and govern
- A visual showpiece, a research-led flow, and a complete capstone
- A small AI-assisted coded prototype, published and checked
- A set of agent UX patterns tested with one person
- 24 teardowns of real products
- ~120 drill entries
- 6 passed defenses
- 3 recorded mock interviews and a full mock loop
- An external, honest assessment of readiness
- A written ledger of what you can demonstrably do

The portfolio is a by-product. The thing being built is the ability to defend a decision to someone who wants it to be wrong.

---

Now go to `Design-Sprint-1/00-READ-FIRST.md`. If you have not done week 0 yet, start there.
