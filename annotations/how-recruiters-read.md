# How Recruiters Read a Resume (6-Second Scan)

Recruiters do not read resumes top to bottom. They scan. Understanding the scan path is the fastest way to fix a resume that "looks fine" but gets no callbacks.

This document describes the actual reading path used by in-house and agency recruiters screening 50–200 resumes per role.

---

## The 6-second path

In roughly six seconds, a recruiter extracts four things:

| Second | What they read | What they're deciding |
| --- | --- | --- |
| 0–1 | Most recent **job title + company** | "Is this the right level and domain?" |
| 1–2 | **Top bullet** of most recent role | "Did this person actually do something concrete?" |
| 2–3 | Previous **job title + company** | "Is the trajectory coherent?" |
| 3–4 | First 1–2 words of every bullet on page 1 | "Does this person sound like everyone else?" |
| 4–5 | **Skills / tools** block (if present) | "Can they do this on day one?" |
| 5–6 | **Education** (only if early-career) | Tiebreaker, rarely decisive for 3+ years |

Everything else — cover letter, projects section, "interests" — is read only if the first six seconds pass.

---

## What passes the scan

A resume passes when the recruiter can answer **yes** to all three:

1. **Level match** — title and company type fit the role (not under- or over-leveled by two bands).
2. **Concrete top bullet** — the first bullet names an artifact, system, or outcome a follow-up question can target.
3. **No AI smell on page 1** — bullets don't all share the same shape, length, and buzzword density.

---

## What fails the scan (instant skip)

| Signal | Example | Why it's fatal |
| --- | --- | --- |
| Buzzword summary | "Passionate, results-oriented professional leveraging cutting-edge..." | Zero verifiable facts in the highest-visibility line |
| Symmetric bullets | Five bullets all "Verb + noun + outcome clause" | Classic ChatGPT rhythm |
| Vague ownership | "Drove strategic initiatives across the organization" | No artifact; collapses on one question |
| Invented metrics | "Increased efficiency by 47%" with no source | Credibility kill in phone screen |
| Title inflation | "Led migration" when candidate was one of five ICs | Exposed in first technical question |

---

## Annotated scan example (PASS)

```
Senior Backend Engineer · Series B fintech · 2022–present
- Split the checkout monolith into three services; owned API contracts with mobile.
- Carried the pager one week per month; rewrote the incident runbook after Q3 outage.
```

**Recruiter internal monologue (approximate):**

- Title + company → "Fintech backend, right domain."
- Bullet 1 → "Monolith split, named mobile — I can ask about service boundaries."
- Bullet 2 → "On-call + runbook — sounds like real production work."
- **Decision:** read more / shortlist.

---

## Annotated scan example (FAIL)

```
Senior Backend Engineer · Series B fintech · 2022–present
- Spearheaded robust, scalable microservices to optimize synergies across stakeholders.
- Leveraged cutting-edge technologies to drive innovative solutions and deliver value.
```

**Recruiter internal monologue:**

- Title + company → "OK domain."
- Bullet 1 → "Buzzword soup, no artifact."
- Bullet 2 → "Same shape as bullet 1, also buzzwords."
- **Decision:** skip (often before bullet 2 finishes).

---

## The "first two words" test

Recruiters often only read the **first two words** of each bullet during the scan. Optimize those words:

| Weak start | Strong start |
| --- | --- |
| Responsible for | Built / Wrote / Split |
| Helped to | Partnered with [team] on |
| Was involved in | Owned the [artifact] |
| Played a key role | Implemented the [feature] |

If the first two words are weak, the rest of the bullet is often never read.

---

## Mobile and ATS interaction

Many recruiters skim on mobile. Long bullets wrap badly. Aim for:

- **One claim per bullet**
- **12–22 words** for most bullets
- **No semicolons** in more than one bullet per role

ATS parsing is a separate pass (see [recruiter-resume-audit-framework](https://github.com/Sahme115/recruiter-resume-audit-framework)). The human scan happens first.

---

## Practice exercise

Take your resume. Set a 6-second timer. Read only:

1. Latest title + company
2. Top bullet
3. Previous title + company
4. First two words of each bullet on page 1

Can you answer "what does this person actually do?" If not, fix the top bullet before anything else.

---

## See also

- [What AI gets wrong](what-ai-gets-wrong.md)
- [recruiter-resume-audit-framework](https://github.com/Sahme115/recruiter-resume-audit-framework)
- Article: [What recruiters notice in 6 seconds](https://cvpage.org/blog/what-recruiters-notice-in-6-seconds)
