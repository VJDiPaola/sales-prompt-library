# Demo Preparation Checklist

**Use Case:** To generate a comprehensive, deal-specific demo preparation plan that ensures every demo is tailored, stakeholder-aware, and outcome-driven — the way a Presidents Club SaaS AE would prepare for a high-stakes live demo.
**Input Required:** [prospect company name], [industry], [attendees — names, titles, and known priorities], [discovery insights — pains, current state, desired outcomes], [deal stage and deal size], [competitive alternatives prospect is evaluating], [specific product capabilities to showcase], [demo date and duration]

## Prompt

```text
I am a SaaS Account Executive preparing for a live product demo with [prospect company name] in the [industry] industry.

**Demo logistics:**
-   Date: [demo date and duration]
-   Deal stage: [deal stage and deal size]

**Attendees and their priorities:**
[attendees — names, titles, and known priorities]
(e.g., "Sarah Chen, VP Ops — cares about reducing manual work; James Liu, IT Director — focused on security and integrations; Mark Torres, CFO — needs ROI justification")

**Discovery insights (pains, current state, desired outcomes):**
[discovery insights — pains, current state, desired outcomes]
(e.g., "Currently using spreadsheets for inventory tracking, losing ~$200K/year in stockouts, goal is real-time visibility across 12 warehouses")

**Competitive alternatives being evaluated:**
[competitive alternatives prospect is evaluating]
(e.g., "Evaluating CompetitorX and building in-house")

**Key product capabilities I plan to show:**
[specific product capabilities to showcase]
(e.g., "Real-time dashboard, automated reorder rules, API integrations with their ERP")

Generate a comprehensive Demo Preparation Checklist covering the following sections:

1.  **Pre-Demo Research & Intel:** A list of specific research tasks I should complete before the demo — company news, earnings, org changes, LinkedIn research on each attendee, and any industry trends I should reference to demonstrate credibility.

2.  **Stakeholder-Specific Game Plan:** For each attendee, provide:
    -   Their likely top question or concern
    -   The 1-2 product moments in the demo that will resonate most with them
    -   A tailored "so what" statement connecting our capability to their specific priority

3.  **Demo Storyline & Flow:** A narrative arc for the demo structured as:
    -   **Opening Hook (2 min):** A compelling opening that references their specific pain and sets the agenda around outcomes, not features
    -   **Current State → Pain (3 min):** How to reflect back what I learned in discovery to build emotional buy-in before showing anything
    -   **Product Walkthrough (core of demo):** The recommended sequence of product capabilities to show, ordered by impact — lead with the capability that solves their #1 pain, not a feature tour
    -   **Competitive Differentiation Moment:** One specific moment in the demo where I should organically highlight what we do that the competition cannot
    -   **ROI / Value Anchor:** A point in the demo to pause and quantify the value of what they just saw, using their own numbers from discovery
    -   **Close & Next Steps (3 min):** A specific closing sequence to drive commitment to a next step

4.  **Objection & Risk Preparation:** The top 3-5 objections or tough questions likely to come up during or after the demo (based on the attendees, competitive landscape, and deal stage), with a prepared response framework for each.

5.  **Technical & Environment Checklist:** A pre-demo technical readiness checklist including:
    -   Demo environment setup and data requirements
    -   Backup plan if a live demo fails (screenshots, recorded walkthrough)
    -   Screen-sharing and AV check reminders
    -   Any custom configuration or sample data to load that mirrors the prospect's world

6.  **Post-Demo Playbook:** A plan for the 24 hours after the demo, including:
    -   A follow-up email template personalized to the demo conversation
    -   Stakeholder-specific follow-ups (e.g., send the security whitepaper to IT, send the ROI model to the CFO)
    -   Internal debrief questions for my team (what landed, what didn't, what's the next blocker)

Format the output with clear headers, bullet points, and checkboxes (using `- [ ]`) so I can use it as a working checklist.
```

## Example

