# UNLOX_INVESTIGATION — Documentation Structure
Version: 0.1
Status: Proposed for freeze

This structure is the one shared earlier, with six changes incorporated —
each one traced to a specific failure or near-failure that actually
occurred during this investigation, not a hypothetical concern.

---

```
UNLOX_INVESTIGATION/
│
├── 00_MANIFEST.md
│       Master index. DERIVED, not independently maintained —
│       generated/checked from the Status header block required
│       in every KNOWLEDGE and THINKING_PROCESSES file (see below).
│       This prevents manifest and file-content drift, which is
│       how status/reality mismatches quietly happen.
│
├── 01_STATUS.md
│       Current investigation status. "Where we stand."
│       Its Open Items section must cross-link to the specific
│       INVESTIGATION_LOG entry that raised each item, so status
│       and history don't drift apart.
│
├── 02_ROADMAP.md
│       Remaining work. Investigation checklist.
│
├── 03_GLOSSARY.md
│       Definitions: Opportunity, Fit, Manifestation, Representation,
│       Discovery, Signal, Noise, Evidence, Renewal, Mandate,
│       Participant, Enquiry, Transaction, etc.
│
├── KNOWLEDGE/
│   │
│   ├── 10_UDE_CATALOG.md
│   │       Canonical UDE catalogue. Every entry carries, not just
│   │       the statement: Status (Active/Retired), Retirement
│   │       Reason (if retired), Audit Badge (V/P/E/N), Provenance.
│   │       Retired UDEs stay in this file, never deleted — the
│   │       Wall's own rule (stakeholder list fixed, count is not,
│   │       nothing removed silently) applies here identically.
│   │
│   ├── 11_UDE_CLUSTERS.md
│   │       UDE clustering. Parent-child mapping. Branches.
│   │
│   ├── 12_STAKEHOLDERS.md
│   │       Stakeholder definitions. Roles. Relationships.
│   │       Each entry states investigation status explicitly:
│   │       Investigation Pending / Observations Recorded — never
│   │       omit a stakeholder for having zero observations yet.
│   │
│   ├── 13_OBJECTIVES.md
│   │       Stakeholder objectives. Every entry requires a
│   │       Level field: Stakeholder | Ecosystem. Do not rely on
│   │       file position or heading alone to convey this — write
│   │       it on the entry. This is the exact distinction that
│   │       caused real rework earlier: stakeholder Clouds and the
│   │       Ecosystem Cloud are not interchangeable in form.
│   │
│   ├── 14_NEEDS.md
│   │       Stakeholder requirements (needs). Same Level field
│   │       requirement as 13_OBJECTIVES.md, for the same reason.
│   │
│   ├── 15_PREREQUISITES.md
│   │       Stakeholder prerequisites (Wants, in TOC terms).
│   │       Must state which Need each Prerequisite currently
│   │       serves, and must be written as description of current
│   │       behavior — never phrased as a capability gap ("no way
│   │       to X"), which reads as a disguised Injection. This was
│   │       an actual, repeated defect this investigation had to
│   │       catch and fix more than once.
│   │
│   ├── 16_ONTOLOGY.md
│   │       Current ontology. Every entity entry states whether it
│   │       is Operationally Primary or Descriptive Context, and
│   │       whether any part of its status is Inferred by symmetry
│   │       rather than directly evidenced — flag, don't silently
│   │       promote inference to established fact.
│   │
│   ├── 17_PHILOSOPHY.md
│   │       Philosophical foundations.
│   │
│   ├── 18_GOVERNING_PRINCIPLES.md
│   │       Stable constitutional principles established by the
│   │       investigation.
│   │
│   └── 19_TRACEABILITY.md
│           NEW. Explicit UDE-to-node mapping for every CRT, Cloud,
│           and ontology claim. Previously this lived only as
│           invisible comments inside .mermaid files — which is
│           exactly what caused real, silent rendering failures
│           during this investigation (malformed escape sequences
│           in comments no one could see were broken). Traceability
│           gets its own structured file; diagrams stay clean.
│
├── THINKING_PROCESSES/
│   │
│   ├── CLOUDS.md
│   │       Individual (stakeholder-level) clouds. Assumptions.
│   │       Commentary. Header must state: "3-box form — Need and
│   │       Cloud collapsed. Valid only as long as no Injection is
│   │       derived independently for a single stakeholder; if one
│   │       ever is, unpack to 5-box first (see CCC.md header)."
│   │
│   ├── CCC.md
│   │       Core Conflict Cloud. Narrative. Assumptions. Discussion.
│   │       Header must state: "5-box form — Needs and Wants kept
│   │       separate. Required specifically because this Cloud
│   │       informs Injection derivation. Do not collapse to 3-box
│   │       to match CLOUDS.md — the two files use different forms
│   │       for a specific, load-bearing reason, not by oversight."
│   │
│   ├── CRT.md
│   │       Current Reality Tree. Narrative. Findings. Relationship
│   │       between Broker, Buyer, Seller, and Ecosystem CRTs —
│   │       explicitly note which cross-stakeholder interactions
│   │       were investigated, which were checked-and-found-empty,
│   │       and which remain unchecked. These are three different
│   │       epistemic states and must not be collapsed into one.
│   │
│   ├── FRT.md
│   │       Future Reality Tree. Injections. Narrative.
│   │
│   ├── NBR.md
│   │       Negative Branch Reservations.
│   │
│   ├── PRT.md
│   │       Prerequisite Tree.
│   │
│   ├── TT.md
│   │       Transition Tree.
│   │
│   └── diagrams/
│       │   All diagrams use .mermaid, not .mmd — this environment
│       │   only renders .mermaid live; .mmd silently downloads as
│       │   text instead, which happened more than once tonight. If
│       │   GitHub rendering is also required, embed the same
│       │   content as a fenced ```mermaid block inside the
│       │   corresponding .md file rather than relying on a
│       │   standalone file extension GitHub doesn't auto-render
│       │   either.
│       │
│       ├── Broker_CRT.mermaid
│       ├── Buyer_CRT.mermaid
│       ├── Seller_CRT.mermaid
│       ├── Ecosystem_CRT.mermaid
│       │
│       ├── FRT.mermaid
│       ├── PRT.mermaid
│       ├── TT.mermaid
│       └── (future diagrams)
│
├── PRODUCT/
│   │
│   ├── CONSTITUTION.md
│   │       Product constitution. Non-negotiable design principles.
│   │
│   ├── ARCHITECTURE.md
│   │       Overall architecture.
│   │
│   ├── FEATURES.md
│   │       Product features. Functional specifications.
│   │
│   ├── WORKFLOWS.md
│   │       User journeys. Operational workflows.
│   │
│   └── VALIDATION.md
│           Validation strategy. Pilot learnings. Evidence gathered.
│
└── INVESTIGATION_LOG/
    │
    ├── YYYY-MM-DD.md
    ├── YYYY-MM-DD.md
    └── ...
