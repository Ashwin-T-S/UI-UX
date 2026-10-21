# 02 - Learning Path

The 27 weeks of learning, week by week. This is the answer to "what am I supposed to be learning right now". The 27 weeks are week0, weeks 1 to 24, week12b and week20b.

Every week has a topic, the named primary sources, and the skill you should be able to demonstrate by the end of it. The week files inside each sprint folder break this down to the day. Current standards and tools for each area are in `09-Modern-Practice-Map.md`. Setup is in `04-Tools-Setup.md`.

---

## How to use this file

- **At the start of every week:** read your row. Then open the week file for the details.
- **Your code.** You are UX1 to UX10. Your work goes in `Design-Sprint-N/students/UX{n}/weekX/`. Never use real names, faces, phone numbers or IDs. Participants are P1, P2.
- **Files you may commit.** Markdown (`.md`), PNG/JPG under 2 MB, PDF under 10 MB, small `.html`, `.css` and `.js` files, task code folders such as `week12b/page/`, and a view-only Figma or Penpot link inside a markdown file. Name images in lowercase with hyphens, no spaces. Never commit `.fig` files, passwords, tokens or real personal data.
- **Nothing is assigned that is not used.** If a book is in a row, a task that week needs it.
- **Reading ahead is fine.** Reading instead of doing is not.
- **Labs.** Sixteen short labs are scheduled in the program, in three families: `L-AI` (AI in design, `07-AI-In-Design.md`), `L-PR` (prototyping and responsive, `08-Prototyping-And-Responsive.md`) and `JR` (job readiness, `06-Job-Readiness-Track.md`). Most sit on a week's Day 6. They appear in the tables below. `L-AI6` is in week12b and `L-AI7` is in week20b.

Primary sources are listed by short name. Full details, cost, and where to get them are in `03-Books-And-Resources.md`.

## Tool and file rule

