# Week 1 - Frame

**Sprint 1, Week 1 of 4. Theme: understand the problem and build your visual foundations.**

Read this whole file before you start. Then work one task at a time. This is new for most people. Go slowly.

## Week at a Glance

| Task ID | Task name | Time | File you will commit |
|---|---|---:|---|
| P1.1 | Find what the brief does not answer | 20 min | `students/UX{n}/week1/P1-1-brief-questions.md` |
| P1.2 | Rewrite the brief as a problem statement | 20 min | `students/UX{n}/week1/P1-2-problem-statement.md` |
| R1.1 | Capture the current public pages | 45 min | `students/UX{n}/week1/R1-1-current-flow-screens/` |
| R1.2 | Heuristic evaluation | 45 min | `students/UX{n}/week1/R1-2-heuristic-audit.md` |
| R1.3 | Accessibility audit | 45 min | `students/UX{n}/week1/R1-3-accessibility-audit.md` |
| C1.1 | Build a type scale | 45 min | `students/UX{n}/week1/C1-1-type-scale.md` |
| C1.2 | Build a spacing scale | 30 min | `students/UX{n}/week1/C1-2-spacing-scale.md` |
| C1.3 | Measure test | 25 min | `students/UX{n}/week1/C1-3-measure-test.md` |
| C2.1 | Build the colour system | 60 min | `students/UX{n}/week1/C2-1-colour-system.md` |
| C2.2 | Map colours to roles | 45 min | `students/UX{n}/week1/C2-2-semantic-roles.md` |
| Critique | Group critique | 90 min | Critique log, filed by the lead |
| C1.4 | Greyscale hierarchy | 90 min | `students/UX{n}/week1/C1-4-greyscale-hierarchy.md` |
| P1.3 | Constraint list | 45 min | `students/UX{n}/week1/P1-3-constraints.md` |
| P1.4 | Metrics | 40 min | `students/UX{n}/week1/P1-4-metrics.md` |
| S1.1 | Agree token naming | 20 min | `system/docs/token-naming.md` |
| S1.2 | Pick the foundations | 30 min | `system/docs/foundations-decision.md` |
| S1.3 | Write the tokens | 30 min | `system/tokens/primitive.json`, `system/tokens/semantic.json` |
| S1.4 | Shared Figma library or shared source | 30 min | `system/README.md` |
| F1.1 | Why session: Gestalt principles | 30 min | `fundamentals/why-sessions/week01-gestalt.md` |
| F1.2 | Teardown: IRCTC ticket booking | 40 min | `fundamentals/teardowns/01-irctc.md` |
| F1.3 | Drill, from now on | 10 min daily | `fundamentals/drills/UX{n}-log.md` |

About 22 hours of work in this week.

Also commit your learning summaries: `Design-Sprint-1/students/UX{n}/week1/session1-learning.md` to `session5-learning.md`.

## 1. What We Are Doing

This week you understand the problem and build your visual foundations. New flow screens start in week 2. This week you rebuild one existing screen as a greyscale exercise. You only look at public pages. Do not register, log in, apply or submit anything.

Task groups:
- P1.1 to P1.4: reframe the brief, list constraints, choose metrics.
- R1.1 to R1.3: capture public pages, run a heuristic audit, run an accessibility audit.
- C1.1 to C1.4: type scale, spacing scale, measure test, greyscale hierarchy.
- C2.1 to C2.2: colour system and colour roles.
- Critique: present your work to the group.
- S1.1 to S1.4: agree shared system names, foundations and tokens.
- F1.1 to F1.3: Gestalt why session, IRCTC teardown, daily drill.

## 2. Why We Are Doing It

A working product designer in India often gets a short client brief and a real service to study. You must turn the brief into a clear problem before you draw screens. You must also judge public pages with known rules, not opinion. This week builds that habit.

For the project, this week gives you the problem statement, audit findings, type scale, spacing scale and colour system you will use in week 2 and later. For your portfolio, these files show how you think before you design. That is a strong signal.

## 3. What to Learn First

By the end of the week you can:
- Turn an unclear client request into a clear problem statement. Add one number you can measure.
- Check a public service. Name what is wrong using known usability rules, not opinion.
- Build a type scale (font sizes), a spacing scale (gaps), and a colour ramp (shades of one colour). Say why each step exists.
- Make hierarchy (what the eye sees first) work in greyscale (black, white and grey). Use no colour.

Core ideas to review first:
- A problem statement names a user, a job, a problem and two costs. It does not name a screen.
- A usability heuristic is a known rule about how people use interfaces.
- WCAG 2.2 AA is an accessibility standard. You need the main points, not memory work.
- A type scale is a short list of font sizes. You choose it once and reuse it.
- A spacing scale is a short list of gap values. You reuse it on every screen.
- A colour ramp is a set of steps of one colour, from light to dark.
- A token is a stored design value with a name, such as `space-4`.
- Greyscale shows if hierarchy is real. If it only works in colour, the screen is not clear.

## 4. Where to Find Resources

Your week in order:

| Step | Source | What exactly | Time |
|---|---|---|---:|
| 1 | Refactoring UI | Ch. 1 "Starting from Scratch", Ch. 2 "Hierarchy is Everything" | 45 min |
| 1 | Figma Learn | "Auto layout" lesson | 20 min |
| 1 | Figma Learn | "Components and instances" lesson | 15 min |
| 1 | The live service | Open https://www.keralapsc.gov.in/ on your phone. Read the home page in English. Switch to Malayalam and look again. Find Notifications. Find Tips to Applicants. Look at One Time Registration. Do not register, log in, apply or submit. | 10 min |
| 2 | NNGroup | "10 Usability Heuristics for User Interface Design". Read the main article and each rule. | 30 min |
| 2 | WCAG 2.2 Quick Reference | Filter for Level AA only. Read Perceivable and Operable. Do not memorise. | 30 min |
| 2 | axe DevTools | Install it. Run it once on any website. Read the output. | 15 min |
| 2 | Refactoring UI | Ch. 2 again, the part on making things less loud. | 15 min |
| 3 | Practical Typography | "Summary of key rules", then "Type composition": point size, line spacing, line length | 30 min |
| 3 | Refactoring UI | Ch. 4 "Designing Text": type scale, line length, line height | 25 min |
| 3 | Refactoring UI | Ch. 3 "Layout and Spacing": too much white space, spacing and sizing system | 15 min |
| 3 | typescale.com | Try three ratios on the same base size. Watch the top of the scale. | 20 min |
| 4 | Refactoring UI | Ch. 5 colour chapter. Choose colours before screens. Do not let lightness kill saturation. Greys do not have to be grey. | 40 min |
| 4 | Leonardo | https://leonardocolor.io/ Read the intro, build one ramp. Watch contrast numbers change. | 25 min |
| 4 | WCAG 1.4.1 | Open https://www.w3.org/WAI/WCAG22/quickref/ , filter Level AA, read 1.4.1 and failure examples. | 15 min |
| 4 | Material 3 | Colour roles page: https://m3.material.io/styles/color/roles . Look at role names, not colour names. | 10 min |
| 5 | Refactoring UI | Ch. 6 "Creating Depth" and "Avoid ambiguous spacing" in ch. 3 | 40 min |
| 5 | Refactoring UI | Ch. 2 "Size isn't everything" and "Balance weight and contrast". Use greyscale as the test. | 20 min |
| 6 | S1 cohort session | Shared system session | 90 min |
| 6 | F1 | Why session and teardown | 90 min |

What you need from these sources:
- Refactoring UI chapters 1 and 2: start with one feature. Keep choices few. Hierarchy comes from size, weight and colour. Do not change all three at once. Small and quiet can work as well as big.
- Heuristics: learn the name of each rule and one sentence on what it costs the user when broken. "Visibility of system status" is why a person taps a button four times when nothing seems to happen.
- Type scale: a short list of font sizes you use again and again. You choose it once. Speed and consistency matter, not beauty.
- Colour: you need more greys than you think, about nine or ten. You need fewer accent colours than you think. Choose a colour for a job, such as "error text", not for a hue.

Tools you open:
- Figma free Starter plan is your main tool. Open it in the browser on Mac or Windows. Setup: `../04-Tools-Setup.md` (Figma setup section). Starter allows 3 files. Use one file per sprint, with one page per week. Use Penpot when the 3-file limit blocks you. This week use ONE Figma file named `SPRINT-1 UX{n}`, page `Week 1`. Penpot is free and open source, in the browser. Setup: `../04-Tools-Setup.md` (Penpot setup section). Check the free plan before use.
- A browser for Kerala PSC, Leonardo, WebAIM, NN/g, WCAG, typescale, Practical Typography and Material 3.
- axe DevTools and a screen reader when R1.3 starts. Setup: `../04-Tools-Setup.md` (accessibility tools section).
- VS Code and Git are not needed this week.

