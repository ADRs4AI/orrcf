# ORRCF

**O**ptions · **R**ecommendation · **R**ationale · **C**onfidence ·
**F**alsifier — always said in full, five words.

The page: **[adrs.systems/orrcf](https://adrs.systems/orrcf/)**

When someone hands you a decision — and especially when an AI hands you
one — the question should carry everything needed to answer it. ORRCF is a
convention for that: **Every decision question ships with five
components.** You can adopt it this afternoon, in any Markdown file, with
no tooling and no buy-in to anything else.

- **Options** — the real option space, laid out. Diversity that resists
  anchoring: If only one path is shown, the question is a formality, not a
  decision.
- **Recommendation** — an attributed lean. The asker shows their hand and
  signs it, so the answerer reacts to a position instead of reconstructing
  one.
- **Rationale** — not a justification after the fact: The explicit,
  inspectable argument connecting the options to the lean, staked in the
  record where it can be audited, challenged, and built on.
- **Confidence** — stated at the end, *with its reasons*. A number without
  reasons is performative confidence, and performative confidence corrodes
  trust in every future question.
- **Falsifier** — the evidence, observation, failed prediction, or changed
  constraint that would cause the recommendation to be revised. Every
  recommendation carries the conditions of its own revision.

A question built this way **streamlines to accept or override** — one word
suffices when the reasoning carries you, and the reasoning is on record
when it doesn't. Delegation becomes delegation-with-a-handle: You can
reclaim any decision you handed off, because the reasoning came with it.

## Steal this

```markdown
### QST: Should we …?
- Status: unanswered
- Why asking: …

**Options**

- **A — …**
- **B — …**
- **C — …**

**Recommendation**: (by NAME, DATE)

**A.** *Rationale*: … *Confidence*: Medium — because …
*Falsifier*: …

**ANS:** (by …)
```

## Provenance

ORRCF is part of [ADRs4AI](https://adrs.systems/) — a git-native toolkit
for keeping the reasoning attached to the work — where it grew out of a
simpler Options-Recommendation-Justification form through months of daily
human–AI practice. The convention stands alone: Use it in a wiki, a pull
request, an email. This repository was generated from the
[ADRs4AI template](https://github.com/ADRs4AI/human-ai-collaboration-template-A)
and keeps its own decisions in `docs/adr/` — the page about the convention
is governed by the convention. MIT licensed; copy freely.
