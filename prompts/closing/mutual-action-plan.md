# Mutual Action Plan (MAP) Template

**Use Case:** To collaboratively build a shared, milestone-driven plan with your prospect that aligns both sides on the steps, owners, and dates needed to reach a successful decision and go-live.
**Input Required:** [prospect company name], [primary contact name and role], [proposed solution], [target go-live date], [key milestones already completed], [known stakeholders and approvals required], [potential risks or blockers]

## Prompt

```text
I am working a deal with [prospect company name]. My primary contact is [primary contact name and role] and we are proposing [proposed solution] with a target go-live date of [target go-live date].

We have already completed the following milestones: [key milestones already completed] (e.g., "initial discovery call," "technical demo with IT team").

The known stakeholders and approvals required are: [known stakeholders and approvals required] (e.g., "Legal review of contract," "CFO budget sign-off," "IT security assessment").

Potential risks or blockers include: [potential risks or blockers] (e.g., "budget freeze in Q3," "competing initiative from another vendor").

Generate a Mutual Action Plan that includes:
1.  **Milestone Table:** A reverse-engineered timeline from the target go-live date to today, with each milestone listed as a row containing: Step, Owner (Buyer or Seller), Target Date, and Status.
2.  **Buyer-Side Actions:** Specific internal steps the prospect must complete (e.g., security review, legal redline, executive sponsor briefing) with suggested owners.
3.  **Seller-Side Actions:** Specific steps my team must deliver (e.g., custom demo, ROI analysis, reference call, SOW delivery) with suggested owners.
4.  **Risk Mitigation:** For each identified risk or blocker, suggest a specific mitigation action and when it should be addressed.
5.  **Next Steps:** The immediate next 2-3 actions both sides should take this week to keep the plan on track.

Format the milestone table in Markdown so I can share it directly with the prospect.
```

## Example

**Input:**
-   Prospect Company: Acme Manufacturing
-   Primary Contact: Sarah Chen, VP of Operations
-   Proposed Solution: Warehouse automation platform (3-year SaaS contract)
-   Target Go-Live: June 1, 2026
-   Milestones Completed: Discovery call, on-site assessment, technical demo with warehouse team
-   Stakeholders/Approvals: CFO budget approval, IT security review, Legal contract review, VP of Supply Chain alignment
-   Risks: Q2 budget cycle may delay CFO approval; IT team is mid-migration on another system

**Output:**

## Mutual Action Plan — Acme Manufacturing × [Your Company]

**Objective:** Go live with warehouse automation platform by June 1, 2026.

### Milestone Table

| # | Step | Owner | Target Date | Status |
|---|------|-------|-------------|--------|
| 1 | Finalize business case & ROI analysis | Seller | Feb 24 | ✅ In Progress |
| 2 | Present ROI to Sarah + VP of Supply Chain | Joint | Mar 3 | ⬜ Not Started |
| 3 | IT security questionnaire submitted | Seller | Mar 5 | ⬜ Not Started |
| 4 | IT security review completed | Buyer (IT) | Mar 19 | ⬜ Not Started |
| 5 | Reference call with similar manufacturer | Seller | Mar 10 | ⬜ Not Started |
| 6 | Executive sponsor briefing with CFO | Buyer (Sarah) | Mar 24 | ⬜ Not Started |
| 7 | CFO budget approval | Buyer (CFO) | Apr 1 | ⬜ Not Started |
| 8 | SOW / contract delivered | Seller | Apr 7 | ⬜ Not Started |
| 9 | Legal redline and review | Buyer (Legal) | Apr 21 | ⬜ Not Started |
| 10 | Contract signed | Joint | Apr 28 | ⬜ Not Started |
| 11 | Implementation kickoff | Joint | May 5 | ⬜ Not Started |
| 12 | Go-live | Joint | Jun 1 | ⬜ Not Started |

### Buyer-Side Actions
-   **Sarah Chen (VP Ops):** Schedule executive sponsor briefing with CFO; align VP of Supply Chain on business case.
-   **IT Team:** Complete security review within 2 weeks of questionnaire submission; confirm no conflicts with current migration timeline.
-   **Legal:** Complete contract redline within 2 weeks of SOW delivery.
-   **CFO:** Approve budget allocation before Q2 cycle lock.

### Seller-Side Actions
-   **Account Executive:** Deliver finalized ROI analysis; coordinate reference call; draft and deliver SOW.
-   **Solutions Engineer:** Complete and submit IT security questionnaire; support any technical follow-up questions.
-   **Customer Success:** Prepare implementation kickoff plan and onboarding timeline.

### Risk Mitigation

| Risk | Mitigation | Timing |
|------|-----------|--------|
| Q2 budget cycle delays CFO approval | Accelerate executive briefing to early March; provide pre-built budget justification memo for Sarah to share | Week of Feb 24 |
| IT mid-migration conflicts | Schedule a 30-min call with IT lead to confirm security review bandwidth and flag any scheduling conflicts early | Week of Mar 3 |

### Next Steps (This Week)
1.  **Seller:** Send draft ROI analysis to Sarah for review by Friday.
2.  **Sarah:** Confirm availability for joint presentation with VP of Supply Chain the week of Mar 3.
3.  **Seller:** Send IT security questionnaire to Sarah's IT contact.

## Tips
- Share the MAP with your prospect as a collaborative document — it should feel like a joint plan, not a seller's checklist.
- Review the MAP together on every call and update statuses in real time. This keeps accountability on both sides.
- Work backward from the go-live date. If a milestone slips, immediately adjust downstream dates and flag the impact.
- Use the MAP to uncover hidden steps. Ask your prospect: "What internal steps am I missing that could surprise us?"
- A MAP that only has seller actions is a project plan, not a mutual plan. Ensure genuine buyer-side ownership.
