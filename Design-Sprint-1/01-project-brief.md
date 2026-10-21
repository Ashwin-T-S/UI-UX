# Sprint 1 Project Brief: Kerala PSC, Apply for a Post

**Weeks 1 to 4 | Track focus: Craft and Interface | Cohort: UX1 to UX10**

---

**Read this first.** The client in this brief is fictional. The service you will study is the real public website of the Kerala Public Service Commission (Kerala PSC). The Commission has not asked for this work. This course is not endorsed by the Commission and does not speak for it. You study a public service. You do not change it.

## 1. The client story

A small digital services team works inside a state recruitment body. The team has money to redesign one service. They chose the "apply for a post" journey.

Why this journey? Many candidates apply for government posts every year. Some applications go wrong. Some candidates miss a step and lose a whole exam cycle. The team wants fewer mistakes and fewer phone calls to the office.

Their brief, in their own words: **"Make applying simple, so we get fewer wrong applications and fewer calls to the office."**

That brief is bad on purpose. It gives you nothing you can measure. "Simple" can mean ten different things. "Fewer wrong applications" and "fewer calls" are two different problems. The brief does not say who applies, or what goes wrong for them. Week 1 turns this into something you can answer.

## 2. Why this service and not a social app

Four reasons.

1. **The stakes are real.** Candidates prepare for months, sometimes years, for one exam. A rejected application or a missed confirmation can cost a full exam cycle. Official guidance says a submitted application is provisional. It cannot be deleted or altered.
2. **The constraints are real.** You design in Malayalam and English. Malayalam script needs careful type. Many candidates use cheap phones on patchy mobile data. Photograph rules are strict. The submit step cannot be undone. Exam posts need a separate confirmation step.
3. **The current version is a rich source of problems you can see for yourself.** Studying a rough live service teaches more than copying a beautiful design. You will name what is wrong and check each claim yourself.
4. **There is no polished concept to copy.** Nobody has posted a smooth redesign of this flow. All your craft has to come from reasoning, not from memory of a picture.

## 3. The service, as it exists

Here is the journey in order. The Evidence column says how sure we are. "Verified" means we read it on an official public page or PDF. "Not public" means nobody outside the system can see it.

| Step | What happens | Evidence |
|---|---|---|
| 1 | Find the right notification under Recruitment > Notifications. Each post has a category number, like Cat.No.812/2025. | Verified (public page) |
| 2 | One Time Registration on the Thulasi portal. Sign up once, then log in with your User ID and password. | Verified (official instructions) |
| 3 | Open your profile, find the post, and click **Apply Now**. | Verified (Tips to Applicants) |
| 4 | Check your profile details. Photograph rules apply. The name and the date the photo was taken must be printed at the bottom. | Verified (Tips to Applicants). Screens are not public. |
| 5 | Submit. The application is provisional and cannot be deleted or altered. | Verified |
| 6 | For exam posts, confirm from your profile. The buttons are CONFIRM NOW, Send OTP and Submit. | Button names verified from an official PDF. Rules and time window: you check |
| 7 | Download the Admission Ticket. | Name verified. Rules: you check |

Now the part you will test yourself. This table lists things that look like problems. Each one is an observation to check, not a proven fact.

| Where it appears to break (verify each one yourself in week 1) | What the candidate may experience |
|---|---|
| The home page has no obvious Login link. Registration appears under two names: "One Time Registration" and "Candidates Registration". | Wanders around the home page and gives up. Or signs up twice. |
| "How to Apply" leads to a page that mostly links to PDF files, not to steps. | Cannot find the steps. Calls the office or asks a friend. |
| Key instruction PDFs use an old Malayalam font. Copied text comes out as garbage. | Cannot copy, search or hear the steps. A screen reader fails. |
| Photograph rules may differ between pages: "after 31.12.2010" on one page, "within six months" in an older notice. | Uploads a photo that is rejected later. |
| The warning that an application cannot be changed after submit: where is it, and how loudly is it shown before the button? | Does not see the warning, or sees it too late. |
| One home page area mixes many notice types: medical forms, date extensions, interview notices. | Misses the one notice that matters for them. |
| Some Results menu items, like "Exam Marks", open a different website. | Thinks the site is broken. Or loses their place. |

