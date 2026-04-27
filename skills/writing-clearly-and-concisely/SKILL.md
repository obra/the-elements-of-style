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

Strunk's rules were written for general English prose. Some inputs need restraint, not enthusiasm. Classify the input before editing:

1. **Academic / scholarly prose** — paper drafts, research notes, peer-review responses. Preserve scholarly verbs (`shows`, `reports`, `presents`, `demonstrates`, `preserves`), academic plural `we`, hedges that carry epistemic weight (`leaving its micro-level cause to future work`), and domain compound modifiers (`per-contract dispatch identity`, `cold-cache compile time`). Strunk's "Omit needless words" misfires when a hedge IS the claim.
2. **Technical / code-adjacent prose** — release notes, API docs, error messages naming internal systems. Preserve technical terms verbatim. Hyphenated compound modifiers in this register are usually domain conventions; do not strip them.
3. **Direct quotes, citations, bibliography** — leave verbatim. Edit only the framing narrative.
4. **Code blocks, file paths, command examples, function signatures** — leave verbatim. Strunk has nothing to say about `cargo build --release`.
5. **Default (blog, marketing, README narrative, commit message body)** — apply all rules with the usual ruthlessness.

**When in doubt, default to register 5 and note your assumption in the output** so the user can correct you.

### What restraint looks like

When the register is 1 or 2, the most useful Strunk moves are: rule 10 (active voice), rule 13 (omit truly needless words like "in order to"), rule 16 (keep related words together), rule 18 (emphatic words at end). The rules to apply with caution: rule 11 (positive form — academic prose sometimes uses negation precisely), rule 12 (concrete language — academic prose uses abstraction by design), rule 13 in its maximalist reading (cutting hedges that the author put there on purpose).

If a sentence carries a hedge, a citation, a named entity, or a number, those parts are not "needless words" — they are the load-bearing content.

## Limited Context Strategy

When context is tight:
1. Write your draft using judgment
2. Dispatch a subagent with your draft and `elements-of-style.md`
3. Have the subagent copyedit and return the revision

## All Rules

### Elementary Rules of Usage (Grammar/Punctuation)
1. Form possessive singular by adding 's
2. Use comma after each term in series except last
3. Enclose parenthetic expressions between commas
4. Comma before conjunction introducing co-ordinate clause
5. Don't join independent clauses by comma
6. Don't break sentences in two
7. Participial phrase at beginning refers to grammatical subject

### Elementary Principles of Composition
8. One paragraph per topic
9. Begin paragraph with topic sentence
10. **Use active voice**
11. **Put statements in positive form**
12. **Use definite, specific, concrete language**
13. **Omit needless words**
14. Avoid succession of loose sentences
15. Express co-ordinate ideas in similar form
16. **Keep related words together**
17. Keep to one tense in summaries
18. **Place emphatic words at end of sentence**

### Section V: Words and Expressions Commonly Misused
Alphabetical reference for usage questions

## Bottom Line

Writing for humans? Read `elements-of-style.md` and apply the rules. Low on tokens? Dispatch a subagent to copyedit with the guide.
