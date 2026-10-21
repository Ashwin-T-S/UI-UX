# 12 - HTML and CSS for Designers

**Seven short code corners across 27 weeks. You read and edit code. You do not master programming.**

## 1. What We Are Doing

Seven times in this program you open VS Code and build one small thing: a page, a row of cards, a form, a click, a coded prototype, a set of tokens, a portfolio. Each corner takes 20 to 40 minutes. You keep your code in a small code folder, paste the code into a markdown file, add a screenshot, and commit.

| Code corner | Week | Time | What you build | Files you commit |
|---|---|---|---|---|
| Z0.7 | 0 | 30 min | First HTML page: heading, text, image, link | `Design-Sprint-1/students/UX{n}/week0/code/index.html`, `Design-Sprint-1/students/UX{n}/week0/code-corner-z0-7.md`, `z0-7-first-page.png` |
| Z3.1 | 3 | 35 min | Three cards in a row, box model and flexbox | `Design-Sprint-1/students/UX{n}/week3/code/index.html`, `code-corner-z3-1.md`, `z3-1-flex-row.png`, `z3-1-box-model.png` |
| Z6.1 | 6 | 35 min | The week 6 screener form as real HTML | `Design-Sprint-2/students/UX{n}/week6/code/form.html`, `code-corner-z6-1.md`, `z6-1-form.png` |
| Z10.1 | 10 | 30 min | A button that changes state, a little JavaScript | `Design-Sprint-3/students/UX{n}/week10/code/state.html`, `code-corner-z10-1.md`, `z10-1-state.png` |
| Y1 | 12b | 40 min in the corner, full lab in the week file | An AI-assisted coded prototype, published | the task files for Y1.1 to Y1.7 in `Design-Sprint-3/students/UX{n}/week12b/` |
| Z15.1 | 15 | 30 min | CSS variables as design tokens | `Design-Sprint-4/students/UX{n}/week15/code/index.html`, `code-corner-z15-1.md`, `z15-1-tokens.png` |
| Z22.1 | 22 | 40 min | Your portfolio page live on GitHub Pages | `Design-Sprint-6/students/UX{n}/week22/code-corner-z22-1.md`, `z22-1-portfolio.png` |

That is about 3.5 hours of code in the whole program.

Four labs in `08-Prototyping-And-Responsive.md` use the same skills. The code corners come first, so the labs are easier:

- L-PR1, week 3, responsive behaviour: Z3.1 gives you the box model words.
- L-PR2, week 10, a prototype with logic: Z10.1 gives you the state idea.
- L-PR3, week 13, components that survive stress: you reuse the DevTools skills from Z3.1.
- L-PR4, week 18, choose the fidelity: this one helps you decide when a coded fragment is the cheapest prototype.

## 2. Why We Are Doing It

A working product designer in India sits with engineers every week. You do not write the product. You do need to read the build, see what is cheap and what is expensive, spot a missing state, and fix a small thing yourself so nobody waits for you.

Three real situations:

- An engineer says "the container is flex, the gap is 16". You know what that means and why your design breaks at 360 px.
- A colour token is wrong in the build. You open the file, change one line, and the review is done in five minutes.
- You need a live link for a job. A portfolio on GitHub Pages is proof that you build, not only draw.

AI coding assistants are now part of normal design work. A designer who can generate a small page, read it, and fix two things is far more useful than one who can only describe it.

## 3. What to Learn First

By the end of the program you can:

- open an HTML file in your browser and see your change after a reload
- read the structure of a page and find the part that shows on screen
- change spacing, colour, border and font size in CSS
- put things in a row and a column with flexbox
- build a form where every field has a working label
- write one click handler in JavaScript
- move colours and spacing into CSS variables and match the token names in `system/`
- publish a page on GitHub Pages and open it on your phone
- ask an engineer a useful question in one sentence

**The limit: designers read and edit. You do not master.** You will not learn frameworks, state management, testing, performance, back end or deployment pipelines. When work needs those, you ask an engineer. That is a normal, professional thing to do.

Core ideas to review first:

