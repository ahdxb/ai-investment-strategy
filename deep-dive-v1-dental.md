# Deep Dive: NACE 86.23 — Dental Practice Activities

*Country focus: France | Version 0.2 | April 2026*

-----

## 1. Sector Overview

### Market Size and Growth

France is Europe’s second-largest dental market. In 2023, approximately 45,249 dentists were active in France, growing at roughly 1% per year. The number is projected to reach ~46,000 by 2030 and ~62,000 by 2050, driven largely by EU-diploma holders entering the market. Average annual revenue per dental practice was approximately €367,000 in 2022, with average net profit of ~€129,000. The broader French dental care market (services + equipment + consumables) is estimated at roughly €1 billion and growing at a CAGR of ~5.5%.

### Structural Drivers

- **Aging population:** Older populations require more restorative and prosthetic work, increasing visit frequency and treatment value.
- **Growing cosmetic demand:** Rising patient interest in aesthetic dentistry (whitening, aligners, veneers) is expanding the addressable market beyond conventional care.
- **Digital dentistry adoption:** CAD/CAM, intraoral scanners, and AI-assisted diagnostics are transforming clinical workflows, but adoption is uneven — concentrated in larger or younger practices.
- **Dental software market growth:** The French dental software market is growing at a CAGR of ~14.6%, indicating rapid digitization of practice management.

### Structural Headwinds

- **Convention pricing constraints:** 99% of general dentists adhere to the Convention Nationale, which fixes fees for core treatments (consultations, basic restorative care). This caps revenue on ~70% of activity. Only prosthetics and aesthetic treatments have free pricing.
- **Geographic maldistribution:** Strong North-South density imbalance. Northern France (except Île-de-France) is underserved (45 dentists per 100,000 in Normandy vs. national average of 67). This limits acquisition opportunities in some regions.
- **Rising operating costs:** Prosthetic materials, laboratory fees, and staff costs have been increasing, compressing margins on convention-priced treatments.

### Fragmentation

Extremely fragmented. In 2024, 63% of practitioners still exercised in solo or small-group settings, though this is declining (down from 87% in 2023 per one survey). The trend toward group practice and société structures is accelerating, but the vast majority of French dental practices remain independent, single- or dual-chair operations. DSO (Dental Service Organization) models are emerging — Colosseum Dental Group acquired Dentelia in 2021, expanding to 300+ clinics across Europe — but the French market remains far less consolidated than the US or UK.

-----

## 2. Typical Business Model at Target Size

### Important Structural Note

Individual dental practices in France typically generate €300–500K in revenue. To reach the €3–10M target range, the acquisition target would be a **multi-practitioner group practice or mini-DSO** with 5–15 dentists across 2–5 locations. These exist but are less common than single-practitioner cabinets.

**Alternative approach:** Acquire 3–5 solo/duo practices in a geographic cluster and consolidate them operationally. This “build-up” model is more realistic for deal flow but requires a different execution path.

### Team Structure (Multi-Site Group, ~€3–5M Revenue)

- **Lead dentist / practice owner** managing clinical standards and business development.
- **5–10 associate dentists** (salaried or on collaboration contracts).
- **10–15 dental assistants** (assistantes dentaires).
- **2–4 reception/admin staff** handling appointments, billing, insurance claims.
- **0–1 practice manager** (in more professionalized groups).

### Revenue Model

- **Convention care (soins conservateurs):** ~70% of activity. Fixed-fee treatments (fillings, extractions, basic restorative). Margins are tight.
- **Prosthetics:** ~19% of activity. Crowns, bridges, implants. Free pricing — this is where margin is made.
- **Other treatments (orthodontics, aesthetics, implantology):** ~11% and growing. Higher margin, less price-regulated.
- **Revenue per practitioner:** ~€350–450K depending on specialization mix.

### Margin Structure

- **Gross margin on convention care:** ~30–35% (constrained by regulated pricing).
- **Gross margin on prosthetics/aesthetics:** ~50–65%.
- **Overall net profit per practitioner:** ~€120–130K average (2022 data). This is “before personal social charges” — actual take-home is lower.
- **Key cost drivers:** Prosthetic lab fees (19% of revenue), supplies/materials, staff costs (10%), social charges (11%), rent/external charges (14%).

### Current Technology State

- **Practice management software:** Widely adopted (Logos, Julie, Visiodent, Desmos). This is a relative strength vs. construction trades.
- **Appointment booking:** Doctolib is dominant for patient scheduling. Most practices have some digital patient management.
- **Digital imaging:** X-ray and panoramic imaging are standard. CBCT (3D imaging) and intraoral scanners are growing but not universal.
- **AI adoption:** Very low in SME practices. Large DSOs are experimenting with AI-assisted diagnostics, but independent practices have near-zero adoption.
- **Insurance claims processing:** Semi-digital (teletransmission via Sesam-Vitale), but reconciliation and follow-up are often manual.

### Pain Points

