# 19_TRACEABILITY.md
Status: Draft (Broker/Seller/Buyer/Ecosystem chains complete; six
stakeholders not yet investigated, so no traceability exists for them)
Version: 1
Last Updated: today
Depends On: diagrams/Broker_CRT.mermaid, Seller_CRT.mermaid,
Buyer_CRT.mermaid, Ecosystem_CRT.mermaid (all frozen), KNOWLEDGE/15_PREREQUISITES.md,
THINKING_PROCESSES/CLOUDS.md, THINKING_PROCESSES/CCC.md, KNOWLEDGE/16_ONTOLOGY.md

---

# Scope

Audit index only — no narrative, no justification. Every row below
was already established as an explicit mapping inside a frozen file or
its inline comments; this document extracts and organizes those
mappings into one navigable index. Where a link in the requested chain
(UDE → CRT node → Cloud → Assumption → Ontology claim → originating
correction) does not exist explicitly, it is marked TODO rather than
inferred.

---

# 1. UDE → CRT Node

## Broker (source: diagrams/Broker_CRT.mermaid, inline traceability comment)

| UDE(s) | CRT Node |
|---|---|
| U016, U017 | B1 |
| U024 | B1a |
| U025 | B1b |
| U013, U014, U026 | B1c |
| U018, U019 | evidence underlying B1d |
| U020 | B1e |
| U015 | B2a |
| U021, U022 | PORTAL (shared node) |
| U023, U028 | BRAND (shared node — discoverability gap, restated; see §6) |

## Seller (source: diagrams/Seller_CRT.mermaid, inline traceability comment)

| UDE(s) | CRT Node |
|---|---|
| U106 | D1 |
| U107 | D2 |
| U108 | D3 |
| U111 | MULTI |
| U109, U110 | E1 |
| U112, U113 | E2 |
| U114, U116, U119, U120 | E3 |
| U115, U122 | E4 |
| U117, U118 | F1 — **flagged, not resolved into the Cloud**; tentatively terminates at SR003 |

## Buyer (source: diagrams/Buyer_CRT.mermaid, inline traceability comment)

| UDE(s) | CRT Node |
|---|---|
| U001 | BS1 |
| U011 | BS2 |
| U012 | BS3 |
| U006 | BS4 |
| U002 | BS5 |
| U003 | BS6 |
| U009 | BS7 |
| U123 | BS8 |
| U004 | TR1 |
| U005 | TR2 |
| U007 | TR3 |
| U008 | TR4 |
| U010 | TR5 |
| U124 | TR6 |
| U125 | TR7 |
| U126 | TR8 |
| U127 | TR9 |
| U128 | TR10 |
| U129 | TR11 |
| U130 | TR12 |

**TODO:** Developer, Bank / Mortgage Provider, Insurance, Legal /
Compliance, Interior Designer / Architect, Property Portal — no CRT
exists, so no UDE → CRT node mapping exists.

---

# 2. CRT Node(s) → Cloud

| Source Nodes | Cloud |
|---|---|
| Broker: B1e, B2a (via PORTAL, BRAND) | Broker's Internal Cloud (CLOUDS.md) |
| Seller: E4; D1 (direct, dashed — "doubt persists either way") | Seller's Internal Cloud (CLOUDS.md) |
| Buyer: BS6, BS7, BS8, TR6–TR12 | Buyer's Internal Cloud (CLOUDS.md) |
| Ecosystem: B_ROOT (Dominant Structural Cause) | Ecosystem Cloud, via Want D and Want D' (CCC.md) |

**Instance-of relationship (source: diagrams/Ecosystem_CRT.mermaid):**
Broker's, Seller's, and Buyer's own Internal Clouds are each marked as
an *instance of* the Ecosystem Cloud's Want-level conflict (D ⟷ D'),
not the Need level (Need B / Need C, which do not conflict).

---

# 3. Cloud → Assumption(s)

| Cloud | Assumption(s) | Source |
|---|---|---|
| Broker's Internal Cloud | A1 (sharing = losing control/differentiation); A2 (only paths to reach are a platform or personal over-extension) | CLOUDS.md |
| Seller's Internal Cloud | A1 (one broker may not reach enough of the market); A2 (multiple brokers = less accountability, not more) | CLOUDS.md |
| Buyer's Internal Cloud | A1 (only way to avoid missing the right property is checking many sources); A2 (settling on one source risks missing what's outside its view) | CLOUDS.md |
| Ecosystem Cloud | Full assumption set (B1–B4, C1–C4, X), merged to irreducible set (#1, #2, #3) | 15_PREREQUISITES.md, summarized in CCC.md |

**Ecosystem irreducible assumption set (source: 15_PREREQUISITES.md):**

| # | Assumption | Supports |
|---|---|---|
| 1 | No third party can observe, verify, or rely on another party's trust, effort, track record, or claims without direct personal experience | Both Want D and Want D' |
| 2 | Compensation for a closed transaction goes entirely to one party, not distributed by contribution | Want D' primarily, threatens Want D — **open fork, explicitly unresolved** (may reduce to #1) |
| 3 | Meaningful accountability requires a single responsible party | Want D' only |

---

# 4. Assumption(s) → Ontology Claim(s)

| Assumption | Ontology Claim | Source |
|---|---|---|
| Ecosystem Assumption #1 / Dominant Structural Cause (B_ROOT) | "Trust, Effort, and Market Knowledge are each confined within a single Mandate and do not cross into any other Mandate" — stated as "the boundary that does the actual explanatory work across this entire investigation" | 16_ONTOLOGY.md, explicitly cross-referencing B_ROOT |

**TODO:** No explicit link was established between Ecosystem Assumption
#2 (compensation allocation) and any specific Ontology claim (e.g. the
Compensation/Commission attribute of Transaction), despite an apparent
topical connection. Not inferred here.

