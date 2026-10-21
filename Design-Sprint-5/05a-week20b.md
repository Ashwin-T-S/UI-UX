# Week 20b - Agent UX lab

**Theme: your capstone now has an AI agent in it. This week you design the controls around it, not just the screen.**

## Week at a Glance

| Task ID | Task name | Time | File you will commit |
|---|---|---|---|
| A5.1 | List the agent actions in your capstone | 45 min | `students/UX{n}/week20b/A5-1-agent-actions.md` |
| A5.2 | Autonomy level and scope limit | 45 min | `students/UX{n}/week20b/A5-2-autonomy.md` |
| A5.3 | Intent preview and confirmation gate | 60 min | `students/UX{n}/week20b/A5-3-preview-and-confirm.md` |
| A5.4 | Reasoning, confidence and failure states | 60 min | `students/UX{n}/week20b/A5-4-reasoning-and-failure.md` |
| A5.5 | Undo and audit trail | 45 min | `students/UX{n}/week20b/A5-5-undo-and-audit.md` |
| A5.6 | Escalate to a human | 30 min | `students/UX{n}/week20b/A5-6-escalation.md` |
| A5.7 | Prototype and test with 1 person | 90 min | `students/UX{n}/week20b/A5-7-prototype-test.md` plus a view-only Figma or Penpot link inside it |

About 7 hours of work in this week.

## 1. What We Are Doing

You take one screen or flow from your capstone and add an AI agent to it. Then you design the parts that keep the person in control: what the agent says before it acts, when it asks first, how you stop it, and how you undo it. All seven tasks together are lab L-AI7.

- Group 1 - Map the agent: A5.1, A5.2
- Group 2 - Design the controls: A5.3, A5.4, A5.5, A5.6
- Group 3 - Prototype and test: A5.7

## 2. Why We Are Doing It

This lab helps you practise controls for AI actions and explain your design decisions in your portfolio.

## 3. What to Learn First

By the end of the week you can:

- List every action an AI agent could take in your capstone.
- Set a clear limit on what the agent may do alone.
- Show a person what the agent is about to do, before it does it.
- Show why the agent acted, and how sure it is.
- Design undo, a readable log, and a path to a human.
- Test the flow with one person and name three changes.

Core ideas to review first:

- **Control and consent.** The person must know what will happen and agree to it, or be able to stop it.
- **Risk level.** Low risk actions can run alone. Money, deleting, sending to other people, and health decisions need a stop.
- **Reversibility.** Ask "can this be undone in one click". If not, it needs a gate.
- **Visible state.** The person must always know if the agent is waiting, working, done, or stuck.
- **Honest limits.** Say what the agent cannot do, and hand over to a human.

### AI agent glossary, 8 words

1. **Agent** - software that takes actions toward a goal, not only answers questions.
2. **Agentic AI** - AI that plans several steps and then acts on them with some freedom.
3. **Intent preview** - a short plain summary of what the agent is about to do, shown before it does it.
4. **Autonomy level** - how much the agent may do alone, from "suggest only" to "act and tell me".
5. **Confirmation gate** - a point where the agent waits for the person's approval before a risky action.
6. **Streaming state** - the visible "working now" state while the agent is doing a job.
7. **Audit trail** - a readable list of what the agent did, when, and with what result.
8. **Escalation** - handing the task to a human when the agent is unsure or the risk is high.

## 4. Where to Find Resources

Your week in order:

| Order | What to learn | Exact source | Time |
|---|---|---|---|
| 1 | What agentic AI changes for design | Smashing Magazine, "Designing For Agentic AI: Practical UX Patterns For Control, Consent, And Accountability", Feb 2026. Search the title on smashingmagazine.com. Check before use. | 30 min |
| 2 | The control and consent patterns | The same article. Check before use. | 20 min |
| 3 | Human control, confirmation, error recovery | https://www.nngroup.com/ - search directly for "AI", "confirmation" and "error recovery". Pick the top two results. No fixed article. | 30 min |
| 4 | Background reading, optional | https://web.dev/learn/ai - browse the index, pick two items that fit your capstone. | 20 min |
| 5 | Optional reading only | Dev Mode MCP server guide, https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server . Most sources say it needs a paid Dev Mode seat. Read only if you are curious. | skip if busy |