- **tag, element, attribute**: `<img src="a.png">` is a tag with one attribute.
- **class vs id**: a class is for CSS, an id is for JavaScript and for labels. Classes can repeat, ids cannot.
- **box model**: content, then padding, then border, then margin.
- **flexbox**: direction, gap, and how children line up. This is Auto Layout in code.
- **CSS custom property (variable)**: `--name: value` written once, used with `var(--name)`.
- **DOM**: the live tree of the page inside the browser. JavaScript changes the DOM.
- **event listener**: a piece of code that runs when something happens, like a click.
- **GitHub Pages**: a branch and a folder that GitHub turns into a website.

## 4. Where to Find Resources

**Your week in order.** Open one source per corner, not all of them.

| Corner | Source | What to open on the page | Time |
|---|---|---|---|
| Z0.7 | https://web.dev/learn/html | Start at the top, read the first modules on page structure | 20 min |
| Z0.7 backup | https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started | Read the module list, pick the module on first steps | 15 min |
| Z3.1 | https://web.dev/learn/css | Read the module list, pick the modules on the box model and on layout | 20 min |
| Z3.1 backup | https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics and https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout | Skim the headings, read the parts you need | 15 min |
| Z6.1 | https://web.dev/learn/forms | Read the module list, pick the modules on form structure and labels | 20 min |
| Z6.1 backup | https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content | The sections on forms and inputs | 15 min |
| Z10.1 | https://web.dev/learn/javascript | Read the module list, pick the first modules on adding interactivity | 20 min |
| Z10.1 backup | https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting | The first sections only | 15 min |
| Y1 | https://web.dev/learn/ai | Read the module list, pick the modules on prompting and checking output | 15 min |
| Z15.1 | https://web.dev/learn/css and https://web.dev/learn/design | The modules on custom properties and on design tokens | 15 min |
| Z22.1 | https://docs.github.com/en/pages/quickstart | The whole page, it is short | 15 min |

**Tools you open**

- **VS Code**: https://code.visualstudio.com/ . Install steps for Mac and Windows are in `04-Tools-Setup.md`, in the VS Code section.
- **Git**: https://git-scm.com/ . Same setup doc, Git section.
- **GitHub**: https://github.com/ , and the branch and pull request steps are in `10-GitHub-For-Designers.md`.
- **Your browser and DevTools**: already installed. Mac: Cmd+Option+I. Windows: Ctrl+Shift+I or F12.
- **axe DevTools**: free browser extension, used once in Y1.5.
- **One AI assistant for Y1**: free tier only. Options include Google Stitch, Figma Make, v0, Lovable, Bolt, Claude, ChatGPT, GitHub Copilot free, Cursor free. Check the free limit before use. Pick one, not five.

**Search keywords when you are stuck**

- "css box model padding vs margin"
- "flexbox items not in a row"
- "html label for input id match"
- "css custom properties :root var example"
- "github pages 404 index.html"

## 5. Step-by-Step Guide

### 1. How the code corners work

1. One task, one commit containing all files listed for that task. The commit rules are in `10-GitHub-For-Designers.md`.
2. Work on your branch in your fork, never on `main` of the shared repo.
3. You do not need to install anything to run the code. Your browser runs it.
4. The repo accepts markdown, PNG/JPG under 2 MB, PDF under 10 MB, a view-only Figma link inside a markdown file, and small `.html`, `.css` and `.js` files in a code folder such as `week0/code/`. One task, one commit, with every file listed for that task.
5. Name images in lowercase with hyphens, for example `z0-7-first-page.png`.
6. Do not commit `.fig` files, passwords, tokens, or real personal data.
7. If a corner takes more than 40 minutes, stop. Ask in Discord with a screenshot and what you tried.

**Check it worked:** you know which files you commit for this corner and where your code folder goes in the repo.

### 2. If you get stuck

Four problems cover most of the failures in this guide. Check these before you ask for help.

