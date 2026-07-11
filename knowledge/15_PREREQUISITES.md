# 15_PREREQUISITES.md
Status: Draft (Ecosystem-level content below is a faithful transcription
of already-frozen findings; stakeholder-level Prerequisites are not yet
investigated — see TODOs)
Version: 1
Last Updated: today
Depends On: THINKING_PROCESSES/diagrams/Ecosystem_CRT.mermaid (frozen)

---

# Scope

This file documents only what has actually been investigated: the
Prerequisites (Wants) of the Ecosystem Cloud, and the assumptions
sustaining them. Individual stakeholder Prerequisites (Broker, Seller,
Buyer) have not been separately unpacked — those Clouds remain in
their frozen 3-box form (Objective → Need → Cloud), with no Want-level
analysis performed. This is a documentation-debt gap, not a diagnostic
finding, and is marked as a TODO below rather than filled in.

---

# Objective (for reference — frozen in Ecosystem_CRT.mermaid)

Reliably convert existing qualified supply and demand into qualified
opportunities.

---

# Needs (for reference — frozen in Ecosystem_CRT.mermaid)

**Need B:** Qualified reach — the right supply must reach the right
demand, not necessarily the widest possible audience.

**Need C:** Trusted representation — effort and claims must be
attributable to a specific, verifiable, accountable party.

Needs B and C are not in conflict with each other. This was an
explicit, corrected finding — an earlier draft of the Ecosystem Cloud
stated the conflict at the Need level ("broad reach" vs. "narrow
accountability"); this was revised after review determined the
evidence never supported "broad" or "maximum" reach as an actual
stakeholder objective, only "qualified" or "right" reach. The
conflict lives entirely at the Prerequisite level, below.

---

# Prerequisite D (Want D)

**Statement (currently-adopted behavior, not a capability gap):**
Broaden exposure as widely as possible, then filter for relevance
afterward.

**Serves:** Need B.

**Assumptions making this Prerequisite appear necessary:**

- **B1.** Relevance between a specific piece of supply and a specific
  piece of demand cannot currently be established before exposure — so
  filtering only happens after broadcasting, never before.
  Classification: Structural. Supports: Want D only. Status: independent.

- **B2.** A supply-side party's visibility into demand is limited to
  their own personal network; no channel gives visibility into the
  wider market's demand.
  Classification: Structural, with a Technological facet. Supports:
  Want D. Status: independent.
  *TODO — wording flag:* this assumption is phrased as "no channel
  gives visibility," which carries the same capability-gap shape the
  investigation deliberately removed from the Cloud's own wording
  (B_ROOT) during an earlier cleanup pass. Left as originally
  concluded per instruction not to reinterpret; flagged for a
  consistency pass, not resolved here.

- **B3.** Increasing the number of parties exposed to a piece of
  supply increases the odds a qualified match exists among them, and
  no better-practiced alternative currently exists.
  Classification: Behavioural / Customary. Supports: Want D only.
  Status: **derived, not independent** — this is what B1/B2 look like
  once acted on as a strategy, not a separate fact.

- **B4.** Prolonged or unusually broad exposure without a completed
  match is itself read by the market as a negative signal about the
  underlying property, independent of its actual merits.
  Classification: Behavioural / Customary. Supports: Want D, in the
  negative — the reason maximizing D can become self-defeating.
  Status: **derived, not independent** — reduces to the same
  observability gap as B1/B2 (buyers infer quality from other buyers'
  collective non-action because they cannot verify quality directly).

**Evidence considered (existing market behavior, treated as evidence
about assumptions, not as a solution):** portal aggregation already
represents the market's own most extreme version of Want D — maximum
listing exposure. It does not resolve the Cloud; inconsistent
information and inability to verify trustworthiness persist under
maximum exposure. Treated as evidence that B1/B2 are load-bearing, not
merely a convenient habit.

---

# Prerequisite D' (Want D')

**Statement (currently-adopted behavior, not a capability gap):**
Keep representation narrow and exclusive.

**Serves:** Need C.

**Assumptions making this Prerequisite appear necessary:**

- **C1.** Trust extended to one relationship cannot be reliably
  transferred or extended to additional parties without being diluted
  or lost entirely.
  Classification: Structural. Supports: Want D' only. Status: independent.

- **C2.** There is no way for a third party to independently observe
  or verify another party's effort, track record, or credibility —
  trust can only be established through direct, first-hand experience.
  Classification: Structural, with a Technological facet. Supports:
  **Both D and D'** (the same gap that produces B2 on the other branch,
  applied to trust rather than demand-visibility). Status: independent.
  *TODO — wording flag:* same issue as B2 above — "there is no way for"
  is capability-gap phrasing. Preserved as originally concluded;
  flagged, not fixed.

