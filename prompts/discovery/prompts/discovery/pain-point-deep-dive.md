# Pain Point Deep Dive

**Use Case:** After initial call when prospect mentions a problem
**Input Required:** [company name], [pain point mentioned], [contact's role]

## Prompt

I'm preparing for a discovery call with [company name]. They mentioned [pain point].

Generate:
1. 5 probing questions that quantify business impact (time wasted, money lost, risks)
2. 3 follow-up questions if they say "it's not that big of a deal"
3. What's probably causing this problem (root causes)
4. How this problem likely affects other departments

Format as: Main question → Possible answers → Follow-up question for each answer

## Example

**Main Q:** "How many hours per week does your team spend on [pain point]?"  
→ If they say "5-10 hours": "What's that costing you in salary? What could they do with that time instead?"  
→ If they say "Not sure": "Who on your team would know? Can we ask them?"

## Tips
- Always ask for numbers (hours, dollars, percentage)
- If they can't quantify it, the pain might not be real enough to buy