```

---

## Required file header (KNOWLEDGE/ and THINKING_PROCESSES/ only)

Every file in these two directories opens with:

```
Status: Draft | Frozen
Version: N
Last Updated: YYYY-MM-DD
Depends On: [other files this one assumes are settled]
```

`00_MANIFEST.md` is built by reading these headers, not maintained
independently — this is the single structural fix that prevents most
of the other drift risks below it.

---

## Summary of what changed from the version you shared, and why

| # | Change | Traced to |
|---|---|---|
| 1 | UDE Catalog requires Status/Retirement/Audit/Provenance fields | The Wall's retirement discipline — never delete, always document |
| 2 | New 19_TRACEABILITY.md, separate from diagrams | Invisible-comment rendering failures that actually occurred |
| 3 | Mandatory Level field on every Objective/Needs entry | The stakeholder-Cloud vs. Ecosystem-Cloud form mismatch |
| 4 | Explicit header notes in CLOUDS.md and CCC.md on representational form | Same mismatch — documented so it can't be "fixed" by collapsing back |
| 5 | Status/Version header required in every file; Manifest derived, not authored | Prevents status-table vs. file-content drift |
| 6 | .mermaid standardized over .mmd | Silent rendering failures that actually occurred, more than once |

Everything else — the top-level layout, PRODUCT/, INVESTIGATION_LOG/,
the overall Diagnosis/Design separation — is unchanged from what you
proposed. It was already right.
