# The Consensus Constitution
### A complete working draft of a second United States Constitution — open for adversarial review

This repository contains a ground-up redraft of the U.S. Constitution: ten articles, ninety-six logged design decisions, and a complete audit trail. It is a serious design exercise, not a manifesto. The request to reviewers is simple: **break it.**

## What this is

A full replacement text built around four commitments:

1. **Consensus as arithmetic, not aspiration.** Legislation passes at 60%. The House is proportional (multi-member districts, single transferable vote, ~1,415 members at 1:240,000), so 60% of the chamber approximates 60% of the country.
2. **An affirmative, enforceable franchise.** The right to vote stated directly, with polling-place density formulas, closure pre-clearance, a two-day election weekend, and worker protections — operational details frozen in constitutional text because they are what bad actors erode first.
3. **Brakes everywhere, veto nowhere.** The Senate becomes a revising chamber (12-month delay, 65% House override). The President holds a suspensive veto (60-day pause, same-threshold override). Every institution can force reconsideration; only a durable supermajority can enact.
4. **Self-executing correction.** Recounts, polling capacity, weapon-harm reclassification, and social-guarantee shortfalls all trigger automatically on published data — the constitution keeps working when the legislature deadlocks by design.

Other major departures: no Electoral College (ranked-choice direct election); 18-year staggered Supreme Court terms with two appointments per presidential term; an information article that abolishes the third-party doctrine and bulk collection; a harm-based weapons framework replacing the Second Amendment; the first social guarantees (health, education, housing, work) in an American constitutional text; federal powers rebuilt on the Convention's own Resolution VI instead of commerce-clause fictions; and a ratification path modeled on the 1787 precedent itself.

## The two editions

| File | What it is |
|---|---|
| [`constitution_enrolled.md`](constitution_enrolled.md) / [`.html`](constitution_enrolled.html) | The clean text. Just the constitution. |
| [`constitution_draft.md`](constitution_draft.md) / [`.html`](constitution_draft.html) | The annotated edition: every provision carries a drafter's note explaining the reasoning, plus the full 96-row decisions log. |

**Reviewers should start with the annotated edition.** The notes are the argument; the decisions log is the commit history of the design. The HTML editions are fully cross-linked — every internal citation jumps to its target.

## Provenance, stated plainly

This draft was produced by a human author in structured collaboration with an AI assistant (Anthropic's Claude). Every design decision was made by the human author and is individually logged in the appendix; the AI drafted language, surfaced tradeoffs, historical precedents, and counterarguments, and performed the consistency audit. We state this up front because reviewers deserve to know how the sausage was made, and because the method — decision-by-decision deliberation with logged reasoning — is part of what is being tested here.

No affiliation with any government, party, or organization. This is not a legal instrument and binds no one.

## How to review

- **Open an Issue per provision.** Title format: `[Art. I §4(c)] Emergency re-enactment under successive declarations`. One mechanism per issue.
- **The most valuable feedback is adversarial.** Assume a bad-faith President, a captured state, a hostile 41%, a motivated billionaire. Show the exploit. Historical and comparative counterexamples ("Weimar tried this; here's what happened") are gold.
- **Propose amendments as Pull Requests** that change the enrolled text, with the failure they repair stated in the PR description. Keep both editions in sync.
- **Cross-cutting design arguments** (bicameralism, positive rights, the 60% threshold itself) go in Discussions, not Issues.

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for labels, templates, and how decisions get adopted.

## Known residual risks (we found these; help us find more)

The audit accepted three unresolved vulnerabilities, documented rather than hidden:

1. A coerced plea to exactly time-served lawfully zeroes the over-detention compensation of Art. VI §7(f); the 30/60-day trial clocks cap the exposure but do not close the channel.
2. A captured Weapon Harm Authority could stall the automatic triggers of Art. VII §6 by slow-walking data; mandamus on the expedited docket is the only backstop.
3. Nothing compels a President to nominate commissioners to the independent authorities at all.

## Status and roadmap

**Revision:** audited working draft (cross-reference sweep complete; 34 audit fixes applied).
**Phase 1 (now):** expert adversarial review via Issues.
**Phase 2:** public deliberation on the highest-contention provisions via Pol.is; findings folded into Revision 2.
**Phase 3:** a stable Revision 2 with a public change log.

## License

Released under **CC0 1.0 (public domain dedication)**. A constitution proposed to the public belongs to the public. Fork it, gut it, improve it.