- **Main tool.** Figma free (Starter) plan. Starter has one team, one folder and 3 files, 30-day version history, no libraries, no Dev Mode, 150 AI credits per day up to 500 per month. Check the free limit before use.
- **One Figma file per sprint.** Name it `SPRINT-N UX{n}`. Use one page per week. Keep 1 spare file. Do not make three files per sprint.
- **Backup.** Penpot (https://penpot.app/) is free and open source in the browser. Use it when the Figma 3-file limit blocks you. Check the free plan before use.
- **FigJam and libraries.** FigJam counts toward limits, so use it sparingly. If the admin confirms the Figma Education plan (https://www.figma.com/education/), limits may lift. Ask the admin. Do not assume.
- **Repo docs.** Read `04-Tools-Setup.md` before week0. It has Mac and Windows steps. `10-GitHub-For-Designers.md` covers fork, clone, branch, commit and pull request. `11-Team-Repo-And-Delivery.md` explains the shared folders; `delivery/` is updated only by the team leader. `12-HTML-CSS-For-Designers.md` covers the code corners. AI rules are in `07-AI-In-Design.md`.
- **Code corners.** These are 20-40 minutes. Week0: install VS Code and Git, make your first page. Week3: CSS box model and flex, linked to Auto Layout. Week6: HTML forms for the research form. Week10: read a little JavaScript, a click that changes state. Week12b: full AI-assisted coded prototype, published on GitHub Pages. Week15: CSS variables as tokens. Week22: portfolio page on GitHub Pages.

---

## Sprint 1 · Weeks 0 to 4 · Set up, visual craft and one complete flow
*Project: Kerala PSC, apply for a post, for a (fictional) state recruitment digital services team. Week 0 sets up your tools and repo before the project.*

**Kerala PSC brief:** Start at https://www.keralapsc.gov.in/ and inspect Notifications and Tips to Applicants. Use public pages only. Never log in, register, apply, submit or open personal profile screens. In week1, save screenshots and record the date. Work from those screenshots if the site changes.

| Week | Topic | Primary source | You can do this by the end of the week |
|---|---|---|---|
| 0 | **Set up (Z0.1-Z0.8).** Accounts, Figma and Penpot, VS Code and Git, fork, first commit and pull request, first HTML page, accessibility tools check | `04-Tools-Setup.md` · `10-GitHub-For-Designers.md` · `12-HTML-CSS-For-Designers.md` · web.dev Learn HTML | Make your accounts and fork; use one Figma file per sprint and Penpot backup; commit an image and a view-only Figma link; open a pull request; make and open a first HTML page locally; run the accessibility tools check |
| 1 | **Frame.** Reframe a vague brief; hierarchy, type, spacing and colour foundations | Refactoring UI ch. 1-6 · Practical Typography · NNGroup heuristics · WCAG 2.2 AA · Figma Learn: Auto Layout, Components | Turn a bad brief into a problem statement; audit a live service; build a type scale, spacing scale and colour ramp and say why each step exists |
| 2 | **Screens and states.** Every state a screen can be in; forms, labels, validation, error messages | Form Design Patterns ch. 1-3 · NNGroup on error messages · Polaris content guidance · Figma Learn: Variants | Produce a states matrix; design a form where every field has a label, hint and validation rule; write every error message · **L-AI1** |
| 3 | **Flow and responsive.** Draw flows with every failure path; responsive layout (code corner: CSS box model and flex, linked to Auto Layout) | Refactoring UI ch. 8 (empty states) · Material 3 and Polaris state guidance · Rocket Surgery Made Easy ch. 1-4 · `12-HTML-CSS-For-Designers.md` · web.dev Learn CSS | Draw a flow with every failure path; build a responsive flow that works at small and large sizes; test with three people without leading them; trace every change to a finding; write a review on a change you did not choose · **L-PR1** |
| 4 | **Ship and defend.** Accessibility, high fidelity, handoff | WCAG 2.2 AA · web.dev Learn Accessibility · Deque University · Refactoring UI ch. 6-8 · Norman ch. 1-4 | Run a real accessibility gate with evidence on every line; use VoiceOver on Mac or NVDA on Windows to test your HTML page; document reading order and labels for the visual prototype separately; write a handoff spec; defend four weeks of decisions · **JR1** |

**Week 0 Git note:** Set Git’s commit email to your GitHub no-reply address, including in GitHub Desktop. Use browser sign-in or GitHub Desktop for pushes; GitHub does not accept your account password.

**Fundamentals spine:** Gestalt principles · visual hierarchy and whitespace · cognitive load and progressive disclosure · affordances, signifiers and mental models.

---

## Sprint 2 · Weeks 5 to 8 · Research and problem framing
*Project: a skill scheme with a 38% drop inside its enrolment form; the client has already diagnosed "motivation".*

| Week | Topic | Primary source | You can do this by the end of the week |
|---|---|---|---|
| 5 | **Plan.** What research is for; assumptions and risk; ethics and consent | Just Enough Research (whole book) · Interviewing Users ch. 1 · `06-research-ethics.md` | Write a research plan that can fail, with a ranked assumption list; recruit five real participants |
| 6 | **Talk.** Interviewing without leading (code corner: HTML form for the research form) | Interviewing Users ch. 2-5 · Just Enough Research on synthesis · NNGroup on affinity diagramming · `12-HTML-CSS-For-Designers.md` · web.dev Learn forms | Run a 45-minute interview, critique your own transcript, turn five conversations into patterns · **L-AI2** |
| 7 | **Test.** Usability testing with no budget | Rocket Surgery Made Easy ch. 1-6 · Don't Make Me Think · NNGroup severity ratings | Run a moderated study on five people; severity-rate every finding; absorb a research-invalidating constraint |
| 8 | **Synthesise.** Findings, confidence, contradiction | Just Enough Research on reporting · NNGroup on sample size and personas · journey mapping and service blueprints · Norman on human error | Present findings with honest confidence levels; trace every design change to a finding; defend a sample of five · **JR2** |

**Fundamentals spine:** memory, attention and cognitive load · mental models and the gulf of evaluation · bias · the psychology of decision-making.

---

## Sprint 3 · Weeks 9 to 12b · Interaction, motion, metrics, ethics and AI-assisted coded prototype
*Project: Sutra, a language-learning app, and its subscription flow. The consumer, visually ambitious project, and your portfolio's front page.*

| Week | Topic | Primary source | You can do this by the end of the week |
|---|---|---|---|
| 9 | **Spec to prototype.** Turn specs into interactive prototypes; state machines, feedback, latency | About Face (postures, undo) · statecharts.dev · NNGroup on response times | Draw a state machine with every guard (a condition that allows a transition); specify feedback by real latency; build a clickable prototype from a spec · **L-AI3** |
| 10 | **Motion.** Animation that communicates (code corner: a click that changes state in JavaScript) | Designing Interface Animation (Val Head) · Material motion · WCAG 2.3.3 · `12-HTML-CSS-For-Designers.md` · web.dev Learn JavaScript | Choose duration and easing for a reason; delete decoration; build a reduced-motion version that is not just "instant"; write a motion spec · **L-PR2** |
| 11 | **Metrics/ethics.** Persuasion versus manipulation; activation and funnels | Google HEART paper · Lean Analytics (funnels) · deceptive.design · CMA, FTC and India CCPA guidance · Ruined by Design · Fogg behaviour model | Name the mechanism behind a dark pattern; build one and account for its cost; make the business case for the honest version with an experiment design; define activation and a metric set with a guardrail; handle a business demand |
| 12 | **Showpiece/live portfolio.** Ethics and ship; where your line is | ACM Code of Ethics · `06-ethics-position.md` · WCAG for interactive components · ARIA APG | Write an ethics position and a refusal a manager could receive; ship an accessible, specified flow with instrumentation; produce the showpiece; publish a live portfolio · **JR3** |
| 12b | **Coded prototype (Y1.1-Y1.7).** One screen from your showpiece, AI-assisted build, publish | `12-HTML-CSS-For-Designers.md` · `07-AI-In-Design.md` · web.dev Learn HTML · web.dev Learn CSS · axe DevTools · GitHub Pages quickstart (https://docs.github.com/en/pages/quickstart) | Pick one showpiece screen; write a prompt and spec; choose a free-tier AI coding assistant; check the free limit before use; generate with an AI coding assistant; read and fix the code; check with axe and keyboard; publish on GitHub Pages; write the AI note and log · **L-AI6** |

**Fundamentals spine:** feedback loops and the two gulfs · perception of time and change blindness · persuasion, nudging and choice architecture · ethics in practice.

---

## Sprint 4 · Weeks 13 to 16 · Design systems, scale and governance
*Project: a health tech company with three products on three frameworks and two brands.*

| Week | Topic | Primary source | You can do this by the end of the week |
|---|---|---|---|
| 13 | **Tokens.** Audit; three-layer architecture; theming | Design Systems (Kholmatova) ch. 1-3 · `06-token-architecture.md` · Design Tokens spec 2025.10 · Style Dictionary and Tokens Studio docs · Material 3 and Polaris token docs · Expressive Design Systems | Cost the divergence; build a primitive, semantic and component token set (primitive: raw values; semantic: purpose-based; component: component-specific) that themes three products without redesign; export it in the standard format · **L-PR3** |
| 14 | **Components.** APIs, variants, slots, documentation | Atomic Design · Design Systems ch. 4-5 · Radix, React Aria or Headless UI docs (composition) · ARIA APG · Storybook docs | Design a component API and defend every property; write documentation a stranger can build from; compose without impossible combinations · **L-AI4** |
| 15 | **Governance.** Who decides; rejection; deprecation (code corner: CSS variables as tokens) | Design Systems ch. 6-7 · Polaris, Carbon and GOV.UK contribution guides · semver · `12-HTML-CSS-For-Designers.md` · web.dev Learn CSS | Write a contribution model with rejection criteria; reject a contribution kindly; deprecate something people use |
| 16 | **Adoption.** Measurement; migration; being ignored | Design Systems ch. 8 · Sparkbox and Zeroheight articles on adoption · semver · web.dev Learn HTML (for L-PR3 and L-AI4) | Measure adoption with something better than a feeling; diagnose a fork; write a migration guide someone completes · **JR4** |

**Fundamentals spine:** abstraction and indirection · Conway's law · APIs as contracts · standardisation versus autonomy.

---

## Sprint 5 · Weeks 17 to 20b · The capstone
*Project: your choice of four (public health appointments, gig worker earnings and disputes, school-to-work, loan underwriting console with an AI score), or your own, approved.*

| Week | Topic | Primary source | You can do this by the end of the week |
|---|---|---|---|
| 17 | **Frame.** Scope it yourself; research; evidence gate | You choose and justify · Google People + AI Guidebook and Microsoft HAX (for L-AI5) | Write your own scoped task list; run research without a template; pass an evidence gate · **L-AI5** |
| 18 | **Design.** The whole flow to the standard in a week | You choose · current Apple HIG or Material 3 for your platform | Hold Sprint 1 to 4 standards unprompted; pass the craft gate · **L-PR4** |
| 19 | **Test.** Real users; iterate; respond to a new constraint | You choose | Change a design because of evidence and show the trace; absorb a severe late constraint; review your own work for the ethical problem you created |
| 20 | **Ship.** Spec, present, defend all twenty weeks | No new source | Ship a complete, specified, accessible design; present to a stranger; defend anything from week 1 · **JR5** |
| 20b | **Agent UX lab (A5.1-A5.7).** Control, consent and accountability for agent actions | Smashing Magazine Feb 2026 "Designing For Agentic AI: Practical UX Patterns For Control, Consent, And Accountability" (check before use) · NN/g articles (search https://www.nngroup.com/) | List agent actions; set autonomy level and scope; add intent preview and confirmation gate; show reasoning, confidence and failure states; add undo and audit trail; add escalation to a human; prototype and test with one person · **L-AI7** |

**Fundamentals spine:** self-directed. Present the concept the capstone forced you to learn.

---

## Sprint 6 · Weeks 21 to 24 · Portfolio, interview, and getting hired
*The project is the evidence that you can do the job.*

| Week | Topic | Primary source | You can do this by the end of the week |
|---|---|---|---|
| 21 | **Case studies.** Three arguments from twenty weeks | `06-case-study-structure.md` · NNGroup on how users read the web · five real case studies | Choose three on evidence; write them to a structure; include a failure; cut by a third |
| 22 | **Portfolio.** Build it, get it reviewed by a stranger, fix it (code corner: portfolio page on GitHub Pages) | Portfolio patterns · résumé conventions · axe and Lighthouse · `12-HTML-CSS-For-Designers.md` · GitHub Pages quickstart (https://docs.github.com/en/pages/quickstart) | Ship a live portfolio that passes its own accessibility check; take external criticism without arguing |
| 23 | **Interview craft.** Talking about the work | `07-interview-question-bank.md` · whiteboard method | Walk a case study in five and in twenty minutes; solve a design problem on a whiteboard; critique without being soft or unpleasant |
| 24 | **Market.** Applications, a full loop (the complete set of interviews for one role, from first call to final round), and a plan | Application strategy | Send ten real applications; complete a mock loop; say honestly what you are still weak at; leave with a 90-day plan |

**Fundamentals spine:** how hiring managers read portfolios · how design interviews are scored · teaching the hardest concept.

---

## The learning summary

After each LEARN block, ten minutes:

```markdown
# Week {n}, Day {n} - Learning summary

## What I read or watched
- {source}, {chapter or section}, {pages or duration}

## Three things I learned
1.
2.
3.

## One thing I did not understand
## Where I will use this
```

Commit to `Design-Sprint-N/students/UX{n}/weekX/session{n}-learning.md`. Use the exact week folder name in the path, for example `week12b`. Use a commit message such as `UX1 week12b session1 learning summary`. One task, one commit containing all files listed for that task; use `git add` with exact paths.

**Why this matters more than it looks.** At the end of the sprint you sit a defense where you are asked what you know. The only reliable preparation is these files in your own words. Notes you did not write are notes you do not have.

---

## The weekly why session

Ninety minutes at the close of each week. One designer presents the week's fundamentals topic to the group, using the cohort's own work as the examples, never textbook diagrams.

Rotates so everyone presents across the program. Committed to `fundamentals/why-sessions/week{nn}-{topic}.md`. Use a commit message such as `UX{n} weekX why session`.

**Presenting is the test.** You find out what you actually understand at the moment someone asks "why" and you have to answer without the slide.

---

## The weekly teardown

One product surface, pulled apart in writing. Assigned by the admin each week.

Format, every time:

| Section | Content |
|---|---|
| The flaw | What is wrong, specifically, with a screenshot |
| The principle | Which named principle or guideline it violates |
| The user cost | What it costs a real person, in their words not yours |
| The fix | What you would do instead |
| The cost of the fix | What it takes to build. If it is expensive, say so. |

Committed to `fundamentals/teardowns/{nn}-{subject}.md`. Use a commit message such as `UX{n} weekX teardown {subject}`.

Subjects are drawn from products with real constraints: government service portals, bank apps, insurance claims, airline booking, hospital appointments, food delivery checkout, payment confirmation, enterprise consoles, AI assistants, and subscription cancellation flows. Cancellation and consent flows are assigned on purpose, because that is where dark patterns live.

---

## The drill

Ten minutes per session, all 27 weeks.

Pick one component from any real product. Rebuild it from memory in your sprint’s Figma file or Penpot equivalent. Then open the real one and compare. Log one line.

```
Session 14 - Razorpay payment method selector. Missed that the selected state
uses a border plus a check, not just a fill. Overestimated the padding.
```

Committed to `fundamentals/drills/UX{n}-log.md`, appended as you go. Use a commit message such as `UX{n} weekX sessionY drill`.

Ten minutes a session adds up to over 20 hours of pure visual observation. Nothing else in the program builds an eye faster.

---

## If you get stuck

If you get stuck, read the setup guide in `04-Tools-Setup.md` or the week file for your task. Then search the keywords in `03-Books-And-Resources.md` or the source listed in your week row. If you still need help, ask in Discord. Share your task ID, the step you tried, and the exact error. Do not share personal data or secrets.

---

Next: `03-Books-And-Resources.md`.
