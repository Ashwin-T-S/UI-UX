# Week 8 - Synthesise

**Theme: turn evidence into decisions, and defend a five-person study.**

## Week at a Glance

| Task ID | Task name | Time | File you will commit |
|---|---|---|---|
| R6.1 | Findings report | 1 h 15 min | `students/UX{n}/week8/R6-1-findings-report.md` |
| R6.2 | Confidence audit | 45 min | `students/UX{n}/week8/R6-2-confidence-audit.md` |
| R6.3 | Journey map | 1 h 15 min | `students/UX{n}/week8/R6-3-journey-map.md` |
| P8.1 | Finding-to-decision map | 45 min | `students/UX{n}/week8/P8-1-finding-to-decision.md` |
| C9.1 | Redesign the two worst steps | 2 h 30 min | `students/UX{n}/week8/C9-1-redesign.md` |
| C9.2 | Full revised flow | 1 h 15 min | `students/UX{n}/week8/C9-2-revised-flow.md` |
| S9.1 | Evidence-linked spec | 45 min | `students/UX{n}/week8/S9-1-spec.md` |
| P8.2 | Reflection | 30 min | `students/UX{n}/week8/P8-2-reflection.md` |
| S10.1 | Sprint 2 system release | 30 min | `students/UX{n}/week8/S10-system-release.md` |
| S10.2 | Component documentation | 45 min | `students/UX{n}/week8/S10-component-docs.md` |
| S10.3 | Debt update | 15 min | `students/UX{n}/week8/S10-debt.md` |
| F8.1 | Why session: decision-making | 45 min | `fundamentals/why-sessions/week08-decision-making.md` |
| F8.2 | Teardown: delivery checkout | 45 min | `fundamentals/teardowns/08-delivery-checkout.md` |
| F8.3 | Explainer: sample size | 30 min | `fundamentals/explainers/sprint2-sample-size.md` |
| F8.4 | Drill log review | 15 min | `students/UX{n}/week8/F8-4-drill-log-review.md` |
| JR2 | Case study 1 and live skeleton | 3 h | `students/UX{n}/portfolio/JR2-case-study-1.md` |

You also commit four learning notes: `session1-learning.md` to `session4-learning.md` in `students/UX{n}/week8/`. Use commit messages `W8.1 add learning note` to `W8.4 add learning note`.

About 21 hours of work in this week.

## 1. What We Are Doing

This week you turn three weeks of research into design decisions you can defend. You write findings with confidence levels, record both conflicting findings without choosing one, map the whole journey, and link each design change to evidence. You end with a defense, a system release, and a reflection.

Task groups:
- Findings and confidence: R6.1, R6.2
- Journey and decision trace: R6.3, P8.1
- Redesign, flow and spec: C9.1, C9.2, S9.1
- Defense and reflection: P8.2
- System release and retro: S10.1, S10.2, S10.3, F8.1, F8.2, F8.3, F8.4
- Job readiness: JR2

## 2. Why We Are Doing It

A working product designer in India often has to defend a change to a manager, client, or engineer who has a stronger opinion. This week gives you a habit: support each change with evidence, state confidence, and keep a separate judgement list. It matters for the project because the scholarship form redesign must be honest. It matters for your portfolio because a defended five-person study is a strong case study.

## 3. What to Learn First

By the end of the week you can:
- Present findings with confidence levels that match their evidence
- Record both conflicting findings without choosing one
- Trace every design change to a specific finding
- Defend a five-person study against someone who wants to dismiss it

Core ideas to review first:
- Confidence is not the same as evidence.
- Said-based evidence and did-based evidence are different.
- A denominator is how many participants a finding is based on, for example 4 of 5.
- Conflicting findings are data. Do not hide them.
- A journey map point must be attributed to a participant or labelled as an assumption.
- A slip is when the user intended the right thing and did the wrong thing.
- A mistake is when the user intended the wrong thing.
- A judgement list is allowed. Disguised judgement is not.
- Formative qualitative research finds problems and explains them. It does not measure how common they are.
- Do not infer prevalence from this sample. Justify confidence using evidence quality, context, consistency, and limitations.

## 4. Where to Find Resources

Your week in order:

| When | Source | What exactly | Time |
|---|---|---|---|
| Day 1 | Just Enough Research | The chapter on reporting and communicating findings | 30 min |
| Day 1 | NNGroup | "Personas Make Users Memorable" and "Why Personas Fail" | 25 min |
| Day 1 | Your own R5.5 | Read your findings and mark the ones you want to be true | 20 min |
| Day 2 | NNGroup | "Journey Mapping 101" and "Service Blueprints: Definition" | 35 min |
| Day 2 | Just Enough Research | The section on turning research into design direction | 25 min |
| Day 2 | Your R4.7 affinity map | Re-read the group names | 15 min |
| Day 3 | Your Sprint 1 work | Re-read your week 1 type and colour work, and the Sprint 1 accessibility gate | 45 min |
| Day 4 | The Design of Everyday Things | The chapter on human error: slips versus mistakes | 40 min |
| Day 4 | Your R5.5 | Classify observed error cases as slips or mistakes where the evidence supports it. Mark other findings "not applicable" or "uncertain". | 20 min |

