# Sprint 1 — Glossary

Every term used in Sprint 1, defined plainly. If a task uses a word you do not know, it is here.

Terms are grouped by where you meet them. Each definition gives the tradeoff or the reason. In the defense you will be asked for the tradeoff, not only the definition.

---

## Typography

**Type scale** — A small, fixed set of font sizes you choose in advance. You often make it from a base size and a ratio. Use only these sizes. Then you stop picking sizes by eye. Many screens stay consistent, and each choice takes no time.

**Ratio** — The multiplier between steps in a type scale. 1.2 is calm and good for dense interfaces. 1.25 is a safe default. 1.333 and above grow fast. They suit marketing pages more than forms.

**Line height / leading** — The vertical space from one line of text to the next. We write it as a multiple of the font size. Large text needs less space, about 1.1 to 1.2. The lines already look separate. Body text needs more, about 1.5 to 1.6. Then the eye can find the next line.

**Measure** — The length of a line, counted in characters. 45 to 90 characters works. 60 to 70 is comfortable. A narrow line makes the eye jump back too often. A wide line makes the eye lose its place.

**Font weight** — How thick the letters look. 400 is regular, 500 is medium, 600 is semibold, 700 is bold. Two or three weights are enough for a whole interface. More weights often hide a problem that size or colour should fix.

**Malayalam script** — The script used for Malayalam, the main language of Kerala. It has many joined letters (conjuncts). It also has tall parts above and below the line. So text needs more line height than English text. Test it at every size. Check for letters that get cut off or crowded. Our project uses Malayalam and English, so test both.

**Baseline** — The invisible line that letters sit on. When you align items to baselines instead of box edges, the layout looks settled. That is why a good layout feels calm.

---

## Colour

**Ramp** — A set of steps of one colour, from light to dark. Most ramps have 10 steps, named 50 to 900. If you build the full ramp first, you never invent a colour in the middle of a screen.

**Even-looking steps** — Steps that look equally spaced to your eye. A computer can make steps that are equal in maths. But our eyes do not see those steps as equal. A tool like Leonardo makes steps that look even.

**Semantic colour** — A colour named for its job, not for its colour. For example, `error-text`, not `red-600`. The job stays the same but the value can change. That is what makes theming (a different look for a brand or a dark screen) possible.

**Primitive token** — The raw value. `blue-500: #3B82F6`. It means nothing on its own.

**Semantic token** — A name for a job that points at a raw value. `interactive-default: blue-500`. This is the layer that components use.

**Contrast ratio** — A number that measures how different two colours look. We write it like 4.5:1. WCAG (the web accessibility rules this course follows) needs 4.5:1 for body text. It needs 3:1 for large text and for graphics that carry meaning.

**Non-text contrast** — The WCAG rule 1.4.11. Borders, icons, focus rings and any graphic that carries meaning need 3:1. People miss this rule often. They check the text and then stop.

## Layout and hierarchy

**Visual hierarchy.** The order in which a viewer notices things. You create this order on purpose. You build it from size, weight, colour and space. Using all four on the same element usually means the hierarchy is not working.

**De-emphasising.** Making the less important things quieter, instead of making the important thing louder. This is often the better move, because the loud version has nowhere left to go.

**Spacing scale.** A fixed set of spacing values that you use again and again. For example: 4, 8, 12, 16, 24, 32, 48, 64. The steps grow bigger at the top end, because two steps next to each other must look clearly different. If they look the same, the scale gives you no real choice.

**Proximity (Gestalt).** Gestalt means the way the eye groups things by itself. Things placed close together are read as related. So the gap between a label and its own input must be smaller than the gap between two fields. Get this wrong and users read the label as belonging to the field above.

**Common region (Gestalt).** Things inside one shared boundary are read as a group, even when they sit far apart. That is why cards work.

**Figure-ground.** What the eye reads as the subject, and what it reads as the background. A modal (a box that sits over the page and blocks it) depends on this. A modal with a weak dark overlay fails at it.

**Optical alignment.** Adjusting alignment by eye, not by coordinate. Round shapes and pointed shapes must hang slightly outside the line to look aligned. Aligned to the grid is not always aligned to the eye.

---

## Forms

**Label**: The visible text that names a form field, a box where the user types. It stays above the field on mobile and is linked to it in the code. That link makes a screen reader (software that reads the screen aloud) say the label.

**Placeholder**: Grey text inside an empty field. It is not a label, and it disappears when the user starts typing, at the moment they need it. It often has low contrast (it is hard to see), so use it only for an example format.

**Hint text / help text**: Guidance that sits below the label. It stays visible while the user types and after an error.

**Inline validation**: A check of one field when the user leaves it. It helps with formats the user cannot guess, like a PIN code. It is bad on every key press, because it says people are wrong while they type.

**Error summary**: A block at the top of a form that lists every error and links to each field. The GOV.UK website uses this pattern. It helps because an error at the bottom can be missed, and screen reader users need to hear how many errors there are.

