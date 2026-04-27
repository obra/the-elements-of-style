---
name: writing-clearly-and-concisely
description: Apply Strunk's timeless writing rules to ANY prose humans will read—documentation, commit messages, error messages, explanations, reports, or UI text. Makes your writing clearer, stronger, and more professional.
---

# Writing Clearly and Concisely

## Overview

William Strunk Jr.'s *The Elements of Style* (1918) teaches you to write clearly and cut ruthlessly.

**WARNING:** `elements-of-style.md` consumes ~12,000 tokens. Read it only when writing or editing prose.

## When to Use This Skill

Use this skill whenever you write prose for humans:

- Documentation, README files, technical explanations
- Commit messages, pull request descriptions
- Error messages, UI copy, help text, comments
- Reports, summaries, or any explanation
- Editing to improve clarity

**If you're writing sentences for a human to read, use this skill.**

## Register Awareness — Apply Strunk Lightly Here

Classify the input before editing. Strunk's rules misfire on some registers.

1. **Academic / scholarly** — preserve scholarly verbs (`shows`, `reports`, `demonstrates`, `preserves`), academic plural `we`, epistemic hedges, and domain compound modifiers (`per-contract dispatch identity`, `cold-cache compile time`).
2. **Technical / code-adjacent** — preserve technical terms verbatim. Domain hyphenated compounds are not "needless words".
3. **Direct quotes, citations, bibliography** — leave verbatim; edit framing only.
4. **Code, paths, commands, signatures** — never edit.
5. **Default (blog, README, marketing, commit body)** — apply all rules.

When in doubt, default to register 5 and note the assumption.

In registers 1–2, lean on rule 10 (active voice), 13 (cut filler like "in order to"), 16, 18. Apply rule 11 (positive form), 12 (concrete), and the maximalist reading of 13 with caution: hedges, citations, named entities, and numbers are load-bearing, not needless.

## Process

1. **Classify the register** (1–5 above).
2. **Identify load-bearing content**: hedges, citations, named entities, numbers, technical compounds, scholarly verbs. These survive every cut.
3. **Apply Strunk's rules.** Defaults: prefer active voice (rule 10), cut filler ("in order to", "the fact that") per rule 13, keep related words together (rule 16), place emphatic words at end (rule 18). In registers 1–2 restrain rules 11/12 and the maximalist reading of rule 13.
4. **Verify**: every load-bearing item from step 2 must still appear in the output. If a hedge, citation, named entity, or number was lost, restore it.
5. **Return only the revised text.** No commentary, no diff, no register classification line, unless the user asked.

When context is tight, dispatch a subagent with `elements-of-style.md` for the full ruleset.

## All Rules

The full 18 rules + the alphabetical "Words and Expressions Commonly Misused" section live in `elements-of-style.md`. The high-leverage rules referenced above:
10 active voice · 11 positive form · 12 concrete language · 13 omit needless words · 16 related words together · 18 emphatic words at end.

## Common cuts

- "In order to" → "To" (or drop)
- "It is important to note that" → drop
- "The fact that X" → "X"
- "is being Xed" → "X-es" (active voice)
