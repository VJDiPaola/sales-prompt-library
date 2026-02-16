# Sales Prompt Library

Reusable AI prompts to accelerate sales workflows — discovery, objections, emails, closing, and more.  
Copy → Paste into Claude / ChatGPT → Replace `[variables]` → Use.

---

## ⚡ 30-Second Quickstart

1. Pick a prompt from the [Prompt Catalog](#-prompt-catalog) below.
2. Open the `.md` file and copy the **Prompt** section.
3. Paste it into [Claude](https://claude.ai) or [ChatGPT](https://chat.openai.com).
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
| 🔍 **Discovery** | [Needs Analysis](prompts/discovery/needs-analysis.md) · [Pain Point Deep Dive](prompts/discovery/pain-point-deep-dive.md) · [Stakeholder Mapping](prompts/discovery/stakeholder-mapping.md) | First-call prep, quantifying pain, mapping decision-makers |
| ✅ **Qualification** | [MEDDIC Scorer](prompts/qualification/meddic-score) | Score deal quality using the MEDDIC framework |
| 🛡️ **Objection Handling** | [Price Objections](prompts/objection-handling/price-objections.md) | Handle "too expensive" / "no budget" pushback |
| ⚔️ **Competitive** | [Battle Card](prompts/competitive/battle-card.md) | Win against specific competitors |
| ✉️ **Email Drafting** | [Cold Outreach](prompts/email-drafting/cold-outreach.md) · [Follow-Up Sequence](prompts/email-drafting/follow-up-sequence.md) | First-contact emails, re-engaging silent prospects |
| 🤝 **Closing** | [Executive Summary](prompts/closing/proposal-summary.md) | Turn proposals into CEO-friendly 1-pagers |

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

**Which AI should I use — ChatGPT or Claude?**  
Both work. These prompts are model-agnostic. Use whichever you have access to.

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

- [ ] Demo preparation checklist
- [ ] Renewal risk assessment
- [ ] Pricing justification framework
- [ ] Champion development strategy

---

**License:** Free to use and modify  
**Last Updated:** February 2026
