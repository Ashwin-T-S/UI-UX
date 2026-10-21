# Week 12b - Code Your Showpiece With an AI Assistant

**Sprint 3, new week · Theme: one real page, made with AI, read by you, published for anyone to open**

## Week at a Glance

| Task ID | Task name | Time | File you will commit |
|---|---|---|---|
| Y1.1 | Pick one screen from your showpiece | 30 min | `students/UX{n}/week12b/Y1-1-screen-choice.md` |
| Y1.2 | Write the prompt and the spec | 60 min | `students/UX{n}/week12b/Y1-2-prompt-and-spec.md` |
| Y1.3 | Generate the page with an AI coding assistant | 60 min | `students/UX{n}/week12b/Y1-3-generation-notes.md` |
| Y1.4 | Read the code and fix 3 things by hand | 90 min | `students/UX{n}/week12b/Y1-4-code-reading.md` |
| Y1.5 | Check with axe and the keyboard | 45 min | `students/UX{n}/week12b/Y1-5-a11y-check.md` |
| Y1.6 | Publish on GitHub Pages | 60 min | `students/UX{n}/week12b/Y1-6-publish.md` |
| Y1.7 | AI note and AI log | 30 min | `students/UX{n}/week12b/Y1-7-ai-note.md` |
| L-AI6 | Lab: AI-assisted coded prototype (runs across Y1.1 to Y1.7) | record 30 min | `students/UX{n}/week12b/L-AI6-lab-record.md` |
| | The page itself | inside the tasks above | `students/UX{n}/week12b/page/index.html` and `style.css` |

About 9 hours 40 minutes of work in this week, including the listed resources.

## 1. What We Are Doing

This week you take one screen from your Sprint 3 showpiece and turn it into a small real web page. You do not design it again. You write a short spec, you ask a free AI coding tool to write the first version, then you read the code, fix three things with your own hands, test it, and publish it on GitHub Pages. At the end you can send a link and say, in plain words, what is inside the page and why.

The task groups:

- Group 1, choose and specify: Y1.1, Y1.2
- Group 2, generate and read the code: Y1.3, Y1.4
- Group 3, test, publish, record: Y1.5, Y1.6, Y1.7
- Group 4, lab L-AI6: one record file that holds the whole week

This week is new for most people. Go slowly.

## 2. Why We Are Doing It

A working product designer in India is often the person who sits between the design file and the engineers. You will not write production code. But you will be asked "can this be built", "why is this spacing wrong on mobile", and "what does this component need from us". A designer who has published one small page, and who can read what is in it, has a very different conversation with engineers than a designer who only hands over a picture.

For the project, this week turns your Sprint 3 showpiece from something people look at into something people can open and click. For the portfolio, you get a real link and a short story: I designed this, I built a small version with AI, I fixed these three things, I tested it, and here it is.

## 3. What to Learn First

By the end of the week you can:

- Take one Figma screen and write a prompt and a spec for it
- Generate a page with a free AI coding tool
- Read the HTML, CSS and JavaScript it made and name the parts out loud
- Fix three things by hand, and say what you changed
- Run axe DevTools and a keyboard check, and fix what they find
- Publish the page on GitHub Pages and share the link
- Explain to an engineer what your page is made of

Core ideas to review first:

- **HTML is structure.** Each part of the page is an element with an opening tag and a closing tag.
- **CSS is look.** A rule has a selector and one or more declarations. A declaration is a property and a value.
- **The box model** has four layers: content, padding, border, margin.
- **Flexbox** puts items in a row or a column, with gaps and alignment.
- **JavaScript is behaviour.** A small script can listen for a click and change the page.
- **The page runs in the browser.** No server, no database, nothing is saved. Static does not mean safe: before you publish, check the content, the external resources the page loads, and the network requests it makes.
- **Access basics:** real buttons, labels on inputs, meaningful alt text on informative images, `alt=""` on decorative images, a visible focus ring, enough contrast.
- **Never paste secrets or participant data** into an AI tool. No keys, no tokens, no real names, no phone numbers.

