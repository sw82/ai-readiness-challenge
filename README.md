# AI Readiness Challenge

> **CAL AI Challenge — Session 2**

---

## The Problem

Many organizations have no idea where to start with AI.

They don't know what they're good at, where the gaps are, or what to tackle first. Traditional consulting firms charge €50,000–€200,000 for this kind of strategic assessment. The result is usually a PowerPoint deck that collects dust.

**CAL wants to change that. We built a free, automated AI readiness assessment — and it works.**

The tool is live at **[gutinvestiert.de](https://gutinvestiert.de)** — go take the quick check. It takes 2 minutes.

---

## Your Challenge

> **Make an LLM behave the way this tool does.**

The tool you just used is backed by a framework — a set of dimensions, weights, scoring logic, and recommendations derived from research. That framework lives in this repo.

Your job: get an LLM to replicate the consultancy intelligence behind it.

You define what "replicate" means. Some directions to explore:

- Can you make an LLM *conduct* the assessment conversationally?
- Can you make it *interpret* a set of answers and produce a tier + recommendations?
- Can you make it *reason* about an organization's AI readiness based on a free-text description alone?
- Can you get it to produce output that is *indistinguishable* from what an expert consultant would write?

There is no single right answer. There is no skeleton code to fill in. This is open-ended by design.

---

## What's in This Repo

```
research/
├── framework.md       ← The assessment dimensions and scoring logic
├── tiers.md           ← The five maturity levels (Einsteiger → Vorreiter)
├── recommendations.md ← What good recommendations look like
└── references.md      ← Scientific sources behind the framework
```

Start there. Understand the framework. Then figure out how to encode it.

---

## Hints (read only if stuck)

<details>
<summary>Hint 1 — Where to start</summary>

An LLM doesn't know your framework by default. You have to tell it. The question is: how?

</details>

<details>
<summary>Hint 2 — What "getting the knowledge in" means</summary>

There are at least three fundamentally different approaches to making an LLM behave like a domain expert:
1. Tell it everything in the prompt
2. Give it structured data and let it reason
3. Show it examples and let it generalize

Which one works best here? Why?

</details>

<details>
<summary>Hint 3 — Evaluation</summary>

How do you know if your LLM is actually good at this? Design a way to evaluate it. What would a ground truth look like?

</details>

---

## Deliverable

At the end of the session, show us:

1. What you built (a prompt, a chain, an app — anything)
2. One example input → output that demonstrates it works
3. One thing that surprised you or didn't work

**Time:** 90 minutes.

---

*Built with ❤️ by CAL. Framework based on 15+ scientific sources — see `research/references.md`.*
