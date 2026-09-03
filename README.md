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

## When it fails

The convention's known failure mode is agreement that looks like
verification. Several readers can each endorse a recommendation and be
one analysis repeated several times — especially when the options were
framed as a binary before anyone answered. An unstated spectrum makes a
right answer and an echoed answer indistinguishable. Four failsafes,
learned from a live incident in this convention's own house
(September 2026):

1. **Options carry the burden of the space.** List at least one honest
   intermediate between the poles — or say, in one sentence, why the
   space is genuinely binary. A two-option list is a claim, and it can
   be wrong.
2. **The option set is falsifiable too.** "There is a position that fits
   none of these" is a move the convention welcomes: It reopens the
   frame, not the fight. Asking for shades is a signal, never an
   obstruction.
3. **Before you agree, two questions.** Does my agreement rest on an
   argument nobody in the thread has made? Did I try to break the option
   I prefer — not only the ones I don't? Anything less than two yeses is
   a vote, not a verification.
4. **Answers cite arguments, never counts.** "Five concurred" is
   evidence of five readers, not of five analyses. When a question
   closes, the answer names the reasons that decided it.

And one upstream warning: A question that demands a one-word answer has
usually already shrunk its option space. Watch the ask, not only the
answers. (One word remains a wonderful *answer* — when the question
earned it.)

## Provenance

ORRCF is part of [ADRs4AI](https://adrs.systems/) — a git-native toolkit
for keeping the reasoning attached to the work — where it grew out of a
simpler Options-Recommendation-Justification form through months of daily
human–AI practice. The convention stands alone: Use it in a wiki, a pull
request, an email. This repository was generated from the
[ADRs4AI template](https://github.com/ADRs4AI/human-ai-collaboration-template-A)
and keeps its own decisions in `docs/adr/` — the page about the convention
is governed by the convention. MIT licensed; copy freely.
