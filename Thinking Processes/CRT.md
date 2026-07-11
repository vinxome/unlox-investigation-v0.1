# THINKING_PROCESSES/CRT.md
Status: Draft (Broker/Seller/Buyer/Ecosystem complete; six stakeholders
and one intra-stakeholder pair not yet investigated — see Not Yet
Investigated section)
Version: 1
Last Updated: today
Depends On: diagrams/Broker_CRT.mermaid, Seller_CRT.mermaid,
Buyer_CRT.mermaid, Ecosystem_CRT.mermaid (all frozen), KNOWLEDGE/16_ONTOLOGY.md

---

# Purpose

This is the narrative companion to the frozen CRT diagrams. It exists
because, until now, understanding what each CRT actually found
required opening and reading Mermaid source directly. Nothing here is
new reasoning — every claim traces to a frozen diagram or an
explicitly-completed interaction investigation.

---

# Methodology Note

Every stakeholder CRT is drawn as an explicit IF/THEN causal chain,
not a compressed "Trunk UDE." An earlier pilot (superseded — see
00_MANIFEST.md) synthesized multiple UDEs into a single abstracted
root-cause node. This was reviewed and rejected: a synthesized node
states a conclusion without showing the steps that get there, which
reads as an analyst's summary rather than something that can be argued
with. Every node in the current diagrams is either a direct Wall
statement (solid border) or an explicit inferred connecting step
(dashed border) — never both merged into one.

---

# Broker CRT

Two branches, both converging on the same shared consequences.

**Branch 1 (protects relationships):** because trust and market
knowledge only work within Broker's own circle and don't transfer,
Broker keeps relationships and inventory knowledge private rather than
share them. This produces two parallel effects: missed co-broking
opportunities and duplicate work with other brokers; and fragmented,
manually-tracked inventory, with knowledge lost whenever a contact
moves on. Both converge on Broker's reach and efficiency staying
limited to what can be personally covered — which shows up as an
inability to demonstrate expertise digitally.

**Branch 2 (increases reach):** Broker's relationships don't scale —
only so many can be personally maintained — so Broker can't personally
build enough relationships to reach further alone, and ends up
depending on portals for visibility.

**Convergence:** both branches land on the same two consequences —
portals controlling who sees Broker's listings (pay-to-play), and
Broker's discoverability lagging aggregated discovery channels, with
no network-effect benefit felt from being on the platform. From here,
Branch 2 continues into losing long-term bargaining power, since the
portal controls access to buyers, not Broker.

**Cloud:** see CLOUDS.md.

---

# Seller CRT

Structurally cyclical, not two static branches meeting at the bottom.

Doubt about a single broker's adequacy — no idea if enough people are
seeing the listing, not knowing what the broker is doing to market it,
unable to tell which marketing efforts work — is itself what drives
Seller toward appointing more than one broker "to cover bases." That
same action is also directly motivated by the need for exposure. Once
multiple brokers are involved, a consequence cluster follows: inability
to tell how much effort any one broker is making or who is genuinely
representing Seller; inconsistent pricing advice and doubt about
whether feedback is genuine; and an operational burden — repeating
information to different parties, communication overload, inability
to filter serious buyers from casual enquiries. These converge on
Seller losing any single, consolidated view of the sale — unable to
estimate time to sell or measure progress. The original exposure doubt
also feeds the Cloud directly: it persists whether Seller appoints one
broker or many.

**Flagged, not resolved into the Cloud:** two UDEs (documentation being
time-consuming, and uncertainty whether it will satisfy buyers) did
not trace into this causal chain on inspection. They are tentatively
attributed to SR003 (transactions are trust-mediated) rather than a
resolvable behavioral pattern — flagged for verification against real
seller input, not asserted as settled.

**Cloud:** see CLOUDS.md.

---

# Buyer CRT

Two branches, both converging on the Cloud. All 20 active Buyer UDEs
were placed; unlike Seller, none required flagging as SR-linked.

**Branch 1 (broad search):** Buyer searches across many uncoordinated
sources, loses history/preferences switching platforms, and sees
listings ranked by payment rather than fit. Checking many separate
places means some of what's seen is stale or a poor match — leading to
messaging about properties already sold, and missing properties that
would have been a fit. This converges on Buyer doing all the work of
finding, checking, and comparing everything personally — time-consuming,
repetitive search, DIY spreadsheets, and difficulty comparing properties
side by side.

**Branch 2 (trust one source):** because different sources tell Buyer
different things, no single one can be trusted outright — inconsistent
listings, no way to verify claims, inability to tell who's trustworthy.
This produces a pattern of double-checking everything and feeling that
everyone else (broker, seller) already knows more. Buyer ends up
repeating requirements to every new broker — and this absence of one
consistent guide extends into the transaction itself: conflicting
advice from brokers, banks, and agents; inability to tell if a price is
fair; delays coordinating multiple independent parties; repeated forms
and documents; financing options staying unclear until late; loan
eligibility uncertainty; and no visibility into where a transaction
actually stands.