Where Figma is named in this file, a view-only Penpot link is also allowed.

Search keywords when stuck:
- usability heuristics government website
- WCAG 2.2 AA keyboard focus contrast
- type scale Malayalam line height
- colour ramp contrast ratio
- token naming design system
- Gestalt proximity common region

## 5. Step-by-Step Guide

> All `students/...` paths in this week are inside your sprint folder (`Design-Sprint-N/`). Open a terminal in the repo root and use full paths.

Work in your fork on a branch. One task, one commit with all files listed for that task. See `../10-GitHub-For-Designers.md`.

### Group 1 - Reframe the brief

#### Task - Find what the brief does not answer (ID `P1.1`)

##### 1. What We Are Doing
Read the client brief and find the questions it does not answer. At the end you have three questions on paper.

##### 2. Why We Are Doing It
The brief is one short sentence, so it leaves a lot out. If we guess the missing parts, we may design the wrong thing. Real teams ask first and build later.

##### 3. What to Learn First
Nothing from Refactoring UI here. This task comes from reading the brief slowly. Use `08-glossary.md` in the sprint folder for any word you do not know.

##### 4. Where to Find Resources
- `01-project-brief.md`, sections 1 to 4. Look for the client sentence, the three users and the limits. The client is made up. The website you study is real.
- https://www.keralapsc.gov.in/tips-applicants - the real service's advice page. Read what it tells a candidate to do.

> **Where to start (Kerala PSC public pages):** Open https://www.keralapsc.gov.in/ on a phone. Look at the menu items: Home, About us, Downloads, Recruitment, Results, Must Know, Contact. Use the English/Malayalam switch. Look at Notifications, One Time Registration (it links to the Thulasi portal), and Tips to Applicants. In R1.1 you will save dated screenshots as a fixed record. If the site changes, note the date and keep working from your screenshots. Never log in, register, apply or submit.

##### 5. Step-by-Step Guide
How to think about it:
- Does the brief say who is applying, or only "people"?
- Does it say what goes wrong, and how often?
- If someone answered this question, would you draw a different screen?

1. Read `01-project-brief.md` sections 1 to 4 again. Underline every sentence that gives a fact.
2. Write the client's sentence in your own words. It is: "Make applying simple, so we get fewer wrong applications and fewer calls to the office."
3. Ask four things of the brief. Who exactly is applying? Why do applications go wrong? How many go wrong? What will the client call success?
4. Write which of the four the brief answers, and which it does not.
5. Pick the three gaps that would most change your design if you had the answer.
6. For each gap write three lines: the question, who could answer it, and how long the answer would take.

Worked example, for a different brief, "make our returns process better": ask what share of returns are because the item was wrong, who can answer it, how long it takes, and why it changes the design. If most returns are "wrong item", the fix sits on the product page, not in the returns flow.

Common mistakes:
- The question is really a solution. "Should we add a progress bar?" is a solution. Ask what the candidate does not know.
- "Everyone" is given as the user. Name a real person, for example a first-time applicant.
- No time estimate. Write "one hour" or "two weeks". Say it is a guess if it is a guess.

If you get stuck: read `01-project-brief.md` sections 1 to 4 again. Search "problem statement vs solution". Ask in Discord with a screenshot of your question and what you tried.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/P1-1-brief-questions.md`
- [ ] Done when: three questions, each one the brief genuinely does not answer
- [ ] Done when: each has a named person or source who could answer it
- [ ] Done when: each has a realistic time estimate
- [ ] Done when: each has one line on why the answer would change your design
- [ ] Commit message: `P1.1: add three brief questions`

#### Task - Rewrite the brief as a problem statement (ID `P1.2`)

##### 1. What We Are Doing
Turn the client's short brief into one clear problem statement. It is one short paragraph.

##### 2. Why We Are Doing It
One clear statement keeps the whole team on the same problem. Without it, each designer builds a different thing. It also helps you say no to extra ideas.

##### 3. What to Learn First
Read the three users in `01-project-brief.md` section 4. Look up "problem statement" and "failure mode" in `08-glossary.md`.

##### 4. Where to Find Resources
- `01-project-brief.md` section 4. Look at the failure mode of Anjali, Suresh and Meera.
- https://www.keralapsc.gov.in/tips-applicants - read one warning the service gives candidates. Think about the cost of getting it wrong.

##### 5. Step-by-Step Guide
How to think about it:
- Which user fails most often? Choose that one, not the saddest story.
- Is your sentence about a rule or about a screen? A rule is a problem. A screen is a solution.
- Would a person at the Commission agree your sentence is true?

1. Use exactly this shape: `[user] cannot [job] because [problem], which costs [cost to user] and [cost to the client].`
2. Choose the user whose failure is most common. Do not choose the most dramatic one.
3. Fill the shape with plain words.
4. Check for solution words: redesign, simplify, add, app, button, screen. Remove every one.
5. Keep it to one paragraph of two or three sentences.

Worked example, for a driving licence renewal: a licence holder who has moved to another city cannot renew online, because the rule says the renewal must be filed at the office that issued the first licence. This costs the person a day of travel. It costs the department a counter appointment that gives no new information. It names the user, the job, the rule, and both costs. It gives no solution.

Common mistakes:
- The sentence names a screen. Say the rule instead.
- Only one cost is written. Give a cost for the person and a cost for the client.
- The user is "everyone". Pick one user from the brief.
- A fix hides in the wording. Say what the person cannot finish.

If you get stuck: read section 4 again. Search "problem statement user cost client cost". Ask in Discord with your sentence and the words you removed.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/P1-2-problem-statement.md`
- [ ] Done when: follows the shape exactly
- [ ] Done when: zero solution words
- [ ] Done when: both costs stated, one for the user and one for the client
- [ ] Done when: someone from the client team would agree it is accurate
- [ ] Commit message: `P1.2: add problem statement`

### Group 2 - Public service audit

#### Task - Capture the current public pages (ID `R1.1`)

##### 1. What We Are Doing
Take screenshots of the public Kerala PSC pages. Keep them in one folder, in order, with a short note for each.

##### 2. Why We Are Doing It
You cannot judge a service you have not looked at. Screenshots also let you and your team talk about the same screen later. In a real job, this folder is the proof of what you studied.

##### 3. What to Learn First
Open keralapsc.gov.in on your phone, in English and then in Malayalam. Find the Notifications page and the Tips to Applicants page. Look at the One Time Registration page. Do not register, log in, apply or submit anything in this task.

##### 4. Where to Find Resources
- Home page: https://www.keralapsc.gov.in/
- Notifications: https://www.keralapsc.gov.in/notifications
- Tips to Applicants: https://www.keralapsc.gov.in/tips-applicants
- OTR Instructions, the "How to Apply" page: https://www.keralapsc.gov.in/otr-instructions-candidates
- Confirmation procedures: https://www.keralapsc.gov.in/confirmation-procedures
- Thulasi portal public page: https://thulasi.psc.kerala.gov.in/thulasi/
- New-registration PDF: https://www.keralapsc.gov.in/sites/default/files/inline-files/otr.pdf
- Confirmation PDF: https://www.keralapsc.gov.in/sites/default/files/inline-files/confirmation_0.pdf

> **Where to start (Kerala PSC public pages):** The brief checked https://www.keralapsc.gov.in/ on 21 Oct 2026. Look at the menu items: Home, About us, Downloads, Recruitment, Results, Must Know, Contact. Use the English/Malayalam switch. Look at Notifications, One Time Registration (it links to the Thulasi portal), and Tips to Applicants. Save dated screenshots here. Treat them as your fixed record. If the site changes, note the date and keep working from your screenshots. Never log in, register, apply or submit.

##### 5. Step-by-Step Guide
How to think about it:
- Ask: "Can a person who is in a hurry find this page?"
- Ask: "Is this page written for a candidate, or for the office?"
- If a page is confusing, write the question you wanted to ask. Do not guess the answer.

