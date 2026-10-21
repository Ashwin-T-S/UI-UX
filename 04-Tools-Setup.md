# 04 - Tools Setup

## 1. What We Are Doing

You will prepare your computer for the DOTSET Product Design cohort.
You will use free tools to design, write notes, check accessibility and share work.

This guide covers Mac and Windows.
Most browser tools work the same way on both.

Start in Week 0.
Finish the core setup before Week 1.
Allow several short sessions for accounts, installation and practice.
The four Figma lessons take about one hour on their own.

This guide supports these Week 0 tasks:

| Task | Setup work |
|---|---|
| `Z0.1` | Create accounts and join Discord |
| `Z0.2` | Set up Figma and Penpot |
| `Z0.3` | Install VS Code and Git |
| `Z0.4` | Fork, clone and create a branch |
| `Z0.5` | Make a first commit with an image and a view-only Figma link |
| `Z0.6` | Open a first pull request |
| `Z0.7` | Make a first HTML page |
| `Z0.8` | Check accessibility tools |

You do not need every tool in this guide today.
Sections marked optional or later can wait.

**The rule:** After Sprint 1, add at most two new working tools per sprint.
Learn the work before adding another tool.
Read `09-Modern-Practice-Map.md` to understand the tool choices.

## 2. Why We Are Doing It

A product designer working in India often shares work with researchers, developers and clients.
Your files must be easy to find, open and review.

Figma holds your design work.
Git records changes to your saved files.
GitHub lets the cohort review those changes.
Accessibility tools help you check whether people can use your work.

Your portfolio needs clear decisions and evidence.
A large collection of tools does not replace these.

This is new for most people.
Go slowly.
Check each part before you continue.

## 3. What to Learn First

| Before you start | What you need |
|---|---|
| Computer | A Mac or Windows computer |
| Internet | Access to the cohort repository and tool websites |
| Student code | Your assigned code, `UX1` to `UX10` |
| Cohort invitations | Discord and Figma invitations from the admin |
| Email | An email account you can access |
| Repository | https://github.com/StartwithDot/UI-UX |
| Storage | Space for your cloned repository and local design backups |

Replace `UX{n}` with your assigned code.
For example, `UX{n}` becomes `UX3`.

Learn these words first:

- A browser tool runs inside a website.
- A plugin adds features inside another tool.
- A terminal accepts commands you type.
- A repository is a project whose changes Git tracks.
- A fork is your GitHub copy of another repository.
- A clone is a copy of a repository on your computer.
- A branch keeps a set of changes separate.
- A commit records a saved change in Git.
- A pull request asks someone to review your changes.
- Markdown is plain text with simple formatting.
- A design token is a named design value, such as a colour or spacing value.
- A screen reader reads interface content aloud.
- A free tier is a free plan with limits.

By the end, you can:

- Open the cohort tools.
- Find your own project folder.
- Create a design file without using unnecessary file slots.
- Share a view-only design link.
- Save notes and images in Git.
- Open a pull request.
- Run a basic accessibility check.
- Find help without sharing private information.

Keep these rules from the start:

- Use your student code in cohort work.
- Use `P1`, `P2` and similar codes for participants.
- Do not include real names, faces, phone numbers or IDs in submitted work.
- Never commit passwords, tokens or real personal data.
- Do not enter payment details to complete a cohort task.
- Check a tool's free limit before you begin a task.

## 4. Where to Find Resources

