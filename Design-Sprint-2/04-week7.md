# Week 7 - Test

**Theme: usability testing with no budget, and the mid-sprint failure. Sprint 2, week 3 of 4.**

## Week at a Glance

| Task ID | Task name | Time | File you will commit |
|---|---|---|---|
| R5.1 | Test plan | 60 min | `students/UX{n}/week7/R5-1-test-plan.md` |
| R5.2 | Build what you will test | 60 min | `students/UX{n}/week7/R5-2-test-prototype.md` |
| R5.3 | Sessions 1 and 2 | 3 hr | `students/UX{n}/week7/R5-3-sessions-1-2.md` |
| R5.4 | Sessions 3, 4, 5 | 3 hr | `students/UX{n}/week7/R5-4-sessions-3-4-5.md` |
| R5.5 | Findings with severity | 60 min | `students/UX{n}/week7/R5-5-findings.md` |
| R5.6 | Fix list | 60 min | `students/UX{n}/week7/R5-6-fix-list.md` |
| X2 | Post mortem | 60 min | `students/UX{n}/week7/X2-post-mortem.md` |
| P7.1 | Revised research position | 60 min | `students/UX{n}/week7/P7-1-revised-position.md` |
| S8 | System update | 90 min | `system/docs/debt.md` and system states |
| F7.1 | Why session: bias | 30 min | `fundamentals/why-sessions/week07-bias.md` |
| F7.2 | Teardown: insurance claim | 30 min | `fundamentals/teardowns/07-insurance-claim.md` |
| F7.3 | Drill continues | 15 min | No file |

About 20 hours of work in this week.

## 1. What We Are Doing

This week you run a small usability test with five people. You write the plan, build a testable prototype, run the sessions, rate findings, and make a fix list. A mid-sprint constraint change lands, and you show what survives.

- Group 1 - Test plan and prototype: R5.1, R5.2
- Group 2 - Usability sessions: R5.3, R5.4
- Group 3 - Findings and fixes: R5.5, R5.6
- Group 4 - Constraint change: X2, P7.1
- Group 5 - System and fundamentals: S8, F7.1, F7.2, F7.3

## 2. Why We Are Doing It

In a real product design job in India, you often have no research budget and five busy users. You still need evidence. You need to write tasks, run sessions, and defend your findings.

This week matters for your project because testing tells you if your week 6 research is true in use. It matters for your portfolio because a case study with five sessions, severity ratings, and a clear fix list is stronger than a set of nice screens. The constraint change also matters. Real projects change in the middle. You need to show what survives.

## 3. What to Learn First

By the end of the week you can:

- Run a moderated usability study on five people
- Write tasks that test the design rather than your instructions
- Rate findings by severity and defend the rating
- Absorb a constraint change without abandoning your evidence

Core ideas to review first:

- A usability test is a planned session with tasks, success criteria, consent, and a no-help rule.
- Five users find most problems in one flow, for one user group, in formative testing. Formative testing means testing early to find problems. Report completion as a count, such as 3 out of 5. Do not treat it as a reliable population completion rate.
- A task is a goal. A route is a set of steps. Test goals, not routes.
- Observation is what happened. Interpretation is what you think it means. Keep them apart.
- Severity is 1 to 4. Confidence is high, medium, or low. Always show the denominator, for example 4 out of 5.
- A failure injection is a planned change from the admin. It tests what survives.

## 4. Where to Find Resources

Your week in order:

