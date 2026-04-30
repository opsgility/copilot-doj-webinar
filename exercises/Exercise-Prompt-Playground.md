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

## Part 2 — Investigative Tasks

### Scenario

You are an intelligence analyst supporting an FBI field office working a cross-component investigation involving organized crime, human trafficking, and financial crimes. You need to synthesize information and support investigative planning.

---

### Prompt 2.1 — Timeline Construction from a Document

1. Upload `DOJ-After-Action-Report.md` from the assets folder using the paperclip icon in Copilot Chat.
2. Enter this prompt:

```
Using only the attached after-action report, construct a
chronological timeline of the key operational events described.
Format as a table with columns for Date/Period, Event, and
Significance. Do not add information from outside the document.
If the document does not provide a specific date for an event,
note it as "Date not specified."
```

**Iteration prompt:**
```
Based only on the same document, which operational gap or
coordination failure appears to have had the greatest impact
on mission outcomes? Cite the specific section of the document
that supports your answer.
```

> **Why this matters:** Grounding Copilot in an uploaded document is the most reliable way to prevent hallucinations in investigative summaries. The model answers from your source, not from memory.

---

### Prompt 2.2 — Investigative Strategy Research

```
Act as a federal law enforcement strategy analyst. What are the
most effective investigative techniques used in multi-agency
federal human trafficking prosecutions? Identify the top five
techniques, with a brief description of each and the primary
DOJ components or law enforcement agencies involved. Format
as a numbered list. Use only publicly available, unclassified
sources. Flag any technique where published effectiveness data
is limited.
```

**Iteration challenge:** Follow up with:
```
For technique #[pick one], draft a one-paragraph summary
suitable for an interagency briefing that explains why this
technique is effective and what coordination it requires
between federal and state partners.
```

---

### Prompt 2.3 — Interagency Coordination Memo

```
I am a supervisory special agent in the FBI's Organized Crime
unit drafting an interagency coordination memo to U.S. Attorneys'
Offices in three districts. The purpose is to align investigative
priorities for a joint operation targeting a transnational organized
crime network involved in human trafficking and money laundering.
Draft a two-paragraph coordination memo that: (1) establishes
the operational objective and scope, and (2) outlines the proposed
roles for FBI, HSI, and the USAO in each district. Use formal
law enforcement memo style. Label the document FICTITIOUS TRAINING
SCENARIO.
```

**Refinement prompt:**
```
Add a third paragraph that addresses case deconfliction procedures
and the designated point of contact for the joint task force.
Maintain the same formal tone.
```

> **Tip:** Iterative follow-up prompts that add sections or refine tone are often faster than rewriting the entire prompt from scratch.

---

## Part 3 — Administrative Tasks

### Scenario

You are a senior program analyst in a DOJ component's Office of Administration, supporting the Component Head. Your work includes budget analysis, executive correspondence, and staff communications.

---

### Prompt 3.1 — Budget Analysis Summary

1. If your facilitator has provided `DOJ-Budget-Data.csv`, upload it to Copilot Chat.
2. Enter this prompt:

```
I am a senior program analyst preparing a budget status briefing
for the Component Head. Using the attached budget data, summarize:
(1) total budget allocation and year-to-date expenditures by
program office, (2) any program offices projected to exceed
their annual allocation before fiscal year-end, and (3) the
two program offices with the largest unspent balances. Format
as an executive summary with three short sections and a table
of key figures. Flag any data that appears incomplete or
inconsistent.
```

**If the CSV is not available, use this standalone version:**
```
I am a senior program analyst preparing a budget planning memo.
Describe the five most common budget execution risks for federal
program offices in the second half of a fiscal year, and recommend
one mitigation action for each risk. Format as a structured list
with a risk header and a one-sentence mitigation. Use formal
government language.
```

---

### Prompt 3.2 — Executive Correspondence

```
I am a senior advisor to the Component Head of the DOJ Executive
Office for Immigration Review (EOIR). Draft a formal response
letter to the Executive Director of a national immigration law
nonprofit acknowledging receipt of their policy recommendations
on immigration court efficiency. The letter should: (1) thank
the organization for their engagement, (2) acknowledge the
specific recommendation areas without committing to any policy
position, and (3) note that EOIR will review the recommendations
through its standard policy process. Tone: formal, professional,
and collegial. Length: three paragraphs. Label the letter
FICTITIOUS TRAINING SCENARIO.
```