**Check your answers (pattern)**: A review screen before the final submit. It shows the user's answers in small groups, and each group has a Change link. It helps stop mistakes before a submit that cannot be undone.

**One thing per page**: A form split so each screen asks one question. It lowers mental effort and makes errors easy to fix. It adds page loads, which is slow on a weak connection, and task P2.3 studies this balance.

**Progressive disclosure**: Showing only what the user needs now. More appears when it is needed, which makes a form feel simpler. The risk is hiding something the user needs to decide.

---

## States

**States matrix** — A grid of screens against possible states. Screens go down one side and states go across the top. You fill each cell with what the screen shows. Empty cells are the states you forgot. Counting the empty cells is a more honest test of a design than counting screens.

**Empty state** — What a screen shows when there is no content yet. A good empty state says three things. What belongs here. Why it is not here. What to do next. "No data" is a failed empty state.

**Loading state** — What is shown while the screen waits for content. Pick the sign by how long the wait will be. A very short wait needs no sign. A short wait can show a skeleton (a grey shape where content will be) or a spinner (a small turning circle). A long wait needs a progress bar and a short message. If the wait is very long, fix the cause instead.

**Skeleton screen** — A grey placeholder in the shape of the content that is coming. It is better than a spinner when you know the page layout. It stops the page from jumping, and it shows people what is coming.

**Partial state** — Some content has loaded and some has not. Real systems do this often and designers rarely draw it. It is not the same as loading, and it is not an error.

**Optimistic UI** — The screen shows the result as if the action worked, before the server has said yes. It feels instant. You must also design the moment it turns out to have failed. Most teams skip that half.

**Session timeout** — The system logs a person out because they did nothing for a while. Warn people before it happens. Say what they will lose and how to keep it.

**Idempotent** — An action that gives the same result if it runs once or five times. This matters when a candidate taps Submit, the connection drops, and they tap Submit again. If Submit is not idempotent, they may send two applications for one post.

**Destructive confirm** — A check step before something that cannot be undone. It must name exactly what will be lost. "Are you sure?" names nothing. In this sprint, the submit step is the one to protect.

## Accessibility

**WCAG**: Web Content Accessibility Guidelines. Level A is the minimum. Level AA is the standard most teams use, and this course uses it. Level AAA is stricter and rarely required in full.

**GIGW**: Guidelines for Indian Government Websites. Indian government sites are expected to follow them. This course also uses WCAG 2.2 AA.

**Success criterion**: One numbered, testable rule, for example 1.4.3 Contrast (Minimum). Cite it by number. "This is inaccessible" is an opinion. "This fails 1.4.3 at 2.85:1" is a finding.

**Focus**: The element that receives keyboard input right now. Only one element has focus at a time.

**Focus visible (2.4.7)**: You can see which element has focus. `outline: none` removes the focus ring. If you do not replace it, keyboard users lose their place. This is a common failure.

**Focus order (2.4.3)**: The order Tab moves through the page. It must match the visual reading order. If it does not, keyboard users get lost.

**Focus trap**: Keeping keyboard focus inside a modal while it is open. A modal is a box that opens over the page. This is correct for modals. It is a bug when there is no way out. Escape must always work.

**Accessible name**: The text a screen reader announces for an element. An icon button with no name is announced as "button". That tells the user nothing.

**ARIA (Accessible Rich Internet Applications)**: Attributes that describe roles, states, and links to assistive technology. Assistive technology means tools that help people with disabilities use a device. First rule: do not use ARIA if a built-in HTML element already does the job. A `<button>` is better than `<div role="button">`.

**Live region**: An area whose changes are announced without moving focus. It can tell a screen reader user that a search returned 12 results. It can also announce a step change.

**Target size (2.5.8)**: The smallest size allowed for anything tappable. At AA, the minimum is 24 by 24 pixels. For phones, 44 by 44 pixels is a practical guide.

**Screen reader**: Software that reads an interface aloud. VoiceOver is on macOS and iOS. NVDA and JAWS are on Windows. TalkBack is on Android.

**Reduced motion**: A system setting that asks for less motion. Respect it for any animation over 200ms. Some people have balance problems. Large motion can make them feel sick. It is not just a preference.

**Verify yourself**: A course callout. It asks you to check a fact on the live service yourself. Write "not found" if you cannot confirm it.

## Research

**Heuristic evaluation** — A review of an interface against a fixed set of rules, usually Nielsen's 10 principles. It is quick and cheap, and it finds real problems. It cannot show what users will really do. So this sprint does both: this review and a usability test.

**Nielsen's 10 heuristics** — Ten simple rules to check an interface against. They are: visibility of system status · match between system and real world · user control and freedom · consistency and standards · error prevention · recognition rather than recall · flexibility and efficiency · aesthetic and minimalist design · help users recognise, diagnose and recover from errors · help and documentation.

**Severity rating** — A number from 1 to 4 that shows how bad a problem is. 1 = cosmetic. 2 = minor, users can work around it. 3 = major, users fail the task. 4 = catastrophic, users lose data or money. The rating helps teams fix the worst problems first.

