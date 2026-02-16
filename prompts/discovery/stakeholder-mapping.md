# Stakeholder Mapping (Complex Deals)

**Use Case:** Multiple decision-makers involved—map who matters and how to reach them
**Input Required:** [company name], [deal size], [what you know about their org]

## Prompt

I'm selling [product/service] to [company name], deal size $[amount].

Help me map the buying committee:

1. **List likely roles involved:**
   - Who evaluates it technically?
   - Who controls the budget?
   - Who actually uses it day-to-day?
   - Who has to approve for security/legal/compliance?

2. **For each role, tell me:**
   - What they care about (their priorities and fears)
   - Questions they'll ask me
   - What makes them say YES
   - What makes them say NO or stall

3. **Power map:**
   - Who has veto power (can kill the deal)?
   - Who's the coach (internal ally selling for me)?
   - Who's a blocker (doesn't want change)?

4. **Strategy:**
   - Which person should I talk to FIRST and what should I say?
   - Which person do I need to win over to close the deal?

## Example

**Technical Evaluator - Director of Engineering:**  
- Cares about: Will this break our existing stack? How hard to implement?  
- Questions: "What's your API like?" "Do you integrate with AWS Lambda?"  
- Says YES if: Proof it works with Python 3.9 and their CI/CD pipeline  
- Says NO if: Requires 2+ months of dev work to integrate  
- Strategy: Offer sandbox trial BEFORE full demo. Let them test it risk-free.

**Economic Buyer - VP of Finance:**  
- Cares about: ROI, total cost of ownership, contract terms  
- Questions: "What's the payback period?" "What if we need to cancel?"  
- Says YES if: ROI is clear and under 12-month payback  
- Says NO if: Sticker shock with no business case  
- Strategy: Don't talk to them until you've proven value with end users. Bring data.

## Tips
- In enterprises (500+ employees), expect 6-8 stakeholders
- Always find your "coach" first—the person who wants you to win