| Day | Source | What exactly | Time | Commit note |
|---|---|---|---|---|
| 1 | Rocket Surgery Made Easy, Krug | Ch. 1-4 | 45 min | `students/UX{n}/week7/session1-learning.md` |
| 1 | Don't Make Me Think | The usability testing chapter | 25 min | Same learning note |
| 1 | NNGroup | "Why You Only Need to Test with 5 Users" and then "Why You Only Need to Test with 5 Users: Revisited" | 20 min | Same learning note |
| 2 | Rocket Surgery Made Easy | Ch. 5-6, on running the session and taking notes | 30 min | `students/UX{n}/week7/session2-learning.md` |
| 2 | Your R4.2 | Your own interview self-critique. The same mistakes appear in usability testing. | 15 min | Same learning note |
| 3 | NNGroup | "Severity Ratings for Usability Problems" | 20 min | `students/UX{n}/week7/session3-learning.md` |
| 3 | Rocket Surgery | Ch. 7, on deciding what to fix | 25 min | Same learning note |
| 4 | Your five session note sets | Read in one sitting, without your earlier interpretation | 45 min | `students/UX{n}/week7/session4-learning.md` |
| 5 | Admin message | Failure injection arrives in the morning LEARN block | Morning block | No new file |
| 6 | System and fundamentals | S8, F7.1, F7.2, F7.3 | See tasks | Shared files |

Read both NNGroup articles. The second one qualifies the first. That qualification helps you answer the sample-size question in the defense.

Open your browser for reading and NNGroup. Open Figma for R5.2. Use one Figma file for Sprint 2: `SPRINT-2 UX{n}`. Put week 7 on one page. Do not make three separate Figma files for practice, system and delivery. Figma setup: see `../04-Tools-Setup.md` (Figma section). If the Figma file limit blocks you, use Penpot as backup: https://penpot.app/ (check the free plan before use). Use your phone for the R5.2 self-test.

Search keywords if you are stuck:

- moderated usability test plan
- usability task success criteria
- severity rating usability problems
- five users usability testing
- confidence in usability findings
- usability test no-help rule

## 5. Step-by-Step Guide

> All `students/...` paths in this week are inside your sprint folder (`Design-Sprint-N/`). Open a terminal in the repo root and use full paths.

Work in small steps. One task, one commit with all files listed for that task. See `../10-GitHub-For-Designers.md` for the Git steps. Use `students/UX{n}/week7/` for your week files. Use P1, P2 in notes. No real names, faces, phone numbers, or IDs. Allowed files: markdown (.md), PNG/JPG under 2 MB, PDF under 10 MB, small .html, .css and .js files (and a code folder when a task asks for code), and a view-only Figma or Penpot link inside a markdown file. Where this week names Figma, a Penpot equivalent and a view-only Penpot link are allowed. Do not commit .fig files, passwords, tokens, or real personal data. Use one Figma file per sprint: `SPRINT-2 UX{n}`, one page per week.

### Group 1 - Test plan and prototype

**Learning checkpoint 1:** Do the Day 1 reading. Commit `students/UX{n}/week7/session1-learning.md` with the message `W7: session 1 learning`.

#### Task - Test plan (ID `R5.1`)

##### 1. What We Are Doing

Write a test plan for a moderated usability test with five people. Define what you test, three tasks, success criteria, measures, the no-help rule, and consent.

##### 2. Why We Are Doing It

A plan stops you from deciding success after the session. It also keeps the test honest when you like a design. Five users can find most problems in one flow, for one user group, in formative testing. Report completion as a count, such as 3 out of 5. Do not treat it as a reliable population completion rate.

##### 3. What to Learn First

- A task is a goal, not a route.
- Success criteria are written before the session.
- The no-help rule needs a number of seconds.
- Observation is different from interpretation.

##### 4. Where to Find Resources

- Use the Day 1 sources in the table above.
- Use the NNGroup five-users articles.
- Browser only. Figma is not needed for this task.

##### 5. Step-by-Step Guide

1. Write one sentence: what you are testing. If it is "the design", make it more specific.
2. Write three tasks as goals with no route.
3. Order the tasks so an early failure does not block a later task.
4. For each task, write what counts as success before you run it.
5. Write what you will measure: completion, where they hesitate, what they say, and time.
6. Note that with five participants, time is directional and not a statistic.
7. Write your no-help rule with the number of seconds.
8. Write the consent step. Use the same standard as week 5.
9. Check that at least one task traces directly to a week 6 finding.
10. Derive each task and each success criterion from your own week 6 evidence. Do not copy a task from someone else. Write one line under each task naming the week 6 finding it comes from.

