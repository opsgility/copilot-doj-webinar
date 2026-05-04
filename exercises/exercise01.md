
# Exercise: Hands-On Prompt Playground
**Standalone Practice Exercise | Estimated Time: 45–60 minutes**

---

## Overview

This exercise gives you guided, open-ended practice writing and refining prompts for three categories of DOJ work: **legal tasks**, **investigative tasks**, and **administrative tasks**. Unlike earlier exercises, there is no single right answer — the goal is to experiment, iterate, and develop your own prompt instincts.

Each section provides a scenario, a starter prompt, and guidance on how to refine it. At the end, a free-play section invites you to bring your own work context.

**Five elements of a strong prompt — keep these in mind throughout:**

| Element | Question it answers |
|---------|---------------------|
| **Role** | Who are you, and for whom are you writing? |
| **Goal** | What do you want Copilot to produce? |
| **Context** | What background or constraints apply? |
| **Source** | Where should Copilot draw information from? |
| **Expectations** | What format, length, and tone do you need? |

> **Reminder:** All prompts in this exercise use unclassified, fictitious scenarios. Do not enter case names, defendant information, grand jury material, PII, attorney work product, or any Privacy Act-protected data into Copilot Chat.

---

## Part 1 — Legal Tasks

### Scenario

You are a trial attorney in a U.S. Attorney's Office supporting a senior AUSA preparing for an upcoming prosecution involving wire fraud and money laundering charges. You need research summaries and drafting support.

---

### Prompt 1.1 — Statute Summary (Start simple, then strengthen)

**Starter prompt — try this first:**
```
Explain the federal wire fraud statute.
```

**Now strengthen it using all five elements:**
```
I am a federal prosecutor in a U.S. Attorney's Office preparing
background materials for a wire fraud and money laundering
prosecution. Summarize the key elements of 18 U.S.C. § 1343
(wire fraud), including what the government must prove at trial.
Format as a numbered list of elements with a one-sentence
explanation of each. Conclude with a brief note on how wire fraud
charges are commonly paired with 18 U.S.C. § 1956 money laundering
charges. Use plain legal language suitable for a junior attorney
reference sheet.
```

**Iteration prompt — refine the output:**
```
Add a section on the statute of limitations for wire fraud and
note any exceptions that apply when the offense targets a
financial institution. Keep the same format.
```

> **Reflect:** Which prompt produced more usable output? What specific elements drove the improvement?

---

### Prompt 1.2 — Legal Research Summary

```
I am a paralegal in the DOJ Civil Division preparing a research
memo for an Assistant U.S. Attorney. Summarize how federal courts
have interpreted the "scheme to defraud" element in wire fraud cases
involving internet-based financial fraud. Cover the circuit split
(if any) on key interpretive questions. Present as 3–4 paragraphs
in formal legal research style. Cite your sources and flag any claims
that cannot be verified against published judicial opinions.
```

**After receiving the response:**
- Did Copilot cite specific cases? Note any case names and verify at least one independently (e.g., via Google Scholar or Westlaw if available).
- Did Copilot flag uncertainty, or did it present every claim with equal confidence?
- If it cited a circuit split, does the description match what you know or can verify?

> **Hallucination alert:** Case citations are a high-risk hallucination category. Before using any case name from this response in a work product, verify it independently.

---

### Prompt 1.3 — Talking Points for Senior Leadership

```
I am a senior litigation counsel in the DOJ National Security Division
preparing a two-minute oral briefing for the Assistant Attorney General.
The topic is the legal framework for prosecuting material support to
foreign terrorist organizations under 18 U.S.C. § 2339B. Produce
talking points that cover: (1) what the statute requires, (2) what
the government must prove, and (3) key court decisions that have
shaped prosecutorial strategy. Present as 5 concise bullet points
in formal policy-brief language. Each bullet should be one to two
sentences. Flag any specific case names as requiring independent
verification before use.
```

**Iteration challenge:** Ask Copilot to reformat the talking points as a two-column table with "Key Point" and "Supporting Detail" headers. Compare readability.

---
