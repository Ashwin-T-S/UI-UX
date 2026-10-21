# Week 4 - Ship and Defend

**Theme: accessibility, high fidelity, handoff, and the defense.**

## Week at a Glance

| Task ID | Task name | Time | File you will commit |
|---|---|---|---|
| C7.1 | Keyboard and focus | 60 min | `students/UX{n}/week4/C7-1-keyboard-focus.md` |
| C7.2 | Contrast pass | 60 min | `students/UX{n}/week4/C7-2-contrast-pass.md` |
| C7.3 | Screen reader run | 60 min | `students/UX{n}/week4/C7-3-screen-reader-run.md` |
| C7.4 | Target sizes and motion | 45 min | `students/UX{n}/week4/C7-4-targets-motion.md` |
| C8.1 | High fidelity, mobile | 75 min | `students/UX{n}/week4/C8-1-high-fidelity-mobile.md` |
| C8.2 | Desktop at 1440px | 45 min | `students/UX{n}/week4/C8-2-desktop.md` |
| S4.1 | Handoff spec | 75 min | `students/UX{n}/week4/S4-1-handoff-spec.md` |
| P4.1 | Decision record | 30 min | `students/UX{n}/week4/P4-1-decision-record.md` |
| Gate | Accessibility gate | about 60 min | `students/UX{n}/week4/accessibility-gate-signed.md` |
| Event | Final critique | 90 min | critique lead files the final log |
| Event | Defense | 55 min each | no file |
| P4.2 | Reflection | 30 min | `students/UX{n}/week4/P4-2-reflection.md` |
| S5.1 | Sprint 1 system release | 40 min | `system/docs/CHANGELOG.md`; `system/README.md` |
| S5.2 | Dark mode test | 20 min | `system/docs/dark-mode-test.md` |
| S5.3 | Debt list | 30 min | `system/docs/debt.md` |
| F4.1 | Why session: affordances, signifiers and mental models | 45 min | `fundamentals/why-sessions/week04-affordances.md` |
| F4.2 | Teardown: a subscription cancellation flow | 45 min | `fundamentals/teardowns/04-cancellation-flow.md` |
| F4.3 | Explainer | 40 min | `fundamentals/explainers/sprint1-{topic}.md` |
| F4.4 | Drill log review | 30 min | `students/UX{n}/week4/F4-4-drill-log-review.md` |
| JR1 | Position yourself and start the portfolio | 2 hours | `students/UX{n}/portfolio/JR1-positioning.md` |

About 23 hours of work in this week.

## 1. What We Are Doing

You finish Sprint 1. You test your apply flow for accessibility, make high fidelity screens, write the handoff and decision record, then defend your work. You also close the design system and the sprint retro.

- Group 1 - Accessibility checks: C7.1, C7.2
- Group 2 - Screen reader, targets and motion: C7.3, C7.4
- Group 3 - High fidelity screens: C8.1, C8.2
- Group 4 - Handoff, decision record, accessibility gate, critique: S4.1, P4.1, Gate, Critique
- Group 5 - Defense and reflection: Defense, P4.2
- Group 6 - System handover: S5.1, S5.2, S5.3
- Group 7 - Sprint retro: F4.1, F4.2, F4.3, F4.4
- Group 8 - Job readiness: JR1

## 2. Why We Are Doing It

A working product designer in India must show evidence, not opinion. A review will ask for the contrast ratio, the screen reader words, and the handoff rule a developer can build. This week turns four weeks of work into proof you can defend in a portfolio and an interview. The accessibility gate is part of the project, not extra polish.

## 3. What to Learn First

By the end of the week you can:

- Run a WCAG 2.2 AA gate on your own work. WCAG is the web accessibility standard this course uses. Every line of the gate needs evidence.
- Use a screen reader on your own design. Then fix what you hear.
- Write a handoff spec (a document an engineer can build from). It must answer questions before they are asked.
- Defend every decision from the last four weeks. Out loud, in your own words, without your files.

Core ideas to review first:

- WCAG is a lookup list, not a memory test. Find the rule and cite the number.
- Focus order, focus ring, keyboard behaviour, and focus after an action.
- Contrast: 4.5:1 for normal text, 3:1 for large text and meaningful non-text.
- Screen reader: name, role, value. Errors linked to fields.
- Target size 24 x 24 px minimum. Aim for 44 x 44 px on phones. Reduced motion.
- Tokens, states, real content, Malayalam clipping, and desktop measure.
- Norman: affordances, signifiers, mapping, feedback, conceptual model.
- Handoff spec, decision record, system changelog, debt, dark mode by tokens.
- JR1 job readiness start.

## 4. Where to Find Resources

### Your week in order