**TODO:** No explicit link was established between Ecosystem Assumption
#3 (single-party accountability) and the Ontology's Accountability
attribute definition, despite an apparent topical connection. Not
inferred here.

---

# 5. UDE → Ontology Claim (direct — bypasses Cloud/Assumption)

Several Ontology claims were established directly from UDE evidence,
not routed through a Cloud or Assumption. Recorded separately rather
than forced into the chain above.

| UDE(s) | Ontology Claim | Source |
|---|---|---|
| U006 | Central test case for demoting Property/Requirement from operational anchor to descriptive context; resolved via a missing propagation event between a Participant's own Mandates | 16_ONTOLOGY.md |
| U002 | Requirement can exist unmatched — evidence Requirement is a genuine entity independent of any Property | 16_ONTOLOGY.md |
| U111, U010 | Mandate formation ("appointment"/"engagement") is a discrete relational event, not an attribute of either party | 16_ONTOLOGY.md |
| U006, U063, U118 | Representation diverges from ground truth — evidence Representation is ontologically separate from what it represents | 16_ONTOLOGY.md |
| U012, U021 | Channel is distinct from Participant interest — evidence basis for retiring "Portal" from fundamental status (§6) | 16_ONTOLOGY.md |
| U114 | Enquiry is distinguished from both Requirement (standing) and Mandate (durable) — evidence Enquiry is its own transient entity | 16_ONTOLOGY.md |
| U026 | Mandate termination can be implicit decay, not only explicit ending | 16_ONTOLOGY.md |
| Broker/Seller/Buyer CRTs (Objective/Need/Cloud each independently derived) | Participant is a genuine locus of agency, not merely a label | 16_ONTOLOGY.md |

---

# 6. Ontology Claim → Originating Investigation or Correction

| Ontology Claim | Origin |
|---|---|
| Property and Requirement reclassified from operational anchor to descriptive context | The "Anchor in which domain?" exchange — resolved specifically via the U006 test, distinguishing physical/legal reality from operational-ontology and computational-implementation domains |
| Missing propagation event (Transaction-completion does not notify a Participant's other Mandates) added in place of a coordinating-identity requirement | Same exchange as above |
| Opportunity (not Property) is the operationally primary unit | Raised independently in conversation (multiple brokers producing independent, non-shared opportunities from one physical asset); the U006 test above later qualified this — Property still supplies a real, independent anchor fact even though it is not an operational coordinator |
| "Portal" retired from fundamental status (conflates Channel and a self-interested Participant) | Original ontology-extraction pass, evidenced by U012/U021/U022 |
| "Broker" identified as a domain-specific instance of a general Intermediary-holding-a-Mandate role | Same ontology-extraction pass |
| "Commission" identified as a domain-specific instance of a general Compensation-allocation rule | Same ontology-extraction pass |
| Demand-side propagation (Requirement analogue of U006) | **Not directly evidenced** — inferred by symmetry only; explicitly flagged as unconfirmed in 16_ONTOLOGY.md and 01_STATUS.md Open Items |

---

# 7. Cross-Stakeholder Interaction Traceability

Recorded separately, as these findings sit alongside individual CRTs
rather than inside the UDE → CRT → Cloud chain above.

| Interaction | Finding | Source |
|---|---|---|
| Broker↔Broker | Closed reinforcing loop; not a new Cloud | diagrams/Broker_Intra_Stakeholder.mermaid (not yet named in the frozen Documentation Structure — see 02_ROADMAP.md compliance note) |
| Buyer↔Buyer | No loop found; recurrence only | diagrams/Buyer_Intra_Stakeholder.mermaid (same compliance note) |
| Broker↔Seller | Closed loop, 3 minimal links | diagrams/Broker_Seller_Interaction.mermaid (same compliance note) |
| Broker↔Buyer | Closed loop, 5 minimal links | diagrams/Broker_Buyer_Interaction.mermaid (same compliance note) |
| Seller↔Buyer | One-directional, non-driving | diagrams/Seller_Buyer_Interaction.mermaid (same compliance note) |

---

# TODOs

1. Assumption #2 (compensation) and Assumption #3 (accountability) have
   no established link to a specific Ontology claim — see §4.
2. Demand-side propagation is unconfirmed — see §6, last row.
3. No traceability exists for Developer, Bank / Mortgage Provider,
   Insurance, Legal / Compliance, Interior Designer / Architect, or
   Property Portal — no investigation has occurred for any of them.
4. The five interaction-map diagrams referenced in §7 are real and
   frozen but are not yet named in the frozen Documentation Structure
   (see 02_ROADMAP.md compliance note) — this document cannot cite a
   canonical structure location for them until that is resolved.
