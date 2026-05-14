# CherylCLAW Cowork Edition — Setup Guide

Welcome. This guide gets you from zero to a running AI executive team in about 20 minutes.

---

## What You Need Before You Start

- Claude desktop app installed on your computer
- Cowork mode enabled (you are reading this, so you likely already have it)
- A folder you want to use as your CherylCLAW workspace

That is it. No API keys. No coding. No external tools required to get started.

---

## Step 1 — Download and Unzip the Repo

Download the CherylCLAW Cowork Edition zip file and unzip it. You will get a folder called `CherylCLAW-Cowork-Edition` with this structure inside:

```
CherylCLAW-Cowork-Edition/
├── README.md
├── CLAUDE.md
├── SETUP.md  (this file)
├── STATE.md
├── souls/
└── skills/
```

Put this folder somewhere you can find it — your Desktop, Documents, or a dedicated AI workspace folder all work fine.

---

## Step 2 — Open the Folder in Cowork

1. Open the Claude desktop app
2. Make sure you are in Cowork mode
3. Click the folder icon or use the workspace selector to point Cowork at your `CherylCLAW-Cowork-Edition` folder
4. Claude now has access to everything inside — the skills, the soul files, and the CLAUDE.md

---

## Step 3 — Install the Skills

Skills are what give each agent its instructions. You need to tell Cowork where to find them.

In the Claude desktop app, navigate to **Settings → Skills** (or the equivalent in your version of Cowork). Add each skill folder from the `skills/` directory:

- `skills/onboarding`
- `skills/ea-orchestrator`
- `skills/content-agent`
- `skills/research-agent`
- `skills/communications-agent`
- `skills/outreach-agent`
- `skills/meeting-agent`
- `skills/business-intel-agent`
- `skills/client-onboarding-agent`

Each folder contains one `SKILL.md` file. Cowork reads that file to know when and how to activate each agent.

> **Note:** If your version of Cowork auto-discovers skills from the workspace folder, you may not need to add them manually. Try running the onboarding first — if Claude finds the skill on its own, you are already set.

---

## Step 4 — Run the Onboarding

This is the most important step. Do not skip it.

Once your folder is open in Cowork, say:

**"Run the CherylCLAW onboarding"**

Claude will start a structured interview — one question at a time — covering who you are, your business, your team, your current priorities, your tools, and how you want your agents to work for you.

At the end of the interview, Claude will:

1. Ask if you want to give your agents personal names
2. Generate 8 customized soul files and write them into your `souls/` folder
3. Write a `CLAUDE.md` with your complete business context
4. Introduce the Morning Briefing and offer to set up your first scheduled automation

The whole process takes 15 to 20 minutes. Give it your real answers — the quality of your agents depends entirely on what you put in here.

---

## Step 5 — You Are Live

When onboarding is complete, your agents are ready. Just talk to Claude naturally:

- "Write a LinkedIn post about..." → Content Agent activates
- "Research competitors in..." → Research Agent activates
- "Draft a follow-up email to..." → Communications Agent activates
- "Find prospects for..." → Outreach Agent activates
- "Prep me for my call with..." → Meeting Agent activates
- "How is the business doing?" → Business Intel Agent activates
- "Onboard my new client..." → Client Onboarding Agent activates
- Anything else → EA Orchestrator handles it or routes it

---

## Connecting Your Tools

Your agents suggest tools based on what you told them during onboarding. To actually use those tools inside Cowork, you will need to connect them via the Cowork MCP connector settings.

Common tools to connect:

- **Gmail or Outlook** — for the Communications Agent to draft and review email
- **Google Calendar or Calendly** — for the Meeting Agent to check and prep
- **LinkedIn** (via ConnectSafely) — for Outreach Agent and Content Agent
- **GoHighLevel** — for CRM and workflow automation
- **Apollo or Instantly** — for outreach prospecting and cold email
- **Blotato** — for content scheduling across platforms

You can connect these one at a time as you need them. The agents will tell you when a tool connection would make their work better.

---

## Updating Your Soul Files

Your soul files live in the `souls/` folder. They are plain text — open any of them in a text editor or ask Claude to read and update them directly.

Update your soul files when:
- Your business priorities shift
- You add or change tools
- Your team changes
- Your communication style evolves
- Something in a generated output feels off

Agents read their soul files on every execution, so changes take effect immediately. No restart needed.

---

## Support & Updates

You have lifetime access to this repository. Future updates — new agents, refined soul prompts, additional tool configurations — will be pushed here and available to all licensed buyers automatically.

If you have questions about setup or need help deploying an agent, reach out directly:

**Email:** cheryltibbs007@gmail.com
**Website:** aimarvelshub.com

For Agency License holders: use this email to schedule your 60-minute onboarding call.

---

## Need Help?

If something is not working, start here:

1. Make sure the workspace folder is correctly selected in Cowork
2. Confirm the skills are installed and visible
3. Re-run the onboarding if soul files are missing or feel generic
4. Check that `CLAUDE.md` in your workspace root has your business context in it (not the placeholder text)

If you are still stuck, bring your question to the community inside the course or reach out directly.