> **Verify yourself:** Pick three rows from this second table. Look for each one at https://www.keralapsc.gov.in/ and write what you actually see. If you cannot find it, write "not found" and say where you looked.

## 4. Users

Three people. Every designer designs for all three, not just the one who looks like them.

**Anjali, 23, final year graduate, Thrissur.** Good phone, good data. Reads English and Malayalam easily. Applies between classes, often in a hurry. This is her first set of PSC posts. **How she fails:** she misses a deadline or the confirmation step. The dates and the steps sit in different places. She also picks the wrong post, because several notices look alike.

**Suresh, 38, repeat applicant, shop assistant, Kozhikode.** Malayalam first, English slowly. Cheap Android phone, data that drops. He has applied many times. He is afraid of the submit button, because it cannot be undone. **How he fails:** he freezes before submitting. Or he submits a photo that is found invalid later. Sometimes he pays an internet café to do it, and never sees what was typed.

**Meera, 29, low vision, Kollam.** She uses a screen magnifier and TalkBack. TalkBack is a free screen reader on Android that reads the screen aloud. She needs the scribe instructions (the rules for a helper who writes for her) and the confirmation steps. **How she fails:** she cannot read the PDF instructions at all. So she cannot even start the confirmation step.

**Secondary user:** the assisted centre operator. This person works in an internet café or an e-centre. They fill many applications a day for other people, on a shared desktop. They work keyboard first and want speed over friendliness. They get a proper design in Sprint 5. Here we only note them.

## 5. Constraints, all real

| Constraint | What it means for your design |
|---|---|
| A submitted application is provisional and cannot be deleted or altered. | Stop mistakes before submit. Do not explain them afterwards. |
| Photograph rules: name and date at the bottom, and a validity period. | Show the rules before the upload, not after a rejection. You check the exact current rule. |
| No application fee. | Fewer payment problems. But every submit still matters. |
| Exam posts need a separate confirmation with an OTP. An OTP is a one time password sent to the phone. | Show the deadline and the next step at the moment of submit. Show them again in the profile. |
| Malayalam and English. | Type must survive Malayalam script. Layout must survive text of different lengths. |
| Mobile data is often slow or patchy. | Every image, every step and every retry has a cost. |
| Government accessibility duty: the Rights of Persons with Disabilities Act, 2016, and GIGW, the guidelines for Indian government websites. | Accessibility is a requirement. WCAG 2.2 AA is the standard for this course. |
| The Commission's rules cannot be changed. | You redesign the experience, not the policy. |
| You cannot see inside the logged in portal in public. | You work from your own profile if you have one, the official PDFs, and the admin's reference screens. Say which evidence each claim rests on. |

Constraints are not up for a vote. **A solution that needs the Commission to change its rules is out of scope. Saying so is part of the work.**

## 6. Scope

**In scope**
- Finding the right notification and the right post, including telling similar posts apart
- Getting into the profile, and what happens when you cannot log in
- **Apply Now** and the check of profile details before submit
- Photograph and signature guidance and upload
- Submit, acknowledgement, and "what happens next"
- Confirmation for exam posts: CONFIRM NOW, OTP, Submit, and the deadline
- The admission ticket and a simple "my applications" status view
- All of this at 390 pixels (phone) and 1440 pixels (desktop), in Malayalam and English
- The shared design system the five flows are built on

**Out of scope**
- The full One Time Registration form (the long profile sign up)
- Results, rank lists and exam content
- Interview scheduling
- The assisted centre console (Sprint 5)
- Native app design
- Backend, policy and security design
- Brand or logo work

## 7. Success measures

You name these in week 1, before you design anything.

**Primary metric.** Application completion rate. That is applications submitted divided by **Apply Now** clicks.

**Input metrics.** Photograph upload retry rate. Time from **Apply Now** to submit. The share of exam post applicants who finish confirmation before the window closes. Contacts to the office about "how do I" questions.

