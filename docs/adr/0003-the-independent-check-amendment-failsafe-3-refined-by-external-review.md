# ADR-0003: The independent-check amendment — failsafe 3 refined by external review

- **Date**: 2026-09-05 | **Iteration**: 1 | **Status**: Accepted | **Deciders**: Jérémie Lumbroso (relayed and triaged the review; override standing); Pharos 5 (the page's tender — wording and shipping)

**TL;DR**: An external reviewer caught a real exclusion bug in failsafe 3 — its "argument nobody has made" test disqualified legitimate verification-by-independent-check — and the refined wording ships to the page and README; the convention's failure doctrine receiving an outside amendment is the doctrine working on itself.

## Context

During an archival paper's review window (2026-09-05), an external
committee-grade review (GPT 6 Astra Pro, relayed by the founder) caught
that failsafe 3's first question — *"does my agreement rest on an
argument nobody in the thread has made?"* — excludes verification that
adds no novel argument: **replication and independent derivation ARE
verification.** An independently performed check reaches the thread's
conclusion from a different position, which is precisely what the
cascade failsafes exist to secure (the underlying principle is already
in the convention's own house: routing buys *a change of position, not
superior knowledge*).

The house had demonstrated the bug's counterexample the same hour it
arrived, unknowingly: A bibliography entry verified by two seats through
two independent sources — same conclusion, zero new arguments — was
correctly celebrated as the *good* kind of agreement. Failsafe 3 as
written would have scored both checks as "a vote."

## Decision

Failsafe 3's first question is refined, on the page and README, to
Astra's form rendered in the convention's plain speech:

> **Before you agree, two questions.** Does my agreement add something
> the thread does not already hold — new evidence, an independent
> derivation, or a check I performed myself — rather than repeating what
> is written? Did I try to break the option I prefer — not only the ones
> I don't? Anything less than two yeses is a vote, not a verification.

The archival paper quoting the convention renders the same refined form
(with an in-text note), so print and page stay coherent — the reason
this ships now rather than after the submission window.

**Attribution, stacked never overwritten**: Failsafe 3's original
self-test is Flint 5's (ADR-0002); the refinement is GPT 6 Astra Pro's
(external review, via the founder, 2026-09-05). The failure doctrine's
first amendment came from outside the house, through the founder's
gate — which is exactly the audience the "When it fails" section was
published for.

## Consequences

- Page + README updated in lockstep with this ADR (same commit); deploy
  verified against the live URL before the lane reports done.
- Falsifier for the refinement itself: If the "check I performed myself"
  clause starts admitting *asserted* checks that were never shown —
  agreement stacking on unreceipted claims of verification — the wording
  tightens to "a check I performed and can show," and this ADR gains the
  iteration.

— Recorded by Pharos 5 (Claude Fable 5), 2026-09-05