**Iteration prompt:**
```
Revise the closing paragraph to include a specific offer
to schedule a follow-up meeting with EOIR leadership within
the next 60 days. Keep the same tone and length.
```

---

### Prompt 3.3 — Staff Communication

```
I am the Chief of Staff to a DOJ Component Head drafting an
all-staff communication about new guidance on the use of
AI tools in the workplace. The guidance requires employees to:
(1) complete AI literacy training by a deadline to be
determined, (2) not enter Privacy Act-protected or
attorney-client privileged information into AI tools, and
(3) verify AI-generated content before including it in any
formal work product. Draft a three-paragraph all-staff email
that communicates these requirements clearly and encourages
a constructive, curious approach to AI adoption. Tone:
direct, professional, and supportive — not alarmist.
```

> **Reflection:** Notice how specifying tone ("direct, professional, and supportive — not alarmist") shapes the output. Try removing that instruction and re-running the prompt to see the difference.

---

## Part 4 — Open Playground

Use this section to practice with your own real work context. Substitute fictitious details for any sensitive information.

### Build-Your-Own Prompt Template

Fill in the brackets and enter the result into Copilot Chat:

```
I am a [your role or a similar fictitious role] at [your component
or a fictitious component]. [Describe the task: draft, summarize,
analyze, research, plan]. The audience is [describe the reader or
end user]. [Add relevant context or constraints]. Format the
response as [describe: bullet list / memo / table / paragraph /
briefing slide content / etc.]. Length: [short / one page / 3–5
bullets / etc.]. Tone: [formal / professional / plain language].
If you are unsure about any specific claim, flag it rather than
estimating.
```

### Suggested Scenarios (pick one or bring your own)

| Category | Scenario |
|----------|---------|
| **Legal** | Summarize the current legal landscape for a statute or enforcement area you work with regularly |
| **Investigative** | Draft an investigative planning outline for a fictitious case type your office handles |
| **Administrative** | Draft a memo or email you write frequently, using fictitious names and details |
| **Research** | Request a structured briefing on a DOJ priority area and apply hallucination-prevention techniques |
| **Iteration practice** | Take any earlier response in this exercise and ask Copilot to reformat, shorten, translate to plain language, or adjust the tone |

---

## Prompt Techniques Reference

| Technique | When to use | Example language |
|-----------|-------------|-----------------|
| **Specify role and audience** | Always | *"I am a [role] preparing [document] for [audience]"* |
| **Require format and length** | Always | *"Format as [table/bullets/memo]. Length: [N paragraphs/words]"* |
| **Constrain sources** | When accuracy is critical | *"Use only information from [source]. If unavailable, say so."* |
| **Require attribution** | Legal and factual claims | *"Cite the source for each claim."* |
| **Allow uncertainty** | Statistical and legal data | *"If unsure, flag it and rate your confidence."* |
| **Ground in uploaded doc** | When you have the source | *"Answer only from the attached document."* |
| **Avoid direct quotes** | AG/DAG statements, legal text | *"Summarize — do not quote directly."* |
| **Iterative refinement** | When output is close but not right | *"Keep the same structure and add / change / remove [X]."* |

---

## Checkpoint

Before finishing, confirm you can:

- [ ] Write a prompt from scratch using all five elements (Role, Goal, Context, Source, Expectations)
- [ ] Iterate on a Copilot response with a targeted follow-up rather than starting over
- [ ] Apply at least two hallucination-prevention techniques in a single prompt
- [ ] Adapt a generic prompt for a specific DOJ legal, investigative, or administrative task
- [ ] Recognize when Copilot output requires independent verification before use

---

*Course: MS-4023 — Transform Ideas into Action with Copilot Chat (DOJ Edition)*  
*Classification: UNCLASSIFIED // FOR OFFICIAL USE ONLY*  
*All scenarios and data used in this exercise are fictitious and for training purposes only.*
