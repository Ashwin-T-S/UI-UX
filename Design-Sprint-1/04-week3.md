# Week 3 - Test and Fix

**Sprint 1, week 3 of 4. Theme: every state a screen can be in, and what real users do to your design. This is the week when something breaks. A rule changes in the middle of the week. You do not know which one yet.**

## Week at a Glance

| Task ID | Task name | Time | File you will commit |
|---|---|---|---|
| - | Day 1 learn: response time, empty states, heuristic 1 | 90 min | `students/UX{n}/week3/session1-learning.md` |
| C5.1 | States matrix | 60 min | `students/UX{n}/week3/C5-1-states-matrix.md` |
| C5.2 | Empty and loading states | 40 min | `students/UX{n}/week3/C5-2-empty-loading.md` |
| - | Day 2 learn: how to write and run a test | 90 min | `students/UX{n}/week3/session2-learning.md` |
| R2.1 | Write the test script | 45 min | `students/UX{n}/week3/R2-1-test-script.md` |
| R2.2 | Session 1 | 75 min | `students/UX{n}/week3/R2-2-session1.md` |
| - | Day 3 learn: notes into problems | 60 min | `students/UX{n}/week3/session3-learning.md` |
| R2.3 | Sessions 2 and 3 | 90 min | `students/UX{n}/week3/R2-3-sessions-2-3.md` |
| R2.4 | Findings and severity | 45 min | `students/UX{n}/week3/R2-4-findings.md` |
| - | Day 4 learn: heuristic audit vs real users | 45 min | `students/UX{n}/week3/session4-learning.md` |
| C5.3 | Offline and interruption states | 60 min | `students/UX{n}/week3/C5-3-offline-states.md` |
| C6.1 | Fix what testing found | 60 min | `students/UX{n}/week3/C6-1-fixes.md` |
| - | Critique | 90 min | No new file. Bring C6.1. |
| - | Whiteboard why (with the admin) | 15 min | No file. |
| X1 | Post mortem | 45 min | `students/UX{n}/week3/X1-post-mortem.md` |
| P3.1 | Revised decisions | 40 min | `students/UX{n}/week3/P3-1-revised-decisions.md` |
| S3.1 | Add the states to the components | 30 min | `system/components/{component}.md` |
| S3.2 | Component contribution rule | 25 min | `system/docs/contribution-rules.md` |
| S3.3 | Handle the injection at system level | 25 min | `system/docs/decisions/{nn}-{topic}.md` |
| F3.1 | Why session: cognitive load and progressive disclosure | 20 min | `fundamentals/why-sessions/week03-cognitive-load.md` |
| F3.2 | Teardown: hospital appointment booking | 20 min | `fundamentals/teardowns/03-hospital-booking.md` |
| F3.3 | Drill continues | 15 min | `students/UX{n}/week3/F3-drill.md` |
| L-PR1 | Lab: responsive behaviour and platform conventions | 2 h | `students/UX{n}/week3/L-PR1-responsive.md` |
| Z3.1 | Code corner: box model and flexbox | 30 min | `students/UX{n}/week3/z3-1-flex-component.html` and `students/UX{n}/week3/z3-1-flex-component.png` |

About 20 hours 35 minutes of work in this week.

## 1. What We Are Doing

You list every state your screens can be in. Then you test your prototype with three real people, and you fix what the test shows you. A new constraint arrives on Day 5, and you write a short report about it. On the last day you update the shared system and run two fundamentals sessions.

- Group 1 - States, empty and loading: C5.1, C5.2
- Group 2 - Usability test: R2.1, R2.2, R2.3, R2.4
- Group 3 - Offline states, fixes, critique: C5.3, C6.1
- Group 4 - The surprise change: X1, P3.1
- Group 5 - System update: S3.1, S3.2, S3.3
- Group 6 - Fundamentals: F3.1, F3.2, F3.3
- Group 7 - Lab: L-PR1
- Group 8 - Code corner: Z3.1

## 2. Why We Are Doing It

In a real product team in India, a designer is judged on two things: does the work hold up when the data is bad, and does it survive a change of plan. This week gives you both. A working designer spends more time on empty, loading, error and offline states than on the pretty first screen, because those are the moments where people give up.

For the project, the Kerala PSC brief has a user called Suresh. He has a cheap phone and his data drops. Your week 2 screens only show the happy path. This week you design what he sees when things go wrong.

For your portfolio, the states matrix, the three test notes and the post mortem are hard evidence. Anyone can show a nice screen. Very few juniors can show a change they made because a real person got stuck, with the reason written down.

## 3. What to Learn First

By the end of the week you can:

- Make a full states matrix (a table that lists every state a screen can be in). Design the states that people often forget.
- Run a usability test (you watch a person use your design) with three people. Do not lead them to the answer.
- Link every design change to one finding from a test.
- Write a post mortem (a short report you write after a change you did not choose).

Core ideas to review first:

- Response time bands: 0.1 seconds feels instant, 1 second keeps the thought going, after about 10 seconds attention is lost. The band decides the loading treatment, not taste.
- Heuristic 1, visibility of system status: does the screen tell the person what is happening now?
- A task gives a goal, never a route. "Order one meal and pay" is a task. "Tap the basket, then pay" is a route.
- What you saw and what you think are two different columns. Never mix them.
- Severity 1 to 4: 1 is a small annoyance, 4 is the person cannot finish or may submit a wrong application.
- Cognitive load (the mental effort to read and choose) and progressive disclosure (show the most important thing first, the rest later).

## 4. Where to Find Resources

### Your week in order

| Day | Source | What exactly | Time |
|---|---|---|---|
| 1 | **Refactoring UI**, book in `Resources/`, site https://www.refactoringui.com/ | Ch. 8. Read the part called "Don't overlook empty states". | 25 min |
| 1 | **Laws of UX** https://lawsofux.com/ | Find the page on response time (Doherty Threshold). Write down the time it gives. | 20 min |
| 1 | **NN/g** https://www.nngroup.com/articles/ten-usability-heuristics/ | Heuristic 1, "Visibility of system status". Ask: does the screen tell the person what is happening? | 20 min |
| 1 | **Your own week 2 work** | Open your P2.1 flow drawing. Write the name of every screen in the flow. | 25 min |
| 2 | **Rocket Surgery Made Easy**, Krug (borrow or buy, see `../03-Books-And-Resources.md`) | Chapters 1 to 4. Short and practical. | 50 min |
| 2 | **Don't Make Me Think**, Krug | The chapter on usability tests. | 20 min |
| 2 | **NN/g**, 10 Usability Heuristics https://www.nngroup.com/articles/ten-usability-heuristics/ | Read rules 1, 2 and 9. They help you write probe questions. | 20 min |
| 3 | **Rocket Surgery Made Easy** | Chapters 5 to 7. How to turn test notes into a short list of problems. | 30 min |
| 3 | **NN/g**, 10 Usability Heuristics | Read the 10 rule names. Use them to name each problem. | 20 min |
| 3 | **Your own R2.2 notes** | Re-read them before session 2. Find the problems you already know. | 10 min |
| 4 | **Your own week 1 and week 3 files** | Re-read your R1.2 heuristic audit, then your R2.4 findings. Write three lines: which week 1 findings did real users hit, which did they never notice, what does this say about the limits of heuristic evaluation? | 45 min |
| all week | Material 3 colour roles https://m3.material.io/styles/color/roles | Reference for state colour. | as needed |
| all week | Shopify Polaris content guidance https://polaris.shopify.com/content | Short, plain words in your messages. | as needed |
| all week | WCAG 2.2 quick reference https://www.w3.org/WAI/WCAG22/quickref/ | For the accessibility checks. | as needed |

