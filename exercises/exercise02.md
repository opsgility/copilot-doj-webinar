
### Prompt 2.1 — Timeline Construction from a Document

1. Upload `DOJ-After-Action-Report.md` from the assets folder using the + icon in Copilot Chat.
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
Add another paragraph that addresses case deconfliction procedures
and the designated point of contact for the joint task force.
Maintain the same formal tone.
```

> **Tip:** Iterative follow-up prompts that add sections or refine tone are often faster than rewriting the entire prompt from scratch.

---
