# What AI Gets Wrong on Resumes

Eight failure modes that appear in the majority of ChatGPT/Claude/Gemini resume rewrites. Each includes a before example, why it fails, and the fix pattern.

These patterns are what the [cvpage.org](https://cvpage.org) Analyze step flags before any rewrite happens.

---

## Failure mode 1 — Symmetric bullet rhythm

**Symptom:** Every bullet has the same structure and similar length.

**Before:**

```
- Led the migration of X to drive Y across stakeholders.
- Led the integration of A to optimize B for key teams.
- Led the rollout of C to enhance D across the organization.
```

**Why it fails:** Humans vary rhythm. LLMs don't unless forced.

**Fix:** Different lead verbs, different lengths (one short ~10 words, one long ~25), different sentence shapes.

---

## Failure mode 2 — Buzzword substitution (not deletion)

**Symptom:** "Leveraged" becomes "harnessed" or "utilized" — still corporate-speak.

**Fix:** Delete the verb; lead with the artifact. See [anti-buzzword list](https://github.com/Sahme115/ai-resume-humanizer-prompts/blob/main/rules/anti-buzzword-list.md).

---

## Failure mode 3 — Invented metrics

**Symptom:** Plausible percentages with no source (often 30%, 40%, 47%, 2x).

**Why it fails:** Hiring managers ask "how did you measure that?" once.

**Fix:** Remove the number or anchor it to a named test/dashboard. If you can't cite the source, delete the metric.

---

## Failure mode 4 — Scope inflation

**Symptom:** "Led" / "Architected" / "Spearheaded" when the candidate contributed.

**Fix:** Match verb to honest contribution level: Implemented, Contributed to, Co-led, Owned (only if true).

---

## Failure mode 5 — Universal summary

**Symptom:** Summary could apply to any role in any industry.

**Before:**

> Passionate professional with a proven track record of delivering exceptional results in dynamic environments.

**Fix:** 2–3 lines naming role, years, stack or domain, and one recent concrete scope.

---

## Failure mode 6 — Phantom artifacts

**Symptom:** Projects or systems named that don't exist in the candidate's real work.

**Fix:** Run a credibility pass with off-resume ground truth. See [Prompt 05 — Credibility pass](https://github.com/Sahme115/ai-resume-humanizer-prompts/blob/main/prompts/05-credibility-pass.md).

---

## Failure mode 7 — Em-dash and parenthetical overload

**Symptom:** Every bullet has an em-dash or a parenthetical aside.

**Fix:** One em-dash per page max. Move asides to a second bullet or delete.

---

## Failure mode 8 — Skills block as adjectives

**Symptom:**

> Proficient in a wide variety of cutting-edge technologies and modern development practices.

**Fix:** List searchable tools: `AWS (Lambda, RDS), Python, Terraform, on-call for data platform`.

---

## Quick self-check (30 seconds)

Count on page 1:

- [ ] Zero Tier-1 buzzwords (passionate, proven track record, dynamic, etc.)
- [ ] No two bullets start with the same word
- [ ] At least one bullet under 14 words
- [ ] Every bullet has one concrete noun a recruiter could ask about
- [ ] No percentage unless you can name where it came from

If any box fails, the resume still reads as AI-assisted.

---

## See also

- [How recruiters read](how-recruiters-read.md)
- [ai-resume-humanizer-prompts](https://github.com/Sahme115/ai-resume-humanizer-prompts)
- Article: [Signs your resume sounds like ChatGPT](https://cvpage.org/blog/signs-your-resume-sounds-like-chatgpt)
