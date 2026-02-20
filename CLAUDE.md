# GTM-consulting

A comprehensive Claude Code project for operationalizing Go-To-Market strategy and execution for consulting clients. Built on Cinzia's proprietary GTM frameworks for deep tech and B2B startups.

## Project Purpose

This project provides a complete GTM consulting toolkit — a system of interconnected agents, skills, and reference documents that help you guide clients through every stage of GTM strategy and execution. Each component can be used independently or as part of an end-to-end engagement.

## How to Use

### For a New Client Engagement (Recommended Flow)
1. **Always start with the Client Intake** — use the `client-intake` skill. This runs a structured 5-round discovery interview that asks about the business, customers, product, competition, current GTM, goals, and constraints. No analysis happens until the interview is complete.
2. After the intake produces a **Client Brief**, review the recommended engagement scope together.
3. Then proceed to the relevant skills in priority order.

To start, just say: *"I have a new client to analyze"* or *"Let's do a client intake"*

### For Specific Deliverables (If You Already Know the Business)
- **Market Analysis** → Use the `market-analyzer` skill
- **Customer Profiling** → Use the `icp-profiler` skill
- **Competitive Landscape** → Use the `competitor-mapper` skill (includes H1 hero scraping, features analysis, verticals mapping)
- **Positioning Statement** → Use the `positioning-builder` skill (April Dunford method)
- **Pricing Strategy** → Use the `pricing-strategist` skill
- **Growth Motions & Channels** → Use the `growth-channel-selector` skill (includes growth motion recommendation + "double down" logic)
- **Pipeline Model** → Use the `pipeline-architect` skill (includes revenue modeling, scenario analysis, CRM validation)
- **Funnel Visualization** → Use the `funnel-visualizer` skill (generates an HTML funnel diagram)
- **Sales Qualification** → Use the `sales-qualification` skill (MEDDICC)
- **Launch Plan** → Use the `launch-planner` skill
- **Tech Stack & Integrations** → Use the `gtm-engineering-stack` skill (includes "double down on what works" + HubSpot/CRM integration)
- **Client-Ready Documents** → Use the `gtm-deliverables` skill (generates individual docs per GTM question)
- **SEO & GEO** → Use the `seo-geo` skill (SEO audit, AI search optimization, schema markup, GEO principles)
- **B2B Content Writing** → Use the `b2b-writer` skill (blog posts, LinkedIn, sales emails, event scripts — matches client voice)
- **Lead Research** → Use the `lead-researcher` skill (prospect research, account intelligence, buying signals)
- **Sales Outreach** → Use the `sales-outreach` skill (cold emails, LinkedIn messages, follow-up sequences — AIDA, PAS, BAB)
- **Call Prep** → Use the `call-prep` skill (pre-meeting research, talking points, objection handling, MEDDICC)

## Architecture

```
GTM-consulting/
├── CLAUDE.md                  ← You are here
├── agents/                    ← AI agent definitions for complex workflows
│   ├── gtm-strategy-agent.md  ← Full GTM strategy orchestrator
│   ├── market-research-agent.md ← Deep market research & sizing
│   └── sales-enablement-agent.md ← Sales process & enablement
├── skills/                    ← Modular skills for specific GTM tasks
│   ├── client-intake/         ← START HERE — discovery interview
│   ├── market-analyzer/
│   ├── icp-profiler/
│   ├── competitor-mapper/     ← Enhanced: H1 hero scraping, features, verticals
│   ├── positioning-builder/
│   ├── pricing-strategist/
│   ├── growth-channel-selector/ ← Enhanced: growth motion reco + double-down logic
│   ├── pipeline-architect/    ← Enhanced: revenue modeling, scenarios, CRM integration
│   ├── sales-qualification/
│   ├── launch-planner/
│   ├── gtm-engineering-stack/ ← Enhanced: double-down logic + CRM integrations
│   ├── funnel-visualizer/     ← NEW: visual funnel generation (HTML)
│   ├── gtm-deliverables/     ← NEW: individual docs per GTM question
│   ├── seo-geo/              ← SEO & GEO (AI search optimization)
│   ├── b2b-writer/           ← B2B content writing (matches client voice)
│   ├── lead-researcher/      ← Prospect research & account intelligence
│   ├── sales-outreach/       ← Cold emails, LinkedIn, sequences (AIDA/PAS/BAB)
│   └── call-prep/            ← Pre-meeting research, talking points, objections
└── docs/                      ← Reference documents and playbooks
    ├── frameworks/            ← Core GTM frameworks
    ├── templates/             ← Client-ready templates
    └── playbooks/             ← Step-by-step engagement guides
```

## Core Philosophy

Based on Cinzia's consulting methodology:
- **Build pipeline more quickly and predictably**
- Focus on the 6 fundamental GTM decisions: Market, Customer Profile, Product, Pricing, Positioning, Growth
- Deep tech and B2B focus with emphasis on MEDDICC sales qualification
- Data-driven market validation (scoring, bottom-up sizing)
- Actionable frameworks over theoretical models
