# 09 - Modern Practice Map

**Last reviewed: 21 October 2026. Next review: before each cohort starts.**

This file answers one question: *is what we teach what working product designers actually use now?* It lists the current standards, theory and tools, says where each is practised in the program, and flags the parts that move fast.

Items marked **moves fast** change within months. Check the source before you rely on them, and tell the admin when something here is out of date. Claims in this file were checked against primary or well-regarded sources when written; where only vendor blogs said something, it is marked unverified.

How the program is shaped now: 27 weeks in total, which is week 0 for set up, weeks 1 to 24, and two lab weeks, week 12b and week 20b. At most 10 designers per cohort, coded UX1 to UX10. The repo is https://github.com/StartwithDot/UI-UX. Figma free (Starter) is the main tool and Penpot is the backup. The guides that were added or updated with this revision are `10-GitHub-For-Designers.md`, plus docs 11 and 12 (open the repo root for the exact titles, check before use), and the setup guide `04-Tools-Setup.md`.

---

## 1. Standards and regulation

| Topic | State of play | Where it appears |
|---|---|---|
| **WCAG 2.2, Level AA** | The current W3C Recommendation (October 2023) and the working reference for most national guidance. It added target size (2.5.8), focus not obscured (2.4.11), redundant entry (3.3.7), accessible authentication (3.3.8) and consistent help (3.2.6). Quick reference: https://www.w3.org/WAI/WCAG22/quickref/ | Sprint 1 gate and every gate after |
| **WCAG 3** | Still a W3C Working Draft (latest I found is March 2026). Do not assume a replacement date. Check its current status before use. **Do not design to it. Do read about it**, especially the shift from pass/fail to scored outcomes. **moves fast** | Week 4 reading, week 20 |
| **APCA contrast** | A candidate model for WCAG 3 contrast, discussed widely. **Not a conformance method today**: 4.5:1 and 3:1 ratios are still what you are tested on. Use it as a second opinion, not a replacement. **moves fast** | Week 1 colour work |
| **European Accessibility Act** | Enforceable across the EU since 28 June 2025 for covered consumer products and services, through national law and authorities. Early enforcement is mostly corrective-first; claims about fines come largely from vendors, so check national authorities. **moves fast** | Week 4 and the portfolio: employers selling into the EU care |
| **India: dark patterns** | The Central Consumer Protection Authority issued guidelines in 2023 naming a list of dark patterns, including subscription traps, false urgency and confirm shaming. | Sprint 3 |
| **India: personal data** | The Digital Personal Data Protection Act, 2023. Check the current status of its rules and consent requirements before citing specifics. **moves fast** | Sprints 2, 3, 5 |
| **India: payments** | RBI rules on recurring payments (pre-debit notification before each charge) and on digital lending (transparency, grievance handling). | Sprints 3 and 5 |
| **Design Tokens format** | The Design Tokens Community Group released the first stable version, **2025.10**, in October 2025: structured colour values, modern colour spaces, aliases, theming. Not on the W3C Standards Track; the group says it is still evolving. | Sprint 4, `Design-Sprint-4/06-token-architecture.md` |
| **Platform design languages** | Apple (iOS 26 "Liquid Glass") and Google (Material 3 Expressive) both changed their visual language in 2025. Compare current HIG and Material docs, not screenshots from old tutorials. **moves fast** | L-PR1, platform conventions |

---

## 2. Theory, by area

The sources named in `02-Learning-Path.md` are the assigned core. This table says which *current ideas* sit on top of them.