| Resource | Use it for |
|---|---|
| [Cohort repository](https://github.com/StartwithDot/UI-UX) | Fork the project and find cohort files |
| [10-GitHub-For-Designers.md](10-GitHub-For-Designers.md) | Branches, commits and pull requests |
| [07-AI-In-Design.md](07-AI-In-Design.md) | AI logs, AI footers and lab rules |
| [09-Modern-Practice-Map.md](09-Modern-Practice-Map.md) | Why the cohort uses these tools |
| [05-The-Six-Sprints.md](05-The-Six-Sprints.md) | Sprint overview |
| [Design-Sprint-1/00-READ-FIRST.md](Design-Sprint-1/00-READ-FIRST.md) | Sprint 1 starting point |
| [Figma pricing](https://www.figma.com/pricing/) | Current free plan limits |
| [Figma plans and features](https://help.figma.com/hc/en-us/articles/360040328273-Figma-plans-and-features) | Feature access |
| [Figma Education](https://www.figma.com/education/) | Eligibility and verification |
| [Penpot](https://penpot.app/) | Backup design tool |
| [Penpot pricing](https://penpot.app/pricing) | Current free plan limits |
| [VS Code](https://code.visualstudio.com/) | Editor download |
| [Git](https://git-scm.com/) | Installation instructions |
| [GitHub](https://github.com/) | Account and repository access |
| [GitHub Desktop](https://desktop.github.com/) | Optional visual Git application |
| [NVDA](https://www.nvaccess.org/) | Windows screen reader |
| [web.dev Learn](https://web.dev/learn) | Web development lessons |
| [MDN Learn web development](https://developer.mozilla.org/en-US/docs/Learn_web_development) | Beginner explanations and examples |
| [WCAG quick reference](https://www.w3.org/WAI/WCAG22/quickref/) | Accessibility requirements |
| [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart) | Publish a small website later |

Complete these Figma Learn lessons before Week 1:

| Order | Lesson | Approximate time |
|---|---|---|
| 1 | Auto layout | 20 min |
| 2 | Components and instances | 15 min |
| 3 | Variants | 10 min |
| 4 | Styles and variables | 15 min |

Search Figma Learn for these lesson names.
If a name has changed, check the current lesson before use.

If Git is new to you, read **Pro Git chapters 1-3**, free at git-scm.com/book.
Read a little at a time.
Start with `clone`, `branch`, `commit` and `push`.
Use the cohort GitHub guide for your actual submission steps.

Search keywords when stuck:

- `Figma Starter file page limits`
- `Penpot import export`
- `VS Code markdown preview`
- `Git fork clone branch`
- `axe DevTools accessibility scan`
- `VoiceOver NVDA headings navigation`

> **Where to ask for help**
>
> Read the matching section below first.
> Then ask in Discord.
> Include your operating system, the step, the error text and what you tried.
> Add a screenshot only after hiding private information.

## 5. Step-by-Step Guide

Do one task, save its evidence and make one commit.
Follow [10-GitHub-For-Designers.md](10-GitHub-For-Designers.md).

For browser tools, the steps apply to both Mac and Windows.
Install only the core tools now.
Return for later tools when a week asks for them.

### 5.1 Accounts and privacy

Use an email account you can keep using throughout the cohort.
Your login email stays private.
Your public work uses your student code.

1. Confirm your student code with the admin.
2. Check that you can open your email.
3. Create the accounts listed in the sections below.
4. Use a different password for each service.
5. Enable a second sign-in step where available.
6. Check each account's public profile.
7. Remove personal details from public cohort evidence.

**Mac and Windows:** Use your browser for account creation.

**Check it worked:** You can sign in, and your public cohort work identifies you by student code.

**If you get stuck:** Check your email's spam folder, retry the official sign-in page, or ask the admin about the invitation.

### 5.2 Discord

Discord is the cohort's place for questions and discussion.
There is no live teacher.
Clear questions help other learners respond.

1. Ask the admin for the cohort invitation.
2. Open the invitation in your browser.
3. Create a free account if needed.
4. Join the cohort server.
5. Use your student code as your server display name.
6. Read the server rules.
7. Find the channel for your current sprint.
8. Post a short introduction using your student code.

The browser version is enough.
For an optional desktop installation, use Discord's official download page.
On Mac, choose its Mac download.
On Windows, choose its Windows download.
The download address is not supplied here, so check before use.

Do not post passwords, private account screens or participant data.

**Check it worked:** You can read the cohort channels and find where to ask a setup question.

**If you get stuck:** Reopen the invitation or ask the admin to check your access.

### 5.3 Figma

Figma is the main design tool.
Use the free Starter plan.

1. Open figma.com.
2. Create an account with the email you gave the admin.
3. Accept the cohort team invitation.
4. Check that you are using the free plan.
5. Check the current file and page limits.
6. Ask the admin how the cohort's file slots are allocated to you.
7. Check that one file slot is free for `SPRINT-1 UX{n}`.
8. Create one working file named `SPRINT-1 UX{n}`.
9. Replace `UX{n}` with your student code.
10. Create a page for Week 0 if the plan allows it.
11. Complete the four Figma Learn lessons in section 4.
12. Create a small practice frame.
13. Open the file's sharing controls.
14. Set the shared link to view-only access.
15. Test the link in a signed-out browser window.

The browser version is enough to start.
The desktop app is optional.
Performance depends on your computer and file size.

For the optional app:

- **Mac:** Open Figma's official download area, choose the Mac version and follow its installation instructions.
- **Windows:** Open the same area, choose the Windows version and follow its installation instructions.

Starter limits supplied for this cohort are one team, one folder, three files and 30-day version history.
Libraries and Dev Mode are not included.
Figma AI has separate credits.
Check the [current plan information](https://www.figma.com/pricing/) before use.

A team invitation does not guarantee a separate three-file allowance for every learner.
Ask the admin how the cohort's file slots are allocated before creating files.
If no slot is free, stop.
Do not delete shared work or another learner's file.
Use Penpot in section 5.5 until the admin frees a slot.

**Check it worked:** Your file has the correct name, and someone with the permitted view-only link can open it.

**If you get stuck:** Check the selected team, check your invitation email, or ask the admin about file slots. If no slot is free, move to Penpot in section 5.5.

### 5.4 Figma file hygiene and Education access

File hygiene means keeping files named, organised and easy to recover.

**Use one Figma file per sprint, named `SPRINT-N UX{n}`.**
Use one page per week where the free plan permits it.
Keep one spare file slot where your workspace allowance permits it.

This does not mean keeping six active sprint files in a three-file workspace.
Plan your archive before starting the next sprint.

| File or place | Who edits | What belongs there |
|---|---|---|
| `SPRINT-N UX{n}` | You | Your sprint screens, components and practice |
| One spare file | You, where permitted | Temporary work that you later remove or archive |
| One shared team library file | Admin-approved contributors only | Shared system components, only when the plan allows libraries |
| `system/` | Approved contributors | Shared tokens and system documentation |
| `delivery/` | Team leader only | Reviewed client-facing output |

The old names `SPRINT-N Practice UX{n}`, `SPRINT-N System` and `SPRINT-N Delivery` described the previous three-file-per-sprint setup.
Do not create those three files.
That setup uses too many Starter file slots.

1. Name the current file `SPRINT-N UX{n}`.
2. Replace `N` with the sprint number.
3. Keep weekly work on clearly named pages where allowed.
4. Use clearly named sections within a page if page limits block you.
5. Save a view-only link in your weekly Markdown file.
6. Export the final screen images required by the task.
7. Save a local design backup before removing an old file.
8. Check that the backup opens before you rely on it.
9. Ask the admin about archiving before the next sprint.

**Save a local `.fig` copy**

1. Open your sprint file.
2. Open the Figma main menu.
3. Choose the option that saves a local copy (the label is something like **Save local copy**; check the current label before use).
4. Save the copy with a clear name, for example `SPRINT-1-UX3-backup.fig`.
5. Keep the copy on your computer only.

**Check that the copy opens**

1. Check how many file slots are free before you import. An import creates a new file.
2. Wait for a free slot if all slots are used.
3. Open the Figma file browser.
4. Choose the import option (check the current label before use).
5. Select your `.fig` copy.
6. Open the imported file.
7. Check that your pages and frames are there.
8. Delete the imported test file to free the slot.
9. Keep the local `.fig` copy outside Git.

A local `.fig` backup stays on your computer.
Never commit it to Git.
A backup is not a reason to delete shared work without agreement.

Do not assume that Figma exports open fully in Penpot.
Test a small transfer first.
Keep exported images, tokens and notes so you can rebuild essential work.

Figma branching is not a Starter requirement.
Use branching for system contributions only when the admin confirms access.
Otherwise, submit a view-only link and token changes for review.

The [Education plan](https://www.figma.com/education/) may provide free Professional access to eligible students in a structured class.
Ask the admin.
Do not assume that cohort membership proves eligibility.

**Mac and Windows:** File organisation and plan checks use the same browser workflow.

**Check it worked:** You have one current sprint file, a clear backup plan and no dependency on paid libraries or branching.

**If you get stuck:** Check both file and page limits, then use Penpot or ask the admin about an approved workspace.

### 5.5 Penpot

Penpot is the backup design tool.
Use it when Figma's limits block your work.

1. Open https://penpot.app/.
2. Check https://penpot.app/pricing.
3. Create a free account.
4. Create a test file.
5. Name it `SPRINT-1 UX{n}`.
6. Add a frame.
7. Add a text label.
8. Export a test image.
9. Test the available view-only sharing option.
10. Record the tool choice in your setup notes.

Penpot is open source and runs in the browser.
Its free plan is described as having no file limit in the cohort pack.
Check before use.
Check storage, collaboration and export conditions too.

You do not need to install or host a Penpot server.

**Mac and Windows:** Use Penpot in your browser.

**Check it worked:** You can edit a test file, export an image and share a view-only link.

**If you get stuck:** Try a current browser, check Penpot's help, or share the error in Discord.

### 5.6 FigJam

FigJam is for flow diagrams, grouping research notes and working together.
Grouping related research notes is called affinity mapping.

Use it sparingly.
Check its current file limits and how your workspace counts FigJam files before creating a board.

1. Open FigJam from your Figma account.
2. Check the free allowance.
3. Use an existing approved board where possible.
4. Create a small flow only when a task needs it.
5. Save final decisions in Markdown.
6. Save final flows as Mermaid in Markdown where the task asks for them.

If limits block you, use Mermaid or an approved Penpot file.

**Mac and Windows:** Use the browser version.

**Check it worked:** You can make a simple flow without using an unplanned file slot.

**If you get stuck:** Ask which shared board is approved or use mermaid.live.

### 5.7 VS Code

VS Code is the main editor for Markdown and small code files.

1. Open https://code.visualstudio.com/.
2. Choose the download for your operating system.
3. Follow the matching installation instructions.
4. Open VS Code.
5. **Mac:** Open the **Code** menu and choose **About Visual Studio Code**.
6. **Windows:** Open the **Help** menu and choose **About**.
7. Read the version number and write it down for `setup.md`.

Check the exact label if your version shows a different menu name.

**Mac:** Open the downloaded package and follow the instructions to place the app in Applications.

**Windows:** Run the downloaded installer and follow its instructions.

After cloning the repository in section 5.10:

1. Choose **File > Open Folder**.
2. Open the cloned `UI-UX` folder.
3. Find `Design-Sprint-1/students/UX{n}/week0/`.
4. Create the folder if it is missing.
5. Create `setup.md` inside it.
6. Write your student code.
7. Write your operating system.
8. Write the VS Code version from the About dialog.
9. Save the file.
10. Open Markdown preview.
11. Open the integrated terminal.

Use `Cmd + Shift + V` for Markdown preview on Mac.
Use `Ctrl + Shift + V` on Windows.

Mermaid preview may need an extension.
Check an extension's publisher and permissions before installing it.
You can also preview diagrams at mermaid.live.

**Check it worked:** The repository appears in the file panel, and `setup.md` opens in Markdown preview.

**If you get stuck:** Reopen the cloned folder and check where the file was saved.

### 5.8 GitHub

GitHub hosts your repository and pull requests.
Do this section before you configure Git in section 5.9.

1. Open https://github.com/.
2. Create a free account if needed.
3. Check your public profile for personal information.
4. Open the account's email settings.
5. Enable the available email privacy settings.
6. Copy the private commit email for section 5.9.
7. Enable a second sign-in step.
8. Store recovery information privately.

Never put recovery codes, passwords or access tokens in the repository.

**Mac and Windows:** Account setup happens in the browser.

**Check it worked:** You can sign in, and you have copied your private commit email for section 5.9.

**If you get stuck:** Use GitHub's account recovery guidance or ask in Discord without sharing sign-in details.

### 5.9 Git

Git records changes on your computer.
GitHub is a separate service.
Do section 5.8 first. You need the private commit email from your GitHub account here.

1. Open https://git-scm.com/.
2. Follow the instructions for your operating system.

**Mac:** Open Terminal and run `git --version` first.
If Git is missing, follow the Mac instructions on the Git website.
Complete any required system installation before continuing.

**Windows:** Install Git for Windows from the Git website.
Open Git Bash after installation.
Use Git Bash for the commands in this guide.

1. Check Git:

   ```bash
   git --version
   ```

2. Set your public commit name:

   ```bash
   git config --global user.name "UX3"
   ```

3. Set your GitHub private commit email:

   ```bash
   git config --global user.email "PASTE_YOUR_GITHUB_NOREPLY_EMAIL"
   ```

4. Check the name:

   ```bash
   git config --global --get user.name
   ```

5. Check the email:

   ```bash
   git config --global --get user.email
   ```

Replace `UX3` with your own code.
Copy your exact private commit email from GitHub's email settings in section 5.8.
Do not invent it.

The old examples used `"Your Name"` and `"you@example.com"`.
Use your student code and private commit email instead.

**Check it worked:** Git prints a version, your student code and the intended private email.

**If you get stuck:** Restart the terminal, check the operating-system installation instructions, or post the exact error in Discord.

### 5.10 GitHub fork, clone, branch and pull request

Fork the program repository once.
Use the same fork across sprints.

1. Open https://github.com/StartwithDot/UI-UX.
2. Create a fork under your account.
3. Copy your fork's HTTPS clone address.
4. **Mac:** Press `Cmd + Space`, type `Terminal` and press Enter.
5. **Mac:** Type `cd ~/Documents` and press Enter. Use your chosen parent folder instead of `Documents`.
6. **Mac:** Type `pwd` and press Enter. Check that the printed path is your parent folder.
7. **Windows:** Open the Start menu, type `Git Bash` and press Enter.
8. **Windows:** Type `cd ~/Documents` and press Enter. Use your chosen parent folder instead of `Documents`.
9. **Windows:** Type `pwd` and press Enter. Check that the printed path is your parent folder.
10. Clone your fork:

   ```bash
   git clone https://github.com/{your-username}/UI-UX.git
   ```

11. Enter the repository:

   ```bash
   cd UI-UX
   ```

12. Add the original repository:

   ```bash
   git remote add upstream https://github.com/StartwithDot/UI-UX.git
   ```

13. Check the addresses:

   ```bash
   git remote -v
   ```

14. Create your Week 0 branch:

   ```bash
   git switch -c UX3-week0
   ```

Replace `{your-username}` before cloning.
Replace `UX3` before creating the branch.

`origin` should point to your fork.
`upstream` should point to the original cohort repository.

Save your work in:

```text
Design-Sprint-N/students/UX{n}/weekX/
```

For Week 0, use:

```text
Design-Sprint-1/students/UX{n}/week0/
```

Follow [10-GitHub-For-Designers.md](10-GitHub-For-Designers.md) for staging, committing, pushing and opening a pull request.
Use one commit per task.
Read a diff, the list of changes, before committing.

**Check it worked:** Both remotes are correct, your student branch is active and your pull request shows only your intended files.

**If you get stuck:** Read the GitHub guide, check `git status`, or ask in Discord. Do not force-push to fix an error you do not understand.

### 5.11 GitHub Desktop, optional

GitHub Desktop gives Git a visual interface.
It is optional.

1. Open https://desktop.github.com/.
2. Download the version for your operating system.
3. Follow the installation instructions.
4. Sign in to GitHub.
5. Open your existing clone.
6. Check the current branch.
7. Review a changed file.

**Mac:** Install the Mac application using the download instructions.

**Windows:** Run the Windows installer.

Do not clone a second copy by accident.
The VS Code folder and GitHub Desktop repository should point to the same local project.

**Check it worked:** You can see the same branch and changed files as in VS Code.

**If you get stuck:** Check the repository's local folder before making changes.

### 5.12 GitHub web upload fallback

Use browser upload if a local Git problem blocks a submission.
Continue fixing Git later.

1. Open your fork in the browser.
2. Select your student branch.
3. Open your own week folder.
4. Use GitHub's file upload option.
5. Review the uploaded files.
6. Commit with the task ID.
7. Open or update the pull request.

Follow the GitHub guide for the exact workflow.
Do not upload the whole project folder or a ZIP of the repository.

**Mac and Windows:** Use the same browser workflow.

**Check it worked:** Your file appears in the correct week folder and pull request.

**If you get stuck:** Check the selected repository, branch and folder.

### 5.13 Node.js, optional

Node.js runs JavaScript tools outside the browser.
You do not need it for a plain HTML and CSS page.

Install it only when a later task or approved AI prototype needs it.

1. Find the official Node.js download page through the tool's documentation.
2. Check the address before use.
3. Choose the recommended long-term support release.
4. Follow the installer for your operating system.
5. Restart the VS Code terminal.
6. Check Node:

   ```bash
   node --version
   ```

7. Check npm:

   ```bash
   npm --version
   ```

npm installs JavaScript packages.

**Mac:** Use the official Mac installation instructions.

**Windows:** Use the official Windows installation instructions.

Do not copy an installation command from an unfamiliar page.
Do not commit `node_modules/`, secret files or downloaded dependencies.

**Check it worked:** Both commands print versions.

**If you get stuck:** Reopen the terminal and read the official installation help.

### 5.14 Stark

Stark is a Figma plugin for accessibility checks.
Start with its available free checks.

1. Find Stark in Figma's plugin area.
2. Check the publisher.
3. Check the free features.
4. Open it in your practice file.
5. Check a text and background colour pair.
6. Record the result.

Use Stark inside Figma from Week 2.
Do not start a paid trial for a cohort task.

**Mac and Windows:** Run the plugin inside browser or desktop Figma.

**Check it worked:** You can run an available contrast check and explain its result.

**If you get stuck:** Use the WebAIM contrast checker or contrast-ratio.com while checking plugin access.

### 5.15 axe DevTools

axe DevTools checks accessibility on live web pages.
You use it in Week 1.

1. Find the official axe DevTools extension in your browser's extension store.
2. Check the publisher.
3. Check the free features.
4. Install it.
5. Open a familiar public page.
6. Open browser DevTools.
7. Find the axe panel.
8. Run an available free scan.
9. Read one reported issue.

Automated scans find only some accessibility problems.
You still need keyboard and screen reader checks.

**Mac and Windows:** Install the extension for your chosen supported browser.

**Check it worked:** You can run a scan and find the element connected to an issue.

**If you get stuck:** Check extension permissions, reopen DevTools, or search `axe DevTools extension scan`.

### 5.16 WAVE

WAVE is another way to inspect accessibility issues.
Use it when a task asks or when another checker is unavailable.

1. Find the official WAVE tool or browser extension.
2. Check its address and publisher before use.
3. Open a public page.
4. Run a check.
5. Read one error and one warning.

Do not submit private or signed-in pages to an external checking service.

**Mac and Windows:** Use the web tool or a supported browser extension.

**Check it worked:** You can identify an issue and explain what needs a manual check.

**If you get stuck:** Read the tool's explanation for the selected marker.

### 5.17 VoiceOver

VoiceOver is built into macOS and iPhone.

1. Open a familiar website on your Mac.
2. Press `Cmd + F5` to turn VoiceOver on.
3. Follow the introductory help if it appears.
4. Press `VO + Cmd + H` to move to the next heading. `VO` means the Control and Option keys together.
5. Press `VO + Cmd + H` again to move to the next heading.
6. Press `VO + Cmd + J` to move to the next form control.
7. Press `VO + Right Arrow` to move to the next item on the page.
8. Listen to what a button announces.
9. Press `Cmd + F5` to turn VoiceOver off.

Some keyboards may also require the `Fn` key.
Check macOS accessibility settings if the shortcut does not work.

**Mac:** Use VoiceOver.

**Windows:** Use NVDA in section 5.18.

An iPhone can provide an additional mobile VoiceOver check.

**Check it worked:** You can turn the screen reader on and off and describe one thing it announced.

**If you get stuck:** Open the system accessibility settings and use the built-in VoiceOver help.

### 5.18 NVDA

NVDA is a free Windows screen reader.

1. Open https://www.nvaccess.org/.
2. Download NVDA.
3. Follow its Windows installation instructions.
4. Open a familiar website.
5. Start NVDA.
6. Press `H` to move to the next heading.
7. Press `H` again to move to the next heading.
8. Press `F` to move to the next form field.
9. Press `B` to move to the next button.
10. Listen to a button announcement.
11. Exit NVDA using its own controls.

Single-letter keys work in browse mode.
If a key does nothing, press `Insert + Space` and try again.

**Windows:** Install NVDA.

**Mac:** Use built-in VoiceOver instead.

**Check it worked:** You can start and stop NVDA and navigate part of a page.

**If you get stuck:** Use NVDA's introductory guide and keyboard help.

### 5.19 TalkBack

TalkBack is Android's built-in screen reader.
Test on Android when you have access to a device.
Android testing is useful for the cohort's India-focused work.

1. Find TalkBack in the phone's accessibility settings.
2. Read how to turn it off before turning it on.
3. Turn it on.
4. Complete the introductory navigation help.
5. Explore a familiar public page.
6. Turn it off using the device's instructions.

**Mac and Windows:** No computer installation is required.
This check happens on an Android device.

**Check it worked:** You can explore a page and safely turn TalkBack off.

**If you get stuck:** Use the device's accessibility help. Do not guess gestures.

### 5.20 Browser DevTools

DevTools are inspection tools built into a browser.
Use Chrome or Firefox.
Chrome is the simplest choice when a task specifically asks for Lighthouse.

1. Open a familiar public page.
2. Open DevTools.
3. Find the element inspector.
4. Find the accessibility information.
5. Find the accessibility tree.
6. Turn on device mode.
7. Inspect a computed style.
8. Find reduced-motion emulation.

A computed style is the final CSS value the browser uses.
Reduced-motion emulation lets you check a preference for less animation.

**Mac:** In Chrome, try `Cmd + Option + I`.

**Windows:** In Chrome, try `Ctrl + Shift + I`.

Browser labels differ.
Use the browser's help if a panel has moved.
Firefox provides similar inspection tools, but does not include Chrome's Lighthouse panel.

**Check it worked:** You can find accessibility information, change the viewport size and inspect a computed value.

**If you get stuck:** Search the browser name with `accessibility tree`, `device mode` or `emulate prefers-reduced-motion`.

### 5.21 Lighthouse

Lighthouse runs automated checks on web pages.
It is available through Chrome DevTools.

1. Open a public page in Chrome.
2. Open DevTools.
3. Find Lighthouse.
4. Select the relevant audit categories.
5. Run the audit.
6. Read one accessibility finding.

A high score does not prove that a page is accessible.
Use keyboard, screen reader and manual checks too.

**Mac and Windows:** Use Chrome's DevTools.

**Check it worked:** You can open the report and explain one suggested improvement.

**If you get stuck:** Check Chrome's current DevTools help and look for hidden panels.

### 5.22 AI assistant: Claude, ChatGPT or Gemini

Choose one assistant.
You do not need accounts with all three.

Use it to suggest options, explain unfamiliar code or summarise material you have already read.
Verify every claim.
An AI summary is not a research finding.

1. Choose Claude, ChatGPT or Gemini.
2. Find the provider's official website.
3. Check the free limit before use.
4. Create a free account.
5. Read the provider's data policy.
6. Read `07-AI-In-Design.md`.
7. Try a prompt without private information.
8. Check the response.
9. Record the use in the required AI log.
10. Add the required AI footer to the submitted work.

Never paste participant data into an AI tool.
Do not use a tool whose data policy you have not read.

**Mac and Windows:** Use the browser version.

**Check it worked:** You can explain what the assistant helped with, what you checked and where you logged it.

**If you get stuck:** Read doc 07 and ask in Discord with a prompt that has all private information removed.

### 5.23 Figma AI

Figma AI features use credits and may vary by plan.

The cohort pack lists Starter credits as 150 per day, up to 500 per month.
Check the free limit before use.
Check whether the specific feature is included.

1. Read the current Figma plan information.
2. Check your remaining credits.
3. Choose one small approved task.
4. Review the result.
5. Record the use under doc 07's rules.

**Mac and Windows:** Use available features in Figma.

**Check it worked:** You understand the credit cost and have logged the result.

**If you get stuck:** Continue manually rather than paying for more credits.

### 5.24 Google Stitch

Google Stitch is an optional AI interface tool.
Check the free limit before use.

1. Find the official service.
2. Read its data policy.
3. Use it only when an AI lab asks.
4. Compare the output with your written requirements.
5. Log the use.

**Mac and Windows:** Use a supported browser.

**Check it worked:** You can explain which requirements the output meets or misses.

**If you get stuck:** Use your existing design tool and ask about an approved alternative.

### 5.25 Figma Make

Figma Make is an optional AI prototyping tool.
Check the free limit before use.
Do not assume that your Starter account includes enough access for a lab.

1. Check availability in your account.
2. Read the lab requirements.
3. Write a small specification.
4. Generate a temporary prototype if free access permits.
5. Compare it with the specification.
6. Record the use.

Treat generated output as a draft.
Do not ship unchecked output.

**Mac and Windows:** Use the supported browser workflow.

**Check it worked:** You can identify differences between the specification and the prototype.

**If you get stuck:** Use an approved free alternative or build the prototype manually.

### 5.26 v0

v0 is an optional AI prototyping and coding tool.
Check the free limit before use.

1. Find the official service.
2. Read its data policy.
3. Check export and publishing restrictions.
4. Generate only the small prototype required by the lab.
5. Review the result.
6. Record the use.

For L-AI3, compare a temporary prototype with your specification.
For later publishing tasks, follow the week's code review, accessibility and publishing checks.

**Mac and Windows:** Use the browser service.

**Check it worked:** You can inspect the output and explain its limitations.

**If you get stuck:** Reduce the scope or use an approved free alternative.

### 5.27 Lovable

Lovable is an optional AI prototype tool.
Check the free limit before use.

1. Find the official service.
2. Read its data policy.
3. Check export and publishing access.
4. Use a small, non-private example.
5. Review the output.
6. Log the output.

**Mac and Windows:** Use a supported browser.

**Check it worked:** You know how to retain your work without paying.

**If you get stuck:** Stop before a paid upgrade and ask about a free alternative.

### 5.28 Bolt

Bolt is an optional AI coding and prototype tool.
Check the free limit before use.

1. Find the official service.
2. Read its data policy.
3. Check usage and export restrictions.
4. Use the smallest task required by the lab.
5. Review the output.
6. Log the output.

**Mac and Windows:** Use a supported browser.

**Check it worked:** You can access the generated files and explain what they do.

**If you get stuck:** Reduce the task or continue in VS Code with approved assistance.

### 5.29 GitHub Copilot Free

GitHub Copilot Free is an optional coding assistant.
Check the free limit before use.

1. Find the official GitHub Copilot extension in VS Code.
2. Check its publisher.
3. Read its data policy.
4. Install it only if your lab needs it.
5. Sign in to the free option.
6. Review each suggested change.
7. Log the assistance.

**Mac and Windows:** Use the extension in VS Code.

**Check it worked:** You can accept or reject a suggestion and explain the accepted code.

**If you get stuck:** Use the provider's current setup help or your browser assistant.

### 5.30 Cursor Free

Cursor is an optional editor with AI assistance.
Check the free limit before use.
Keep VS Code as your default unless a lab gives you a reason to change.

1. Find the official download.
2. Check its address and data policy.
3. Choose the Mac or Windows installer.
4. Follow the matching installation instructions.
5. Open your existing repository.
6. Review every generated change.
7. Log every generated change.

**Mac:** Use the official Mac package.

**Windows:** Use the official Windows installer.

**Check it worked:** You can inspect the diff before accepting a change.

**If you get stuck:** Return to VS Code and continue with the same repository.

### 5.31 Free web tools and recording tools

These tools need no setup until a task uses them.
Bookmark the resources listed in the table below.

| Tool | Use |
|---|---|
| typescale.com | Build a type scale |
| leonardocolor.io | Build perceptually even colour ramps |
| contrast-ratio.com | Check contrast |
| WebAIM contrast checker | Alternative contrast check |
| mermaid.live | Write and preview flow diagrams |
| Loom | Record prototype clips and mock interviews from Week 10 |
| Operating system screen recorder | Free alternative for recording |

Each named tool has its own subsection below.
Check current free access before use.

**Mac and Windows:** Bookmarks work in your browser.

**Check it worked:** You can find the saved resources without searching again.

### 5.32 Type Scale

1. Open typescale.com.
2. Choose a starting text size.
3. Compare the generated sizes.
4. Record the sizes you use.

**Mac and Windows:** Use the browser.

**Check it worked:** You have a short, named set of text sizes.

**If you get stuck:** Keep fewer sizes and test them in your design.

### 5.33 Leonardo

1. Open leonardocolor.io.
2. Explore a small colour ramp.
3. Check the selected colours in your interface.
4. Save the final values in your token notes.

**Mac and Windows:** Use the browser.

**Check it worked:** Your chosen colours have recorded values.

**If you get stuck:** Start with a small ramp and check contrast separately.

### 5.34 Contrast checkers

Use contrast-ratio.com or the WebAIM contrast checker.

1. Enter the text colour.
2. Enter the background colour.
3. Read the result for your text size.
4. Record the result with the colour pair.

**Mac and Windows:** Use the browser.

**Check it worked:** You can explain whether the tested pair meets the relevant requirement.

**If you get stuck:** Compare the result with the WCAG quick reference.

### 5.35 Mermaid

Mermaid creates diagrams from text.
The source text can stay in Git.

1. Open mermaid.live.
2. Try a small flow.
3. Read any syntax error.
4. Save the final Mermaid source in Markdown.

**Mac and Windows:** Use the browser or a supported editor preview.

**Check it worked:** The saved source produces the intended flow.

**If you get stuck:** Reduce the diagram to two steps and add one step at a time.

### 5.36 Loom and operating system recording

Use recording for prototype clips and mock interviews from Week 10.

1. Check Loom's free recording and storage limits.
2. Choose Loom or your operating system's recorder.
3. Close private windows.
4. Record a short test.
5. Play it back.
6. Check the sound and visible content.

**Mac:** Use the built-in screen recording controls or the official Loom option.

**Windows:** Use the available built-in recorder or the official Loom option.
Check your Windows version's recording support.

Large video files do not belong in the cohort repository.
Follow the task's sharing instructions.

**Check it worked:** The recording plays, and no private information is visible.

**If you get stuck:** Make a shorter test and check microphone permissions.

### 5.37 Obsidian, optional

Obsidian is an alternative Markdown editor.
You do not need it if VS Code works for you.

1. Find the official download.
2. Check the current free terms.
3. Install the version for your operating system.
4. Open only the folder you intend to edit.
5. Test Markdown and Mermaid preview.

**Mac:** Follow the Mac installation instructions.

**Windows:** Follow the Windows installation instructions.

Do not enable a paid sync service for cohort work.

**Check it worked:** Your Markdown file stays in the intended repository folder.

**If you get stuck:** Use VS Code instead.

### 5.38 Tools by sprint

After Sprint 1, add at most two new working tools per sprint.
Everything already learned carries forward.

Sprint 1 is the Week 0 setup sprint.
It is the one sprint that installs more than two tools, because every later sprint depends on them.

| Sprint | Required new tools (at most two) | Optional reading or alternatives | Carried forward |
|---|---|---|---|
| 1 | Figma and Penpot, plus the core setup tools: git and GitHub, VS Code, one AI assistant | Stark (Week 2) · axe DevTools and Lighthouse (Week 1 reading) · WAVE · FigJam | None yet |
| 2 | Maze **or** Lyssna, and Dovetail **or** Notion | A transcription tool, with consent · Optimal Workshop for card sorts and tree tests | Figma, git, AI assistant |
| 3 | FigJam, and one AI prototyping tool (Figma Make or v0) for L-AI3 only | Figma prototyping with variables is a Figma feature, not a new tool | everything above |
| 4 | Tokens Studio, and Style Dictionary | Storybook as reading only · Figma Dev Mode as optional reading, it may need a paid seat | everything above |
| 5 | At most two tools your capstone needs | Rive or ProtoPie | everything above |
| 6 | One analytics tool (PostHog **or** Microsoft Clarity), and one portfolio route you do not already have (Framer or Webflow) | The other analytics tool · GitHub Pages when you already know it | everything above |

Check each tool's free limits before use.
Do not assume that every listed product's free tier covers the task.
Use the alternatives below when access is blocked.

The tool map below is not an instruction to install every listed tool.
Some entries are features of an existing tool.
Others are optional, paid or need a free alternative.

| Tool | Learn this, and stop |
|---|---|
| **Figma** | Auto layout, components, variants and properties, **variables and modes**, prototyping with variables and conditionals where available. Libraries, branching and **Dev Mode** are optional reading when unavailable. |
| **Figma Make / v0** | Prompt a temporary prototype and compare it with your spec. Never ship unchecked output. |
| **FigJam** | Flow diagrams, affinity mapping, running a session |
| **Stark / axe** | Contrast checking, focus order, running an automated scan and reading the result |
| **VoiceOver / NVDA / TalkBack** | Navigate by heading, navigate by form control, hear what a button announces |
| **AI assistant** | Draft options to react against, read unfamiliar code, summarise what you already read. Verify everything; keep the log. |
| **Maze / Lyssna** | Build an unmoderated test, read task success, read a misclick heatmap |
| **Optimal Workshop** | Card sort, tree test, read the result |
| **Dovetail / Notion** | Tag a transcript, produce a finding that remains useful after the sprint. AI summaries are a first pass for you to check, never the finding. |
| **Tokens Studio** | Figma variables to token JSON |
| **Style Dictionary** | Token JSON (Design Tokens format 2025.10) to CSS custom properties, check compatibility before use |
| **Figma Dev Mode** | Inspect a spec, see which tokens a component uses. Know that the Dev Mode MCP server can connect design context to AI coding tools. |
| **Browser DevTools** | Accessibility tree, device mode, Lighthouse, reduced-motion emulation, inspecting computed values |
| **Storybook** | Read a story, document a component |
| **git** | branch, commit, push, open a pull request, read a diff |
| **PostHog** | Define an event, build a funnel, read a session replay, run a feature flag |
| **Clarity** | Heatmap and replay, nothing else |

**Mac and Windows:** Use browser tools where possible. Follow a tool's official operating-system instructions only when the relevant week requires installation.

**Check it worked:** You know which tools are needed now and which can wait.

### 5.39 Google Forms

Google Forms is a free option for simple research forms.

1. Check account access.
2. Create a test form without personal data.
3. Test it in a signed-out window.
4. Check what information it collects.

**Mac and Windows:** Use the browser.

**Check it worked:** A test participant can respond without an unintended sign-in requirement.

**If you get stuck:** Check response permissions and use the research week's consent instructions.

### 5.40 Maze

Maze may support unmoderated testing, where a participant completes tasks without a researcher present.

1. Check the current free study and response limits.
2. Confirm that the task fits those limits.
3. Build one small test only when the research week asks.

**Mac and Windows:** Use a supported browser.

**Check it worked:** You can preview the task and understand its success result.

**If you get stuck:** Use the week's approved manual testing method.

### 5.41 Lyssna

Lyssna is an alternative research testing tool.

1. Check its current free limits.
2. Check whether the required test type is included.
3. Preview a small test before recruiting anyone.

**Mac and Windows:** Use a supported browser.

**Check it worked:** The preview follows your research task.

**If you get stuck:** Use manual testing rather than a paid upgrade.

### 5.42 Dovetail

Dovetail can organise research notes and transcripts.

1. Check the free limits.
2. Check the data policy.
3. Use only approved, de-identified material.
4. Tag a short sample.
5. Verify any AI summary against the source.

**Mac and Windows:** Use the browser.

**Check it worked:** You can trace a finding back to evidence.

**If you get stuck:** Use Markdown notes or an approved Notion workspace.

### 5.43 Notion

Notion is an optional place to organise notes.
Final cohort decisions still belong in Git.

1. Check the free workspace, sharing and upload limits.
2. Create a private test page.
3. Add de-identified notes.
4. Copy final findings into the required Markdown file.

**Mac and Windows:** The browser version is enough.

**Check it worked:** Your submitted finding does not depend on private Notion access.

**If you get stuck:** Work directly in Markdown.

### 5.44 Transcription tools

Transcription tools turn speech into text.
Use one only with participant consent and an approved data policy.

1. Check the free limit.
2. Check storage and deletion terms.
3. Obtain consent before recording.
4. Review the transcript against the recording.
5. Remove identifying details.

**Mac and Windows:** Use the approved browser tool or follow its official operating-system installer instructions.

**Check it worked:** The transcript is checked, de-identified and handled under the research rules.

**If you get stuck:** Take manual notes with consent.

### 5.45 Optimal Workshop

Optimal Workshop may support card sorting and tree testing.
These methods check how people group information and find items.

1. Check the free limits.
2. Check whether the required method is included.
3. Preview the study before sharing it.

**Mac and Windows:** Use the browser.

**Check it worked:** The preview matches the research question.

**If you get stuck:** Ask about a manual card sort or navigation test.

### 5.46 Tokens Studio

Tokens Studio can help manage design tokens.
It is introduced later.

1. Check the plugin's free features.
2. Test with a small set of non-private tokens.
3. Export only the format required by the task.
4. Review the JSON before committing it.

JSON is a structured text format.

**Mac and Windows:** Use the supported Figma plugin workflow.

**Check it worked:** The exported values match your documented tokens.

**If you get stuck:** Maintain the approved token JSON manually.

### 5.47 Style Dictionary

Style Dictionary can turn token JSON into code values.
Do not install it during core setup.

1. Read the Sprint 4 instructions.
2. Check compatibility with Design Tokens format 2025.10.
3. Install Node only if the task requires it.
4. Follow the approved project setup.
5. Compare generated CSS values with the source tokens.

**Mac and Windows:** Use the same project instructions in the VS Code terminal after the matching Node installation.

**Check it worked:** The generated CSS values match the token source.

**If you get stuck:** Use the task's manual CSS custom property alternative.

### 5.48 Storybook

Storybook shows coded components and their states.
Start by reading an existing example.

1. Open the example supplied by the week.
2. Find one component.
3. Compare its states.
4. Read its documentation.

**Mac and Windows:** Use the browser for reading.
Install a local project only when the week provides instructions.

**Check it worked:** You can explain one component and its states.

**If you get stuck:** Ask which example to inspect before installing anything.

### 5.49 Figma Dev Mode and MCP, optional reading

Dev Mode is not part of the cohort's Starter setup.
Do not buy a seat.

Read about inspecting specs and token references.
Use Markdown specs, exported tokens and view-only links for required work.

The Dev Mode MCP server connects design context to AI coding tools.
Treat it as optional reading because access can require a paid Dev Mode seat.
Check the [official guide](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server).

**Mac and Windows:** Reading needs only a browser.
No server setup is required.

**Check it worked:** You know the free handoff method and do not depend on paid access.

**If you get stuck:** Ask for the Markdown specification and token files.

### 5.50 Rive, optional

Rive appears once in Sprint 5 for a motion handoff task.
It can create interactive animation with states.

1. Check the free editing, sharing and export limits.
2. Follow the motion task's instructions.
3. Use a free alternative if the required output is restricted.

**Mac and Windows:** Prefer the supported browser workflow. Any optional desktop install must follow the official instructions for your operating system.

**Check it worked:** You can share the required motion evidence without payment.

**If you get stuck:** Use the task's approved Figma prototype or recorded demonstration.

### 5.51 ProtoPie, optional

ProtoPie is an optional advanced prototyping tool.

1. Check whether ongoing free access covers the task.
2. Avoid depending on a temporary paid trial.
3. Use it only if the task has an approved free workflow.

**Mac and Windows:** Follow the official installer for the matching operating system only if needed.

**Check it worked:** The reviewer can access your required prototype without payment.

**If you get stuck:** Use Figma's available prototyping features or Penpot.

### 5.52 PostHog

PostHog is a later analytics tool.
Analytics records how a product is used.

1. Check the current free limits.
2. Use a demo or approved test project.
3. Define one event.
4. Inspect a funnel or replay only with approved data.
5. Check privacy and consent requirements before adding tracking.

A funnel shows how many people complete a sequence of actions.

**Mac and Windows:** Use the browser dashboard. Add code only through the week's instructions.

**Check it worked:** You can explain the event and what the result does and does not show.

**If you get stuck:** Use supplied sample data rather than tracking real participants.

### 5.53 Microsoft Clarity

Clarity provides heatmaps and session replay.
A heatmap shows where recorded interactions are concentrated.

1. Check current free terms.
2. Use a demo or approved test project.
3. Inspect a heatmap.
4. Inspect a replay only under the privacy rules.

**Mac and Windows:** Use the browser dashboard.

**Check it worked:** You can describe an observation without claiming it proves a person's intention.

**If you get stuck:** Use the week's sample evidence.

### 5.54 GitHub Pages

GitHub Pages publishes a website from repository files.
It is the cohort's free publishing option for small coded pages.

1. Read the [quickstart](https://docs.github.com/en/pages/quickstart).
2. Follow the publishing instructions in Week 12b or Week 22.
3. Check the selected repository and publishing source.
4. Open the published page.
5. Test its links and keyboard access.

Check current eligibility and usage limits before use.
Never publish private information or secrets.

**Mac and Windows:** Settings are managed in the browser.

**Check it worked:** The page opens at the published address and matches your reviewed files.

**If you get stuck:** Check the deployment result and the quickstart.

### 5.55 Framer, optional

Framer can publish a portfolio or marketing site.
It is not required for design files.

1. Check free publishing, branding and export restrictions.
2. Confirm the free option meets the portfolio task.
3. Use GitHub Pages if it does not.

**Mac and Windows:** Use the supported browser workflow.

**Check it worked:** A reviewer can open the portfolio without signing in or paying.

**If you get stuck:** Use the cohort's GitHub Pages route.

### 5.56 Webflow, optional

Webflow can build marketing sites with managed content.
A CMS is a system for editing content separately from page layouts.

1. Check free site, page and publishing limits.
2. Confirm the portfolio task fits.
3. Use GitHub Pages if the required feature is paid.

**Mac and Windows:** Use the supported browser workflow.

**Check it worked:** The required portfolio pages are publicly viewable.

**If you get stuck:** Use a simpler hand-coded page.

### 5.57 Miro, optional

Miro is useful when a collaborator already uses it.
It is not an extra requirement when FigJam or Mermaid is enough.

1. Check the free board and sharing limits.
2. Use an existing approved board where possible.
3. Save final decisions in Markdown.

**Mac and Windows:** Use the browser version.

**Check it worked:** Your submitted evidence remains accessible outside the board.

**If you get stuck:** Use Mermaid or an approved FigJam board.

### 5.58 Tools you do not need

None of the tools below needs installing for core setup.
Several are paid.
The table explains when they may be useful, not what you must buy.

| Tool | Genuinely needed when | Not needed for |
|---|---|---|
| **Adobe Photoshop** | Real photo retouching, complex masking, print prep | Routine UI design in Figma |
| **Adobe Illustrator** | Custom icon sets, logo work, complex vector illustration | Product icons covered by an existing icon library |
| **After Effects** | Marketing video, brand animation | Routine interface prototypes; start with available Figma animation |
| **Blender** | 3D renders, spatial and AR concepts | Standard product design |
| **Spline** | Interactive 3D on a marketing page | Standard product interfaces |
| **Rive** | Interactive animation with state machines | Static prototypes |
| **Framer** | Publishing a portfolio or marketing site quickly | Product design source files |
| **Webflow** | A marketing site with a CMS | Product design source files |
| **Sketch** | Joining a Mac-only team that uses it | Cohort work |
| **Adobe XD** | Existing legacy work only; check current product status before use | New cohort work |
| **Canva** | A quick internal presentation | Core product design work |
| **Miro** | Workshops with a collaborator who already uses it | Tasks already covered by FigJam or Mermaid |
| **Excalidraw** | A quick temporary diagram during a call | Required deliverables when the task specifies another format |
| **Penpot** | Figma access or licensing limits block you | No extra setup beyond a browser account |

Penpot is the cohort's supported backup.
It is more than an optional product name to recognise.

Photoshop and Illustrator remain optional.
If a task needs retouching or custom vector icons, use an approved free method.
After Effects, Blender and Spline stay optional throughout.

The old checklist asked you to purchase and download Refactoring UI.
That purchase is not required.
Use only free cohort resources.

**Mac and Windows:** No installation is required for this section.

**Check it worked:** You can continue without buying software.

### 5.59 Where work lives

Use the same storage rules on Mac and Windows.

| Thing | Figma or Penpot | Git |
|---|---|---|
| Screens and components | Source design file | View-only link and exported PNG of the final state |
| Tokens | Figma variables mirror the approved values where supported | **Source of truth**, `system/tokens/*.tokens.json` |
| Flows and IA | Optional in FigJam | **Source of truth**, Mermaid in Markdown |
| Decisions and rationale | Do not keep the only copy here | **Always**, Markdown |
| Specs and annotations | Optional visual annotations; Dev Mode only if available | Markdown spec next to the link |

IA means information architecture, how content is grouped and organised.

Git cannot show useful line-by-line differences inside a Figma design file.
Keep decisions and reviewable specifications in text.

Teams without libraries share a view-only design link and exported tokens.
Only the team leader updates `delivery/`.
Follow the week's review process for `system/` and `fundamentals/`.

1. Save individual work in your own sprint and week folder.
2. Save a view-only design link in Markdown.
3. Add the final export requested by the task.
4. Save decisions and specifications in Markdown.
5. Review the files before committing.

Allowed submission formats:

- Markdown, `.md`.
- PNG or JPG under 2 MB each.
- PDF under 10 MB.
- A view-only Figma link written inside Markdown.
- A view-only Penpot link inside Markdown when using the backup.

Use lowercase image names with hyphens and no spaces.
Example: `r1-1-home-page.png`.

Shared token JSON is a specific system contribution.
Follow the system task's instructions.
Do not add unrelated code or data files to design submissions.

Code tasks explicitly ask for HTML, CSS or JavaScript.
Follow that task's permitted paths and files.

**Check it worked:** Your work can be reviewed from the repository without an editable design link.

**If you get stuck:** Check the week's “What to Commit” section before adding files.

### 5.60 Code corner preparation

You will read and edit small amounts of HTML, CSS and JavaScript.
You are not expected to master programming.

Keep each code corner to about 20-40 minutes unless the week gives a larger task.

| Week | Code work | Resource |
|---|---|---|
| Week 0 | Install VS Code and Git; make a first HTML page | https://web.dev/learn/html |
| Week 3 | CSS box model and flex layout; connect them to Auto Layout | https://web.dev/learn/css |
| Week 6 | HTML forms for the research form | https://web.dev/learn/forms |
| Week 10 | Read a small JavaScript click interaction that changes state | https://web.dev/learn/javascript |
| Week 12b | Build, review and publish an AI-assisted coded prototype | https://docs.github.com/en/pages/quickstart |
| Week 15 | Connect CSS variables to design tokens | https://web.dev/learn/css |
| Week 22 | Publish a portfolio page | https://docs.github.com/en/pages/quickstart |

1. Open your cloned repository in VS Code.
2. Follow the current week's code task.
3. Save files only in its required location.
4. Open the page in a browser.
5. Check the result.
6. Review any AI-generated code before committing.

**Mac and Windows:** Plain HTML and CSS need an editor and browser.
Node is optional unless the project requires it.

**Check it worked:** You can explain a small change you made and show its browser result.

**If you get stuck:** Use MDN, reduce the change, or ask in Discord with the relevant code and error.

### 5.61 Common problems and free tier limits

Free plans change.
Check before use, especially before recruiting participants or starting a large prototype.

| Tool or group | Check before use | Free fallback |
|---|---|---|
| Figma Starter | File slots, page limits, collaboration, history, variables and AI credits | Penpot, local backups, Markdown tokens |
| Figma Education | Eligibility, verification and included features | Starter workflow |
| Penpot | Current file, storage and collaboration terms | Smaller files and exported evidence |
| FigJam | Board allowance and workspace counting | Mermaid |
| AI tools | Requests, credits, model access, exports and data policy | Smaller task or manual work |
| Research tools | Study types, participants, responses and export access | Consented manual testing |
| Notion and Dovetail | Sharing, storage, uploads and export access | Markdown |
| Loom | Recording length, count, storage and sharing | Operating system recorder |
| Accessibility plugins | Free checks and scan restrictions | Manual checks and alternative free checkers |
| Animation tools | Editing, export and sharing restrictions | Approved recorded or Figma prototype |
| Portfolio platforms | Pages, branding, public hosting and export access | GitHub Pages |
| Analytics tools | Usage caps, billing behaviour, retention and consent settings | Supplied sample evidence |
| GitHub | Repository, file, storage and publishing limits | Small text files and compressed exports |

| Problem | What to try |
|---|---|
| Figma will not create another file | Check workspace slots, ask the admin, then use Penpot |
| Figma will not create another page | Use named sections or switch to Penpot |
| A library or Dev Mode asks for payment | Use view-only links, Markdown specs and token files |
| A design link asks the reviewer to request access | Check view-only sharing and test signed out |
| Git is not found | Restart the terminal and check installation instructions |
| Git commit has the wrong identity | Correct the student code and private email before continuing |
| `upstream` already exists | Inspect `git remote -v`; do not add it again |
| Git push is rejected | Check branch, remote and the exact error; do not force-push |
| A file is in the wrong folder | Reopen the clone and move the file into your own week folder |
| A screen reader is hard to stop | Use its documented exit method or system accessibility controls |
| An extension does not appear | Check browser support and reopen DevTools |
| An AI tool reaches its free limit | Stop, reduce the task or use an approved alternative |
| A paid trial appears | Leave the trial and choose the free workflow |
| A secret enters Git history | Tell the admin promptly; deleting the visible file is not enough |

**Mac and Windows:** Include your operating system when asking for help.

**Check it worked:** You can repeat the action successfully or continue with an approved free alternative.

**If you get stuck:** Post the exact error, the section number and what you tried in Discord. Hide private information first.

## 6. What to Commit

Read the Week 0 tasks in [Design-Sprint-1/00-READ-FIRST.md](Design-Sprint-1/00-READ-FIRST.md).
That page links the Week 0 task file with the exact task titles and file names.
Check the exact Week 0 task file name before use.
Do not create duplicate evidence just for this guide.

Every setup commit message starts with the task ID. Use these messages:

| Task | Commit message |
|---|---|
| `Z0.1` | `Z0.1 accounts and Discord` |
| `Z0.2` | `Z0.2 Figma and Penpot setup` |
| `Z0.3` | `Z0.3 VS Code and Git installed` |
| `Z0.4` | `Z0.4 fork, clone and branch` |
| `Z0.5` | `Z0.5 first commit with image and Figma link` |
| `Z0.6` | `Z0.6 first pull request` |
| `Z0.7` | `Z0.7 first HTML page` |
| `Z0.8` | `Z0.8 accessibility tools check` |

If the Week 0 task file gives a different exact message, use that message.

For setup notes, use:

```text
Design-Sprint-1/students/UX{n}/week0/setup.md
```

Record only:

- Your student code.
- Your operating system.
- Installed Git and VS Code versions.
- Completed setup checks.
- Your view-only design link.
- Any blocked step and the free alternative you used.

Do not include login emails, local paths containing real names, account recovery codes or private screenshots.

Complete this checklist:

- [ ] Your accounts work.
- [ ] You have joined Discord and found the help channel.
- [ ] Your Figma account works.
- [ ] Your cohort team invitation is accepted, or the admin knows it is blocked.
- [ ] Your current Figma file is named `SPRINT-1 UX{n}`.
- [ ] You understand the file and page limits.
- [ ] You have not created three separate Figma files for one sprint.
- [ ] You have a local backup and archive plan.
- [ ] Your Penpot backup account and test file work.
- [ ] The four Figma Learn lessons are completed.
- [ ] axe DevTools works.
- [ ] Stark is set up as a Week 2 item.
- [ ] You can find browser accessibility information.
- [ ] VoiceOver or NVDA has been used for five minutes on a familiar website.
- [ ] TalkBack has been tested if an Android device is available.
- [ ] Your GitHub account works.
- [ ] Git is installed.
- [ ] Git uses your student code and intended private commit email.
- [ ] The program repository is forked once.
- [ ] Your fork is cloned.
- [ ] `origin` and `upstream` point to the correct repositories.
- [ ] Your student branch is active.
- [ ] VS Code opens the cloned folder.
- [ ] Markdown preview works.
- [ ] One free AI assistant is available.
- [ ] Its data policy has been read.
- [ ] You know the AI log and footer rules in `07-AI-In-Design.md`.
- [ ] typescale.com, leonardocolor.io, a contrast checker and mermaid.live are bookmarked.
- [ ] `09-Modern-Practice-Map.md` has been skimmed.
- [ ] No purchase, including Refactoring UI, was needed.
- [ ] Optional tools remain optional.

Before each commit:

1. Save the task file.
2. Run `git status`.
3. Review the diff.
4. Stage only the intended files.
5. Commit with the task ID.
6. Push your student branch.
7. Open or update the pull request using `10-GitHub-For-Designers.md`.

Final submission checks:

- [ ] Files are inside your own sprint and week folder.
- [ ] Each completed task has its own commit.
- [ ] The image is PNG or JPG under 2 MB.
- [ ] Image names are lowercase, with hyphens and no spaces.
- [ ] PDFs are under 10 MB.
- [ ] Design links are view-only and written inside Markdown.
- [ ] No `.fig` files are committed.
- [ ] No passwords, tokens or real personal data are included.
- [ ] Any code files belong to an explicit code task.
- [ ] Only the team leader has updated `delivery/`.
- [ ] Your first pull request opens successfully.

Next: `05-The-Six-Sprints.md`, then `Design-Sprint-1/00-READ-FIRST.md`.