**Tools to open this week:**

- **Figma free plan** (main tool): your sprint file `SPRINT-5 UX{n}`, plus one new page for this week. Setup guide: the Figma section of `../04-Tools-Setup.md`.
- **Penpot** (backup) if the Figma 3-file limit blocks you: https://penpot.app/ . Setup guide: the Penpot section of `../04-Tools-Setup.md`.
- **Browser**: for the article and NN/g.
- **FigJam**: only if you truly need a messy map. It counts toward your Figma limits. Use a markdown list instead when you can.
- **Loom free** if you want to record the test. Check the free limit before use.

**Search keywords when you are stuck:**

- "agentic AI UX patterns"
- "AI autonomy levels design"
- "confirmation dialog before AI action"
- "AI error recovery UX"
- "audit log design pattern"
- "human in the loop escalation UX"

## 5. Step-by-Step Guide

> All `students/...` paths in this week are inside your sprint folder (`Design-Sprint-N/`). Open a terminal in the repo root and use full paths.

One task, one commit with all files listed for that task. See `../10-GitHub-For-Designers.md`.

Sprint 5 gives you little step-by-step support, so keep every task small. A rough markdown file and a rough Figma frame are enough this week. Do not polish.

### Group 1 - Map the agent

#### Task - List the agent actions in your capstone (ID `A5.1`)

##### 1. What We Are Doing

Pick one agent idea for your capstone. Then write every action that agent could take, alone or with the person.

##### 2. Why We Are Doing It

You cannot design controls for actions you have not listed. Teams write this list before any screen, because it shows where the risk is.

##### 3. What to Learn First

- Read the opening of the Smashing article (check before use), and note what the author says changes when software acts.

##### 4. Where to Find Resources

- Smashing Magazine, "Designing For Agentic AI..." (check before use).
- NN/g search: https://www.nngroup.com/

##### 5. Step-by-Step Guide

1. Open your capstone brief.
2. Write one sentence: "The agent exists to ______."
3. List every action it could take. One line each, plain verbs.
4. Mark each action with a type: read, write, send, pay, delete, or other.
5. Mark each action as reversible or not reversible.
6. Mark the actions a person would be angry about if they happened by surprise.
7. Save the list as `A5-1-agent-actions.md`.

If you get stuck: re-read your capstone problem statement, search "agentic AI UX patterns" on NN/g, or post your one-sentence agent purpose in Discord and ask if it is clear.

**How to think about it:** the list is not a feature list. It is a risk list. Keep only actions that support your capstone problem. Explain the possible harm of each action.

##### 6. What to Commit

- [ ] `students/UX{n}/week20b/A5-1-agent-actions.md`
- [ ] One sentence on what the agent is for
- [ ] Every action listed, with type and reversible/not reversible
- [ ] Risky actions marked
- Commit message: `A5.1: list agent actions for my capstone`

#### Task - Autonomy level and scope limit (ID `A5.2`)

##### 1. What We Are Doing

You decide how much freedom the agent gets for each action, and what it may never touch.

##### 2. Why We Are Doing It

"Smart AI" is not a design decision. A stated autonomy level is. It shows a hiring team that you can set a boundary and defend it.

##### 3. What to Learn First

- The four levels, defined by you in one line each:
  1. Suggest only: the agent says what it would do, the person does it.
  2. Ask first: the agent asks, then acts.
  3. Act and report: the agent acts, then tells the person, with undo.
  4. Act silently: no message. Use only for low risk, reversible actions.

##### 4. Where to Find Resources

- The Smashing article, autonomy and consent parts (check before use).
- NN/g search: "AI autonomy" and "human control".

##### 5. Step-by-Step Guide

1. Open `A5-1-agent-actions.md`.
2. Give each action a level from 1 to 4.
3. Write one reason for each level, tied to risk and reversibility.
4. Write the scope limit: three things the agent may never do in your product.
5. Check that no risky action sits at level 3 or 4.
6. Save as `A5-2-autonomy.md`.