**Cloud:** see CLOUDS.md.

---

# Ecosystem CRT

Assembled, not constructed — each stakeholder appears as a reference
to its own frozen CRT, not redrawn. The central finding: Broker's
dominant structural cause (trust, effort, and market knowledge existing
only in personal memory, unobservable outside that relationship) is
what *produces* both Seller's and Buyer's own Clouds in the first
place (via the Broker↔Seller and Broker↔Buyer interaction findings,
below) — and is then independently *reinforced* by three separate
mechanisms. This is the basis for the Ecosystem Constraint (stated as
an observed failure: qualified supply and demand exist across all
three stakeholders, yet the ecosystem does not reliably convert this
into qualified opportunities) and the Ecosystem Cloud (full 5-box
form — see CCC.md).

---

# Cross-Stakeholder Investigations

| Pair | Type | Finding |
|---|---|---|
| Broker↔Broker | Intra-stakeholder | **One closed reinforcing loop.** Not a new Cloud — the same Broker Cloud reinforcing itself across the population. Two exit points (missed co-broking, duplicate effort) are both explicitly about other brokers in their own wording. |
| Buyer↔Buyer | Intra-stakeholder | **No loop.** No Buyer UDE references or implies awareness of another buyer. Recurrence only — the same Cloud repeats identically per instance, with no evidenced mechanism connecting instances. |
| Seller↔Seller | Intra-stakeholder | **Not yet investigated.** See Not Yet Investigated. |
| Broker↔Seller | Inter-stakeholder | **One closed loop**, three minimal cross-links: Broker's portal-dependent visibility → Seller's exposure doubt; Broker's siloed knowledge → Seller's inability to verify effort/pricing advice; Seller's multi-broker hedge → Broker's duplicate effort, closing the loop. |
| Broker↔Buyer | Inter-stakeholder | **One closed loop**, five minimal cross-links, structurally analogous to Broker↔Seller. Broker's U028 was originally worded as a claim about buyer psychology ("buyers trust the portal's name more than mine") and flagged as an evidence gap; on review, restated as a pure discoverability observation, and the gap resolved — it was already independently confirmed by the existing Broker U021/U022 → Buyer U012 link, not missing evidence. |
| Seller↔Buyer | Direct interaction | **One-directional, non-driving.** Buyer's search volume produces Seller's communication overload; no return path found, no new Cloud, confirmed complete. |

---

# Empty and Checked-Not-Linked Findings

Findings recorded as an explicit absence, not a gap left unchecked:

- **Buyer↔Buyer produced no loop.** This is a genuine result, not an
  incomplete investigation — every Buyer UDE was checked against every
  other for a cross-instance reference, and none exists.
- **Seller's pricing struggle and Buyer's fair-price doubt look like a
  mirror pair but are not linked.** Checked and found to be two
  independent symptoms of the same already-diagnosed root (Broker's
  siloed knowledge) rather than one causing the other — positing direct
  causation would have added an unevidenced hop where a shared cause
  already explains both sides.
- **Two Buyer UDEs partially attribute to SR003, not a stakeholder
  interaction.** Both name "seller" explicitly but have no anchoring
  Seller UDE — an owner inherently knowing more about their own
  property than an outside buyer is treated as a structural fact of
  the domain, not a fixable interaction.

---

# Why the Investigation Converges on One Constraint, Not Three

Three independent reinforcing loops were found — Broker↔Broker,
Broker↔Seller, and Broker↔Buyer — not one. What makes this "one
constraint" rather than three is that **all three close back onto the
exact same dominant structural cause.** This was checked explicitly,
not assumed: every UDE not part of one of these loops was traced and
confirmed either self-contained within its own stakeholder's CRT, or
already accounted for by a different loop. Broker's duplicate-effort
UDE, notably, is fed by *both* the Seller-side and Buyer-side loops
simultaneously — a genuine convergence point, not a double-count. Three
separate mechanisms reinforcing one shared root is a stronger and more
parsimonious finding than three independent ecosystem-level problems
would have been, and is the basis for the Ecosystem CRT treating this
as a single Constraint rather than modeling three parallel ones.

---

# Not Yet Investigated

- **Seller↔Seller intra-stakeholder.** Requested and completed for
  Broker and Buyer; never requested or performed for Seller. This is a
  real gap, not a documentation omission.
- **All pairs involving Developer, Bank / Mortgage Provider, Insurance,
  Legal / Compliance, Interior Designer / Architect, and Property
  Portal.** No CRT, Cloud, or interaction investigation exists for any
  of these six stakeholders.

---

# Boundary Held Throughout

No Injection, Negative Branch Reservation, Future Reality Tree, or
product/architecture reasoning was performed as part of building any
CRT, Cloud, or interaction finding documented above. That work begins
in FRT.md (Not Started).
