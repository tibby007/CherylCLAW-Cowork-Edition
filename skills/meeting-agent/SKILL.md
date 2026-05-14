# Meeting Agent Skill

## When To Use This Skill
Trigger when the user needs anything meeting-related:
- "Prep me for my call with...", "I have a meeting with..."
- "Summarize this call", "action items from...", "follow up from our meeting"
- "Who is [person]", "what do I know about [company]"
- "Draft an agenda for...", "what should I cover in this meeting"
- Any transcript, notes, or recording needing to be processed

---

## What This Skill Does

The Meeting Agent prepares the owner before meetings and captures value after them. It researches who they are meeting with, builds prep briefs, drafts agendas, processes notes or transcripts into action items, and drafts follow-up communications.

---

## Operating Instructions

**Step 1 — Load soul**
Read `souls/meeting-soul.md` and `CLAUDE.md`. The soul file contains the owner's meeting prep preferences, recurring meeting types, key people context, and how they like action items handled.

**Step 2 — Identify the task**
Is this pre-meeting (prep and agenda) or post-meeting (summary and follow-up)? The two modes are different.

**Pre-meeting mode:**
- Research the person or company being met with if name/company is provided
- Summarize what is known about them — role, background, relevant context
- Surface any prior interactions mentioned in CLAUDE.md or the soul file
- Draft a suggested agenda based on the meeting purpose
- Suggest 2-3 key questions the owner might want to ask
- Deliver a concise prep brief — not a novel

**Post-meeting mode:**
- Process any notes, transcript, or recording summary provided
- Extract clear action items with owners and deadlines if mentioned
- Identify any commitments the owner made
- Draft a follow-up email to the other party if needed
- Suggest any CRM updates based on what was discussed

**Step 3 — Deliver in the right format**
The soul file specifies how this owner likes meeting materials. Match it. If not specified, default to: short brief, bullet action items, one clear next step highlighted.

---

## Meeting Standards

Prep briefs should be scannable in under 2 minutes. If it takes longer, it is too long.

Action items must be specific: who does what by when. Vague action items are not action items.

Never make up information about a person or company being researched. If something cannot be verified, say so.

Suggest the follow-up draft immediately after delivering post-meeting summaries — the owner should not have to ask for it.
