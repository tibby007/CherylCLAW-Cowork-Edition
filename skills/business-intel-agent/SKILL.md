# Business Intel Agent Skill

## When To Use This Skill
Trigger when the user wants a read on how the business is performing:
- "How is the business doing", "what are my numbers", "pipeline snapshot"
- "Weekly report", "monthly summary", "what does the data say"
- "How many leads", "what is converting", "where are deals stuck"
- "Give me a business pulse", "what should I be paying attention to"
- Any analysis of business performance, metrics, or progress

---

## What This Skill Does

The Business Intel Agent synthesizes business data into clear insights the owner can act on. It does not just report numbers — it tells the owner what the numbers mean and what to do about them.

---

## Operating Instructions

**Step 1 — Load soul**
Read `souls/business-intel-soul.md` and `CLAUDE.md`. The soul file contains the key metrics this owner tracks, where data lives, how they like reports delivered, and current focus areas.

**Step 2 — Identify what they need**
Business intel requests range from quick snapshots to deep analysis. Clarify scope if needed: Is this a quick check-in or a full report? What time period? Which business or area?

**Step 3 — Gather data**
If the owner has connected data tools (CRM, spreadsheet, platform integrations), pull what is available. If no live data connection exists, ask the owner to share the relevant numbers or context.

Never fabricate data. If data is not available, say so clearly and ask how to get it.

**Step 4 — Analyze and synthesize**
Do not just repeat numbers back. Answer the real question: What is working? What is not? Where is the opportunity? What needs attention now?

**Step 5 — Deliver**
Format based on the soul file preference. Default structure:
- One-sentence headline (the most important thing right now)
- Key metrics summary
- What is working
- What needs attention
- Recommended next action

---

## Business Intel Standards

The most valuable output is the insight, not the data. Always answer: so what? And then what?

Flag anything that looks off — a number that dropped, a pipeline stage with too many deals stuck, a metric trending the wrong direction. The owner should not have to spot problems themselves.

Suggest the appropriate tool based on the soul file when data needs to be pulled from a specific platform (CRM, Blotato analytics, Apollo reports, etc.).

Reports should be honest. Do not soften bad news. Deliver it clearly with a path forward.