Tool to open: Figma for C9.1 and C9.2. Setup: [Figma and Penpot setup](../04-Tools-Setup.md). Keep one Figma file for Sprint 2: `SPRINT-2 UX{n}`, with one page per week. If the Figma free plan file limit blocks you, use the Penpot free plan (check before use). A view-only Penpot link is allowed in place of a view-only Figma link. Open a browser for readings and GitHub for commits. If you need account setup, see the [setup guide](../04-Tools-Setup.md).

Search keywords when you are stuck:
- formative research confidence findings
- said vs did research evidence
- journey map attribution
- slip vs mistake design
- finding to decision traceability
- evidence linked design spec

## 5. Step-by-Step Guide

> All `students/...` paths in this week are inside your sprint folder (`Design-Sprint-N/`). Open a terminal in the repo root and use full paths.

Learning notes for this week: each note must include the date, the source, three key ideas in your own words, one question you still have, and one next action. Use these commit messages:
- `W8.1 add learning note` for `session1-learning.md`
- `W8.2 add learning note` for `session2-learning.md`
- `W8.3 add learning note` for `session3-learning.md`
- `W8.4 add learning note` for `session4-learning.md`

One task, one commit with all files listed for that task. See `../10-GitHub-For-Designers.md`. Do not put two tasks in one file. Use P1 to P5 only. No real names, faces, phone numbers, or IDs. Allowed files: markdown (.md), small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, and a view-only Figma or Penpot link inside a markdown file. Never commit .fig files, passwords, tokens, or real personal data.

Use one Figma file for Sprint 2: `SPRINT-2 UX{n}`, with one page per week. Do not split a sprint into many Figma files. Without libraries, use the shared view-only system reference and tokens in `system/`, and create local components in your sprint file. Use a team library only if the admin confirms access.

### Group 1 - Findings and confidence (Day 1)

First, commit your Day 1 learning note to `students/UX{n}/week8/session1-learning.md` with message `W8.1 add learning note`. Use the learning note checklist above.

#### Task - Findings report (ID `R6.1`)

##### 1. What We Are Doing
Write a six-section findings report from your five sessions. It must state confidence, name bias, and record one contradiction without choosing a side. Add a one-page persona summary built from your five participants.

##### 2. Why We Are Doing It
A report that hides contradictions or overstates confidence will fail in the defense. A working designer needs to show what the evidence can and cannot support.

##### 3. What to Learn First
- Denominator: how many participants a finding is based on.
- Confidence: how strong the evidence is.
- Recruitment channel: where you found people, and how that shapes the sample.
- A contradiction means two findings that point in different directions. Record both. Do not choose one by preference.
- A persona is a summary of evidence. It is not a fictional person used to win arguments.

##### 4. Where to Find Resources
Use R5.5 and your Day 1 learning note. Use the Just Enough Research chapter on reporting. Read both NNGroup persona articles.

##### 5. Step-by-Step Guide
1. Create `R6-1-findings-report.md`.
2. Write section 1: what you set out to learn. Use your three questions from R3.3.
3. Write section 2: method, sample, and dates.
4. Add the recruitment channel.
5. Name the recruitment channel as a bias source.
6. Write section 3: one finding per block. Add its denominator, evidence, and confidence.
7. Write section 4 heading. State one contradiction.
8. State both sides of the contradiction.
9. State what would settle it.
10. Do not choose your favourite side.
11. Write section 5: what you still do not know.
12. Add how you would find out.
13. Add roughly what it would cost.
14. Write section 6: ranked recommendations.
15. Add the finding ID to each recommendation.
16. Add a one-page persona summary from P1 to P5.
17. Label each part with the participant it comes from, or write "assumption".
18. Check the Done when list below.

Fictional example from an unrelated project. This is not your scholarship study. Do not copy it into your report.

> **Contradiction.** In a fictional library book renewal study, P1 and P3 asked for automatic renewals, because they often forget the date. P2 did not want automatic renewals, because a late return is sometimes how they notice a book they no longer need.
>
> Both views are valid. The context is different: one is about forgetting, the other is about noticing. I do not know which case is more common. What would settle it: a question in the next library survey asking whether people want reminders or automatic renewal. Until then, any automatic renewal must be easy to switch off.

Use only your own participant evidence in your real report.