## 4. Where to Find Resources

Your week in order:

| Order | Source | What exactly | Time |
|---|---|---|---|
| 1 | MDN, Structuring content (https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content) | Headings, paragraphs, links, images, and how elements nest | 20 min |
| 2 | MDN, Styling basics (https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics) | Selectors, properties, values, and the box model | 20 min |
| 3 | web.dev/learn/css (https://web.dev/learn/css) | Pick the box model module and the flexbox module from the course list on the page | 25 min |
| 4 | web.dev/learn/javascript (https://web.dev/learn/javascript) | The first modules only: where a script goes, and what an event is | 15 min |
| 5 | GitHub Pages quickstart (https://docs.github.com/en/pages/quickstart) | How to publish from a branch and a folder | 15 min |
| 6 | `../07-AI-In-Design.md` | The AI footer rule and the AI log rule | 10 min |
| 7 | `../10-GitHub-For-Designers.md` | Branch, commit, pull request | 10 min |

Tools you open this week:

- **Figma**, to read values from your screen. Open `../04-Tools-Setup.md` and read the Figma part, where Figma first appears.
- **VS Code**, to read and edit the code. Open `../04-Tools-Setup.md`, the VS Code part.
- **Chrome**, to open the page, run axe DevTools and run Lighthouse. If Chrome is not on your machine, the browser part of `../04-Tools-Setup.md` has both Mac and Windows steps.
- **Git and GitHub**, to commit and push. Open `../04-Tools-Setup.md`, the Git part, then `../10-GitHub-For-Designers.md`.
- **Penpot** (https://penpot.app/), only if the Figma file limit blocks you this week. Check before use.
- **Your AI coding tool.** Free tier only. Check the free limit before use. Write the tool name and the date in your notes.

If you are stuck, search these words:

- `html button vs link when to use`
- `css flexbox center items gap`
- `html label for input id`
- `github pages deploy from branch folder`
- `axe devtools how to run a scan`
- `css focus visible outline`

## 5. Step-by-Step Guide

> All `students/...` paths in this week are inside your sprint folder (`Design-Sprint-N/`). Open a terminal in the repo root and use full paths.

One task, one commit with all files listed for that task. The branch, commit and pull request steps are in `../10-GitHub-For-Designers.md`.

Allowed file types this week: markdown (`.md`), PNG or JPG under 2 MB (lowercase name, hyphens, no spaces), PDF under 10 MB, a view-only Figma link written inside a markdown file, and the small page files for this task (`index.html`, `style.css`, `script.js`) inside `students/UX{n}/week12b/page/`. The course policy allows these small code files, and the same rule is used in Y1.3, Y1.4, Y1.5, Y1.6 and in the end of week checklist. Nothing else. If the repo check rejects a file, ask in Discord before you rename things.

> **Hard rule for the whole week:** never paste secrets or participant data into an AI tool or into a file. No API keys, no tokens, no passwords, no real names, no phone numbers, no participant quotes with names. Use P1, P2. If a tool asks for a key or a card, close it and use another tool.

> **You are not becoming an engineer.** The goal is a small page that works and the ability to talk to engineers about it. If a step feels like a programming exam, you are doing too much. Make it smaller.

### Group 1 - Choose and Specify

#### Task - Pick one screen from your showpiece (ID `Y1.1`)

##### 1. What We Are Doing

Choose one screen from the three hero screens you made in C12.3 and write down what it is made of.

##### 2. Why We Are Doing It

A small page that works beats a big page that half works. One screen can be built in a week, tested, published and explained in an interview. A whole flow cannot, not at this stage.

##### 3. What to Learn First

- What makes a screen easy to code: few parts, one column on mobile, two states at most.
- What "static" means: the page shows content and reacts to clicks, but it does not save anything and it does not talk to a server.
- Your screen is the reference for colours, type sizes and spacing. Copy the values, do not guess them.

##### 4. Where to Find Resources

- Your own `students/UX{n}/week12/C12-3-showpiece.md`, where the hero screens are described.
- Your Figma file `SPRINT-3 UX{n}`, on the week 12 page.
- MDN, Structuring content (https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content), to see the small set of HTML parts you will need.

##### 5. Step-by-Step Guide

1. Open your Figma file `SPRINT-3 UX{n}`.
2. Go to the week 12 page.
3. Look at the three hero screens you made for C12.3.
4. Pick the one with the fewest parts.
5. Create the file `students/UX{n}/week12b/Y1-1-screen-choice.md`.
6. Write the screen name as a heading.
7. Write one sentence: what the person does on this screen.
8. List the parts you can see, in reading order, for example heading, short text, two buttons, one image.
9. Write the two states you will build, for example default and confirmation.
10. Write a short "not building" line: no login, no payment, no saved data.
11. Copy the exact colours, font names, font sizes and spacing values from Figma into the file.
12. Add a PNG export of the screen at 2x, named `y1-1-screen.png`.

If you get stuck:

- Read step 8 again and write only what you can point at on the screen.
- Select the layer and read its colour, typography and spacing values in the Design panel, instead of guessing.
- Post a screenshot of the screen in Discord and ask which one people would pick.

**How to think about it:** you are choosing for the build, not for the portfolio. The best pick is the screen with the fewest parts that still looks like your product.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/Y1-1-screen-choice.md`
- [ ] `students/UX{n}/week12b/y1-1-screen.png` (under 2 MB)
- [ ] The screen name, the one sentence, the parts list and the two states are in the file
- [ ] The exact colour and type values from Figma are in the file
- [ ] The "not building" line is in the file

Commit message: `Y1.1 choose the screen for the coded page`

---

#### Task - Write the prompt and the spec (ID `Y1.2`)

##### 1. What We Are Doing

Write a short spec and a prompt before you open any AI tool.

##### 2. Why We Are Doing It

The AI gives you back what you describe. A vague prompt gives a vague page, and then you cannot tell what went wrong or what to fix. Writing the spec first also means the design decisions stay yours.

##### 3. What to Learn First

- What a useful prompt contains: the goal, the parts, the states, the real values, the rules, and what to leave out.
- What "plain" code means here: one HTML file, one CSS file, a little JavaScript, no frameworks, no paid libraries.
- The data rule: the prompt never contains real names, phone numbers, keys or participant quotes.

##### 4. Where to Find Resources

- `../07-AI-In-Design.md`, for the AI footer and the AI log rules.
- MDN, Structuring content (https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content), for the names of the parts.
- Your own `Y1-1-screen-choice.md`.

##### 5. Step-by-Step Guide

1. Create the file `students/UX{n}/week12b/Y1-2-prompt-and-spec.md`.
2. Write the goal in one sentence: what the page is for.
3. Paste the parts list from Y1.1.
4. Paste the exact colours, font sizes and spacing values from Figma.
5. Write the two states and what changes between them.
6. Write a rules block: one `index.html`, one `style.css`, plain JavaScript only, no frameworks, no outside libraries, no images I do not own.
7. Write an accessibility block: real `button` elements, a `label` for every input, meaningful alt text for informative images, `alt=""` for decorative images, a visible focus ring, body text contrast at least 4.5 to 1.
8. Write a "do not" block: no real names, no phone numbers, no participant data, no API keys, no passwords, no analytics scripts.
9. Write the prompt as one short paragraph that points to the spec above it.
10. Choose your AI coding tool from the free options you know. Check the free limit before use.
11. Write the tool name and today's date in the file.
12. Save the file and commit.

If you get stuck:

- Copy the structure of your C12.3 caption. It already says problem, decision, result.
- Search `good prompt for html css page` and read one result, then write your own.
- Ask someone in Discord to review the "do not" block. That block is the one that must be right.

**How to think about it:** the spec is for you and the prompt is for the tool. If the tool produces something strange, the fix is almost always in the spec, not in the tool.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/Y1-2-prompt-and-spec.md`
- [ ] The goal sentence, the parts, the exact values, the two states
- [ ] The rules block, the accessibility block, the "do not" block
- [ ] The prompt paragraph, the tool name and the date
- [ ] No secrets and no participant data anywhere in the file

Commit message: `Y1.2 write the prompt and spec for the coded page`

---

### Group 2 - Generate and Read the Code

#### Task - Generate the page with an AI coding assistant (ID `Y1.3`)

##### 1. What We Are Doing

Run your prompt in a free AI coding tool, then save the output as real files in your week folder and open them in the browser.

##### 2. Why We Are Doing It

The first output is a draft, not the answer. Getting it into files early means you can see it, break it, and fix it. This is the same habit as saving a bad version of a design instead of describing it.

##### 3. What to Learn First

- A page is usually three files: `index.html` for structure, `style.css` for look, `script.js` for behaviour.
- The browser finds the CSS through a `link` tag in the `head`, and the script through a `script` tag.
- File names matter. `index.html` is the name browsers and GitHub Pages look for first.

##### 4. Where to Find Resources

- `../04-Tools-Setup.md`, the VS Code part, if VS Code is not open yet. It gives both Mac and Windows steps.
- MDN, Structuring content (https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content), for the `head` and `link` parts.
- `../07-AI-In-Design.md`, for what you must log.

##### 5. Step-by-Step Guide

1. Open your AI coding tool.
2. Paste your spec, then your prompt.
3. Ask for one `index.html` and one `style.css` first, with no JavaScript.
4. Read the reply once before you copy anything.
5. Check the reply only uses content you wrote. If it invented text or images, say so and ask again.
6. Create the folder `students/UX{n}/week12b/page/`.
7. In VS Code, create `index.html` in that folder and paste the HTML.
8. Create `style.css` in the same folder and paste the CSS.
9. Check the `head` has a `link` tag that points to `style.css`.
10. Open `index.html` in Chrome. On Mac, right click the file and choose Open With, Chrome. On Windows, right click the file and choose Open with, Chrome.
11. Take a screenshot and save it as `y1-3-first-result.png`.
12. Write three things that are wrong or missing in `Y1-3-generation-notes.md`.
13. Write one line on what the AI did well.
14. Commit.

If you get stuck:

- If the page opens with no styling, the `link` tag is wrong. Read step 9 again.
- If the tool stops or asks for money, stop and use a different free tool. Check the free limit before use.
- Post the screenshot in Discord next to your Figma screen and ask what people see first.

**How to think about it:** compare the browser result to Figma the way you would compare a junior designer's first version. Name the gaps, do not judge the whole thing.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/page/index.html`
- [ ] `students/UX{n}/week12b/page/style.css`
- [ ] `students/UX{n}/week12b/Y1-3-generation-notes.md`
- [ ] `students/UX{n}/week12b/y1-3-first-result.png` (under 2 MB)
- [ ] The page opens in your browser with styling applied
- [ ] Three gaps are written down

Commit message: `Y1.3 generate the first version of the page`

---

#### Task - Read the code and fix 3 things by hand (ID `Y1.4`)

##### 1. What We Are Doing

Read the HTML and CSS from top to bottom, name each part, then change three things yourself.

##### 2. Why We Are Doing It

If you cannot read the code, you cannot fix it, and you cannot talk to an engineer about it. Three hand fixes are also your proof that you are the designer here, not a person copying output.

##### 3. What to Learn First

HTML, in one screen:

- `<h1>` is the main heading, `<p>` is a paragraph, `<button>` is a button, `<a href="...">` is a link, `<img src="..." alt="...">` is an image.
- An attribute sits inside the opening tag and gives extra information, like `alt` or `href`.
- Elements sit inside other elements. The inside one is a child.

CSS, in one screen:

- A rule looks like `selector { property: value; }`.
- A class is written `class="card"` in HTML and `.card` in CSS.
- The box model is four layers on every element: content, padding, border, margin.

JavaScript, in one screen:

- `<script src="script.js" defer></script>` loads the file after the HTML is ready.
- `document.querySelector(".card")` finds an element on the page.
- `element.addEventListener("click", ...)` runs code when the person clicks.
- `element.classList.toggle("is-open")` adds or removes a class, and the CSS does the rest.

##### 4. Where to Find Resources

- MDN, Styling basics (https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics), for selectors and the box model.
- web.dev/learn/css (https://web.dev/learn/css), the box model module and the flexbox module.
- web.dev/learn/javascript (https://web.dev/learn/javascript), the first modules, for the script tag and events.

##### 5. Step-by-Step Guide

1. Open `index.html` in VS Code.
2. Read only the first 10 lines.
3. Find the `head` and write what is inside it.
4. Find the `body`.
5. Write every element inside the `body`, in order, in your notes file.
6. Pick one attribute and write what it does.
7. Check every image: informative images have meaningful alt text, not a file name, and decorative images have `alt=""`.
8. Check every input has a `label` connected with `for` and `id`.
9. Check buttons are `button` and links are `a`.
10. Open `style.css`.
11. Find one element and write its four box model values.
12. Find the flex container and list its children.
13. Compare every colour in the CSS to your Figma values and mark the ones that are off.
14. Fix 1, a visual value: change a spacing, size or colour so it matches Figma.
15. Fix 2, an accessibility problem: alt text, a label, the focus ring, or contrast.
16. Fix 3, a content problem: wrong copy, wrong order, or a missing state.
17. If you want the second state to work, ask your AI tool for a small `script.js` that toggles a class on a button click.
18. Read every line of the reply before you save it.
19. Save it as `students/UX{n}/week12b/page/script.js`.
20. Open `index.html` and add this line just before the closing `</body>` tag: `<script src="script.js" defer></script>`.
21. Save `index.html`.
22. Refresh the page in Chrome.
23. Click the button and check the second state appears.
24. Click again and check it goes back to the first state.
25. Refresh the browser once more and screenshot the final result as `y1-4-after-fixes.png`.
26. Write each fix as before and after in `Y1-4-code-reading.md`.

If you get stuck:

- Read the element names out loud. If you cannot name a part, look it up on MDN, Structuring content.
- Search `css box model padding vs margin` and read one short page.
- Post your three lines of code in Discord with what you expected and what happened.

**How to think about it:** reading code is like reading a wireframe. You are checking order, grouping and labels, not memorising syntax. You only need to be able to point at a line and say what it does.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/Y1-4-code-reading.md`
- [ ] `students/UX{n}/week12b/y1-4-after-fixes.png` (under 2 MB)
- [ ] The updated `students/UX{n}/week12b/page/index.html` and `style.css`
- [ ] `students/UX{n}/week12b/page/script.js`, only if you used one
- [ ] Every element in the body is listed in your notes
- [ ] Three fixes are written as before and after, one visual, one accessibility, one content
- [ ] No secrets and no participant data in the files

Commit message: `Y1.4 read the code and fix three things`

---

### Group 3 - Test, Publish, Record

#### Task - Check with axe and the keyboard (ID `Y1.5`)

##### 1. What We Are Doing

Run axe DevTools on the page, walk the page with the keyboard, fix what you find, and record the results.

##### 2. Why We Are Doing It

This is your Sprint 1 accessibility gate, now applied to something real. Automated tools find some problems. A keyboard check finds additional problems with focus, order and operation; these checks do not find every accessibility problem. Both are quick, and both are things a working designer is expected to do before handover.

##### 3. What to Learn First

- **axe DevTools** is a free browser extension that scans a page and lists accessibility problems.
- **Keyboard basics:** Tab moves forward, Shift + Tab moves back, Enter and Space activate, Escape closes.
- **Focus visible** means you can always see which element is selected.
- A screen reader reads the page out loud. VoiceOver is on Mac, NVDA is on Windows.

##### 4. Where to Find Resources

- axe DevTools, installed from the Chrome Web Store, free. Check before use.
- Chrome DevTools, built in and free.
- VoiceOver on Mac: press Cmd + F5 to turn it on and off.
- NVDA on Windows: https://www.nvaccess.org/, free. Check the current version before use.

##### 5. Step-by-Step Guide

1. Open Chrome.
2. Go to the Chrome Web Store and search for axe DevTools.
3. Click Add to Chrome.
4. Click Add extension. This is the same on Mac and Windows.
5. Open a new tab and type `chrome://extensions` in the address bar.
6. Find axe DevTools in the list of extensions.
7. Click Details.
8. Turn on "Allow access to file URLs".
9. Open your `index.html` in Chrome.
10. Open DevTools. On Mac press Cmd + Option + I. On Windows press Ctrl + Shift + I.
11. Open the axe DevTools tab.
12. Click Scan all of my page.
13. Screenshot the results as `y1-5-axe.png`.
14. Fix the most serious issue first.
15. Save the file.
16. Reload the page in Chrome.
17. Scan again.
18. Repeat steps 14 to 17 until nothing serious is left.
19. Click in the browser address bar.
20. Press Tab once.
21. Press Tab through the whole page.
22. Write the order in your notes.
23. Check the focus ring is visible at every stop.
24. Press Enter on each button and check it does what it says.
25. Press Space on each button and check it does what it says.
26. Optional screen reader check. On Mac, press Cmd + F5 and Tab through. On Windows, install NVDA from https://www.nvaccess.org/ and Tab through.
27. Write every result and every fix in `Y1-5-a11y-check.md`.

If you get stuck:

- If the axe tab does not appear, go back to `chrome://extensions`, check axe DevTools is turned on, then reload the page.
- If axe will not scan the file, go back to step 7 and check that "Allow access to file URLs" is on. If it still fails, ask in Discord for help restoring axe access, and finish the scan before you submit.
- If you cannot see the focus ring, search `css focus visible outline` and add the rule yourself.
- Ask in Discord with your axe screenshot and the line of code you think is the cause.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/Y1-5-a11y-check.md`
- [ ] `students/UX{n}/week12b/y1-5-axe.png` (under 2 MB)
- [ ] The updated `students/UX{n}/week12b/page/index.html` and `style.css`
- [ ] `students/UX{n}/week12b/page/script.js`, only if you used one
- [ ] The axe scan result is written down, before and after
- [ ] The keyboard order is written down, not just "it works"
- [ ] Every fix you made is listed

Commit message: `Y1.5 check the page with axe and the keyboard`

---

#### Task - Publish on GitHub Pages (ID `Y1.6`)

##### 1. What We Are Doing

Put the page online with GitHub Pages, get a link you can share, and run the accessibility audit on the live link.

##### 2. Why We Are Doing It

A link is proof. Anyone can open it, on any device, without your laptop. You also learn what "deploy" means, which is a word you will hear in every engineering standup.

##### 3. What to Learn First

- **GitHub Pages** is free hosting for static files, served from a repository.
- **Static** means HTML, CSS, images and small scripts. No server code, no database, no secrets.
- Pages publishes from a branch and a folder. The quickstart page shows the current options.
- **Lighthouse** is built into Chrome. You run the Accessibility part only, on the live HTTPS link.
- Anything you put in the repository can be public. Never put keys or personal data in it.

##### 4. Where to Find Resources

- GitHub Pages quickstart: https://docs.github.com/en/pages/quickstart
- `../10-GitHub-For-Designers.md`, for push and pull request.
- `../04-Tools-Setup.md`, the Git and GitHub part, for both Mac and Windows steps if push is new.

##### 5. Step-by-Step Guide

1. Commit your page files.
2. Push your branch to your fork on GitHub.
3. Open your fork on https://github.com/ and click Settings.
4. Click Pages in the left menu.
5. Under Source, choose Deploy from a branch.
6. Choose your branch.
7. Choose the folder `/ (root)`. Read the quickstart page before you pick.
8. Click Save.
9. Wait a few minutes.
10. Reload the Pages settings page.
11. Copy the site link it gives you. It looks like `https://<your-name>.github.io/UI-UX/`.
12. Add your page path to the end of that link: `/Design-Sprint-3/students/UX{n}/week12b/page/`.
13. Open the full link in a new tab.
14. Open the same link on your phone.
15. Open DevTools on the live link. On Mac press Cmd + Option + I. On Windows press Ctrl + Shift + I.
16. Open the Network tab.
17. Reload the page and check no request goes to a site you do not know.
18. Open the Lighthouse tab.
19. Tick Accessibility only.
20. Click Analyze page load.
21. Write the score down.
22. Check the page text again for real names, phone numbers and any personal data.
23. Fix anything you found, and commit the fix.
24. Write the link in `Y1-6-publish.md` as a normal markdown link.
25. Write the date.
26. Write one line on what you had to change to make it publish.

If you get stuck:

- If the link shows a 404, wait five more minutes and reload. The first publish is slow.
- If the page loads with no styling, your file paths do not match. Check the `link` tag again.
- If the link shows an error, read the path after the site link letter by letter: `/Design-Sprint-3/students/UX{n}/week12b/page/`.
- Ask in Discord with your Pages settings screenshot and the link. Do not spend more than 15 minutes alone on the path.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/Y1-6-publish.md` with the live link
- [ ] The page files are pushed and the page is online
- [ ] The link opens on a phone as well as on your laptop
- [ ] The Lighthouse accessibility score, run on the live link, is written down
- [ ] `students/UX{n}/week12b/page/index.html` and `style.css`, if the Lighthouse run or the network check made you fix something
- [ ] Nothing private is in the repository

Commit message: `Y1.6 publish the page on GitHub Pages`

---

#### Task - AI note and AI log (ID `Y1.7`)

##### 1. What We Are Doing

Write the AI note for the week, add the AI footer to your page work, and complete the AI log.

##### 2. Why We Are Doing It

The cohort rule is that AI use is written down, not hidden. The note also protects you: if an interviewer asks "did you write this", you have a clear, honest answer with the parts you changed by hand.

##### 3. What to Learn First

- The AI footer and the AI log rules come from `../07-AI-In-Design.md`. Use the exact format from that document. Do not write your own version.
- A good AI log has the tool, the date, the prompt, what came back, and what you changed.
- Honest is more useful than impressive here.

##### 4. Where to Find Resources

- `../07-AI-In-Design.md`, the AI footer rule and the AI log rule.
- Your own Y1.2, Y1.3 and Y1.4 files.

##### 5. Step-by-Step Guide

1. Open `../07-AI-In-Design.md`.
2. Find the AI footer rule.
3. Copy the footer template exactly.
4. Fill in the tool name, the date and what you used it for.
5. Add the footer where the rule says it goes.
6. Copy the AI log template into `Y1-7-ai-note.md`.
7. Fill in each entry: tool, date, prompt, what came back.
8. List your three hand fixes from Y1.4.
9. Write two lines on what the AI got wrong.
10. Write one line on what you would ask differently next time.
11. Do a final data check on every file: no real names, no phone numbers, no keys, no participant quotes with names.
12. Commit.

If you get stuck:

- If you cannot find the footer rule, search the document for the word footer.
- If you used more than one tool, write a footer line for each.
- Ask in Discord and paste the footer you wrote. Do not ask whether you need one.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/Y1-7-ai-note.md`
- [ ] The AI footer from `../07-AI-In-Design.md` is in place, in the exact format
- [ ] The AI log has the tool, date, prompt and result for each use
- [ ] Three hand fixes are listed
- [ ] The final data check is done and written down

Commit message: `Y1.7 add the AI note and the AI log`

---

### Group 4 - Lab L-AI6

#### Task - Lab L-AI6, AI-assisted coded prototype (ID `L-AI6`)

##### 1. What We Are Doing

Collect the whole week into one lab record: what you built, with which tool, what you changed, how it tested, and where it lives.

##### 2. Why We Are Doing It

Lab records are what the cohort reviews and what you will re-read in Sprint 6 when you write your portfolio. A live link plus a short honest record is a strong portfolio item. It also proves the lab was done, not claimed.

##### 3. What to Learn First

- Nothing new. This lab is the record of Y1.1 to Y1.7.
- A lab record is short. Eight sections, one page, facts only.

##### 4. Where to Find Resources

- Your own files from this week.
- `../07-AI-In-Design.md`, for the footer.

##### 5. Step-by-Step Guide

1. Create `students/UX{n}/week12b/L-AI6-lab-record.md`.
2. Add a heading with your code and the week.
3. Section 1: the screen you built, and the reason you picked it.
4. Section 2: the AI tool, the date, and the free limit as you understood it.
5. Section 3: the prompt, in a code block.
6. Section 4: the three things you fixed by hand.
7. Section 5: the axe result and the keyboard result.
8. Section 6: the live GitHub Pages link.
9. Section 7: what the page does not do yet.
10. Section 8: the AI footer.
11. Read it once and remove anything you cannot support.
12. Commit.

If you get stuck:

- If a section feels empty, copy the exact sentence from the Y-file it belongs to.
- If the link is not live yet, finish Y1.6 first and come back.
- Ask in Discord for a review of the "what it does not do yet" section. That section is the one interviewers trust.

**How to think about it:** the record is for the next person, who may be you in six months. Write what you would want to read then.

##### 6. What to Commit

- [ ] `students/UX{n}/week12b/L-AI6-lab-record.md`
- [ ] All eight sections are filled
- [ ] The live link is in the record
- [ ] The AI footer is in the record
- [ ] No secrets and no participant data

Commit message: `L-AI6 add the lab record for the coded page`

## 6. What to Commit

End of week checklist:

- [ ] `students/UX{n}/week12b/Y1-1-screen-choice.md`
- [ ] `students/UX{n}/week12b/Y1-2-prompt-and-spec.md`
- [ ] `students/UX{n}/week12b/Y1-3-generation-notes.md`
- [ ] `students/UX{n}/week12b/Y1-4-code-reading.md`
- [ ] `students/UX{n}/week12b/Y1-5-a11y-check.md`
- [ ] `students/UX{n}/week12b/Y1-6-publish.md`
- [ ] `students/UX{n}/week12b/Y1-7-ai-note.md`
- [ ] `students/UX{n}/week12b/L-AI6-lab-record.md`
- [ ] `students/UX{n}/week12b/page/index.html`
- [ ] `students/UX{n}/week12b/page/style.css`
- [ ] `students/UX{n}/week12b/page/script.js`, only if you used one
- [ ] `students/UX{n}/week12b/y1-1-screen.png`, `y1-3-first-result.png`, `y1-4-after-fixes.png`, `y1-5-axe.png`, all under 2 MB, lowercase names with hyphens
- [ ] The page is live on GitHub Pages and the link is in `Y1-6-publish.md`
- [ ] Three hand fixes are written as before and after
- [ ] axe and the keyboard check are recorded, not just claimed
- [ ] The Lighthouse accessibility score was run on the live link and is written down
- [ ] The AI footer and the AI log follow `../07-AI-In-Design.md`
- [ ] No secrets, no keys, no real names, no phone numbers, no participant data anywhere

If you are short on time, cut in this order:

1. The optional screen reader check in Y1.5.
2. The second state and the JavaScript piece. Keep the default state.
3. The Lighthouse score. Keep the axe scan and the keyboard check.

Never cut the axe scan, the keyboard check, the live link, or the AI footer.

When your commits are pushed, open one pull request from your branch with a short title and one line on what is inside. The steps are in `../10-GitHub-For-Designers.md`.

Next: `../Design-Sprint-4/00-READ-FIRST.md`
