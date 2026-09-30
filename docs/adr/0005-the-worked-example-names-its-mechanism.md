# ADR-0005: The worked example names its mechanism — a revision of the specimen

- **Date**: 2026-09-30
- **Status**: Accepted
- **Deciders**: Jérémie Lumbroso (authorization); Compositor 5, Claude Fable 5 (edit, at his instruction)

**TL;DR**: The worked example's record is revised in place: its falsifier
now names the mechanism that separates the options (revocation effective
on the next request, under the stated implementations), because the
original's condition did not connect to its outcome.

## Context

Readers working with this example in a manuscript found two defects,
independently. First, the original falsifier both named a winner ("C's
simplicity wins") and said "revisited" — one condition, two licensed
readings. Second, and deeper: its condition did not discriminate. Short
session gaps do not favor session cookies over refresh tokens when both
carry seven-day windows; and revocability alone does not separate tokens
from cookies either, since token revocation exists (RFC 7009) — the
discriminating property must be stated as a property of the particular
implementations. The original had located the decision's ground in
re-login frequency, which separates nothing as specified.

For the record, the original read: Options — A: refresh tokens, 7-day
expiry · B: long-lived access tokens · C: session cookies, mobile
re-login weekly. Falsifier: If session analytics show median session
gaps under one day, C's simplicity wins and this recommendation should
be revisited.

## Options

- **A — Keep the original, add an erratum note**: Preserves the surface
  verbatim; makes the page teach two lessons at once.
- **B — Revise in place** (chosen): The example is an illustrative
  record, not a case history; the page teaches the form cleanly; this
  repository's history preserves the original, and this record quotes it.
- **C — Append a revision block on the page**: Shows the correction
  discipline on the surface; overloads the one example the page has.

**Recommendation**: (by Compositor 5, Claude Fable 5, 2026-09-30)

**B.** *Rationale*: The page's register rules keep this surface a wedge a
stranger can take whole; an example must exemplify the form, and the
correction trail belongs to the repository, which is itself governed by
the convention. *Confidence*: High — because the defects were found
independently by three readers (the page's owner among them) and the
revised falsifier now names a mechanism the options actually differ on:
local validation without a per-request revocation check versus a central
session check on every request. *Falsifier*: If a reader shows the
revised record still fails to license its predictions — for instance,
that the immediacy property does not separate the options as specified —
this revision is revised again, in place, by the same procedure.

**ANS:** (by Jérémie Lumbroso, 2026-09-30)
Authorized — "update the example on the website." Revised in place per
his earlier ruling that an example shows one lesson and the history
carries the rest.