If you get stuck: read the fictional example again; search "research findings report contradiction"; ask in Discord with a screenshot and what you tried.

How to think about it: the contradiction is data. The persona is a summary. Neither is a place to hide your preference. Use only your own participant evidence.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/R6-1-findings-report.md`
- [ ] All six sections
- [ ] Recruitment channel named as a bias source
- [ ] Every finding has a denominator and a confidence level
- [ ] At least one contradiction stated and left unresolved, with what would settle it
- [ ] Recommendations ranked and each traced to a finding
- [ ] Persona summary added and grounded in P1 to P5
- [ ] Commit message: `R6.1 add findings report`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Confidence audit (ID `R6.2`)

##### 1. What We Are Doing
Audit every finding for the evidence under it. Mark it as said-based or did-based. Identify any unsupported confidence ratings and explain each change. If no rating needs changing, justify one rating you checked.

##### 2. Why We Are Doing It
Your favourite ideas often get the strongest confidence by accident. This audit finds that before the defense does.

##### 3. What to Learn First
- What people do is stronger evidence than what people say.
- What people say about the past is stronger than what they say they would do in future.
- Do not treat one person as proof of how common a problem is. Justify confidence using evidence quality, context, consistency, and limitations.
- Do not infer prevalence from this sample.

##### 4. Where to Find Resources
Use R6.1. Use your Day 1 note on the persona articles.

##### 5. Step-by-Step Guide
1. Open R6.1.
2. Mark each finding as said-based or did-based.
3. Mark any finding based on a hypothetical as lower confidence.
4. Reassess every finding.
5. Identify any unsupported confidence ratings.
6. Name the ratings you change.
7. Explain each change you make.
8. If no rating needs changing, choose one rating you checked and justify it.
9. Check that confidence uses evidence quality, context, consistency, and limitations.
10. Check that no finding claims how common a problem is from this sample.

If you get stuck: search "said vs did research evidence"; ask in Discord with the finding you are unsure about.

How to think about it: look first at the ratings you like most. That is where overconfidence hides.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/R6-2-confidence-audit.md`
- [ ] Every finding marked as said-based or did-based
- [ ] Any hypothetical-based finding downgraded
- [ ] Unsupported confidence ratings identified and changes explained
- [ ] If no rating needed changing, one checked rating is justified
- [ ] Confidence uses evidence quality, context, consistency, and limitations
- [ ] No claim about how common a problem is based on this sample
- [ ] Commit message: `R6.2 add confidence audit`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

### Group 2 - Journey and decision trace (Day 2)

First, commit your Day 2 learning note to `students/UX{n}/week8/session2-learning.md` with message `W8.2 add learning note`. Use the learning note checklist above.

#### Task - Journey map (ID `R6.3`)

##### 1. What We Are Doing
Map the whole journey, from hearing about the scholarship to money arriving or not. Include offline steps and a behind-the-scenes row. Attribute every point to a participant or label it as an assumption.

##### 2. Why We Are Doing It
Most of the journey is not on your screen. The biggest failures often happen off it. Attribution stops you from inventing a neat journey.

##### 3. What to Learn First
- Attribution: marking each point with the participant who said or did it.
- An assumption is allowed. A hidden assumption is not.
- A service blueprint shows what happens behind the scenes.

##### 4. Where to Find Resources
Use R4.7 affinity map. Read NNGroup "Journey Mapping 101" and "Service Blueprints: Definition".

##### 5. Step-by-Step Guide
1. Open R4.7 and re-read the group names.
2. Draw five rows: what they do, what they think, what they feel, where the pain is, and what happens behind the scenes.
3. Start before the screen: when someone hears the scholarship exists.
4. End after money arrives or does not.
5. Add journey points.
6. Mark each point with P1 to P5 or write "assumption".
7. Add offline steps: getting a certificate.
8. Add an office visit.
9. Add asking a teacher.
10. Find the worst moment.
11. Add the evidence for it.
12. Check the Done when list.

If you get stuck: read "Journey Mapping 101" again; search "journey map assumptions"; ask in Discord with your five rows.