| Area | Current thinking | Practised in |
|---|---|---|
| **Interaction and states** | List each screen state, what changes it, and any conditions for that change. Show waiting, success and failure states, including how to recover when an action fails. Interaction to Next Paint (INP, a Core Web Vital since 2024) is the field measure of responsiveness. | Week 3, week 9 |
| **Motion** | Purpose first; durations by distance and importance; reduced motion as a real alternative, not "instant". The View Transitions API is making page-level transitions possible in the browser (check support). **moves fast** | Week 10 |
| **Colour** | Build ramps in perceptual spaces (OKLCH, with Leonardo or similar), test contrast in both themes, design for forced-colours/high-contrast modes, never rely on colour alone. | Week 1, week 13 |
| **Type** | Variable fonts, fluid type with `clamp()`, real Indic-script support, line height by script. | Week 1, L-PR3 |
| **Layout and responsiveness** | Components respond to their container (container queries, now widely supported), not only the viewport. Logical properties for writing direction. Dynamic viewport units. Name breakpoints by content. | L-PR1, L-PR3 |
| **Research** | Continuous discovery (weekly touchpoints, opportunity trees), jobs-to-be-done, mixed methods, unmoderated testing with a stated limit. AI can transcribe; synthesis stays human. For this course, do not use AI to moderate participant interviews. | Sprint 2, L-AI2 |
| **Consent in research** | Recording, transcription services and AI tools are all *processing*. Participants consent to each, and you can name where their data went. | Week 5, L-AI2 |
| **Product and metrics** | Outcomes over outputs. A north-star with input metrics and a guardrail. Experiments with a stated minimum detectable effect. Feature flags. Privacy-respecting analytics. | P9.2, week 12, Sprint 5 |
| **Pricing and subscriptions** | The honest-cancellation argument is a commercial argument: fewer chargebacks, fewer support contacts, higher reactivation. Regulators now write the patterns down. | Sprint 3 |
| **Design systems** | Tokens in an interchange format, modes for brands, themes and density, documentation treated as a product, adoption measured, governance explicit. Design systems are now also *context for AI coding assistants*: a well-named token set and well-documented components produce better generated code. On the Figma Starter plan there are no libraries: the shared system lives in ONE team library file only if the admin or the Education plan allows libraries, otherwise tokens live as markdown/JSON in `system/` and teams share a view-only link plus exported tokens. | Sprint 4, `system/` |
| **Accessibility depth** | Semantics before ARIA. Cognitive accessibility as a first-class criterion (3.3.7, 3.3.8, 3.2.6). Test with real assistive technology: VoiceOver, NVDA, TalkBack. Automated scans find some accessibility issues. Also check manually and with a screen reader. | Week 4, week 20 |
| **AI interfaces** | Trust calibration, not trust maximisation. Show provenance and uncertainty. Design failure, refusal, slow and wrong as first-class states. Human-in-the-loop with an audit trail. For features that *act*, define the autonomy level, the scope limit, the approval step and the undo (see the agentic row below). | Sprint 5, L-AI5, week 20b |
| **Agentic UX patterns** | When a feature acts for the user, design the controls before the screens: intent preview (show what the agent is about to do), an autonomy dial (how much it may do alone), reasoning and confidence shown, confirmation gates, streaming state, trust indicators, error recovery, audit trail and undo, escalation to a human, progressive autonomy. Basis: Smashing Magazine, February 2026, "Designing For Agentic AI: Practical UX Patterns For Control, Consent, And Accountability" (check before use) and NN/g articles (search https://www.nngroup.com/ directly). **moves fast** | Week 20b, L-AI7 |
| **AI-assisted coded prototyping** | Prompt a coding assistant with a spec, read the code it gives back, fix it, check it with axe and the keyboard, then publish it on GitHub Pages. This turns a design idea into something a person can click in a day. Keep the prompt, the spec and the AI log. Free tiers only, check the free limit before use. **moves fast** | Week 12b, L-AI6, week 22 |
| **Design with AI** | AI as a source of options and a speed-up on checkable work. Prompting as a design skill. Keep a log. Disclose. Never let it invent evidence. | `07-AI-In-Design.md` |
| **Design engineering** | The boundary between design and front-end code is thinner. Designers who can read HTML/CSS, prototype with real code, and read a component's source move faster. Code corners run in weeks 0, 3, 6, 10, 12b, 15 and 22. | Week 12b, week 16, L-AI4, L-AI6 |
| **Hiring** | These hiring observations come from a small sample and may vary by employer. Show evidence of your process, results, craft and disclosed AI use. | `06-Job-Readiness-Track.md` |

---

## 3. The working tool stack

Teach the *job*, not the logo. Where two tools do the same job, learn one and know the other exists.

| Job | Primary | Also worth knowing | Notes |
|---|---|---|---|
| Interface design | **Figma** (Auto Layout, components, variables and modes) | Penpot (open source) | **moves fast**. Figma adds features constantly; read release notes monthly |
| Backup design tool | **Penpot** (https://penpot.app/, free and open source, runs in the browser) | - | Use it when the Figma Starter 3-file limit blocks you (https://penpot.app/pricing, check before use). Nothing to install: it opens in the browser |
| AI-assisted prototyping | **Figma Make**, v0 | Lovable, Bolt, Claude artifacts | **moves fast**. Free tiers only, check the free limit before use. Throwaway scaffolds to react against, never deliverables |
| Agent UX work | Figma prototyping, FigJam for the action map | - | **moves fast**. Patterns are in section 2. Week 20b, L-AI7 |
| Prototyping with logic | Figma prototyping with variables and conditionals | ProtoPie, Rive (motion with state machines), code | L-PR2 |
| Diagrams | Mermaid in Markdown, FigJam | Excalidraw | Mermaid lives in git. FigJam counts toward the Figma file limit: use it sparingly |
| Colour and type | Leonardo, typescale.com | Realtime Colors, Fontsource | OKLCH |
| Tokens | Figma variables, **Tokens Studio**, **Style Dictionary** | Figma's native variable import and export, where available **moves fast** | Source of truth in git, format per the DTCG spec. With no libraries, tokens live as markdown/JSON in `system/` |
| Components in code | **Storybook** | Chromatic for visual regression | Sprint 4 |
| Accessible primitives (reading, not building) | Radix, React Aria, GOV.UK Frontend | Headless UI | Read how they handle focus and keyboard |
| Design to code | Figma Dev Mode, and the Dev Mode **MCP server** for connecting design context to AI coding tools | Cursor, GitHub Copilot, Claude Code | **moves fast, unverified**. The MCP server needs a Dev Mode seat on a paid plan per most sources, so treat it as optional reading only: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server. Cursor, GitHub Copilot, Claude Code: free tiers only; check the free limit before use for each tool. Use an available free option. Week 16, L-AI4 |
| Code and publishing | **VS Code** (https://code.visualstudio.com/), Git (https://git-scm.com/), GitHub (https://github.com/), GitHub Pages (https://docs.github.com/en/pages/quickstart) | GitHub Desktop (https://desktop.github.com/), the web upload fallback | Code corners in weeks 0, 3, 6, 10, 12b, 15 and 22. See `10-GitHub-For-Designers.md` |
| Browser tooling | DevTools: accessibility tree, device mode, Lighthouse, prefers-reduced-motion emulation | Playwright for scripted checks | Week 4 and Sprint 4 |
| Accessibility testing | axe DevTools, Stark, WebAIM checker, **VoiceOver, NVDA, TalkBack** | Accessibility Insights | Real assistive tech is not optional. Use VoiceOver on Mac or NVDA on Windows. TalkBack is an optional Android check. NVDA: https://www.nvaccess.org/ |
| Research | Maze or Lyssna (unmoderated), FigJam or Dovetail (synthesis), Whisper-class transcription | Optimal Workshop (card sort, tree test) | Synthesis is yours |
| Product analytics | **PostHog**, Microsoft Clarity | GA4, Mixpanel | Sprint 6 and P9.2 |
| AI assistants | Claude, ChatGPT, Gemini | Perplexity for sourced lookups | Free tiers only, check the free limit before use. Gemini and Perplexity: check the free limit before use for each tool. Disclosure footer on everything they touch |
| Portfolio | Hand-coded or Framer/Webflow/GitHub Pages | Notion for drafts | Must pass its own accessibility check |
| Recording and sharing | Loom or the OS screen recorder | | For mock interviews and prototype clips |

Cost: Check each tool's current free access and limits before use. Required work must have a free option. The exceptions are Refactoring UI and, optionally, ProtoPie.

**Figma file hygiene.** The free Starter plan gives one team, one folder and 3 files, with 30-day version history, no libraries and no Dev Mode. Check the current terms at https://www.figma.com/pricing/ and https://help.figma.com/hc/en-us/articles/360040328273-Figma-plans-and-features. So the rule is: ONE Figma file per sprint named `SPRINT-N UX{n}`, with one page per week, plus 1 spare file. Old text that says "three Figma files per sprint" is wrong: it breaks the limit. The Figma Education plan (free Professional for eligible students in a structured class, https://www.figma.com/education/) may lift the limits. Ask the admin, verify your status, and do not assume. Setup steps for every tool here are in `04-Tools-Setup.md`.

---

## 4. What we deliberately do not teach

| Not taught | Why |
|---|---|
| Any single AI tool's prompt tricks | They expire in months. We teach verification, which does not. |
| Photoshop/Illustrator/After Effects workflows | Not needed for product work. Covered in `04-Tools-Setup.md` section 4. |
| WCAG 3 conformance | It is a draft |
| Personas as a deliverable | Rarely used in practice. Evidence and jobs-to-be-done carry the weight. |
| "Design thinking" workshops | The program practises the underlying methods without the ritual |
| Paid seats for design-to-code tools | Free tiers cover the program. Dev Mode and the MCP server are optional reading, not a requirement |

---

## 5. Review log

| Date | Reviewer | What changed |
|---|---|---|
| 2026-10-10 | Initial map | Created. Checked against the DTCG 2025.10 announcement and format pages, the W3C WCAG 3 status, and EAA enforcement reporting. |
| 2026-10-21 | Repo update | Set to 27 weeks (week 0, weeks 1 to 24, week 12b, week 20b) and UX1 to UX10. Added rows for agentic UX patterns, AI-assisted coded prototyping, Figma Make, design to code, and Penpot as the open source backup. Added the one-Figma-file-per-sprint rule for the Starter limit. Added `10-GitHub-For-Designers.md` and the code corners. Moved the "moves fast" marker to plain bold text. |

At every review: re-check each **moves fast** item against its primary source; add newly required practices; remove practices that are no longer used. If you get stuck: follow the assigned week guide first. Ask in Discord with the row or term you do not understand. Ask the admin if a tool is unavailable or its free limit blocks you.