1. Open the home page on your phone.
2. Take one screenshot.
3. Switch the language to Malayalam.
4. Take one screenshot.
5. Switch back to English if you want.
6. Open Notifications.
7. Pick two posts.
8. Screenshot both posts.
9. Write the category number of each post, for example `Cat.No.812/2025`.
10. Open Tips to Applicants.
11. Screenshot it.
12. Open OTR Instructions.
13. Screenshot it.
14. Open Confirmation procedures.
15. Screenshot the page.
16. Open the first page of its PDF and screenshot it.
17. Open the Thulasi public page. Look only. Do not log in.
18. Screenshot it.
19. Open the new-registration PDF.
20. Screenshot the first two pages.
21. Write a file called `gaps.md`.
22. List every screen you could not reach.
23. Add one line on why for each one.
24. Name the files in order, like this: `01-home.png`, `02-home-malayalam.png`, `03-notifications.png`.
25. Write a `README.md`.
26. Give each file one line on what the screen is for.

Verify yourself: the two photo rules on the site may disagree. Note where you saw each one, and write "not settled" if you cannot decide.

Worked example: a student cannot open the login-only pages. She does not invent them. She writes in `gaps.md`: "Login-only screens: not reachable. I do not have an account and I will not log in. I will use the public pages I captured." That is a correct result, not a failure.

Common mistakes:
- Creating an account to "see more". This breaks the safety rules. Use the gaps list instead.
- Leaving a User ID or a phone number in a screenshot. Redact it before you save the file.
- Screenshots with no order and no names.
- Writing "looks bad" with no note. Say what the screen was meant to do.

If you get stuck: re-open the public page in a private window. Search "screenshot redact personal data". Ask in Discord with the page name and what you could not reach.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/R1-1-current-flow-screens/`
- [ ] Save images as PNG or JPG under 2 MB. Redact personal data.
- [ ] Done when: every public page you reached is captured, in order
- [ ] Done when: the home page is captured in English and in Malayalam
- [ ] Done when: two notification pages are captured, with their category numbers written down
- [ ] Done when: `gaps.md` lists at least 4 screens or questions you could not reach or answer
- [ ] Done when: a `README.md` lists each file with one line on its purpose
- [ ] Done when: no screenshot shows a User ID, name, date of birth, photo, phone number or email
- [ ] Commit message: `R1.1: add dated screenshots and gaps list`

#### Task - Heuristic evaluation (ID `R1.2`)

##### 1. What We Are Doing
Look at your screenshots and find problems. For each problem, name the rule it breaks and say how bad it is.

##### 2. Why We Are Doing It
"It feels wrong" cannot be fixed. A named rule and a severity give the team something to act on. Clients pay for this list.

##### 3. What to Learn First
Use the 10 heuristics from today's LEARN block. A heuristic is a known usability rule.

##### 4. Where to Find Resources
- 10 Usability Heuristics: https://www.nngroup.com/articles/ten-usability-heuristics/
- Your own `students/UX{n}/week1/R1-1-current-flow-screens/` folder
- The two official PDFs listed in R1.1

##### 5. Step-by-Step Guide
How to think about it:
- Ask: "What does the person try to do on this screen?"
- Ask: "What stops them, and what does it cost them?"
- One finding, one rule. If two rules apply, pick the one with the bigger cost.

1. Open your screenshots one at a time.
2. Write one row per problem. Use four columns: screen, rule broken, what the person experiences, severity.
3. Use this severity scale: 1 cosmetic, 2 minor, they work around it, 3 major, they fail the task, 4 catastrophic, they lose data or a chance.
4. Aim for 12 findings or more. A table is fine.
5. Your findings come from the public pages and the two official PDFs. Say which one each finding came from.

Worked example from a different government portal:
- Payment confirmation: Visibility of system status. After tapping Pay, nothing changes for 9 seconds. No spinner, no disabled button. The user taps Pay a second time and is charged twice. Severity 4.
- Document upload: Help users recognise, diagnose and recover from errors. The error reads "ERR_UPLOAD_422". No file size is mentioned, and the real limit is never shown. Severity 3.

Not a finding: "looks outdated", "the colours are ugly", "not modern". These have no user cost.

Common mistakes:
- Naming a rule twice in one row. Pick the rule that costs the most.
- Writing "confusing" with no detail. Say what the person sees and does next.
- Giving severity 4 to a small thing. Save 4 for lost data or a lost chance.

If you get stuck: read the 10 rule definitions again. Search "usability heuristic severity rating". Ask in Discord with one row and the cost you see.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/R1-2-heuristic-audit.md`
- [ ] Done when: 12 or more findings
- [ ] Done when: every finding names one of the 10 heuristics
- [ ] Done when: every "what the user experiences" describes behaviour, not looks
- [ ] Done when: every severity 3 or 4 has the cost spelled out
- [ ] Done when: every finding says where it came from: public page or PDF
- [ ] Commit message: `R1.2: add heuristic audit`

#### Task - Accessibility audit (ID `R1.3`)

##### 1. What We Are Doing
Run seven checks on the public pages. Each check gets a pass or a fail, and proof.

##### 2. Why We Are Doing It
Many candidates use a screen reader, a magnifier, or only one hand. If the page fails them, they cannot apply at all. Public services in India are expected to be accessible, so this is part of the job.

##### 3. What to Learn First
Skim the WCAG AA criteria. You do not need all of them. You need the seven checks below. WCAG is an accessibility standard.

Tool setup: axe DevTools and a screen reader first appear here. See `../04-Tools-Setup.md` (accessibility tools section).

##### 4. Where to Find Resources
- WCAG 2.2 quick reference: https://www.w3.org/WAI/WCAG22/quickref/
- WebAIM contrast checker: https://webaim.org/resources/contrastchecker/
- axe DevTools: https://www.deque.com/axe/devtools/
- VoiceOver on Mac: https://support.apple.com/guide/voiceover/welcome/mac
- NVDA for Windows: https://www.nvaccess.org/download/
- TalkBack on Android: https://support.google.com/accessibility/android/answer/6283677
- The confirmation PDF and the new-registration PDF from R1.1

##### 5. Step-by-Step Guide
How to think about it:
- Ask: "Could I finish this task with my eyes closed, or with a magnifier?"
- Ask: "Can I tell what went wrong without seeing colour?"
- Use the public pages and the public login page only. Look, do not log in.

1. Install axe DevTools in Chrome. Mac: open Chrome. Windows: open Chrome. Open the browser extensions store, search for axe DevTools, and add it. Check before use.
2. Keyboard only. Do not touch the mouse. Use Tab, Shift+Tab, Enter and Space to work through the public pages. Write where you get stuck. WCAG 2.1.1.
3. Focus visible. Press Tab and stop at each item. Write down every item where you cannot see which thing is focused. WCAG 2.4.7.
4. Contrast. Pick 5 text elements.
5. Measure each one with axe DevTools or the WebAIM checker. Body text needs 4.5:1. Large text needs 3:1. WCAG 1.4.3.
6. Form labels. On the public login page, check that each field has a real label, not only placeholder text. Turn on your screen reader and listen to one field. WCAG 1.3.1, 4.1.2. Mac: turn on VoiceOver with Cmd+F5. Windows: install and open NVDA from https://www.nvaccess.org/.
7. Target size. Find the smallest tappable thing. Under 24 × 24 px fails. WCAG 2.5.8.
8. Colour alone. Find anything where colour is the only signal, like a red border with no text. WCAG 1.4.1.
9. PDF accessibility. Open one official instruction PDF. Try to select and copy the Malayalam text. Then open it with VoiceOver or NVDA. Write what happens. WCAG 1.3.1, 4.1.2.

Worked example:
- Keyboard only: Fail. The date picker cannot be opened with Enter or Space, only with a click. 2.1.1 Keyboard. Evidence: tabbed to the field, pressed Enter and Space, nothing opened.
- Contrast, hint text: Fail. #9A9A9A on #FFFFFF = 2.85:1, needs 4.5:1. 1.4.3 Contrast (Minimum). Evidence: WebAIM checker screenshot.
- PDF accessibility: Fail. Copied text comes out as garbage characters, not Malayalam. 1.3.1, 4.1.2. Evidence: pasted the copied text into a note and saved a screenshot.

Common mistakes:
- Using the mouse "just once". Then the keyboard result is not true.
- Saying "contrast is bad" with no numbers. Give the ratio.
- Skipping the PDF check because it looks hard. It takes two minutes.
- Logging in to test a field. Look at the login page only.

