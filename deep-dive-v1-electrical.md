# Deep Dive: NACE 43.21 — Electrical Installation

*Country focus: France | Version 0.2 | April 2026*

-----

## 1. Sector Overview

### Market Size and Growth

The French electrical installation market is valued at approximately €43.8 billion (2025), with roughly 70,500 businesses operating in the sector. Revenue has grown at a CAGR of ~4.8% between 2020 and 2025. In 2023, there were approximately 27,300 companies and 207,000 employees in the narrower electrical installation subsector. The number of companies grew approximately 24% since 2015, indicating strong new business formation.

### Structural Drivers

- **Electrification of buildings:** France’s RE2020 regulation and EU energy performance mandates are driving the replacement of gas and oil systems with electric alternatives (heat pumps, electric heating, induction).
- **EV charging infrastructure:** France is rapidly expanding its EV charging network. In 2023, 16.8% of new vehicles sold were electric, driving demand for residential, commercial, and public charging station installation.
- **Smart home and building automation:** Connected objects are present in approximately 40% of French households (up from 33% in 2020), creating installation and integration demand.
- **Solar/photovoltaic self-consumption:** France is targeting 4 million solar self-consumption installations by 2030, up from roughly 387,000 today, with a target of 4 GW of new capacity per year until 2028. Each installation requires qualified electrical work.
- **Labor scarcity:** Persistent shortage of qualified electricians. This acts as both a growth constraint and a barrier to entry for new competitors.

### Structural Headwinds

- **New construction downturn:** Residential building starts have declined sharply, reducing new-build electrical installation volume. The sector must pivot toward renovation and maintenance.
- **Price inelasticity:** Competitive pressure limits the ability to pass on cost increases, especially in residential work.
- **Electrification pace slower than expected:** Despite strong policy support, EV charging and solar installation rollout has lagged behind government targets.

### Fragmentation

Extremely fragmented at the target size. The sector is dominated by small artisan businesses — 85% of electrical installation companies employ fewer than 6 people. At the top end, large groups (Vinci Énergies, Equans, Eiffage Énergie Systèmes, SPIE, SNEF) handle major commercial and industrial projects. The vast middle ground of €3–10M businesses — serving residential renovation, small commercial, and light industrial clients — is highly fragmented with no dominant player.

-----

## 2. Typical Business Model at Target Size (€3–10M Revenue)

### Team Structure

- **Owner-operator** (master electrician) managing sales, key accounts, and technical oversight.
- **15–50 electricians** organized into crews of 1–3 depending on project scale.
- **1–2 project managers** (for firms closer to €10M handling multiple concurrent projects).
- **1–3 office staff** (admin, scheduling, accounting support).

### Revenue Model

- **Installation — renovation:** 40–55% of revenue. Rewiring, panel upgrades, lighting systems for existing buildings. Mix of B2B (property managers, contractors) and B2C.
- **Installation — new build:** 15–30% of revenue. Subcontracting to general contractors or direct contracts on smaller projects.
- **Maintenance and service contracts:** 15–25% of revenue. Recurring: annual inspections, emergency call-outs, compliance checks (NF C 15-100).
- **Specialty installations:** 5–15% of revenue. EV charging, solar PV, smart home, security systems. Growing rapidly.
- **Pricing:** Renovation averages €80–142.50/m²; hourly rates range €35–65 depending on region and specialization.

### Margin Structure

- **Gross margin:** 35–45%. Higher on maintenance/repair and specialty work; lower on competitive new-build subcontracting.
- **Net margin (pre-owner comp):** 7–14%.
- **Key cost drivers:** Labor (50–60% of revenue), materials (15–25%), vehicles (5–8%), insurance/certification (2–4%).

### Current Technology State

Very similar to 43.22. Basic digital accounting (Sage, EBP). Scheduling is largely manual (phone, WhatsApp). Quoting is Excel-based or manual. CRM is rare. Job management software adoption exists but is not universal. AI adoption is effectively zero.

### Pain Points

Nearly identical to 43.22, with one additional emphasis:

- **NF C 15-100 compliance documentation** is labor-intensive. Post-installation electrical compliance certificates (Consuel) require detailed documentation that is largely manual.
- **Multi-trade coordination:** Electrical work often runs in parallel with plumbing, HVAC, and finishing trades. Scheduling dependencies cause delays and idle time.
- **Quoting complexity:** Electrical installation quotes must account for cable runs, panel specifications, and compliance requirements. Errors lead to margin erosion on fixed-price contracts.