**How to think about it:** A task with a route tells the person what to click. A task with a goal tests the design.

**If you get stuck:** Read the R5.1 method again. Search "usability test plan task success criteria". Ask in Discord with a screenshot and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/R5-1-test-plan.md`
- [ ] What you are testing, in one specific sentence
- [ ] Three tasks, goals not routes, sensibly ordered, each traced to your own week 6 evidence
- [ ] Success criteria written before running anything
- [ ] Measures stated, with their limits acknowledged
- [ ] No-help rule written with a number of seconds
- [ ] At least one task traces directly to a week 6 finding
- [ ] Commit message: `R5.1: test plan with three tasks and success criteria`

#### Task - Build what you will test (ID `R5.2`)

##### 1. What We Are Doing

Build a mid-fidelity prototype that you can test with your three tasks.

##### 2. Why We Are Doing It

You need something testable. A clickable flow lets you see where people hesitate and fail. Failure paths matter because recovery is part of the design.

##### 3. What to Learn First

- Mid fidelity is enough. People should comment on flow, not colours.
- Failure paths must be clickable.
- Test your own prototype before you ask someone else.

##### 4. Where to Find Resources

- Open Figma. Use `SPRINT-2 UX{n}` and one page for week 7. Figma setup: see `../04-Tools-Setup.md` (Figma section).
- Use system components if your team has them.
- Use your phone for the self-test.

##### 5. Step-by-Step Guide

1. Open your `SPRINT-2 UX{n}` Figma file.
2. Create or open the week 7 page.
3. Choose what to test: a clickable Figma prototype of the current service flow, or your redesign of the two or three screens your findings point at.
4. Make the paths in your three tasks work.
5. Make the failure paths clickable.
6. Keep fidelity mid. Use system components.
7. Open the prototype on your phone.
8. Follow your own three tasks.
9. List any dead ends.
10. Fix the dead ends.
11. Copy a view-only Figma link.

**If you get stuck:** Check the prototype links again. Search "Figma prototype clickable link". Ask in Discord with a screenshot of the dead end and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/R5-2-test-prototype.md` with a view-only Figma link
- [ ] All three tasks completable in the prototype
- [ ] Failure paths clickable
- [ ] You have run it yourself on a phone and fixed the dead ends
- [ ] Mid fidelity, using system components
- [ ] Figma link
- [ ] Commit message: `R5.2: test prototype with clickable failure paths`

### Group 2 - Usability sessions

**Learning checkpoint 2:** Read Rocket Surgery ch. 5-6 and your R4.2. Commit `students/UX{n}/week7/session2-learning.md` with the message `W7: session 2 learning`.

#### Task - Sessions 1 and 2 (ID `R5.3`)

##### 1. What We Are Doing

Run the first two usability sessions with consent. Take notes in four columns.

##### 2. Why We Are Doing It

The first two sessions show if the test plan works. They also give you early evidence without letting you change the prototype between people.

##### 3. What to Learn First

- A task completed with help is not a completed task.
- Notes must separate what happened from what you think.
- Do not change the prototype between sessions.

##### 4. Where to Find Resources

- Use Rocket Surgery ch. 5-6.
- Use your R4.2 self-critique.
- Use your test plan from R5.1.

##### 5. Step-by-Step Guide

1. Check consent before you start.
2. Run session 1.
3. Take notes in four columns: what they did, what they said, where they hesitated, where they failed.
4. Do not help for the number of seconds you wrote down.
5. When you help, log a help event with when and what you said.
6. Keep interpretation out of the session notes.
7. Do not change the prototype between sessions.
8. Run session 2 with the same protocol.
9. Use P1, P2 labels in notes. No real names, faces, phone numbers, or IDs.

