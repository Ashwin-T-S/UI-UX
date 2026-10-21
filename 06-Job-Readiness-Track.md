# 06 - Job Readiness Track

The portfolio is built during the program, not after it.

Sprint 6 is the sprint where you finish the portfolio and apply. If it is the first time you write a case study, four weeks is not enough to do it well. So the work starts in Sprint 1 and every sprint ends with something a stranger can look at.

This track runs across 27 weeks, from week 0 to week 24. Week 12b and week 20b add portfolio material. Codes are UX1 to UX10. Replace `{n}` with your code.

## 1. The rules of the track

1. **Every sprint ends with a case-study draft.** One page is enough. It is rewritten later. The point is that it exists.
2. **A public portfolio is live by week 12.** It can be small. It must be a real URL that opens on a phone.
3. **Every sprint has a review by someone outside the cohort.** Someone who does not know the cohort and has no reason to be kind looks at your work and talks to you.
4. **Complete the three mock interviews in JR3, JR4 and JR5.** Use a different format each time, so all interview formats are rehearsed by week 24.
5. **The first screen explains your value.** It has to say who you are, what you design, and why they should keep reading.
6. **Nothing here is a placement guarantee.** The program can make you ready. It cannot create openings. See section 8.
7. **One Figma file per sprint.** Name it `SPRINT-N UX{n}` and use one page per week. Do not create Practice, System and Delivery files. The Figma free Starter plan has a 3-file limit. Keep one spare file only. If the limit blocks you, use Penpot free as the backup (https://penpot.app/). Check the free limit before use. The Figma Education plan may lift limits if the admin confirms you are eligible. Do not assume it. See https://www.figma.com/education/. For Mac and Windows setup, see `04-Tools-Setup.md`.
8. **Code corners are part of the track.** Each is 20 to 40 minutes. You do not need to become a programmer. You need to read and edit code, run an AI coding assistant, and publish a small page. The code corners are: week 0 (install VS Code and Git, make your first page), week 3 (CSS box model and Flexbox, linked to Auto Layout), week 6 (HTML forms for the research form), week 10 (a little JavaScript: a click that changes state), week 12b (AI-assisted coded prototype, published on GitHub Pages), week 15 (CSS variables as tokens), week 22 (portfolio page on GitHub Pages). Sources: https://web.dev/learn/html, https://web.dev/learn/css, https://web.dev/learn/javascript, and https://developer.mozilla.org/en-US/docs/Learn_web_development.
9. **Use free tools only.** Check the free limit before use. For repo work, see `10-GitHub-For-Designers.md`. The repo also has new docs 11 and 12. Check their exact file names in the repo before you link to them.
10. **No real personal data.** No real names, faces, phone numbers, IDs or private details anywhere. Use P1 and P2. Never commit .fig files, passwords, tokens or real personal data.

## 2. The five tasks

Task IDs start with `JR`. Each is built in the week's Day 6 (cohort day). The writing and the reviews are committed to `Design-Sprint-N/students/UX{n}/weekX/portfolio/`. For example, `Design-Sprint-1/students/UX1/week4/portfolio/`. Replace `UX1` with your code and `weekX` with the week number. The portfolio site itself lives in your own repository, linked from your `portfolio/README.md` inside that folder. The hours are in addition to the normal week. They are the reason lab weeks run longer; see `01-How-The-Program-Works.md` section 13.

| ID | Week | Time | You produce | External input |
|---|---|---|---|---|
| **JR1** | 4 | 2 h | Positioning, platform decision, portfolio repo and asset checklist | None |
| **JR2** | 8 | 3 h | Case study 1 (Sprint 1) as a one-page draft, and a basic published site | 20-minute async review (not live) by a working designer |
| **JR3** | 12 | 3 h | Live portfolio with two case studies and an About page | 30-minute live portfolio review, plus **Mock interview 1: portfolio walk** |
| **JR4** | 16 | 3 h | Case study 3 (the design system), LinkedIn skeleton | **Mock interview 2: craft and critique** |
| **JR5** | 20 | 3 h | Capstone case study draft, target list of 20 companies | **Mock interview 3: behavioural and whiteboard** |

All commits follow `10-GitHub-For-Designers.md`: fork, clone, branch, commit, pull request. Allowed files: markdown, PNG/JPG under 2 MB, PDF under 10 MB, and a view-only Figma link inside a markdown file. You may also commit small `.html`, `.css` and `.js` files and code folders (for example `week12b/page/`). Image names must be lowercase, use hyphens and no spaces (for example `r1-1-home-page.png`). A view-only Penpot link inside a markdown file is also allowed. Use one task, one commit containing all files listed for that task. Branch names include the task or week: `ux1-week4-jr1`. For publishing, use GitHub Pages: https://docs.github.com/en/pages/quickstart.

Sprint 6 then turns these drafts into two or three deep case studies, not a long list. Three strong is the target. Two strong beats three weak. It also finishes the polished site, the resume, LinkedIn, Behance or Dribbble or your own site on GitHub Pages, ten applications and the final loop. See `Design-Sprint-6/00-READ-FIRST.md`.

### JR1 - Position yourself (week 4)

**Learn first:** your own Sprint 1 work, and three portfolios of designers at the level you want.

**Method**
1. Write three sentences: *I design [what] for [whom]. The evidence is [one specific thing from the program]. I am looking for [kind of role].* No adjectives like "passionate" or "creative".
2. Write a one-page decision record for the platform: hand-coded on GitHub Pages, Notion free, Framer, Webflow or similar.
3. For each platform, use free tiers only. Check the free limit before use.
4. Score each platform on: accessibility of the output, load speed on a mid-range Android phone, ownership of your content, and the hours it will cost you.
5. Pick one platform.
6. Create `Design-Sprint-1/students/UX{n}/week4/portfolio/` with `positioning.md`, `platform-decision.md` and `assets-checklist.md`.
7. The assets checklist lists, per project, what you must export as you go: final PNGs at 2x, a 20-second prototype recording, the problem statement, one number, one mistake. Export from your one Figma file per sprint, `SPRINT-N UX{n}`. If Figma limits block you, use Penpot. Build the habit now so week 21 is not a search through old files.

**Done when**
- [ ] Positioning is three sentences and contains one specific piece of evidence
- [ ] The platform decision has scores and a reason, not a preference
- [ ] The assets checklist exists for Sprint 1

**If you get stuck:**
- Read the three portfolios again. Write down one sentence about what each designer does.
- Search for "UX portfolio positioning statement examples" and check the free limit before use.
- Ask in Discord with a screenshot of your three sentences and what you tried.

**Commit:**
Create one commit with all listed files. Use the message `JR1: add positioning, platform decision and asset checklist`.
Files:
- `Design-Sprint-1/students/UX{n}/week4/portfolio/positioning.md`
- `Design-Sprint-1/students/UX{n}/week4/portfolio/platform-decision.md`
- `Design-Sprint-1/students/UX{n}/week4/portfolio/assets-checklist.md`

### JR2 - Case study 1 and a basic published site (week 8)

**Learn first:** `Design-Sprint-6/06-case-study-structure.md`, the whole file. You are using the structure early on purpose. Also read the beginner publishing lesson in `04-Tools-Setup.md`. It covers: creating an account on your chosen platform, the steps to publish, and how to check the page on a phone. If the section is missing, search the web for "publish a site on [platform name]" and check the free limit before use.

**Method**
1. Write the Sprint 1 (Kerala PSC) case study as one page using the nine-part structure. Part 9, *what you got wrong and what you would do differently*, is mandatory. Cut every sentence that does not serve the argument.
2. Complete the beginner publishing lesson in `04-Tools-Setup.md`. Set up an account on your chosen platform. Follow the publishing steps. Open the URL on a phone to check it works.
3. Publish a basic published site at a real URL with a home page, this case study, and a contact link. Put the URL in your README. Use GitHub Pages if you choose the code route. See https://docs.github.com/en/pages/quickstart.
4. Send it for the async review. The reviewer answers three questions in 20 minutes: *What do you think this person does? Would you keep reading? What is the first thing you would cut?*
5. Commit the reviewer's answers verbatim.
6. Write your response in two lines.

**Done when**
- [ ] One-page case study with all nine parts
- [ ] A URL that opens on a phone
- [ ] The three reviewer answers, uncut
- [ ] One change you made because of them

**If you get stuck:**
- Read the nine-part structure again. Check that each part has at least one sentence.
- Search for "one-page UX case study example" and check the free limit before use.
- Ask in Discord with a screenshot of your case study outline and what you tried.

**Commit:**
Create one commit with all listed files. Use the message `JR2: add case study 1, basic site URL and review answers`.
Files:
- `Design-Sprint-2/students/UX{n}/week8/portfolio/JR2-case-study-1.md`
- Any updated `README.md` in that folder with the URL.

### JR3 - Live portfolio and Mock interview 1 (week 12)

**Learn first:** your JR2 review answers.

**Method**
1. Add the Sprint 3 flow (the consumer subscription showpiece, task C12.3) to your portfolio.
2. Add an About page. Two case studies is enough; three weak ones are worse.
3. Run the portfolio against `Design-Sprint-6/03-week22.md` task B2.6 (accessibility and performance). Fix what fails now rather than in week 22.
4. **Live review, 30 minutes with an external designer.** Share your screen on a phone-sized window. They think aloud while they read.
5. **Mock interview 1, portfolio walk, 20 minutes.** Walk one case study in five minutes, then take questions. Record it.
6. Write down the three questions you answered worst.

**Done when**
- [ ] Portfolio is live, two case studies, About page, passes keyboard-only navigation
- [ ] Review notes committed
- [ ] Recording exists, and the three worst questions are written down

**If you get stuck:**
- Re-read `Design-Sprint-6/03-week22.md` task B2.6. Check each accessibility point one by one.
- Search for "keyboard only navigation test checklist" and check the free limit before use.
- Ask in Discord with a screenshot of the failing check and what you tried.

**Commit:**
Create one commit with all listed files. Use the message `JR3: add live portfolio, review notes and worst questions`.
Files:
- `Design-Sprint-3/students/UX{n}/week12/portfolio/JR3-live-portfolio.md`
- Any review notes as markdown in the same folder.
Do not commit the recording.

### JR4 - Case study 3 and Mock interview 2 (week 16)

**Learn first:** your Sprint 4 design system files, and the mock interview scorecard in section 5 of this document.

**Method**
1. Write the design-system case study. This is the hardest to write because the output is invisible. The argument is not "I made components". It is "I made decisions about who may change what, and here is the one that went wrong".
2. Draft the LinkedIn headline from your positioning.
3. Draft the LinkedIn about section from your positioning.
4. **Mock interview 2, craft and critique, 45 minutes, external.** You are shown an unseen screen and asked to critique it. Then you are asked to redesign one part live. Record it.
5. Commit the interviewer's scorecard.
6. Write anonymised notes from the interview. Do not include real names or faces. Do not commit the recording.

**Done when**
- [ ] Case study 3 reads to someone who has not seen the system
- [ ] LinkedIn draft committed
- [ ] Scorecard and anonymised written notes committed; do not commit recordings

**If you get stuck:**
- Re-read your design system tokens and component rules. Write down one decision you made about who can change a token.
- Search for "design system case study example" and check the free limit before use.
- Ask in Discord with a screenshot of your case study outline and what you tried.

**Commit:**
Create one commit with all listed files. Use the message `JR4: add design system case study, LinkedIn draft and scorecard`.
Files:
- `Design-Sprint-4/students/UX{n}/week16/portfolio/JR4-case-study-3.md`
- `Design-Sprint-4/students/UX{n}/week16/portfolio/linkedin-draft.md`
- `Design-Sprint-4/students/UX{n}/week16/portfolio/scorecard.md`
- `Design-Sprint-4/students/UX{n}/week16/portfolio/interview-notes.md` (anonymised)

### JR5 - Capstone draft and Mock interview 3 (week 20)

**Learn first:** your capstone decision log from Sprint 5, and the scorecard in section 5.

**Method**
1. Write the capstone case study from the decision log. It must include the review of the failure introduced during the capstone and one result you cannot prove.
2. Build a target list of 20 companies and teams. Columns: company, role, why you, what you can show them, who you know. You will send applications to ten of them in Sprint 6.
3. **Mock interview 3, behavioural and whiteboard, 60 minutes, external.** Two behavioural questions, one 30-minute design whiteboard, one question about salary expectations.
4. Record the mock interview using Loom free or a similar tool you already use. Check the free limit before use. Do not show real names, faces or private details. Keep the recording outside the repo; do not commit it.
5. Commit the scorecard.
6. Write anonymised notes from the interview. Do not include real names or faces. Do not commit the recording.

**Done when**
- [ ] Capstone case study draft with the review of the failure introduced during the capstone in it
- [ ] Target list of 20
- [ ] Scorecard and anonymised written notes committed; do not commit recordings

**If you get stuck:**
- Re-read your capstone decision log. Find one failure you can describe without blaming anyone.
- Search for "capstone case study template" and check the free limit before use.
- Ask in Discord with a screenshot of your target list and what you tried.

**Commit:**
Create one commit with all listed files. Use the message `JR5: add capstone draft, target list and scorecard`.
Files:
- `Design-Sprint-5/students/UX{n}/week20/portfolio/JR5-capstone-draft.md`
- `Design-Sprint-5/students/UX{n}/week20/portfolio/target-list.md`
- `Design-Sprint-5/students/UX{n}/week20/portfolio/scorecard.md`
- `Design-Sprint-5/students/UX{n}/week20/portfolio/interview-notes.md` (anonymised)

## 3. Portfolio additions from the labs

The job track also uses two labs. They are not extra JR tasks. They feed the portfolio.

### Week 12b - L-AI6: AI-assisted coded prototype

The lab has seven tasks. Follow each one in order. See the full instructions, deliverables and commit details in the week 12b file: `Design-Sprint-3/12b/00-READ-FIRST.md` (check the exact file name in the repo).

- **Y1.1** Pick one screen from your showpiece.
- **Y1.2** Write the prompt and spec.
- **Y1.3** Generate with an AI coding assistant on a free tier. Check the free limit before use.
- **Y1.4** Read and fix the code in VS Code.
- **Y1.5** Check it with axe DevTools and keyboard.
- **Y1.6** Publish on GitHub Pages.
- **Y1.7** Add a short note: what you asked, what the AI got wrong, what you fixed, and your AI log and AI footer. The AI log and AI footer rules are in `07-AI-In-Design.md`. Link the published page from your portfolio. This shows a coded prototype and AI fluency.

### Week 20b - L-AI7: Agent UX lab

The lab has seven tasks. See the full instructions in the week 20b file: `Design-Sprint-5/20b/00-READ-FIRST.md` (check the exact file name in the repo).

- **A5.1** List agent actions in your capstone.
- **A5.2** Set autonomy level and scope limit.
- **A5.3** Add intent preview and confirmation gate.
- **A5.4** Add reasoning, confidence and failure states.
- **A5.5** Add undo and audit trail.
- **A5.6** Add escalation to a human.
- **A5.7** Prototype the agent flow and test it with one person.

Add a short section to your capstone case study covering these points. Use the Agent UX patterns from the lab. Check the source before use.

Design work for these labs goes in the same `SPRINT-N UX{n}` Figma file, one page per week. Use Penpot if the Figma free limit blocks you.

## 4. What job readiness looks like in 2026

Hiring signals change. The points below are a small sample of hiring signals in 2026. Do not overstate them. Use them to prepare, not to predict the market.

**Portfolio: two or three deep case studies.**
Each case study shows:
- the outcome, in a number or a clear change
- your process, and the decisions you rejected
- craft, with screens and states
- accessibility, with what you tested and what failed
- prototyping, with a link or a recording
- AI fluency, with a note and a log
- systems thinking, with components, tokens or rules
- working with engineers, with handoff notes and trade-offs

**Interviews you will meet:**
- portfolio walkthrough
- design challenge
- whiteboard
- critique
- behavioural

Use the mock interviews JR3, JR4 and JR5 to practise these formats. Record them. Write down the questions you answer worst.

**India roles to target:**
- UX designer
- product designer
- UX researcher
- design systems designer
- UI engineer / design engineer

**Application kit:**
- resume: one page, plain, with links to your portfolio
- LinkedIn: headline and about section from your positioning
- Behance, Dribbble or your own site on GitHub Pages: one clear link, current work
- a target list of 20 companies, and 10 applications in Sprint 6

## 5. Mock interview scorecard

The same four-point scale every time, used by the external interviewer. Full admin rubric is in the private admin material.

| Dimension | 1 | 2 | 3 | 4 |
|---|---|---|---|---|
| **Clarity** | Could not say what they did | Said it, but I had to dig | Clear in the first minute | Clear in ten seconds and the structure helped |
| **Reasoning** | Decisions with no reasons | Reasons, no alternatives | Reasons and rejected alternatives | Reasons, alternatives and what would change their mind |
| **Evidence** | Opinion | Some evidence, not defended | Evidence defended | Evidence defended, with its limits stated unprompted |
| **Honesty** | Everything went well | Mistakes mentioned | A mistake they learned from | A mistake that cost something, clearly accepts responsibility |
| **Presence** | Read from notes, froze, or defended | Uneven | Calm, engaged | Calm, curious, easy to talk to |

Each mock interview also records the question the designer answered worst. That list becomes the Sprint 6 practice list.

## 6. Who the external people are

The admin recruits them before Sprint 1 ends and keeps a list of at least five.

| Requirement | Why |
|---|---|
| Working product designer, design manager, or someone who hires designers | They know what a real shortlist (the short list for interview) looks like |
| Has not seen the cohort's work | No reason to be kind |
| Does not know the designers and has no reason to be kind | No kindness |
| Available for about three hours per sprint | One critique, one review, one portfolio or mock session |

Rotate them. If a designer sits in front of the same external person twice in a row, the second session is worth much less.

## 7. The placement-readiness check (week 24)

The final loop in `Design-Sprint-6/05-week24.md` is scored by externals who have not seen the designer before. Each designer receives one of three honest outcomes:

| Outcome | Meaning | What happens next |
|---|---|---|
| **Ready** | Would put this person through to an interview round | Apply now. 90-day plan stays. |
| **Ready, with a named gap** | Would interview them, but one thing will cost them offers | The gap is named in writing. The 90-day plan is built around closing it. |
| **Not yet** | Portfolio or interview performance will not survive a real shortlist | Honest conversation, and a specific list: what to do, and in what order. |

"Not yet" is a result, not a failure. The program should say it plainly rather than let someone discover it after fifty rejections.

## 8. What the program can and cannot say

**It can say:** graduates leave with two or three portfolio-grade case studies, a live portfolio, three recorded mock interviews, a set of rehearsed answers, and an external assessment of where they stand.

**It cannot say:** graduates get jobs. Entry-level product design is a competitive market. Outcomes depend on the market, on location, on prior experience, and on how many applications a designer is willing to send and learn from.

**What the program does promise:** it will track outcomes and publish them. The admin contacts every graduate at 30, 90 and 180 days after week 24 and records: applications sent, interviews, offers, and what they would change. Those numbers go in the next cohort's welcome pack, whatever they are.

## 9. Optional: a live project

A designer who can secure a real client may substitute it for one of the Sprint 5 options, with the admin's written approval before week 17. Four conditions, all required:

1. A named contact who has agreed in writing
2. Five real users reachable in weeks 17 and 19
3. Something that can go live, even partially, inside four weeks
4. A number that exists before you start

A live project that cannot meet all four is a distraction. Choose a Sprint 5 option instead.

Next: `07-AI-In-Design.md`.
