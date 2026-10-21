# 07 - AI In Design

**The AI and agentic design handbook: seven labs across 27 weeks.**

This guide practises two skills for the course's interview exercises.

1. **Using AI as part of how you work.** Faster exploration, faster prototypes, without handing over judgement.
2. **Designing interfaces that contain AI.** Confidence, explanation, failure, and trust. This includes agents, which are systems that can take actions, not just answer.

The program already allows AI tools with disclosure (`03-Books-And-Resources.md`, section 8). This file turns that into practice. Seven short labs, spread across the 27 weeks, each ending with something you can talk about in an interview.

This is new for most people. Go slowly.

Related reading: the setup guide (`04-Tools-Setup.md`), the commit and pull request guide (`10-GitHub-For-Designers.md`), and docs 11 and 12.

---

## 1. The stance

**AI generates options. You decide.** An AI tool is useful for the first draft of anything you can check, and dangerous for anything you cannot. The labs are built around finding out, with your own evidence, where that line is for each task.

**Treat as unvalidated** any claim that an AI tool can moderate an interview or replace participants. At most it can help you screen or rehearse. The evidence must come from people.

**Never** use AI for: inventing a research finding, writing a quote a participant did not say, choosing between design options, or producing something you cannot explain in a defense.

**Always** carry the one-line footer on anything AI touched:

> *AI note: used {tool} to {what}. Verified by {how}.*

---

## 2. The AI log

Keep one file per sprint: `students/UX{n}/ai-log.md` in the current sprint folder. Append one row every time you use an AI tool on program work.

| Date | Task ID | Tool | What I asked for | What came back | What I kept, changed, rejected | How I verified |
|---|---|---|---|---|---|---|

It is the evidence base for the interview question *"how do you use AI in your process?"*. The honest answer has three specific examples, including one where the tool was wrong.

---

## 3. Free AI tools

Use free tiers only. **Check the free limit before use** for every tool below. Limits change often, so the number you saw last month may be wrong today.

| Tool | Good for | Limit rule |
|---|---|---|
| Figma AI (inside your Figma file) | first drafts, renaming layers, quick variants | Starter plan gives 150 AI credits per day, up to 500 per month (verified). Check before use: https://www.figma.com/pricing/ |
| Figma Make | turning a prompt into a rough interactive screen | check the free limit before use |
| Google Stitch | screen ideas from a prompt | check the free limit before use |
| v0, Lovable, Bolt | prompt to a small web page | check the free limit before use, one at a time |
| Claude, ChatGPT | thinking partner, rewriting, reading code | check the free limit before use |
| GitHub Copilot free, Cursor free | code suggestions inside your editor | check the free limit before use |

Notes:

- The Figma Education plan (free Professional for eligible students in a structured class) may lift limits. Ask the admin first. Do not assume. See https://www.figma.com/education/
- Figma file hygiene still applies: ONE Figma file per sprint, named `SPRINT-N UX{n}`, with one page per week. Put AI output on the page for that week. If the 3-file Starter limit blocks you, use Penpot free (https://penpot.app/, check the plan before use: https://penpot.app/pricing).
- FigJam counts toward your limits. Use it sparingly.
- Optional reading only: the Figma Dev Mode MCP server needs a Dev Mode seat on paid plans per most sources. See https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server
- Write the prompt down. Keep the output. Log the row. Do all three, every time.

---

## 4. AI coding assistants, safety first

You meet AI coding assistants in the code corners (week0, 3, 6, 10, 12b, 15, 22) and in full in week12b, where you build and publish a small coded prototype. Install steps for Mac and Windows are in `04-Tools-Setup.md`. Commit and pull request rules are in `10-GitHub-For-Designers.md`.

Four rules. No exceptions.

**1. No secrets.**
Never paste API keys, tokens, passwords, or your GitHub login into a prompt or a chat. If a key goes in by mistake, tell the admin and replace the key.

**2. No participant data.**
No real names, faces, phone numbers, IDs, or recordings. Participants are P1, P2. Use a practice transcript supplied by the admin if your own data is not safe to paste.

**3. Read the code.**
Never commit code you cannot explain line by line. Ask the assistant to explain a line, then check the explanation against MDN (https://developer.mozilla.org/en-US/docs/Learn_web_development). Fix one thing by hand so you know the code is yours to change.

**4. Do not run what you cannot explain.**
If the assistant gives you a terminal command you do not understand, do not run it. Ask in Discord with a screenshot first.

Then: put the AI footer in the file, and add a row to the AI log. Every time.

---

## 5. The labs

Each lab is done on the week's Day 6 (cohort day). Commit the output to `students/UX{n}/week{n}/` in the current sprint folder. L-AI6 lives in `week12b/`, L-AI7 in `week20b/`.

Every lab below has an exact output path and an exact commit message. One lab, one commit.

| ID | Week | Time | Name | You prove |
|---|---|---|---|---|
| **L-AI1** | 2 | 90 min | Options to react against | You can use AI to widen options without lowering the standard |
| **L-AI2** | 6 | 90 min | Catch the invention | You can find where AI summarisation invents or flattens evidence |
| **L-AI3** | 9 | 90 min | From spec to throwaway prototype | You know what AI-built prototypes get wrong |
| **L-AI6** | 12b | part of week 12b | A coded prototype you can read | You can go from one Figma screen to a small coded page with an assistant, check it, and publish it |
| **L-AI4** | 14 | 90 min | Reading code you did not write | You can use AI to read a component and verify what it says |
| **L-AI5** | 17 | 3 h | Design an AI feature | You can design confidence, explanation and failure so the user neither over-trusts nor ignores |
| **L-AI7** | 20b | part of week 20b | Agent UX patterns | You can design control, consent and accountability for an agent |

### L-AI1 - Options to react against (week 2)

**Learn first:** the three jobs of an error message (C4.1 reading) and your error inventory from C4.1.

**Method**
1. Pick three of your errors. For each, ask an AI tool for ten alternative messages. Use the same prompt for each, and write the prompt down.
2. Score every one of the 30 against your three-jobs rubric: says what happened, says what to do, names the field. Mark each pass or fail on each job.
3. Keep the best two per error and rewrite them in your own words. Reject the rest and write the reason for the three most common ways they failed.
4. Choose one rewritten message for each of the three errors. That gives you three final messages. Write one line on why you chose each one.
5. Test your three final messages with one person who has not seen them. Record whether they know what to do.

**Done when**
- [ ] The prompt, the 30 outputs and the scoring table are committed
- [ ] A hit rate is stated ("7 of 30 passed all three jobs")
- [ ] The three most common failure patterns are named
- [ ] The choice of one message per error is written down
- [ ] AI footer and AI log entries exist

**Commit**
→ `students/UX{n}/week2/L-AI1-options.md`
Commit message: `UX{n}: complete L-AI1 options lab`

**If you get stuck:**
- Reread your C4.1 error inventory and pick three errors you already understand well.
- Search for "error message checklist" or read the week 2 reading again.
- If the tool gives you nothing useful after one prompt rewording, use your own drafts and say so in the file.
- Ask in Discord with a screenshot and one line on what you tried. Do not paste names, contact details, account details or API keys. Use P1, P2.

### L-AI2 - Catch the invention (week 6)

**Learn first:** your own R4.2 self-critique of an interview transcript.

**Method**
1. Take the transcript of one interview you ran and read yourself. Anonymised. Remove anything identifying before you paste it anywhere, and check the participant's consent covered this. If it did not, use a practice transcript supplied by the admin.
2. Ask an AI tool for the main themes and three supporting quotes.
3. Check every quote against the transcript. Mark each as: exact, paraphrased, or invented.
4. Compare the themes to your own notes. List what it missed, what it overstated, and any contradiction it smoothed away.
5. Write a verification checklist of at least five steps that you will apply to any AI summary of research.

**Done when**
- [ ] Every quote is checked and classified
- [ ] At least three specific errors are documented, or you state honestly that you found none and how thoroughly you looked
- [ ] The checklist exists
- [ ] The rule is restated in your words: why synthesis stays human

**Commit**
→ `students/UX{n}/week6/L-AI2-catch-the-invention.md`
Commit message: `UX{n}: complete L-AI2 catch the invention lab`

**If you get stuck:**
- Use a practice transcript from the admin if your own transcript is not safe to paste.
- Reread your R4.2 self-critique before you start.
- If you cannot find three errors, that is a finding. Write how you checked and how long you looked.
- Ask in Discord with a screenshot of your quote table only. Never paste the full transcript with names in it.

### L-AI3 - From spec to throwaway prototype (week 9)

**Learn first:** your I1.1 state machine.

**Method**
1. Take one flow from your state machine (for example Active → PastDue → Active). Write a prompt for an AI prototyping tool (v0, Figma Make, or similar) that describes it. Check the free limit before use.
2. Preview the output in the tool's own browser preview. If the tool needs local setup, installs or terminal commands you do not know, stop and switch to a tool that has a browser preview. Walk the preview with your state machine beside you. List every state and transition it missed or invented.
3. Test it with keyboard only and with a screen reader for two minutes. Write down what you checked and what failed.
4. Decide what you would keep (layout idea, copy, structure) and what you must rebuild. Never ship it.

**Done when**
- [ ] The prompt and a screenshot of the output are committed
- [ ] A table of missed and invented states
- [ ] Record each accessibility failure found, or state that none were found and describe the checks performed
- [ ] One sentence: what the spec had that the prompt could not carry

**Commit**
→ `students/UX{n}/week9/L-AI3-prototype.md`
Commit message: `UX{n}: complete L-AI3 prototype lab`

**If you get stuck:**
- Reread your I1.1 state machine and pick the shortest flow.
- If the tool asks you to install things or run commands, switch to a tool with a browser preview.
- If the free limit is used up, save a screenshot of what you have and finish the table in text.
- Ask in Discord with a screenshot and what you tried. No personal data, no keys.

### L-AI6 - A coded prototype you can read (week 12b)

This lab is week12b. The seven tasks Y1.1 to Y1.7 are the method. Nothing extra is needed here.

**Learn first:** the HTML and CSS basics from the week0 and week3 code corners (https://web.dev/learn/html, https://web.dev/learn/css), and your own Y1.1 screen choice.

**Method**
1. Pick one screen from your showpiece (Y1.1). Write down the states it needs.
2. Write the prompt and the spec before you open the tool (Y1.2). The spec names the layout, the text, the states, and the keyboard behaviour.
3. Ask the assistant for one page at a time (Y1.3). Do not ask for a whole site.
4. Read every line (Y1.4). Ask the assistant to explain any line you cannot read. Fix one thing by hand. If a line still cannot be explained, remove it or replace it with something simpler before you commit.
5. Check it with axe DevTools and with keyboard only (Y1.5). Two minutes each. Write what failed.
6. Publish it on GitHub Pages (Y1.6): https://docs.github.com/en/pages/quickstart
7. Write the AI note and the AI log rows (Y1.7). Say what the assistant got wrong.

**Done when**
- [ ] One screen is live on a GitHub Pages link
- [ ] The spec and the prompt are committed next to the code
- [ ] You can explain every line of the code you commit. Simplify or remove any line you cannot explain before you commit.
- [ ] Two accessibility checks recorded, axe and keyboard
- [ ] AI footer and AI log entries exist

**Commit**
→ `Design-Sprint-3/students/UX{n}/week12b/page/index.html`
→ any `.css` and `.js` files in the same `page/` folder
→ `Design-Sprint-3/students/UX{n}/week12b/L-AI6-coded-prototype.md`
Commit message: `UX{n}: complete L-AI6 coded prototype lab`
One commit contains all the files for this lab.

**If you get stuck:**
- Reread the week0 and week3 code corners and the week12b task pages Y1.1 to Y1.7.
- Ask the assistant to explain the line, then check that explanation on MDN. If you still cannot explain the line, delete it.
- If publishing fails, read the GitHub Pages guide again and ask the admin to check the repository settings.
- Ask in Discord with a screenshot of the error. Never paste your password or a token.

### L-AI4 - Reading code you did not write (week 14)

**Learn first:** the ARIA APG pattern for the component type you chose in T2.1.

**Method**
1. Open the source of one real component (a Polaris, Carbon or GOV.UK modal, select, or tabs). Ask an AI tool to explain its API, its keyboard behaviour and its focus management.
2. Check each claim three ways: the system's documentation, the ARIA APG pattern, and by using the live component with a keyboard.
3. Produce a corrected explanation: five facts you verified, and every claim you found that was wrong or that the AI could not know. If you found none, say so and describe how you checked.
4. Say what you learned that changes your own component's documentation.

**Done when**
- [ ] Each AI claim is marked verified, wrong, or unverifiable
- [ ] Five verified facts, plus any wrong or unverifiable claims, or a clear statement that none were found
- [ ] One change made to your own component docs

**Commit**
→ `students/UX{n}/week14/L-AI4-reading-code.md`
Commit message: `UX{n}: complete L-AI4 reading code lab`

**If you get stuck:**
- Pick a component you have used or documented before, such as a modal or tabs.
- Check one claim at a time: system docs first, then the ARIA APG pattern, then a keyboard test.
- If the answer is too broad, ask a smaller question, for example "what does this attribute do".
- Ask in Discord with the exact claim and the two sources you checked. No personal data, no keys.

### L-AI5 - Design an AI feature (week 17)

**The case:** an underwriting tool where a model scores a loan application and a human decides. Full detail is in `Design-Sprint-5/01-project-options.md`, Option D. Everyone does this lab, whichever capstone option they chose. Option D designers extend it into their capstone.

**Learn first:** the Google People + AI Guidebook. Read these chapters: User Needs + Defining Success, Data Collection + Privacy, Mental Models, Explainability + Trust, Feedback + Control, and Errors + Graceful Failure (check the chapter titles and the link before use). Also read the Microsoft HAX Toolkit guidelines, all 18 (check the link and the numbering before use). In this lab you will cite the guidelines on making clear what the system can do, making clear how well it can do it, making clear why the system did what it did, conveying the consequences of user actions, and graceful failure. Write the number of each guideline you cite, and check that number on the page before use.

**Method**
1. Write the two ways this goes wrong: over-trust and under-trust. For each, name a specific behaviour a real underwriter would show.
2. Design the score display. Decide what is shown (band, number, factors), what is not, and why. Say how your design avoids implying the model made the decision.
3. Design three failure states as separate screens showing the message and the action the user can take next: model slow (2 to 8 seconds), confidence unavailable, and model clearly wrong (the underwriter overrides).
4. Write the explanation text for one applicant decline. It must not claim the factors *caused* the decline.
5. Name one measure that would tell you in production that trust is calibrated, and one that would warn you it is not.
6. **Autonomy.** The business now asks whether the green band could be approved automatically. Without designing it, write the conditions you would require before agreeing: the autonomy level (suggest, approve-then-act, act-then-notify), the scope limit (which loans, up to what amount), the human approval step that remains, the audit trail, and how a wrong automatic decision is undone. If you cannot write the undo, say the feature should not ship.

**Done when**
- [ ] Over-trust and under-trust each have a named behaviour
- [ ] Score display decision is justified against HAX guideline numbers
- [ ] Three failure states designed as separate screens
- [ ] Decline explanation avoids causal language
- [ ] Two measures stated
- [ ] Autonomy conditions written: level, scope limit, approval, audit trail and undo

**Commit**
→ `students/UX{n}/week17/L-AI5-ai-feature.md`
Commit message: `UX{n}: complete L-AI5 AI feature lab`

**If you get stuck:**
- Reread the case in `Design-Sprint-5/01-project-options.md`, Option D.
- If a guideline number is unclear, quote the guideline text and mark the number "(check before use)".
- If you cannot write the undo, write "this feature should not ship" and say why. That is a valid and strong answer.
- Ask in Discord with a screenshot and the guideline you are unsure about. No personal data, no keys.

### L-AI7 - Agent UX patterns (week 20b)

This lab is week20b. The seven tasks A5.1 to A5.7 are the method. An agent is a system that can take actions, not just answer. The design question is always: what may it do alone, and who can undo it?

**Learn first:** the ten patterns below, the Smashing Magazine February 2026 article "Designing For Agentic AI: Practical UX Patterns For Control, Consent, And Accountability" (check before use), and NN/g articles (search https://www.nngroup.com/ directly).

The ten patterns, in plain words, with one question to ask on your own screen:

1. **Intent preview.** The user sees what the agent plans to do before it does it. Ask: where does the user see the plan before it runs?
2. **Autonomy dial.** A setting that controls how much the agent may do alone. Ask: which levels do you offer, and which one is the default?
3. **Show reasoning and confidence.** The agent says why it chose this and how sure it is. Ask: where do a short reason and a confidence level appear on your screen?
4. **Confirmation gates.** A stop where the user says yes before a risky action. Ask: which agent actions must stop and wait for a yes?
5. **Streaming state.** The screen shows the work happening step by step, not one frozen spinner. Ask: what does the user see at second 2, at second 10, and after a failure?
6. **Trust indicators.** Small signals that say how reliable this answer or action is. Ask: which one signal will you show, and what makes it honest?
7. **Error recovery.** A clear path back when the agent fails. Ask: what does your agent say and offer when it fails halfway?
8. **Audit and undo.** A record of what the agent did, and a way to reverse it. Ask: can you draw the undo, and where does the user find the record?
9. **Escalation to a human.** A route to a person when the agent cannot continue. Ask: who is that person, when are they contacted, and what do they see?
10. **Progressive autonomy.** The agent earns more freedom over time, with evidence. Ask: what evidence would let you raise the level?

**Method**
1. List every action your agent can take in your capstone (A5.1). Write each as a verb and an object.
2. Give each action an autonomy level and a scope limit (A5.2).
3. Design the intent preview and the confirmation gate (A5.3).
4. Design reasoning, confidence and the failure states (A5.4).
5. Design undo and the audit trail (A5.5). If you cannot draw the undo, the action stays manual.
6. Design the path that escalates to a human (A5.6). Say who, when, and what they see.
7. Prototype it and test it with one person (A5.7). Record where they hesitated.

**Done when**
- [ ] Every agent action has an autonomy level and a scope limit
- [ ] Intent preview and confirmation gate drawn as screens
- [ ] Reasoning, confidence and at least two failure states drawn
- [ ] Undo and audit trail drawn
- [ ] Human escalation path drawn
- [ ] One test with one person, notes committed
- [ ] AI footer and AI log entries exist

**Commit**
→ `students/UX{n}/week20b/L-AI7-agent-ux.md`
Commit message: `UX{n}: complete L-AI7 agent UX lab`

**If you get stuck:**
- Do one pattern per sitting. Ten in one go is too much.
- If an action has no undo, set it to manual and write why.
- Ask the person you test with to say out loud where they hesitate, and write it down word for word.
- Ask in Discord with a photo of the sketch or a view-only Figma link. No personal data, no keys.

---

## 6. In the interview

By week 23 you should be able to answer, with examples from your log:

- How do you use AI in your design process?
- Tell me about a time an AI tool was wrong and how you caught it.
- What would you never use AI for?
- How would you design the interface for a feature where the model is sometimes wrong?
- How would you decide what an agent may do without asking the user?
- How do you keep participant data and secrets out of AI tools?

The question bank (`Design-Sprint-6/07-interview-question-bank.md`) has these.

---

Next: `08-Prototyping-And-Responsive.md`.