**If you get stuck:** Read the four-column note example again. Search "usability test note taking four columns". Ask in Discord with your notes redacted and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/R5-3-sessions-1-2.md`
- [ ] Two sessions, consented, documented in anonymised written notes
- [ ] Four-column notes
- [ ] Every help event logged with when and what you said
- [ ] Zero interpretation
- [ ] Prototype unchanged
- [ ] Commit message: `R5.3: sessions 1 and 2 with four-column notes`

**Learning checkpoint 3:** Read NNGroup "Severity Ratings for Usability Problems" and Rocket Surgery ch. 7. Commit `students/UX{n}/week7/session3-learning.md` with the message `W7: session 3 learning`.

#### Task - Sessions 3, 4, 5 (ID `R5.4`)

##### 1. What We Are Doing

Run the last three usability sessions with the same protocol. Write down your predictions before sessions 4 and 5.

##### 2. Why We Are Doing It

By session 4 you will be able to predict what happens next. Write that prediction down before the session. It is a hypothesis, and the session shows whether it holds. Being consistently right is a sign the pattern is real.

##### 3. What to Learn First

- Same protocol for every session.
- Predictions are hypotheses; later observations provide evidence.
- The prototype stays unchanged.

##### 4. Where to Find Resources

- Use the Day 3 sources in the table above.
- Use your R5.1 plan and R5.3 notes.

##### 5. Step-by-Step Guide

1. Run session 3 with the same protocol.
2. Keep the prototype unchanged.
3. Before session 4, write what you expect to happen.
4. Run session 4.
5. Write down whether your prediction was right.
6. Before session 5, write what you expect to happen.
7. Run session 5.
8. Write down whether your prediction was right.
9. Keep the four-column notes for every session.

**If you get stuck:** Compare your notes to the R5.3 columns. Search "usability test prediction notes". Ask in Discord with one anonymised note and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/R5-4-sessions-3-4-5.md`
- [ ] Three sessions, consented, documented in anonymised written notes
- [ ] Four-column notes for each session
- [ ] Predictions written before sessions 4 and 5
- [ ] Every help event logged
- [ ] Prototype unchanged
- [ ] Commit message: `R5.4: sessions 3 to 5 with predictions`

### Group 3 - Findings and fixes

**Learning checkpoint 4:** Read all five sets of session notes in one sitting, without your earlier interpretation. Write three lines: what all five did the same, what only one did, and which week 6 interview findings the testing contradicted. Commit `students/UX{n}/week7/session4-learning.md` with the message `W7: session 4 learning`.

#### Task - Findings with severity (ID `R5.5`)

##### 1. What We Are Doing

Turn the five sessions into one findings table with severity and confidence.

##### 2. Why We Are Doing It

A finding with no denominator is a story. A finding with a denominator is evidence. Severity and confidence help you defend the fix list.

##### 3. What to Learn First

- Severity: 1 cosmetic, 2 minor with workaround, 3 major task failed, 4 catastrophic data or money lost.
- Confidence: high if 4 or 5 of 5 and consistent with interviews; medium if 3 of 5 or if interviews and testing disagree; low if 1 or 2 of 5.
- Observation and interpretation are separate columns.

##### 4. Where to Find Resources

- Use your five sets of session notes.
- Use NNGroup "Severity Ratings for Usability Problems".
- Use the Day 4 learning note.

##### 5. Step-by-Step Guide

1. Make one row per issue.
2. Add columns: what happened, n out of 5, severity 1-4, what it cost the user, your interpretation, and confidence.
3. Assign severity 1 to 4.
4. Assign confidence high, medium, or low with a reason.
5. Include findings that disagree with your week 6 hypothesis. Especially those.
6. Keep observation separate from interpretation.
7. Check that every issue across all five sessions is in the table.

**How to think about it:** Ask "How many out of five?" before you ask "Do I like this finding?"

