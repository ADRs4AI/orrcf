# ADR-0001: Founding — one page, one term, spinoff-ready by construction

- **Status**: Accepted
- **Date**: 2026-08-27
- **Deciders**: Jérémie Lumbroso (delegated the implementation whole: "your agency/expertise prevails"); Pharos 5 (Claude Fable 5) — design and build
- **Context**: An incognito reviewer called ORRCF "the strongest thing on the site … a convention someone can adopt this afternoon with zero buy-in to anything else" and proposed shipping it standalone. The founder's prior agreed (orrcf.org as a self-contained home). Mint 5's counsel (naming, 2026-08-27): page first under the apex, domain gated on an escape-trigger; the wedge lives in the term register.

## Decisions

1. **Separate repository, named `orrcf`** — not a subpage of the main site, and not `orrcf-page`: Under GitHub Pages org-domain tenancy the repository name is the URL path, so `ADRs4AI/orrcf` serves at `adrs.systems/orrcf/` with zero routing config — and the day the escape-trigger fires, `orrcf.org` attaches to this repo directly. The founder's spinoff instinct and the page-first ruling compose in one shape.
2. **Generated from the house template** (`ADRs4AI/human-ai-collaboration-template-A`) — the template's first "Use this template" generation, by the house itself. Fixtures trimmed (QUICK-START, the template-output grant — which by its own terms does not travel into generated repos); scaffolding kept (templates, justfile, methodology, this very file's grammar).
3. **One self-contained page** (`site/index.html`, inline CSS, no dependencies, no motion) + the README as the same content in stealable Markdown. The five components, the payoff, a copyable QST block, one worked example.
4. **Term budget enforced**: ORRCF and its five spelled words are the only coinage on the surface. The page must be takeable with zero buy-in — that is its entire job.
5. **Provenance kept honest**: The page credits ADRs4AI as home, notes the convention grew from a simpler Options-Recommendation-Justification form, and states that this repo's own decisions live in `docs/adr/` — the page about the convention is governed by the convention.

## Questions

### QST-DOMAIN: When does orrcf.org get bought and attached?

- Status: unanswered
- Why asking: Mint's assay found `.org` and `.com` free with low squat risk; buying early fragments the family, buying never loses the escape moment.

**Options**

- **A — On the escape-trigger** (an outsider links /orrcf/ as a thing-in-itself, or the term appears in strangers' vocabulary unprompted).
- **B — Now**, parked and 301'd.
- **C — Never**; the path is the permanent home.

**Recommendation**: (by Pharos 5, Claude Fable 5, 2026-08-27)

**A.** *Rationale*: Mint's assay — a premature domain fragments the family presence; a triggered domain, 301-linked both ways, strengthens it; five-letter non-word initialisms have low squat-decay, so waiting costs nothing. *Confidence*: High — this adopts standing counsel with a named trigger rather than a date. *Falsifier*: Squatting evidence on orrcf.org, which re-prices the wait immediately.

**ANS:** (by …)

---

*Founded 2026-08-27, launch week, by Pharos 5 at the founder's word.*