How to think about it: if you cannot attribute a point, it is an assumption. That is allowed. Hiding it is not.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/R6-3-journey-map.md`
- [ ] The journey extends before and after the digital flow
- [ ] Five rows including the behind-the-scenes row
- [ ] Every point attributed to a participant or labelled as an assumption
- [ ] Offline steps included
- [ ] The worst moment is identified, with the evidence for it
- [ ] Commit message: `R6.3 add journey map`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Finding-to-decision map (ID `P8.1`)

##### 1. What We Are Doing
Make a table with one row per design decision. Link each decision to a finding, its confidence, and what you would change if the finding is wrong. Put decisions with no finding in a separate judgement list.

##### 2. Why We Are Doing It
This is how you show that a change is supported by evidence. It also protects honest visual and interaction quality decisions from pretending to be research.

##### 3. What to Learn First
- A decision with no finding is allowed in the judgement list.
- Confidence must come from R6.2, not from how much you like the decision.
- "If wrong" means what you would change, not a defence.

##### 4. Where to Find Resources
Use R6.2 and R6.1. Use the fictional example below.

##### 5. Step-by-Step Guide
1. Create a table with four columns: decision, finding, confidence, if the finding is wrong.
2. List the decisions you plan to make in this week's redesign.
3. Fill in the finding ID from R6.2.
4. Fill in the confidence from R6.2.
5. Answer "if wrong" for every row.
6. Move decisions with no finding to a list named "designer's judgement".
7. Check the judgement list. It must be honest.

Fictional example from an unrelated project. This is not your scholarship study. Do not copy these findings or decisions. Use only your own participant evidence.

| Decision | Finding | Confidence | If the finding is wrong |
|---|---|---|---|
| Ask for the library card number before showing the renewal options | Fictional finding F-03: 4 of 5 could not find their card number at the start | Medium | If borrowers usually have the number ready, this adds a step for no benefit and should be removed. |
| Show the full list of renewal rules up front | Fictional finding F-05: 3 of 5 wanted to know all rules before starting | Low | If most borrowers prefer to start immediately, this becomes a long, intimidating list and should be collapsible. |

Judgement list example: button placement, exact wording of the confirmation heading, icon choices. No research supports these. They are visual and interaction quality decisions and must be named as such.

If you get stuck: search "design decision traceability"; ask in Discord with one row you cannot trace.

How to think about it: judgement is allowed. Disguised judgement is the problem. Use only your own participant evidence in your real table.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/P8-1-finding-to-decision.md`
- [ ] Every design decision in the table
- [ ] Every one traced to a finding, or moved to the judgement list
- [ ] Confidence carried across from R6.2
- [ ] Every row has an "if wrong" answer
- [ ] The judgement list exists and is honest
- [ ] Commit message: `P8.1 add finding to decision map`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

### Group 3 - Redesign, flow and spec (Day 3 and Day 4)

First, commit your Day 3 learning note to `students/UX{n}/week8/session3-learning.md` with message `W8.3 add learning note`. Use the learning note checklist above.

#### Task - Redesign the two worst steps (ID `C9.1`)

##### 1. What We Are Doing
Redesign the two worst steps in the journey. Use the shared system. State the finding, the change, your prediction, and how you would test it.

##### 2. Why We Are Doing It
This is your first design work after three weeks of research. The visual and interaction quality standard from Sprint 1 still applies.

##### 3. What to Learn First
- All relevant states: default, focus, error, success, loading if needed.
- Contrast and focus order are part of the design, not a later task.
- A focus order is the order a keyboard or switch user reaches controls. An annotated focus order is a numbered list or overlay that shows this order.
- A prediction is a testable sentence.

##### 4. Where to Find Resources
Use R6.3 and P8.1. Open Figma file `SPRINT-2 UX{n}`, page for week 8. Re-read the Sprint 1 accessibility gate. Without libraries, use the shared view-only system reference and tokens in `system/`, and create local components in your sprint file. Use a team library only if the admin confirms access.

##### 5. Step-by-Step Guide
1. Open Figma file `SPRINT-2 UX{n}`.
2. Pick the two worst steps from R6.3.
3. Redesign step 1 with all relevant states.
4. Redesign step 2 with all relevant states.
5. Use local components, or a team library only if the admin confirms access.
6. For each change, write the finding ID.
7. Write what you changed.
8. Write your prediction.
9. Write how you would test each prediction.
10. Check contrast.
11. Add an annotated focus order for each redesigned step.
12. If you make a Figma or Penpot prototype, test only the keyboard interactions the tool supports.
13. Add a view-only Figma or Penpot link to your markdown file.

If you get stuck: re-read the Sprint 1 accessibility gate; search "focus order check"; ask in Discord with a screenshot and what you tried.