If you get stuck: read one WCAG criterion at a time. Search "WCAG 2.2 keyboard focus visible". Ask in Discord with a screenshot of the check and what you tried.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/R1-3-accessibility-audit.md`
- [ ] Done when: all seven checks are done, each with pass or fail
- [ ] Done when: every failure names its WCAG criterion number
- [ ] Done when: every failure has proof: a measurement, a screenshot, or what the screen reader said
- [ ] Done when: the keyboard-only attempt is described, including where you gave up
- [ ] Done when: the PDF result says whether the Malayalam text could be copied and read aloud
- [ ] Commit message: `R1.3: add accessibility audit`

### Group 3 - Type and spacing

#### Task - Build a type scale (ID `C1.1`)

##### 1. What We Are Doing
Build one short list of font sizes. You will use this list for every screen in the sprint.

##### 2. Why We Are Doing It
In a real team, several designers can pick different sizes. The screens then look messy and the work gets slower. One agreed list keeps every screen the same.

##### 3. What to Learn First
Read Refactoring UI ch. 4, "Establish a type scale". Read Practical Typography on point size and line spacing.

Short lesson: create and apply text styles. Do this before you build the scale.
- Figma: open your `SPRINT-1 UX{n}` file on the `Week 1` page. Select a text layer. In the right panel, use the style menu to create a text style. Give it a name, for example `body`. To apply it, select another text layer and pick the same style from the menu. Menu names change, so check the Figma help pages before use.
- Penpot: select a text layer. In the right panel, save its type values as a typography asset. Give it the same name. Apply it to another text layer from the assets panel. Check the Penpot help pages before use.
- Check it worked: change the size inside your `body` style. Every layer that uses `body` must change with it.

Tool setup: Figma first appears here as your working canvas. See `../04-Tools-Setup.md` (Figma setup section). Use ONE Figma file per sprint named `SPRINT-1 UX{n}`, one page per week. This week use page `Week 1`. Starter allows 3 files. Use one file per sprint, with one page per week. If the 3-file limit blocks you, use Penpot. See `../04-Tools-Setup.md` (Penpot setup section). Check the free plan before use.

##### 4. Where to Find Resources
- Refactoring UI chapter 4, "Establish a type scale". The book is in the repo folder `Resources/`.
- https://practicaltypography.com/ - read the summary of key rules first.
- https://typescale.com/ - this free tool makes the steps for you.
- Noto Sans Malayalam: https://fonts.google.com/noto/specimen/Noto+Sans+Malayalam

##### 5. Step-by-Step Guide
How to think about it:
- Can someone read this size on a cheap phone, in bright light?
- Does every step have a job? If not, why keep it?
- Do the tall Malayalam letters still fit inside the line?

1. Pick your base body size. 16px is the smallest for a government service on cheap phones. 17px or 18px is safer.
2. Pick a ratio, the step between one size and the next. 1.2 is calm. 1.25 is a good default. 1.333 grows fast.
3. Make the steps at https://typescale.com/. Round every value to a whole pixel. Never use 17.36px.
4. Give every step a name and a use. Delete any step with no use.
5. Set a line height for each step. Tight for big text, 1.1 to 1.2. Looser for body text, 1.5 to 1.6.
6. Malayalam test. Type `അപേക്ഷ സമർപ്പിക്കുക` at every step. Malayalam has joined letters and tall parts above and below the line. Write down every step where the text is cut off or crowded.

Worked example: base 17px, ratio 1.25, rounded. body-sm 14px, line height 1.5 (21px), hint text. body 17px, line height 1.55 (26px), form labels and paragraph text. h3 21px, line height 1.4 (29px), section headings. h2 27px, line height 1.3 (35px), screen title. h1 33px, line height 1.2 (40px), not used in this flow. Malayalam test: at body-sm 14px/21px the joined letters crowded the line above. Raise body-sm line height to 1.65 (23px) for Malayalam. Mark it as a mode, not a global change.

Common mistakes:
- Picking sizes by eye, then finding a ratio that fits them. Fix: pick the ratio first.
- Keeping a step you never use. Fix: delete it.
- Raising the line height of every step to hide clipping. Fix: change only the steps that need it.
- Leaving decimals in the sizes. Fix: round to whole pixels.

If you get stuck: read the type scale section in Refactoring UI again. Search "modular scale line height Malayalam". Ask in Discord with your base size and one screenshot of the Malayalam test.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/C1-1-type-scale.md`
- [ ] Put a view-only link from your chosen tool (Figma or Penpot) inside the markdown file.
- [ ] Done when: base size stated with a reason tied to this audience
- [ ] Done when: ratio stated with a reason
- [ ] Done when: every step has a whole-pixel size, a line height, and a named use
- [ ] Done when: any step with no use has been deleted
- [ ] Done when: Malayalam tested at every step, with what broke and what you changed
- [ ] Done when: view-only link included, with the scale built as text styles (Figma text styles, or Penpot typography assets)
- [ ] Commit message: `C1.1: add type scale`

#### Task - Build a spacing scale (ID `C1.2`)

##### 1. What We Are Doing
Build one short list of space values. You will use it for padding and gaps on every screen.

##### 2. Why We Are Doing It
Without a list, every gap is a new guess. The work slows down and the screens stop matching. A fixed list makes the next screens quick to build.

##### 3. What to Learn First
Read Refactoring UI ch. 3, "Start with too much white space" and "Establish a spacing and sizing system".

##### 4. Where to Find Resources
- Refactoring UI ch. 3, "Start with too much white space" and "Establish a spacing and sizing system".
- Your own C1.1 file, to see how you wrote the scale down.

##### 5. Step-by-Step Guide
How to think about it:
- Do two neighbouring steps look clearly different?
- Is this gap about grouping, or about separating a big decision?
- Would this gap still work on a 390px phone?

1. Pick a base unit. 4px or 8px. 8px means fewer decisions. 4px gives finer control on small screens.
2. Build the steps. Do not make them even. `4, 8, 12, 16, 24, 32, 48, 64` works better than `4, 8, 12, 16, 20, 24, 28`, because neighbouring steps must look different.
3. Pick three steps. Name one real place in this flow where each one is correct.

Worked example: base 4px. Steps: 4, 8, 12, 16, 24, 32, 48, 64.
- 8px: gap between a line of photograph rules and the line under it. Small enough that they read as one block, Gestalt proximity.
- 24px: gap between two groups of details on the check-your-answers screen. Big enough to show they are separate groups.
- 48px: space above the Submit button. It separates "checking your details" from "committing", which is a different kind of decision.

Common mistakes:
- Making every step evenly spaced. Fix: keep neighbouring steps clearly different.
- Using a new gap for every screen. Fix: reuse a step from the list.
- Putting lots of space before Submit and none before Cancel. Fix: group the two buttons with a smaller gap.

If you get stuck: read the spacing section again. Search "spacing scale 4px 8px". Ask in Discord with your step list and one screen place.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/C1-2-spacing-scale.md`
- [ ] Done when: base unit stated with a reason
- [ ] Done when: full step list, not evenly spaced at the top end
- [ ] Done when: three steps each mapped to a real place in this flow, with the reason
- [ ] Commit message: `C1.2: add spacing scale`

#### Task - Measure test (ID `C1.3`)

##### 1. What We Are Doing
Set one real paragraph at three widths. Then choose the best width for reading.

##### 2. Why We Are Doing It
A line that is too long makes the eye lose its place. A line that is too short makes the eye jump back too often. Both slow the reader down. A real job needs a stated number, not a feeling.

##### 3. What to Learn First
Read Practical Typography on line length. It says 45 to 90 characters per line. 60 to 70 is comfortable.

##### 4. Where to Find Resources
- https://practicaltypography.com/ - the part on line length.
- https://www.keralapsc.gov.in/tips-applicants - the page you will copy your paragraph from.

##### 5. Step-by-Step Guide
How to think about it:
- What does my eye do at the end of each line?
- Would this still work on a phone held in one hand?
- Can I say the width as a number, not as "it looks better"?

1. Open https://www.keralapsc.gov.in/tips-applicants and copy one real paragraph. A paragraph about the photograph or about the final submit works well. Copy and paste it yourself.
2. Set the paragraph three times at your `body` size, at three widths: about 30 characters, about 65, about 110.
3. Screenshot all three.
4. Read each one out loud. Note what your eye does at the end of each line.
5. Say which one works, using characters per line and reading behaviour. Do not write "it looks better".

Worked example: a student set a paragraph from a bus booking site at three widths.
- 30 characters: the eye jumped back on almost every line. Reading felt choppy.
- 65 characters: smooth. The eye found the next line easily.
- 110 characters: the eye often landed on the wrong line.
The student chose 65 characters and wrote "max width 640px at body 17px" for the rest of the sprint. The choice is written as a number.

Common mistakes:
- Choosing a width because it fills your laptop screen. Fix: think about a 390px phone first.
- Counting characters on one line only. Fix: count two or three lines and take the middle number.
- Retyping the paragraph by hand. Fix: copy and paste, so the words stay exact.

If you get stuck: read the line length part again. Search "characters per line 65". Ask in Discord with your three screenshots and the character counts.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/C1-3-measure-test.md`
- [ ] Done when: three screenshots at three stated widths
- [ ] Done when: character count per line stated for each
- [ ] Done when: your choice justified by reading behaviour, with the source named
- [ ] Done when: the chosen max width recorded as a number you will use for the rest of the sprint
- [ ] Done when: the paragraph comes from the Tips to Applicants page, and its link is written next to it
- [ ] Commit message: `C1.3: add measure test`