1. **Broken image.** The image file must sit in the same folder as the page.
2. Check the exact spelling in `src`, including the extension.
3. Mac: in Finder, check the real file name.
4. Windows: in File Explorer, open the View tab and turn on "File name extensions". Then check the real file name.
5. **Missing styles.** Check the `<style>` block sits inside `<head>`.
6. Check the selector matches the class name exactly, with a dot, for example `.card`.
7. Check for a missing `}` at the end of a rule.
8. **JavaScript error.** Open the Console in DevTools. Mac: Cmd+Option+J. Windows: Ctrl+Shift+J.
9. Read the first red line only. It names the file and the line number.
10. **Pages 404.** Check the file is named `index.html` exactly.
11. Check Settings, then Pages, points at the main branch and the root folder. Then wait a few minutes.
12. If it is still broken, post in Discord. Add a screenshot, the exact file name, one line on what you tried, and the first red error line.

**Check it worked:** you know the first thing to check for each of the four problems, and what to send in Discord.

### 3. How to read code you did not write

This is the skill that matters most. Use it in Y1 and in every handoff.

1. Do not read from the top. Find the part that draws the thing you see on screen.
2. Open the page in the browser.
3. Right-click the thing you care about, then choose Inspect.
4. DevTools shows the exact line of HTML.
5. Read the class name on that line.
6. Search the CSS for that class name. Mac: Cmd+F. Windows: Ctrl+F.
7. On the first pass, read only property names you already know: `display`, `padding`, `gap`, `color`, `font-size`.
8. Ignore everything else on the first pass. It is noise until you need it.
9. Test one line at a time.
10. Delete one property. Save. Reload. Look at the page.
11. Put the property back. Mac: Cmd+Z. Windows: Ctrl+Z.
12. Optional, from week 12b onward: ask an AI assistant to explain a block line by line. Then check every claim by deleting that line and reloading. Check the free limit before use. Record the use in your AI log and add the required AI footer from doc 07.
13. Never edit code you cannot explain after one pass. Ask for help with that block instead.

**Check it worked:** you can point at something on screen and say which line of CSS makes it look that way.

### 4. Corner Z0.7 - Your first page (week 0, 30 minutes)

**Source:** https://web.dev/learn/html

**What to build:** one page with a big heading, one sentence, one image, one link. Fifteen lines of code, no more.

**Steps**

1. Open VS Code.
2. Create a folder on your Desktop called `week0-code`.
3. Make a new file and save it as `index.html` inside that folder. The spelling matters.
4. Type `!` and press Tab. VS Code fills in the basic page structure.
5. Change the text inside `<title>` to your cohort code, for example `UX3 first page`.
6. Inside `<body>`, add an `<h1>` with your cohort code.
7. Add one `<p>` with one sentence about what you are learning.
8. Find the screenshot you saved for task Z0.5.
9. Copy that screenshot into `week0-code`. Keep the same file name.
10. Add an `<img>` with `src` set to that exact file name, for example `<img src="z0-5-fork.png" alt="My fork on GitHub">`.
11. Add an `<a>` linking to https://github.com/StartwithDot/UI-UX .
12. Save. Mac: Cmd+S. Windows: Ctrl+S.
13. Open the file in your browser. Mac: right-click the file in Finder, then Open With, then your browser. Windows: right-click in File Explorer, then Open with, then your browser.
14. Change one word in the `<h1>`.
15. Save again.
16. Reload the tab. Mac: Cmd+R. Windows: Ctrl+R or F5.

**Check it worked:** you see the heading, the sentence, the image and the link, and your edit appears after a reload. The browser tab shows your title text.

**If you get stuck:** if the image is broken, check the exact file name and the extension against the `src` value. If the page is blank, check that your code sits inside `<body>`. Post a screenshot in Discord with the file name and what you tried.

**What to commit:** `Design-Sprint-1/students/UX{n}/week0/code/index.html`, `Design-Sprint-1/students/UX{n}/week0/code-corner-z0-7.md` with the code in a fenced block, and `z0-7-first-page.png`. Commit message: `Z0.7 code corner: first HTML page`

### 5. Corner Z3.1 - Box model and flexbox (week 3, 35 minutes)

**Source:** https://web.dev/learn/css

**What to build:** your Z0.7 page plus a row of three cards, and one screenshot of the box model in DevTools.

**Steps**