| Day | Source | What exactly | Time |
|---|---|---|---|
| 1 | WCAG 2.2 Quick Reference (https://www.w3.org/WAI/WCAG22/quickref/) | Include both Level A and Level AA. Read these 12 rules in full: 1.3.1 Info and Relationships; 1.4.1 Use of Color; 1.4.3 Contrast; 1.4.11 Non-text Contrast; 1.4.12 Text Spacing; 2.1.1 Keyboard; 2.4.3 Focus Order; 2.4.7 Focus Visible; 2.5.8 Target Size; 3.3.1 Error Identification; 3.3.2 Labels or Instructions; 4.1.2 Name, Role, Value | 50 min |
| 1 | web.dev Learn Accessibility (https://web.dev/learn/accessibility) | The "Focus" and "Keyboard" modules | 25 min |
| 1 | WebAIM contrast checker (https://webaim.org/resources/contrastchecker/) | Try four colour pairs from your own flow. Write down every ratio you get. | 15 min |
| 2 | web.dev Learn Accessibility | The "Forms" and "ARIA and HTML" modules. ARIA is code that gives controls names and roles. Learn how a screen reader moves by heading and by form control. | 35 min |
| 2 | VoiceOver on Mac or NVDA for Windows | The help pages for the screen reader you will use. Practise moving by heading and by form control. | 30 min |
| 2 | WCAG 2.2 quick reference | Read 4.1.2 Name, Role, Value and 3.3.2 Labels or Instructions, in full. | 25 min |
| 3 | Refactoring UI | Chapter 8 "Finishing Touches", chapter 6 "Creating Depth", chapter 7 "Working with Images" | 40 min |
| 3 | Your own week 1 tokens | Read C1.1, C1.2 and C2.1 again. You will use these values now at full detail. | 20 min |
| 4 | The Design of Everyday Things, Norman | Chapters 1 to 4. Learn five ideas: affordances, signifiers, mapping, feedback, conceptual model. | 45 min |
| 4 | Your own decision files | Read P1.2, P2.3, P3.1, and X1 in order, as one story. Look for the apply flow, the photo rules, and the confirmation steps. | 15 min |

### Tools to open

You will open Figma for screens and measures. Setup: see the Figma part of `../04-Tools-Setup.md`. Figma rule for this week: ONE file per sprint named `SPRINT-N UX{n}`, one page per week. Do not use three files per sprint. If the Starter 3-file limit blocks you, use Penpot as the backup: see the Penpot part of `../04-Tools-Setup.md`.

You will use a browser for WCAG, WebAIM, axe DevTools, Material 3, Laws of UX, and NN/g. You will use VoiceOver, NVDA or TalkBack for C7.3. You do not code a screen for this task: use the ready-made practice page (see C7.3). Setup help: see `../04-Tools-Setup.md`.

### Search keywords when you are stuck

- WCAG 2.2 AA form
- focus order form
- WebAIM contrast checker
- screen reader form error
- target size 24 x 24
- prefers-reduced-motion

## 5. Step-by-Step Guide

> All `students/...` paths in this week are inside your sprint folder (`Design-Sprint-N/`). Open a terminal in the repo root and use full paths.

One task, one commit with all files listed for that task. The Git steps are in `../10-GitHub-For-Designers.md`.

Allowed files for all tasks: markdown (.md), PNG/JPG under 2 MB with lowercase hyphen names, PDF under 10 MB, small `.html`, `.css` and `.js` files kept in a code folder inside the task folder (for example `week4/page/`), and a view-only Figma link or a view-only Penpot link written inside a markdown file. Never commit .fig files, passwords, tokens, or real personal data.

### Group 1 - Accessibility checks, keyboard and contrast

#### Task - Keyboard and focus (ID `C7.1`)

##### 1. What We Are Doing

We make every screen work with a keyboard only. We also decide where the focus goes. The focus is the small mark that shows which thing will react to the keyboard.

##### 2. Why We Are Doing It

Some people cannot use a mouse or a touch screen. P1 uses a screen reader, which reads the page aloud. If the focus gets lost, a person cannot apply at all. They will call the office instead.

##### 3. What to Learn First

WCAG 2.1.1, 2.4.3 and 2.4.7 from today's LEARN block. Look up "focus", "tab order" and "screen reader" in `08-glossary.md`.

##### 4. Where to Find Resources

- WCAG 2.2 Quick Reference: https://www.w3.org/WAI/WCAG22/quickref/. Include both Level A and Level AA. Read 2.1.1, 2.4.3 and 2.4.7.
- web.dev Learn Accessibility: https://web.dev/learn/accessibility. Read the "Focus" and "Keyboard" modules.
- `08-glossary.md` in this folder. Look up "focus", "tab order" and "screen reader".

##### 5. Step-by-Step Guide

Before you start: use your mid-fidelity screens from week 3 and the list of every screen in your flow, including error screens. Allow about 60 minutes.

How to think about it:
- Can I reach every button with the Tab key alone?
- If I look away and come back, can I see where I am?
- After the screen changes, does the person know where they are now?
- What does a person hear when an error appears?

1. Write the tab order for every screen. List the order, screen by screen.
2. Draw the focus order on every screen as numbered labels. It must follow the reading order. If it does not, fix the layout or the order.
3. Design the focus indicator (the ring around the focused thing). It must pass 3:1 contrast against the part and against the background behind it (1.4.11). A thin light grey line fails.
4. Define the keyboard behaviour for every control. Write what Enter does, what Space does and what Escape does. If a pop-up keeps the focus inside, say how the person gets out.
5. Define where the focus goes after each action. Say it for after Submit, after an error, after a pop-up closes, and after a step change. The code screen for confirmation is a step change too.

Everyone forgets step 5. An error summary appears, the focus stays on the old button, and a screen reader user never learns about the error.

Worked example, from a different product (not your apply flow): a cinema ticket booking form, after a failed Submit. The focus moves to the error summary heading at the top of the page. The summary has `role="alert"` (a code label that tells the screen reader to speak it at once). Each error in the summary is a link to its field. From there the tab order is: first error link, second error link, then the first failed field. Why: the person needs three things. Something failed. How many things failed. How to reach each one. Leaving the focus on Submit gives them none of these.

Your apply flow: do not copy this answer. Write your own focus destination for after Submit, after an error and after a pop-up closes. Say why the focus goes there.

Common mistakes:
- The focus ring is thin and light grey. Make it thick and dark, at 3:1 or more.
- The tab order follows the order you drew the boxes. Check the reading order instead.
- An error appears and the focus stays on Submit. Move the focus to the error summary.
- The confirmation code screen opens and the focus stays on the old page. Move it to the first code box.

If you get stuck: read the WCAG 2.4.3 page again. Search "focus order form". Ask in Discord with a screenshot and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/C7-1-keyboard-focus.md`
- [ ] Done when:
  - [ ] Focus order labelled on every screen, and it matches the reading order
  - [ ] Focus indicator designed and measured at 3:1 or more (1.4.11)
  - [ ] Enter, Space and Escape written for every control
  - [ ] Focus destination written for after Submit, after an error and after a pop-up closes
  - [ ] Every pop-up has a written way to keep the focus in, and a written way out
  - [ ] Each screen checked with the longer Malayalam label text, not only English
- [ ] Commit message: `C7.1: keyboard and focus`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Contrast pass (ID `C7.2`)

##### 1. What We Are Doing

We measure the contrast (how strongly two colours differ) of every text and every meaningful shape. Then we fix what fails.

##### 2. Why We Are Doing It

Low contrast is a common problem. Many people cannot read light grey text. P2 applies on a cheap phone, in daylight. If the photo rule text is too light, he cannot read it.

##### 3. What to Learn First

WCAG 1.4.3 and 1.4.11.

##### 4. Where to Find Resources

- WebAIM contrast checker: https://webaim.org/resources/contrastchecker/. Put in the two colour codes and read the ratio.
- WCAG 2.2 Quick Reference: https://www.w3.org/WAI/WCAG22/quickref/. Read 1.4.3 and 1.4.11.
- axe DevTools: https://www.deque.com/axe/devtools/. This browser extension can check contrast on a web page.

##### 5. Step-by-Step Guide

Before you start: use your screens with the final colours and a contrast checker open in a browser tab. Allow about 60 minutes.

How to think about it:
- Can I read this in bright sun, on a cheap phone?
- Is the border the only thing that shows the field edge? Then it must pass 3:1.
- Would a grey "not ready yet" button still look like a button?
- Does the error text rely on red alone? Colour alone is not enough (1.4.1).

1. Measure every text element in your flow. Body text needs 4.5:1. Large text needs 3:1. Large means 24px and up, or 19px and up in bold.
2. Measure every non-text thing that carries meaning: field borders, icons, focus rings, and the ticks and crosses on the photo upload states. They need 3:1 (1.4.11).
3. Look at the inactive controls too, such as a disabled Submit button. WCAG exempts inactive controls from 1.4.3 and 1.4.11, so a low contrast disabled button is not a WCAG failure. Checking it anyway is a course usability recommendation, not a gate line. If you check it, say so and mark it as a recommendation.
4. Measure the hard cases in this flow: the photo rule text, the "code sent" message on the confirmation screen, and the error text next to a field.
5. For every failure, write three things: the ratio you measured, the ratio you need, and what you changed.

Worked example: the Submit button on "Check your answers", white text on a light green fill. Assume for the exercise: the checker gives 3.1:1. You need 4.5:1 for text this size. So you darken the green, and the checker gives 4.6:1. You write both numbers in your file. Why: the number is the proof. "It looks better now" is not a proof, and nobody can check it.

Common mistakes:
- Only the main text is measured. The grey helper text and placeholders are missed.
- A field border is left at 1.5:1. Then the field has no visible edge.
- Red is used alone for an error. Add an icon and a word as well (1.4.1).
- A failing pair stays and gets the note "brand colour". Write the mitigation, or change the colour.

If you get stuck: read WCAG 1.4.3 again. Search "WebAIM contrast checker". Ask in Discord with the two colour codes, the ratio, and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/C7-2-contrast-pass.md`
- [ ] Done when:
  - [ ] Every text element measured, with its ratio written down
  - [ ] Every meaningful non-text element measured
  - [ ] Inactive controls looked at and marked as a course recommendation, not a WCAG failure
  - [ ] The photo rule text, the code message and the field error text all measured
  - [ ] Zero remaining failures, or each one has a reason and a written mitigation
- [ ] Commit message: `C7.2: contrast pass`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

### Group 2 - Screen reader, targets and motion

#### Task - Screen reader run (ID `C7.3`)

##### 1. What We Are Doing

You will test your design with a screen reader. You will write down what it says. Then you will fix the problems. You do not write code for this task.

##### 2. Why We Are Doing It

Many users cannot see the screen. They rely on sound. A button with no name gives no help. A missed error can stop the application.

##### 3. What to Learn First

WCAG 2.2 4.1.2 Name, Role, Value and 3.3.2 Labels or Instructions. Building an accessible form is taught in week 6. Scripted states are taught in week 10. So today you test with a ready-made page, and you write a specification for anything you cannot test.

##### 4. Where to Find Resources

- The ready-made accessible HTML form example for this task is pinned in the week 4 Discord channel. If you cannot find it, ask there.
- VoiceOver on Mac: https://support.apple.com/guide/voiceover/welcome/mac. Look for "Navigate by heading" and "Navigate by form control".
- NVDA for Windows (free): https://www.nvaccess.org/download/. Look for "Browse mode" and "Forms mode" in the user guide.
- TalkBack on Android: https://support.google.com/accessibility/android/answer/6283677. Look for "Turn on TalkBack".
- WCAG 2.2 quick reference: https://www.w3.org/WAI/WCAG22/quickref/. Read 4.1.2 and 3.3.2.

##### 5. Step-by-Step Guide

Before you start: use your clickable prototype from Week 3. If the prototype cannot be read by a screen reader, use the ready-made practice page from the week 4 Discord channel. Do not build a form yourself for this task. Allow about 60 minutes. Setup help: see `../04-Tools-Setup.md`.

How to think about it:
- Would a blind user know what this control does?
- Would they hear the error before they try to fix it?
- Would they know which step they are on?
- If the text is in Malayalam, does the screen reader say it clearly?

1. Turn on VoiceOver (`Cmd+F5`), NVDA, or TalkBack.
2. Open your prototype. If it cannot be read, open the ready-made practice page.
3. Test these parts: the photo upload, the OTP step (the one time code step), and the check your answers page. On the practice page, test the form fields and the error message.
4. Write down the exact words you hear. Do not write what you hoped to hear.
5. For a part you cannot test, write the words you want it to say. Mark it "specified, not tested".
6. Listen to any Malayalam text. Note words that sound wrong or are skipped. Ask a Malayalam speaker to judge.
7. Fix each problem. Write the fix so an engineer can build it.

Worked example:

| Element | What was announced | Problem | Fix |
|---|---|---|---|
| The help icon next to "Photo" | "button" | No name. 4.1.2 fail. | Give it the name "Photo rules" in the handoff |
| The photo upload field with an error | "Photo, file upload" | The error is visible but not read. 3.3.1 fail. | Link the error text to the field. It should say "Photo, file upload, Photo must show your name and date at the bottom" |
| The one time code (OTP) field | "code, edit text" | It does not say where the code went. | Name it "One time code sent to your mobile" |
| "Edit" on check your answers | "link" | It does not say which answer it changes. | Name it "Edit photograph" or "Edit qualification" |
| "Step 2 of 3" | not announced | The user does not know where they are. | Make it a heading and announce step changes |

Common mistakes:
- Testing only with a mouse. Use the keyboard and the screen reader.
- Writing what you hoped to hear. Copy the exact words.
- Leaving an icon button with no name. Give it a clear name.
- Building your own form for this task. Use the ready-made page and specify the rest.
- Testing English only. Listen to the Malayalam text and ask a Malayalam speaker.

If you get stuck: read the NVDA or VoiceOver help page again. Search "screen reader form error". Ask in Discord with the exact words you heard and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/C7-3-screen-reader-run.md`
- [ ] Done when:
  - [ ] Every interactive element's announcement is recorded word for word, or marked "specified, not tested"
  - [ ] Every icon button has a name a screen reader can say
  - [ ] Every error is either linked to its field in tested code, or written as a field-to-error specification marked "specified, not tested"
  - [ ] The user hears the step or progress
  - [ ] Malayalam text is checked with a Malayalam speaker, and notes are written
  - [ ] Every problem has a fix an engineer can build
- [ ] Commit message: `C7.3: screen reader run`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Target sizes and motion (ID `C7.4`)

##### 1. What We Are Doing

You will check every tappable target. You will check every animation (movement on screen). You will fix the small targets and the motion that cannot be turned off. You check your week 3 mid-fidelity screens first, then you repeat the measurements on the high fidelity screens after C8.1.

##### 2. Why We Are Doing It

People use cheap phones on busy buses. A small button causes a wrong tap. Motion can make some people feel sick. A government service must work for them too.

##### 3. What to Learn First

WCAG 2.5.8 Target Size, which is Level AA. WCAG 2.3.3 Animation from Interactions is Level AAA. It is not part of the AA gate, and this course asks for it as an extra requirement beyond AA.

##### 4. Where to Find Resources

- WCAG 2.2 quick reference: https://www.w3.org/WAI/WCAG22/quickref/. Read 2.5.8 Target Size. Then read 2.3.3 Animation from Interactions, which is Level AAA, an extra course requirement beyond AA.
- web.dev Learn Accessibility: https://web.dev/learn/accessibility. Use the module list. Find the parts about animation and touch.
- Refactoring UI (book in `Resources/`), chapters 2 and 3, on hierarchy, layout, and spacing.

##### 5. Step-by-Step Guide

Before you start: use your mid-fidelity screens from week 3 and a measure tool in Figma, or the measure tool in your browser. Allow about 45 minutes. Setup: see the Figma part of `../04-Tools-Setup.md`. After you finish C8.1, repeat steps 1 to 5 on the high fidelity screens and add the new numbers to the same file.

How to think about it:
- Can a person with a shaky hand hit this on a bus?
- Are two buttons so close that one tap hits the wrong one?
- Does this motion help the user know what changed?
- Can the user turn the motion off?

1. Measure every tappable target. The smallest is 24 x 24 px for WCAG 2.5.8 AA. Aim for 44 x 44 px on phones.
2. Check the space between targets. Look at "Upload photo" and "Remove photo". Look at the "Edit" links on check your answers.
3. List every animation and transition. There is no time cutoff: a short animation can still cause discomfort.
4. For each one, write the reduced-motion alternative wherever the motion can cause discomfort. In code, this is `prefers-reduced-motion` (the setting that asks apps to reduce motion).
5. Say what each animation is for. If it does not show a change or where the user is, delete it.
6. After C8.1, repeat steps 1 to 5 on the high fidelity screens. Write both sets of numbers in the file.

Worked example: a ticket app has "Pay" and "Cancel" 2 px apart. Both are 20 x 20 px. On a bus, the thumb hits "Cancel". Fix: make both 44 x 44 px and put 8 px between them. Notice: size alone is not enough. Space matters too.

Common mistakes:
- Making every target 24 px and stopping. Use 44 px on phones.
- Putting small links close together. Add space or use a full block.
- Adding motion because it looks nice. Delete it.
- Forgetting the reduced-motion setting. Add it and test it.
- Measuring only once. Measure the mid-fidelity screens, then measure again after C8.1.

If you get stuck: read WCAG 2.5.8 again. Search "target size 24 x 24". Ask in Discord with a screenshot and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/C7-4-targets-motion.md`
- [ ] Done when:
  - [ ] Every target measured on the mid-fidelity screens, the minimum met, and the smallest one named
  - [ ] The measurements repeated on the high fidelity screens after C8.1
  - [ ] The space between adjacent targets checked
  - [ ] Every animation and transition listed, at any length, with a reduced-motion alternative wherever the motion can cause discomfort
  - [ ] Every animation has a stated purpose, or it is deleted
  - [ ] The photo upload, OTP and check your answers screens are checked
- [ ] Commit message: `C7.4: target sizes and motion`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

### Group 3 - High fidelity screens

#### Task - High fidelity, mobile (ID `C8.1`)

##### 1. What We Are Doing

You turn every flow screen into a finished mobile design at 390px. At the end, the screens look real and use real content.

##### 2. Why We Are Doing It

A rough sketch hides problems. A finished screen shows if the photograph rule is clear. It shows if the check-your-answers page works on a small phone. It shows if the OTP step is clear.

##### 3. What to Learn First

Read Refactoring UI, chapter 8. Look at how small details change a finished screen.

##### 4. Where to Find Resources

- Refactoring UI, chapter 8 "Finishing Touches", chapter 6 "Creating Depth", chapter 7 "Working with Images". The book is in `Resources/`. Website: https://www.refactoringui.com/
- Figma Learn for tool help: https://help.figma.com/
- Noto Sans Malayalam, a free font: https://fonts.google.com/noto/specimen/Noto+Sans+Malayalam

##### 5. Step-by-Step Guide

Before you start: use your C3, C4 and C5 screens, your week 1 tokens, your C7 accessibility fixes, and the C5.1 states matrix. Allow about 75 minutes. Figma setup: see `../04-Tools-Setup.md`. Use ONE Figma file per sprint named `SPRINT-N UX{n}`, one page per week.

How to think about it:
- Can a person on a slow phone finish the photograph upload without guessing?
- Does the check-your-answers page show the photograph rule before the submit button?
- Does the OTP step show what to do next and how long is left?
- Is every colour, space and type size from a token?

1. Take each screen to full detail at 390px. Full detail means final type, colour, space, icons and real words. Leave no choice open.
2. Use only tokens. A token is a saved design value, such as a colour or a space size. If you type a value by hand, stop. Either add it to the system or write down why it is a special case.
3. Add every state from the C5.1 matrix. Example states: empty photograph, photograph too large, upload failed, OTP sent, OTP wrong, time left low. If a state is not ready, mark it as not ready and say why.
4. Put real content in every screen. Use a real post name, a real category number style, and short Malayalam and English labels. Do not use fake words.
5. Add shadows and depth last. Use them only when they show a layer or a raised surface. Do not use them as decoration.
6. Check the Malayalam text. It must not clip at the top or bottom. Use the test string `അപേക്ഷ സമർപ്പിക്കുക` and the font above.
7. Apply all fixes from C7.1 to C7.4 to the final screens.
8. Export PNGs and add the Figma link.

Worked example: a library fine payment app shows a fine summary, a card field and a pay button. The finished screen shows "Fine: 20 rupees", a clear error under an empty card field, and a pay button that cannot be used yet. Notice that the error sits next to the field. You can see if the button is ready or not. Copy this level of detail, not the screen.

Common mistakes:
- You type a colour by hand. Use the token or log the value.
- You show only the normal success case. Add error, empty and loading states.
- The Malayalam text is cut at the top. Increase line height and test again.
- The photograph rule is hidden after upload. Move the rule above the upload field.

If you get stuck: read Refactoring UI chapter 8 again. Search "Figma token styles". Ask in Discord with a screenshot and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/C8-1-high-fidelity-mobile.md`
- [ ] Done when:
  - [ ] Every screen is full detail at 390px.
  - [ ] Zero values are typed by hand, or each one is logged with a reason.
  - [ ] Every state from the C5.1 matrix is present or marked as not ready.
  - [ ] Real content is used throughout.
  - [ ] Malayalam and English versions are shown.
  - [ ] All fixes from C7.1 to C7.4 are in the final screens.
  - [ ] Figma link and exported PNGs are ready.
- [ ] Commit message: `C8.1: high fidelity mobile`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Desktop at 1440px (ID `C8.2`)

##### 1. What We Are Doing

You adapt your finished mobile screens to a desktop screen at 1440px. At the end, every screen has a desktop layout.

##### 2. Why We Are Doing It

A desktop is not a big phone. Wide text and wide fields are hard to read. We need a layout that uses the space well.

##### 3. What to Learn First

Read Practical Typography, the part on line length. It shows why long lines are hard to read.

##### 4. Where to Find Resources

- Practical Typography, the part on line length: https://practicaltypography.com/. Look for line length and text width.
- Refactoring UI, chapter 6, for depth and layout: https://www.refactoringui.com/
- Figma Learn for tool help: https://help.figma.com/

##### 5. Step-by-Step Guide

Before you start: use your C8.1 mobile screens and the C1.3 measure limit. Allow about 45 minutes.

How to think about it:
- Is the line length still easy to read?
- Does the extra space help the candidate check details before submit?
- Can a person see the photograph rule and the OTP deadline on the same screen?
- What is better on desktop? What is worse?

1. Adapt the layout for desktop. Do not make the phone layout wider. A very wide input field is hard to read. It is worse than the phone version.
2. Use your measure limit from C1.3. Measure is the length of a line of text. The limit stays the same on a wide screen.
3. For each screen, write what you changed and why. Examples: a two-column layout, a side panel for guidance, and a summary that stays on screen. Each change needs a reason.
4. Let the extra space help the check-your-answers page. Keep the details close to their change links. Keep the photograph and OTP warnings visible.
5. Name one thing that is better on desktop and one thing that is worse. Be honest.
6. Export PNGs and add the Figma link.

Worked example: a bank account page on desktop uses a narrow column for text and a side panel for help. The text line stays short. The help panel is close to the form. Notice that the page does not stretch the form across the whole screen. Copy the idea, not the bank page.

Common mistakes:
- You stretch the mobile screen to 1440px. Change the layout, not the width.
- You use a 1200px-wide input. Keep fields at a readable width.
- You hide the summary far from the form. Keep it near the fields or make it stay on screen.
- You do not say why a layout changed. Write one reason for each change.

If you get stuck: read the Practical Typography line length page again. Search "readable line length". Ask in Discord with a screenshot and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/C8-2-desktop.md`
- [ ] Done when:
  - [ ] Every screen is shown at 1440px.
  - [ ] The measure limit from C1.3 is respected.
  - [ ] Every layout change has a written reason.
  - [ ] One thing better and one thing worse on desktop are named.
  - [ ] Malayalam and English versions are checked.
  - [ ] Figma link and exported PNGs are ready.
- [ ] Commit message: `C8.2: desktop at 1440px`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

### Group 4 - Handoff, decision record, gate and critique

#### Task - Handoff spec (ID `S4.1`)

##### 1. What We Are Doing

Write a handoff spec for your full apply flow. A handoff spec is a document that tells an engineer how to build your design. At the end, someone can build it without asking you questions.

##### 2. Why We Are Doing It

A good design can fail if the builder must guess. Guessing causes wrong buttons, missing errors, and broken states. A clear spec protects the user and the work.

##### 3. What to Learn First

Read Chapters 1 to 4 of *The Design of Everyday Things*. Look for feedback and states.

##### 4. Where to Find Resources

- `../08-Prototyping-And-Responsive.md` for layout, breakpoints (screen widths where the layout changes), and responsive rules.
- `08-glossary.md` for words like token (a named value), state (a screen condition), and focus order (the order controls are reached).
- Your own C3.3 file for profile check rules. Your own C4.2 file for exact error messages.
- WCAG quick reference (the web accessibility rules) for focus order and announcements: https://www.w3.org/WAI/WCAG22/quickref/
- GOV.UK check answers pattern for the review step: https://design-system.service.gov.uk/patterns/check-answers/

##### 5. Step-by-Step Guide

Before you start: use your final screens for the apply flow, your files from C3.3 and C4.2. Include the photograph upload, the check-your-answers page, and the confirmation OTP step. Allow about 75 minutes.

How to think about it:
- Can a builder make this screen with no call to me?
- Does every button say what happens next?
- Can a user on a slow phone finish the photo upload?
- What happens if the OTP does not arrive? Is that state written down?

1. List every screen in your apply flow. Start with the notification, then Apply Now, profile check, photo upload, submit, confirmation OTP, and admission ticket.
2. For each screen, write the layout. Give grid, breakpoints, and max widths as tokens. Example: "space-4" not "16px".
3. List every component. Say if it comes from `system/` or if it is new.
4. For each interaction, write the trigger, the result, and the duration. Example: "Tap Upload photo. Show a spinner. Stop when the upload ends."
5. List every state. For the photo upload, write: empty, file chosen, uploading, too large, wrong file type, upload failed, and done.
6. Write the validation rules for each field. Use the same rules as C3.3. Include the photo rules before upload.
7. Copy every error message from C4.2. Give its exact words in Malayalam and English. Say where it appears.
8. Write the accessibility notes. Give focus order, ARIA labels where needed, and announcements. ARIA labels are extra labels for screen readers. A screen reader is software that reads the screen aloud. For the OTP step, say how a screen reader user hears the code field.
9. Write anything you do not know as a question. Add who can answer it. Example: "Unknown: does the OTP expire? Ask the Commission office."
10. Read the spec as a builder. If you must ask a question, add the answer to the spec.

Worked example: a library book return kiosk. The button says "Return book". When pressed, show a spinner for 2 seconds. If the machine is offline, show "Cannot return now. Try again later". Notice the exact words, trigger, and time. Your spec should do the same.

Common mistakes:
- Writing "make it clear" and not the exact words. Paste the real message.
- Using a screenshot as the spec. Write the values and rules in text.
- Forgetting the photo error states. List every upload state.
- Leaving unknown items out. Write each one as a question with a name.

If you get stuck: read `../08-Prototyping-And-Responsive.md` again. Search "handoff spec states". Ask in Discord with the spec section and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/S4-1-handoff-spec.md`
- [ ] Done when:
  - [ ] Every screen has all 8 spec sections: layout, components, interactions, states, validation, errors, accessibility, and open questions.
  - [ ] Values are given as tokens, not pixels.
  - [ ] The photo upload has at least six states.
  - [ ] The OTP step has an announcement note for screen readers.
  - [ ] Every open item is a question with a named person who can answer.
  - [ ] No screenshot is used in place of a written rule.
- [ ] Commit message: `S4.1: handoff spec`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Decision record (ID `P4.1`)

##### 1. What We Are Doing

Write a one-page record for one hard decision in your apply flow. The record explains what you chose and why. It also says what could change your mind.

##### 2. Why We Are Doing It

A decision without a reason is hard to defend. A record helps a Commission official or a candidate see your thinking. It also helps the next designer.

##### 3. What to Learn First

Read `07-critique-guide.md`. Look for one fair way to compare two options.

##### 4. Where to Find Resources

- Your own R2.4 findings file for evidence.
- `07-critique-guide.md` for how to state a fair argument.
- `08-glossary.md` for words like trade-off (what you give up to get something) and evidence.
- Tips to Applicants for the rule that a submitted application is provisional (not final) and cannot be altered: https://www.keralapsc.gov.in/tips-applicants

##### 5. Step-by-Step Guide

Before you start: use your final flow, your findings from R2.4, and your notes from P3.1 and X1. Allow about 30 minutes.

How to think about it:
- Which choice would a Commission official or a candidate question?
- What did you give up to get the benefit?
- What evidence would make you choose the other option?
- Is the reason clear to a person who was not in the room?

1. Pick one decision that a Commission official or a candidate would question. Good choices: the review step before submit, the photo check before upload, or the OTP step for confirmation.
2. Write the context. Say what problem you faced and who it affects.
3. Write at least two real options. Describe each one fairly.
4. Write your decision in one sentence.
5. Give your reason and the evidence. Use your own R2.4 finding or a named rule.
6. Write the good results and the bad results. Do not hide the bad ones.
7. Write what would change your mind. Make it a real test or event.
8. Keep it to one page. If it is longer, you have not decided.

Worked example: a café decides to take orders at the table. The context is a long queue at lunch. The options are a counter order or a table order. The café chooses table order. The reason is that people leave when the queue is long. The bad result is that staff walk more. The café would change its mind if table orders slow down the kitchen. Notice that the bad result is written down.

Common mistakes:
- Picking a safe decision that no one would question. Choose the review step or the OTP rule.
- Listing only one option. Add a real second option.
- Hiding the bad result. Write one clear cost.
- Writing three pages. Cut to one page and keep the main reason.

If you get stuck: read `07-critique-guide.md` again. Search "decision record design". Ask in Discord with your two options and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/P4-1-decision-record.md`
- [ ] Done when:
  - [ ] The decision is one that a Commission official or a candidate would question.
  - [ ] At least two real options are described fairly.
  - [ ] The evidence comes from your own R2.4 or a named rule.
  - [ ] The negative results are stated.
  - [ ] What would change your mind is concrete.
  - [ ] The record is one page.
- [ ] Commit message: `P4.1: decision record`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Gate - The accessibility gate (Gate, no task ID)

##### 1. What We Are Doing

Run the full checklist in `06-accessibility-gate.md` on your final prototype. Every line needs evidence. Evidence can be a measurement, a screenshot, or a quoted screen reader announcement.

##### 2. Why We Are Doing It

This is a gate, not a review. If it fails, the sprint is not done. It does not matter how good the work looks. The gate is what protects the person applying in a bus, on a cheap phone, with a screen reader.

##### 3. What to Learn First

Have your C7.1 to C7.4 files open while you run the gate. Most of the evidence is already in them. Read each line of `06-accessibility-gate.md` before you start.

##### 4. Where to Find Resources

- `06-accessibility-gate.md` in the sprint folder. This is the checklist you run.
- WCAG 2.2 Quick Reference, for the rule number behind a line: https://www.w3.org/WAI/WCAG22/quickref/
- Your own C7.1, C7.2, C7.3 and C7.4 files.
- A Malayalam speaker, for the two test strings.

##### 5. Step-by-Step Guide

Before you start: use your final prototype, your C7 files and the checklist. Allow about 60 minutes.

1. Open `06-accessibility-gate.md`.
2. Read the first line of the checklist. Write one evidence line under it: a measurement, a screenshot name, or a quoted announcement.
3. Repeat line by line for the whole checklist. Do not skip a line.
4. Test your final prototype on the photo upload, the check-your-answers page, and the OTP step.
5. Test these two Malayalam strings: `അപേക്ഷ സമർപ്പിക്കുക` and `ഫോട്ടോ അപ്‌ലോഡ് ചെയ്യുക`. Ask a Malayalam speaker to check the meaning and the sound.
6. For any line you cannot evidence, write "not signed" and the reason. A gate with an unsigned line is not a pass.
7. Save the signed file.

If you get stuck: read `06-accessibility-gate.md` again. Search "WCAG 2.2 AA checklist". Ask in Discord with the line you cannot sign and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/accessibility-gate-signed.md`
- [ ] Done when:
  - [ ] Every line in `06-accessibility-gate.md` has evidence.
  - [ ] The photo upload, check-your-answers page, and OTP step are tested.
  - [ ] The two Malayalam strings are checked with a Malayalam speaker.
- [ ] Commit message: `Gate: accessibility gate signed`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Critique - Final critique (no task ID)

##### 1. What We Are Doing

A 90-minute final critique. You present your full flow. Show the photo upload, the review step, and the OTP step. The critique lead files the final log for the sprint.

##### 2. Why We Are Doing It

Critique is where you hear what a stranger sees. You get one last set of eyes before the defense. A problem found now is cheaper than a problem found in an interview.

##### 3. What to Learn First

Read `07-critique-guide.md` again. Look at how to give feedback about the work, not about the person.

##### 4. Where to Find Resources

- `07-critique-guide.md` in the sprint folder. Use its question list.
- Your final screens and your clickable prototype.
- `../10-GitHub-For-Designers.md` for the commit and pull request steps, if you are the team leader.

##### 5. Step-by-Step Guide

Before you start: have your final prototype and screens open. Allow 90 minutes.

1. Present your full flow in order: notification, Apply Now, profile check, photo upload, review, OTP, admission ticket.
2. Show the photo upload, the review step and the OTP step in detail.
3. Take notes while others speak. Do not defend your work during the critique. The defense is later.
4. Give one written note to each other presenter. Say the screen and what you saw.
5. The critique lead writes the final log.
6. The team leader commits the log. Only the team leader updates the shared `delivery/` folder.

Who files the log: the critique lead, who is the team leader. Exact path: `delivery/critique-logs/week04-final-critique.md`. Nobody else edits that file.

If you get stuck: read `07-critique-guide.md` again. Search "design critique feedback". Ask in Discord with one note you want to phrase better and what you tried.

##### 6. What to Commit

- [ ] Presenters: no file for the critique itself.
- [ ] Team leader only: `delivery/critique-logs/week04-final-critique.md`
- [ ] Done when:
  - [ ] The log lists every presenter, the screens shown, and one action per person.
  - [ ] The log is committed by the team leader, and nobody else edited `delivery/`.
- [ ] Commit message: `Critique: week 4 final critique log`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; view-only Figma or Penpot link in .md.

### Group 5 - Defense and reflection

#### Defense - 55 minutes each (no task ID)

##### 1. What We Are Doing

A live defense, 55 minutes each. No files. No notes. You draw your own diagram live, from memory.

##### 2. Why We Are Doing It

Anyone can read a file. A defense shows that the thinking is yours. It is also the closest practice for a job interview, where nobody lets you open your Figma file.

##### 3. What to Learn First

Read your own P1.2, P2.3, P3.1 and X1 files again as one story. Make a short list of the words you used, so you can define them out loud.

##### 4. Where to Find Resources

- `07-critique-guide.md` for how a critique works and how to answer a hard question.
- `08-glossary.md` for the design words you must be able to define.
- Your own week 1 to week 3 files, read as one story.

##### 5. Step-by-Step Guide

| Part | Time | What you do |
|---|---|---|
| Flow walk | 10 min | Draw your flow from memory and walk it. Every branch. |
| Terminology and tradeoff | 10 min | Define the words you used. Say the trade-off that comes with each choice. |
| Failure story | 10 min | The change we added in week 3. Say what it cost and what you would do differently. |
| Business framing | 5 min | What the Commission gets, in their words, not in design words. |
| Evidence defense | 10 min | Defend your three-person study. Say the sample size. Say what you cannot claim. |
| Alternative design | 10 min | We draw a constraint card for you. Redesign under it, out loud. |

Sprint 1 constraint cards: no colour available; screen reader only; 2G connection; feature phone, no smartphone; one hand, in sunlight, on a crowded bus; the Commission will not accept any file upload online.

To pass, all four:
1. Correct vocabulary used correctly.
2. One piece of evidence you can defend, including its limits.
3. One coherent alternative design under the constraint drawn.
4. One honest "I do not know yet, and here is how I would find out".

If you get stuck: read `07-critique-guide.md` again. Search "design interview whiteboard". Ask in Discord before your slot, with the part of the table you want to practise.

##### 6. What to Commit

- [ ] No file for the defense.
- [ ] Done when:
  - [ ] All four pass criteria are met out loud, without your files.
  - [ ] If a criterion is not met, the team leader schedules a re-run in the buffer week.
- [ ] Commit message: none, there is no file.
- [ ] If you want to keep notes after the defense, put them in `students/UX{n}/week4/P4-2-reflection.md`.

#### Task - Reflection (ID `P4.2`)

##### 1. What We Are Doing

You write four short answers about your defense. You do it straight away, while the questions are still fresh. This file is also your Sprint 1 post mortem.

##### 2. Why We Are Doing It

Your defense shows you where your thinking is thin. If you write now, you write the truth. If you wait a week, you will make it sound better than it was. Then you learn less.

##### 3. What to Learn First

Look at `07-critique-guide.md` for how to take a critique without feeling attacked. Use `08-glossary.md` for design words.

##### 4. Where to Find Resources

- `07-critique-guide.md`: how to take a critique without feeling attacked.
- `08-glossary.md`: the design words you may want to use in your answers.

##### 5. Step-by-Step Guide

Before you start: use your memory of the defense. You do not need notes. Allow about 30 minutes.

How to think about it:
- Which question made you stop and think the longest?
- Which answer did you guess instead of know?
- What is one behaviour you will change in Sprint 2?

1. Write the question you answered worst. Say what you now know you do not understand.
2. Write the strongest thing in your work. Give the reason it is strong.
3. Write the weakest thing in your work. Give the reason it is weak.
4. Write one behaviour for Sprint 2. Make it something you can see yourself do, not a wish.

Worked example: a student defended a library book-return flow. The student wrote: "I could not say how many people return books late. I only had three people. I will run a short survey in Sprint 2." Notice three things. The student names the gap. The student names the limit. The student names the next step.

Common mistakes:
- "I did well" with no reason. Add the reason, or drop the line.
- Blaming the reviewer. Write about your work, not about them.
- A long essay. Four short answers are enough.
- "I will try harder." That is not a behaviour. Write what you will actually do.

If you get stuck: read `07-critique-guide.md` again. Search "design reflection". Ask in Discord with the question you answered worst and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/P4-2-reflection.md`
- [ ] Done when:
  - [ ] Four answers are written, in the order above.
  - [ ] Each strength and weakness has a reason.
  - [ ] The Sprint 2 line names one behaviour you can see yourself do.
  - [ ] The file is saved at the path below.
- [ ] Commit message: `P4.2: reflection`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

### Group 6 - System handover

Day 6 - Cohort day. Today you close Sprint 1. You finish your design system, write your retro tasks, and meet the external reviewer. The week 3 injection is still live. Keep it in your product and your notes. The S5 block is 90 minutes.

#### Task - Sprint 1 system release (ID `S5.1`)

##### 1. What We Are Doing

You finish the design system for Sprint 1. Your tokens are final. Every component has a frame or a section with all its states, on your existing week page. A changelog lists what changed.

##### 2. Why We Are Doing It

Other people will use your system after you. If a component has no notes, they guess. Then one product looks different on every screen.

##### 3. What to Learn First

Use `system/README.md` in your own project as your map. Look at Refactoring UI chapters 1 to 6 and 8 for how it names spacing and colour.

##### 4. Where to Find Resources

- `system/README.md` in your own project. This is the page you are writing, so use its list as your map.
- Refactoring UI, chapters 1 to 6 and 8. Look at how it names spacing and colour.
- `08-glossary.md` in the sprint folder. Use it to get the words right.

##### 5. Step-by-Step Guide

Before you start: use your token files and component files from this week, and your notes from the week 3 injection and the accessibility gate. This task is part of the 90-minute S5 block. Allow about 40 minutes for it.

How to think about it:
- Could a new designer use this system without asking me?
- Does every component show every state?
- Does my changelog say what changed and why?

1. Open your token files. Remove tokens you no longer use. Give the rest clear names.
2. Open each component. Put it in its own frame or section on your existing week page. Do not add a new Figma page for each component: the Starter plan gives you 3 files, and you keep one page per week.
3. Show the default, hover, focus, error and loading states in that frame or section.
4. Write the changelog. Use one line per change. Each line says what changed and why.
5. Write `system/README.md`. Say what the system is for and how a person starts. Shared system documentation stays in `system/`, not in the Figma file.

Worked example: a good changelog line reads: "Button: error state added. Why: the submit step can fail on slow data." Notice it says what and why. It does not say "various fixes".

Common mistakes:
- Listing changes with no reason. Add one short "why" line to each.
- Showing only the default state. Add focus, error and loading.
- Adding a new Figma page for every component. Use frames or sections on the week page.
- Naming a token "blue2". Name it for its job, like "action-primary".

If you get stuck: read `system/README.md` again. Search "design system changelog". Ask in Discord with the component name and what you tried.

##### 6. What to Commit

- [ ] Files: `system/docs/CHANGELOG.md`; `system/README.md`
- [ ] Done when:
  - [ ] Every component has a frame or section on the week page, with all its states.
  - [ ] No new Figma page was added for each component.
  - [ ] The changelog has one line per change, each with a reason.
  - [ ] `system/README.md` says what the system is and how to start.
- [ ] Commit message: `S5.1: sprint 1 system release`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Dark mode test (ID `S5.2`)

##### 1. What We Are Doing

You test a dark mode using your written colour values only. You do not change one single component. You work inside the design tool and you record every tested value in markdown.

##### 2. Why We Are Doing It

A good colour layer sends one change everywhere. This test shows if your colour choices carry meaning or only decoration. It also shows if your written colour list is complete enough for someone else to use.

##### 3. What to Learn First

Read Material 3 colour roles. Look at how colour roles map to light and dark. CSS variables are taught in week 15, so today you do not touch code. You change fills in Figma or Penpot and you write the values down.

##### 4. Where to Find Resources

- Material 3 colour roles: https://m3.material.io/styles/color/roles - read how colour roles map to light and dark.
- WebAIM contrast checker: https://webaim.org/resources/contrastchecker/ - check each text colour pair in dark mode.
- Your own written colour list in `system/`. This is the list you documented in S5.1. If it is not written down yet, write it down now.

##### 5. Step-by-Step Guide

Before you start: use your final colour values from S5.1, written in `system/`. Allow about 20 minutes.

How to think about it:
- Does the error colour still look like an error in the dark?
- Can you still read the photo rules and the OTP code?
- Can another designer repeat this from your written list?

1. Open the written colour list in `system/`. Write a dark value next to each colour. Change colour values only.
2. In Figma: open your existing week page. Copy the three key screens into a new section on the same page. Change the fills and text colours to your dark values. Do not edit the original frames.
3. Penpot equivalent: duplicate the boards on the same page and change the fills to the same dark values.
4. Walk three key screens: photo upload, check your answers, confirmation OTP.
5. Write down every place a component breaks. That list is your finding.
6. Record the exact dark values you used and the contrast ratio of each text pair in `system/docs/dark-mode-test.md`.

Worked example: a button with a fixed grey text colour breaks in dark mode. Notice the fix is a new colour value in the list, not a new button.

Common mistakes:
- Editing the original component or frame to patch dark mode. Change the copy and the colour value instead.
- Choosing dark colours by eye only. Run the contrast checker.
- Keeping the dark values only inside the tool. Write them in the markdown file.

If you get stuck: read the Material 3 colour roles page again. Search "dark mode design tokens". Ask in Discord with a screenshot and what you tried.

##### 6. What to Commit

- [ ] File: `system/docs/dark-mode-test.md`
- [ ] Done when:
  - [ ] Dark mode works with colour value changes only, and no component was edited.
  - [ ] Every break is written down with its cause.
  - [ ] Contrast checked on at least three screens, with the ratios written down.
  - [ ] The exact dark colour values are recorded in the file, so a Penpot or Figma user can repeat them.
- [ ] Commit message: `S5.2: dark mode test`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Debt list (ID `S5.3`)

##### 1. What We Are Doing

You write a list of what your system got wrong or left undone. You write it for the next owner of the system.

##### 2. Why We Are Doing It

Every system has debt (work you owe later). If you hide it, the next person finds it the hard way. A clear list saves weeks. Sprint 4 starts from this list.

##### 3. What to Learn First

Use `06-accessibility-gate.md` to find lines you could not sign with evidence. Use `07-critique-guide.md` to find gaps.

##### 4. Where to Find Resources

- `06-accessibility-gate.md` in the sprint folder. Use the lines you could not sign with evidence.
- `07-critique-guide.md` in the sprint folder. Use its questions to find gaps in your own work.

##### 5. Step-by-Step Guide

Before you start: use your notes from Sprint 1: failures, missing states, parts you skipped. Allow about 30 minutes.

How to think about it:
- What did I skip because of time?
- Which decision will be hard to change later?
- What would confuse a new owner on day one?

1. Write one line for each debt item.
2. Add three things to each line: why it exists, what it costs, and a rough fix.
3. Sort the list into "fix first" and "fix later".
4. Say which item Sprint 4 should start with.

Worked example: "Photo upload has no error state for a file that is too big. Why: I ran out of time. Cost: the candidate sees nothing and tries again. Fix: one error message in Malayalam and English."

Common mistakes:
- Writing "many things" in one line. Write one line per item.
- Blaming a person. Describe the system, not the person.

If you get stuck: read `06-accessibility-gate.md` again. Search "design system debt". Ask in Discord with one debt item and what you tried.

##### 6. What to Commit

- [ ] File: `system/docs/debt.md`
- [ ] Done when:
  - [ ] At least five items, each with a reason and a fix.
  - [ ] Items sorted into "fix first" and "fix later".
  - [ ] One item named as the Sprint 4 starting point.
- [ ] Commit message: `S5.3: debt list`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

### Group 7 - Sprint retro

#### Task - Why session: affordances, signifiers and mental models (ID `F4.1`)

##### 1. What We Are Doing

You write a why session about three ideas. The ideas are affordance (what a thing can do), signifier (the visible clue that shows it can do it), and mental model (what a person expects to happen). Every idea uses something you built or broke in the last four weeks.

##### 2. Why We Are Doing It

These three ideas explain most confusion in forms. If you can name them in your own work, you can fix confusion fast.

##### 3. What to Learn First

Read The Design of Everyday Things (Norman), chapters 1 to 4. Read the parts on affordances and signifiers.

##### 4. Where to Find Resources

- The Design of Everyday Things (Norman), chapters 1 to 4. Read the parts on affordances and signifiers.
- Laws of UX: https://lawsofux.com/ - look for the entries about how people expect things to work.

##### 5. Step-by-Step Guide

Before you start: use your Sprint 1 screens, flow diagram and notes. Allow about 45 minutes.

How to think about it:
- Where did a person expect a button and find plain text?
- Which screen looked like it could be edited, but could not?
- Where did your design break a habit from other websites?

1. Pick three moments from your flow: one affordance, one signifier, one mental model.
2. For each one, write what the person expected, what they saw, and what happened.
3. Write the fix in one line.
4. Keep the whole piece to one page.

Worked example: a lift button with no light is a signifier problem. You press it and nothing says "I heard you". Notice the button works fine. The missing clue is the problem.

Common mistakes:
- Using the three words with no example. Every idea needs a screen from your work.
- Copying the book. Write about your own flow.

If you get stuck: read the Norman chapter again. Search "affordance signifier mental model". Ask in Discord with one example and what you tried.

##### 6. What to Commit

- [ ] File: `fundamentals/why-sessions/week04-affordances.md`
- [ ] Done when:
  - [ ] Three ideas, each with one example from your Sprint 1 work.
  - [ ] Each example says what the person expected and what they saw.
  - [ ] One page, in plain words.
- [ ] Commit message: `F4.1: why session affordances`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Teardown: a subscription cancellation flow (ID `F4.2`)

##### 1. What We Are Doing

You take apart a subscription cancellation flow and write down what it does.

##### 2. Why We Are Doing It

This is where dark patterns live (tricks that push you to do what the company wants). You study them in Sprint 3, so start now. You also see what a fair exit looks like.

##### 3. What to Learn First

Read NN/g heuristic 3, user control and freedom.

##### 4. Where to Find Resources

- `07-critique-guide.md` in the sprint folder. Use its questions on each screen.
- 10 Usability Heuristics: https://www.nngroup.com/articles/ten-usability-heuristics/ - read heuristic 3, user control and freedom.

##### 5. Step-by-Step Guide

Before you start: use a subscription you can cancel, or screenshots of one cancellation flow. Allow about 45 minutes. Do not cancel a service you still need. Use screenshots if you are unsure.

How to think about it:
- How many steps to join, and how many to cancel?
- Does the flow use a colour or a word to make you feel bad?
- Can you leave by yourself, or must you ask a person?

1. Count the steps to join. Count the steps to cancel. Write both numbers.
2. Save a screenshot of each cancellation step, from your own account only. Hide your name and card details.
3. Name each dark pattern you see, in plain words.
4. Say what a fair version would look like.

Worked example: think of a shop with one door for entering and the same door for leaving. Notice the exit is as easy to find as the entrance.

Common mistakes:
- Writing "bad design" and stopping there. Name the pattern and the step where it appears.
- Sharing your own personal data. Hide it before you save the file.

If you get stuck: read `07-critique-guide.md` again. Search "dark patterns cancellation". Ask in Discord with one screenshot and what you tried.

##### 6. What to Commit

- [ ] File: `fundamentals/teardowns/04-cancellation-flow.md`
- [ ] Done when:
  - [ ] Step counts for joining and for cancelling.
  - [ ] Every dark pattern named, with its step.
  - [ ] One short paragraph on what a fair version looks like.
- [ ] Commit message: `F4.2: cancellation flow teardown`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Explainer (ID `F4.3`)

##### 1. What We Are Doing

You write one page that explains one Sprint 1 idea. The reader has never designed anything.

##### 2. Why We Are Doing It

If you cannot explain an idea simply, you know the words but not the idea. This is also the skill you use in a job interview.

##### 3. What to Learn First

Check every special word in `08-glossary.md`. Look at how Shopify Polaris writes for non-experts.

##### 4. Where to Find Resources

- `08-glossary.md` in the sprint folder. Check every special word you use.
- Shopify Polaris content guidance: https://polaris.shopify.com/content - see how it writes for non-experts.
- Practical Typography: https://practicaltypography.com/ - for a clean one-page layout.

##### 5. Step-by-Step Guide

Before you start: pick one idea from Sprint 1. For example, why the photo rules appear before the upload. Allow about 40 minutes.

How to think about it:
- Would my neighbour understand this after one read?
- Did I use a word I have not explained?
- Can I show it with a small example instead of a definition?

1. Choose one idea. Write it in one sentence.
2. Explain it again in three short sentences, with an example.
3. Read it aloud. Cut every word a beginner would not say.
4. Ask one person outside this course to read it. Write down their questions.

Worked example: instead of "progressive disclosure", write: "We show one question at a time, so the page does not look scary." Notice the plain version needs no design word.

Common mistakes:
- Using design words. Replace each one with a plain sentence.
- Explaining many ideas. Keep one.

If you get stuck: read `08-glossary.md` again. Search "plain language design". Ask in Discord with one sentence and what you tried.

##### 6. What to Commit

- [ ] File: `fundamentals/explainers/sprint1-{topic}.md`
- [ ] Done when:
  - [ ] One page, one idea.
  - [ ] No design jargon, or each term explained in the same line.
  - [ ] One non-designer has read it and you wrote their questions down.
- [ ] Commit message: `F4.3: explainer`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

#### Task - Drill log review (ID `F4.4`)

##### 1. What We Are Doing

You read every drill entry you have from Week 1 to Week 3 and find the mistakes you make again and again from memory. Week 4 has no new drill task, so the entries stop at Week 3.

##### 2. Why We Are Doing It

A mistake you repeat is a blind spot (a thing you cannot see in your own work). Once you know it, you can check for it on purpose. That makes you faster and safer.

##### 3. What to Learn First

Use Refactoring UI chapters 1 to 6 and 8 to name what you got wrong.

##### 4. Where to Find Resources

- Your own drill log files from Week 1 to Week 3.
- Refactoring UI, chapters 1 to 6 and 8. Use it to name what you got wrong.

##### 5. Step-by-Step Guide

Before you start: use every drill entry assigned in Week 1 to Week 3. Allow about 30 minutes.

How to think about it:
- Which mistake appears three times or more?
- Is it about spacing, type, colour or alignment?
- What one check will catch it next time?

1. Read every entry. Mark every mistake you made.
2. Count how often each mistake appears. Write the counts down.
3. Pick the top one or two. Write one check you will do every time.
4. Write three lines on what you will watch in Sprint 2.

Worked example: if your buttons always have uneven padding, your check is simple. Measure the space on the left and on the right before you finish.

Common mistakes:
- Reading fast and marking nothing. Mark each entry as you read it.
- Picking five mistakes to fix. Pick one or two you can really change.

If you get stuck: read your own drill log again. Search "spacing mistakes UI". Ask in Discord with one repeated mistake and what you tried.

##### 6. What to Commit

- [ ] File: `students/UX{n}/week4/F4-4-drill-log-review.md`
- [ ] Done when:
  - [ ] Every drill entry from Week 1 to Week 3 read and marked.
  - [ ] Counts written for each repeated mistake.
  - [ ] One or two checks written for Sprint 2.
- [ ] Commit message: `F4.4: drill log review`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

### Group 8 - Job readiness

#### Task - Position yourself and start the portfolio (ID `JR1`)

##### 1. What We Are Doing

You start the job readiness track with JR1. You position yourself and start your portfolio.

##### 2. Why We Are Doing It

A portfolio needs a clear position before you build pages. JR1 sets that direction.

##### 3. What to Learn First

Read section JR1 in `06-Job-Readiness-Track.md` before you start.

##### 4. Where to Find Resources

- Full method and done-when checklist: `06-Job-Readiness-Track.md` (repository root), section JR1.

##### 5. Step-by-Step Guide

Before you start: open `06-Job-Readiness-Track.md` at section JR1. Allow 2 hours.

1. Read section JR1 in `06-Job-Readiness-Track.md`.
2. Follow each step in that section.
3. Save your work at the path below.

If you get stuck: read section JR1 again. Ask in Discord with a screenshot and what you tried. If a tool blocks you, check `../04-Tools-Setup.md`.

##### 6. What to Commit

- [ ] File: `students/UX{n}/portfolio/JR1-positioning.md`
- [ ] Done when:
  - [ ] Full method and done-when checklist in `06-Job-Readiness-Track.md`, section JR1, is complete.
- [ ] Commit message: `JR1: positioning`
- [ ] Allowed here: .md; PNG/JPG under 2 MB; PDF; small .html, .css and .js files in a code folder; view-only Figma or Penpot link in .md.

## 6. What to Commit

Sprint 1 done when:

- [ ] 20 learning summaries across 4 weeks
- [ ] Every week's tasks committed
- [ ] Accessibility gate signed, with evidence on every line
- [ ] Handoff spec complete
- [ ] Decision record written
- [ ] Post mortem written. This is `students/UX{n}/week4/P4-2-reflection.md` (P4.2), plus the S5.3 debt list for the system
- [ ] Defense passed, or a re-run scheduled in the buffer week
- [ ] Reflection written
- [ ] System released with a changelog and a debt list
- [ ] 4 teardowns, 1 explainer, and every drill entry assigned from Week 1 to Week 3
- [ ] JR1 done, with the external input it needs

If you are short on time, cut in this order: F4.4 drill log review, F4.2 teardown, S5.2 dark mode test, C8.2 desktop. A cut task is deferred to the buffer week, not dropped. The sprint stays incomplete until every deferred task is completed and committed. Do not cut the accessibility gate, the defense, P4.2, or the Sprint 1 checklist.

When your files are ready, open one pull request for the week. The steps are in `../10-GitHub-For-Designers.md`.

Next: `../Design-Sprint-2/00-READ-FIRST.md`
