
## Part 3 — Administrative Tasks

### Scenario

You are a senior program analyst in a DOJ component's Office of Administration, supporting the Component Head. Your work includes budget analysis, executive correspondence, and staff communications.

---

### Prompt 3.1 — Budget Analysis Summary

1. Upload `DOJ-Budget-Data.csv` from the assets folder using the + icon in Copilot Chat.
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

<!-- **If the CSV is not available, use this standalone version:**
```
I am a senior program analyst preparing a budget planning memo.
Describe the five most common budget execution risks for federal
program offices in the second half of a fiscal year, and recommend
one mitigation action for each risk. Format as a structured list
with a risk header and a one-sentence mitigation. Use formal
government language.
``` -->

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