If you get stuck: use the rule "if it costs money, touches another person, or cannot be undone, it is level 1 or 2". Search "AI autonomy levels design" if you need another example.

**How to think about it:** the level is a promise to the user. If you cannot write the reason in one line, the level is wrong.

##### 6. What to Commit

- [ ] `students/UX{n}/week20b/A5-2-autonomy.md`
- [ ] Every action from A5.1 has a level and a one-line reason
- [ ] A scope limit with three "never" items
- Commit message: `A5.2: set autonomy levels and scope limit`

### Group 2 - Design the controls

#### Task - Intent preview and confirmation gate (ID `A5.3`)

##### 1. What We Are Doing

You design the moment before the agent acts: a plain summary of what it will do, and a point where the agent waits for the person's approval for risky actions.

##### 2. Why We Are Doing It

Most AI complaints start here. The person did not know what was coming. A preview and a gate fix that in one screen.

##### 3. What to Learn First

- A good preview names the action, the target, and the effect. Example shape: "I will book the 3pm slot for you and send a message to the clinic." No jargon.

##### 4. Where to Find Resources

- Smashing article, intent preview and confirmation parts (check before use).
- NN/g search: "confirmation dialog".

##### 5. Step-by-Step Guide

1. Open your sprint file `SPRINT-5 UX{n}` in Figma, or open Penpot if the Figma 3-file limit blocks you.
2. Add a new page for this week, for example `W20B`.
3. Pick the two riskiest actions from A5.2.
4. Draw a small frame for each: the agent's preview text, and two buttons, confirm and cancel.
5. Write the preview text in plain words. Name the action, the target, and the effect.
6. Remove any word the person would not say out loud.
7. Export one PNG under 2 MB, named `a5-3-preview.png`.
8. Write `A5-3-preview-and-confirm.md` with the two texts and a view-only Figma link or a view-only Penpot link.

If you get stuck: read your preview out loud. If it sounds like a system message, rewrite it shorter. Search "confirmation dialog before AI action" for examples.

##### 6. What to Commit

- [ ] `students/UX{n}/week20b/A5-3-preview-and-confirm.md`
- [ ] `students/UX{n}/week20b/a5-3-preview.png` (under 2 MB)
- [ ] A view-only Figma link or a view-only Penpot link inside the markdown file
- [ ] Preview text for two risky actions, plus confirm and cancel buttons
- Commit message: `A5.3: add intent preview and confirmation gate`

#### Task - Reasoning, confidence and failure states (ID `A5.4`)

##### 1. What We Are Doing

You design how the agent shows why it acted, how sure it is, and what it says when it fails.

##### 2. Why We Are Doing It

People trust a system more when it admits limits. They trust it less when it sounds certain and is wrong. Failure states are the part beginners skip and reviewers look for first.

##### 3. What to Learn First

- A "why" note is one or two short sentences, not a log.
- Confidence is better as words than a fake number. "I found two matching records" is honest. "97% sure" is not, unless you can prove it.
- Three failure types to design: the agent did not understand, it did part of the job, it did the wrong thing.

##### 4. Where to Find Resources

- Smashing article, show reasoning and error recovery parts (check before use).
- NN/g search: "error recovery" and "AI trust".

##### 5. Step-by-Step Guide

1. In your `W20B` page in Figma or Penpot, add a small frame for the "why" note, placed near the agent's result.
2. Write the note in two sentences maximum.
3. Write the confidence line in plain words, for example "I found 1 match. There may be more."
4. Draw three small frames, one per failure type.
5. In each failure frame, show what happened, what the person can do next, and the path to a human.
6. Export one PNG under 2 MB, named `a5-4-failure-states.png`.
7. Write `A5-4-reasoning-and-failure.md` with the texts and a view-only Figma link or a view-only Penpot link.

If you get stuck: take one real error you have seen in any app, and copy its structure, not its words. Search "AI error recovery UX" for more examples.

**How to think about it:** write the failure screen before the success screen. Check the failure screen alongside confirmation, stopping, undo, and human support.

##### 6. What to Commit

