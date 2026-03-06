# What Good Recommendations Look Like

This document describes the pattern and quality bar for AI readiness recommendations.

Understanding this is key to the challenge — the hardest part isn't scoring, it's producing *useful* recommendations.

---

## The Problem with Generic Recommendations

Most AI assessments produce recommendations like:

> "Invest in your data infrastructure."
> "Build a culture of innovation."
> "Develop an AI strategy."

These are useless. Every organization knows this. The value of a good assessment lies in **specificity, prioritization, and actionability**.

---

## What Good Looks Like

Good recommendations have these properties:

### 1. Tier-Aware
The right recommendation for an Einsteiger is different from a Gestalter. An Einsteiger doesn't need a governance framework yet — they need their first use case.

### 2. Dimension-Specific
Address the actual weak points, not generic advice. If D3 (talent) is the weakest dimension, the recommendations should be about talent — not strategy.

### 3. Concrete and Time-Bounded
Bad: *"Improve AI literacy across the organization."*
Good: *"Run a 4-hour AI workshop for all department heads in Q2. Focus on prompt engineering and identifying use cases in their domain."*

### 4. Sequenced
Some actions only make sense after others. A good recommendation engine understands dependencies:
- You can't govern AI well before you have AI to govern
- You can't scale AI before you have data pipelines
- You can't change culture with a memo

### 5. Industry-Aware (if available)
A logistics company's AI use cases are different from a law firm's. Recommendations should reflect this.

---

## Example: Gestalter in Manufacturing

Given:
- Total score: 3.1 (Gestalter)
- Weakest dimensions: D5 (Governance) and D7 (Digital Grundkompetenz)
- Industry: manufacturing
- Role mix: mostly CXO respondents

**Good recommendation output:**

> **Top Priority: Close the governance gap before scaling**
>
> You have live AI use cases and momentum — but no formal process for evaluating risk or ensuring compliance. Before your next deployment, define three things: (1) who approves new AI use cases, (2) what data can and cannot be used for training, (3) what happens when an AI system makes a wrong decision.
>
> One afternoon with your legal team and your AI lead is enough to create a one-page policy. The EU AI Act makes this non-optional by 2026.
>
> **Quick Win: Digital basics for the shop floor**
>
> Your CXO scores are significantly higher than your operational scores, suggesting leadership is ahead of the workforce. 43% of manufacturing automation failures stem from poor digital baseline skills (McKinsey, 2023).
>
> Run a half-day "AI tools on the job" session for team leads. Practical, not theoretical. Let them try Copilot or a custom GPT on a real problem they have today.

---

## The Readiness Gap — The Most Actionable Finding

When the CXO Score and Employee Score diverge by more than 0.8 points, there is a systemic problem.

Leadership thinks the organization is more ready than it is. Employees experience a different reality. This gap predicts implementation failures better than any single dimension score.

The right recommendation here is never "communicate better." It is:
1. Make the gap visible — share the data with both groups
2. Investigate why — structured interviews with middle management
3. Redesign involvement — employees who participate in AI design adopt it faster

---

## Evaluation Criteria for Your LLM

When you test your implementation, ask:

- Does it distinguish between tiers, or give the same advice to everyone?
- Does it address the weakest dimensions specifically?
- Are the actions concrete enough to put in a project plan?
- Does it acknowledge what's already working (not just what's broken)?
- Would a real consultant be embarrassed or proud to have written this?