Day 1 takeaway: the three time limits above decide your loading treatment. If you want the source article on response time, ask your admin.

Day 2 takeaway: Krug says three users find most of the problems. Talk very little. The best question is "what are you trying to do?". The worst is "did you see the button up there?".

Day 4 takeaway: heuristic evaluation finds things a test misses, and a test finds things heuristics miss. Knowing which is which is a real skill.

### Tools you open

- **Figma (free Starter plan)** for every design task in this week. Setup guide: `../04-Tools-Setup.md`, section on Figma.
- **Penpot** (https://penpot.app/) as the backup if the Figma file limit blocks you. Setup guide: `../04-Tools-Setup.md`, section on Penpot.
- **A browser and your phone** to run the three test sessions. No install.
- **VS Code** for the code corner. Setup guide: `../04-Tools-Setup.md`, section on VS Code.
- **Figma Learn** https://help.figma.com/ for components, variants and states.

File hygiene rule for this sprint: ONE Figma file per sprint, named `SPRINT-1 UX{n}`, with one page per week. Do not make three files per sprint. The Starter plan allows 3 files in total, so keep the shared system in tokens (markdown or JSON) inside `system/`.

A shared library needs verified plan access that supports libraries, for example the Figma Education plan or a paid plan. Admin permission alone is not enough, because the Starter plan has no libraries. If your access is not verified, keep the shared system in tokens in `system/` and share it with a view-only link.

### Search keywords when you are stuck

- empty state design examples
- skeleton screen loading state
- usability test task writing
- severity rating usability problem
- offline error state mobile
- CSS box model flexbox

## 5. Step-by-Step Guide

> All `students/...` paths in this week are inside your sprint folder (`Design-Sprint-N/`). Open a terminal in the repo root and use full paths.

One task, one commit containing all files listed for that task. Do not put two tasks in one commit. The branch and pull request steps are in `../10-GitHub-For-Designers.md`.

### Group 1 - States, empty and loading (Day 1)

Do the Day 1 learn block first, then commit `students/UX{n}/week3/session1-learning.md` with the message `week3 day1 learning notes`.

Start the daily drill today. It is 15 minutes a day, from Day 1 to Day 5. The steps, the schedule and the file path are in task F3.3, at the end of this week.

#### Task - States matrix (ID `C5.1`)

##### 1. What We Are Doing
You build one table. The rows are your screens. The columns are the states each screen can be in. At the end you see, in one place, which states you designed and which you did not.

##### 2. Why We Are Doing It
A screen is never only the happy path. A list can be empty. An upload can fail. If nobody designs these states, the developer makes them up, and usually badly. This table is also your to-do list for the rest of the week.

##### 3. What to Learn First
- How a states table looks and reads.
- Your own flow from week 2, task P2.1, so you know your rows.

##### 4. Where to Find Resources
- Refactoring UI, Ch. 8, the part "Don't overlook empty states". Book in `Resources/`.
- https://www.nngroup.com/articles/ten-usability-heuristics/ heuristic 1. Look for "what is the system doing now?".
- Your P2.1 flow drawing. Every box in it becomes one row.

##### 5. Step-by-Step Guide
1. Open a new markdown file.
2. Write rows: every screen in your flow. For example the notification list, the profile check, the photograph upload, the confirmation, the admission ticket, my applications.
3. Write columns: default, empty, loading, partial, error, success, offline, permission denied, zero results, first run, destructive confirm.
4. Fill every cell with one of three things: **N/A** with a reason, **exists** with a link to the file and screen where you designed it, or **missing**.
5. Write the reason under every N/A. "This screen is never empty" is true only if you can say why.
6. Count the missing cells.
7. Write that number at the top of the file. That number is the honest state of your design.
8. Make a list of the missing cells at the end. That list is your to-do list.

Worked example, two rows:

| Screen | default | empty | loading | offline | error |
|---|---|---|---|---|---|
| Notification list | C3.1 | C3.1: "No notices match your choice" | missing: the list can be slow on a weak phone | missing: data drops while the list loads | C4.2 |
| Photograph upload | C3.4, state 1 | N/A: the screen always asks for a file. Reason written in the file. | C3.4, progress state | missing: data drops at 90 per cent | C3.4, states 2 and 3 |

Notice two things. The N/A has a reason next to it. The missing cells are named, not hidden.

Common mistakes:
- Writing "missing" and stopping there. Fix: add the missing cells to the list at the end.
- Writing N/A in every cell to look clean. Fix: a reader cannot check it, so it is worth nothing.
- Describing the real website instead of your own design. Fix: the rows are your screens.
- One row called "the whole flow". Fix: each screen gets its own row.

If you get stuck:
- Re-read the worked example above and copy its shape, not its words.
- Search the keyword "empty state design examples".
- Ask in Discord with a screenshot of your table and what you tried.

How to think about it:
- Would this screen ever open with nothing in it? For whom, and when?
- What does the person see in the first second, before anything loads?
- What if the phone loses data in the middle of this screen?
- "N/A" is a real answer only if you can say why in one short sentence.

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/C5-1-states-matrix.md`
- [ ] Every screen has a row, and every column is filled
- [ ] Every N/A has a stated reason in one sentence
- [ ] The number of missing cells is written at the top of the file
- [ ] Every "exists" links to the file where it lives
- [ ] Commit message: `C5.1 states matrix`

#### Task - Empty and loading states (ID `C5.2`)

##### 1. What We Are Doing
You design two empty states and two loading states from your matrix. You write the real words for each one.

##### 2. Why We Are Doing It
"No data" tells the person nothing. An empty screen is a moment when someone is lost and needs a next step. A spinner that flashes for a moment looks like a fault. Both are small screens with a big effect on trust.

##### 3. What to Learn First
- The four duration bands and the treatment for each one.
- What a skeleton is: a grey shape that holds the space while content loads.

##### 4. Where to Find Resources
- Refactoring UI, Ch. 8, the empty state examples.
- https://www.nngroup.com/articles/ten-usability-heuristics/ heuristic 1. Check that your loading state says what is happening.
- https://polaris.shopify.com/content for short, plain words.
- Tool: Figma. Setup guide: `../04-Tools-Setup.md`, section on Figma. If the file limit blocks you, use Penpot (https://penpot.app/), setup in `../04-Tools-Setup.md`, section on Penpot.

##### 5. Step-by-Step Guide
1. From your matrix, pick the two empty states that matter most.
2. From your matrix, pick the two loading states that matter most.
3. Write one line for each pick: why it matters most.
4. For each empty state, write what would be here.
5. Write why it is not here.
6. Write what to do next. "No data" is a failure.
7. For each loading state, choose a treatment from the table below.
8. Write the expected duration for each loading state.
9. Write where that estimate came from.
10. Check that the page does not move when the content arrives.
11. Use a skeleton to hold the space.
12. Design both states in Figma, on page `W3` of your file `SPRINT-1 UX{n}`.

| Expected duration | Treatment |
|---|---|
| Under 1s | Nothing. Do not flash a spinner. |
| 1 to 3s | A small spinner or a skeleton, with the layout held still |
| 3 to 10s | A progress sign, with a message about what is happening |
| Over 10s | Do not make them wait. Confirm receipt and tell them you will let them know later. |

These four bands are the guide for this course. Use them, and say so in your file.

Worked example, empty state for "My applications":

- Screen: My applications, when there are none.
- Weak: "No applications found."
- Good heading: "You have not started any application yet."
- Good body: "An application you send will show here. Open one to see what happens next."
- Good action: "Find a post"

Worked example, loading state for the same area: show the shape of three rows, plus the words "Loading today's notices."

Common mistakes:
- "No data." Fix: say what belongs here, why it is empty, and the next step.
- A spinner for a very short wait. Fix: show nothing.
- A long wait with no message. Fix: say what is happening.
- Content that jumps into place. Fix: hold the space with a skeleton.

If you get stuck:
- Re-read the duration table and put each of your states in one band.
- Search the keyword "skeleton screen loading state".
- Ask in Discord with your two screenshots and the band you chose.

How to think about it:
- After reading this screen, would the person know what to do next?
- Is the wait short or long? Say where your time estimate came from.
- Does the layout jump when the content arrives?
- Is there a moment when the person cannot tell if their action worked?

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/C5-2-empty-loading.md`
- [ ] Two empty states, each saying what belongs here, why it is empty, and what to do
- [ ] Two loading states, each with an expected duration and the source of that estimate
- [ ] Each treatment matches its duration band
- [ ] The layout does not move when content arrives
- [ ] Commit message: `C5.2 empty and loading states`

### Group 2 - Usability test (Day 2 and Day 3)

Do the Day 2 learn block, then commit `students/UX{n}/week3/session2-learning.md` with the message `week3 day2 learning notes`. Do the Day 3 learn block, then commit `students/UX{n}/week3/session3-learning.md` with the message `week3 day3 learning notes`.

#### Task - Write the test script (ID `R2.1`)

##### 1. What We Are Doing
You write three tasks, some probe questions and a consent script. At the end you have a plan you can run with three people.

##### 2. Why We Are Doing It
Without a script you will help people by accident. Then you learn nothing from the session. A written script keeps every session the same, so you can compare them.

##### 3. What to Learn First
- How Krug turns a goal into a task.
- What a probe question is: a short open question that does not name anything on the screen.

##### 4. Where to Find Resources
- Rocket Surgery Made Easy, chapters 2 and 3. `../03-Books-And-Resources.md` says where to get it.
- https://www.nngroup.com/articles/ten-usability-heuristics/ rule 1, to write a probe question about what the person expects to see.
- `07-critique-guide.md` in this sprint folder, for writing what you see and not what you think.

##### 5. Step-by-Step Guide
1. Write a plain text file for the script.
2. Write task 1: finding the right post in the Notifications list.
3. Write task 2: applying from the profile.
4. Write task 3: confirming for an exam post and getting the admission ticket.
5. Check each task gives a goal, never a route. Bad: "Click Apply Now, then open your profile." Good: "You want to apply for a post you found in the Notifications list. Start here."
6. Write your probe questions. Allowed: "what are you trying to do?", "what do you expect to happen?", "what does that mean to you?". Not allowed: any question with a button name in it.
7. Write the consent script. Say what you record, what you do with it, that they can stop at any time, that you test the design and not them, and that you will not keep their name or their photo.
8. Write your own session rules: no help for the first 60 seconds of a struggle, no explaining, no defending the design.

Worked example, a different case, a food delivery app:
- Weak task: "Tap the basket icon, then tap pay."
- Good task: "Order one meal and pay for it. Start here."

The weak version tells you the route. The good version says what the person wants, so you learn where they look first and where they stop.

Common mistakes:
- The task names a button. Fix: delete the name, keep the goal.
- All three tasks sit on one screen. Fix: spread them over the whole journey.
- The probe question gives a hint, like "did you notice the photo rule?". Fix: ask "what do you expect here?".
- No consent script. Fix: write it before you invite anyone.

If you get stuck:
- Re-read the good and weak examples above and mark each of your tasks as goal or route.
- Search the keyword "usability test task writing".
- Ask in Discord with your three tasks pasted in.

How to think about it:
- Would a person who has never seen my design know where to start?
- Does my task give a goal and not a route?
- Could the person finish the task in more than one way? If yes, good.
- What would I say if they get stuck? Write it down, then delete it.

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/R2-1-test-script.md`
- [ ] Three tasks, each with a goal and no route
- [ ] The three tasks cover finding a post, applying, and confirming plus the admission ticket
- [ ] Probe questions written down, and none names a screen element
- [ ] Consent script written, and it says "you can stop at any time"
- [ ] Your own no-help rule written down before you start
- [ ] Commit message: `R2.1 test script`

#### Task - Session 1 (ID `R2.2`)

##### 1. What We Are Doing
You find three people and run the first test session with one of them. You run all three tasks from R2.1. You record what they do and what they say. You do not explain your design.

##### 2. Why We Are Doing It
A real person will get stuck in places you cannot see any more. Their struggle is your best design feedback. If you help them, you lose that feedback for ever.

##### 3. What to Learn First
- Krug chapter 4: how to run a session and stay quiet.
- The four note columns: what they did, what they said, where they hesitated, what they expected.

##### 4. Where to Find Resources
- Rocket Surgery Made Easy, chapters 3 and 4.
- Don't Make Me Think, the usability testing chapter.
- `07-critique-guide.md` in this sprint folder, for the note format.

##### 5. Step-by-Step Guide
1. Find three people who are not designers. Ideally each one has applied for a government job before. Try a neighbour, a shop worker or a relative.
2. Ask each person for one hour. Say clearly that you test your own design and not them.
3. Give each person a code: P1 for session 1, P2 for session 2, P3 for session 3. Never write a phone number, an address, a date of birth or a photo.
4. Open your prototype at the start screen.
5. Get your notes ready. Written notes are the default in this course. You need one page and a pen, or a text file.
6. Read the consent script from R2.1 out loud.
7. Ask the person to say yes to taking part.
8. If you plan to record, read the recording section below first, then ask for permission. If the person says no, take written notes only.
9. Show the first screen. Read task 1 from R2.1 out loud.
10. Stay quiet. Use a probe question only after a long pause.
11. Take notes in four columns only: what they did, what they said, where they hesitated, what they expected.
12. When task 1 is finished, say "thank you, next task".
13. Show the start screen again.
14. Read task 2 from R2.1 out loud.
15. Stay quiet again for the first 60 seconds of a struggle. Use the same four columns.
16. When task 2 is finished, say "thank you, next task".
17. Show the start screen again.
18. Read task 3 from R2.1 out loud.
19. Stay quiet again. Use the same four columns.
20. Do not write what you think it means. That work comes in R2.4, on purpose.
21. After the person leaves, write down every time you broke your own no-help rule.

Recording, only if you choose it:
- Written notes are enough. Most people in this cohort never record.
- Mac: QuickTime Player is built into macOS. Open QuickTime Player, choose File, then New Screen Recording. Choose the microphone. Start.
- Windows: Xbox Game Bar is built into Windows. Press the Windows key and G. Choose the capture button. Check the microphone is on.
- Do not commit a recording. Do not share a recording in Discord. A recording can show a person's voice or face. Keep it on your own device and delete it when the week ends.

Worked example, a different case, testing a train ticket app with a friend: "P1 held the phone with one hand. P1 said 'where is my ticket?'. P1 tapped three different icons. P1 expected the ticket at the top of the screen." There is no opinion in that note. Your opinion comes later, in a different file.

Common mistakes:
- You help in the first 30 seconds. Fix: count to 60 in your head.
- You write "the button is confusing". Fix: write "P1 tapped it twice and said 'nothing happened'".
- You keep a person's name and phone number. Fix: use a code, and say why.
- You test on the live website and enter real details. Fix: test only your own prototype. Never log in, register or submit on the real site.
- You run only task 1. Fix: run tasks 1, 2 and 3 with the same method.

If you get stuck:
- Re-read the four note columns and use them as the only headings in your notes.
- Search the keyword "usability test moderation do not help".
- Ask in Discord with one of your notes and the moment you were unsure.

How to think about it:
- Am I writing what happened, or what I think it means?
- Would another designer read my notes and see the same scene?
- Did I stay quiet for the first 60 seconds?
- Is any personal detail in my notes? If yes, remove it now.

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/R2-2-session1.md`
- [ ] Three people asked, and one session run with P1, all three tasks
- [ ] Consent to participate obtained. Recording consent obtained if recording, otherwise written notes only.
- [ ] Notes in the four-column format, with a code and no personal data
- [ ] Zero interpretation in the notes
- [ ] Every time you broke your own no-help rule is written down honestly
- [ ] Commit message: `R2.2 session 1 notes`

#### Task - Sessions 2 and 3 (ID `R2.3`)

##### 1. What We Are Doing
You run session 2 and session 3 of your usability test. Each session is one person using your prototype. Every person does all three R2.1 tasks, in the same order.

##### 2. Why We Are Doing It
One person can be a coincidence. Three people show a pattern. A pattern tells you what to fix first. You can only compare the three sessions if each person did the same tasks in the same order.

##### 3. What to Learn First
- How to run a session and stay quiet. Rocket Surgery Made Easy, chapters 5 to 7.
- Consent: the person says yes to take part.

##### 4. Where to Find Resources
- Rocket Surgery Made Easy, chapters 5 to 7.
- `07-critique-guide.md` in the sprint folder, to describe a problem in plain words.

##### 5. Step-by-Step Guide
1. Set up your prototype on the same phone size and language as R2.2. Do not change the design.
2. Read the consent script you wrote in R2.1. Ask the person to say yes.
3. Do not write their name. Use P2 for session 2 and P3 for session 3.
4. Read task 1 from R2.1 out loud, word for word.
5. Ask the person to think aloud.
6. Do not help. If they ask, say "What would you do next?"
7. Write what they do and say in the same four columns as R2.2.
8. When task 1 is finished, show the start screen again.
9. Read task 2 from R2.1 out loud, word for word.
10. Keep the same four columns.
11. When task 2 is finished, show the start screen again.
12. Read task 3 from R2.1 out loud, word for word.
13. Keep the same four columns.
14. Use the same three tasks, in the same order, for every person. This is the only way to compare P1, P2 and P3.
15. If something is very bad, write it down and keep going. Do not fix it now.
16. After the session, ask three short questions: what was easy, what was hard, what would you change?
17. Run session 3 the same way, with P3 and the same three tasks.
18. Do not change the prototype between session 2 and session 3.

Worked example: P2 is using a cinema booking site and stops at the seat map. You write: "P2 opened the seat map and did not move for 30 seconds. P2 said, 'Which seat is good?'" You do not write: "P2 was confused."

Common mistakes:
- You help when they get stuck. Fix: stay quiet and write down the moment.
- You change a screen after session 2. Fix: wait until all three sessions end.
- You write "the user was confused". Fix: write the exact action, for example "stopped at the photo step for 40 seconds".
- You collect names or phone numbers. Fix: use P1, P2 and P3.
- You use the live site in the test. Fix: use your prototype only.
- You swap the task order. Fix: every person gets tasks 1, 2 and 3 in the same order.

If you get stuck:
- Re-read the note format from R2.2 and copy your own columns.
- Search the keyword "think aloud usability test".
- Ask in Discord with the task you gave and the moment the person stopped.

How to think about it:
- Can the person find the next step alone?
- Where do they stop and look lost?
- What do they say they expect to happen?
- Are you helping too much?

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/R2-3-sessions-2-3.md`
- [ ] Three people did a session, or you wrote why not
- [ ] Each session has a short note with exact actions
- [ ] Every person did all three R2.1 tasks, in the same order
- [ ] Your notes have no personal data
- [ ] You did not change the prototype between sessions
- [ ] You wrote down the task you gave each person
- [ ] Commit message: `R2.3 sessions 2 and 3 notes`

#### Task - Findings and severity (ID `R2.4`)

##### 1. What We Are Doing
You turn your three session notes into one list of problems. You give each problem a severity score (how bad the problem is).

##### 2. Why We Are Doing It
A long list of problems does not help the team. You need to know which problems stop people. The team must fix the worst first.

##### 3. What to Learn First
- How to separate what you saw from what you think.
- The severity scale: 1 small annoyance, 2 slows the person, 3 the person may fail, 4 the person cannot finish, or may submit a wrong application.

##### 4. Where to Find Resources
- Rocket Surgery Made Easy, chapters 5 to 7, for turning notes into a short list.
- `07-critique-guide.md` in the sprint folder, to write a problem in plain words.
- https://www.nngroup.com/articles/ten-usability-heuristics/ to name the kind of problem.

##### 5. Step-by-Step Guide
1. Make one row for each problem. A problem is something that happened in a session.
2. Point every row at a note from R2.2 or R2.3. If a row has no note, delete the row.
3. Use these columns: What I saw, People (of 3), Severity, Why I think it happened, What I will change.
4. Write "What I saw" as an action. Example: "P2 stopped at the photo step and said, 'I do not know if this photo is good.'"
5. Put your guess in the "Why" column. Do not mix it with the observation.
6. Give every problem a severity from 1 to 4, using the scale above.
7. If all three people did the same thing, write "3/3". That is one strong signal. Do not count it as three separate problems.
8. For every severity 3 or 4, write one clear change. The change must remove the cause, not hide the symptom.
9. Use a post ID format like `Cat.No.812/2025` when a problem is about the category number. For exam posts, confirmation is a separate step after Submit.

Worked example: a different product, a food delivery app. These rows show the shape only. Do not copy them. Your rows must come from your own notes in R2.2 and R2.3.

| What I saw | People (of 3) | Severity | Why I think it happened | What I will change |
|---|---|---|---|---|
| P1 and P3 tapped Checkout, then looked for the total price for more than 20 seconds. | 2/3 | 3 | The total price appears only after the address step. | Show the total price on the Checkout button. |
| All 3 people went back to the menu after filling the address, to add one more item. | 3/3 | 2 | The basket button sits at the bottom of the page and is easy to miss. | Keep the basket button visible at the top of the page. |
| P2 pressed Place order, then said, "did it work?". | 1/3 | 4 | The confirmation message appears below the fold. | Put the confirmation text and the order number at the top of the screen. |

Common mistakes:
- You write "the user was confused". Fix: write the exact action and words.
- You mix what you saw with what you think. Fix: two separate columns.
- You treat 3/3 as three problems. Fix: one row with "3/3".
- You give every problem severity 4. Fix: use the full scale. Small annoyances are common.
- You write a row that no session note supports. Fix: delete it, or point it at the note.

If you get stuck:
- Re-read one of your notes and split it into two columns on paper first.
- Search the keyword "severity rating usability problem".
- Ask in Discord with your table and the severity you are unsure about.

How to think about it:
- Would this problem stop a person from finishing?
- Would it make them submit a wrong application?
- Is it a small annoyance or a block?
- Did all three people do the same thing?

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/R2-4-findings.md`
- [ ] Every issue from all three sessions is listed
- [ ] Every row points at a note from R2.2 or R2.3
- [ ] What I saw and why I think it happened are in separate columns
- [ ] Every issue has a severity from 1 to 4
- [ ] Every severity 3 or 4 has one stated change
- [ ] The file has no personal data
- [ ] Commit message: `R2.4 findings and severity`

### Group 3 - Offline states, fixes, critique (Day 4)

Do the Day 4 learn block first, then commit `students/UX{n}/week3/session4-learning.md` with the message `week3 day4 learning notes`.

#### Task - Offline and interruption states (ID `C5.3`)

##### 1. What We Are Doing
You design five states for Suresh when his phone loses connection. A state is what the screen shows at one moment. The states cover the start, the profile check, the photo upload, Submit, and coming back.

##### 2. Why We Are Doing It
Suresh uses a cheap phone and his data drops. If the screen does not say what happened, he may submit twice. He may also stop and lose his chance to apply.

##### 3. What to Learn First
- What an acknowledgement is: the message that says the application is received.
- Your own notes on Suresh, and your C5.1 matrix.

##### 4. Where to Find Resources
- GOV.UK error message guidance https://design-system.service.gov.uk/components/error-message/ Look at how a message says what happened and what to do next.
- The sprint glossary `08-glossary.md`, for any word you do not know.
- Your C5.1 matrix and your C5.2 states.

##### 5. Step-by-Step Guide
1. Draw offline before starting. Suresh opens the notification list and finds no connection.
2. Show what he sees.
3. Show what he can do.
4. Draw connection lost during the profile check, after he types something.
5. Say if his typed details stay.
6. Say how he knows they stay.
7. Draw connection lost during the photograph upload.
8. Say what happens to the part that uploaded.
9. Say how he can try again.
10. Draw connection lost after he presses Submit, before the acknowledgement appears. This is the worst state: Suresh cannot know if the application went through.
11. Show a clear message.
12. Show a safe next step.
13. In this state, say if pressing Submit again can make a second application.
14. If you do not know, write the exact question to ask an engineer. Do not guess.
15. Draw reconnected.
16. Show how Suresh gets back to the same place.
17. Show how he checks the status.
18. Note that there is no application fee. The risk is a second copy of the application or a missing application. Say how the design helps him check.
19. Put all five drawings on page `W3` of your file `SPRINT-1 UX{n}`.

Worked example: a parcel app loses connection after "Place order". It shows "We are checking your order. Do not order again." and gives a status link. It names the doubt and gives a safe next step.

Common mistakes:
- A message says only "Connection error". Fix: say what happened and what to do next.
- The screen asks Suresh to start again. Fix: keep his work where you can.
- The screen says "Try again" but does not say if the first try worked. Fix: show a status check.
- You guess how the system works. Fix: write the question for an engineer.

If you get stuck:
- Re-read the parcel app example and name the doubt in it.
- Search the keyword "offline error state mobile".
- Ask in Discord with one state and the question you would ask an engineer.

How to think about it:
- Would Suresh know if his application was sent?
- Would he know it is safe to try again?
- What can he do next without calling the office?
- Does the screen work on a slow phone?

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/C5-3-offline-states.md`
- [ ] All five states are designed
- [ ] The profile check state says if typed details stay, and how
- [ ] The Submit state says how Suresh can learn if the application went through, or gives the exact question for an engineer
- [ ] The Submit state says if a second Submit can make a second copy of the same application, or gives the exact question for an engineer
- [ ] No state uses only a generic "connection error"
- [ ] Commit message: `C5.3 offline and interruption states`

#### Task - Fix what testing found (ID `C6.1`)

##### 1. What We Are Doing
You fix the worst problems from your R2.4 test. For each fix, you record the cost or the risk.

##### 2. Why We Are Doing It
A test is only useful if it changes the design. Real work also needs trade-offs. A fix can cause a new problem.

##### 3. What to Learn First
- How to describe a problem and its cost.
- The full severity scale from R2.4.

##### 4. Where to Find Resources
- `07-critique-guide.md`, for describing a problem and its cost.
- https://www.nngroup.com/articles/ten-usability-heuristics/ to name the problem.
- `08-glossary.md` for any word you do not know.

##### 5. Step-by-Step Guide
1. List every severity 3 and 4 finding from R2.4.
2. For each finding, write one line: who hit it, what happened, and why.
3. Redesign for each finding. Show before and after.
4. For each change, write three lines: which finding it fixes, what changed, and the cost or risk.
5. Record an actual cost or risk. If none is known, write "No known cost" and say what you checked.
6. If you do not fix a severity 3, say why. "I fixed it in another place" is a good reason. "The cost is too high for how often it happens" is also good. "I ran out of time" is honest and allowed.

Worked example: a test user cannot find the Apply Now button. You move it under the post title. Cost or risk: the title area is now more crowded.

Common mistakes:
- You fix many small things and skip the worst problem. Fix: start with severity 4.
- You say "it is simpler now" but do not say what changed. Fix: name the old problem and the new screen.
- You invent a cost that nobody can check. Fix: name a real cost or risk, or write "No known cost" and what you checked.
- You hide a problem with more text. Fix: change the screen, not only the words.

If you get stuck:
- Re-read your R2.4 row for the finding you are fixing and copy its words.
- Search the keyword "design fix trade-off".
- Ask in Discord with your before and after screens.

How to think about it:
- Does this fix help the main problem, or only hide it?
- Would a tired user on a slow phone still finish?
- What new problem does this fix create?
- Is the cost of the fix worth it for this problem?

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/C6-1-fixes.md`
- [ ] Every severity 3 and 4 finding is fixed, or deferred with a reason
- [ ] Each change names the finding by its row
- [ ] Each change records an actual cost or risk, or says "No known cost" and what you checked
- [ ] Before and after screens are shown
- [ ] No fix says only "make it simpler"
- [ ] Commit message: `C6.1 fixes from test findings`

#### Critique - 90 minutes

No new file. Bring C6.1.

1. Present your findings and your fixes.
2. Show one finding that changed your mind.
3. Say what you will fix first.
4. Ask for one clear next step.

#### Whiteboard why - 15 minutes, with the admin

1. Close your notes. Do not open any files.
2. Draw your flow from memory.
3. Answer three questions from the sprint question bank.
4. Accept the result. "Needs work" is a normal result, and you will try again next week.

### Group 4 - The surprise change (Day 5)

The admin gives you a new constraint (a rule you must follow) during this morning's learn block. You do not know it in advance. It is real. You cannot argue with it. It breaks part of what you built. Write the admin's message at the top of your X1 file. That note is your fifth learning summary for the week.

#### Task - Post mortem (ID `X1`)

##### 1. What We Are Doing
Write a short report on the change that arrived today. A post mortem is a report written after something goes wrong. It says what broke, what it cost, and what you will do next time.

##### 2. Why We Are Doing It
Requirements change in every real job. A designer who can name the cost of a change learns fast. Your reviewers will ask these questions too. A report that only says "the rule changed" helps nobody.

##### 3. What to Learn First
- The table "Constraint | Consequence for design" in the brief, so you know the rules you planned for.

##### 4. Where to Find Resources
- `01-project-brief.md` in this sprint folder, the constraint table.
- `07-critique-guide.md` in this sprint folder. Use its questions on your own work.

##### 5. Step-by-Step Guide
1. Write what changed, in one sentence. Use facts only. Do not blame a person.
2. Walk through every screen, decision and file. Write a list. Name each one.
3. Write the hours the fix will take. Write what you will now not finish.
4. Write one earlier decision that would have made this cheaper. Say why you made it then, and what it cost you now. Use the worked example below as the shape.
5. Write one clear change to how you will work. "Be more flexible" is not a change.

Worked example, the shape of point 4, for a different change: "If I had built the address entry as one component, with the field list driven by a configuration list, two new fields would have taken 10 minutes. I placed nine fields by hand on four screens instead. I did it by hand because it felt faster on Day 2. It cost me four hours on Day 5."

That is the answer your reviewers look for. Name the early decision. Say why you made it. Say the price it charged.

Common mistakes:
- Writing "the rule changed" and stopping. Fix: add what broke and what it cost.
- Point 4 says "I should have planned better". Fix: name the exact decision and the hours.
- No hours written down. Fix: add your estimate and write "my estimate" next to it.
- Blaming a person or a team. Fix: write facts and your own choices.

If you get stuck:
- Re-read the worked example and copy its four moves: decision, why, then, now.
- Search the keyword "post mortem blameless write-up".
- Ask in Discord with your point 4 line and ask if the decision is specific enough.

How to think about it:
- Which choice of mine was quick to make and slow to change?
- Would any designer pay this price, or is it only my mistake?
- What small change would have saved the most hours?

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/X1-post-mortem.md`
- [ ] The admin's message is copied at the top
- [ ] What changed, in one factual sentence
- [ ] Every broken screen, decision and file, named
- [ ] A real cost in hours and in work you dropped
- [ ] Point 4 names one early decision, not a general lesson
- [ ] Point 5 is one clear change to how you work
- [ ] Commit message: `X1 post mortem`

#### Task - Revised decisions (ID `P3.1`)

##### 1. What We Are Doing
Update your list of decisions. Mark the old ones that no longer hold. Add the new ones. Update the screens.

##### 2. Why We Are Doing It
Your list shows why each screen looks the way it does. If you delete the old rows, nobody can follow your reasons. A reviewer will ask "why is this here?". The list is your answer.

##### 3. What to Learn First
- Which rules cannot change, from the constraint table in the brief.
- The decisions you wrote in weeks 1 and 2.

##### 4. Where to Find Resources
- `01-project-brief.md`, the constraint table.
- Your own week 1 and week 2 task files.

##### 5. Step-by-Step Guide
1. Open your decision list from weeks 1 and 2. Add today's date at the top.
2. Find every decision the change has broken. Write "Superseded" next to each one. Do not delete it.
3. For each broken decision, write three lines: what it was, why it no longer holds, what replaces it.
4. Update every screen that used a broken decision.
5. Do step 4 at 390px.
6. Do step 4 at 1440px.
7. Update the Malayalam frames as well as the English frames.

Worked example, a made-up change, to show the shape: what it was, all fields on one long page. Why it no longer holds, the change adds a step before the check. What replaces it, the same fields split into two short steps. The old row is still there, the reason is one line, and the new row says what to build now.

Common mistakes:
- Deleting the old decision. Fix: mark it "Superseded" and leave it in place.
- Writing "changed the design" with no reason. Fix: say why the old decision no longer holds.
- Updating the 390px frames only. Fix: check 1440px too.
- Forgetting the Malayalam frames. Fix: update both languages in one pass.

If you get stuck:
- Search your own files for the word "decision" to find the old list.
- Search the keyword "design decision log superseded".
- Ask in Discord with one broken decision and your replacement line.

How to think about it:
- Could a new person read this list and follow your reasons?
- Is the old decision still easy to read after you mark it?

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/P3-1-revised-decisions.md`
- [ ] Every broken decision is listed
- [ ] Each one has a replacement and a reason
- [ ] The screens that use them are updated at 390px and 1440px
- [ ] Old decisions are marked superseded, not deleted
- [ ] Commit message: `P3.1 revised decisions`

### Group 5 - System update (Day 6)

#### Task - Add the states to the components (ID `S3.1`)

##### 1. What We Are Doing
Add the missing states to your component. A component is one reusable part of a screen, such as a button. The states are loading, disabled, error and focus. Disabled means the control cannot be used now. Focus is the ring that shows where the keyboard is.

##### 2. Why We Are Doing It
Users need to know what the screen is doing. A missing state makes them tap again or give up. Your component must work for the new apply flow.

##### 3. What to Learn First
- The state list from C5.1 and C5.2.
- How variants work in Figma, if you have not used them.

##### 4. Where to Find Resources
- Figma Learn https://help.figma.com/ The pages on components and variants. Read the part on states.
- Setup guide: `../04-Tools-Setup.md`, section on Figma.
- File hygiene: your work stays on page `W3` of `SPRINT-1 UX{n}`. One file per sprint, not three.

##### 5. Step-by-Step Guide
1. Open your component page.
2. List the states it has now.
3. Add loading.
4. Show a short text or a spinner.
5. Say what is loading.
6. Add disabled.
7. Show why the control is disabled.
8. Add error.
9. Put the message next to the field.
10. Say how to fix it.
11. Add focus if it is missing.
12. Use a clear ring or outline.
13. Add a short text label to each state.
14. Test each state at 390px and 1440px.
15. Test each state with long Malayalam text.
16. Update the markdown file `system/components/{component}.md` with the new state list.

Worked example: a library app search box can show "Searching..." when loading. It can be disabled with the text "Type a book name first". It can show "No book found" as an error. Each state says what is happening or what to do.

Common mistakes:
- Only adding colour and no text. Fix: add a word too.
- Hiding the error until after Submit. Fix: show it near the field.
- Using English only. Fix: test Malayalam and English.
- Forgetting the focus ring. Fix: add it back.

If you get stuck:
- Search Figma Learn for the variants page and follow its shortest example.
- Search the keyword "button states loading disabled error focus".
- Ask in Discord with a screenshot of your variant set.

##### 6. What to Commit
- [ ] Update `system/components/{component}.md`
- [ ] Your component has loading, disabled, error and focus
- [ ] Each state has a short text label
- [ ] Each state works at 390px and 1440px
- [ ] Each state works with Malayalam text
- [ ] You updated the component file
- [ ] Commit message: `S3.1 component states loading disabled error focus`

#### Task - Write the component contribution rule (ID `S3.2`)

##### 1. What We Are Doing
Write the rule for adding a component to the shared system. The shared system is the set of components the cohort uses. The rule must be short and clear.

##### 2. Why We Are Doing It
A shared system grows fast. Without a rule, parts look and behave in different ways. The group then cannot reuse them.

##### 3. What to Learn First
- The component list from week 2.
- What a shared library is, if your team has one.

##### 4. Where to Find Resources
- Figma Learn https://help.figma.com/ The pages on shared libraries and components.
- Your `system/` folder.

##### 5. Step-by-Step Guide
1. List what every component must include: name, owner, states, mobile width, a Malayalam test and a change note.
2. Write one short line for each item.
3. Say who checks the work before merge.
4. Say what happens if a rule is missing.
5. Ask one teammate to try to reject a bad example with your rule.
6. Save the file.

Worked example, a rule for a date picker: "Show a label, a hint and an error text. Test at 390px. Test with long Malayalam text. Name one owner." Each line can be checked.

Common mistakes:
- Writing "must look good". Fix: no one can check that.
- Forgetting the owner. Fix: name one person.
- Asking for every state but not the text. Fix: ask for both.
- Making the rule long. Fix: keep it to one page.

If you get stuck:
- Re-read the worked example and count how many lines can be checked by a stranger.
- Ask in Discord and ask a teammate to reject your bad example.

##### 6. What to Commit
- [ ] File at `system/docs/contribution-rules.md`
- [ ] The rule has six or more checks
- [ ] Each check is one short line
- [ ] The rule names an owner and a checker
- [ ] A teammate used it to reject one weak example
- [ ] You saved the file
- [ ] Commit message: `S3.2 component contribution rule`

#### Task - Handle the injection at system level (ID `S3.3`)

##### 1. What We Are Doing
Decide as a group if the Day 5 client change touched the shared system. If it did, write one decision record. A decision record is a short note. It says what changes and why.

##### 2. Why We Are Doing It
A shared system needs one clear answer. If everyone fixes it in their own way, the parts stop matching.

##### 3. What to Learn First
- The Day 5 notes.
- The list of shared components.

##### 4. Where to Find Resources
- Your own `system/docs/contribution-rules.md`.
- `07-critique-guide.md` in this sprint folder.

##### 5. Step-by-Step Guide
1. Read the Day 5 notes. List the shared parts that may be affected.
2. Mark each part: no change, small change, or big change.
3. Choose the smallest shared fix.
4. Write the decision: what changes, why, who owns it, and when it is done.
5. Add one test that every flow must pass after the fix.
6. Save the file under `system/docs/decisions/`.

Worked example: a shared date field needs a new format. The group writes one decision. It lists the three forms that use the field. It says who updates them and how to test the new format.

Common mistakes:
- Fixing one screen and leaving the others. Fix: the system then has two rules.
- Writing a decision with no owner. Fix: name one person.
- Forgetting the test. Fix: add one test every flow must pass.
- Changing the client rule. Fix: you can change the design, not the rule.

If you get stuck:
- Re-read the worked example and check if your decision names all the users of the part.
- Ask in Discord and tag the group so you agree on one fix.

##### 6. What to Commit
- [ ] File at `system/docs/decisions/{nn}-{topic}.md`
- [ ] The group listed the affected shared parts
- [ ] The group chose one fix
- [ ] The decision names an owner and a date
- [ ] The decision names one test for every flow
- [ ] You saved the file
- [ ] Commit message: `S3.3 system decision for the Day 5 change`

### Group 6 - Fundamentals (Day 6)

#### Task - Why session: cognitive load and progressive disclosure (ID `F3.1`)

##### 1. What We Are Doing
Give a short talk on cognitive load and progressive disclosure. Cognitive load is the mental effort to read and choose. Progressive disclosure means show the most important thing first, and show the rest only when it is needed.

##### 2. Why We Are Doing It
Too much on one screen makes people stop. A simple order helps them finish. The talk shows the group how to do this.

##### 3. What to Learn First
- The two terms in plain words.

##### 4. Where to Find Resources
- Laws of UX https://lawsofux.com/ Read Hick's Law and Miller's Law.
- One screen from the cohort work with too much on it.

##### 5. Step-by-Step Guide
1. Show the busy screen. Name the problem in one line.
2. Explain cognitive load in one plain line.
3. Remove one thing.
4. Move one thing to a later step.
5. Show the new screen.
6. Say what you changed and why.
7. Ask one question: "What still feels heavy?"
8. Save your notes in the file below.

Worked example: a hotel booking page can ask for dates first. Room type comes next. Breakfast choice comes last. The user sees only what they need now.

Common mistakes:
- Hiding important facts. Fix: that is not progressive disclosure.
- Removing all detail. Fix: the user then cannot decide.
- Using hard words in the talk. Fix: explain each term in one line.
- Showing no before screen. Fix: then no one sees the gain.

If you get stuck:
- Re-read Hick's Law and Miller's Law and pick one line each.
- Ask in Discord and ask someone to time your 10 minutes.

##### 6. What to Commit
- [ ] File at `fundamentals/why-sessions/week03-cognitive-load.md`
- [ ] The talk is 10 minutes or less
- [ ] You show one before screen and one after screen
- [ ] You explain both terms in plain words
- [ ] You name one change and why it helps
- [ ] You saved the notes
- [ ] Commit message: `F3.1 why session cognitive load`

#### Task - Teardown: a hospital appointment booking flow (ID `F3.2`)

##### 1. What We Are Doing
Study a hospital appointment booking flow. List what works and what fails. A teardown is a close study of a real flow.

##### 2. Why We Are Doing It
It trains your eye for problems. You can use the same eye on your own flow.

##### 3. What to Learn First
- The 10 usability heuristics. A heuristic is a simple rule for good design.

##### 4. Where to Find Resources
- https://www.nngroup.com/articles/ten-usability-heuristics/ Use the 10 rules as a checklist.
- A public hospital booking page from your admin. Do not make a real booking.

##### 5. Step-by-Step Guide
1. Open the booking page.
2. Write the steps from start to end.
3. Check each step with the 10 heuristics.
4. Write 6 or more findings. Each finding names one heuristic.
5. Add one short fix for each finding.
6. Save the notes.

Worked example: a cinema ticket page hides the fee until the last step. The fix is to show the fee before the seat choice. The finding names the heuristic: visibility of system status.

Common mistakes:
- Writing "it looks bad". Fix: name the rule and the effect.
- Using private data. Fix: do not enter a real name or phone.
- Listing problems with no fix. Fix: add one short fix each.
- Copying the whole page. Fix: write only the findings.

If you get stuck:
- Re-read the 10 heuristic names and pick the closest one for each finding.
- Search the keyword "heuristic evaluation findings example".

##### 6. What to Commit
- [ ] File at `fundamentals/teardowns/03-hospital-booking.md`
- [ ] You wrote the steps from start to end
- [ ] You wrote 6 or more findings
- [ ] Each finding names one heuristic
- [ ] Each finding has one short fix
- [ ] You saved the notes
- [ ] Commit message: `F3.2 teardown hospital booking flow`

#### Task - Drill continues (ID `F3.3`)

##### 1. What We Are Doing
Keep doing the practice drill from Day 1 to Day 5. A drill is a short repeated practice. You do it in 15 minutes a day, in one file. Today you add two new screens from this week.

##### 2. Why We Are Doing It
Short practice each day makes the work faster. The drill keeps your basic skills sharp.

##### 3. What to Learn First
- The drill steps below. Read them before Day 1, so the schedule works.
- The drill file path: `students/UX{n}/week3/F3-drill.md`. You write in this one file all week.

##### 4. Where to Find Resources
- Your own week 2 screens in Figma, file `SPRINT-1 UX{n}`, page `W2`.
- Figma Learn https://help.figma.com/ Use a short practice lesson for the same skill.

The drill schedule, Day 1 to Day 5:

| Day | What you draw | Time |
|---|---|---|
| Day 1 | Redraw one row of your notification list in a blank frame. Do not copy from week 2. | 15 min |
| Day 2 | Redraw the same row again, from a blank frame. | 15 min |
| Day 3 | Redraw the photograph upload row, from a blank frame. | 15 min |
| Day 4 | Redraw the photograph upload row again, from a blank frame. | 15 min |
| Day 5 | Redraw the notification row again, as fast as you can. | 15 min |

Write one line in `students/UX{n}/week3/F3-drill.md` after each day: what you drew, how long it took, one thing that was faster.

##### 5. Step-by-Step Guide
1. Open `students/UX{n}/week3/F3-drill.md` on Day 1.
2. Write the date and the day number.
3. Set the timer for 15 minutes.
4. Do the drill for that day from the table.
5. Stop when the timer rings, even if it is not finished.
6. Write one line: what you drew, how long it took, one thing that was faster.
7. Repeat steps 2 to 6 on Days 2, 3 and 4.
8. On Day 5, set the timer for 15 minutes.
9. Do the Day 5 drill.
10. Add two new screens from this week to the drill file. Name each screen.
11. Check the result at 390px.
12. Check the result at 1440px.
13. Write one line on what was faster across the week.

Worked example: a person learns to type. They practise the same short sentence each day. On day six they add two new words. The base drill stays the same.

Common mistakes:
- Changing the drill every day. Fix: keep the base the same.
- Skipping the timer. Fix: then the drill takes too long.
- Adding too many screens. Fix: add only two.
- Not writing what changed. Fix: then you cannot see progress.

If you get stuck:
- Re-read your earlier drill lines in `students/UX{n}/week3/F3-drill.md` and repeat the same steps.
- Ask in Discord and share the two screens you added.

##### 6. What to Commit
- [ ] Your drill file at `students/UX{n}/week3/F3-drill.md`, updated
- [ ] One line for each day, Day 1 to Day 5
- [ ] You did the drill for 15 minutes each day
- [ ] You added two new screens
- [ ] You checked both widths
- [ ] You wrote one line on what was faster
- [ ] Commit message: `F3.3 drill day 6`

### Group 7 - Lab L-PR1

#### Task - Responsive behaviour and platform conventions (ID `L-PR1`)

##### 1. What We Are Doing
You check your screens on 390px and 1440px and against platform conventions (the habits people already have on their phone).

##### 2. Why We Are Doing It
People in India use your design on many screen sizes. A screen that breaks at 390px is a real failure.

##### 3. What to Learn First
- The full method and done-when checklist in `08-Prototyping-And-Responsive.md` (repository root), section L-PR1.

##### 4. Where to Find Resources
- `08-Prototyping-And-Responsive.md` (repository root), section L-PR1.

##### 5. Step-by-Step Guide
1. Open `08-Prototyping-And-Responsive.md` and read the L-PR1 section fully.
2. Follow its steps in order. Do not skip a step.
3. Tick its done-when checklist.
4. Save your notes in the file below.

If you get stuck:
- Re-read the L-PR1 section and write which step you are on.
- Ask in Discord with a screenshot at 390px and at 1440px.

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/L-PR1-responsive.md`
- [ ] All points in the L-PR1 done-when checklist are ticked
- [ ] Commit message: `L-PR1 responsive behaviour check`

### Group 8 - Code corner

#### Task - CSS box model and flexbox (ID `Z3.1`)

##### 1. What We Are Doing
You rebuild one component from your Figma auto layout in plain HTML and CSS. You use the box model (margin, border, padding, content) and flexbox (a one-line layout rule for a row or a column).

##### 2. Why We Are Doing It
Auto Layout and flexbox solve the same problem. When you build one component by hand, you see why the spacing values in Figma matter, and you can talk to engineers about them.

##### 3. What to Learn First
- The box model: content, padding, border, margin.
- Flexbox basics: `display: flex`, `gap`, `justify-content`, `align-items`.

##### 4. Where to Find Resources
- https://web.dev/learn/css
- https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics
- Tool: VS Code. Setup guide: `../04-Tools-Setup.md`, section on VS Code.
- Your own Figma file `SPRINT-1 UX{n}`, page `W3`.

##### 5. Step-by-Step Guide
1. Read the box model page on https://web.dev/learn/css. Take 5 minutes.
2. Read the layout part of the MDN Styling basics page. Take 5 minutes.
3. Open your Figma component.
4. Write down its padding, gap, font size and colours.
5. In VS Code, make a new file named `z3-1-flex-component.html` in your week3 folder.
6. Write the HTML for the same component: one label, one short text, one button.
7. Add a `<style>` block.
8. Set `display: flex` and a `gap` on the container.
9. Add the padding from your Figma values.
10. Add the border radius from your Figma values.
11. Save the file.
12. Open it in your browser. Mac: right-click the file in Finder and choose Open With, then your browser. Or run `open z3-1-flex-component.html` in Terminal. Windows: right-click the file and choose Open with, then your browser. Or run `start z3-1-flex-component.html` in PowerShell.
13. Compare it with the Figma component side by side.
14. Change one value in the CSS.
15. Save the file.
16. Refresh the browser.
17. Watch what moves.
18. Take a screenshot with both the browser and the Figma component visible.
19. Save the screenshot as `z3-1-flex-component.png`, under 2 MB, lowercase with hyphens.

If you get stuck:
- Re-read the box model page on web.dev/learn/css and name which layer is wrong.
- Search the keyword "CSS box model flexbox".
- Ask in Discord with your .html file pasted and the screenshot.

##### 6. What to Commit
- [ ] File at `students/UX{n}/week3/z3-1-flex-component.html`
- [ ] Screenshot at `students/UX{n}/week3/z3-1-flex-component.png`, under 2 MB
- [ ] The component uses `display: flex` and a `gap`
- [ ] The padding and colours match your Figma component
- [ ] The screenshot shows the browser and the Figma component together
- [ ] Commit message: `Z3.1 box model and flexbox component`

## 6. What to Commit

- [ ] 5 learning summaries: Day 1 to Day 4 files, plus the Day 5 constraint written at the top of `X1-post-mortem.md`
- [ ] C5.1, C5.2, C5.3
- [ ] R2.1, R2.2, R2.3, R2.4
- [ ] C6.1
- [ ] X1 post mortem, P3.1 revised decisions
- [ ] Whiteboard why attempted
- [ ] Critique attended
- [ ] S3.1, S3.2, S3.3
- [ ] F3.1, F3.2, F3.3, and your drill file at `students/UX{n}/week3/F3-drill.md`
- [ ] L-PR1 done (2 hours)
- [ ] Z3.1 code corner (.html plus .png)
- [ ] Allowed file types only: markdown, PNG or JPG under 2 MB, PDF under 10 MB, small .html, .css and .js files (a code folder such as `students/UX{n}/week3/` is allowed), and a view-only Figma or Penpot link inside a markdown file. No .fig files, no recordings, no passwords, no real personal data.

If you are short on time, cut in this order: F3.3, then F3.1, then the second loading state in C5.2, then S3.3. **Do not cut R2.2, R2.3, or R2.4.** Three real users is the entire evidence base for your defense next week. Without it you have opinions.

When your week3 folder is ready, push your branch and open one pull request for the week. The steps are in `../10-GitHub-For-Designers.md`.

Next: `05-week4.md`