**Guardrail metric.** Wrong or ineligible applications must not rise. Watch summary rejections and duplicate applications. A summary rejection means an application is thrown out for not following the notification. A flow that is fast because it stopped checking anything is a failure. Every designer names one guardrail and defends it at the defense.

You do not have these numbers. Nobody is giving you the Commission's data. That is normal. You name the metric, and you say how you would measure it. Where a number would help your argument, find one or estimate one, and write the method. If you assume a figure, write **"Assume for the exercise:"** in front of it.

## 8. Deliverables by week

| Week | Ships |
|---|---|
| 1 | Problem reframe (P1.1, P1.2). Constraint list (P1.3). Metric definition (P1.4). Heuristic audit (R1.2), which is a check against 10 known usability rules. Accessibility audit, including the PDF check (R1.3). Type scale (C1.1), a short list of font sizes used again and again, with the Malayalam test. Spacing scale (C1.2). Colour system (C1.3). |
| 2 | Flow diagram with every failure path (P2.1). The can't-get-in path (P2.2). Form structure decision (P2.3). First components and the mid fidelity happy path (C3.1). Mid fidelity means rough screens, not final visuals. Photograph and signature guidance (C3.2). Check-your-answers screen (C3.3). Upload states (C3.4). Every error message in Malayalam and English (C4.1, C4.2). |
| 3 | All states for all screens. Usability test with 3 people (R2.x). The injected failure, handled. Post mortem. |
| 4 | High fidelity at both widths. Accessibility gate passed. Handoff spec, the notes a developer needs to build it. Decision record. Defense. |

## 9. The shared system

All designers build one design system together, in the folder `system/`. Not five systems.

Why? A system that only one person uses proves nothing. A system that five people build on straight away shows the real problems. Those problems are naming, ownership, and the cost of changing a token everyone depends on. A token is a named value, like a spacing step or a colour role.

The system owner changes every week. Before the sprint is called done, the system must build. Its documentation must match what is inside it.

## 10. Reference material

The full list, with tiers, is in `../03-Books-And-Resources.md`. These four are assigned reading, not reference:

- Refactoring UI, Wathan and Schoger, chapters 1 to 6 and 8
- Form Design Patterns, Adam Silver, chapters 1 to 3
- The Design of Everyday Things, Norman, chapters 1 to 4
- WCAG 2.2 quick reference, Level AA criteria: https://www.w3.org/WAI/WCAG22/quickref/

Before you write anything, study the real service at https://www.keralapsc.gov.in/. Read the public pages and the PDF files. Start with these:
- Tips to Applicants: https://www.keralapsc.gov.in/tips-applicants
- OTR Instructions: https://www.keralapsc.gov.in/otr-instructions-candidates
- Notifications: https://www.keralapsc.gov.in/notifications
- The new registration PDF: https://www.keralapsc.gov.in/sites/default/files/inline-files/otr.pdf
- The confirmation PDF: https://www.keralapsc.gov.in/sites/default/files/inline-files/confirmation_0.pdf

Screenshot everything you legitimately can. Write down what you cannot reach. Section 12 tells you how.

## 11. The client conversation you will not get

Real government teams do not run design reviews. You will not get a friendly chat to check your thinking.

The core admin plays the client. Expect a change in week 3, and expect it to be awkward. That is not unfair. That is the job. A designer who only works when the brief holds still is not ready for work.

## 12. Study it safely

This is a study of a public service by students. You are not a candidate here. You are not testing the system. Follow these rules.

- [ ] Use only public pages, and your own existing profile if you already have one.
- [ ] Do not create an account for this course.
- [ ] Do not enter another person's details anywhere.
- [ ] Do not submit, confirm or change anything.
- [ ] Do not try other people's User IDs. Do not repeat failed logins.
- [ ] Hide your User ID, name, date of birth, photo, phone number and email in every screenshot before you commit it.
- [ ] Note the Aadhaar ID proof field in a candidate's profile only as a field. Never show the number.
- [ ] Do not post screenshots of private data anywhere.
- [ ] Write "not reachable" for anything you cannot open, and list it as a gap.
