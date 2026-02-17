---
name: adding-prompts
description: Creates new sales prompt pages matching the repo's format and style. Use when adding a prompt, creating a new prompt file, or contributing a prompt to the library.
---

# Adding Prompts to the Sales Prompt Library

## Step 1 — Determine the Category

Place the new file under the correct subdirectory in `prompts/`. Existing categories:

| Directory | Category |
|---|---|
| `discovery/` | 🔍 Discovery |
| `qualification/` | ✅ Qualification |
| `objection-handling/` | 🛡️ Objection Handling |
| `competitive/` | ⚔️ Competitive |
| `email-drafting/` | ✉️ Email Drafting |
| `closing/` | 🤝 Closing |
| `social-selling/` | 📈 Social Selling |
| `referral-selling/` | 📣 Referral Selling |

If none of these fit, create a new subdirectory with a lowercase-kebab-case name.

## Step 2 — Name the File

- Use lowercase kebab-case: `my-prompt-name.md`
- Be specific and descriptive (e.g., `gap-selling-analysis.md`, not `gap.md`)

## Step 3 — Write the Prompt File

Every prompt file MUST follow this exact structure. Do not add, remove, or reorder sections.

````markdown
# [Title]

**Use Case:** [One sentence — when to use this prompt]
**Input Required:** [Comma-separated list of [bracketed variables] the user must fill in]

## Prompt

```text
[The full prompt text the user will copy into their AI tool.
All user-specific values use [bracketed variables].
This MUST be inside a ```text code fence so GitHub renders a copy button.]
```

## Example

**Input:**
- [Variable 1]: [sample value]
- [Variable 2]: [sample value]

**Output:**

[Realistic sample output showing what the AI would generate with the sample input above.]

## Tips
- [Practical tip 1 for getting better results]
- [Practical tip 2]
- [Practical tip 3 (optional)]
````

### Formatting Rules

1. **Title** (`# ...`): Descriptive, title-cased. May include the methodology name (e.g., "SPIN Selling: Implication Questions").
2. **Use Case**: One sentence. Describes the sales situation, not the prompt mechanics.
3. **Input Required**: Lists every `[bracketed variable]` that appears in the prompt text.
4. **Prompt section**: The prompt text MUST be wrapped in a ` ```text ` code fence so GitHub shows a click-to-copy button. Use `[bracketed variables]` for user-specific values. Write in the voice of the salesperson talking to the AI. Use numbered lists and bold labels for structure.
5. **Example section**: Show realistic **Input** values and a complete **Output**. Bold the labels. Use the prospect's language (quotes, dollar amounts, time frames).
6. **Tips section**: 2–3 bullet points. Actionable, specific. No filler.

## Step 4 — Update the README Catalog

Add the new prompt to the `## 📂 Prompt Catalog` table in `README.md`.

Find the row for the matching category and append a link using this format:

```
· [Display Name](prompts/category/file-name.md)
```

Append it before the closing `|` of the **Prompts** column. If adding a new category row, follow the existing table pattern with emoji + bold category name, prompt links separated by ` · `, and a short "What It Solves" summary.

Also update the directory tree in the **Usage** section if a new category was created.

## Step 5 — Update the Roadmap (if applicable)

If the new prompt corresponds to a roadmap item in `README.md` under `## 📋 Roadmap`, change its checkbox from `- [ ]` to `- [x]`.

## Checklist

Before finishing, verify:

- [ ] File is in the correct `prompts/<category>/` directory
- [ ] File name is lowercase kebab-case with `.md` extension
- [ ] All five sections present in order: title, Use Case/Input Required, Prompt, Example, Tips
- [ ] Prompt text is inside a ` ```text ` code fence (click-to-copy on GitHub)
- [ ] All `[bracketed variables]` in the prompt are listed in **Input Required**
- [ ] Example shows realistic sample input AND output
- [ ] README catalog table is updated with a link to the new file
- [ ] Roadmap checkbox updated if applicable
