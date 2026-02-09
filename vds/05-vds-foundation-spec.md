# Value-Directed Systems (VDS) — Foundation Specification (Revised)

Status: FOUNDATIONAL  
Depends On: VDS Core Invariants  
Does Not Define: software architecture, APIs, storage, execution, automation, AI, or vendors  

This document defines how a **Value-Directed System behaves in practice**.

It translates VDS invariants into a behavioral contract while remaining
strictly implementation-agnostic.

This is not a how-to.  
It is not an operating manual.  
It is a **constraint on behavior**.

---

## 1. What a Value-Directed System Is

A Value-Directed System (VDS) is a **caregiving system** that exists to preserve
alignment between **observed conditions** and **explicitly declared decisions**.

A VDS:

- Observes behavior within a defined identity or area
- Interprets observations only relative to explicit decisions
- Issues **check-ins** that describe alignment, drift, or capacity change
- Preserves intent, ownership, and historical explainability
- Escalates visibility without enforcing action
- Supports deliberate change without executing it

A VDS does not:
- act on systems  
- optimize outcomes  
- decide on behalf of humans  

A VDS helps systems:
- change **on purpose**
- pause **on purpose**
- remain stable **on purpose**

---

## 2. Decisions as the Source of Meaning

All meaning within a VDS originates from **explicit decisions** recorded elsewhere
(e.g., a decision ledger or Charter).

A decision defines:
- what matters
- within what scope or area
- under what assumptions
- with what bounds or tolerances
- with what acknowledged importance or risk

Decisions are not controls or policies.  
They are **commitments** that make observation interpretable.

Without explicit decisions:
- metrics have no meaning
- check-ins have no reference
- escalation has no legitimacy

In the absence of decisions, a VDS may observe — but it may not interpret.

---

## 3. Identity, Area, and Caregiving Boundaries

A VDS operates within a **defined identity**, composed of one or more **areas**.

- An identity is a bounded domain of responsibility
- Each identity has one declared purpose at a time
- Areas represent coherent decision domains within that identity
- Scope changes constitute identity evolution and must be explicit

A VDS provides caregiving **within** identity boundaries.

It does not:
- redefine identity
- assume authority
- collapse boundaries

---

## 4. Observation as the Default State

When decisions exist, a VDS operates in **caregiving mode** by default.

In this mode, the VDS:
- observes behavior relevant to declared decisions
- contextualizes telemetry relative to assumptions and bounds
- notices stability, drift, stress responses, and degradation
- prepares **check-ins** as descriptive artifacts

Observation:
- never changes system behavior
- never implies fault or urgency
- never creates obligation

This mirrors clinical monitoring — not control systems.

---

## 5. Check-Ins (Caregiving Artifacts)

A **check-in** is the primary output of a VDS.

A check-in:
- describes observed conditions
- references affected decisions or areas
- uses neutral, non-judgmental language
- may include optional rationale or annotations
- does not prescribe action

Examples of check-in states may include:
- intent unchanged
- capacity reduced
- paused intentionally
- observations inconclusive
- reassessment requested

Check-ins communicate care, not performance.

---

## 6. Telemetry and Forgetting

Telemetry exists to support caregiving, not permanence.

- Raw telemetry may be summarized, aged out, or discarded
- Long-term legitimacy does not depend on raw data retention
- Decisions, check-ins, experiments, and commitments are preserved

A VDS remembers **why things mattered**, not every operational detail.

Forgetting telemetry is not loss of meaning.

---

## 7. Requests (Invitations to Deliberate)

When caregiving alone cannot restore clarity, a VDS may issue a **request**.

A request:
- invites deliberation
- asks for clarification, reassessment, or decision update
- carries no authority
- carries no deadline
- carries no enforcement

Requests exist to surface gaps — not to compel response.

---

## 8. Experiments (Anticipated Change Context)

An **experiment** marks a period of heightened observation due to anticipated change.

Experiments are used when:
- behavior is expected to change
- a decision may have uncertain impact
- temporary instability is acceptable

Experiments:
- do not authorize change
- do not execute change
- contextualize observations
- end explicitly

Experiments change **how we observe**, not **what we decide**.

---

## 9. Measurement Adjustments (Formerly Treatment Plans)

A measurement adjustment is a deliberate refinement to interpretation.

It may include:
- redefining signals
- adjusting bounds or tolerances
- correcting assumptions
- improving signal fidelity

Measurement adjustments:
- affect interpretation only
- never modify system behavior
- are explicitly recorded
- do not imply action

They exist to preserve interpretability and legitimacy.

---

## 10. Commitment and Irreversibility

Commitments are made **outside** the VDS.

When commitments occur:
- they are recorded with rationale and context
- irreversibility or elevated impact is noted
- history becomes part of lineage

A VDS may observe commitments.  
It may never create them.

---

## 11. Federation and Visibility

A VDS may participate in federation across identities or areas.

Federation:
- aggregates check-ins
- preserves local context
- increases visibility without pressure
- supports reflection across boundaries

Federation never:
- propagates raw telemetry
- enforces alignment
- synchronizes authority
- collapses local agency

Intent may be shared.  
Authority never is.

---

## 12. Relationship to Value Lineage Systems (VLS)

VDS and VLS are complementary but asymmetric.

- VDS cares for behavior relative to decisions
- VLS preserves identity, intent, and lineage over time

A VDS may:
- escalate persistent drift or deprecation signals to VLS
- request identity clarification when caregiving is no longer sufficient

A VLS:
- does not observe behavior
- does not issue check-ins
- does not intervene

This separation prevents coercion and preserves legitimacy.

---

## 13. Silence as a Valid Outcome

If:
- decisions exist
- conditions remain aligned
- no experiments or requests are active

Then the VDS remains silent.

Silence indicates:
- stability
- sufficient care
- no new information requiring attention

Noise without need is a failure mode.

---

## Closing Perspective

A Value-Directed System behaves less like an optimizer
and more like a careful professional:

- observant
- explicit
- context-aware
- restrained
- honest about limits

Its success is not measured by speed or throughput,
but by **trust, legitimacy, and sustained alignment over time**.