**If you get stuck:** Read the severity scale again. Search "severity ratings usability problems". Ask in Discord with one table row and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/R5-5-findings.md`
- [ ] Every issue across all five sessions
- [ ] Denominators throughout
- [ ] Severity and confidence both assigned, with reasons
- [ ] Observation separated from interpretation
- [ ] Report any findings that contradict an earlier belief; if none do, state that
- [ ] Commit message: `R5.5: findings table with severity and confidence`

#### Task - Fix list (ID `R5.6`)

##### 1. What We Are Doing

Write a ranked fix list for the serious findings.

##### 2. Why We Are Doing It

A fix list turns findings into decisions. A good list also says what you will not fix. That shows judgement.

##### 3. What to Learn First

- Every severity 3 and 4 needs a fix or a stated deferral.
- Each fix names what gets worse.
- Rank by severity, then confidence. Use estimated effort to break ties.

##### 4. Where to Find Resources

- Use your R5.5 findings table.
- Use Rocket Surgery ch. 7.
- Use your system components if a fix needs one.

##### 5. Step-by-Step Guide

1. List every severity 3 and 4 issue.
2. Write a proposed fix for each one.
3. For each fix, write what changes.
4. Write a build cost estimate. Your estimate is fine.
5. Write what gets worse.
6. Rank by severity, then confidence. Use estimated effort to break ties.
7. Do not rank by what you find interesting.
8. List what you are not fixing and why.
9. Show the ranking method.

**How to think about it:** A fix list with nothing deferred is not a prioritised list.

**If you get stuck:** Check that every sev 3 and 4 has a row. Search "usability fix list prioritisation". Ask in Discord with your ranking table and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/R5-6-fix-list.md`
- [ ] Every sev 3 and 4 has a fix or a stated deferral
- [ ] Each fix names what gets worse
- [ ] Ranked, with the ranking method shown
- [ ] Deferrals justified
- [ ] Commit message: `R5.6: ranked fix list with deferrals`

**Critique - 90 minutes**

Present three findings with their confidence levels. The critique focus: is the confidence level honest, or is the finding you like most given more confidence than its denominator supports?

**Whiteboard why - 15 minutes**

No notes. Draw your research plan from memory. State your three questions. Answer what five participants can and cannot support.

### Group 4 - Constraint change

A failure injection is a planned change from the admin. It lands during the morning LEARN block. In this sprint it is likely to invalidate part of your research, not just your design. That is deliberate. It is the most common thing that happens to real research.

#### Task - Post mortem (ID `X2`)

##### 1. What We Are Doing

Write a post mortem on the constraint change.

##### 2. Why We Are Doing It

The important skill is separating what survives from what does not. Findings about how people think often survive a change in requirements. Findings about a specific screen often do not.

##### 3. What to Learn First

- What changed, in facts.
- What was invalidated, by name.
- What survives, with the reason.

##### 4. Where to Find Resources

- Use the admin message.
- Use your R5.5 findings and R5.6 fix list.
- Use `students/UX{n}/week7/X2-post-mortem.md` as the file.

##### 5. Step-by-Step Guide

1. Write what changed in one factual sentence.
2. List what it invalidated. Be specific: which findings, which participants' relevance, which tasks.
3. List what survives and why.
4. Name an earlier decision that would have made this cheaper.
5. Write one concrete change to how you work.
6. Name one finding from your own sessions that survives, and one that does not. Quote the session note, the participant label, and the reason for each. Do not use an example from someone else.

**How to think about it:** Being able to separate these two is the skill being tested.

