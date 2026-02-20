---
name: pipeline-architect
description: Design and model sales pipelines with stage definitions, conversion rates, velocity metrics, and revenue projections. Build pipeline models that connect marketing activities to revenue outcomes.
---

# Pipeline Architect

Help clients design, model, and optimize their sales pipeline to build revenue more quickly and predictably.

## When to Use
- Client needs to forecast revenue from pipeline
- Building a new sales process from scratch
- Pipeline velocity is too slow
- Conversion rates need benchmarking
- Connecting marketing spend to revenue outcomes

## Pipeline Stage Framework

### Standard B2B SaaS Pipeline Stages

| Stage | Definition | Typical Conversion |
|-------|-----------|-------------------|
| Lead / MQL | Marketing qualified lead (downloaded content, attended webinar, etc.) | - |
| SQL | Sales qualified lead (meets ICP criteria, has budget/authority) | 30-40% from MQL |
| Discovery | Initial meeting completed, pain confirmed | 60-70% from SQL |
| Proposal | Solution presented, pricing shared | 50-60% from Discovery |
| Negotiation | Terms being discussed, procurement involved | 60-70% from Proposal |
| Closed Won | Deal signed | 70-80% from Negotiation |
| Closed Lost | Deal lost (track reason) | - |

### Pipeline Velocity Formula

Pipeline Velocity = (Number of Opportunities × Win Rate × Average Deal Size) / Sales Cycle Length (days)

### Key Pipeline Metrics

| Metric | Formula | Benchmark (B2B SaaS) |
|--------|---------|---------------------|
| Win Rate | Closed Won / Total Opportunities | 15-25% |
| Average Deal Size | Total Revenue / Deals Closed | Varies by segment |
| Sales Cycle Length | Average days from SQL to Close | 30-90 days (SMB), 90-180 (Mid), 180+ (Enterprise) |
| Pipeline Coverage | Pipeline Value / Revenue Target | 3-4x target |
| Lead-to-Close Rate | Closed Won / Total Leads | 1-5% |
| CAC | Total Sales+Marketing Cost / New Customers | < 1/3 of LTV |
| LTV:CAC Ratio | LTV / CAC | > 3:1 |

## Pipeline Model Template

Build a bottoms-up model connecting activities to revenue:

| Input | → | Output |
|-------|---|--------|
| Marketing budget | → | Leads generated |
| Leads × MQL rate | → | MQLs |
| MQLs × SQL rate | → | SQLs |
| SQLs × Opportunity rate | → | Opportunities |
| Opportunities × Win rate | → | Closed deals |
| Closed deals × ACV | → | New ARR |

## Workflow

1. **Define pipeline stages** with clear entry/exit criteria
2. **Set conversion rate assumptions** (use benchmarks, then refine with data)
3. **Build the pipeline model** connecting activities → leads → revenue
4. **Calculate pipeline velocity** and coverage requirements
5. **Identify bottlenecks** — where do deals stall or die?
6. **Design improvement experiments** for weakest stages
7. **Set reporting cadence** and dashboard

## Pipeline Modeling & Recommendations

After defining stages and conversion rates, build a complete pipeline model with recommendations:

### Revenue Model (Bottoms-Up)
Connect the funnel to revenue with specific numbers:

| Parameter | Input | Source |
|-----------|-------|--------|
| Monthly website visitors | [from client or estimate] | Analytics / estimate |
| Visitor → Lead rate | [%] | Benchmark or actual |
| Lead → MQL rate | [%] | Benchmark or actual |
| MQL → SQL rate | [%] | Benchmark or actual |
| SQL → Opportunity rate | [%] | Benchmark or actual |
| Win rate | [%] | Benchmark or actual |
| Average deal size (ACV) | [$] | Client data |
| Sales cycle length | [days] | Client data or benchmark |

**Model output**: Monthly new deals, monthly new ARR, annual ARR projection, required pipeline coverage

### Pipeline Recommendations

Based on the model, generate specific recommendations:

1. **Coverage gap**: If pipeline value < 3-4x revenue target → recommend lead generation tactics
2. **Conversion bottleneck**: Identify the stage with the worst conversion rate → recommend specific fixes
3. **Velocity issue**: If sales cycle > benchmark → recommend acceleration tactics (better qualification, faster proposals, champion enablement)
4. **Capacity planning**: How many SDRs/AEs needed to hit target based on rep productivity benchmarks
5. **Channel attribution**: Which marketing channels feed the pipeline and at what cost per opportunity

### Scenario Modeling

Build 3 scenarios:
- **Conservative**: Current conversion rates, organic growth only
- **Base**: Improved rates from recommended optimizations
- **Aggressive**: Full execution of all recommendations + new channel investment

## Integration with CRM (HubSpot / Salesforce)

If the client uses HubSpot or Salesforce, the pipeline model can be validated against real data:

### HubSpot Integration
- Pull deal stages and conversion rates from HubSpot pipeline
- Pull lead sources and attribution data
- Compare actual metrics vs. model assumptions
- Identify discrepancies between model and reality

### Data Points to Pull from CRM
- Deals by stage (current pipeline snapshot)
- Historical conversion rates by stage
- Average deal size by segment
- Sales cycle length by deal type
- Lead source attribution
- Rep productivity metrics

## Output Artifacts
- Pipeline stage definitions with entry/exit criteria
- **Pipeline revenue model** (activities → revenue with 3 scenarios)
- Pipeline velocity calculations
- Conversion rate benchmarks and targets
- **Pipeline recommendations** (specific actions to close gaps)
- **Capacity plan** (headcount needed to hit targets)
- Pipeline review cadence and meeting agenda
- **CRM validation report** (if CRM data available)
