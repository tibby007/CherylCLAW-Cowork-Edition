# CherylCLAW Cowork Edition

**A Claude-native autonomous EA system with 8 AI specialists — built for the Claude desktop Cowork environment.**

Created by Cheryl Tibbs | AI Marvels | EmergeStack Development Company

---

## What This Is

CherylCLAW Cowork Edition gives you a fully operational AI Executive Assistant team running inside Claude desktop. One orchestrating EA. Eight specialized agents. All customized to YOUR business through a guided onboarding interview.

No servers. No coding. No n8n. Just Claude doing real work.

---

## The Agent Team

| Agent | What It Does |
|-------|-------------|
| EA Orchestrator | Receives every request, routes to the right specialist, synthesizes outputs |
| Content Agent | Writes in your voice — posts, articles, scripts, copy |
| Research Agent | Web research, competitor intel, market trends |
| Communications Agent | Emails, follow-ups, client responses, proposals |
| Outreach Agent | Prospecting copy, connection requests, cold sequences |
| Meeting Agent | Prep briefs, agendas, summaries, action items |
| Business Intel Agent | Data analysis, pipeline reports, business snapshots |
| Client Onboarding Agent | Welcome sequences, onboarding flows, new client setup |

---

## How It Works

**Step 1 — Clone this repo**
```
git clone https://github.com/cheryltibbs/CherylCLAW-Cowork-Edition
```

**Step 2 — Point Cowork at the skills folder**
In Claude desktop, add the `skills/` folder from this repo as your skills directory.

**Step 3 — Run the onboarding skill first**
Tell Claude: *"Run the CherylCLAW onboarding"*

This launches a 15-20 minute guided interview. Answer every question honestly and completely. At the end, your custom soul files are written directly into your Cowork workspace. Every agent now knows your business, your voice, your clients, and your tools.

**Step 4 — Start using your team**
Tell Claude what you need. The EA Orchestrator handles the routing automatically.

---

## What Is Free vs. Gated

**This repo (free):**
- Full framework and folder structure
- All 8 agent skill definitions
- The onboarding interview flow
- Soul file templates showing the structure
- Setup and usage documentation

**Inside Cheryl's course (gated):**
- Cheryl's battle-tested soul prompts for each agent
- Advanced tool configurations (Blotato, Apollo, GHL, Instantly)
- The `.plugin` file for one-click installation
- Video walkthroughs for each agent
- Community access and live Q&A

Learn more at [aimarvelshub.com] ← add your course link

---

## Folder Structure

```
CherylCLAW-Cowork-Edition/
├── README.md                        ← you are here
├── SETUP.md                         ← detailed setup instructions
├── CLAUDE.md                        ← gets written by onboarding (do not edit manually)
├── skills/
│   ├── onboarding/
│   │   └── SKILL.md                 ← run this first — always
│   ├── ea-orchestrator/
│   │   └── SKILL.md
│   ├── content-agent/
│   │   └── SKILL.md
│   ├── research-agent/
│   │   └── SKILL.md
│   ├── communications-agent/
│   │   └── SKILL.md
│   ├── outreach-agent/
│   │   └── SKILL.md
│   ├── meeting-agent/
│   │   └── SKILL.md
│   ├── business-intel-agent/
│   │   └── SKILL.md
│   └── client-onboarding-agent/
│       └── SKILL.md
└── souls/
    ├── README.md                    ← explains soul architecture
    ├── ea-soul.md                   ← template (real soul written by onboarding)
    ├── content-soul.md
    ├── research-soul.md
    ├── communications-soul.md
    ├── outreach-soul.md
    ├── meeting-soul.md
    ├── business-intel-soul.md
    └── client-onboarding-soul.md
```

---

## The Soul Architecture

Every agent in CherylCLAW has a soul — a personality and operating context file that tells it who you are, how you work, and what it is responsible for.

The onboarding skill generates your souls from scratch based on your interview answers. After onboarding, you can open any soul file in the `souls/` folder, read exactly what your agent knows about you, and edit it directly if anything needs adjusting.

This transparency is intentional. You should always know what your AI team knows about you.

---

## About Cheryl Tibbs

Cheryl Tibbs is an international speaker, AI automation trainer, and multi-business founder based in Douglasville, GA.

- **Commercial Capital Connect** — business finance marketplace
- **AI Marvels** — AI automation agency
- **EmergeStack Development Company** — custom AI automation builds

Member of BWAI, ABWA, BEFN, and AACFB. Credentialed by Google and Amazon for AI and Machine Learning.

---

## License

MIT — use it, fork it, teach with it. Credit Cheryl Tibbs and CherylCLAW.

*Coming soon: CherylCLAW VPS Edition — the always-on autonomous agent for advanced users.*