**Input:**
-   Prospect Company: BrightPath Health Systems
-   Industry: Healthcare SaaS
-   Attendees: Dr. Lisa Patel, CMIO — clinical workflow efficiency; Tom Andersen, VP of IT — integration with Epic EHR and SOC 2 compliance; Rachel Kim, CFO — cost reduction and ROI timeline
-   Discovery Insights: Currently using 3 disconnected point solutions for care coordination; nurses spend ~40 min/shift on redundant documentation; goal is a unified platform that reduces documentation burden by 50% and improves care team communication
-   Deal Stage: Stage 3 — Evaluation / $280K ACV
-   Competitive Alternatives: CompetitorX (incumbent, poor UX) and an internal IT build option
-   Key Capabilities: Unified care coordination dashboard, real-time handoff alerts, Epic EHR integration, SOC 2 + HIPAA compliance, configurable clinical workflows
-   Demo Date: March 5, 2026 — 45 minutes via Zoom

**Output:**

## Demo Preparation Checklist — BrightPath Health Systems

---

### 1. Pre-Demo Research & Intel

- [ ] Review BrightPath's latest earnings call or press releases for strategic priorities (look for mentions of "digital transformation," "clinician burnout," or "operational efficiency")
- [ ] Check LinkedIn for all three attendees — note recent posts, shared connections, tenure, and career trajectory
- [ ] Research Dr. Patel's published work or conference talks — referencing a specific insight builds instant credibility with a CMIO
- [ ] Confirm BrightPath's Epic EHR version and deployment model (hosted vs. on-prem) — ask Tom's team pre-demo if needed
- [ ] Review CompetitorX's latest product updates and known weaknesses (especially UX complaints in G2/KLAS reviews)
- [ ] Pull one relevant industry stat (e.g., "Nurses spend up to 35% of shift time on documentation — JAMA 2025") to anchor your opening

---

### 2. Stakeholder-Specific Game Plan