**If you get stuck:** Read the admin message again. Search "design research post mortem constraint change". Ask in Discord with the change note and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/X2-post-mortem.md`
- [ ] What changed, factually
- [ ] What was invalidated, named specifically
- [ ] What survives, with the reason it survives
- [ ] Your own surviving finding and your own invalidated finding, each tied to a session note
- [ ] A named earlier decision that would have made this cheaper
- [ ] One concrete change to how you work
- [ ] Commit message: `X2: post mortem for constraint change`

#### Task - Revised research position (ID `P7.1`)

##### 1. What We Are Doing

Restate your research position under the new constraint.

##### 2. Why We Are Doing It

You need a clear record of what is still valid, what needs re-testing, and what is invalid. This protects your evidence and your portfolio story.

##### 3. What to Learn First

- Three labels: still valid, needs re-testing, invalid.
- The fix list must change with the findings.
- State what you give up.

##### 4. Where to Find Resources

- Use X2.
- Use your R5.5 findings and R5.6 fix list.
- Use the new constraint from the admin.

##### 5. Step-by-Step Guide

1. Restate your findings under the new constraint.
2. Mark each finding as still valid, needs re-testing, or invalid.
3. Update your fix list.
4. State what you would do with two more days.
5. Put that in priority order.
6. State what you are giving up instead.

**How to think about it:** A clear "not now" is part of good research work.

**If you get stuck:** Read X2 again. Search "research plan change constraint". Ask in Discord with your labels and what you tried.

##### 6. What to Commit

- [ ] `students/UX{n}/week7/P7-1-revised-position.md`
- [ ] `students/UX{n}/week7/R5-6-fix-list.md`, updated for the new constraint
- [ ] Every finding classified into the three categories
- [ ] Fix list updated
- [ ] What you would do with more time, stated as a priority order
- [ ] What you are giving up, named
- [ ] One commit with both files: `P7.1: revised research position after change`

### Group 5 - System and fundamentals

#### Task - System update (ID `S8`)

##### 1. What We Are Doing

Update the system with the states your testing exposed. Review one peer's contribution. Update the debt file.

##### 2. Why We Are Doing It

If participants got stuck somewhere the system has no component for, that is a system gap. The system must learn from testing.

##### 3. What to Learn First

- A system gap is a missing component or state that made the test fail.
- Debt is a written note of known gaps.
- If your team has no Figma library, share by view-only link and a markdown description of the states.

##### 4. Where to Find Resources

- Use your R5.5 findings.
- Use `system/docs/debt.md`.
- Use Figma for the system state. Figma setup: see `../04-Tools-Setup.md` (Figma section). Keep one file per sprint. Do not make three separate Figma files.

##### 5. Step-by-Step Guide

1. List the states your testing exposed.
2. Check if the system has a component for each state.
3. S8.1: Add the missing states to the system, or write a clear system gap note.
4. S8.2: Review one peer's contribution and leave one clear comment.
5. S8.3: Update `system/docs/debt.md` with anything this sprint has added.
6. If your team has no library, share the state as a view-only Figma or Penpot link and write a markdown description of each state. Token export is deferred to week 15, when tokens are taught.
7. Keep the shared system in one team library file only if the admin or Education plan allows libraries.

**If you get stuck:** Read the system gap note again. Search "design system missing state". Ask in Discord with a screenshot and what you tried.

##### 6. What to Commit

- [ ] `system/docs/debt.md` updated
- [ ] System states added or logged
- [ ] One peer review comment
- [ ] Shared view-only link or markdown state description if needed
- [ ] Commit message: `S8: add test states and update debt`

#### Task - Why session: bias (ID `F7.1`)

##### 1. What We Are Doing

Do the why session on bias. Cover confirmation bias, anchoring, the framing effect, and social desirability bias.

##### 2. Why We Are Doing It

Bias changes what you hear and what you record. This week you test with five people, so bias can decide the findings.

##### 3. What to Learn First

- Confirmation bias: you look for evidence you already believe.
- Anchoring: the first number or idea pulls later judgement.
- Framing effect: the way a question is worded changes the answer.
- Social desirability bias: people say what makes them look good.

##### 4. Where to Find Resources

- Use the cohort's own interview notes from this fortnight.
- Write to `fundamentals/why-sessions/week07-bias.md`.

##### 5. Step-by-Step Guide

1. Open the why session notes file.
2. Write one example from the cohort interviews for each bias.
3. For each example, write how it could affect a usability finding.
4. Add one rule you will use to reduce that bias.
5. Save the file.

**If you get stuck:** Read the four bias names again. Search "confirmation bias anchoring framing social desirability". Ask in Discord with one example and what you tried.

##### 6. What to Commit

- [ ] `fundamentals/why-sessions/week07-bias.md`
- [ ] Four biases covered
- [ ] Each has a cohort example
- [ ] Each has a usability test risk
- [ ] One rule per bias
- [ ] Commit message: `F7.1: bias why session with cohort examples`

#### Task - Teardown: insurance claim (ID `F7.2`)

##### 1. What We Are Doing

Do a teardown of an insurance claim submission flow.

##### 2. Why We Are Doing It

Insurance claims are a high-cost flow. Small usability errors can lose money or data. The patterns connect to this week's severity and recovery work.

##### 3. What to Learn First

- A teardown is a structured review of a flow, screen by screen.
- Look for states, errors, recovery, and consent.

##### 4. Where to Find Resources

- Use a public insurance claim flow.
- Write to `fundamentals/teardowns/07-insurance-claim.md`.

##### 5. Step-by-Step Guide

1. Open the public insurance claim flow.
2. Do not log in, register, or submit a claim.
3. List the steps in the flow.
4. Note the states: empty, error, loading, success, failure.
5. Note one good pattern and one risk.
6. Save the teardown.

**If you get stuck:** Read the state list again. Search "insurance claim flow teardown UX". Ask in Discord with one screenshot and what you tried.

##### 6. What to Commit

- [ ] `fundamentals/teardowns/07-insurance-claim.md`
- [ ] Steps listed
- [ ] States noted
- [ ] One good pattern
- [ ] One risk
- [ ] No real data used
- [ ] Commit message: `F7.2: insurance claim teardown`

#### Task - Drill continues (ID `F7.3`)

##### 1. What We Are Doing

Do the next exercise in your fundamentals drill series. This continues the drill you were taught in the earlier weeks.

##### 2. Why We Are Doing It

The drill builds one skill by short repetition. Fifteen minutes a week keeps the skill sharp. It is practice, not new theory.

##### 3. What to Learn First

- The drill uses the same steps you practised in the earlier weeks.
- Speed is not the goal. Correct steps are the goal.
- Write down the exercise and the date.

##### 4. Where to Find Resources

- Open your last drill note in `fundamentals/` and find the next exercise in the same series.
- If you cannot find it, ask in Discord: "which drill exercise comes after the one I did last week?"
- No new sources this week.

##### 5. Step-by-Step Guide

1. Open your last drill note in `fundamentals/`.
2. Find the next exercise in the same drill series.
3. Set a timer for 15 minutes.
4. Do the exercise.
5. Write one line: what you did and what was hard.
6. Stop at 15 minutes.

**If you get stuck:** Read your last drill note again. Check the earlier weeks' files in `fundamentals/` for the drill list. Ask in Discord with a screenshot of your last drill note and what you tried.

##### 6. What to Commit

- [ ] No commit required. This drill is practice only this week.
- [ ] Keep your one-line note locally for yourself.

## 6. What to Commit

End of week checklist:

- [ ] Four learning summaries: `students/UX{n}/week7/session1-learning.md` to `session4-learning.md`. The constraint-change record is `X2-post-mortem.md`.
- [ ] R5.1 to R5.6 complete
- [ ] Five usability sessions run
- [ ] X2 post mortem
- [ ] P7.1 revised research position
- [ ] Whiteboard why attempted
- [ ] Critique attended
- [ ] S8 system update done
- [ ] F7.1 and F7.2 done
- [ ] Everything anonymised. Use P1, P2. No real names, faces, phone numbers, or IDs.
- [ ] Allowed file types only: markdown, PNG/JPG under 2 MB, PDF under 10 MB, small .html, .css and .js files (and a code folder when a task asks for code), or a view-only Figma or Penpot link inside a markdown file
- [ ] No .fig files, passwords, tokens, or real personal data

If you are short on time, cut in this order: F7.2 teardown, then S8.2 peer review, then the extra notes in R5.5 while keeping the table. Do not cut the five sessions or the consent step.

When the week is done, open one pull request from your branch. See `../10-GitHub-For-Designers.md`.

Next: `05-week8.md`