- [ ] `students/UX{n}/week20b/A5-4-reasoning-and-failure.md`
- [ ] `students/UX{n}/week20b/a5-4-failure-states.png` (under 2 MB)
- [ ] A view-only Figma link or a view-only Penpot link inside the markdown file
- [ ] A two-sentence "why" note, a confidence line, three failure frames with a next step
- Commit message: `A5.4: add reasoning, confidence and failure states`

#### Task - Undo and audit trail (ID `A5.5`)

##### 1. What We Are Doing

You design a way to take back what the agent did, and a short readable list of everything it did.

##### 2. Why We Are Doing It

Undo turns a scary feature into a usable one. A visible log answers "what happened while I was away" and it is the first thing support teams ask for.

##### 3. What to Learn First

- Undo needs a time window and a limit. Say what can be undone and what cannot, for example "I cannot unsend a message that was already delivered."

##### 4. Where to Find Resources

- Smashing article, accountability and audit parts (check before use).
- NN/g search: "undo" and "audit log".

##### 5. Step-by-Step Guide

1. Pick two actions from A5.2 that need undo.
2. Write the undo window for each, for example "10 seconds" or "until you close this page".
3. Write one line for actions that cannot be undone, and what the person should do instead.
4. Design the log row: time, action, target, result, and an undo link where it applies.
5. Draw the log as a short list in your `W20B` page in Figma or Penpot, five rows maximum.
6. Export one PNG under 2 MB, named `a5-5-audit-trail.png`.
7. Write `A5-5-undo-and-audit.md` with the texts and a view-only Figma link or a view-only Penpot link.

If you get stuck: look at the "recent activity" screen in any tool you use daily, and copy the row structure. Search "audit log design pattern" if you need another view.

##### 6. What to Commit

- [ ] `students/UX{n}/week20b/A5-5-undo-and-audit.md`
- [ ] `students/UX{n}/week20b/a5-5-audit-trail.png` (under 2 MB)
- [ ] A view-only Figma link or a view-only Penpot link inside the markdown file
- [ ] Undo window for two actions, one "cannot undo" line, a log row with five fields
- Commit message: `A5.5: add undo and audit trail`

#### Task - Escalate to a human (ID `A5.6`)

##### 1. What We Are Doing

You design the exit: when the agent stops and hands the task to a real person.

##### 2. Why We Are Doing It

Some users will always want a human, and some cases must go to one. A product with no exit is a product that traps people. In India, services like banking and government portals always need a human path.

##### 3. What to Learn First

- Three moments to escalate: the agent is unsure, the cost of a mistake is high, the person asks for a human.

##### 4. Where to Find Resources

- Smashing article, escalation parts (check before use).
- NN/g search: "human in the loop".

##### 5. Step-by-Step Guide

1. List your three escalation triggers in one line each.
2. Design the handover screen: what happened, what the person gets next, and the wait time in plain words.
3. Write what the agent passes to the human, in one short list.
4. Add one line so the person can ask for a human at any point.
5. Write `A5-6-escalation.md` with the texts and a view-only Figma link or a view-only Penpot link.

If you get stuck: use a chat support handoff you have seen, and copy the order of information, not the design. Search "escalation to human UX" if you need another example.

##### 6. What to Commit

- [ ] `students/UX{n}/week20b/A5-6-escalation.md`
- [ ] A view-only Figma link or a view-only Penpot link inside the markdown file
- [ ] Three triggers, a handover screen description, the list passed to the human
- Commit message: `A5.6: add escalation to a human`

### Group 3 - Prototype and test

#### Task - Prototype and test with 1 person (ID `A5.7`)

##### 1. What We Are Doing

You join the pieces into one short flow and test it with one person. Then you list three changes to make next week.

##### 2. Why We Are Doing It

A flow that was never tested is a guess. One test finds the obvious problem, and it takes 90 minutes, not a week.

##### 3. What to Learn First

- A test needs a task, not an opinion. Say "the agent wants to send this message. Show me what you would do." Then stay quiet.
- A streaming state shows the agent is waiting, working, or stopped. The stopped state must say why it stopped.
- A trust line shows the basis and the limits of a result, in plain words.
- Progressive autonomy lets the person increase or reduce what the agent may do next.

##### 4. Where to Find Resources