### Group 4 - Colour system

#### Task - Build the colour system (ID `C2.1`)

##### 1. What We Are Doing
Build the full colour set for the Kerala PSC application redesign. At the end you have one file with every colour, its step number, and its contrast numbers.

##### 2. Why We Are Doing It
Colour is where beginners make small mistakes. A light grey looks fine on a big laptop and fails on a phone in sunlight. If you fix the colours now, week 2 and week 3 go fast. You will not check the same grey five times.

##### 3. What to Learn First
Read Refactoring UI ch. 5 for the ideas. Use Leonardo for generating the ramps and reading the contrast numbers.

##### 4. Where to Find Resources
- Refactoring UI, chapter 5. The book is in the repo folder `Resources/`.
- Leonardo colour tool: https://leonardocolor.io/ - generate each ramp and read the contrast numbers.
- WebAIM contrast checker: https://webaim.org/resources/contrastchecker/ - paste two hex values and read the ratio. A hex value is a colour code such as `#6B7280`.
- WCAG 2.2 quick reference: https://www.w3.org/WAI/WCAG22/quickref/ - find Level AA rules 1.4.3 and 1.4.11.

##### 5. Step-by-Step Guide
How to think about it:
- Would this grey still be easy to read on a cheap phone, outdoors?
- Is this colour chosen for its job, or only because it looks nice?
- Can you say the job of each colour in three words?
- If your client changes one colour later, how much work is that?

1. Neutral ramp, 10 steps. Build a neutral ramp, greys from near-white to near-black. Use Leonardo so the steps look even to the eye, not just even in numbers. Number them 50, 100, 200 and so on, up to 900.
2. Primary ramp. Choose one strong colour and make 10 steps, the same way. If the client gives you a brand colour, use it and write down where it came from. If not, choose one and say why.
3. Semantic colours. Build success, warning, error and information colours. These are colours that carry a meaning. Each one needs a text value and a surface value, because error text on white and an error background need different lightness. Your error colour will sit under the photograph upload field. Your disabled colour will sit on the Submit button.
4. Check contrast for every step. Record each colour's ratio against white and against your darkest neutral. Mark which steps pass 4.5:1 and which pass 3:1.
5. Do not skip step 4. Use this record to shortlist colours; check every actual text/background pair and component state.

Worked example, three rows of a neutral ramp. This is an example set of values, not a rule.
- neutral-500 #6B7280. vs white 4.83:1. vs neutral-900 3.11:1. Passes AA body text on white.
- neutral-400 #9CA3AF. vs white 2.85:1. vs neutral-900 5.27:1. Fails both body and large text on white.
- neutral-200 #E5E7EB. vs white 1.22:1. vs neutral-900 12.3:1. Borders and surfaces only. Never text.

Common mistakes:
- Using many accent colours. Fix: one accent, plus the four meaning colours.
- Using a soft grey for body text because it looks calm. Fix: body text needs 4.5:1.
- Building the ramps and skipping the contrast record. Fix: record as you build, one row at a time.
- Writing "it looks fine" instead of a number. Fix: a number or nothing.

If you get stuck: read the colour chapter again. Search "colour ramp contrast ratio 4.5". Ask in Discord with one ramp and the contrast number you cannot read.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/C2-1-colour-system.md`
- [ ] Done when: 10-step neutral ramp, even to the eye, with the method stated
- [ ] Done when: primary ramp, with its source written down
- [ ] Done when: four meaning colours, each with a text and a surface value
- [ ] Done when: every step has both contrast ratios recorded
- [ ] Done when: every step is marked with what it may be used for
- [ ] Commit message: `C2.1: add colour system`

#### Task - Map colours to roles (ID `C2.2`)

##### 1. What We Are Doing
Give every colour a job name, called a role. A role is a name for a colour value, such as `color.text.primary`. Your screens will use the role name, never the raw hex.

##### 2. Why We Are Doing It
Raw hex codes spread through a file and become hard to change. A role is written once and used everywhere. This mapping becomes your token file in S1.3. It also makes a dark version possible in week 4 without redesigning anything.

##### 3. What to Learn First
Read the Material 3 colour roles page. It shows how a role name describes a job, such as "surface" or "text on surface".

##### 4. Where to Find Resources
- Material 3 colour roles: https://m3.material.io/styles/color/roles - look at role names and how they pair a text colour with a background.
- WebAIM contrast checker: https://webaim.org/resources/contrastchecker/ - use it for each text and background pair.
- Refactoring UI, chapter 5, for when two greys are too close to tell apart.

##### 5. Step-by-Step Guide
How to think about it:
- Could a new person on the team use this name without asking you?
- Does every text role have a background role that it always sits on?
- Is your focus ring easy to see on the page and on a button?
- Which role has no good colour yet?

1. Fill in every role below with a token from C2.1, never a raw hex.
2. Roles: page background, surface, surface raised, border default, border strong, text primary, text secondary, text disabled, interactive default, interactive hover, interactive pressed, interactive disabled, focus ring, error text, error surface, error border, success text, success surface.
3. For every text role, confirm the contrast against the background role it sits on.
4. Put your roles on the real places in this flow. Check the error text under the photograph upload field. Check the disabled Submit button. Check the focus ring on the "Apply Now" button.
5. If a role has no token that works, say so. That is a finding, not a failure.

Worked example, a small role map from a different product, a food delivery app:
- error text: red-700. 5.1:1 on neutral-50.
- page background: neutral-50. The lightest step, used on every screen.
- focus ring: blue-600. 3.4:1 against the page and against white.
Notice that nothing here says "red" in the role name. The name says the job. If the brand changes to purple, you change one value and the name stays.

Common mistakes:
- Writing hex codes in the role table. Fix: a token name, then the hex in C2.1 only.
- Skipping the focus ring because it is hard to see in a static file. Fix: test it on a real button.
- Forgetting that disabled text still has to be readable enough to know it is text. Fix: record its ratio and write the limit.
- Hiding a role that does not work. Fix: name it as a gap.

If you get stuck: read the role page again. Search "semantic colour roles focus ring". Ask in Discord with one role and its contrast pair.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/C2-2-semantic-roles.md`
- [ ] Done when: every role has a token, not a hex
- [ ] Done when: every text role has its contrast against its own background confirmed
- [ ] Done when: focus ring is included and passes 3:1 against both the component and the background
- [ ] Done when: any role you could not fill is named as a gap
- [ ] Commit message: `C2.2: add semantic colour roles`

#### Task - Group critique (ID `Critique`)

##### 1. What We Are Doing
Present your work to the group for 12 minutes and take questions. Then log what you heard. Present in this order: your problem statement, your three worst audit findings, then your type and colour scales.

##### 2. Why We Are Doing It
You cannot see your own gaps after a week of work. A new person finds them in two minutes. The log is what you carry into week 2.

##### 3. What to Learn First
Read `07-critique-guide.md` in the sprint folder. It gives the questions to ask and the order to follow.

##### 4. Where to Find Resources
- `07-critique-guide.md` in the sprint folder.

##### 5. Step-by-Step Guide
How to think about it:
- Can you say your problem statement in one breath, without reading it?
- Do your three findings show a pattern, or are they three random things?
- Would a person who was not in the room follow your colour choices?

1. Present in the order above. Keep to 12 minutes.
2. Take questions. Write down at least three notes from others.
3. For each note, write what you will change, or why you will not.
4. Give one substantive comment to two other designers.

If you get stuck: read `07-critique-guide.md` again. Ask in Discord for the critique order. Send your problem statement and one finding.