-----

## 3. Ideal Acquisition Target Profile

### Must-Haves

- Revenue: €3–10M.
- Gross margin ≥ 35%.
- At least 15% of revenue from recurring maintenance/service contracts.
- No single client > 20% of revenue.
- Qualibat and/or relevant NF certifications current.
- Basic digital infrastructure.
- Owner willing to stay 12–24 months or strong project manager in place.

### Nice-to-Haves

- EV charging installation capability (IRVE qualification).
- Solar PV installation capability (QualiPV).
- Existing job management software.
- Geographic adjacency to a 43.22 (HVAC/plumbing) acquisition for cross-referral and shared infrastructure.

### Red Flags

- Heavy dependence on one general contractor for new-build subcontracting.
- No documented processes — all technical knowledge in the owner’s head.
- Declining revenue from new construction without compensating growth in renovation/specialty.
- Outstanding Consuel compliance issues or insurance claims.

-----

## 4. AI Deployment Playbook

### Phase A — GenAI + RPA (Day 1 to Month 3)

|# |Intervention                                                                                                                                                                  |Framework Lever|Tool      |Expected Impact                                                                                                              |
|--|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------|-----------------------------------------------------------------------------------------------------------------------------|
|A1|Automated quoting with compliance awareness: GenAI generates quotes incorporating NF C 15-100 requirements, material specifications, and labor estimates from historical data.|1.1, 1.3, 2.2  |GenAI     |30–50% reduction in quoting time. Fewer errors → fewer margin-eroding change orders.                                         |
|A2|Scheduling and dispatch optimization: Same as 43.22 — rules-based assignment of crews to jobs by location, skill, and availability.                                           |1.1, 1.5       |RPA       |10–15% reduction in travel/idle time.                                                                                        |
|A3|Administrative and compliance automation: RPA generates Consuel documentation, invoice processing, compliance certificates.                                                   |1.1            |RPA       |40–60% reduction in admin time per job.                                                                                      |
|A4|Knowledge codification: Internal knowledge base capturing wiring standards, panel configurations, supplier preferences, pricing rules.                                        |1.4            |GenAI, NLP|Reduces owner-dependence. Enables junior electricians or project managers to handle quoting.                                 |
|A5|Post-job follow-up and upselling: Automated proposals for maintenance contracts, smart home upgrades, EV charger installation after completing renovation work.               |2.1, 2.3       |GenAI, RPA|Increases cross-sell conversion. Target: 5–10% of completed renovation jobs convert to ongoing maintenance or specialty work.|
|A6|Data instrumentation.                                                                                                                                                         |5.1            |—         |Enables Phase B.                                                                                                             |

### Phase B — ML + Statistical (Month 6 to 18)

|# |Intervention                                                                                                                                          |Framework Lever|Tool           |Expected Impact                                                     |
|--|------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|---------------|--------------------------------------------------------------------|
|B1|Project cost estimation model: ML model trained on completed jobs predicts true cost (labor hours, materials) for new quotes. Reduces under-quoting.  |3.1            |ML             |3–5% improvement in quote accuracy → direct margin protection.      |
|B2|Demand forecasting by segment: Predict seasonal and segment-level demand (renovation vs. new build vs. EV charging) for capacity planning.            |1.5            |ML, Statistical|Improved resource allocation. Reduced overtime and temp labor costs.|
|B3|Customer lifetime value scoring: ML ranks clients by total expected value (installation + maintenance + referral potential). Prioritizes sales effort.|2.1, 2.4       |ML             |Improved sales focus. Higher retention of valuable B2B clients.     |
|B4|Material procurement optimization: Aggregate purchasing data across jobs. Identify savings from supplier consolidation and volume commitments.        |3.2            |Statistical    |3–5% reduction in material costs.                                   |

-----

## 5. Financial Impact Model (Illustrative)

### Baseline: Representative Target

|Metric                      |Value       |
|----------------------------|------------|
|Revenue                     |€6.0M       |
|Gross margin                |38% (€2.28M)|
|Operating costs (excl. COGS)|€1.88M      |
|Net profit (pre-owner comp) |€400K (6.7%)|

### Phase A Impact (Year 1): ~€150K incremental profit

Key contributors: quoting speed (+conversion), scheduling optimization (recovered labor), admin automation (FTE savings), upsell on specialty services.