**Moderated usability test** — You watch a person try a task and mostly stay quiet. Your only reliable questions are "what are you trying to do?" and "what did you expect?".

**Think aloud** — Asking the participant to say their thoughts out loud as they work. It slows them down a little, but it is the most useful thing to ask for.

**Leading question** — A question that contains its own answer. "Did you see the Continue button?" is leading. It spoils the finding you were about to get.

**Task, in a test** — A goal with no route. "Apply for the post" is a task. "Click Apply Now, then click Next, then click Submit" is a script, and it tests nothing.

## Kerala PSC terms

**Admission ticket** — A document named "Admission Ticket" that a candidate downloads for an exam post. The exact rules are not in the public pages we checked. Check the rules yourself.

**Apply Now** — The button in your profile that starts an application for a post. Log in, find the post in the notification, then click it.

**Category number (Cat.No.)** — A code that names a post in a notification, like `Cat.No.812/2025`. Each post has its own code. Use it to tell similar posts apart.

**Confirmation (for exam posts)** — A separate step after you submit, for posts with an exam. The official PDF shows three buttons: CONFIRM NOW, Send OTP, Submit. OTP means one-time password: a short code sent to you. The exact rules and the deadline window are not in the public pages we checked. Check them yourself.

**Notification** — The official announcement of one or more posts. It gives the category numbers, qualifications and dates. You find it under Recruitment > Notifications. You apply for a post from its notification.

**One Time Registration (OTR)** — A sign-up you do once on the Thulasi portal. After that, you log in with your User ID and password to apply for any post. The home page uses two names for it: "One Time Registration" (a tile) and "Candidates Registration" (under Must Know).

**Profile** — Your personal record on the Thulasi portal. It holds your details and your photograph. You check it before applying, and you click Apply Now there. You can print your registration card from it.

**Provisional application** — An application that is submitted but not final. It cannot be deleted or changed after you submit. So check everything before you press Submit.

**Summary rejection** — Rejecting an application straight away, without a full review. It often happens when the candidate did not follow the notification. So read the notification carefully.

**Thulasi portal** — The website where One Time Registration and login happen. Its public address is thulasi.psc.kerala.gov.in/thulasi/. You must log in to use it.

## Product

**Problem statement** — A short sentence with a fixed shape: `[user] cannot [job] because [problem], which costs [user cost] and [business cost].` Do not use solution words. If it names a screen or a feature, it is a solution.

**Primary metric** — The one number that decides if the work succeeded.

**Input metric** — Something that moves before the primary metric moves. It tells you earlier if you are on the right track.

**Guardrail metric** — Something that must not get worse while you improve the primary metric. People can cheat a number. The guardrail is where the cheating shows up.

**Constraint** — Something you cannot change. Sort each one into fixed policy, technical, or assumed. An assumed constraint is one you think is fixed, but nobody checked. In an old service, many constraints are only assumed. Those are the ones worth questioning.

**Decision record** — A one-page written note with six parts: context, options, decision, reason with evidence, results, and what would change your mind. Six months later, it tells a reader why you chose this. Without it, they may think you were careless.

## Systems and process

**Design system** — A set of tokens (named values), components, patterns and written rules, used across many products. The written rules and the people who keep them are what make it a system. A Figma file full of components is not a system on its own.

**Design token** — A named value, such as a colour or a space. Mature systems use three layers: primitive (raw value), semantic (job it does) and component (this part only). The layers let you change a theme without redesigning screens.

**Component API** — The set of properties a component lets other people change: variants, sizes, states and slots (places where content goes). Designing this set is deciding what other people may change. Anything outside the set is fixed by you.

**Governance** — Who decides what goes into the system, and how a new part is accepted or rejected. Without it, a design system is just a folder of files.

**Handoff spec** — Everything an engineer needs, written down: layout, components, interactions, states, checks, error messages, accessibility and open questions. The test is simple: can they build it without asking you anything?

**Critique** — A structured review against a rubric (a short list of things to judge). Every comment names a principle and what it costs the user. "I do not like it" is not a critique comment.

**Failure injection** — A change the admin makes to the brief in the middle of a sprint, on purpose. Real projects change, so the practice is useful. It shows you which of your earlier decisions made your work fragile.

**Post mortem** — A written review after something went wrong. The useful part is not the story of what happened. It is finding the earlier decision that would have made the problem cheaper.

**Defense** — The spoken exam at the end of each sprint. You explain and justify your work with no files in front of you. It tests your thinking, not your memory of a screen.

---

## Git

**Fork** — Your own copy of a repository, saved on your own account. A repository is a project folder and its saved history.

**Clone** — A copy of a repository on your own machine.

**Upstream** — The original repository that your fork came from. You copy new changes from it, so your copy stays up to date.

**Branch** — A parallel line of work. Use one branch for each task.

**Commit** — A saved change, with a short message. Start each message with the task ID.

**Pull request** — A request to merge (join) your branch into the main project. It is also where other people review your work.

**Diff** — The line-by-line difference between two versions of a file. We keep decisions in Markdown files because a diff shows each change clearly.