How to think about it: a prediction is not a hope. Write what you expect to see and how you would know. A full keyboard test belongs to an implemented page, not to a visual design.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/C9-1-redesign.md`
- [ ] Two steps redesigned, all relevant states
- [ ] Local components used, or a team library only if the admin confirms access
- [ ] Each change linked to a finding by its ID
- [ ] A stated prediction per change, and how you would test it
- [ ] Contrast checked
- [ ] Annotated focus order added for each redesigned step
- [ ] If you built a prototype, supported keyboard interactions tested
- [ ] Commit message: `C9.1 redesign worst steps`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

Next, commit your Day 4 learning note to `students/UX{n}/week8/session4-learning.md` with message `W8.4 add learning note`. Use the learning note checklist above.

#### Task - Full revised flow (ID `C9.2`)

##### 1. What We Are Doing
Design every screen in the revised flow. Use the system. Handle slips and mistakes differently, and state the difference.

##### 2. Why We Are Doing It
A flow that treats every error the same will fail. A slip needs layout, size, or confirmation. A mistake needs a better model.

##### 3. What to Learn First
- Slip: the user intended the right thing and did the wrong thing.
- Mistake: the user intended the wrong thing.
- Treating a mistake as a slip is why many redesigns fail.

##### 4. Where to Find Resources
Use your Day 4 note on The Design of Everyday Things. Open Figma file `SPRINT-2 UX{n}`.

##### 5. Step-by-Step Guide
1. Open Figma file `SPRINT-2 UX{n}`.
2. List every screen in the revised flow.
3. Design each screen at mid to high fidelity.
4. Use local components, or a team library only if the admin confirms access.
5. For each error case, mark it as a slip or a mistake.
6. Show a different handling for each type.
7. Write one line that states the difference.
8. Check contrast.
9. Add an annotated focus order for the flow.
10. If your prototype supports keyboard interactions, test those interactions.
11. A full keyboard test is required only for an implemented page.

If you get stuck: search "slip vs mistake design"; ask in Discord with one error case.

How to think about it: a mistake needs a better model, not a bigger button.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/C9-2-revised-flow.md`
- [ ] Every screen in the revised flow, mid to high fidelity
- [ ] Local components used, or a team library only if the admin confirms access
- [ ] Slips and mistakes handled differently, with the difference stated
- [ ] Contrast checked
- [ ] Annotated focus order added
- [ ] Supported prototype keyboard interactions tested
- [ ] Commit message: `C9.2 add revised flow`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Evidence-linked spec (ID `S9.1`)

##### 1. What We Are Doing
Write the handoff spec to the Sprint 1 standard. Add one thing: every non-obvious decision carries the finding ID it came from.

##### 2. Why We Are Doing It
An engineer who wants to change something should see what evidence they would be arguing with.

##### 3. What to Learn First
- A non-obvious decision is one that needs a reason.
- A finding ID is a short link to R6.1.
- A judgement note is allowed when there is no finding.

##### 4. Where to Find Resources
Use your Sprint 1 handoff spec. Use P8.1 and C9.2.

##### 5. Step-by-Step Guide
1. Open your Sprint 1 handoff spec.
2. Copy the structure into `S9-1-spec.md`.
3. Add each screen and state from C9.2.
4. Add the finding ID to every non-obvious decision.
5. Add a view-only Figma or Penpot link.
6. Check every decision has evidence or a named judgement note.

If you get stuck: search "evidence linked design spec"; ask in Discord with one decision.

How to think about it: the spec is an argument with evidence, not only a list of screens.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/S9-1-spec.md`
- [ ] Handoff spec to the Sprint 1 standard
- [ ] Every non-obvious decision carries the finding ID it came from
- [ ] Commit message: `S9.1 add evidence linked spec`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Critique - 90 minutes

Final critique. Present the flow and the finding-to-decision map together. The critique focus: is every change supported by evidence, or has a visual and interaction quality preference been hidden behind a quote?

### Group 4 - Defense and reflection (Day 5)

#### Defense - 55 minutes

Arrange the defense in Discord. Book a 60 minute voice session with at least one peer. One peer acts as examiner and keeps time. The examiner draws one constraint card at random. If you have no peer, do a solo defense: write the five cards, shuffle them, draw one, and record the session with Loom free (check the free limit before use). Save the examiner feedback, or your solo review, in `students/UX{n}/week8/P8-2-reflection.md` under the heading "Defense feedback".

Pass criteria: you can state your questions, method, sample, three findings with confidence, one unresolved contradiction, and answer the sample size question with sources. You do not need to win the argument. If you are solo, review the recording against the same criteria.

| Part | Time | What you do |
|---|---|---|
| Research walk | 10 min | Your questions, your method, your sample. From memory. |
| Findings | 10 min | Three findings with confidence and evidence |
| Contradiction | 5 min | The one you did not resolve, and why that is the right answer |
| Sample size attack | 10 min | You will be told five is worthless. Answer it properly. |
| Failure story | 10 min | The Week 7 mid-study change injection exercise. Use the saved file in your Week 7 folder (`students/UX{n}/week7/`; open the Week 7 task list and use the exact filename you saved). |
| Alternative | 10 min | The examiner draws a constraint card. |

**Prepare your answer to the sample size attack.** Write your answer in your own words. Support it with at least two sources you read this week. Do not memorise a model answer.

**Sprint 2 constraint cards:** you get one participant instead of five · no recording allowed · participants are all from one school · the mission insists the form length is the problem and will not fund anything else · you must report to someone who does not believe in research.

#### Task - Reflection (ID `P8.2`)

##### 1. What We Are Doing
Write a short reflection on what you got wrong, your interviewing habit, your worst defense answer, and one behaviour you will change in Sprint 3.

##### 2. Why We Are Doing It
The reflection turns the defense into learning. It is for the next sprint, not for looking good.

##### 3. What to Learn First
- A specific behaviour is small and observable.
- "I will listen better" is not specific. "I will wait three seconds before the next question" is specific.

##### 4. Where to Find Resources
Use your defense notes and your five interview notes.

##### 5. Step-by-Step Guide
1. Open your defense notes.
2. Write the finding you were most wrong about at the start.
3. Write your worst interviewing habit.
4. Write whether it improved between interview 1 and 5.
5. Write the question in the defense you answered worst.
6. Write one specific behaviour you will change in Sprint 3.
7. Add a "Defense feedback" section. Use the examiner feedback or your solo review.
8. Check the Done when list.

If you get stuck: ask in Discord with the behavior you want to change.

How to think about it: a useful reflection names one small action. It does not list many wishes.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/P8-2-reflection.md`
- [ ] The finding you were most wrong about at the start
- [ ] Your worst interviewing habit and whether it improved between interview 1 and 5
- [ ] The question in the defense you answered worst
- [ ] One specific behaviour you will change in Sprint 3
- [ ] Defense feedback section added from the examiner or solo review
- [ ] Commit message: `P8.2 add reflection`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