##### 6. What to Commit
- [ ] Path: `Design-Sprint-1/students/UX{n}/week1/critique-log.md`, where n is the lead's number
- [ ] Done when: you presented for 12 minutes and kept to the time
- [ ] Done when: at least three notes from others are written down
- [ ] Done when: each note says what you will change, or why you will not
- [ ] Done when: the critique lead filed the log straight after the session
- [ ] Lead commit message: `W1: add group critique log`
- [ ] Students who are not the lead do not commit the shared log. The lead files it.

### Group 5 - Greyscale, constraints, metrics

#### Task - Greyscale hierarchy (ID `C1.4`)

##### 1. What We Are Doing
Rebuild one busy screen using only size, weight, and grey. The screen must still make sense with no colour.

##### 2. Why We Are Doing It
Colour can hide weak hierarchy. If the screen works in grey, the structure is strong. If it only works in colour, the screen is not clear.

##### 3. What to Learn First
Read Refactoring UI ch. 6 "Creating Depth" and ch. 2 "Size isn't everything". Greyscale is the test: if the hierarchy survives without colour, it is real.

##### 4. Where to Find Resources
- Refactoring UI, chapter 6 "Creating Depth" and chapter 2 "Size isn't everything".
- Figma Learn: https://help.figma.com/ - search for "blur" or "effects".
- What to look for: how size, weight, and grey change what you see first.

##### 5. Step-by-Step Guide
How to think about it:
- If I remove all colour, what do I see first?
- Is the most important thing easy to find?
- Is any grey text too light to read?

1. Open your R1.1 screenshots. Pick the busiest screen.
2. Use the busiest public page you captured, such as Notifications. Do not use your own profile screens.
3. Rebuild it in Figma or Penpot. Use only your type scale, spacing scale, and neutral ramp.
4. Do not use brand colour. Do not use colour that carries meaning, such as red for an error.
5. Show importance with size, weight, and grey value only.
6. Blur the screen in your tool, or use the squint test (half close your eyes).
7. Write down the three things you notice first.
8. Put your version next to the original screenshot.
9. Write one short note about what the grey test showed.

Worked example: in a weather app, the temperature is large and bold. The city name is medium. The small facts are grey and smaller. Blur the screen. You still see the temperature first. The size jump is big. The grey text is still dark enough to read.

Common mistakes:
- Using colour to fix a weak layout. Fix the size and weight first.
- Making every grey too light. Check that small text is easy to read.
- Using five font sizes. Use your scale.
- Comparing from memory. Put both screens side by side.

If you get stuck: read the depth chapter again. Search "greyscale hierarchy blur test". Ask in Discord with your blurred screen and the original.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/C1-4-greyscale-hierarchy.md`
- [ ] Put a view-only link from your chosen tool (Figma or Penpot) inside the markdown file.
- [ ] Done when: one screen fully rebuilt, greyscale only
- [ ] Done when: uses only tokens from C1.1, C1.2, C2.1
- [ ] Done when: a written record of the three things you noticed first, and they are the intended three
- [ ] Done when: blurred version included, or the squint test recorded if you used that instead
- [ ] Done when: side by side with the original
- [ ] Done when: view-only link from Figma or Penpot
- [ ] Commit message: `C1.4: add greyscale hierarchy`

#### Task - Constraint list (ID `P1.3`)

##### 1. What We Are Doing
List the rules that limit this project. Sort them by type.

##### 2. Why We Are Doing It
Some limits are policy. You cannot design them away. Some are only technical. They can change. If you mix them, you may work on the wrong thing.

##### 3. What to Learn First
Read the constraints section in `01-project-brief.md`.

##### 4. Where to Find Resources
- `01-project-brief.md`: read the constraints section and the scope section.
- Tips to Applicants: https://www.keralapsc.gov.in/tips-applicants - look for rules about photos, fee, and confirmation.
- Notifications: https://www.keralapsc.gov.in/notifications - look at real post notices.
- Confirmation procedures: https://www.keralapsc.gov.in/confirmation-procedures - it links to a PDF.

##### 5. Step-by-Step Guide
How to think about it:
- Can the Commission change this rule, or is it only how the site is built now?
- Has anyone checked this, or are we guessing?
- Would this stop a real candidate?

1. Open `01-project-brief.md`. Find these five constraints from the brief: a submitted application is provisional and cannot be deleted or altered; photograph rules apply, the photo needs your name and the date at the bottom, the validity period is a rule to check; there is no application fee; exam posts need a separate confirmation, with an OTP, inside a window; the service must work in Malayalam and English.
2. Open the public pages. Add at least three more constraints you found yourself. Use only what you can see or read in official pages and PDFs.
3. Mark each constraint as one of three types. Fixed policy: a rule you cannot change. Technical: current implementation, could change with effort. Assumed: nobody has checked it.
4. For each assumed constraint, write one line on how you would check it. Say where you would look.
5. Pick two assumed constraints to work on in week 2. Write one sentence for each.

Worked example:
- A submitted application is provisional and cannot be deleted or altered. Fixed policy. This is the Commission's rule. We cannot design it away. We can warn before submit.
- Photo date rule: one page says after 31.12.2010. Another notice says within six months. Assumed. The two statements disagree. Check the current notification and the Tips page. Write what you find.
- Confirmation for exam posts uses an OTP. Fixed policy, exact window not checked. The button names are official. The window and exact rule need checking.

Verify yourself: open Tips to Applicants and one recent notification. Write the photo date rule each one shows. If you cannot find it, write "not found".

Common mistakes:
- Calling a technical limit a policy. Ask if it can change.
- Marking something assumed but not saying how to check it.
- Writing vague limits like "slow internet" without a source.
- Missing the rule that submit cannot be undone.

If you get stuck: read the constraints section again. Search "Kerala PSC photo date rule". Ask in Discord with the two pages that disagree.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/P1-3-constraints.md`
- [ ] Done when: five brief constraints listed
- [ ] Done when: at least three more found from public pages
- [ ] Done when: each one marked fixed policy, technical, or assumed
- [ ] Done when: at least two assumed ones have a check plan
- [ ] Done when: two assumed ones chosen for week 2
- [ ] Commit message: `P1.3: add constraint list`

#### Task - Metrics (ID `P1.4`)

##### 1. What We Are Doing
Choose the numbers that show if the redesign works. Say how to measure each one.

##### 2. Why We Are Doing It
A clear number keeps the team honest. It shows if the design helped or only looked good. A guardrail stops us from fixing one problem and causing a worse one.

##### 3. What to Learn First
Read the success measures section in `01-project-brief.md`.

##### 4. Where to Find Resources
- `01-project-brief.md`: read the success measures section.
- Tips to Applicants: https://www.keralapsc.gov.in/tips-applicants - look for the steps a candidate must complete.
- Notifications: https://www.keralapsc.gov.in/notifications - look at the journey from a post to an application.

##### 5. Step-by-Step Guide
How to think about it:
- Will this number move early enough to help us?
- Can we measure it without new work?
- Could a designer make this number look good and still harm candidates?

1. Write the primary metric: application completion rate. It is applications submitted divided by "Apply Now" clicks. Say how you would measure it. Name the two events and the time period.
2. Write two input metrics. They must move before the primary metric. Choose from: photograph upload retry rate; time from "Apply Now" to submit; share of exam-post applicants who complete confirmation before the window closes; contacts to the office about "how do I...".
3. Write one guardrail metric. Wrong or ineligible applications must not rise. Say how you would measure summary rejections and duplicate applications.
4. Write one sentence: your own harmful shortcut, the bad design you would be tempted to make if only the primary metric mattered. Do not copy an example from this file.
5. Add one line: how that shortcut would move your guardrail metric.
6. Name one guardrail you will defend in the design review.

Worked example, for a driving licence renewal. This is an example shape, not a finished answer. Write your own shortcut for your own flow.
- Primary: completed renewals divided by sessions that start.
- Input 1: photo upload success on the first try.
- Input 2: time from start to submit.
- Guardrail: rejected applications.
- An example of a harmful shortcut, from a different task, a food delivery app: if only completed orders mattered, a team could hide the delivery fee until the last screen. More orders get completed. The guardrail, refund complaints, rises. That is the pattern to look for in your own flow.

Common mistakes:
- Choosing a metric you cannot measure. Pick one you can count.
- Writing a vague guardrail. Name the exact bad result.
- Using five input metrics. Two is enough.
- Copying the example shortcut instead of writing your own.

If you get stuck: read the success measures section again. Search "completion rate guardrail metric". Ask in Discord with your primary metric and one input metric.

