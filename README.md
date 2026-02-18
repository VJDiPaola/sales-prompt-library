# Sales Prompt Library

Reusable AI prompts to accelerate sales workflows — discovery, objections, emails, closing, and more.  
Copy → Paste into Claude / ChatGPT / Gemini → Replace `[variables]` → Use.

---

## ⚡ 30-Second Quickstart

1. Pick a prompt from the [Prompt Catalog](#-prompt-catalog) below.
2. Open the `.md` file and copy the **Prompt** section.
3. Paste it into [Claude](https://claude.ai), [ChatGPT](https://chat.openai.com), or [Gemini](https://gemini.google.com).
4. Replace every `[bracketed variable]` with your deal-specific details.
5. Send — then iterate on the output until it's great.

**Try it now** — copy this into your AI chat:

```text
I'm preparing for a discovery call with [company name] in the [industry] industry.

Generate 5 open-ended questions to uncover:
- Current workflow and pain points
- Goals for the next 6-12 months
- Budget and decision-making process

Format as a conversation guide with follow-up questions.
```

Replace `[company name]` and `[industry]`, hit Enter, and you've got a call prep sheet in seconds.

---

## 📂 Prompt Catalog

| Category | Prompts | What It Solves |
|---|---|---|
| 🔍 **Discovery** | [Needs Analysis](prompts/discovery/needs-analysis.md) · [Pain Point Deep Dive](prompts/discovery/pain-point-deep-dive.md) · [Stakeholder Mapping](prompts/discovery/stakeholder-mapping.md) · [Gap Selling Analysis](prompts/discovery/gap-selling-analysis.md) · [SPIN Implication Questions](prompts/discovery/spin-implication-questions.md) · [Sandler Up-Front Contract](prompts/discovery/sandler-up-front-contract.md) · [Conceptual Selling](prompts/discovery/conceptual-selling-uncover-concept.md) | First-call prep, quantifying pain, mapping decision-makers, creating urgency |
| ✅ **Qualification** | [MEDDIC Scorer](prompts/qualification/meddic-score.md) · [MEDDIC Qualification Questions](prompts/qualification/meddic-qualification-questions.md) · [SNAP Selling First-Call Triage](prompts/qualification/snap-selling-first-call-triage.md) | Score deal quality, structured qualification, fast triage for busy prospects |
| 🛡️ **Objection Handling** | [Price Objections](prompts/objection-handling/price-objections.md) · [Value-Based Price Objection](prompts/objection-handling/value-based-price-objection.md) | Handle "too expensive" pushback by reframing around value |
| ⚔️ **Competitive** | [Battle Card](prompts/competitive/battle-card.md) · [Challenger Sale Teach Moment](prompts/competitive/challenger-sale-teach-moment.md) | Win against competitors, reframe the prospect's thinking |
| ✉️ **Email Drafting** | [Cold Outreach](prompts/email-drafting/cold-outreach.md) · [Follow-Up Sequence](prompts/email-drafting/follow-up-sequence.md) · [Fanatical Prospecting Voicemail](prompts/email-drafting/fanatical-prospecting-voicemail.md) · [Post-Demo Follow-Up](prompts/email-drafting/post-demo-follow-up.md) · [Re-Engage Ghosted Prospect](prompts/email-drafting/re-engage-ghosted-prospect.md) | First-contact, follow-ups, compelling voicemails, maintaining momentum |
| 🤝 **Closing** | [Executive Summary](prompts/closing/proposal-summary.md) · [Value-Based ROI Calculation](prompts/closing/value-based-roi-calculation.md) · [TAS Multi-Thread Engagement](prompts/closing/tas-multi-thread-engagement.md) · [Champion Development Plan](prompts/closing/champion-development-plan.md) · [Renewal Risk Assessment](prompts/closing/renewal-risk-assessment.md) · [Mutual Action Plan](prompts/closing/mutual-action-plan.md) · [Demo Preparation Checklist](prompts/closing/demo-preparation-checklist.md) · [Pricing Justification](prompts/closing/pricing-justification-framework.md) · [Post-Sale Handoff to CS](prompts/closing/post-sale-handoff-to-cs.md) | CEO-friendly summaries, ROI justification, de-risking deals, proactive renewals |
| 📈 **Social Selling** | [SMYKM LinkedIn Profile Review](prompts/social-selling/smykm-linkedin-profile-review.md) · [SMYKM Inbound Lead Personalization](prompts/social-selling/smykm-inbound-lead-personalization.md) · [SMYKM Competitor Mention](prompts/social-selling/smykm-competitor-mention.md) | Personalize outreach, engage on social platforms, build your brand |
| 📣 **Referral Selling** | [Referral Request Email](prompts/referral-selling/referral-request-email.md) · [Referral Thank You Note](prompts/referral-selling/referral-thank-you-note.md) | Proactively generate and manage warm referrals |

---

## 🧑‍💻 Usage

### Step 1 — Choose Your Prompt

Browse the catalog above or look directly in the [`prompts/`](prompts/) directory:

```
prompts/
├── closing/
├── competitive/
├── discovery/
├── email-drafting/
├── objection-handling/
└── qualification/
```

### Step 2 — Copy & Customize

Every prompt file contains a **Prompt** section with `[bracketed variables]`. Copy the prompt text, then fill in the blanks.

**Example — Cold Outreach email:**

```text
Write a cold email to Sarah Chen, VP Engineering at DataCorp.

Use this structure:
1. Hook (1 sentence): Reference a specific trigger event
2. Problem (1 sentence): Connect that trigger to a common pain point
3. Proof (1 sentence): Share one result a similar company got
4. Ask (1 sentence): Request a specific, short call

Rules:
- Maximum 100 words total
- No buzzwords like "synergy," "game-changer," "solutions"
- Don't mention features—focus on THEIR problem
- Subject line: DataCorp + hiring 10 engineers, no hype words
```

### Step 3 — Iterate

The first output is usually 70% there. Follow up with:

```text
Make it shorter — under 80 words.
```
```text
Make the subject line more specific to their Q3 goals.
```
```text
Give me 3 variations of the hook.
```

### Step 4 — Save What Works

When you get a great result, save the exact prompt you used back to this repo (see [Contributing](#-contributing)).

---

## 📝 Prompt Format

Every prompt in this library follows the same structure:

| Section | Purpose |
|---|---|
| **Use Case** | When to use this prompt |
| **Input Required** | The `[variables]` you need to fill in |
| **Prompt** | The text you copy into the AI |
| **Example** | Sample input/output so you know what to expect |
| **Tips** | How to get better results |

---

## 🤝 Contributing

Found a prompt that works great? Add it:

1. Click **Add file → Create new file** on GitHub.
2. Name it `prompts/[category]/[prompt-name].md` (use an existing category or create a new one).
3. Follow the format above: Use Case, Input Required, Prompt, Example, Tips.
4. Commit with a descriptive message (e.g., "Add renewal risk assessment prompt").

**Pro tip:** Combine prompts in sequence for a full deal workflow:  
Discovery → Qualification → Objection Handling → Email → Closing.

---

## ❓ FAQ & Troubleshooting

**Which AI should I use — ChatGPT, Claude, or Gemini?**  
All three work. These prompts are model-agnostic. Use whichever you have access to.

**The output is too generic / not useful.**  
Add more context. Replace `[company name]` with real details, paste in notes from your last call, or add lines like: *"They're a 200-person fintech company. The VP of Engineering mentioned deployment speed is their top priority."*

**Can I chain multiple prompts together?**  
Yes. Run a Discovery prompt first, then paste the output into a Qualification or Objection Handling prompt as context. The more context you carry forward, the better.

**How do I customize a prompt for my industry?**  
Add a line to the prompt: *"My product is [X], selling to [industry]. Adjust the language and examples for this audience."*

**A link isn't working.**  
Some prompt files may not have been added yet, or the filename may differ. Check the [`prompts/`](prompts/) directory directly, or contribute the missing prompt yourself!

---

## 📋 Roadmap

Prompts planned for future addition (contributions welcome):

- [x] Demo preparation checklist
- [x] Renewal risk assessment
- [x] Pricing justification framework
- [x] Champion development strategy
- [x] Mutual Action Plan (MAP) template
- [x] Post-sale handoff to Customer Success

---

**License:** Free to use and modify  
**Last Updated:** February 2026