### Group 5 - System release and retro (Day 6)

#### Task - Sprint 2 system release (ID `S10.1`)

##### 1. What We Are Doing
Release the Sprint 2 system and update the changelog.

##### 2. Why We Are Doing It
A release note makes the system state clear for Sprint 3 and Sprint 4.

##### 3. What to Learn First
- A changelog lists what changed and when.
- Use the one Figma file for Sprint 2: `SPRINT-2 UX{n}`.

##### 4. Where to Find Resources
Open Figma file `SPRINT-2 UX{n}`. Use your Sprint 2 notes.

##### 5. Step-by-Step Guide
1. Open Figma file `SPRINT-2 UX{n}`.
2. Check the Sprint 2 pages are present.
3. Open `S10-system-release.md`.
4. Add the Sprint 2 release date.
5. List the changes in the changelog.
6. Check the file is committed.

If you get stuck: ask in Discord with the page you cannot find.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/S10-system-release.md`
- [ ] Sprint 2 release noted
- [ ] Changelog updated
- [ ] Commit message: `S10.1 add Sprint 2 release note`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Component documentation (ID `S10.2`)

##### 1. What We Are Doing
Document every component to the same standard. Do not carry exceptions forward.

##### 2. Why We Are Doing It
Sprint 4 will build on this system. Hidden exceptions become debt.

##### 3. What to Learn First
- Same standard means every component has the same sections.
- An exception is a component that lacks a section or has unclear states.

##### 4. Where to Find Resources
Use the system component list and the Sprint 1 documentation standard.

##### 5. Step-by-Step Guide
1. Open the component list.
2. Check each component against the same standard.
3. Fix one gap.
4. Repeat for each component.
5. Write a short "no exceptions" note in `S10-component-docs.md`.
6. Check the file is committed.

If you get stuck: ask in Discord with one component.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/S10-component-docs.md`
- [ ] Every component documented to the same standard
- [ ] No exceptions carried forward
- [ ] Commit message: `S10.2 add component docs`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Debt update (ID `S10.3`)

##### 1. What We Are Doing
Update the debt list. Note which Sprint 1 debt items are now two sprints old.

##### 2. Why We Are Doing It
Sprint 4 will inherit this debt. Naming it now makes it visible.

##### 3. What to Learn First
- Debt is work you know is needed but have not done.
- Two sprints old means it started in Sprint 1 and is still open in Sprint 2.

##### 4. Where to Find Resources
Open `system/debt.md` if your team allows it. Use your Sprint 1 notes.

##### 5. Step-by-Step Guide
1. Open `system/debt.md` if your team allows it.
2. Add new debt from Sprint 2.
3. Mark Sprint 1 debt items that are now two sprints old.
4. Save your copy in `S10-debt.md`.
5. Check the file is committed.

If you get stuck: ask in Discord which file the team uses for debt.

##### 6. What to Commit
- [ ] Team file: `system/debt.md` if your team allows it
- [ ] Student note: `students/UX{n}/week8/S10-debt.md`
- [ ] New debt added
- [ ] Sprint 1 debt items that are now two sprints old are noted
- [ ] Commit message: `S10.3 update debt`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Why session: decision-making (ID `F8.1`)

