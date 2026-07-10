# 02_ROADMAP.md
Status: Current
Version: 1
Last Updated: today
Depends On: UNLOX_Documentation_Structure.md (frozen), 00_MANIFEST.md

---

# Standing Rule

Every artifact defined in UNLOX_Documentation_Structure.md appears
exactly once below. No more, no less. This file has no independent
content — it is the execution-state view of a structure that is
already frozen. If a new artifact is ever needed, it is added to the
structure first, and only then gets a row here.

Two exclusions, both deliberate, not oversights:
- **diagrams/** files are included as their own subsection below,
  since they are individually named in the frozen structure — even
  though the illustrative example that prompted this file didn't show
  them. Excluding named artifacts would violate the standing rule above.
- **INVESTIGATION_LOG/** is excluded. It's an open-ended pattern
  (`YYYY-MM-DD.md`), not a fixed, enumerable artifact — there is no
  single row it could correspond to.

Columns: **Investigation** = has the diagnostic/analytical work
actually been done, regardless of where it currently lives.
**Documentation** = does it exist as this specific file, in this
specific structure, right now.

---

## Top Level

| Artifact | Investigation | Documentation | Status |
|---|---|---|---|
| 00_MANIFEST.md | ✓ | ✓ | Complete |
| 01_STATUS.md | ✓ | ✓ | Complete |
| 02_ROADMAP.md | WIP | WIP | Current |
| 03_GLOSSARY.md | Partial (core ontology terms rigorously defined; Fit, Manifestation, Signal, Noise, Renewal used informally, not yet formally defined) | ✗ | Pending |

## KNOWLEDGE/

| Artifact | Investigation | Documentation | Status |
|---|---|---|---|
| 10_UDE_CATALOG.md | ✓ | ✗ (content exists as UDE_Wall_Stakeholder_v4.html, not filed under this name) | Documentation WIP |
| 11_UDE_CLUSTERS.md | ✓ | ✗ | Documentation WIP |
| 12_STAKEHOLDERS.md | ✓ | ✗ | Documentation WIP |
| 13_OBJECTIVES.md | ✓ (largely — Broker/Seller/Buyer/Ecosystem done; Developer/Bank/Insurance/Legal/Designer/Portal not investigated) | ✗ (exists only inside CRT diagrams) | Documentation WIP |
| 14_NEEDS.md | ✓ (largely — same scope as 13_OBJECTIVES.md) | ✗ | Documentation WIP |
| 15_PREREQUISITES.md | ✓ (largely — full assumption analysis done for the Ecosystem Cloud; NOT done for individual stakeholder Clouds, which remain in simplified 3-box form) | ✗ (exists only in chat transcript) | Documentation WIP |
| 16_ONTOLOGY.md | ✓ | ✓ | Complete |
| 17_PHILOSOPHY.md | ✓ | ✗ (scattered across 01_STATUS.md's principle lists; no dedicated file) | Documentation WIP |
| 18_GOVERNING_PRINCIPLES.md | ✓ (largely — 8 stable principles already established in 01_STATUS.md; not exhaustively finalized) | ✗ | Documentation WIP |
| 19_TRACEABILITY.md | ✓ (implicit — exists as inline comments in every diagram) | ✗ | Documentation WIP |

**Correction from the illustrative example:** 18_GOVERNING_PRINCIPLES.md
investigation status raised from "Partial" to "✓ (largely)" — real,
substantive principles already exist (Opportunity primacy, fit over
exhaustive search, evidence close to source, decay, renewal,
constitutional neutrality, broker-centricity, discovery≠trust), just
not yet filed under this exact name.

## THINKING_PROCESSES/

| Artifact | Investigation | Documentation | Status |
|---|---|---|---|
| CLOUDS.md | ✓ (partially — Broker, Seller, Buyer done; other stakeholders not investigated) | ✗ (exists only inside CRT diagrams) | Documentation WIP |
| CCC.md | ✓ (Cloud fully unpacked to 5-box form, plus complete assumption analysis) | Partial (Cloud itself frozen in Ecosystem_CRT.mermaid; assumption-analysis prose not yet filed here) | Documentation WIP |
| CRT.md | ✓ (all four CRTs built, frozen, and cross-interaction fully traced) | ✗ (narrative prose doesn't exist; diagrams are currently the only source of truth) | Documentation WIP |
| FRT.md | ✗ | ✗ | Not Started |
| NBR.md | ✗ | ✗ | Not Started |
| PRT.md | ✗ | ✗ | Not Started |
| TT.md | ✗ | ✗ | Not Started |

## THINKING_PROCESSES/diagrams/

**Compliance note:** the frozen structure names exactly 7 files here
(the four CRTs plus FRT/PRT/TT placeholders), with a trailing
`(future diagrams)` comment. It does **not** name
Broker_Intra_Stakeholder.mermaid, Buyer_Intra_Stakeholder.mermaid,
Broker_Seller_Interaction.mermaid, Broker_Buyer_Interaction.mermaid,
or Seller_Buyer_Interaction.mermaid — five real, frozen artifacts that
the Ecosystem_CRT.mermaid's own reinforcing-loop findings directly
depend on. An earlier version of this roadmap added rows for them
anyway, which broke the "no more, no less" rule stated at the top of
this file. Removed below, not silently — this is a genuine gap
between what's been produced and what the structure enumerates, and
it belongs in UNLOX_Documentation_Structure.md as a deliberate
amendment (naming them explicitly, replacing the generic "(future
diagrams)" placeholder), not patched here by exception.

| Artifact | Investigation | Documentation | Status |
|---|---|---|---|
| Broker_CRT.mermaid | ✓ | ✓ | Complete |
| Seller_CRT.mermaid | ✓ | ✓ | Complete |
| Buyer_CRT.mermaid | ✓ | ✓ | Complete |
| Ecosystem_CRT.mermaid | ✓ | ✓ | Complete |
| FRT.mermaid | ✗ | ✗ | Not Started |
| PRT.mermaid | ✗ | ✗ | Not Started |
| TT.mermaid | ✗ | ✗ | Not Started |

**Not yet representable in this roadmap** (exist, frozen, real —
excluded only because the structure doesn't name them yet):
Broker_Intra_Stakeholder.mermaid, Buyer_Intra_Stakeholder.mermaid,
Broker_Seller_Interaction.mermaid, Broker_Buyer_Interaction.mermaid,
Seller_Buyer_Interaction.mermaid.

## PRODUCT/

| Artifact | Investigation | Documentation | Status |
|---|---|---|---|
| CONSTITUTION.md | Partial (three structural non-negotiables discussed: no consumer-facing surface, no pay-for-visibility revenue, no in-house brokerage) | ✗ | Pending |
| ARCHITECTURE.md | Partial, unintegrated (a matching-network sketch exists in detail, but was produced before the diagnostic freeze and has not been reconciled against the frozen CRT/Cloud) | ✗ | Documentation WIP |
| FEATURES.md | ✗ | ✗ | Not Started |
| WORKFLOWS.md | ✗ | ✗ | Not Started |
| VALIDATION.md | Partial (pilot/validation philosophy discussed — observe→intervene→observe cycle, "under investigation" investor framing) | ✗ | Pending |

**Corrections from the illustrative example:** FEATURES.md and
WORKFLOWS.md investigation status lowered from "✓" to "✗" — no
feature-level or user-journey work has actually occurred; the CRT work
deliberately stayed in diagnosis throughout. ARCHITECTURE.md changed
from "✓ (implicit)" to "Partial, unintegrated" — real detail exists,
but it predates the freeze and hasn't been checked against what the
frozen Ecosystem Cloud actually implies.

---

# What This Roadmap Is Not

It is not an independent checklist and carries no content of its own
beyond execution state. If investigation or documentation status ever
needs to change, the change is made here — not by adding a new kind of
entry, and not by describing new work that isn't already implied by an
artifact already named in the frozen structure.