1. Make a new folder called `week3-code`.
2. Copy your `index.html` from `week0-code` into `week3-code`.
3. Find the image file that your `<img src="...">` points to in `week0-code`.
4. Copy that image file into `week3-code`. Keep the same file name, so the `src` still works.
5. Open `index.html` in VS Code.
6. In the `<head>`, add a `<style>` block.
7. In the `<body>`, add `<div class="row">`.
8. Inside that div, add three `<div class="card">`.
9. Give each card a short heading.
10. Add one line of text to each card.
11. In the style block write `.row { display: flex; gap: 16px; }`.
12. Write `.card { padding: 16px; border: 1px solid #cccccc; }`.
13. Save.
14. Reload the page.
15. Open DevTools. Mac: Cmd+Option+I. Windows: Ctrl+Shift+I or F12.
16. Click the small arrow icon at the top left of the DevTools panel.
17. Click one card on the page.
18. Find the box model diagram in the panel, the coloured rectangles.
19. Hover padding, border and margin. Watch the page highlight.
20. Change `gap` to `4px`.
21. Save and reload.
22. Look at the space between the cards. It is smaller now.
23. Change it back to `16px`.

**Check it worked:** three cards sit in one row with equal space between them. DevTools shows padding 16, border 1, margin 0 for a card.

**If you get stuck:** if the cards stack, `display: flex` is missing or spelled wrong. If the image is broken, the image file is not in `week3-code`. If a style does nothing, check the class name in the HTML and in the CSS match.

**How to think about it:** flexbox is Auto Layout in code. `display: flex` creates a flex container. `flex-direction` sets row or column. `gap` is the spacing between items. `padding` is padding. You now understand what an engineer means by "the container is flex".

**What to commit:** `Design-Sprint-1/students/UX{n}/week3/code/index.html`, `Design-Sprint-1/students/UX{n}/week3/code-corner-z3-1.md` with the code, plus `z3-1-flex-row.png` and `z3-1-box-model.png`. Commit message: `Z3.1 code corner: box model and flexbox`

### 6. Corner Z6.1 - A form (week 6, 35 minutes)

**Source:** https://web.dev/learn/forms

**What to build:** the week 6 screener form in real HTML. One text field, one radio group with two options, one select, one checkbox, one button. Every field has a label.

**Steps**

1. Make a new folder called `week6-code` and a new file `form.html` inside it.
2. Type `!` and press Tab to get the basic structure.
3. Add a `<form>` inside `<body>`.
4. Add a label and a text field: `<label for="role">Your role</label>` then `<input id="role" name="role" type="text">`. The `for` value and the `id` value must be identical.
5. Add a radio group: two inputs with the same `name`, different `id`, and one label for each.
6. Add a select with three options and one label for it, using the same `for` and `id` match.
7. Add a checkbox with its own label.
8. Add `<button type="submit">Send</button>`.
9. Save.
10. Open the file in your browser.
11. Press Tab through the whole form.
12. Type in each field. It will not send anywhere. That is expected on a local page.

**Check it worked:** Tab moves through the fields in reading order, the focus ring is visible on each one, clicking a label puts the cursor in its field, and arrow keys change the radio choice.

**If you get stuck:** if Tab skips a field, the `for` value and the `id` value do not match. If clicking a label does nothing, check the same match. Read the labels module in https://web.dev/learn/forms again.

**Note:** this is a practice form. Do not put real participant data in it and do not connect it to a live collection.

**What to commit:** `Design-Sprint-2/students/UX{n}/week6/code/form.html`, `Design-Sprint-2/students/UX{n}/week6/code-corner-z6-1.md` with the code, plus `z6-1-form.png`. Commit message: `Z6.1 code corner: form in HTML`

### 7. Corner Z10.1 - A little JavaScript (week 10, 30 minutes)

**Source:** https://web.dev/learn/javascript

**What to build:** one button that changes the state of one box, from active to paused and back. One click adds a class, the next click removes it. This is the same idea as the states in L-PR2.

**Steps**