##### 1. What We Are Doing
Write one page on the psychology of decision-making: choice overload, defaults, and loss aversion. Use the scholarship form and what your participants actually did.

##### 2. Why We Are Doing It
This explains why people act differently from what they say. It helps you read your findings.

##### 3. What to Learn First
- Choice overload: too many options makes choosing harder.
- Defaults: the option already selected.
- Loss aversion: people dislike losing more than they like gaining.

##### 4. Where to Find Resources
Use your R5.5 findings and the scholarship form.

##### 5. Step-by-Step Guide
1. Write the one-page why session.
2. Add one example from the scholarship form.
3. Add one example from what your participants did.
4. Commit to the shared path if your team allows it.
5. If not, save a draft in your week 8 folder.

If you get stuck: ask in Discord with your example.

##### 6. What to Commit
- [ ] Shared file: `fundamentals/why-sessions/week08-decision-making.md` if your team allows it
- [ ] Or draft: `students/UX{n}/week8/F8-1-why-session.md`
- [ ] One page on choice overload, defaults, and loss aversion
- [ ] One example from the scholarship form and one from participant behaviour
- [ ] Commit message: `F8.1 add why session on decision making`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Teardown: delivery checkout (ID `F8.2`)

##### 1. What We Are Doing
Teardown a food delivery app checkout. It is the opposite of this sprint: high frequency, low stakes, heavily optimised.

##### 2. Why We Are Doing It
The contrast shows what changes when a flow is used often and has little risk.

##### 3. What to Learn First
- High frequency: people use it many times.
- Low stakes: a mistake is easy to fix.
- Heavily optimised: the design is tuned for speed.

##### 4. Where to Find Resources
Use one approved public food delivery checkout example marked "check before use". Open it only if it is available without login. Do not log in or place an order. If login is required, use the anonymised checkout screenshots supplied by your team. If screenshots are not supplied, ask in Discord for an approved public example (check before use).

##### 5. Step-by-Step Guide
1. Open a public food delivery checkout only if it is available without login (check before use).
2. If login is required, do not log in.
3. Use the anonymised checkout screenshots supplied by your team.
4. Note the main steps.
5. Note what is optimised for speed.
6. Write the teardown.
7. Commit to the shared path if your team allows it.
8. If not, save a draft in your week 8 folder.

If you get stuck: ask in Discord with the checkout step you are unsure about.

##### 6. What to Commit
- [ ] Shared file: `fundamentals/teardowns/08-delivery-checkout.md` if your team allows it
- [ ] Or draft: `students/UX{n}/week8/F8-2-delivery-checkout.md`
- [ ] Teardown covers the checkout and why it is the opposite of this sprint
- [ ] Commit message: `F8.2 add delivery checkout teardown`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Explainer: sample size (ID `F8.3`)

##### 1. What We Are Doing
Write one page on why five users is enough for some things and not others. Write for someone who has never done research.

##### 2. Why We Are Doing It
This is the written version of your defense answer. It helps you in interviews too.

##### 3. What to Learn First
- Five users can show that a problem exists.
- Five users cannot show how common the problem is.
- A completion rate needs a larger sample.

##### 4. Where to Find Resources
Use your defense notes and R6.2.

##### 5. Step-by-Step Guide
1. Write a plain definition of formative qualitative research.
2. List what five users can support.
3. List what five users cannot support.
4. Add what you would run to get frequency or completion rate.
5. Commit to the shared path if your team allows it.

If you get stuck: ask in Discord with one sentence you cannot simplify.

##### 6. What to Commit
- [ ] Shared file: `fundamentals/explainers/sprint2-sample-size.md` if your team allows it
- [ ] Or draft: `students/UX{n}/week8/F8-3-sample-size.md`
- [ ] One page written for someone who has never done research
- [ ] States what five users can and cannot support
- [ ] Commit message: `F8.3 add sample size explainer`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

#### Task - Drill log review (ID `F8.4`)

##### 1. What We Are Doing
Review your drill log. You now have 40 entries.

##### 2. Why We Are Doing It
A review shows patterns you cannot see one entry at a time.

##### 3. What to Learn First
- A pattern is something that repeats across entries.
- A next drill is one small practice task.

##### 4. Where to Find Resources
Use your drill log.

##### 5. Step-by-Step Guide
1. Count the entries.
2. Check you have 40.
3. Write three patterns you see.
4. Write one next drill.
5. Commit the review.

If you get stuck: ask in Discord with two entries you cannot classify.

##### 6. What to Commit
- [ ] `students/UX{n}/week8/F8-4-drill-log-review.md`
- [ ] 40 entries reviewed
- [ ] Three patterns and one next drill written
- [ ] Commit message: `F8.4 add drill log review`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

