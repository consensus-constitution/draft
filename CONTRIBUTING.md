# Contributing

This project runs on one rule: **attack mechanisms, not motives.** Every provision here is a machine; show where the machine breaks and you have contributed, whatever your politics.

## Issue types and labels

| Label | Use for | Example |
|---|---|---|
| `adversarial` | An exploit: a realistic actor, a realistic move, the constitutional text failing to stop it | "A President can chain fresh 90-day emergency declarations for distinct 'emergencies' arising from one crisis" |
| `interaction-bug` | Two provisions that fight each other | "The §3(c) Senate override clock vs. the §5(a) committee deadline can strand a bill for 16 months" |
| `comparative` | A jurisdiction that tried this and what happened | "Israel's pure proportionality produced X; your 3–7 magnitude bound may not prevent it because…" |
| `drafting` | Ambiguity, vagueness, or a term of art misused | "'Measurable' in Art. V §4(a) has no measurer identified" |
| `consistency` | Cross-references, defined terms, numbering | — |
| `policy` | You think a decision is wrong on the merits | Argue against the logged decision, citing its row number |

**Issue title format:** `[Art. VII §6(a)] Short description of the failure`.
One mechanism per issue. Link the decisions-log row you are attacking.

## Pull requests

- PRs amend the **enrolled** text; mirror the change in the annotated edition, updating or adding the drafter's note.
- Every PR description must state: **the failure repaired**, **the mechanism of the fix**, and **what the fix costs** (every fix costs something; PRs claiming otherwise will be asked to find it).
- Follow the house drafting rules:
  - **Formulas, not numbers**, wherever a value must track reality (the 435 rule).
  - Thresholds vocabulary is fixed: 60% ordinary, 65% extraordinary. New thresholds need extraordinary justification.
  - Rights are drafted with **purpose-or-effect** standards, revenue-scaled penalties, personal liability, and private rights of action, unless the PR argues why not.
  - No provision may depend on an official's good faith where a trigger can replace it.

## How changes are adopted

The maintainer adopts a change by merging the PR **and adding a numbered row to the decisions log** stating the decision and its reasoning. The log is append-only: reversed decisions get a new row, not an edit. This keeps the design auditable end to end.

## Scope

In scope: everything in the ten articles, the transition schedule, and the ratification design.
Out of scope: whether a new constitution should exist at all (take it to Discussions), current-events litigation of any kind, and any claim that this document has legal force. It does not.

## Conduct

Argue hard about text; never about people. Contributions attacking contributors rather than provisions are removed without ceremony.