**Dr. Lisa Patel, CMIO**
-   **Likely top question:** "How does this actually reduce documentation time for my nurses without adding another screen to their workflow?"
-   **Key demo moments:** Unified care coordination dashboard (show a nurse's single-pane view); configurable clinical workflows (show how documentation auto-populates from handoff data)
-   **"So what" statement:** "Dr. Patel, instead of your nurses toggling between three systems and re-entering the same patient data, they'll see one unified view that pulls forward context from the last handoff — that's how we get you to that 50% reduction in documentation time."

**Tom Andersen, VP of IT**
-   **Likely top question:** "How deep is the Epic integration, and what does the implementation timeline look like?"
-   **Key demo moments:** Epic EHR integration (show live FHIR API data flow); SOC 2 + HIPAA compliance overview (show audit log and access controls)
-   **"So what" statement:** "Tom, this isn't a screen-scrape or a bolt-on. We have a certified Epic integration using FHIR R4 APIs, and we'll hand you a SOC 2 Type II report and a pre-built security questionnaire before your review even starts."

**Rachel Kim, CFO**
-   **Likely top question:** "What's the payback period, and how does the cost compare to what we're spending on three tools plus the internal build option?"
-   **Key demo moments:** ROI / Value Anchor moment (pause after the dashboard demo to quantify); consolidation narrative (show how one platform replaces three contracts)
-   **"So what" statement:** "Rachel, you're currently paying for three separate platforms plus the IT overhead to maintain them. At $280K ACV, we project a payback period under 9 months based on the documentation time savings and the contract consolidation alone — and that's before you factor in the cost of the internal build you'd be avoiding."

---

### 3. Demo Storyline & Flow (45 min)

**Opening Hook (2 min)**
-   "Dr. Patel, when we spoke last month, you told me your nurses lose about 40 minutes every shift to redundant documentation across three systems. Today, I want to show you exactly how we eliminate that — and how BrightPath could become a reference site for care coordination. We're going to focus on three outcomes: reducing documentation burden, unifying your care team communication, and doing it in a way that Tom's team can deploy and secure with confidence."

**Current State → Pain (3 min)**
-   Reflect back the discovery: "Right now, your care coordinators open System A for patient context, System B for task assignments, and System C to document the handoff. That's three logins, three data entries, and zero real-time visibility for the charge nurse. You told us this is contributing to burnout and missed handoff details."
-   Let Dr. Patel confirm or expand — this builds emotional buy-in before showing product.

**Product Walkthrough (30 min, ordered by impact)**
1.  **Unified Care Coordination Dashboard (10 min)** — Lead with the #1 pain. Show a nurse logging in once and seeing patient context, task list, and handoff notes in a single view. Use sample data that mirrors BrightPath's workflow.
2.  **Real-Time Handoff Alerts (5 min)** — Show a shift-change scenario where the incoming nurse gets an automated alert with critical patient context. Highlight what CompetitorX cannot do: real-time push notifications with escalation logic.
3.  **Configurable Clinical Workflows (5 min)** — Show how Dr. Patel's team can modify documentation templates without IT tickets. This is the "build vs. buy" killer — show the speed of configuration.
4.  **Epic EHR Integration (5 min)** — Show live data flowing from Epic into the dashboard. Address Tom's concern head-on.
5.  **Compliance & Security (5 min)** — Quick walkthrough of audit logs, role-based access, and the SOC 2 / HIPAA documentation. Don't linger — just build confidence.

**Competitive Differentiation Moment**
-   During the handoff alerts demo, say: "I know you've seen other solutions handle care coordination. What's different here is that this isn't a static task list — it's a real-time, context-aware alert system that escalates based on clinical priority. That's something we hear is a gap in the tools you've been evaluating."

**ROI / Value Anchor**
-   After the dashboard walkthrough, pause: "Dr. Patel, you mentioned 40 minutes per nurse per shift. With 200 nurses across your system, that's over 1,300 hours per week of redundant documentation. If we cut that in half — which is what our similar-sized health system clients see — that's 650 hours back to direct patient care every single week. Rachel, at a blended nursing rate, that's roughly $1.7M in annual recovered capacity."

**Close & Next Steps (3 min)**
-   "Based on what you saw today, does this align with what you need to solve the documentation and handoff challenge? ... Great. Here's what I'd recommend as next steps: First, Tom, I'll send over the security questionnaire and our SOC 2 report so your team can start their review this week. Second, Dr. Patel, I'd love to schedule a 30-minute session where two of your charge nurses can get hands-on with the product in a sandbox — nothing sells this better than clinician feedback. And Rachel, I'll send over a detailed ROI model with BrightPath-specific numbers. Can we lock in a follow-up for March 12 to regroup?"

---

### 4. Objection & Risk Preparation

| # | Likely Objection | Prepared Response |
|---|-----------------|-------------------|
| 1 | "We're considering building this in-house with our IT team." | "That's a path some health systems explore. The question I'd ask is: what's the total cost of building, maintaining, and keeping it current with Epic API changes — and how long until your nurses actually see relief? Our customers typically go live in 8 weeks. An internal build is usually 12-18 months before v1, and that's 12-18 months your nurses are still losing 40 minutes a shift." |
| 2 | "CompetitorX is already embedded in our environment." | "That's actually an advantage for you in this evaluation — you know firsthand what it can and can't do. The feedback we consistently hear from health systems migrating from CompetitorX is that the UX creates its own documentation burden. I'd suggest we let your nurses compare side-by-side in a sandbox — their feedback will tell you everything." |
| 3 | "How do we know the Epic integration won't break with updates?" | "Great question, Tom. We maintain a certified Epic integration and we're part of the Epic App Orchard program, which means we're tested against every quarterly release before it ships. We also have a dedicated integration support team that monitors your connection proactively." |
| 4 | "$280K is a big line item. Can you sharpen the pencil?" | "Rachel, I completely understand. Let's make sure the ROI model is airtight first — because if the value case is $1.7M in recovered nursing capacity, the conversation isn't about whether $280K is too much, it's about how fast we can get to that return. If the numbers work, I'm confident we can find a structure that fits your budget cycle." |
| 5 | "We need to see a reference from a health system our size." | "Absolutely — I'll set up a call with [Reference Customer], a 200-bed system that went live 6 months ago. They saw a 45% reduction in documentation time in the first 90 days. I'll have that scheduled before our next meeting." |

---

### 5. Technical & Environment Checklist

**Demo Environment Setup**
- [ ] Load sample data that mirrors BrightPath's setup: multi-unit health system, 200+ nurses, Epic EHR integration active
- [ ] Create 2-3 realistic patient scenarios for the handoff demo (shift change, escalation, routine coordination)
- [ ] Configure clinical workflow templates to resemble BrightPath's documentation requirements (ask Dr. Patel's team for a sample form pre-demo)
- [ ] Verify Epic sandbox integration is live and returning data — test the FHIR API calls the morning of the demo