- **Administrative burden:** Insurance claim management, Sécurité Sociale reconciliation, and mutuelle processing consume significant staff time.
- **Appointment no-shows:** A persistent problem. Doctolib reports substantial no-show rates. Each empty chair-hour is lost revenue.
- **Treatment plan acceptance:** Patients often delay or decline high-value prosthetic/aesthetic treatments. Follow-up is inconsistent.
- **Staff scheduling complexity:** Coordinating multiple dentists, assistants, hygienists, and chair availability across multi-site operations.
- **Inconsistent clinical protocols:** In group practices, standardization of treatment protocols and patient communication varies by practitioner.

-----

## 3. Ideal Acquisition Target Profile

### Must-Haves

- Revenue: €1.5–5M (recognizing the lower revenue ceiling per practice vs. construction trades). Multi-site or group practice preferred.
- At least 25% of revenue from non-convention treatments (prosthetics, aesthetics, implantology).
- Patient base ≥ 3,000 active patients.
- Digital practice management system in use.
- Practitioner retention: associate dentists on stable contracts (not all about to leave).

### Nice-to-Haves

- Multiple locations in the same city/département (enables operational consolidation).
- Existing Doctolib or equivalent online booking integration.
- CBCT or digital impression capability already installed.
- Practice manager in place (not just a lead dentist doing everything).

### Red Flags

- 100% convention-care practice with no prosthetic/aesthetic revenue (margin-constrained with limited AI upside).
- Single practitioner with no associates (zero scalability without recruiting).
- Practice in a zone where dentist density is already above average (high competition, lower patient loyalty).
- Significant pending litigation or malpractice history.

-----

## 4. AI Deployment Playbook

### Phase A — GenAI + RPA (Day 1 to Month 3)

|# |Intervention                                                                                                                                                                        |Framework Lever|Tool      |Expected Impact                                                                                             |
|--|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------|------------------------------------------------------------------------------------------------------------|
|A1|Insurance claim automation: RPA handles Sécurité Sociale teletransmission, mutuelle reconciliation, and payment follow-up.                                                          |1.1            |RPA       |30–50% reduction in admin time spent on billing. Frees reception staff for patient-facing work.             |
|A2|Appointment optimization: GenAI + RPA manages waitlists, cancellation backfilling, and automated no-show follow-up (SMS/email reminders with rebooking links).                      |1.1, 2.4       |GenAI, RPA|10–15% reduction in no-show rate. Each recovered appointment-hour is ~€100–200 in revenue.                  |
|A3|Treatment plan communication: GenAI drafts personalized patient communications explaining proposed treatments, costs, and reimbursement levels. Supports treatment acceptance.      |2.1, 2.2       |GenAI     |5–10% improvement in treatment plan acceptance rate, especially for high-value prosthetic work.             |
|A4|Knowledge codification and protocol standardization: GenAI-powered clinical protocol library. Standard treatment pathways, post-operative instructions, patient education materials.|1.3, 1.4       |GenAI, NLP|Improved consistency across practitioners in group settings. Reduces clinical variation and complaint rates.|
|A5|Automated patient recall: RPA schedules and sends recall reminders for periodic check-ups, hygiene visits, and follow-up appointments.                                              |2.4            |RPA       |Improved patient retention. 5–10% increase in recall visit completion.                                      |
|A6|Data instrumentation: Ensure practice management system captures all treatment data, appointment outcomes, patient demographics, and financial data in structured format.           |5.1            |—         |Enables Phase B.                                                                                            |

### Phase B — ML + Statistical (Month 6 to 18)

|# |Intervention                                                                                                                                                            |Framework Lever|Tool            |Expected Impact                                                                                                     |
|--|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------------|--------------------------------------------------------------------------------------------------------------------|
|B1|Treatment acceptance prediction: ML model identifies patients most likely to accept high-value treatment plans. Prioritizes follow-up effort and tailors communication. |2.1, 2.3       |ML              |Higher conversion on prosthetic/aesthetic treatments. Even 5% improvement on these high-margin services is material.|
|B2|Chair utilization optimization: Statistical model optimizes appointment slot allocation by treatment type, duration, and practitioner. Maximizes revenue per chair-hour.|1.5, 3.1       |Statistical     |5–10% improvement in chair utilization rate.                                                                        |
|B3|Patient lifetime value scoring: ML model segments patients by expected lifetime revenue. Informs retention, recall, and service priorities.                             |2.4            |ML              |Improved allocation of retention effort toward high-value patients.                                                 |
|B4|Procurement optimization: Aggregate material and lab purchasing across multiple practice sites. Statistical analysis of supplier pricing and volume opportunities.      |3.2            |Statistical, NLP|5–10% reduction in prosthetic lab costs and consumables (the single largest cost line).                             |

-----

## 5. Financial Impact Model (Illustrative)

### Baseline: Multi-Site Group (3 locations, 8 practitioners)

|Metric                            |Value        |
|----------------------------------|-------------|
|Revenue                           |€3.2M        |
|Convention care revenue (70%)     |€2.24M       |
|Prosthetic/aesthetic revenue (30%)|€0.96M       |
|Blended gross margin              |~40% (€1.28M)|
|Operating costs                   |€0.98M       |
|Net profit (pre-owner comp)       |€300K (9.4%) |

### Phase A Impact (Year 1): ~€120K incremental profit