### Phase B Impact (Year 2): ~€100K incremental profit

Key contributors: quote accuracy (margin protection), procurement savings, demand-based capacity planning.

### Steady State (Year 2+)

|Metric    |Baseline|Post-AI|Change|
|----------|--------|-------|------|
|Revenue   |€6.0M   |€6.3M  |+5%   |
|Net profit|€400K   |€650K  |+63%  |
|Net margin|6.7%    |10.3%  |+3.6pp|

**Confidence level:** Medium. Similar logic and magnitude to 43.22 but slightly lower confidence on the upselling lever (EV charging/solar cross-sell is newer and less proven than HVAC maintenance contracts).

-----

## 6. Portfolio Logic

### Synergy with 43.22

This is the strongest portfolio synergy in the entire screening. HVAC/plumbing and electrical installation are the two core building trades that:

- Share the same client base (property managers, general contractors, homeowners).
- Often work on the same job sites (a heat pump installation requires both HVAC and electrical work).
- Have nearly identical operational models (mobile crews, project + maintenance revenue, same scheduling/quoting pain points).
- Can share back-office, procurement, software infrastructure, and AI tooling with minimal adaptation.

A portfolio combining 43.22 and 43.21 acquisitions in the same geographic cluster creates immediate cross-referral revenue, shared dispatch, and the ability to offer bundled “mechanical + electrical” service packages that larger competitors already provide but fragmented SMEs cannot.

### Repeatable Playbook

The AI playbook developed for 43.22 transfers to 43.21 with roughly 80% reuse. The quoting assistant needs electrical-specific templates (NF C 15-100 vs. DTU for plumbing), but the scheduling, admin automation, CRM, and Phase B models are functionally identical.

-----

## 7. Sector-Specific Risks

|Risk                                                                                                                                         |Severity          |Mitigation                                                                                                                             |
|---------------------------------------------------------------------------------------------------------------------------------------------|------------------|---------------------------------------------------------------------------------------------------------------------------------------|
|**New construction dependency:** Firms heavily weighted toward new-build subcontracting face revenue pressure as construction starts decline.|Medium-High       |Target firms with ≥50% renovation/maintenance revenue. The sector is actively pivoting toward renovation.                              |
|**EV/solar regulatory uncertainty:** Subsidy levels and qualification requirements for IRVE/QualiPV may change.                              |Medium            |Treat specialty installations as upside, not core thesis. Base case profitability should hold without them.                            |
|**Electrician shortage:** Same labor constraint as 43.22. Severe in some regions.                                                            |High              |AI-driven productivity gains reduce headcount need per €M revenue. Shared training and apprenticeship programs across portfolio.       |
|**Technology obsolescence risk:** Smart home and building automation standards evolve rapidly. Skills gap for legacy electricians.           |Low-Medium        |Fractional AI/tech team across portfolio provides upskilling. Older electricians handle core installation; specializations centralized.|
|**Competition from integrated multi-trade operators:** Large groups (Equans, SPIE) are moving downstream.                                    |Low at target size|Integrated groups focus on contracts >€100K. The sub-€10M SME market is too fragmented and low-ticket for them to address efficiently. |

-----

## 8. Comparative Assessment

|Dimension            |43.21 Rating   |Comparison to 43.22                                                                    |
|---------------------|---------------|---------------------------------------------------------------------------------------|
|AI fit (Phase A)     |★★★★★          |Equivalent. Same pain points, same tools.                                              |
|AI fit (Phase B)     |★★★☆☆          |Equivalent.                                                                            |
|Fragmentation        |★★★★★          |Equivalent — arguably even more fragmented (70K+ businesses).                          |
|Business quality     |★★★★☆          |Comparable. Slightly more new-build exposure → slightly more cyclical.                 |
|Structural tailwinds |★★★★★          |Comparable. EV charging and solar add diversification vs. 43.22’s heat pump focus.     |
|AI disruption risk   |★☆☆☆☆ (minimal)|Equivalent.                                                                            |
|Deal flow feasibility|★★★★☆          |Equivalent.                                                                            |
|Portfolio scalability|★★★★★          |Enhanced by 43.22 synergy — this is the single best portfolio pairing in the screening.|

**Overall: Joint top-tier with 43.22.** The combined 43.21 + 43.22 portfolio strategy is the strongest play identified in the screening. The operational similarity, client overlap, and AI playbook reuse make this a natural two-sector rollup.
