# Sector Screening: Strategy & Methodology

*Version 0.1*

-----

## 1. Objective & Scope

### What We’re Screening For

Identify European industry sectors where acquiring sub-€10M revenue SMEs and deploying AI solutions will reliably and materially improve profitability, and where the deployment playbook can be repeated across multiple similar businesses in a portfolio.

The screening is looking for sectors where:

- AI creates **measurable financial impact** using tools that are available and deployable today (GenAI, RPA, ML, statistical computing, NLP, computer vision, recommender systems)
- The target businesses are **acquirable at reasonable valuations** and are fundamentally sound before AI
- The AI playbook is **repeatable** — one deployment methodology works across many targets in the same sector
- Value creation is **durable** — not dependent on a single tool, vendor, or temporary market condition

### Universe Definition

- **Sector classification:** NACE Rev. 2 at the 4-digit level (European standard)
- **Geography:** Europe and the GCC, with France, UAE, and KSA as primary countries of interest
- **Target company size:** Sub-€10M annual revenue (sweet spot: €3M–€10M)
- **Excluded sectors:** Extractive industries (NACE A, B), regulated utilities (D), public administration (O), household activities (T), extraterritorial (U). Also excluded: sectors where the typical business exceeds the target size, and sectors where AI adoption is already high (minimal gap to exploit).
- **Note on declining sectors:** Sectors in structural decline are *not* automatically excluded. A declining sector can still be a viable acquisition target if the business generates durable cash flows for 5+ years, the purchase price reflects the decline (lower multiples), and AI deployment improves margins on a shrinking but still substantial revenue base. Decline is a factor in scoring (reflected in R7 and the verdict rationale) but not an exclusion criterion.

### Link to Phase 1 Framework

The screening criteria are derived directly from the Phase 1 value creation framework:

- **Value creation levers** (Categories 1–5) define *what* AI can do in a sector
- **Reliability conditions** (R1–R7) define *whether* AI deployment will actually work
- **Two-phase deployment model** (Phase A: GenAI+RPA; Phase B: data-dependent ML/stats) defines *how quickly* value is created

-----

## 2. Screening Funnel

The screening process has four stages, each progressively narrower and deeper.

### Stage 1: Long List Generation

**Objective:** Build a comprehensive universe of candidate sectors.

**Method:** Systematic review of all NACE Rev. 2 4-digit codes, excluding sectors that obviously fail reliability conditions (see exclusions above). Inclusion is deliberately broad — better to score and eliminate than to miss a viable sector.

**Output:** Over 300 sub-sectors across 15 NACE sections.

**Key principle:** At this stage, the filter is *plausibility*, not *attractiveness*. Any sector that could conceivably contain sub-€10M SMEs amenable to AI deployment is included.

### Stage 2: Quantitative Scoring

**Objective:** Score every sector on the long list against standardized criteria, producing a composite score and an initial verdict (Yes / Maybe / No).

**Method:** Each sector is scored 1–5 on nine dimensions (seven reliability conditions + two deployment potential scores). Scores are summed into a composite (max 45). A qualitative verdict is assigned based on the scores plus judgment on sector-specific factors.

**Output:** Scored spreadsheet with all sub-sectors. [X] rated “Yes,” [X] rated “Maybe,” [X] rated “No.”

**Key principle:** The scoring is a *ranking tool*, not a decision tool. It identifies which sectors deserve deeper analysis, not which sectors to invest in. The composite score weights all criteria equally, which is a deliberate simplification — weighting is applied through judgment in later stages.

### Stage 3: Deep Dive Analysis

**Objective:** For top-scoring sectors, develop a detailed understanding of the business model, AI deployment playbook, financial impact potential, risks, and portfolio logic.

**Method:** Structured analysis following the Deep Dive Framework (Section 4 below). Each deep dive produces a standalone document.

**Output:** Deep dive documents. 

**Key principle:** Deep dives are where quantitative scoring meets qualitative judgment. A high-scoring sector may be downgraded after deep analysis (e.g., recruitment: high AI fit but long-term disruption risk). A moderate-scoring sector may be upgraded if the deep dive reveals a compelling niche.

### Stage 4: Final Selection

