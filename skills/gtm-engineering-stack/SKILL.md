---
name: gtm-engineering-stack
description: Recommend and design the GTM tech stack organized by growth motion — Data & Enrichment, Inbound/MLG, Sales-Led/Outbound, PLG, and Cross-Motion Ops. Practical tool recommendations for each layer.
---

# GTM Engineering Stack

Help clients build the right technical infrastructure to power their go-to-market execution.

## When to Use
- Client needs to build or optimize their GTM tech stack
- Transitioning between growth motions (e.g., MLG → SLG)
- Tech stack is bloated or disconnected
- Need to automate GTM workflows
- Starting from scratch (early-stage)

## GTM Engineering Stack by Growth Motion

### 1. Data & Enrichment Layer (Foundation for All Motions)

Applicable across all three motions. Tools for building a clean, enriched view of prospects and customers.

| Category | Tools |
|----------|-------|
| CRM | HubSpot, Salesforce |
| Data Enrichment | Clay, Clearbit, Apollo |
| Reverse IP Identification | RB2B, Leadfeeder |
| Data Warehouse | BigQuery, Snowflake (if connecting product usage data) |

### 2. Inbound / MLG Motion

| Category | Tools |
|----------|-------|
| Content & SEO | CMS, SEO tools (Ahrefs, Semrush, Surfer SEO), AI writing assistants |
| Lead Capture & Conversion | Landing page builders (Unbounce, Webflow), forms (Typeform, HubSpot Forms), chatbots (Intercom, Drift) |
| Marketing Automation & Nurture | Email/lifecycle platforms (HubSpot, ActiveCampaign, Customer.io), marketing automation for lead scoring and nurture sequences |
| Paid & Distribution | Ad platforms (Google Ads, LinkedIn Ads, Meta), retargeting (metadata.io), social scheduling (Buffer, Taplio for LinkedIn) |
| Attribution & Analytics | Web analytics (GA4, Plausible), attribution (HockeyStack, Dreamdata), dashboards (Looker, Metabase) |

### 3. Sales-Led / Outbound Motion

| Category | Tools |
|----------|-------|
| Prospecting & List Building | Apollo, Clay, LinkedIn Sales Navigator, ZoomInfo |
| Outbound Sequencing | Multi-channel outreach tools (Instantly, Smartlead, Apollo Sequences, Outreach, Salesloft) for automated email + LinkedIn cadences |
| Conversations & Demos | Meeting scheduling (Calendly, Chili Piper), call recording and intelligence (Apollo, Gong, Chorus), video demos (Loom, Navattic) |
| CRM & Pipeline Management | Deal tracking, pipeline stages, forecasting — all inside HubSpot or Salesforce, with automation |
| Sales Enablement | Proposal and contract tools (PandaDoc, DocuSign), battle cards, competitive intel |

### 4. PLG Motion

| Category | Tools |
|----------|-------|
| Product Analytics & PQL Detection | Track user behavior to identify product-qualified leads (Amplitude, Mixpanel, PostHog, Segment) |
| Onboarding & Activation | In-app guidance (Appcues, Userflow, Chameleon), email triggers based on product events (Customer.io, Loops) |
| Billing & Self-Serve Revenue | Subscription management (Stripe, Paddle, Orb), paywall and plan management |
| Reverse Trial / Freemium Infrastructure | Feature flagging (LaunchDarkly, PostHog), usage limits and upgrade prompts |
| Product-to-Sales Handoff | Connect product analytics to CRM (Segment → HubSpot, or custom Zapier/n8n workflows) |

### 5. Cross-Motion Ops & Automation

The glue that connects everything.

| Category | Tools |
|----------|-------|
| Workflow Automation | Zapier, Make, n8n |
| Reverse ETL | Census, Hightouch |
| Internal Alerting | Slack notifications for key signals |
| AI Agents | Data processing and personalization (Clay, custom scripts) |

## "Double Down on What Works" Logic

The most impactful stack recommendations come from understanding what's already producing results for the client. This is captured during the client intake (Round 4: Current GTM).

### Assessment Framework

For each tool/channel the client currently uses:

| Question | If Yes → Recommendation |
|----------|------------------------|
| Is this generating leads? | Invest more: add automation, scale budget, expand content |
| Is this converting leads to customers? | Optimize: add tracking, improve workflows, A/B test |
| Is this tool being used to <50% capacity? | Train and activate: workshops, playbooks, automation setup |
| Is this tool redundant with another? | Consolidate: migrate to one tool, reduce costs |
| Is a key capability missing? | Add: recommend specific tool to fill the gap |

### Recommendation Priority
1. **First**: Maximize tools that are already working (highest ROI)
2. **Second**: Fix underutilized tools (training, setup, workflows)
3. **Third**: Add missing capabilities for the primary motion
4. **Fourth**: Remove redundant tools (cost savings)
5. **Last**: Add new experimental tools

## CRM Integration Guide (HubSpot, Salesforce, etc.)

### HubSpot Integration
If the client uses HubSpot, the GTM consulting framework can connect to HubSpot data for:

**What to Pull from HubSpot:**
- Contact and company data (for ICP validation)
- Deal pipeline stages and conversion rates (for pipeline modeling)
- Marketing email performance (for channel effectiveness)
- Lead sources and attribution (for channel scoring)
- Campaign ROI data (for budget allocation)
- Custom properties (for qualification scoring)

**How to Connect:**
- HubSpot MCP connector (if available in Claude Code) for direct data access
- HubSpot API via custom scripts for automated reporting
- HubSpot dashboards for ongoing monitoring
- Export CSVs for one-time analysis

**What to Push Back to HubSpot:**
- Updated ICP criteria as contact properties
- Lead scoring rules based on MEDDICC qualification
- Pipeline stage definitions and exit criteria
- Automated workflows based on GTM recommendations

### Salesforce Integration
Similar to HubSpot, pull pipeline data, lead sources, opportunity stages, and rep productivity metrics.

### Other Tool Integrations
| Tool Category | Integration Use Case |
|---|---|
| Analytics (GA4, Amplitude, PostHog) | Product usage data for PLG funnel, website conversion data |
| Email (HubSpot, ActiveCampaign) | Campaign performance for channel scoring |
| Outbound (Apollo, Outreach) | Outbound pipeline metrics and response rates |
| Advertising (LinkedIn, Google Ads) | Paid channel performance and CAC data |
| Support (Intercom, Zendesk) | Churn signals, feature requests for product roadmap |

## Key Principle

Start with the minimum stack for your primary motion — CRM + one tool per functional category. The biggest trap is buying 15 tools before you've talked to 50 prospects. GTM engineering should automate what you've already proven works manually. **Always invest in what's already generating results before adding new tools.**

## Workflow

1. **Identify primary growth motion** (MLG, SLG, PLG, or Hybrid)
2. **Audit current stack** — what exists? what's working? what's underutilized?
3. **Apply "Double Down" logic** — prioritize investment in proven tools
4. **Map gaps** against the stack framework
5. **Recommend tools** per layer, prioritized by impact
6. **Design integrations** — how tools connect to each other (especially CRM)
7. **Plan implementation** — phased rollout, not big bang
8. **Connect to CRM** — pull data for validation, push recommendations back
9. **Set up dashboards** — unified view of pipeline and performance

## Output Artifacts
- Current stack audit **with "working / underutilized / redundant" classification**
- **"Double down" recommendations** (what to invest more in)
- Recommended stack by motion (with specific tools)
- **CRM integration plan** (what to pull, what to push, how to connect)
- Integration architecture diagram
- Implementation roadmap (phased)
- Budget estimate for stack
- Dashboard and reporting design
