---
name: funnel-visualizer
description: Generate a visual marketing and sales funnel for the company being analyzed. Produces an HTML visualization showing funnel stages, conversion rates, volume at each stage, and revenue projections. Based on the GTM framework applied to the client's business.
---

# Funnel Visualizer

Create a visual funnel diagram for the client's business, connecting top-of-funnel awareness through to revenue. The funnel is specific to the client's growth motion and includes actual (or projected) numbers at each stage.

## When to Use
- After client intake is complete and you understand the business model
- When building a pipeline model and want a visual representation
- When presenting GTM strategy to stakeholders
- When identifying where the funnel leaks and needs optimization

## Funnel Structure by Growth Motion

### SLG (Sales-Led Growth) Funnel
```
Awareness (Website visitors, content consumers)
    ↓
Interest (Content downloads, webinar attendees)
    ↓
MQL (Marketing Qualified Lead — meets firmographic criteria)
    ↓
SQL (Sales Qualified Lead — BANT confirmed)
    ↓
Discovery (First meeting, pain confirmed)
    ↓
Proposal (Solution + pricing presented)
    ↓
Negotiation (Terms, procurement)
    ↓
Closed Won → Revenue
```

### PLG (Product-Led Growth) Funnel
```
Awareness (Website visitors, referrals)
    ↓
Signup (Free trial / freemium account created)
    ↓
Activation (Key onboarding milestone reached)
    ↓
PQL (Product Qualified Lead — usage threshold hit)
    ↓
Conversion (Paid plan or upgrade)
    ↓
Expansion (Upsell, more seats, higher tier)
    ↓
Revenue
```

### MLG (Marketing-Led Growth) Funnel
```
Awareness (SEO, ads, social, PR)
    ↓
Engagement (Blog reads, newsletter signups, social follows)
    ↓
Lead Capture (Gated content, webinar registration)
    ↓
MQL (Lead scoring threshold met)
    ↓
SQL (Sales accepts the lead)
    ↓
Opportunity (Active deal in pipeline)
    ↓
Closed Won → Revenue
```

### Hybrid Funnel
Combine stages from multiple motions. Most B2B SaaS companies run hybrid funnels (e.g., PLG for SMB + SLG for Enterprise).

## How to Generate the Funnel Visualization

Create an HTML file with an SVG or CSS-based funnel visualization. The funnel should include:

### Visual Requirements
1. **Funnel shape**: Trapezoid stages that narrow from top to bottom
2. **Stage labels**: Name of each funnel stage on the left
3. **Volume numbers**: Number of people/accounts at each stage on the right
4. **Conversion rates**: Percentage between each stage (shown as arrows or labels)
5. **Color coding**: Gradient from light (top) to dark (bottom), or use the client's brand colors
6. **Revenue outcome**: Final revenue number at the bottom
7. **Leakage indicators**: Show where the biggest drop-offs occur (red highlights)

### Data Inputs Needed
For each funnel stage, capture:
- Stage name
- Volume (number of leads/accounts/users)
- Conversion rate to next stage
- Average time in stage (optional)
- Key metric or KPI for that stage

### Template HTML Structure
Generate a single-file HTML with embedded CSS and JavaScript. Use:
- CSS trapezoid shapes or SVG paths for the funnel segments
- Responsive design so it works in presentations
- Clean typography (system fonts)
- Print-friendly layout
- Include a data table below the visual for exact numbers

## Workflow

1. **Determine growth motion** from client intake (SLG, PLG, MLG, Hybrid)
2. **Select funnel template** matching the motion
3. **Populate with data**: Use client's actual numbers if available, or industry benchmarks
4. **Calculate conversions**: Compute volume at each stage based on conversion rates
5. **Identify bottlenecks**: Highlight stages with below-benchmark conversion
6. **Generate HTML visualization**: Create the funnel as a standalone HTML file
7. **Add recommendations**: Note where to focus optimization efforts

## Conversion Rate Benchmarks (B2B SaaS)

| Stage Transition | Benchmark Range |
|-----------------|----------------|
| Visitor → Lead | 1-3% |
| Lead → MQL | 15-25% |
| MQL → SQL | 30-40% |
| SQL → Opportunity | 50-60% |
| Opportunity → Proposal | 60-70% |
| Proposal → Closed Won | 20-30% |
| Overall Visitor → Customer | 0.5-2% |
| Free Trial → Paid (PLG) | 3-7% |
| Freemium → Paid (PLG) | 1-4% |

## Output Artifacts
- **Funnel HTML visualization** (standalone file, ready to present or embed)
- Funnel data table with volumes, conversion rates, and benchmarks
- Bottleneck analysis with optimization recommendations
- Revenue projection based on funnel model

## Key Principles
- The funnel must match the client's actual growth motion, not a generic template
- Use real data when available; clearly label assumptions when using benchmarks
- Always show where the biggest leakage is — that's where the ROI lives
- Include revenue at the bottom — stakeholders care about the money
- Keep it visual and clean enough for a board presentation