##### 6. What to Commit
- [ ] Path: `students/UX{n}/week1/P1-4-metrics.md`
- [ ] Done when: primary metric with the exact calculation
- [ ] Done when: two input metrics that move earlier
- [ ] Done when: one guardrail metric
- [ ] Done when: one sentence naming your own harmful shortcut, and its effect on the guardrail metric
- [ ] Done when: one guardrail named for the design review
- [ ] Commit message: `P1.4: add metrics`

### Group 6 - Shared system and fundamentals

#### Task - Agree token naming (ID `S1.1`)

##### 1. What We Are Doing
Write one naming rule for design tokens. A token is a stored design value with a name, such as `space-4` or `colour-danger`. At the end, the team has one naming document.

##### 2. Why We Are Doing It
Five people made five sets of names this week. Different names break the shared library. One clear rule saves hours in week 2 and later.

##### 3. What to Learn First
Read the Figma help pages on variables and styles. Look at how Figma names them. Read the names you already used in C1 and C2.

##### 4. Where to Find Resources
- Figma Learn, https://help.figma.com/ - read the help pages on variables and styles.
- Your own C1 and C2 files.

##### 5. Step-by-Step Guide
How to think about it:
- Could a new teammate guess this name without asking you?
- Does the name say the job, not the value? For example `colour-danger`, not `red`.

1. Collect every name from the five sets. Put them in one list.
2. Group the names: colour, type, space, size.
3. Write one rule per group. Keep each rule to one line.
4. Add three names that follow the rule and three that break it. Write the reason next to each one.

Worked example: a rule for a food delivery app, "Use lower case and dashes. Two parts only." Follows the rule: `space-4`, `text-heading`. Breaks the rule: `Space4`, `headingTextLarge`. Notice that the broken names still make sense. They fail because they break the team rule, not because they are silly.

Common mistakes:
- Naming a token after its value, like `blue-500`, when it is a role. Fix: name the job, like `text-link`.
- Names of five words or more. Fix: keep it to three parts at most.
- Writing rules only you can follow. Fix: ask one teammate to apply them without help.

If you get stuck: read the variables page again. Search "design token naming convention". Ask in Discord with one rule and one name that breaks it.

##### 6. What to Commit
- [ ] Path: `system/docs/token-naming.md`, written by this week's system owner
- [ ] Done when: the file has one rule per group, in simple words
- [ ] Done when: it has three correct examples and three wrong ones, each with a reason
- [ ] Done when: one other designer used the rule without asking you a question
- [ ] Commit message: `S1.1: add token naming rules`

#### Task - Pick the foundations (ID `S1.2`)

##### 1. What We Are Doing
The team chooses one type scale, one spacing scale and one colour system for all five flows. You may also join two sets into one.

##### 2. Why We Are Doing It
Five different scales make five different-looking flows. A shared system keeps the screens calm and saves work in Sprint 4.

##### 3. What to Learn First
Read Refactoring UI chapters 1 to 6 and 8. Look at the parts on scale and hierarchy.

##### 4. Where to Find Resources
- All five sets of C1 and C2 work, posted in the cohort channel.
- Refactoring UI, chapters 1 to 6 and 8.
- Type scale tool, https://typescale.com/ and colour tool, https://leonardocolor.io/. Use them to compare two sets side by side.

##### 5. Step-by-Step Guide
How to think about it:
- Which set works at 390px with long Malayalam labels?
- Which set is easiest to explain to someone who joins next month?

1. Put the five sets side by side on one screen.
2. Test each set with the Malayalam test string `അപേക്ഷ സമർപ്പിക്കുക` at small and large sizes.
3. Choose one set, or join two sets. Write the reason in two lines.
4. List what you rejected and why. One line per rejected set.

Worked example: a team rejected a 12-step type scale. Reason: "Only four steps were ever used, and the small steps were too close to tell apart." The reason names a use, not a taste.

Common mistakes:
- Choosing by look alone. Fix: test both sets with Malayalam text first.
- No reason written for the choice. Fix: write two lines before you close the file.

If you get stuck: read the scale chapters again. Search "type scale Malayalam 390px". Ask in Discord with two sets and the Malayalam test.

##### 6. What to Commit
- [ ] Path: `system/docs/foundations-decision.md`
- [ ] Done when: one type scale, one spacing scale and one colour system are chosen
- [ ] Done when: every rejected set has one line with a reason
- [ ] Done when: the file says who decided and on which day
- [ ] Commit message: `S1.2: add foundations decision`
- [ ] This decision cannot be reopened after week 2 without a written decision record.

#### Task - Write the tokens (ID `S1.3`)

##### 1. What We Are Doing
Turn the agreed foundations into two JSON files. JSON is a plain text format that a computer can read. Layer one holds raw values. Layer two holds roles.

##### 2. Why We Are Doing It
Typed values stop small drift, like six shades of grey. They also carry the work into Sprint 4 without a rewrite.

##### 3. What to Learn First
Read `Design-Sprint-4/06-token-architecture.md`, section "Format". Look at the `$type` and `$value` structure and copy it. Read the Figma help pages on variables to see how a role points to a raw value.

##### 4. Where to Find Resources
- `Design-Sprint-4/06-token-architecture.md`, section "Format".
- Figma Learn, https://help.figma.com/ - the pages on variables.

##### 5. Step-by-Step Guide
How to think about it:
- Does every role point to a raw value, and never to another role?
- Can you read the file out loud and still follow it?

1. List the raw values first: font sizes, space steps, colours.
2. Give each one a name from your S1.1 rule.
3. Add the second layer: roles such as `text-body` or `space-gap`.
4. Point each role to one raw value. Do not skip a role.
5. Save two files and commit them.

Worked example: a chess app token: `{"colour-base-white": {"$type": "color", "$value": "#FFFFFF"}}` in the raw layer. In the roles layer: `{"surface-page": {"$type": "color", "$value": "{colour-base-white}"}}`. Notice that the role points to a name, not a code.

Common mistakes:
- Putting raw codes in the roles layer. Fix: roles point to names only.
- One layer for everything. Fix: keep raw values and roles apart.
- Odd names that break the S1.1 rule. Fix: run the rule over every name before you commit.

If you get stuck: read the format section again. Search "design tokens JSON $type $value". Ask in Discord with one token and its role.

##### 6. What to Commit
- [ ] Path: `system/tokens/primitive.json`
- [ ] Path: `system/tokens/semantic.json`
- [ ] Done when: two JSON files exist and both are valid
- [ ] Done when: every role points to a raw value
- [ ] Done when: every name follows the S1.1 rule
- [ ] Commit message: `S1.3: add primitive and semantic tokens`

#### Task - Shared Figma library or shared source (ID `S1.4`)

##### 1. What We Are Doing
Make one shared source for the agreed variables and styles. All designers switch to it this week if the plan allows.

##### 2. Why We Are Doing It
A shared source keeps five files in step. When the client asks for a change in week 3, you edit one place, not five.

##### 3. What to Learn First
Read the Figma help pages on libraries and on publishing styles. Check with the admin if the Figma Education plan or a team library is allowed. Do not assume.

Tool setup: see `../04-Tools-Setup.md` (Figma setup section). Use ONE Figma file per sprint named `SPRINT-1 UX{n}`, one page per week. Starter allows 3 files. Use one file per sprint, with one page per week. The shared system lives in ONE team library file only if the admin or Education plan allows libraries. Otherwise the shared system lives in `system/` as markdown or JSON tokens.

##### 4. Where to Find Resources
- Figma Learn, https://help.figma.com/ - read the pages on libraries and on publishing styles.
- `../04-Tools-Setup.md` - look for the Figma setup section.
- The token files from S1.3.

##### 5. Step-by-Step Guide
How to think about it:
- Can a new designer find a colour in under ten seconds?
- Will this source still make sense in Sprint 4, when the flows grow?
- If libraries are not allowed, can a teammate use the tokens and a view-only link?

1. Ask the admin if the team can use libraries. If yes, continue. If no, skip to step 4.
2. Make ONE team library file named `system`. Add the raw values as variables. Add the roles as variables too. Link each role to its raw value. Publish the file as a library.
3. Switch your own `SPRINT-1 UX{n}` file to the library. Check that nothing breaks.
4. If libraries are not allowed, do not publish a library. Keep the tokens in `system/tokens/`. Share a view-only Figma link and the exported tokens in the cohort channel.
5. Open the link in a private window and test it.
6. Post the link in the cohort channel.