1. Make a new folder `week10-code` and a new file `state.html`.
2. Add the basic structure with `!` and Tab.
3. In the body add `<button id="pauseButton">Pause</button>`.
4. After it add `<div id="status" class="status">Active</div>`.
5. In a style block add `.status { padding: 16px; background: #e6f2e6; }` and `.status.is-paused { background: #f2e6e6; }`.
6. Just before `</body>`, add `<script>` and `</script>`.
7. Between them write `const button = document.getElementById('pauseButton');`
8. On the next line write `const status = document.getElementById('status');`
9. On the next line write `button.addEventListener('click', () => { status.classList.toggle('is-paused'); });`
10. Save.
11. Reload the page.
12. Click the button twice.
13. Test with the keyboard: Tab to the button, then press Enter or Space.

**Check it worked:** the first click changes the box colour, the second click changes it back, and the keyboard does the same as the mouse.

**If you get stuck:** if nothing happens, open the Console. Mac: Cmd+Option+J. Windows: Ctrl+Shift+J. Read the first red line. If it says the element is null, the `id` in the HTML and in the script do not match.

**How to think about it:** the variables reference the button and the box. The presence of `is-paused` stores the state. CSS shows it through colour. If the screen and the state disagree, that is a bug. This is true in Figma and in code.

**What to commit:** `Design-Sprint-3/students/UX{n}/week10/code/state.html`, `Design-Sprint-3/students/UX{n}/week10/code-corner-z10-1.md` with the code, plus `z10-1-state.png`. Commit message: `Z10.1 code corner: a click changes state`

### 8. Corner Y1 - AI-assisted coded prototype (week 12b, 40 minutes in the corner)

This corner is part of the week 12b lab, tasks Y1.1 to Y1.7. The full lab has its own time. Here you learn the loop: prompt, read, fix, check, publish.

**Source:** https://web.dev/learn/ai , plus https://web.dev/learn/css and https://web.dev/learn/javascript when you need to read the output.

**Tool:** one AI coding assistant on a free tier. Check the free limit before use. Write every tool you use in your AI log.

**Steps**

1. Y1.1: pick one screen from your showpiece. One screen, not a flow.
2. Y1.2: write the spec first, in plain words, without the tool. Width, sections, order, real text, states, colours, and what happens on a click.
3. Write the prompt from that spec. Ask for one `index.html` file with CSS inside it. Say "plain HTML and CSS, no framework, no build tools".
4. Paste the answer into a new `index.html` in `page/`.
5. Open it in the browser.
6. Read the code with the method in section 3 of this guide.
7. Find the part that draws the thing you care about.
8. Fix two things by hand. Keep them small: spacing, colour, font size, a missing label.
9. Run axe DevTools on the page.
10. Fix or write down every serious issue (Y1.5).
11. Tab through the page. Every control must be reachable.
12. Resize the window to about 360 px wide.
13. Resize it wide again. Note what breaks.
14. Y1.6: publish it with GitHub Pages, following https://docs.github.com/en/pages/quickstart .
15. Y1.7: write the AI note and the AI log, using the rules in doc 07 (check the file name in the repo).

**Check it worked:** the page opens locally, it looks close to your screen at 360 px and at 1440 px, axe shows no critical issues, the keyboard reaches every control, and the live link opens on your phone.

**If you get stuck:** if the page is blank, open the Console and read the first red line. If it looks wrong at 360 px, search "css media query 360px example". If Pages shows 404, check the file name is `index.html` and wait a few minutes. Post the live link and a screenshot in Discord.

**What to commit:** one commit per task, containing every file listed for that task. All paths start with `Design-Sprint-3/students/UX{n}/week12b/`.

| Task | Files | Commit message |
|---|---|---|
| Y1.1 | `y1-1-screen.md` with a view-only Figma or Penpot link, and `y1-1-screen.png` | `Y1.1 code corner: pick one screen` |
| Y1.2 | `y1-2-spec-and-prompt.md` with the spec and the prompt | `Y1.2 code corner: spec and prompt` |
| Y1.3 | `page/index.html`, `y1-3-generate.md` with the tool name, and `y1-3-generated.png` | `Y1.3 code corner: generate the page` |
| Y1.4 | `page/index.html` updated, `y1-4-fixes.md` with the two fixes, `y1-4-fix-1.png`, `y1-4-fix-2.png` | `Y1.4 code corner: read and fix the code` |
| Y1.5 | `y1-5-accessibility.md` with the axe results and the keyboard notes, `y1-5-axe.png` | `Y1.5 code corner: axe and keyboard check` |
| Y1.6 | `y1-6-publish.md` with the live link, `y1-6-live.png` | `Y1.6 code corner: publish on GitHub Pages` |
| Y1.7 | `y1-7-ai-note.md` with the AI note and the AI log, and the AI footer from doc 07 | `Y1.7 code corner: AI note and log` |