**Objective:** Select max 10 sectors to pursue for active deal sourcing.

**Method:** Comparative assessment across deep-dived sectors using the decision criteria in Section 5. The decision is made by the investment team, not by the model.

**Output:** Selected sector(s) with a rationale document, target profile, and geographic focus.

**Key principle:** The final selection balances analytical rigor with practical considerations — deal flow feasibility, investor group expertise, geographic fit, and portfolio construction logic.

-----

## 3. Scoring Model

### Criteria Definitions

Each criterion is scored 1–5. The descriptions below define what each score level means.

#### A. Data Conditions

**R1. Data Availability**

|Score|Definition                                                                                                  |
|-----|------------------------------------------------------------------------------------------------------------|
|1    |Businesses in this sector generate virtually no digital data. Operations are analog.                        |
|2    |Minimal digital data — basic accounting records only.                                                       |
|3    |Moderate data — digital accounting, some transaction records, basic customer records.                       |
|4    |Good data — digital transactions, customer interaction logs, operational records exist even if unstructured.|
|5    |Rich data — high-frequency digital transactions, customer interactions, and operational telemetry.          |

Note: R1 assesses the *typical* data state. Individual targets may be ahead of or behind the sector norm. R1a (data exists) and R1b (data can be created post-acquisition) are both considered — the score reflects the likely starting position.

**R2. Data Volume**

|Score|Definition                                                                                           |
|-----|-----------------------------------------------------------------------------------------------------|
|1    |Very few data-generating events (e.g., <100 transactions/year).                                      |
|2    |Low volume — enough for basic reporting but not for ML.                                              |
|3    |Moderate — hundreds to low thousands of events per year. Sufficient for simple ML after accumulation.|
|4    |High volume — thousands of events/year. ML models can be trained within 6–12 months.                 |
|5    |Very high volume — daily/hourly data generation. ML viable within months.                            |

**R3. Process Repeatability**

|Score|Definition                                                                             |
|-----|---------------------------------------------------------------------------------------|
|1    |Highly bespoke — every job/engagement is unique with minimal repeating patterns.       |
|2    |Mostly bespoke with some repeating elements.                                           |
|3    |Mixed — significant variation but with recognizable patterns and standard procedures.  |
|4    |Largely standardized — most work follows established patterns, with some customization.|
|5    |Highly repetitive — the same core processes are executed daily with minimal variation. |

#### B. Operational Conditions

**R4. Human Activity Amenable to AI**

|Score|Definition                                                                                                                                               |
|-----|---------------------------------------------------------------------------------------------------------------------------------------------------------|
|1    |Minimal human operational activity that AI could improve (e.g., capital-intensive automated processes).                                                  |
|2    |Some human tasks, but primarily physical/manual with limited AI applicability.                                                                           |
|3    |Moderate — meaningful human tasks where AI could add value in speed, accuracy, or cost.                                                                  |
|4    |Substantial — humans perform many tasks where AI delivers clear gains.                                                                                   |
|5    |Extensive — the business is fundamentally a human-activity business where AI can improve speed, cost, reliability, and/or accuracy across most functions.|

**R5. Low AI Adoption with Digitization Baseline**

|Score|Definition                                                                                                     |
|-----|---------------------------------------------------------------------------------------------------------------|
|1    |Either already tech-native (low AI gap) OR entirely analog (no digitization baseline). Both extremes score low.|
|2    |Minimal digitization or already moderately tech-savvy.                                                         |
|3    |Basic digital tools in place (accounting, email) but limited operational digitization. Some AI gap.            |
|4    |Digitized operations (CRM, job management, digital records) but no AI adoption. Clear gap.                     |
|5    |Sweet spot — digitized enough to deploy AI on existing systems, but zero AI adoption. Maximum gap.             |

#### C. Market & Structural Conditions

**R6. Fragmentation**

|Score|Definition                                                                                                    |
|-----|--------------------------------------------------------------------------------------------------------------|
|1    |Consolidated — dominated by a few large players. Few SME-scale businesses exist.                              |
|2    |Semi-consolidated — some large players plus a moderate number of SMEs.                                        |
|3    |Moderately fragmented — meaningful number of SMEs but some concentration.                                     |
|4    |Fragmented — many SMEs, no dominant player at the target size range.                                          |
|5    |Extremely fragmented — thousands of similar sub-€10M businesses. No player has >1% market share at this scale.|