Worked example: a news app team grouped its variables by job: `text`, `surface`, `border`. New members found a value fast. The groups follow the job, not the colour.

Common mistakes:
- Publishing before the names are checked. Fix: run the S1.1 rule first.
- Adding dark mode now. Fix: light mode only this week, as agreed.
- Posting a link nobody can open. Fix: open the link in a private window and test it.
- Making three Figma files for one sprint. Fix: one file per sprint, one page per week. Use tokens in `system/` when libraries are not allowed.

If you get stuck: read the libraries page again. Search "Figma publish library variables". Ask in Discord with your plan type and what you see.

##### 6. What to Commit
- [ ] Path: `system/README.md`
- [ ] Done when: one shared source is published if libraries are allowed, otherwise tokens and a view-only link are posted
- [ ] Done when: every variable has a name that follows the rule
- [ ] Done when: your own file uses the shared source, with no broken styles, if libraries are allowed
- [ ] Done when: the link is posted and the `system/README.md` says who owns it
- [ ] Commit message: `S1.4: add shared source notes`

#### Task - Why session: Gestalt principles (ID `F1.1`)

##### 1. What We Are Doing
One designer presents the Gestalt principles. Gestalt principles are rules about how the eye groups things. Every principle is shown with a screenshot from the public Kerala PSC website, not from a textbook.

##### 2. Why We Are Doing It
Grouping decides what a candidate sees first on a busy page. If you cannot name the grouping, you cannot fix a messy notice area.

##### 3. What to Learn First
Learn the six principles: proximity, similarity, common region, continuity, closure, figure-ground.

##### 4. Where to Find Resources
- Kerala PSC home page, https://www.keralapsc.gov.in/ - take your screenshots here.
- Laws of UX, https://lawsofux.com/ - read the short pages on proximity, similarity and common region.
- `08-glossary.md` in the sprint folder. Check the plain meaning of any term you are unsure about.

##### 5. Step-by-Step Guide
How to think about it:
- What does the eye group here, and is that grouping useful to a candidate?
- Which principle explains the grouping best? Use one, not three.

1. Open the home page on a laptop. Take one full-page screenshot.
2. Find one clear example for each principle. Use the menu groups, the quick-access tiles and the announcements area.
3. Crop each screenshot to the part that shows the principle. Never crop out the context.
4. Write two lines under each one: what the eye groups, and what the candidate may miss.
5. Present in the session. Six screenshots, six short notes.

Verify yourself: you decide what each screenshot shows. Write what you see and where you found it. If a principle has no clear example, write "no clear example found".

Worked example: a railway booking page puts the date and the class choice in one bordered box. Common region explains it. The traveller reads them as one decision. The note names the grouping and the effect, not just the box.

Common mistakes:
- Using textbook diagrams. Fix: every image must come from the public site.
- One screenshot for two principles. Fix: one example per principle.
- Long notes. Fix: two lines each.

If you get stuck: read the Laws of UX pages again. Search "Gestalt proximity common region". Ask in Discord with one screenshot and the principle you think it shows.

##### 6. What to Commit
- [ ] Path: `fundamentals/why-sessions/week01-gestalt.md`
- [ ] Done when: six principles, one screenshot each, all from public Kerala PSC pages
- [ ] Done when: each screenshot has two lines: the grouping and the effect on a candidate
- [ ] Done when: the session is presented and the file is committed
- [ ] Commit message: `F1.1: add Gestalt why session`

#### Task - Teardown: IRCTC ticket booking (ID `F1.2`)

##### 1. What We Are Doing
Study the IRCTC ticket booking flow and write a teardown. A teardown is a short study of a real product: what it does, and why.

##### 2. Why We Are Doing It
A second real service shows patterns you can reuse. It also trains you to look at a flow step by step, as you did with the Kerala PSC journey.

##### 3. What to Learn First
Read the five-part teardown format in root `02-Learning-Path.md` before you start writing.

##### 4. Where to Find Resources
- Root `02-Learning-Path.md`. Copy the five-part teardown format exactly.
- 10 Usability Heuristics, https://www.nngroup.com/articles/ten-usability-heuristics/ - name a heuristic when you say something works or fails.

##### 5. Step-by-Step Guide
How to think about it:
- Which step is the moment of no return? What does the screen say before it?
- What does this service do that the Kerala PSC journey could learn from?

1. Open the IRCTC booking site. Do not pay and do not book a ticket.
2. Walk the flow slowly: search, choose, check, pay.
3. Screenshot the four or five key steps. Redact any personal data.
4. Write the five parts. Keep each part short.
5. Add one line: one thing the Kerala PSC flow could borrow.

Worked example: a student wrote: "The seat choice shows price and availability in the same row. The candidate compares without leaving the page." The note names a pattern, not a feeling.

Common mistakes:
- Writing a review, not a teardown. Fix: describe the step, then the reason.
- Screenshots with a name or a phone number. Fix: redact before you save.
- No link back to your own project. Fix: add the closing line.

If you get stuck: read the format again. Search "IRCTC booking flow steps". Ask in Discord with one screenshot and the step you cannot name.

##### 6. What to Commit
- [ ] Path: `fundamentals/teardowns/01-irctc.md`
- [ ] Save screenshots as PNG or JPG under 2 MB. Redact personal data.
- [ ] Done when: all five parts are present and short
- [ ] Done when: four or more screenshots are saved, with personal data removed
- [ ] Done when: one line says what the Kerala PSC flow could borrow
- [ ] Commit message: `F1.2: add IRCTC teardown`

#### Task - Drill, from now on (ID `F1.3`)

##### 1. What We Are Doing
A ten-minute drill, every day. Rebuild one component from any real Indian product from memory. Then compare it with the real one.

##### 2. Why We Are Doing It
Fast hands leave more time for thinking. A daily drill also trains your eye for spacing and alignment.

##### 3. What to Learn First
Open the Figma help pages on frames, auto layout and components. Use `../08-Prototyping-And-Responsive.md` when you want to rebuild a whole screen.

##### 4. Where to Find Resources
- Figma Learn, https://help.figma.com/ - the pages on frames, auto layout and components.
- `../08-Prototyping-And-Responsive.md` at the repo root.

##### 5. Step-by-Step Guide
How to think about it:
- What did you get wrong: size, spacing or label?
- What will you check first tomorrow?

1. Pick one component: a button, a card, a form field.
2. Rebuild it from memory. Do not look at the real one. Take ten minutes.
3. Open the real product. Compare side by side.
4. Write one line in the log: what differed, and why.

Worked example: log line: "My button was 44px high, the real one is 48px. The label sat too close to the edge." The line is short and names a number.

Common mistakes:
- Copying instead of rebuilding from memory. Fix: hide the real screen first.
- No number in the log. Fix: write one size or one gap.
- Skipping days. Fix: do it at the same time each day.

If you get stuck: read the auto layout page again. Search "Figma button auto layout". Ask in Discord with your rebuilt component and the real screenshot.

##### 6. What to Commit
- [ ] Path: `fundamentals/drills/UX{n}-log.md`
- [ ] Done when: the log has one entry for each day practised in week 1; continue daily through the sprint
- [ ] Done when: every line names one difference and one number
- [ ] Done when: the log file is committed
- [ ] Commit message: `F1.3: start daily drill log`

Code corner: none this week. The first code work starts in week 0 setup and week 3.

## 6. What to Commit

End of week checklist:
- [ ] 5 learning summaries: `Design-Sprint-1/students/UX{n}/week1/session1-learning.md` to `session5-learning.md`, one commit each, message `W1: add session N learning summary`
- [ ] P1.1, P1.2, P1.3, P1.4
- [ ] R1.1, R1.2, R1.3
- [ ] C1.1, C1.2, C1.3, C1.4
- [ ] C2.1, C2.2
- [ ] Two peer reviews given, each with one substantive comment
- [ ] Critique attended, log filed if you were lead
- [ ] Day 6: S1 session done, teardown committed, drill log started

Allowed files: markdown (.md), PNG/JPG under 2 MB, PDF under 10 MB, and a view-only Figma link written inside a markdown file. Name images in lowercase with hyphens, no spaces. Never commit .fig files, passwords, tokens, or real personal data. Where Figma is named, a view-only Penpot link is allowed.

If you are short on time, cut in this order: C1.3, then C1.4. Never cut R1.2, R1.3, or the learning summaries. Craft can be polished later. Audit findings and understanding cannot be added later.

When your branch is ready, open a pull request. See `../10-GitHub-For-Designers.md`.

Next: `03-week2.md`