**Backup Plan**
- [ ] Record a 5-minute backup walkthrough of the dashboard and handoff flow in case of live demo failure
- [ ] Prepare 4-5 high-resolution screenshots of key screens as a static fallback
- [ ] Have the backup video and screenshots loaded in a separate browser tab, ready to switch in under 10 seconds

**AV & Screen Sharing**
- [ ] Test Zoom screen sharing 30 minutes before the demo — confirm resolution, frame rate, and audio
- [ ] Close all non-demo tabs, notifications, and Slack — nothing kills credibility like a ping during a demo
- [ ] Use a clean browser profile with no autofill or bookmarks visible
- [ ] Confirm attendee calendar invites are accepted and include the Zoom link

**Team Coordination**
- [ ] Brief the Solutions Engineer on the demo flow, which features to highlight, and which to skip
- [ ] Assign a "chat monitor" if the demo is virtual — someone to capture questions in real time so the presenter stays in flow
- [ ] Align on who handles each objection if it comes up live (AE owns business objections, SE owns technical)

---

### 6. Post-Demo Playbook (First 24 Hours)

**Follow-Up Email (send within 2 hours)**
- [ ] Send a personalized recap email to all attendees with:
    -   A 3-bullet summary of the key outcomes discussed (not features — outcomes)
    -   Specific next steps with owners and dates (from the close section of the demo)
    -   Attachments tailored by stakeholder (see below)

**Stakeholder-Specific Follow-Ups**
- [ ] **Dr. Patel:** Send a link to the clinician sandbox environment with a 2-minute video showing how to log in and explore
- [ ] **Tom:** Send the SOC 2 Type II report, HIPAA compliance documentation, and the pre-filled security questionnaire
- [ ] **Rachel:** Send the BrightPath-specific ROI model (Excel) with the nursing capacity numbers discussed live

**Internal Debrief (same day)**
- [ ] Huddle with SE and manager to answer:
    -   What landed? Which moment got the strongest reaction?
    -   What didn't land? Where did we see skepticism or disengagement?
    -   Who is the real power in the room? Did that change from our assumption?
    -   What is the next blocker to advance this deal?
    -   Do we need to add or remove anyone from the next meeting?
- [ ] Update CRM with demo notes, next steps, and revised close date if needed

## Tips
- Never start a demo with "Let me show you our platform." Start with their pain. The first two minutes determine whether you have the room's attention or their laptops do.
- Sequence your demo by impact, not by product menu. The #1 mistake average reps make is giving a feature tour. Presidents Club reps tell a story where the product is the resolution to the prospect's specific problem.
- Pause after your biggest "wow" moment and anchor value in their numbers. Silence after a value statement is more powerful than another feature.
- Prepare for the demo to go sideways. If an attendee derails with questions early, welcome it — engagement is better than a polished monologue. Adjust the flow in real time.
- The demo is not the close. The demo is the vehicle to earn the next step. Always leave with a specific, calendar-confirmed action.
- If you can get the prospect's own data or documents into the demo environment, do it. Nothing converts like seeing your own world inside the product.