- **C3.** Meaningful accountability for an outcome can only attach to
  a single party — responsibility shared across several collapses to
  no one being accountable, rather than partially persisting.
  Classification: Behavioural. Supports: Want D' only. Status:
  independent, though closely coupled to C1/C2 (this coupling was
  noted, not resolved, in the original analysis).

- **C4.** Compensation for facilitating a transaction is awarded
  entirely to whichever single party closes it — not distributed
  proportionally among everyone who contributed.
  Classification: Institutional. Supports: Want D' primarily, and
  indirectly threatens Want D (broad exposure risks someone else
  closing and capturing the entire reward).
  Status: **open fork, explicitly unresolved.** It is not settled
  whether C4 reduces further to C2 (if contribution could be measured,
  proportional compensation might replace winner-take-all) or is an
  independent institutional convention that would likely persist for
  reasons of established practice or contractual simplicity, even if
  C2 were resolved. The original analysis did not settle this and
  explicitly declined to force a conclusion.

**Evidence considered on the C4 fork specifically:** large brokerage
franchises, where many agents already share one institutional brand
and often one compensation pool, still exhibit individual-agent
protectiveness (per the frozen Broker↔Broker interaction finding —
duplicate, uncoordinated effort persists even among agents sharing a
firm). Treated as evidence that changing the institutional layer (C4)
alone, without touching the observability layer (C2), does not
dissolve the behavior — suggesting C2 does more of the real work than
C4 does independently, though this does not fully resolve the fork.

---

# Assumption Sustaining the Direct Conflict (D ⟷ D')

**X.** Information, once shared with an additional party, cannot be
selectively contained — there is no way to extend access to some
information while restricting what a party does with it or who they
further share it with.
Classification: Structural, with a Technological facet. Sustains: the
conflict relationship itself, not either Want individually. Status:
**derived, not independent** — the same gap as C2, viewed from the
sharing side rather than the trusting side.
*TODO — wording flag:* same "there is no way to" pattern as B2/C2 above.

**Evidence considered:** at high ticket sizes, the market already
voluntarily abandons Want D almost entirely — invitation-only viewing,
KYC before inventory is even revealed. Treated as the strongest
evidence in the original analysis: participants deliberately sacrifice
reach when stakes rise (SR002, high value), which would not happen if
X/C1/C2 were weak or merely nominal.

---

# Irreducible Set (after merging duplicates)

Three assumptions survive as genuinely independent; everything else
above is a derived restatement of one of these.

| # | Assumption | Classification | Supports | Status |
|---|---|---|---|---|
| 1 | No third party can observe, verify, or rely on another party's trust, effort, track record, or claims without direct personal experience | Structural (Technological facet) | Both D and D' | Fundamental |
| 2 | Compensation for a closed transaction goes entirely to one party, not distributed by contribution | Institutional | D' primarily, threatens D | Fundamental — but with the open, unresolved C4 fork noted above |
| 3 | Meaningful accountability requires a single responsible party — shared responsibility collapses to none | Behavioural | D' only | Fundamental, though closely coupled to #1 and #2 |

B2, B3, B4, C1, C2, C4, and X are each a derived restatement or
consequence of assumption #1 above — the same observability/
verification gap, appearing as demand-blindness, probability-chasing
behavior, stigma toward stale listings, trust non-transferability, or
information non-containment, depending on which face of the Cloud is
being viewed. This merge was the explicit stopping point of the
original analysis; no further reduction was attempted.

---

# TODOs

1. **Wording consistency.** B2, C2, and X all use "no way to X" /
   "no channel gives" phrasing — the capability-gap pattern the
   investigation deliberately eliminated from the Cloud's own wording
   (B_ROOT) in an earlier pass. Not fixed here per instruction not to
   reinterpret. Needs a deliberate consistency pass, reconciled against
   how B_ROOT was corrected, without changing what the assumptions claim.
2. **Stakeholder-level Prerequisites not investigated.** Broker, Seller,
   and Buyer Clouds remain in 3-box form. No Want-level unpacking, and
   no corresponding assumption analysis, has been performed for any of
   them. Not inferred here — left absent, per instruction.
3. **C4's fork is unresolved by design**, not by omission. Do not
   collapse it into assumption #1 or treat it as independently settled
   without new evidence — the original analysis explicitly declined to
   force this conclusion either way.
