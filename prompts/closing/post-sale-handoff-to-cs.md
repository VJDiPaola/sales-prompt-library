# Post-Sale Handoff to Customer Success

**Use Case:** To generate a comprehensive internal handoff document that transfers every critical piece of deal context from the Account Executive to the Customer Success Manager — ensuring the customer never has to repeat themselves, the CS team inherits the full political landscape, and the account is set up for long-term retention and expansion from Day 1.
**Input Required:** [customer name], [CS manager name], [AE name], [contract details — ACV, term, start date, billing structure], [primary contact and role], [executive sponsor and role], [full stakeholder map — names, titles, roles in the deal, and disposition], [original business problem and quantified pain], [success metrics agreed during the sale], [product capabilities purchased and any features explicitly excluded], [competitive alternatives they evaluated and why they chose us], [implementation requirements and technical environment], [known risks, sensitivities, or political dynamics], [promises made during the sales process — explicit and implied], [expansion opportunities identified but not sold], [key dates — go-live target, first QBR, renewal date]

## Prompt

```text
I am a SaaS Account Executive and I just closed a deal with [customer name]. I need to create a thorough internal handoff document for [CS manager name], the assigned Customer Success Manager, so they can onboard this customer with full context and set the account up for long-term success.

**Contract details:**
-   AE: [AE name]
-   ACV: [contract details — ACV, term, start date, billing structure]

**Customer contacts:**
-   Primary Day-to-Day Contact: [primary contact and role]
-   Executive Sponsor: [executive sponsor and role]
-   Full Stakeholder Map: [full stakeholder map — names, titles, roles in the deal, and disposition]
    (e.g., "Sarah Chen, VP Ops — Champion, highly engaged; Tom Liu, IT Director — Supportive but cautious on timeline; James Park, CFO — Signed off but skeptical, needs ROI proof at 90 days; Nina Patel, End User Lead — Was not involved in evaluation, will need onboarding attention")

**Business context:**
-   Original Business Problem: [original business problem and quantified pain]
-   Agreed Success Metrics: [success metrics agreed during the sale]
-   What They Bought (and didn't buy): [product capabilities purchased and any features explicitly excluded]
-   Competitive Alternatives Evaluated: [competitive alternatives they evaluated and why they chose us]

**Technical context:**
-   Implementation Requirements: [implementation requirements and technical environment]
    (e.g., "Integrate with Salesforce (Enterprise edition), SSO via Okta, data migration from legacy system, API connection to their data warehouse")

**Deal dynamics (critical for CS):**
-   Known Risks, Sensitivities, or Political Dynamics: [known risks, sensitivities, or political dynamics]
    (e.g., "CFO was the last to approve and set a hard 90-day ROI checkpoint; IT team is stretched thin with another migration; the VP of Sales who championed this reports to a new CRO who wasn't involved in the evaluation")
-   Promises Made During the Sales Process: [promises made during the sales process — explicit and implied]
    (e.g., "Committed to a dedicated onboarding specialist for the first 30 days; implied we could customize the dashboard layout; told them implementation would be 'about 6 weeks'")
-   Expansion Opportunities: [expansion opportunities identified but not sold]

**Key dates:**
-   [key dates — go-live target, first QBR, renewal date]

Generate a comprehensive Post-Sale Handoff Document with the following sections:

1.  **Account Overview & Deal Summary:** A concise summary of who the customer is, what they bought, the contract structure, and why they bought. This should give the CSM a complete picture in 60 seconds.

2.  **Stakeholder Intelligence Brief:** For each stakeholder, provide:
    -   Their role in the organization and in this deal (Champion, Economic Buyer, Technical Evaluator, End User, Blocker, etc.)
    -   Their communication style and preferences (if known)
    -   Their personal win — what they individually care about getting from this solution
    -   Their current disposition (Enthusiastic, Supportive, Neutral, Skeptical)
    -   Recommended CS engagement approach for each person

3.  **Success Criteria & Measurement Plan:** A clear definition of what "success" looks like for this customer, including:
    -   The specific metrics they expect to improve (with baseline numbers from discovery)
    -   The timeline for when they expect to see results
    -   How success will be measured and reported
    -   Who on the customer side is accountable for each metric
    -   A recommended QBR cadence and agenda framework

4.  **Promises & Commitments Register:** A detailed log of every commitment made during the sales process — both explicit contractual commitments and informal verbal commitments. For each, note:
    -   What was promised
    -   Who it was promised to
    -   When it was promised
    -   Current status (fulfilled, pending, or at-risk)
    -   Owner on our side responsible for delivery
    This section is critical. Broken promises are the #1 cause of early churn.

5.  **Risk Register & Early Warning Signals:** A list of known risks to the account's success, including:
    -   Political risks (org changes, skeptical stakeholders, champion dependency)
    -   Technical risks (complex integrations, resource constraints, data quality)
    -   Adoption risks (change management gaps, end-user resistance, competing priorities)
    -   Timeline risks (aggressive go-live date, dependency on customer-side resources)
    For each risk, provide a severity level, a trigger signal to watch for, and a recommended mitigation action.

6.  **Implementation & Onboarding Roadmap:** A recommended phased onboarding plan including:
    -   Phase 1 (Week 1-2): Technical setup, integrations, data migration
    -   Phase 2 (Week 3-4): Admin training, workflow configuration, pilot user group
    -   Phase 3 (Week 5-6): Full user rollout, end-user training, go-live
    -   Phase 4 (Week 7-12): Adoption monitoring, optimization, first QBR
    Include specific milestones, owners, and dependencies for each phase.

7.  **Expansion & Growth Roadmap:** A forward-looking view of where this account can grow, including:
    -   Products or modules they didn't buy but showed interest in
    -   Additional teams, departments, or business units that could benefit
    -   Trigger events or success milestones that would open the expansion conversation
    -   Recommended timing for the first expansion discussion

8.  **Warm Introduction Plan:** A script for the AE to use when introducing the CSM to the customer's primary contact and executive sponsor, designed to:
    -   Transfer credibility and trust from the AE to the CSM
    -   Reinforce the customer's decision to buy
    -   Set expectations for the CS relationship
    -   Position the first onboarding call
```

