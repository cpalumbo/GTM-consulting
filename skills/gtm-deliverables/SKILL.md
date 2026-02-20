---
name: gtm-deliverables
description: Generate individual, standalone documents for each GTM strategy question — Market, Product, Positioning, Value Proposition, ICP, ECP, and Pricing. Each document applies Cinzia's GTM framework to the specific client and is ready for client delivery.
---

# GTM Deliverables Generator

After completing the client intake and running the relevant analysis skills, this skill generates polished, standalone deliverable documents for each of the core GTM strategy questions. Each document can be shared with the client independently.

## When to Use
- After client intake is complete and analysis skills have been run
- When you need to package GTM analysis into client-ready documents
- When the client needs individual deliverables per strategic area
- For building a complete GTM strategy binder

## The 7 GTM Deliverable Documents

### 1. Market Analysis Document
**Source skill**: `market-analyzer`
**File**: `[Client]-Market-Analysis.md`

Contents:
- Executive summary: Recommended beachhead market and why
- Market segments evaluated (3-4 segments with scoring)
- 10-dimension weighted scoring matrix results
- Bottom-up market sizing (S × P × A) per segment
- Top 10 target accounts in beachhead segment
- Market trends and tailwinds
- Risks and headwinds
- Recommended market entry strategy

### 2. ICP & ECP Document
**Source skills**: `icp-profiler`
**File**: `[Client]-ICP-ECP-Profile.md`

Contents:
- Executive summary: Who the ideal customer is and why
- Existing Customer Profile (ECP) analysis — patterns from current customers
- Ideal Customer Profile (ICP) definition with firmographic and behavioral criteria
- ECP → ICP gap analysis (where to expand)
- Buyer personas (Decision Maker + Champion + Influencer)
- Buying process map with stakeholders at each stage
- Qualification criteria (which leads to pursue)
- Anti-personas (who NOT to sell to)

### 3. Product & Value Proposition Document
**Source skill**: Phase 5 of `gtm-strategy-agent`
**File**: `[Client]-Value-Proposition.md`

Contents:
- Executive summary: Core value proposition statement
- Feature → Benefit → Value mapping (for top 5-7 features)
- Functional value (what it does)
- Economic value (money/time saved)
- Emotional value (how it makes users feel)
- Unique value proposition vs. alternatives
- Proof points and evidence (case studies, metrics, testimonials)
- Value proposition by persona (how to message differently to each buyer)

### 4. Positioning Document
**Source skill**: `positioning-builder`
**File**: `[Client]-Positioning.md`

Contents:
- Executive summary: Positioning statement
- April Dunford positioning framework results:
  - Competitive alternatives (what customers would use instead)
  - Unique attributes (what you have that alternatives don't)
  - Value delivered (what those attributes enable)
  - Target customers (who cares most about that value)
  - Market category (where you compete and win)
- Messaging framework (headline, subheadline, 3 supporting pillars)
- Positioning dos and don'ts
- Competitive positioning map (2x2 matrix)

### 5. Pricing Strategy Document
**Source skill**: `pricing-strategist`
**File**: `[Client]-Pricing-Strategy.md`

Contents:
- Executive summary: Recommended pricing model and rationale
- Pricing model analysis (models evaluated with scores)
- Competitor pricing landscape
- Willingness-to-pay analysis
- Recommended pricing tiers/packages
- Unit economics model (CAC, LTV, LTV:CAC ratio, payback period)
- Pricing implementation roadmap
- Price change communication strategy (if applicable)

### 6. Growth Motions & Channels Document
**Source skill**: `growth-channel-selector`
**File**: `[Client]-Growth-Strategy.md`

Contents:
- Executive summary: Recommended growth motion and top channels
- Growth motion recommendation (PLG / SLG / MLG / Hybrid) with rationale
- Channel scoring matrix (18 channels scored across 4 dimensions)
- Top 3 channel deep-dives (strategy, tactics, budget, KPIs)
- Channel experiment plans (what to test first)
- Channel layering strategy (what to add at each growth stage)
- Budget allocation recommendation
- 90-day growth execution plan

### 7. Competitive Landscape Document
**Source skill**: `competitor-mapper`
**File**: `[Client]-Competitive-Analysis.md`

Contents:
- Executive summary: Competitive position and key opportunities
- Competitive analysis matrix (15-dimension table)
- Hero positioning analysis (competitor H1s and positioning types)
- Features comparison matrix
- Verticals heatmap (which competitors serve which verticals)
- Competitive positioning map (2x2)
- Key vulnerabilities to exploit
- Battle cards (one per major competitor)
- Win/loss patterns and talk tracks

## Document Format Standards

Each document follows this structure:
1. **Header**: Document title, client name, date, confidentiality notice
2. **Executive Summary**: 2-3 paragraph overview with key recommendation
3. **Analysis**: Detailed findings with tables, frameworks, and data
4. **Recommendations**: Specific, actionable next steps
5. **Appendix**: Supporting data, methodology notes, sources

### Formatting Guidelines
- Use Markdown for all documents (easily convertible to PDF or DOCX)
- Include tables for all framework outputs
- Use headers (H2, H3) for clear section navigation
- Keep executive summaries under 300 words
- Every recommendation must include: What to do, Why, Expected impact, Timeline

## Workflow

1. **Verify intake is complete**: Check that the Client Brief exists
2. **Run relevant analysis skills**: Each document maps to a specific skill
3. **Generate documents**: Create each document using the template structure above
4. **Cross-reference**: Ensure consistency across all 7 documents
5. **Package**: Compile into a client-ready deliverable set
6. **Review**: Verify all recommendations are actionable within client constraints

## Output Artifacts
- 7 individual GTM strategy documents (Markdown format)
- Document index / table of contents
- Cross-reference summary showing how documents connect
- Optional: Combined GTM Strategy Report (all 7 in one document)

## Key Principles
- Each document should stand alone — a reader should understand it without seeing the others
- Always lead with the recommendation, then show the work
- Use the client's language and terminology, not consulting jargon
- Include specific next steps with timelines, not just analysis
- Flag assumptions clearly — distinguish between data-backed findings and estimates