**R7. Business Quality at SME Scale**

|Score|Definition                                                                                                       |
|-----|-----------------------------------------------------------------------------------------------------------------|
|1    |Poor fundamentals — commodity pricing, no recurring revenue, thin margins, high customer concentration.          |
|2    |Below average — one or two positive attributes but overall weak business model.                                  |
|3    |Average — viable business but no standout characteristics. Margins are acceptable but not strong.                |
|4    |Good — healthy margins, some recurring/repeat revenue, manageable customer concentration, viable market position.|
|5    |Excellent — strong recurring revenue, high margins, loyal customer base, clear market position.                  |

**R8. AI Disruption Resilience**

|Score|Definition                                                                                                                                |
|-----|------------------------------------------------------------------------------------------------------------------------------------------|
|1    |Core service is highly vulnerable — AI could replace the primary value proposition within 3–5 years.                                      |
|2    |Significant exposure — AI is already eroding demand or commoditizing key deliverables.                                                    |
|3    |Moderate exposure — some functions at risk but core delivery has durable human/physical components.                                       |
|4    |Low exposure — core work is physical, relational, or regulatory-gated. AI augments but cannot substitute.                                 |
|5    |Minimal exposure — the service fundamentally requires on-site human presence, licensed expertise, or physical transformation of materials.|

#### D. Deployment Potential

**Phase A Potential (GenAI + RPA, deployable Day 1)**

|Score|Definition                                                                                                       |
|-----|-----------------------------------------------------------------------------------------------------------------|
|1    |Minimal — few processes that GenAI or RPA can improve without data or customization.                             |
|2    |Limited — one or two applications with modest impact.                                                            |
|3    |Moderate — several clear GenAI/RPA use cases with meaningful combined impact.                                    |
|4    |Strong — GenAI and RPA can materially improve multiple operational areas from day one.                           |
|5    |Transformative — Phase A tools alone can deliver a step-change in operational efficiency and/or revenue capacity.|

**Phase B Potential (ML, statistical computing, recommender systems — month 6–12)**

|Score|Definition                                                                                                                          |
|-----|------------------------------------------------------------------------------------------------------------------------------------|
|1    |Minimal — limited additional upside from data-dependent AI beyond Phase A.                                                          |
|2    |Limited — one narrow ML application with modest incremental impact.                                                                 |
|3    |Moderate — meaningful additional levers unlock once data accumulates.                                                               |
|4    |Strong — data-dependent models can significantly improve pricing, forecasting, retention, or quality.                               |
|5    |Transformative — ML/stats unlock major new value (e.g., demand forecasting in perishable goods, predictive matching in recruitment).|

### Composite Score

**Composite = R1 + R2 + R3 + 2 x R4 + R5 + 2 x R6 + R7 + 2 x Phase_A + Phase_B**

Maximum possible: 65.

|Range|Interpretation                                                                                   |
|-----|-------------------------------------------------------------------------------------------------|
|45–65|Top tier — strong fit across most dimensions. Proceed to deep dive.                              |
|35–45|Promising — likely viable with some conditional factors. Review for deep dive.                   |
|25–35|Marginal — may work in specific niches or geographies. Low priority for deep dive.               |
|<25  |Weak fit — unlikely to meet reliability conditions. Exclude unless specific justification exists.|

### Verdicts

- **Yes:** Strong overall fit. Sector proceeds to deep dive unless overridden by a specific disqualifying factor.
- **Maybe:** Conditional fit. Sector may be viable in specific sub-segments, geographies, or niches. Reviewed case by case.
- **No:** Poor fit or explicitly excluded. Clear reason documented in the rationale column.

### Weighting

The criteria that matter most for our strategy are **R4**, **R6**, and **Phase A potential**. They currently receive a x2 weighting.

-----

## 4. Deep Dive Framework

Each deep dive follows a standard structure to ensure consistency and comparability across sectors.

### 4.1 Sector Overview

