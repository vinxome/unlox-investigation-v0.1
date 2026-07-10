# 16_ONTOLOGY.md
Status: Frozen
Version: 2
Last Updated: today
Depends On: 10_UDE_CATALOG.md (specifically U006, U111, U112, U114), THINKING_PROCESSES/CRT.md

Supersedes: v1 (Property treated as operational anchor). Superseded
after evidence showed the anchor claim was inherited from a canonical
information-architecture assumption, not required by the UDEs
themselves. See Open Item in 01_STATUS.md regarding demand-side
symmetry, which this revision inherits.

---

# Operational Unit

**Opportunity** is the operational unit of the ecosystem.

A Selling Opportunity and a Buying Opportunity are instances of the
same fundamental concept. Supply and demand are not fundamentally
different entity types — this symmetry is what the identically-shaped
Broker↔Seller and Broker↔Buyer Ecosystem Cloud findings predicted in
advance, not a coincidence discovered afterward.

An Opportunity has a lifecycle: **open/seeking → engaged/paired →
manifested or abandoned.** [See Open Item in 01_STATUS.md: this
lifecycle's terms are not yet reconciled with the Ecosystem
Constraint's use of "qualified opportunities."]

---

# Entities

| Entity | Primary / Context | Persistent / Transient | Local / Ecosystem |
|---|---|---|---|
| Participant | Primary | Persistent | Ecosystem |
| Opportunity | Primary | Transient | Ecosystem by nature |
| Mandate | Primary | Transient | Local |
| Representation | Primary | Transient | Local-to-Channel |
| Channel | Primary | Persistent | Ecosystem |
| Enquiry | Primary | Transient | Local |
| Transaction | Primary | Transient (instantaneous) | Ecosystem |
| Property | Descriptive context | Persistent (in physical/legal reality) | — not an operational entity |
| Requirement | Descriptive context | Transient | — not an operational entity |

Not independent entities — attributes of the above, retained here
only to prevent them being reintroduced as if they were entities:

- **Trust** — belief-state held within a Mandate.
- **Effort** — attribute of a Participant's actions within a Mandate.
- **Market Knowledge** — derived aggregate, built from accumulated
  Opportunity/Transaction history; has no existence prior to or
  independent of the primary entities.
- **Discoverability / Reach / Exposure / Visibility** — one attribute
  of Representation, referred to by four different words across
  Broker, Seller, and Buyer's own independently-derived wording.
- **Compensation / Commission** — an allocation rule applied at the
  Transaction event, not a standalone entity.
- **Accountability** — derived from whether Trust and Effort are
  observable; no independent existence apart from them.

---

# Property and Requirement — Descriptive Context, Not Operational Anchors

This is the load-bearing revision in this version. Full reasoning
lives in the transcript; the conclusion, precisely stated:

**Property and Requirement are real** — a physical asset exists, and
its ownership changes exactly once in objective reality. **But the
ecosystem does not require a shared operational identity for either
one** in order to explain the evidence collected.

The test case is U006 ("I message about a property only to find out
it was sold or rented weeks ago"). This does not require Property to
function as a coordinating identity that independent Opportunities
check against. It is fully explained by a narrower, cheaper mechanism:
a Seller who closes one Mandate already knows the deal closed — this
is trivial, already-possessed knowledge, not something requiring a
new entity to model. **The actual gap is a missing propagation event
between that Participant's own Mandates**, not a missing shared
identity across independent Participants.

This finding is currently evidenced only on the supply side. The
demand-side equivalent (a Buyer's satisfied Requirement propagating
across that Buyer's own active Mandates) is inferred by symmetry, not
directly evidenced by any wall UDE. **Flagged, not settled** — see
01_STATUS.md Open Items.

---

# Events

| Event | Effect |
|---|---|
| Requirement formed | Creates a Requirement (Buyer) |
| Requirement abandoned/satisfied | Terminates a Requirement |
| Mandate formed | Creates a relationship between two Participants |
| Mandate terminated | Ends a relationship (sometimes explicit, sometimes decay — U026 describes decay with no clean termination event) |
| Representation published | Creates an artifact standing in for descriptive context |
| Representation staled | Representation diverges from current reality (U006) |
| Enquiry made | A Participant acts toward a Representation |
| Opportunity formed | An Enquiry is recognized as reflecting genuine mutual relevance |
| Opportunity abandoned | Fails to convert and decays |
| Transaction completed | An Opportunity converts |
| **[Missing]** Mandate-closure propagation | Does not currently occur: a Transaction completing does not notify a Participant's other active Mandates referencing the same descriptive context. This is the mechanism U006 is a symptom of. No new entity required to add this — only the event itself. |
| Compensation allocated | Value distributed among contributing Mandates, following Transaction |

---

# Relationships

- Seller **owns** Property (exactly one Seller per Property at a time — in objective reality; not tracked as a coordinating fact by the ecosystem)
- Buyer **holds** Requirement
- Participant **enters** Mandate **with** an Intermediary (many Mandates possible in parallel, per party — evidenced directly by U111)
- Intermediary **publishes** Representation **via** Channel
- Participant **performs** Enquiry **directed at** Representation
- Enquiry **may become** Opportunity
- Opportunity **may convert into** Transaction
- Transaction **should, but currently does not, propagate** to a Participant's other Mandates referencing the same descriptive context

---

# Boundaries

**Relationship boundary:** a Mandate links exactly two Participants,
but one Participant can hold many Mandates concurrently, with no
exclusivity currently enforced. This is what produces Broker's own
Cloud once multiplied across a population.

**The boundary that does the actual explanatory work across this
entire investigation:** Trust, Effort, and Market Knowledge are each
confined within a single Mandate and do not cross into any other
Mandate held by the same or a different Participant. Every stakeholder
Cloud, the Broker↔Broker/Seller/Buyer interaction loops, and the
Ecosystem Cloud itself are different views of consequences of this one
boundary — not separate phenomena.

**Investigation boundary (scope, not domain):** Seller, Buyer, and
Broker are validated Participant roles with their own derived CRTs.
Bank, Insurance, Legal, Designer, Developer, and Portal-as-Channel are
acknowledged as existing but remain outside what this investigation
has directly validated.

---

# Concepts Retired From Fundamental Status

- **"Portal"** — conflates two separate things: Channel (hosting
  Representations for discovery) and a self-interested Participant
  (pay-to-play ranking). Domain terminology for an unresolved
  conflation, not a fundamental entity.
- **"Broker"** — domain label for the general role
  Intermediary-holding-a-Mandate. Validated as its own Participant in
  this investigation, but structurally an instance of a pattern Bank,
  Insurance, Legal, and Designer likely also instantiate.
- **"Commission"** — instance of the general Compensation-allocation
  rule applied at Transaction.

---

# Methodological Note Carried Into This Ontology

Before positing a new entity or shared coordinating identity, verify
whether an existing Participant already possesses the relevant fact
privately, and the actual gap is only a missing propagation event.
This is the specific, evidence-tested lesson this revision produced —
not a general truism, a rule this investigation got wrong once and
corrected.
