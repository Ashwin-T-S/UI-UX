# GitHub for Designers

## 1. What We Are Doing

You will use GitHub to save design work, track changes, and ask for review.

A repository, or repo, stores files and their change history. The cohort repo is [StartwithDot/UI-UX](https://github.com/StartwithDot/UI-UX).

You can work in three ways:

| Way | Use it when | What you need |
|---|---|---|
| VS Code + Git | You want to edit Markdown and work on code tasks. | VS Code, Git, and a browser. |
| GitHub Desktop | You want to use buttons for most Git actions. | GitHub Desktop and a text editor. |
| GitHub web upload | You need the easiest fallback for submitting files. | A browser and your finished files. |

Choose one way for your first submission. You do not need to learn all three at once.

All three ways follow the same order:

**Fork > branch > add work > commit > push if working locally > pull request > review.**

## 2. Why We Are Doing It

Product designers work with engineers and other designers. GitHub helps you share clear files, explain changes, and respond to feedback.

Your design stays in Figma or Penpot. GitHub holds your written decisions, exported images, and review history. Later, it also holds the small pages you build.

Your commits help you find earlier work. Your pull requests show how you explain and improve your work.

This is new for most people. Go slowly.

## 3. What to Learn First

| Word | Simple meaning |
|---|---|
| Git | A tool that records file changes. |
| GitHub | A website that hosts Git repositories and reviews. |
| Fork | Your GitHub copy of another repository. |
| Clone | A local copy of a repository on your computer. |
| Branch | A separate place to prepare changes inside a repository. |
| Stage | Choose the changes for your next commit. |
| Commit | A saved record of selected changes. |
| Push | Send local commits to GitHub. |
| Pull | Bring remote changes into your current local branch. |
| Pull request, or PR | A request to review and merge changes from a branch. |
| Merge | Combine changes into another branch. |
| Remote | A named connection to a repository on GitHub. |
| `origin` | The remote name normally used for your fork. |
| `upstream` | The remote name you add for the original cohort repo. |
| Merge conflict | Changes Git cannot combine without your help. |
| Markdown | Plain text with simple marks for headings, lists, and links. |

Before you start:

- Know your student code, `UX1` to `UX10`.
- Know your sprint number.
- Find the exact task ID and required filename in your week guide.
- Have your finished file ready.
- Use only free tools.

By the end, you can:

- Create your accounts and install your chosen tools.
- Fork the cohort repo.
- Clone your fork when working locally.
- Create a branch.
- Save one task in one commit.
- Open a pull request.
- Bring cohort updates into your fork and local copy.
- Share safe images and a view-only Figma link.
- Fix common problems without deleting your work.

## 4. Where to Find Resources

| Resource | Use it for |
|---|---|
| [Tools setup](04-Tools-Setup.md) | Account and tool setup. Find the section for your tool. |
| [Cohort repo](https://github.com/StartwithDot/UI-UX) | The original repository and pull requests. |
| [GitHub](https://github.com/) | Your account and fork. |
| [VS Code](https://code.visualstudio.com/) | A free editor for Markdown and code. |
| [Git](https://git-scm.com/) | Git installation and learning resources. |
| [GitHub Desktop](https://desktop.github.com/) | A free app for working with Git using buttons. |
| [Penpot](https://penpot.app/) | The backup design tool when Figma limits block you. |
| Your current week guide | Exact task IDs, filenames, commit messages, and “Done when” points. |

> **Where you work**
>
> Design in Figma or Penpot.
> Write Markdown in VS Code or another plain text editor.
> Use Git commands in the VS Code terminal.
> Use GitHub Desktop if you prefer buttons.
> Use your browser for web uploads and pull requests.

Search keywords: `GitHub fork`, `Git clone`, `GitHub Desktop branch`, `Git upstream`, `Git merge conflict`, `Figma view-only link`.

If a button label differs from this guide, look for the action described. Ask in Discord if you cannot find it.

## 5. Step-by-Step Guide

Work on one task, one file, and one commit at a time.

A task may also require an image beside its Markdown file. Include the required supporting file in the same task commit.

### 5.1 Create your accounts and install your chosen tools

Use your student code in cohort files. Never put your real name or other personal data in committed work.

**Mac**

1. Open [GitHub](https://github.com/).
2. Create an account if you do not have one.
3. Verify your account using the instructions GitHub sends.
4. Open your GitHub account settings.
5. Find the email privacy settings.
6. Enable email privacy.
7. Copy the GitHub-provided no-reply email for Git setup.
8. Create or sign in to your Figma account.
9. Choose your GitHub workflow from the table below.

**Windows**

Follow the same account steps in your browser.

| Workflow | Mac installation | Windows installation |
|---|---|---|
| VS Code + Git | 1. Download VS Code from its official site.<br>2. Install VS Code.<br>3. Download Git from its official site.<br>4. Follow the Git Mac install instructions. | 1. Download VS Code from its official site.<br>2. Run the VS Code installer.<br>3. Download Git from its official site.<br>4. Run the Git installer. |
| GitHub Desktop | 1. Download GitHub Desktop from its official site.<br>2. Install GitHub Desktop.<br>3. Sign in to GitHub. | 1. Download GitHub Desktop from its official site.<br>2. Run the installer.<br>3. Sign in to GitHub. |
| Web upload | 1. Use your browser.<br>2. No Git installation is needed. | 1. Use your browser.<br>2. No Git installation is needed. |

For VS Code + Git, restart VS Code after installing Git.

Open the VS Code terminal. Run each command separately.

**Mac, Terminal; Windows, PowerShell or Git Bash**

```bash
git --version
```

Replace `UX1` with your student code.

```bash
git config --global user.name "UX1"
```

Replace `YOUR_GITHUB_NOREPLY_EMAIL` with the exact no-reply email from your GitHub settings.

```bash
git config --global user.email "YOUR_GITHUB_NOREPLY_EMAIL"
```

Check the saved settings:

```bash
git config --global user.name
```

```bash
git config --global user.email
```

Git commit details can be public. Set the student code and no-reply email before your first commit. If you already use Git for another project, ask in Discord about setting these values only for this repo.

**GitHub Desktop users**

GitHub Desktop uses the same Git author details. Set them before your first Desktop commit.

1. Open GitHub Desktop.
2. Sign in to GitHub if asked.
3. Open the app settings. On Mac, look in the GitHub Desktop menu. On Windows, look in the File menu.
4. Find the Git author name and email settings.
5. Set the name to your student code, such as `UX1`.
6. Set the email to the GitHub no-reply email from your settings.
7. Save the settings.

**Check it worked:** On Mac or Windows, you can sign in to GitHub. Your chosen app opens. If you chose Git, `git --version` prints a version number. If you chose GitHub Desktop, its commit author settings show your student code and no-reply email.

### 5.2 Find your folder and prepare safe files

Your work belongs inside the current sprint:

```text
Design-Sprint-N/
  students/
    UX{n}/
      README.md
      weekN/
      portfolio/
      ai-log.md
```

These are placeholders:

- `Design-Sprint-N` means the sprint folder, such as `Design-Sprint-1`.
- `UX{n}` means your assigned code, such as `UX1`.
- `weekN` means the week folder, such as `week0` or `week3`.
- Special weeks use `week12b` and `week20b`.

Do not type the braces into a real folder name.

For example, work by UX1 in week 0 goes here:

```text
Design-Sprint-1/students/UX1/week0/
```

Week numbers continue across sprints. Sprint 2 holds `week5` to `week8`.

Keep these folder rules:

1. Work only in your own student folder.
2. Follow the current week guide for exact filenames.
3. Keep one learning note per LEARN block, using `session{n}-learning.md`.
4. Keep task notes in the required `{TASK-ID}-{name}.md` file.
5. Keep case-study writing and reviews in `portfolio/`.
6. Link your separate portfolio site from `portfolio/README.md`.
7. Record every use of AI in `ai-log.md`.
8. Add the required AI footer to files an AI tool touched, following doc 07.
9. Copy templates from `_templates/`.
10. Leave the original templates unchanged.

Shared cohort work belongs in `system/`, `delivery/`, or `fundamentals/` through a pull request. Only the team leader updates `delivery/`.

**Allowed submission files**

| File | Rule |
|---|---|
| Markdown, `.md` | Use for notes, decisions, and design links. |
| PNG or JPG | Each file must be under 2 MB. |
| PDF | Each file must be under 10 MB. |
| Figma link | Put a view-only link inside a Markdown file. |

Code tasks may explicitly require HTML, CSS, JavaScript, or other project files. Follow that task's instructions.

Never commit `.fig` files, passwords, tokens, or real personal data. Do not include real user IDs, phone numbers, dates of birth, participant names, photographs, or faces. Use `P1`, `P2`, and similar participant codes. Redact screenshots before uploading them.

**Mac:** Use Finder to inspect your prepared files and folder.

**Windows:** Use File Explorer to inspect your prepared files and folder.

**Check it worked:** On either system, every file has a clear destination inside your own week folder and contains no personal data.

### 5.3 Fork the cohort repo

A fork belongs to your GitHub account. You normally push student work to your fork, then ask the cohort to review it.

**Mac and Windows, browser**

1. Sign in to GitHub.
2. Open [StartwithDot/UI-UX](https://github.com/StartwithDot/UI-UX).
3. Select **Fork**.
4. Choose your account as the owner.
5. Create the fork.
6. Open the new fork.

The repository heading should show your account as the owner. The original cohort repo stays under `StartwithDot`.

Create one fork. Reuse it for later weeks.

**Check it worked:** On Mac or Windows, your browser shows a fork owned by your GitHub account.

### 5.4 Way 1: clone and create a branch with VS Code + Git

Skip this section if you chose GitHub Desktop or web upload.

Open your fork in the browser. Copy its HTTPS clone URL from **Code**.

Replace `YOUR_FORK_HTTPS_URL` below with that copied URL.

**Mac**

1. Open Terminal.
2. Move to Documents.

```bash
cd ~/Documents
```

3. Clone your fork.

```bash
git clone YOUR_FORK_HTTPS_URL
```

4. Enter the cloned folder.

```bash
cd UI-UX
```

**Windows, PowerShell**

1. Open File Explorer.
2. Open the folder where you want to keep the clone.
3. Open PowerShell in that folder.
4. Clone your fork.

```powershell
git clone YOUR_FORK_HTTPS_URL
```

5. Enter the cloned folder.

```powershell
cd UI-UX
```

**Mac and Windows**

1. Open VS Code.
2. Choose **File > Open Folder**.
3. Select the cloned `UI-UX` folder.
4. Open the VS Code terminal.
5. Check the remote.

```bash
git remote -v
```

`origin` must point to your fork.

6. Add the original cohort repo as `upstream`.

```bash
git remote add upstream https://github.com/StartwithDot/UI-UX
```

If Git says `upstream` already exists, inspect it with `git remote -v`. Do not add it again.

7. Check your current branch.

```bash
git branch --show-current
```

The examples below use `main` for the default branch. If the repo uses a different default branch, use its exact name.

8. Create your work branch.

```bash
git switch -c ux1-week0-z0-5
```

Replace `ux1-week0-z0-5` with your own code, week, and task ID. Keep it lowercase.

**Check it worked:** On Mac or Windows, `git remote -v` shows your fork as `origin` and the cohort repo as `upstream`. Your current branch is your work branch.

### 5.5 Way 1: save, commit, and push with Git

The example below uses the week 0 task ID `Z0.5`. For other tasks, use the exact path and commit message from the week guide.

Complete section 5.10 before creating your first Markdown file.

**Mac and Windows, VS Code**

1. Open your week folder.
2. Create the required Markdown file.
3. Add your task notes.
4. Save the file.

Save shortcuts:

| Action | Mac | Windows |
|---|---|---|
| Save | `Cmd+S` | `Ctrl+S` |
| Markdown preview | `Cmd+Shift+V` | `Ctrl+Shift+V` |

For a folder that does not exist yet, use the VS Code file panel to create it.

You can also create the example folder in the terminal.

**Mac**

```bash
mkdir -p Design-Sprint-1/students/UX1/week0
```

**Windows, PowerShell**

```powershell
New-Item -ItemType Directory -Force -Path "Design-Sprint-1/students/UX1/week0"
```

Run the following Git commands separately. They are the same on Mac and Windows.

1. Check which files changed.

```bash
git status
```

2. Read changes to existing text files.

```bash
git diff
```

`git diff` does not show new, untracked files. Open each new file in VS Code. Open each image to inspect it.

3. Stage the required file.

```bash
git add Design-Sprint-1/students/UX1/week0/Z0.5-first-commit.md
```

4. Stage any image required by that task, using its exact path.
5. Review the staged text.

```bash
git diff --cached
```

6. Check the staged file list.

```bash
git status
```

7. Make the task commit.

```bash
git commit -m "Z0.5 add first image and view-only Figma link"
```

8. Push your branch.

```bash
git push -u origin ux1-week0-z0-5
```

Follow any sign-in prompt through the supported browser flow. Do not type your GitHub account password into a Git password prompt.

For later commits on this same branch, use:

```bash
git push
```

**Check it worked:** On Mac or Windows, your branch on GitHub shows the new commit and the correct files.

### 5.6 Way 2: use GitHub Desktop

GitHub Desktop handles cloning, branches, commits, and pushes using buttons.

**Mac**

1. Install GitHub Desktop from [its official site](https://desktop.github.com/).
2. Open the app.
3. Sign in to GitHub.

**Windows**

1. Download GitHub Desktop from [its official site](https://desktop.github.com/).
2. Run the installer.
3. Open the app.
4. Sign in to GitHub.

**Mac and Windows**

1. Find the action to clone a repository.
2. Select your fork.
3. Choose a local folder.
4. Clone the fork.
5. Select the cloned repo in the app.
6. Create a branch named for your code, week, and task ID, such as `ux1-week0-z0-5`.
7. Open the local repo folder in your editor.
8. Save your task files in your own week folder.
9. Return to GitHub Desktop.
10. Review the changed files.
11. Select only the files for this task.
12. Check the commit author settings. Use your student code and the GitHub no-reply email.
13. Write the task ID and action in the commit summary.
14. Commit to your work branch.
15. Publish the branch if it is new.
16. Push any later local commits.
17. Open the branch on GitHub.

Read each file before committing it. Inspect images in your image viewer.

If you cannot find an action, look for the words **clone**, **branch**, **commit**, or **push** in the app.

**Check it worked:** On Mac or Windows, GitHub shows your work branch, task commit, and intended files.

### 5.7 Way 3: use web upload as the easiest fallback

This route needs no local Git setup. You still use a fork, a branch, a commit, and a pull request.

Browser commits are saved directly to GitHub. There is no separate push step.

**Mac**

Prepare files using Finder and a plain text editor. Check that Markdown filenames end in `.md`.

**Windows**

Prepare files using File Explorer and a plain text editor. Show file extensions so you can check that a file is not accidentally named `.md.txt`.

**Mac and Windows, browser**

1. Open your fork.
2. Open its branch selector.
3. Create a work branch with your code, week, and task ID, such as `ux1-week0-z0-5`, from the default branch.
4. Confirm that your work branch is selected.
5. Open your sprint folder.
6. Open your student folder.
7. Open your week folder.
8. Find the action to upload files.
9. Select the prepared files.
10. Review the displayed paths.
11. Enter a commit message starting with the task ID.
12. Commit to your work branch.
13. Open each uploaded file to inspect it.

If the week folder does not exist, use the new-file action. Enter the folder and filename together, such as `week0/Z0.5-first-commit.md`, from inside your student folder.

Keep each commit focused on one task.

**Check it worked:** On Mac or Windows, the files appear on your work branch inside your own week folder.

### 5.8 Prepare and commit images

The cohort image rule is **under 2 MB per PNG or JPG**. This is a cohort rule.

Use lowercase letters and hyphens for image filenames. Do not use spaces.

Example:

```text
r1-1-home-page.png
```

Keep exact task filenames from the week guide. The lowercase rule above applies to image names.

**Mac**

1. Export the required screen from Figma or Penpot.
2. Select the image file in Finder.
3. Use **Get Info** to check its size.
4. Rename it using lowercase letters and hyphens.
5. Open it to check the content.
6. Move it into your week folder.

**Windows**

1. Export the required screen from Figma or Penpot.
2. Select the image file in File Explorer.
3. Use **Properties** to check its size.
4. Rename it using lowercase letters and hyphens.
5. Open it to check the content.
6. Move it into your week folder.

If the image is too large:

1. Export only the frame you need.
2. Reduce the export dimensions or scale.
3. Use JPG for a photograph when appropriate.
4. Check the new file size.
5. Check that text remains readable.

Renaming a file does not reduce its size. Changing its extension does not convert it.

Before committing, confirm that redacted personal data is absent from the exported image itself.

Use your chosen workflow to commit the image. You can display a nearby image inside Markdown:

```markdown
![Home page screen](r1-1-home-page.png)
```

**Check it worked:** On Mac or Windows, the image is readable, under 2 MB, safely redacted, and visible in the GitHub Markdown preview.

### 5.9 Share a view-only Figma link inside Markdown

Use one Figma file per sprint, named `SPRINT-N UX{n}`, with one page per week. Do not create separate Practice, System, and Delivery files for every sprint.

Figma Starter allows 3 files. Use one file per sprint plus one spare; use Penpot when the 3-file limit blocks you.

If the 3-file limit blocks you, ask the admin or use Penpot. Do not assume you have Education access or shared libraries.

**Mac and Windows, Figma in the browser or app**

1. Open your sprint design file.
2. Open the required week page.
3. Open the sharing controls.
4. Find the link-access setting.
5. Choose a setting that lets your reviewer open the file.
6. Set the permission to view.
7. Copy the link.
8. Open a private browser window.
9. Paste the link.
10. Check whether the intended reviewer can open it without edit access.

Private-window shortcuts:

| Action | Mac | Windows |
|---|---|---|
| Chrome private window | `Cmd+Shift+N` | `Ctrl+Shift+N` |
| Firefox private window | `Cmd+Shift+P` | `Ctrl+Shift+P` |

If account rules require sign-in, test with a reviewer who has access. If the link asks for access unexpectedly, fix the sharing setting before submitting.

Paste this structure into your task Markdown file:

```markdown
## Design link

[View the design](PASTE_YOUR_VIEW_ONLY_FIGMA_LINK_HERE)

- File: SPRINT-N UX{n}
- Page: weekN
- Frame: REPLACE_WITH_FRAME_NAME
- Permission: view only
```

Replace every placeholder. The copied design link is your submission content. Do not upload a `.fig` file.

For Penpot, use the equivalent view-only sharing option and label the link as Penpot.

**Check it worked:** On Mac or Windows, the link opens the intended design for your reviewer and does not give edit access.

### 5.10 Write Markdown

Markdown is plain text. GitHub displays its marks as formatted content.

**Mac:** Write in VS Code and use `Cmd+Shift+V` to preview.

**Windows:** Write in VS Code and use `Ctrl+Shift+V` to preview.

For web editing, use the browser's preview option before committing.

````markdown
# Document title

## Section title

### Smaller section

Write a short paragraph.

Leave a blank line before the next paragraph.

**Bold text**

*Italic text*

- First item
- Second item

1. First action.
2. Second action.

- [ ] Not finished
- [x] Finished

[Open the cohort repo](https://github.com/StartwithDot/UI-UX)

[Open a nearby note](notes.md)

![Home page screen](r1-1-home-page.png)

Use `git status` to check files.

```text
Put a command, path, or plain text example here.
```

| Item | Note |
|---|---|
| Screen | Home page |
````

Keep these habits:

- Use one `#` heading for the document title.
- Put a space after heading marks.
- Leave a blank line before lists and tables.
- Use short paragraphs.
- Use descriptive link text.
- Match filename spelling and letter case exactly.
- Use `/` in Markdown links on both Mac and Windows.
- Use relative links for nearby files.
- Include the AI footer required by doc 07 when applicable.

A link inside a student task must work from that task file's location. Do not copy a relative path from a different folder without checking it.

**Check it worked:** On Mac or Windows, the preview shows readable headings, working links, and the intended image.

### 5.11 Open a pull request

Pushing a branch or uploading files does not submit a pull request automatically.

A pull request should compare your work branch with the cohort's default branch.

**Mac and Windows, browser**

1. Open your fork on GitHub.
2. Open the action to create a pull request.
3. Set the base repository to `StartwithDot/UI-UX`.
4. Set the base branch to the cohort default branch.
5. Set the head repository to your fork.
6. Set the compare branch to your work branch.
7. Review the changed-file list.
8. Open each changed file.
9. Start the title with the task ID.
10. Describe what changed.
11. Include the review checks you completed.
12. Create the pull request.

You can use this body structure:

```markdown
## Task

TASK_ID and task title

## What changed

- Describe the submitted work.

## Checks

- [ ] Files are in my own week folder.
- [ ] Images are under 2 MB.
- [ ] PDFs are under 10 MB.
- [ ] Design links are view only.
- [ ] No personal data or secrets are included.
- [ ] Required AI log and footer are included.

## Help needed

Describe a specific question, or write "None".
```

Do not tick a check until you have completed it.

Wait for review. Follow the cohort's merge process. Do not squash task commits.

To respond to feedback:

1. Open the same work branch.
2. Make the requested change.
3. Commit the correction with the task ID.
4. Push it, or commit through the browser.
5. Reply to the review comment.

The existing pull request updates automatically when you add commits to its branch.

**Check it worked:** On Mac or Windows, the PR targets the cohort repo, shows your intended files, and starts with the task ID.

### 5.12 Pull updates from upstream

The original cohort repo may gain new guides, fixes, and merged work. Bring those updates into your fork before starting a new task.

Finish your current work first. Do not switch branches while unsure about unsaved or uncommitted changes.

The commands below assume the default branch is `main`.

**Mac and Windows, VS Code terminal**

1. Check your working files.

```bash
git status
```

2. Finish and commit any intended work.
3. Check the remotes.

```bash
git remote -v
```

4. Add `upstream` only if it is missing.

```bash
git remote add upstream https://github.com/StartwithDot/UI-UX
```

5. Switch to the default branch.

```bash
git switch main
```

6. Pull cohort updates.

```bash
git pull upstream main
```

7. Send the updated default branch to your fork.

```bash
git push origin main
```

8. Create a new work branch.

```bash
git switch -c ux1-week1-task-id
```

Replace `task-id` with the exact task ID in lowercase. Replace `ux1-week1` with your own code and week.

**Mac and Windows, GitHub Desktop**

1. Open your fork in the browser.
2. Switch to its default branch.
3. Find the fork-sync action.
4. Review the proposed update.
5. Update your fork from the cohort repo.
6. Open GitHub Desktop.
7. Select your local clone.
8. Switch to its default branch.
9. Fetch remote changes.
10. Pull the available updates.
11. Create a new work branch with a task ID in the name.

**Mac and Windows, web upload**

1. Open your fork.
2. Switch to its default branch.
3. Find the fork-sync action.
4. Review the proposed update.
5. Update your fork from the cohort repo.
6. Create a new work branch with a task ID in the name.

If GitHub reports a conflict, stop and follow the next section. Do not choose an option that discards your work.

**Check it worked:** On Mac or Windows, your fork includes the latest cohort updates. If working locally, your local default branch includes them too.

### 5.13 Fix common mistakes

Use the same Git commands on Mac and Windows. Run them inside your local repo.

| Problem | What to do |
|---|---|
| `git` is not recognised or not found | Check Git installation in the setup guide. Restart VS Code after installation. |
| `not a git repository` | Open the cloned `UI-UX` folder. Run `git status` there. |
| `remote upstream already exists` | Run `git remote -v`. Check the existing URL instead of adding it again. |
| `nothing to commit` | Save your file. Check that it is inside this clone. Run `git status`. |
| My commit is missing on GitHub | Push your branch. Then select that branch on GitHub. |
| My file is missing on `main` | Check your work branch. It reaches the cohort default branch only after review and merge. |
| My PR targets my own fork | Change the PR base repository to `StartwithDot/UI-UX`. |
| My PR includes another student's files | Stop before merging. Ask for help checking the branch and changed files. |
| My image is too large | Export a smaller image. Keep it readable and under 2 MB. |
| My image link is broken | Check the filename, letter case, extension, and relative path. |
| My Markdown file ends in `.md.txt` | Show file extensions in Finder or File Explorer. Rename it to end in `.md`. |
| My Figma link asks for access | Recheck link access and view permission. Test it again. |
| A push is rejected | Read the error. Check the remote and branch. Fetch updates and ask for help before combining unfamiliar changes. Do not force-push. |
| I edited the wrong file | Inspect the diff. Undo only the unintended edit. Ask for help if the file contains work you need. |
| I staged the wrong file | Unstage that file with the command below. Your working file stays on your computer. |

**Mac and Windows**

```bash
git restore --staged path/to/file
```

Replace `path/to/file` with the exact file path.

**If you committed on local `main` but have not pushed**

1. Create a work branch with the task ID at the current commit.

```bash
git switch -c ux1-week0-z0-5
```

2. Push that branch.
3. Open the PR from that branch.
4. Ask for help restoring local `main` safely before starting the next task.

Do not delete the commit or run a reset command you do not understand.

**If a merge conflict appears**

1. Read the error.
2. Run `git status`.
3. Ask the reviewer to compare the affected changes with you.
4. Agree on the final content.
5. Open the conflicted file.
6. Remove `<<<<<<<`, `=======`, and `>>>>>>>`.
7. Keep the agreed content.
8. Save the file.
9. Stage each resolved file by its exact path.
10. Run `git status` again.
11. Follow Git's printed instruction to complete the merge.
12. Review the result before pushing.

Images cannot be combined like text. Agree with the reviewer which image to keep.

If you need to stop a merge started by `git pull`, ask for help or use `git merge --abort` while that merge is still in progress. Do not use unrelated recovery commands.

**If you uploaded a secret or personal data**

Stop sharing the file. Tell the admin privately what happened. A later deletion does not remove earlier copies from Git history. Revoke any exposed credential through its provider.

**When asking in Discord**

Include:

- Your student code and task ID.
- The file path.
- The action or command you tried.
- The exact error text.
- A screenshot with private information removed.

**Check it worked:** On Mac or Windows, your files contain the intended content, `git status` shows no unresolved conflicts, and the PR contains only the intended work.

### 5.14 One-page cheat sheet

Use this after your first successful submission.

**Your folder**

```text
Design-Sprint-N/students/UX{n}/weekN/
```

**Your file rules**

| Keep | Leave out |
|---|---|
| Required `.md` files | `.fig` files |
| PNG/JPG under 2 MB each | Passwords and tokens |
| PDF under 10 MB each | Real names and participant details |
| View-only Figma link inside `.md` | Faces and unredacted personal data |
| Files explicitly required by code tasks | Changes to another student's folder |

Image names: lowercase, hyphens, no spaces, such as `r1-1-home-page.png`.

**Mac and Windows, first local setup**

Run each command separately. Replace uppercase placeholders.

```bash
git clone YOUR_FORK_HTTPS_URL
git remote -v
```

Run the remaining commands from inside the cloned repo:

```bash
git remote add upstream https://github.com/StartwithDot/UI-UX
git switch -c YOUR_WORK_BRANCH_WITH_TASK_ID
```

Use a branch name with your code, week, and task ID, such as `ux1-week0-z0-5`.

**Mac and Windows, each task**

```bash
git status
git diff
git add EXACT_FILE_PATH
git diff --cached
git status
git commit -m "TASK_ID short action"
git push -u origin YOUR_WORK_BRANCH_WITH_TASK_ID
```

Open new files and images yourself before staging them.

**Mac and Windows, before a new task**

Start with a clean working folder. Use the actual default branch if it is not `main`.

```bash
git status
git switch main
git pull upstream main
git push origin main
git switch -c YOUR_NEW_BRANCH_WITH_TASK_ID
```

**GitHub Desktop**

Clone your fork > create a branch with the task ID > save files > review changes > commit with task ID > publish or push > open PR.

**Web fallback**

Open fork > sync default branch > create a branch with the task ID > open your week folder > upload files > commit with task ID > open PR.

**Pull request**

Base: `StartwithDot/UI-UX`, cohort default branch.

Compare: your fork, your work branch.

Review the files. Start the title with the task ID. Wait for review. Do not squash task commits.

**Useful shortcuts**

| Action | Mac | Windows |
|---|---|---|
| Save | `Cmd+S` | `Ctrl+S` |
| Markdown preview in VS Code | `Cmd+Shift+V` | `Ctrl+Shift+V` |

**Stuck?**

Read the error. Check the path and branch. Ask in Discord with the task ID, command, error, and a safe screenshot.

**Check it worked:** On Mac or Windows, you can use this sheet to submit one task and find its pull request.

## 6. What to Commit

Use this checklist before every task pull request.

- [ ] I used my assigned code, `UX1` to `UX10`.
- [ ] My files are in the required locations inside my student folder; any authorised shared files follow the shared-folder rules.
- [ ] I followed the current week guide's exact filenames.
- [ ] I completed the task's “Done when” points.
- [ ] My task commit starts with the exact task ID.
- [ ] My commit contains only that task and its required supporting files.
- [ ] Each PNG or JPG is under 2 MB.
- [ ] Image names use lowercase letters, hyphens, and no spaces.
- [ ] Each PDF is under 10 MB.
- [ ] My design link is inside a Markdown file.
- [ ] My reviewer can open the design with view-only access.
- [ ] My Markdown links and images work on GitHub.
- [ ] I included no `.fig` files, secrets, or personal data.
- [ ] I added the required AI log entry and AI footer when applicable.
- [ ] I left other students' folders and original templates unchanged.
- [ ] I changed `delivery/` only if I am the current team leader.
- [ ] My branch is visible on GitHub.
- [ ] My PR targets `StartwithDot/UI-UX`.
- [ ] My PR title starts with the task ID.
- [ ] I reviewed every changed file.
- [ ] I am waiting for review before merging.

For your first submission, follow week 0 tasks `Z0.4`, `Z0.5`, and `Z0.6` in order. Use that week's exact required files and commit messages.