- Market size and growth trajectory 
- Structural drivers and headwinds
- Fragmentation evidence (number of firms, concentration ratios if available)

### 4.2 Typical Business Model at Target Size

- Team structure and size
- Revenue model and mix (project vs. recurring, B2B vs. B2C)
- Margin structure (gross and net, with benchmarks)
- Key cost drivers
- Current technology state
- Pain points and operational bottlenecks

### 4.3 Ideal Acquisition Target Profile

- Must-haves (revenue range, margin thresholds, revenue mix, digitization baseline, customer diversification)
- Nice-to-haves (recurring revenue contracts, online presence, owner willing to stay)
- Red flags (excessive owner-dependence, no digital records, revenue concentration, structural decline)

### 4.4 AI Deployment Playbook

- **Phase A interventions** (GenAI + RPA, Day 1 to Month 3): specific tools and use cases, mapped to framework levers, with expected impact
- **Phase B interventions** (ML + stats, Month 6 to 18): data-dependent deployments, mapped to levers, with expected impact
- For each intervention: problem statement → AI solution → expected impact (quantified where possible)

### 4.5 Financial Impact Model (Illustrative)

- Baseline: representative target’s revenue, margins, cost structure
- Impact by intervention: estimated annual value, timeline to realization
- Aggregated pre/post comparison: revenue, net profit, net margin
- Caveats and confidence level for estimates

### 4.6 Portfolio Logic

- How the repeatable playbook applies across multiple acquisitions
- Shared infrastructure opportunities (software, back-office, procurement, AI team)
- Geographic clustering potential

### 4.7 Sector-Specific Risks

- Risks unique to this sector (beyond the general risks in Phase 1)
- Severity assessment and mitigation strategies

### 4.8 Comparative Assessment

- How this sector compares to others analyzed on key dimensions
- Relative ranking for this strategy’s objectives

-----

## 5. Decision Criteria for Final Sector Selection

The scoring model and deep dives inform the decision, but the final selection is a judgment call that weighs multiple factors. The criteria below are organized by priority.

### Tier 1: Non-Negotiable

These must be met for a sector to be selected:

- **AI creates material, quantifiable financial impact.** Phase A alone should justify the deployment cost and deliver meaningful profitability improvement within the first year.
- **The sector is sufficiently fragmented (R6 ≥ 4).** The portfolio playbook is the core strategic edge. Without fragmentation, there’s no repeatable play.
- **Businesses at target size are fundamentally sound (R7 ≥ 3).** We are not using AI to rescue bad businesses.
- **Deal flow is feasible.** Targets must be identifiable and acquirable in the chosen geography — through brokers, proprietary outreach, or other channels.

### Tier 2: Strongly Preferred

These significantly improve the attractiveness of a sector:

- **Recurring or highly repeatable revenue.** Service contracts, maintenance agreements, and long-term customer relationships provide predictability and compound over time.
- **Strong Phase A potential (≥ 4).** Immediate value creation reduces execution risk and improves cash-on-cash returns.
- **Structural tailwinds.** Sectors benefiting from secular trends (e.g., energy transition, aging population, labor scarcity) are preferred over stable-but-flat sectors.
- **Low long-term AI disruption risk.** AI should improve the business, not threaten to replace it. Sectors where AI might commoditize the core service (e.g., translation, call centres) are less attractive for long-term holds.

### Tier 3: Differentiators

These are tiebreakers between otherwise comparable sectors:

- **Country fit.** The sector must be large and fragmented in France (our primary geography). Some sectors that score well pan-European may not be well-suited to the French market specifically.
- **Investor group expertise.** Sectors where the investor group has existing operational knowledge or relationships accelerate execution.
- **Portfolio construction.** If multiple sectors are selected, they should be complementary — diversified by cycle, customer type, and risk profile.
- **Valuation accessibility.** Sectors where acquisition multiples are reasonable relative to AI-enhanced profitability potential are preferred.

-----

## 6. Limitations & Confidence Levels

### What This Methodology Does Well

(to be completed after a few deep dives)

### Known Limitations

(to be completed after a few deep dives)

### Summary Confidence Matrix

(to be completed after a few deep dives)