### Group 6 - Job readiness (Day 6)

#### Task - Case study 1 and a live skeleton (ID `JR2`)

##### 1. What We Are Doing
Build case study 1 and a live skeleton. Full method and done-when checklist: `06-Job-Readiness-Track.md` (repository root), section JR2. Publish the live skeleton with GitHub Pages.

##### 2. Why We Are Doing It
This is where the Sprint 2 work becomes portfolio evidence. The live skeleton is the start of your own site.

##### 3. What to Learn First
- A case study needs outcome, process, and visual and interaction quality.
- A live skeleton is a simple page you can publish, not a finished site.

##### 4. Where to Find Resources
Open `06-Job-Readiness-Track.md` at the repository root. Go to section JR2. Use the GitHub Pages quickstart: https://docs.github.com/en/pages/quickstart

##### 5. Step-by-Step Guide
1. Open `06-Job-Readiness-Track.md`.
2. Find section JR2.
3. Follow the method in that section.
4. Build case study 1.
5. Build the live skeleton as a small page with `index.html` and a CSS file if needed.
6. Put the page files in `students/UX{n}/portfolio/jr2-live/`.
7. Open https://docs.github.com/en/pages/quickstart
8. Follow the steps to create a GitHub Pages site from your repository.
9. Publish the page.
10. Open the published URL and check it loads.
11. Add the published URL to `JR2-case-study-1.md`.
12. Check the JR2 done-when checklist.
13. Commit the case study file and the page code files.

If you get stuck: ask in Discord with the JR2 step you are on and what you tried. Read the GitHub Pages quickstart again. Check that your `index.html` is in the folder you chose in the quickstart.

##### 6. What to Commit
- [ ] `students/UX{n}/portfolio/JR2-case-study-1.md`
- [ ] `students/UX{n}/portfolio/jr2-live/index.html`
- [ ] `students/UX{n}/portfolio/jr2-live/styles.css` if used
- [ ] `students/UX{n}/portfolio/jr2-live/script.js` if used
- [ ] Published GitHub Pages URL added to the case study file
- [ ] JR2 done-when checklist complete
- [ ] Commit message: `JR2 add case study 1`
- [ ] Allowed: .md, small .html, .css, .js files and code folders, PNG/JPG under 2 MB (lowercase, hyphens, no spaces, e.g. `r1-1-home-page.png`), PDF under 10 MB, or a view-only Figma or Penpot link inside .md

## 6. What to Commit

End of week checklist:
- [ ] `students/UX{n}/week8/session1-learning.md` with commit `W8.1 add learning note`
- [ ] `students/UX{n}/week8/session2-learning.md` with commit `W8.2 add learning note`
- [ ] `students/UX{n}/week8/session3-learning.md` with commit `W8.3 add learning note`
- [ ] `students/UX{n}/week8/session4-learning.md` with commit `W8.4 add learning note`
- [ ] R6.1 to R6.3 files
- [ ] P8.1 file
- [ ] C9.1, C9.2, S9.1 files
- [ ] P8.2 file
- [ ] S10.1, S10.2, S10.3 files
- [ ] F8.1 to F8.4 files
- [ ] JR2 file
- [ ] JR2 live skeleton page files (`index.html`, `styles.css` if used, `script.js` if used)
- [ ] Published GitHub Pages URL in the JR2 case study file
- [ ] One pull request for Week 8

Sprint 2 done when:
- [ ] 20 learning summaries
- [ ] 5 interviews, consented, anonymised, transcribed in part
- [ ] Self-critique with counted mistakes
- [ ] 5 usability sessions with severity-rated findings
- [ ] Findings report with confidence levels and one unresolved contradiction
- [ ] Journey map with every point attributed
- [ ] Finding-to-decision map, with an honest judgement list
- [ ] Redesigned flow and evidence-linked spec
- [ ] Post mortem
- [ ] Defense passed
- [ ] Reflection
- [ ] System released, debt updated
- [ ] 4 teardowns, 1 explainer, 40 drill entries
- [ ] JR2 done, with the external input it needs

If you are short on time, cut in this order for this week's commit: F8.2, F8.1, S10.2. These tasks are deferred, not removed. Deadline: before the Sprint 2 gate is closed. Record the deferred tasks in your Week 8 pull request, then complete them in a follow-up commit. They stay in the Sprint 2 done when list. Keep R6.1, R6.2, R6.3, P8.1, C9.1, C9.2, S9.1, Defense, P8.2.

Open one pull request for Week 8 with a clear title and link the task files in the description (see `../10-GitHub-For-Designers.md`).

Next: `../Design-Sprint-3/00-READ-FIRST.md`