Do not skip a task. Y1.6 and Y1.7 are part of the lab, not extras.

### 9. Corner Z15.1 - CSS variables as tokens (week 15, 30 minutes)

**Source:** https://web.dev/learn/css and https://web.dev/learn/design

**What to build:** your week 3 page again, but every colour and space comes from a variable in `:root`.

**Steps**

1. Make a new folder `week15-code`.
2. Copy the `index.html` from `week3-code` into it.
3. Copy the image the `src` points to. Keep the same file name.
4. At the top of the style block add: `:root { --color-text: #1a1a1a; --color-surface: #ffffff; --color-border: #cccccc; --space-2: 8px; --space-4: 16px; --radius: 8px; }`
5. Replace the hardcoded border colour in the card with `var(--color-border)`.
6. Replace `padding: 16px` with `padding: var(--space-4);`.
7. In `.row`, replace `gap: 16px` with `gap: var(--space-4);`.
8. Save and reload. Nothing should look different.
9. Change `--space-4` to `24px`.
10. Save and reload. Every card grows.
11. Change it back to `16px`.
12. Add `border-radius: var(--radius);` to the card.
13. Search the file for `#` and for `px` inside `.row` and `.card`. Any colour or spacing value that is still hardcoded gets a variable, or you write one line saying why it stays.
14. Compare your names with the token names used in `system/`. If a name is different, write one line about the conversion.

**Check it worked:** changing one line in `:root` changes every card at once, and there is no hardcoded colour or spacing left inside `.row` and `.card`.

**If you get stuck:** if a value does not change, the property still has a hardcoded value. If nothing changes at all, the `:root` block is outside the `<style>` block or a `}` is missing.

**How to think about it:** a token is a name for a decision. Figma variables, or Penpot tokens, CSS variables and the tokens in `system/` are three copies of the same list. Keep the meanings and the values aligned across them. If a name has to change between tools, write down the conversion so the handoff stays clear.

**What to commit:** `Design-Sprint-4/students/UX{n}/week15/code/index.html`, `Design-Sprint-4/students/UX{n}/week15/code-corner-z15-1.md` with the code, plus `z15-1-tokens.png`. Commit message: `Z15.1 code corner: CSS variables as tokens`

### 10. Corner Z22.1 - Portfolio page on GitHub Pages (week 22, 40 minutes)

**Source:** https://docs.github.com/en/pages/quickstart

**What to build:** a one-page portfolio. One heading, one short line about you, three project cards linking to your case studies, one contact link. A public profile link or email is enough. No phone number, no home address.

**Steps**

1. Open the quickstart and follow it. Create a repository named `yourusername.github.io`, all lowercase.
2. Add an `index.html` file at the root of that repository.
3. Build the page with your Z15.1 layout: `:root` tokens and `.row { display: flex; flex-wrap: wrap; gap: var(--space-4); }`.
4. Add three cards. Each card has a project name, one line about the outcome, and a link.
5. Commit the file with Git. Or use the web upload: Add file, then Upload files.
6. Go to Settings, then Pages, choose the main branch and the root folder, then save. If the labels differ, follow the quickstart page.
7. Wait a few minutes, then open `https://yourusername.github.io`.
8. Open the same link on your phone.
9. In DevTools, switch to device mode with the phone icon and check the page at 360 px wide.
10. Fix two things.
11. Commit again.
12. Check the live link a few minutes later.

**Check it worked:** the live link opens on your phone, every card link works, and no text runs off the screen at 360 px.

