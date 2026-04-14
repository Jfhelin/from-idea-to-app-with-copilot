# Facilitator Guide — From Idea to App with Copilot

This document is for the person running the workshop. Participants do not need to read this.

---

## Workshop Goal

Help non-technical participants experience the value of GitHub Copilot by building a small, working application entirely through conversation — with no coding, no setup, and no prior knowledge required.

The outcome is not a production app. The outcome is a feeling of confidence: *I described what I wanted, and it got built in front of me.*

---

## Target Audience

This workshop is designed for:

- Microsoft ATU (Account Technology Unit) team members
- Business Development Managers (BDMs)
- Technical specialists who engage with customers but do not write code day-to-day
- Anyone who wants to understand Copilot's value without a developer background

### What changed from the old workshop

The previous version of this workshop was built for developers and people comfortable with VS Code, terminal commands, repository workflows, and Copilot's more advanced features (agents, reusable prompts, MCP, model selection, design skills). It ran for 90 minutes and required significant prior familiarity with the tooling.

This version:
- Removes all setup friction and decision fatigue
- Provides pre-written prompts participants can paste in rather than compose
- Limits the app ideas to a curated short list — no blank-slate ideation required
- Removes all references to developers' concepts (branches, files, specs, terminals, models)
- Targets 45–60 minutes including discussion time
- Focuses entirely on the experience of describing → reviewing → improving

---

## Session Flow and Suggested Pacing

| Time | Activity | Step |
|------|----------|------|
| 0–5 min | Welcome, context-setting, reassurance ("no coding needed") | Intro |
| 5–15 min | Facilitator demo — show the finished app and how it was built | [Step 1](STEP-1-SEE-IT.md) |
| 15–30 min | Participants choose an idea and ask Copilot to build it | [Step 2](STEP-2-TRY-IT.md) |
| 30–45 min | Participants ask for improvements and iterate | [Step 3](STEP-3-REFINE-IT.md) |
| 45–60 min | Group share-out, reflection, and Q&A | Close |

Adjust timing based on group size. With more than 10 participants, pair people up so no one is stuck alone when Copilot needs guidance.

---

## Before the Session

