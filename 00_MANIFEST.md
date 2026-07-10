# 00_MANIFEST.md
Status: Frozen
Version: 1
Last Updated: today
Depends On: (this file has no dependencies — it is derived from every other file's header)

---

This manifest is derived from the Status/Version/Depends-On header of
every file in KNOWLEDGE/ and THINKING_PROCESSES/. It is not
independently authored. If a file's header changes, this manifest
must be regenerated from it — never edited to match a stale file, or
edited in place while the file lags behind.

---

## KNOWLEDGE/

| File | Status | Version | Depends On |
|---|---|---|---|
| 10_UDE_CATALOG.md | Frozen | 4 | — |
| 11_UDE_CLUSTERS.md | Frozen | 3 | 10_UDE_CATALOG.md |
| 12_STAKEHOLDERS.md | Frozen | 3 | 10_UDE_CATALOG.md, 11_UDE_CLUSTERS.md |
| 13_OBJECTIVES.md | Draft | 1 | 12_STAKEHOLDERS.md |
| 14_NEEDS.md | Draft | 1 | 13_OBJECTIVES.md |
| 15_PREREQUISITES.md | Draft | 1 | 14_NEEDS.md — content exists only in chat transcript (the Ecosystem Cloud assumption analysis); not yet filed |
| 16_ONTOLOGY.md | Frozen | 2 | 10_UDE_CATALOG.md (specifically U006), THINKING_PROCESSES/CRT.md |
| 17_PHILOSOPHY.md | Stable | 1 | — |
| 18_GOVERNING_PRINCIPLES.md | Stable | 1 | — |
| 19_TRACEABILITY.md | Not started | — | 10_UDE_CATALOG.md, all diagrams/ |

## THINKING_PROCESSES/

| File | Status | Version | Depends On |
|---|---|---|---|
| CLOUDS.md | Not started | — | 13_OBJECTIVES.md, 14_NEEDS.md — content exists only in each stakeholder CRT diagram, not yet extracted into prose |
| CCC.md | Draft | 1 | CRT.md — 5-box Cloud is frozen inside diagrams/Ecosystem_CRT.mermaid; assumption analysis exists only in chat transcript, not yet filed here |
| CRT.md | Draft | 1 | diagrams/Broker_CRT.mermaid, Seller_CRT.mermaid, Buyer_CRT.mermaid, Ecosystem_CRT.mermaid — narrative prose not yet written; diagrams are the frozen source of truth |
| FRT.md | Not started | — | CCC.md |
| NBR.md | Not started | — | FRT.md |
| PRT.md | Not started | — | NBR.md |
| TT.md | Not started | — | PRT.md |

## THINKING_PROCESSES/diagrams/ (frozen artifacts, source of truth for CRT.md and CCC.md above)

| File | Status | Supersedes |
|---|---|---|
| Broker_CRT.mermaid | Frozen | Broker_Minimal_Stakeholder_CRT (pilot — used synthesized Trunk UDEs, rejected for readability) |
| Seller_CRT.mermaid | Frozen | — |
| Buyer_CRT.mermaid | Frozen | — |
| Broker_Intra_Stakeholder.mermaid | Frozen | — |
| Buyer_Intra_Stakeholder.mermaid | Frozen | — (finding: no loop exists, recurrence only) |
| Broker_Seller_Interaction.mermaid | Frozen | — |
| Broker_Buyer_Interaction.mermaid | Frozen | — |
| Seller_Buyer_Interaction.mermaid | Frozen | — (finding: one-directional, non-driving) |
| Ecosystem_CRT.mermaid | Frozen | CRT_v5.1 through v9 (ecosystem-down approach, superseded entirely by stakeholder-up assembly) |

## PRODUCT/

| File | Status |
|---|---|
| CONSTITUTION.md | Not started |
| ARCHITECTURE.md | Not started |
| FEATURES.md | Not started |
| WORKFLOWS.md | Not started |
| VALIDATION.md | Not started — informal Injection sketches (Broker/Seller matching-network concept) exist only in chat transcript |

---

## Known gaps this manifest surfaces (do not silently resolve — see 01_STATUS.md Open Items)

- 15_PREREQUISITES.md and part of CCC.md's assumption analysis exist only in chat transcript, not yet filed. This is real content, already produced, sitting outside the documentation structure.
- CLOUDS.md and CRT.md narrative prose do not exist yet — the diagrams are currently the only frozen source of truth for stakeholder-level findings.
- 19_TRACEABILITY.md does not exist yet. Traceability currently still lives as inline Mermaid comments inside the diagrams — the exact arrangement this structure was designed to move away from.