## Example

**Input:**
-   Customer Name: Apex Logistics
-   CS Manager: Jordan Rivera
-   AE: Lauren Mitchell
-   Contract: $220K ACV, 3-year term, annual billing, starts April 1, 2026
-   Primary Contact: Derek Huang, Director of Fleet Operations
-   Executive Sponsor: Patricia Morales, COO
-   Stakeholder Map: Derek Huang, Director of Fleet Ops — Champion, highly engaged, drove the evaluation; Patricia Morales, COO — Executive Sponsor, supportive, wants quarterly updates on ROI; Kevin Tran, VP of IT — Technical Evaluator, supportive but firm on security requirements; Aisha Johnson, Fleet Manager (Southeast Region) — End User Lead, was part of the pilot, enthusiastic; Bill Crawford, CFO — Signed off reluctantly, set a hard 6-month ROI review; Maria Santos, VP of HR — Not involved in evaluation, but her team will be impacted by workflow changes
-   Original Business Problem: Manual route planning costing $1.8M/year in excess fuel, overtime, and missed deliveries across 400 vehicles in 3 regions
-   Success Metrics: Reduce fuel costs by 15%, cut route planning time from 4 hours to 30 minutes per day, improve on-time delivery rate from 91% to 97%
-   What They Bought: Route optimization platform (all 3 regions), real-time GPS tracking, driver mobile app, analytics dashboard. Did NOT buy: predictive maintenance module, customer delivery notifications
-   Competitive Alternatives: RouteMaster ($160K/year, weaker optimization algorithm) and manual expansion of existing spreadsheet process
-   Implementation Requirements: Integrate with SAP TM (transportation management), GPS hardware already installed on 380 of 400 vehicles (20 need retrofitting), SSO via Azure AD, historical route data migration (2 years)
-   Known Risks: CFO set a hard 6-month ROI checkpoint; IT team is simultaneously migrating to a new ERP; 20 vehicles need GPS hardware installed before full go-live; Southeast region (Aisha's team) is enthusiastic but Northeast region has not been involved yet; Patricia reports to a new CEO who started in January and wasn't involved in the deal
-   Promises Made: Dedicated implementation manager for first 60 days; told Derek route planning time would drop to "under 30 minutes" by Week 6; committed to a custom analytics dashboard view for Patricia's monthly board report; implied we could integrate with their future ERP (SAP S/4HANA migration planned for Q4)
-   Expansion Opportunities: Predictive maintenance module ($45K/year) — Derek expressed strong interest for Year 2; customer delivery notifications ($30K/year) — Patricia mentioned this as a future priority; 2 additional distribution centers opening in Q1 2027
-   Key Dates: Go-live target May 15, 2026; first QBR August 1, 2026; 6-month ROI review October 1, 2026; renewal date April 1, 2029

**Output:**

## Post-Sale Handoff Document — Apex Logistics

**Prepared by:** Lauren Mitchell (AE) → **For:** Jordan Rivera (CSM)
**Date:** March 28, 2026

---

### 1. Account Overview & Deal Summary

**Customer:** Apex Logistics — mid-market logistics company operating 400 vehicles across 3 U.S. regions (Southeast, Northeast, Central).

**What They Bought:** Route optimization platform with real-time GPS tracking, driver mobile app, and analytics dashboard for all 3 regions. 3-year term, $220K ACV, annual billing, starting April 1, 2026.

**Why They Bought:** Manual route planning was costing them $1.8M/year in excess fuel, driver overtime, and missed deliveries. Their Director of Fleet Operations, Derek Huang, championed the evaluation after calculating that their route planners were spending 4 hours per day building routes in spreadsheets. The COO, Patricia Morales, sponsored the deal because on-time delivery had dropped to 91% and was becoming a customer retention issue.

**Why They Chose Us Over Alternatives:** RouteMaster was $60K/year cheaper but their optimization algorithm couldn't handle Apex's multi-stop, multi-constraint routing (temperature-controlled + time-window deliveries). The internal spreadsheet expansion was rejected by Derek as unsustainable at scale.

**What They Did NOT Buy:** Predictive maintenance module and customer delivery notifications. Both are expansion opportunities (see Section 7).

---

### 2. Stakeholder Intelligence Brief

**Derek Huang — Director of Fleet Operations**
-   **Deal Role:** Champion. Drove the entire evaluation, built the internal business case, and personally presented to the CFO.
-   **Communication Style:** Data-driven, detail-oriented, prefers email with supporting documentation. Responds quickly. Likes to be consulted before decisions are made, not informed after.
-   **Personal Win:** He wants to be seen as the person who modernized Apex's fleet operations. A successful rollout strengthens his case for a VP promotion.
-   **Disposition:** Enthusiastic — deeply invested in the success of this project.
-   **CS Approach:** Treat Derek as your primary partner. Give him early visibility into metrics so he can report wins up the chain. He will be your best internal advocate if he feels informed and respected.

**Patricia Morales — COO (Executive Sponsor)**
-   **Deal Role:** Executive Sponsor. Approved the budget and set the strategic direction. Wants ROI data for her monthly board report.
-   **Communication Style:** High-level, outcome-focused. Does not want to be in the weeds. Prefers a monthly 15-minute update or a polished dashboard she can pull from herself.
-   **Personal Win:** She needs to show the board that operational efficiency is improving under her leadership. On-time delivery rate is her marquee metric.
-   **Disposition:** Supportive — trusts Derek's judgment, but will disengage if she doesn't see results surfaced proactively.
-   **CS Approach:** Build the custom board report dashboard early (this was a promise — see Section 4). Send a monthly executive summary email. Keep it to 5 lines and 3 numbers. Don't schedule meetings with Patricia unless Derek recommends it.

**Kevin Tran — VP of IT**
-   **Deal Role:** Technical Evaluator. Approved the security assessment and integration architecture.
-   **Communication Style:** Thorough, process-oriented. Wants technical documentation ahead of any call. Will hold us to SLAs.
-   **Personal Win:** A clean implementation that doesn't disrupt his ERP migration timeline or create security incidents.
-   **Disposition:** Supportive but cautious. He's stretched thin with the SAP S/4HANA migration in Q4.
-   **CS Approach:** Proactively share technical status updates weekly during implementation. Never surprise Kevin with a change. Loop in our Solutions Engineering team for any integration questions — Kevin will escalate fast if he feels under-supported.

**Aisha Johnson — Fleet Manager, Southeast Region**
-   **Deal Role:** End User Lead for the pilot region. Participated in the evaluation and tested the product.
-   **Communication Style:** Hands-on, practical, quick to give feedback. Prefers Slack or phone over email.
-   **Personal Win:** She wants her drivers to stop complaining about inefficient routes and late-night rework.
-   **Disposition:** Enthusiastic — she's already seen the product in action and is a vocal advocate.
-   **CS Approach:** Leverage Aisha as a power user and internal trainer for the other regions. She can be the bridge to the Northeast region, which hasn't been involved yet. Ask her to co-lead end-user training sessions.

**Bill Crawford — CFO**
-   **Deal Role:** Economic Buyer. Approved the $220K spend reluctantly and set a hard 6-month ROI review on October 1.
-   **Communication Style:** Numbers only. Does not care about features or functionality — cares about dollars in vs. dollars out.
-   **Personal Win:** He needs to justify this spend to the new CEO. If the ROI is clear, he looks smart. If it's not, he'll be the first to push for cancellation.
-   **Disposition:** Skeptical. He approved the deal but is not emotionally invested. He will be a churn risk if we don't deliver measurable ROI by October.
-   **CS Approach:** Do not engage Bill directly unless invited. Feed all financial data through Derek and Patricia. Build toward the October 1 ROI review from Day 1 — this is the single most important milestone for retention. Have the ROI case airtight by September.

**Maria Santos — VP of HR**
-   **Deal Role:** Not involved in evaluation. Her team will be impacted by workflow changes (driver scheduling, route assignments).
-   **Communication Style:** Unknown — Lauren did not interact with Maria during the sales process.
-   **Personal Win:** Unknown — but likely cares about driver satisfaction and change management.
-   **Disposition:** Neutral — unaware of the project details.
-   **CS Approach:** Flag Maria as a stakeholder to engage during Phase 2 (admin training / workflow configuration). Derek should make the introduction. If driver workflows change significantly, Maria's team may need to update scheduling policies. Ignoring HR is a common adoption risk in fleet tech rollouts.

---

### 3. Success Criteria & Measurement Plan

| Success Metric | Baseline (Current) | Target | Timeline | Owner (Customer) |
|---|---|---|---|---|
| Fuel cost reduction | $1.2M/year in fuel | 15% reduction ($180K savings) | Measurable by Month 4 | Derek Huang |
| Route planning time | 4 hours/day per planner | Under 30 minutes/day | By Week 6 (go-live) | Derek Huang |
| On-time delivery rate | 91% | 97% | By Month 6 (Oct 1 ROI review) | Patricia Morales |

**How Success Will Be Measured:**
-   Fuel cost data: Pulled from SAP TM integration — compare monthly fuel invoices pre- and post-implementation.
-   Route planning time: Self-reported by planners in Weeks 1-2 (baseline), then tracked via platform time-to-plan analytics.
-   On-time delivery rate: Tracked via real-time GPS data against delivery windows — dashboard metric available from Day 1 of go-live.

**QBR Cadence:** Quarterly, starting August 1, 2026.

**Recommended QBR Agenda:**
1.  Success metrics scorecard (5 min) — green/yellow/red on each metric
2.  Usage and adoption data (5 min) — active users, feature utilization by region
3.  Customer feedback and open issues (10 min) — what's working, what's not
4.  Roadmap preview and expansion discussion (5 min) — new features, additional modules
5.  Action items and next steps (5 min)

**⚠️ Critical Milestone — October 1 ROI Review:**
Bill Crawford set a hard 6-month checkpoint. Jordan, this is the renewal decision in disguise. Start building the ROI narrative from Week 1. By September 1, you should have a draft ROI report ready for Derek to review before it reaches Bill. Do not wait until September to start pulling numbers.

---

### 4. Promises & Commitments Register

| # | Promise | Made To | When | Status | Owner (Our Side) |
|---|---------|---------|------|--------|-----------------|
| 1 | Dedicated implementation manager for first 60 days | Derek Huang | During negotiation (Feb 2026) | ⬜ Pending — must assign before April 1 kickoff | CS / Implementation Team |
| 2 | Route planning time under 30 minutes by Week 6 | Derek Huang | Discovery call (Jan 2026) | ⬜ Pending — this is a hard expectation | Implementation Manager |
| 3 | Custom analytics dashboard view for Patricia's monthly board report | Patricia Morales | Proposal meeting (Feb 2026) | ⬜ Pending — needs scoping during Phase 2 | CSM + Product |
| 4 | Future ERP integration support (SAP S/4HANA) | Kevin Tran | Technical review (Feb 2026) | ⚠️ Implied, not contractual — Lauren said "we can work with you on that" but no formal commitment. Kevin may expect this is included. | CSM — clarify scope early |
| 5 | GPS hardware retrofit for 20 remaining vehicles | Derek Huang | Implementation planning (March 2026) | ⬜ Pending — customer responsibility, but Lauren offered to coordinate with our hardware partner | AE + Implementation |

**⚠️ Highest Risk Promise:** #4 — the implied ERP integration. Kevin may bring this up during implementation. Jordan, get ahead of this. In Week 1, confirm with Kevin what his expectations are for S/4HANA integration support. If it's out of scope, set that expectation now — not in Q4 when his migration starts. If it requires a professional services engagement, surface that early so it becomes an expansion conversation, not a broken promise.

---

### 5. Risk Register & Early Warning Signals

| # | Risk | Severity | Trigger Signal | Mitigation |
|---|------|----------|---------------|------------|
| 1 | **CFO 6-month ROI checkpoint** — Bill may push to cancel or renegotiate if ROI is unclear by October 1 | 🔴 High | Bill asks for an unscheduled financial review before October; Derek reports "Bill is asking questions about the spend" | Build ROI tracking from Day 1. Deliver a preliminary ROI snapshot at the first QBR (August). Give Derek and Patricia the data to pre-sell Bill before October. |
| 2 | **IT bandwidth — ERP migration conflict** — Kevin's team is simultaneously migrating to SAP S/4HANA in Q4, creating resource contention for our integration work | 🟡 Medium | Kevin delays integration milestones or stops responding to technical requests in Q3 | Front-load all integration work into Phase 1 (April). Get SAP TM connected before Kevin's team pivots to S/4HANA. Confirm Kevin's resource availability in Week 1. |
| 3 | **Northeast region adoption gap** — This region was not involved in the evaluation. Drivers and planners there may resist the change. | 🟡 Medium | Low login rates from Northeast users in Weeks 5-6; complaints or workaround reports from Northeast fleet managers | Use Aisha (Southeast) as an internal advocate. Schedule a dedicated Northeast onboarding session. Identify a Northeast fleet manager early to serve as a regional champion. |
| 4 | **20 vehicles without GPS hardware** — Full go-live requires all 400 vehicles instrumented. 20 still need retrofitting. | 🟡 Medium | Hardware vendor delays; vehicles not retrofitted by go-live date | Confirm hardware order status in Week 1. If there's a delay risk, plan for a phased go-live (380 vehicles first, 20 added post-retrofit) rather than holding up the entire rollout. |
| 5 | **New CEO — unknown relationship** — Patricia's new CEO (started January) wasn't part of the deal. If the CEO questions the spend, Patricia may not have full air cover. | 🟡 Medium | Patricia mentions the CEO is "reviewing all major vendor contracts" or asks for additional justification materials | Prepare an executive briefing one-pager for Patricia to share with the CEO proactively. Include the business case, competitive rationale, and early wins. It's better for Patricia to introduce us on her terms than for the CEO to discover us during a cost review. |
| 6 | **Maria Santos (HR) — unmanaged stakeholder** — Workflow changes will affect driver scheduling, and HR hasn't been briefed. | 🟢 Low | Maria raises concerns about driver workflow changes after rollout; HR pushes back on new scheduling processes | Derek should introduce Jordan to Maria during Phase 2. A 30-minute briefing on what's changing and how it benefits drivers will prevent an avoidable blocker. |

---

### 6. Implementation & Onboarding Roadmap

**Phase 1 — Technical Foundation (Weeks 1-2: April 1-14)**
- [ ] Assign dedicated implementation manager (fulfill Promise #1)
- [ ] Kickoff call: Jordan + Implementation Manager + Derek + Kevin
- [ ] SAP TM integration: begin API configuration and data mapping
- [ ] Azure AD SSO setup and testing
- [ ] Historical route data migration (2 years of data from legacy system)
- [ ] Confirm GPS hardware retrofit timeline for 20 remaining vehicles
- [ ] Clarify S/4HANA integration expectations with Kevin (address Promise #4)
-   **Owners:** Implementation Manager (our side), Kevin Tran (IT)
-   **Dependency:** Kevin's availability — confirm in kickoff call

**Phase 2 — Configuration & Pilot (Weeks 3-4: April 15-28)**
- [ ] Configure platform for Apex's 3-region structure (Southeast, Northeast, Central)
- [ ] Build custom analytics dashboard view for Patricia's board report (fulfill Promise #3)
- [ ] Admin training for Derek and 2 regional fleet managers
- [ ] Pilot launch with Southeast region (Aisha's team — 140 vehicles)
- [ ] Introduce Jordan to Maria Santos (HR) — brief on workflow changes
- [ ] Collect baseline route planning time data from planners (for ROI tracking)
-   **Owners:** CSM + Implementation Manager (our side), Derek + Aisha (customer side)
-   **Dependency:** SAP TM integration must be complete before pilot data flows correctly

**Phase 3 — Full Rollout & Go-Live (Weeks 5-6: April 29 - May 15)**
- [ ] Expand to Northeast and Central regions
- [ ] End-user training: drivers (mobile app) and planners (desktop platform)
- [ ] Dedicated Northeast onboarding session — identify and enable a regional champion
- [ ] Validate route planning time is trending toward <30-minute target (Promise #2)
- [ ] Go-live: May 15, 2026 — all 3 regions, all vehicles (or phased if 20 retrofits aren't complete)
- [ ] Go-live celebration email from Derek to his team (CSM to draft, Derek to send)
-   **Owners:** CSM (our side), Derek + regional fleet managers (customer side)
-   **Dependency:** GPS retrofits on remaining 20 vehicles

**Phase 4 — Adoption & Optimization (Weeks 7-12: May 16 - July 15)**
- [ ] Weekly adoption check-ins with Derek (first 4 weeks post-go-live)
- [ ] Monitor usage dashboards: daily active users, feature adoption by region, route optimization acceptance rate
- [ ] Address any driver app adoption issues (common: drivers reverting to old habits in Week 2-3)
- [ ] Optimize routing algorithms based on real-world Apex data (first 30 days of data)
- [ ] Prepare preliminary ROI snapshot for first QBR (August 1)
- [ ] First QBR: August 1, 2026
-   **Owners:** CSM (our side), Derek (customer side)
-   **Success Gate:** By July 15, all three regions should show >80% daily active user rate and route planning time should be under 45 minutes (trending toward 30)

---

### 7. Expansion & Growth Roadmap

| Opportunity | Est. Value | Interest Level | Trigger Event | Recommended Timing |
|---|---|---|---|---|
| **Predictive Maintenance Module** | $45K/year | High — Derek explicitly asked about this for Year 2 | Successful go-live + Derek seeing maintenance cost data in the analytics dashboard | Month 6-8 (after October ROI review proves base platform value) |
| **Customer Delivery Notifications** | $30K/year | Medium — Patricia mentioned as a future priority for customer experience | On-time delivery rate hits 95%+ and Patricia is ready to invest in customer-facing improvements | Month 9-12 |
| **2 New Distribution Centers (Q1 2027)** | ~$75K/year (incremental licensing) | High — confirmed by Derek, facilities under construction | Derek confirms operational launch dates for new centers | Month 10-12 (begin scoping before centers open) |
| **SAP S/4HANA Integration (Post-Migration)** | Professional services engagement (TBD) | Medium — Kevin expects some level of support (see Promise #4) | Kevin's ERP migration reaches UAT phase in Q4 2026 | Q1 2027 (after their migration stabilizes) |

**Total Year 2 Expansion Potential:** $150K+ ACV uplift

**Expansion Principles:**
-   Never pitch expansion before the base platform is delivering measurable value. Derek and Patricia must both be able to say "this is working" before we ask for more.
-   Use the first QBR to plant seeds. Share a roadmap slide that includes the modules they didn't buy. Let Derek react — don't sell.
-   The October ROI review is the expansion gate. If Bill Crawford sees clear ROI, he becomes an ally rather than a blocker for Year 2 investment.

---

### 8. Warm Introduction Plan

**Email from Lauren (AE) to Derek and Patricia, cc: Jordan (CSM)**

Subject: Introducing Jordan Rivera — Your Dedicated Customer Success Manager

"Derek, Patricia —

I'm thrilled that we're officially kicking off together. Working with you both over the past few months has been a highlight — the rigor you brought to evaluating this decision gives me full confidence that we're going to deliver real results for Apex.

I want to introduce you to Jordan Rivera, who will be your dedicated Customer Success Manager from here forward. Jordan is one of our best — they've led onboarding for several of our logistics customers and they know the fleet operations world inside and out.

Jordan has the full context of our conversations — the goals we set around fuel cost reduction, route planning efficiency, and on-time delivery — and they'll be your primary point of contact for everything from implementation through your first QBR and beyond.

Jordan will be reaching out this week to schedule your kickoff call and walk through the onboarding timeline. I'll join that first call to make sure the transition is seamless, and I'll stay involved for any commercial or strategic conversations.

Thank you again for your partnership. I'm looking forward to celebrating some big wins together.

Best,
Lauren"

**Talking points for Lauren on the first joint call (5 minutes):**
1.  "Derek, Patricia — I want to personally hand this off and make sure you never have to repeat anything you've already told me. Jordan has the full picture."
2.  "Jordan, why don't you share a bit about your background and how you'll be working with the Apex team?" (Let Jordan build their own credibility.)
3.  "I'll stay connected for anything strategic or commercial, but Jordan is your go-to from here. You're in great hands."
4.  Transition to Jordan leading the kickoff agenda.

## Tips
- The handoff is the most fragile moment in the customer lifecycle. If the customer feels like they're starting over with a stranger, trust erodes immediately. The AE must personally transfer credibility to the CSM.
- Document every promise — especially the informal ones. "We can probably do that" during a sales call becomes "you committed to that" in the customer's mind. Surface these early so the CS team can manage expectations before they become complaints.
- The stakeholder map is not a list of names — it's a political intelligence brief. The CSM needs to know who is enthusiastic, who is skeptical, who has power, and who is watching from the sidelines. This is what separates a good handoff from a great one.
- Start building toward the first major milestone (in this case, the October ROI review) from Day 1. If you wait until Month 4 to think about Month 6, you're already behind.
- A Presidents Club AE doesn't disappear after the close. They stay involved through the first QBR, attend the executive sponsor check-in, and show up when expansion conversations begin. Your commission is earned at close; your reputation is earned in renewal.