- Confirm GitHub Copilot is enabled for each participant in VS Code
- Open Copilot Chat yourself and verify it responds as expected
- Pre-load [STEP-1-SEE-IT.md](STEP-1-SEE-IT.md) in VS Code Markdown preview so you can demo from it
- Have your demo app ready to show (you can build one in advance using Step 2's prompts)
- Test that the output from Step 2 prompts actually opens in a browser on the machines in the room

If participants cannot open Copilot Chat at the start, stop and resolve it before continuing. The session does not work without it.

---

## Opening the Session (First 5 Minutes)

Set the tone early. Say something like:

> "This is not a coding workshop. You are not going to write any code today. Your job is to describe what you want in plain English, look at what Copilot produces, and tell it what to change. That is the whole skill."

> "If you have ever told a colleague exactly what a report should look like, you already have the main skill needed here."

> "The goal by the end is that you feel like: I could use this tool tomorrow with a customer."

Avoid spending more than 2 minutes on how Copilot works technically. Getting into the tool is more valuable than explaining it.

---

## Helping Participants Who Get Stuck

### If Copilot produces something unexpected or confusing

Say: "That is a normal result. Now let us describe what we actually want and ask it to change that specific thing."

Do not try to explain why Copilot did what it did. Redirect to the refinement step.

### If a participant cannot describe what they want

Suggest they pick the KPI dashboard option from Step 2 — it is the most self-explanatory and requires the least imagination.

### If the app does not open in the browser

Ask the participant to tell Copilot: "The app is not opening. Can you make it work by just opening a file in the browser?"

If that does not resolve it within two exchanges, move to sharing your screen so the participant can continue observing alongside you.

### If a participant wants to go deeper

Note their enthusiasm and let them know there is a more advanced workshop for people who want to explore further. Do not try to cover agents, models, or MCP during this session — keep the group together.

---

## What to Avoid

The following concepts and tasks should not dominate this session. If a participant asks about them, acknowledge the question and offer to follow up separately rather than explaining during the workshop.

| Avoid | Why |
|-------|-----|
| Explaining how to use Git or clone a repository | Adds friction and confusion for non-technical participants |
| Switching between AI models | Adds decision fatigue and is not necessary to demonstrate value |
| Using or explaining "agent mode" by name | The term confuses non-developers; what matters is the conversation, not the mode |
| Opening or editing code files | Breaks the abstraction that "Copilot handles this" |
| Discussing how prompts work internally | Not relevant to the learning goal |
| Comparing Copilot to other AI tools | Risks turning the session into a debate rather than an experience |
| Running terminal commands | Participants do not need to see a terminal |
| Explaining what a repository is | Irrelevant to this audience at this stage |
| Requiring participants to invent an original idea | Adds cognitive load and stalls momentum |
| Discussing token limits, context windows, or model versions | Too technical; likely to create anxiety rather than confidence |

---

## Closing the Session

End with a short round of share-outs. Ask each participant (or pair):

> "What one thing did you build or change today?"

Then ask the group:

> "Where could you see this being useful in a customer conversation?"

This connects the experience to their actual day-to-day work and makes the session stick.

---

## After the Session

Point participants to the three step files for reference if they want to try this on their own:

- [Step 1 — See It](STEP-1-SEE-IT.md)
- [Step 2 — Try It](STEP-2-TRY-IT.md)
- [Step 3 — Refine It](STEP-3-REFINE-IT.md)

# Facilitator Guide — From Idea to App with Copilot

This document is for the person running the workshop. Participants do not need to read this.

---

## Workshop Goal

Help non-technical participants experience the value of GitHub Copilot by building a small, working application entirely through conversation — with no coding, no setup, and no prior knowledge required.

**Success = confidence**, not correctness:
> *“I described what I wanted, and it got built in front of me.”*

---

## Target Audience

- Microsoft ATU team members  
- Business Development Managers (BDMs)  
- Technical specialists who engage with customers but do not code day-to-day  
- Anyone curious about Copilot without a developer background  

### What changed from the old workshop

This version:
- Removes setup friction and decision fatigue  
- Uses **copy‑paste prompts** (no blank-page thinking)  
- Limits ideas to a short curated list  
- Avoids developer concepts (files, repos, terminals, models)  
- Fits a **45–60 minute** session  
- Focuses on **Describe → Review → Improve**

---

## Quick Facilitator Checklist (Do This First)

- [ ] Copilot Chat opens and responds on your machine  
- [ ] Participants can open Copilot Chat  
- [ ] You have a **working demo app** ready  
- [ ] You tested that apps can open in a browser on these machines  
- [ ] You have **STEP-1/2/3** open and ready to point to  

> If Copilot Chat does not work for participants, **stop and fix it first**.

---

## Session Flow (45–60 min)

| Time | Activity |
|------|----------|
| 0–5  | Welcome + reassurance (no coding needed) |
| 5–15 | **Demo** (you drive) |
| 15–30 | Participants build (Step 2) |
| 30–45 | Participants refine (Step 3) |
| 45–60 | Share-out + Q&A |

> With >10 participants: **pair people up**.

---

## Opening (First 3–5 Minutes)

Say this (or similar):

> “This is not a coding workshop. You will not write code.  
> Your job is to describe what you want, look at what comes back, and ask for changes.”

> “If you’ve ever told someone how you want a report or dashboard to look — you already have the skill.”

> “You’ll have something working within the first 10 minutes.”

---

## Demo Script (Keep it to ~3 minutes)

1. Open Copilot Chat  
2. Paste:

> "Build me a simple KPI dashboard for a sales team. Show total revenue, deals closed, average deal size, and top five customers. Use realistic sample data. Make it clean and easy to read. It should open in a browser with no setup."

3. Wait → then say:
   - “Notice: plain English, no technical steps”
4. Open the app (or show your prebuilt version)
5. Make one change live:

> “Add a search box and make the layout clearer.”

6. Stop. Do **not** over-explain.

Key line to repeat:
> “Describe → Review → Improve”

---

## Helping Participants (Fast Responses)

### If Copilot output is weird
Say:
> “Good — now let’s tell it exactly what to change.”

Avoid explaining *why* it happened.

---

### If they don’t know what to ask
Point to Step 2 prompts.  
Recommend **KPI dashboard** as the easiest.

---

### If the app does not open (common)

Have them paste:

> "The app is not opening. Please make it work by opening a file directly in the browser."

If still blocked after ~1 minute:
- Let them **pair with you** or watch your screen
- Keep momentum over perfection

---

### If someone goes too deep
Say:
> “Great question — we’ll cover that in an advanced session.”

Do **not** derail the group.

---

## What to Avoid (Strict)

- Git, cloning, repositories  
- Terminals or commands  
- Model switching or comparisons  
- “Agent mode”, MCP, prompt internals  
- Opening or editing code files  
- Long technical explanations  

If it doesn’t help them succeed in **5 minutes**, skip it.

---

## Keep the Energy Right

Your role is to:
- Keep people moving
- Reduce overthinking
- Normalize imperfect results

Say often:
> “Start simple — you can improve it.”

---

## Closing (Last 10–15 Minutes)

Ask each person/pair:

> “What did you build or improve?”

Then ask:

> “Where could this help in a customer conversation?”

End with:

> “You just turned an idea into something real — without coding.”

---

## After the Session

Point them to:

- Step 1 — See It  
- Step 2 — Try It  
- Step 3 — Refine It  

Encourage them to try **one small use case** in their own work within a week.

---

## Facilitator Tip (Most Important)

If something breaks:

👉 **Do not debug deeply. Move forward.**

This is a confidence workshop — not a technical one.