- Your own notes from A5.3 to A5.6.
- Loom free if you record the session. Check the free limit before use.
- Figma prototyping basics, in the Figma section of `../04-Tools-Setup.md`. If you use Penpot, use the Penpot section.

##### 5. Step-by-Step Guide

1. In your `W20B` page in Figma or Penpot, link the screens into one short flow, four or five steps.
2. Add three small frames to the flow: waiting, working, and stopped. The stopped frame must say why the agent stopped.
3. Add a trust line under the result. It names the basis of the result and one limit, for example "Based on your last booking. I cannot check real time."
4. Add one control that lets the person increase or reduce the agent's autonomy for the next action. This is progressive autonomy.
5. Ask one person to test. Call them P1 in your notes. Never write a real name.
6. Ask for consent to take notes. Do not record the face.
7. Give the task in one sentence.
8. Watch where P1 stops.
9. Write down each stopping point as it happens.
10. Ask three questions at the end: what did the agent just do, how did you feel, what would you change.
11. Write three changes you will make next week, in order of importance.
12. Write `A5-7-prototype-test.md` with the test notes and a view-only Figma link or a view-only Penpot link.
13. Create `students/UX{n}/week20b/L-AI7-agent-ux.md` with one heading and seven short lines, one for each task.
14. Link the seven task files from that page.
15. Set the Figma link to "anyone with the link can view". If you use Penpot, set the Penpot link to view only.

If you get stuck: test with a friend who is not a designer and give no hints. Re-read `A5-3-preview-and-confirm.md` and check if your preview text was the problem. Post the three changes in Discord and ask if they are the right three.

##### 6. What to Commit

- [ ] `students/UX{n}/week20b/A5-7-prototype-test.md`
- [ ] `students/UX{n}/week20b/L-AI7-agent-ux.md`, with links to the seven task files
- [ ] A view-only Figma link or a view-only Penpot link inside the markdown file
- [ ] Notes from one test, person coded as P1
- [ ] Three changes, in order
- [ ] Waiting, working, and stopped frames, a trust line, and an autonomy control
- Commit message: `A5.7: prototype and test the agent flow with one person`

## 6. What to Commit

End of week checklist:

- [ ] `students/UX{n}/week20b/A5-1-agent-actions.md`
- [ ] `students/UX{n}/week20b/A5-2-autonomy.md`
- [ ] `students/UX{n}/week20b/A5-3-preview-and-confirm.md`
- [ ] `students/UX{n}/week20b/a5-3-preview.png`
- [ ] `students/UX{n}/week20b/A5-4-reasoning-and-failure.md`
- [ ] `students/UX{n}/week20b/a5-4-failure-states.png`
- [ ] `students/UX{n}/week20b/A5-5-undo-and-audit.md`
- [ ] `students/UX{n}/week20b/a5-5-audit-trail.png`
- [ ] `students/UX{n}/week20b/A5-6-escalation.md`
- [ ] `students/UX{n}/week20b/A5-7-prototype-test.md`
- [ ] `students/UX{n}/week20b/L-AI7-agent-ux.md`, one short page that links the seven files above
- [ ] All Figma or Penpot links are view-only and written inside a markdown file
- [ ] All images are PNG or JPG, under 2 MB, lowercase, with hyphens
- [ ] No real names, faces, phone numbers or IDs anywhere. Use P1, P2
- [ ] No `.fig` files, no passwords, no tokens
- [ ] Seven commits, each starting with the task ID

Allowed file types in this folder: markdown (`.md`), PNG or JPG under 2 MB, PDF under 10 MB, and a view-only Figma link or a view-only Penpot link inside a markdown file.

If you are short on time, cut in this order:

1. The audit trail screen. Write the five fields as a markdown list instead.
2. The streaming-state frame: waiting, working, stopped. Replace it with a written description.
3. The prototype. Keep two screens, the preview and the failure, and test those.

Never cut: the test with one person, the confirmation gate on a risky action, and the escalation path.

Open one pull request containing all required files in the end-of-week checklist. See `../10-GitHub-For-Designers.md`.

Next: week 21 in Sprint 6. Check the file name in the Sprint 6 folder before you link it.