Key contributors: billing automation (staff reallocation), no-show reduction (recovered revenue), treatment plan acceptance improvement (high-margin revenue uplift).

### Phase B Impact (Year 2): ~€80K incremental profit

Key contributors: chair utilization optimization, prosthetic lab cost reduction, targeted patient retention.

### Steady State (Year 2+)

|Metric    |Baseline|Post-AI|Change|
|----------|--------|-------|------|
|Revenue   |€3.2M   |€3.4M  |+6%   |
|Net profit|€300K   |€500K  |+67%  |
|Net margin|9.4%    |14.7%  |+5.3pp|

**Confidence level:** Medium-Low. This is lower confidence than the construction trades deep dives for three reasons: (1) convention pricing limits revenue upside on the majority of activity, (2) the target size requires multi-site group practices which are less common, and (3) the healthcare regulatory environment adds implementation complexity.

-----

## 6. Portfolio Logic

### Repeatable Playbook

The AI playbook is repeatable across dental practices because the operational model (appointments, billing, treatment plans, recalls) is standardized. The practice management software ecosystem (Logos, Julie, Visiodent) uses similar data structures, so integrations can be reused.

### Build-Up Strategy

The more likely execution path in France is a **build-up**: acquire 3–5 solo/duo practices in the same city or département, consolidate back-office (billing, procurement, scheduling), and deploy AI tools across the group. This creates a mini-DSO without requiring an existing multi-site practice to be available for sale.

### Shared Infrastructure

- **Centralized billing and insurance processing** across all practice locations.
- **Shared procurement** of consumables, prosthetic lab services (significant volume leverage — lab fees are 19% of revenue).
- **Shared AI tools** (appointment optimization, recall systems, treatment plan communication).
- **Centralized practice management** allowing the founding practitioners to focus on clinical work.

-----

## 7. Sector-Specific Risks

|Risk                                                                                                                                                                           |Severity   |Mitigation                                                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**Convention pricing constraints:** Core care pricing is regulated and has not kept pace with cost inflation.                                                                  |High       |Focus acquisition targets on practices with strong prosthetic/aesthetic mix (≥25% of revenue). AI levers are most impactful on the non-regulated revenue.      |
|**Regulatory complexity:** Healthcare in France is heavily regulated. CNIL (data protection), HAS (clinical standards), Ordre des chirurgiens-dentistes all impose constraints.|Medium-High|Dedicated compliance function in the portfolio. Legal counsel familiar with healthcare acquisitions. This is a structural barrier that also deters competitors.|
|**Practitioner recruitment and retention:** Dentists have high bargaining power. Associate turnover can destroy a multi-site practice.                                         |High       |Offer equity participation, better working conditions (AI handles admin, not clinical work), and modern equipment as retention tools.                          |
|**DSO competition:** Colosseum Dental Group (Dentelia), dental chains, and PE-backed DSOs are consolidating in France.                                                         |Medium     |They target larger urban practices. The rural and semi-urban build-up strategy avoids direct competition. But valuations may rise as the DSO model matures.    |
|**Patient data sensitivity:** Healthcare data is subject to stricter GDPR and French law requirements. AI tools must be compliant.                                             |Medium     |Use healthcare-certified software vendors. Ensure all AI processing respects CNIL requirements and data is stored in France/EU.                                |

-----

## 8. Comparative Assessment

|Dimension            |86.23 Rating|Comparison to 43.22/43.21                                                                                                                                                                                            |
|---------------------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|AI fit (Phase A)     |★★★★☆       |Strong on admin automation. Weaker on operational levers (dentists’ core work is clinical, not schedulable in the same way as technician crews).                                                                     |
|AI fit (Phase B)     |★★★☆☆       |Treatment acceptance and chair optimization are valuable but smaller in magnitude than construction trade levers.                                                                                                    |
|Fragmentation        |★★★★★       |Extremely fragmented.                                                                                                                                                                                                |
|Business quality     |★★★★★       |High margins on prosthetics, strong recurring demand, regulatory protection, patient loyalty. Best business quality of any sector screened.                                                                          |
|Structural tailwinds |★★★★☆       |Aging population, growing cosmetic demand, digital dentistry. Solid but less acute than the energy transition tailwind for construction trades.                                                                      |
|AI disruption risk   |★★☆☆☆       |Low for now. AI-assisted diagnostics may eventually shift the clinical skill distribution, but the physical chair-side work remains human. Scored 4 in screening, but the long-term trajectory warrants some caution.|
|Deal flow feasibility|★★★☆☆       |Weaker than construction trades. Multi-site group practices are rare. Build-up strategy is viable but slower and more complex.                                                                                       |
|Portfolio scalability|★★★☆☆       |Repeatable playbook exists, but healthcare regulations, practitioner recruitment, and convention pricing constraints limit the speed and scale of the rollup.                                                        |

**Overall: Strong second-tier sector.** Excellent business quality and AI fit, but deal flow challenges, convention pricing constraints, and regulatory complexity make it harder to execute than construction trades. Best suited as a diversifying second vertical after the 43.21/43.22 portfolio is established, or for an investor group with healthcare operational expertise.