**If you get stuck:** a 404 usually means the file is not named `index.html`, or Pages is not set to the main branch and the root folder. Wait five minutes and reload. Check your repository is public. Follow the quickstart page again before you ask in Discord.

**What to commit:** in the cohort repo, `Design-Sprint-6/students/UX{n}/week22/code-corner-z22-1.md` with the live link and `z22-1-portfolio.png`. Keep personal contact details out of the shared repo apart from the public link you chose. Commit message: `Z22.1 code corner: portfolio page live`

### 11. The limit: you read and edit, not master

This is on purpose. You are not training to be an engineer.

**What you will do:** open a file, find the right line, change a value, check it in the browser, and say what happened in plain words.

**What you will not do:** build an app, pick a framework, design a database, write tests, fix performance, or deploy a product. Engineers do that. Asking them is correct, not a failure.

**When to stop and ask:** the fix needs more than about ten lines of new code, or you cannot explain a block after two reads, or the page breaks in a way you cannot describe.

**Check it worked:** you can say what you will not do, and who you ask instead.

### 12. How to talk to engineers: 10 phrases

Engineers are not a different species. They are busy and they like clear requests. Use these.

1. "Can you show me how it works in the build? I want to see the current behaviour."
2. "What do you need from me: a spec, a screen, or a link?"
3. "Which part is expensive to build? I will redesign that part."
4. "What is the smallest change that gets most of it?"
5. "Is this a design decision or a data limit? I want to ask the right person."
6. "Here are all the states: empty, loading, error, long text, and 200% zoom."
7. "Can we spend at most one day on this and look at it together?"
8. "I am not sure this is possible. Tell me what is, and I will pick."
9. "I checked this in the browser at 360 and 1440 px. Here is the screenshot."
10. "Can I sit with you for 20 minutes while you build it? I learn faster that way."

**Words that cost you:** "just", "quick", "simple", "it should be easy". They all sound like you think the work is small. Say what you need instead.

**Check it worked:** you used one of these phrases in Discord or in a comment this week, and you wrote down the answer.

## 6. What to Commit

End of program checklist. One task, one commit containing all files listed for that task. Each commit message starts with the task ID.

- [ ] `Design-Sprint-1/students/UX{n}/week0/code/index.html`, `Design-Sprint-1/students/UX{n}/week0/code-corner-z0-7.md`, `z0-7-first-page.png`
- [ ] `Design-Sprint-1/students/UX{n}/week3/code/index.html`, `Design-Sprint-1/students/UX{n}/week3/code-corner-z3-1.md`, `z3-1-flex-row.png`, `z3-1-box-model.png`
- [ ] `Design-Sprint-2/students/UX{n}/week6/code/form.html`, `Design-Sprint-2/students/UX{n}/week6/code-corner-z6-1.md`, `z6-1-form.png`
- [ ] `Design-Sprint-3/students/UX{n}/week10/code/state.html`, `Design-Sprint-3/students/UX{n}/week10/code-corner-z10-1.md`, `z10-1-state.png`
- [ ] `Design-Sprint-3/students/UX{n}/week12b/` files for Y1.1 to Y1.7, one commit per task, including `page/index.html`, the live link and the AI log
- [ ] `Design-Sprint-4/students/UX{n}/week15/code/index.html`, `Design-Sprint-4/students/UX{n}/week15/code-corner-z15-1.md`, `z15-1-tokens.png`
- [ ] `Design-Sprint-6/students/UX{n}/week22/code-corner-z22-1.md`, the live portfolio link, and `z22-1-portfolio.png`
- [ ] Every image is PNG or JPG, under 2 MB, lowercase with hyphens, no spaces
- [ ] Code sits in a code folder (`week0/code/`, `week12b/page/`) and also in a fenced block inside the markdown file
- [ ] No `.fig` files, no passwords, no tokens, no real personal data
- [ ] Every commit message starts with the task ID, for example `Z3.1 code corner: box model and flexbox`
- [ ] Open a pull request for the current task or week, following `10-GitHub-For-Designers.md`. Complete Z0.6 before Z0.7

Next: back to `00-START-HERE.md`, or on to `04-Tools-Setup.md` if VS Code and Git are not installed yet.
