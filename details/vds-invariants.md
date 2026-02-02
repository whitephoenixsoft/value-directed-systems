# Value-Directed Systems (VDS) — Core Invariants
Status: DRAFT (Preservation)
Intent: Conceptual Lock-In, Not Implementation
Scope: Any system that claims to operate as a Value-Directed System

This document defines the non-negotiable invariants of a Value-Directed System (VDS).
These invariants describe what must always be true, regardless of implementation,
architecture, scale, or tooling.

They exist to preserve human intent, system dignity, and defensible behavior over time.

---

## I. Value Is Explicit or It Does Not Exist

A system MUST NOT act in the name of “value” unless that value is explicitly declared.

- All value claims MUST be represented as explicit, inspectable decisions.
- Implicit goals, inferred optimization targets, or silent heuristics are forbidden.
- If no value declarations exist, the system MUST remain observational only.

Fail if:
- The system optimizes behavior without a declared value reference.
- Value is inferred from metrics alone.

---

## II. Decisions Are Human-Owned, Not System-Inferred

All value-defining decisions MUST originate from explicit human commitment.

- Systems may evaluate, observe, measure, and report.
- Systems MUST NOT decide what matters.
- Systems MUST NOT reinterpret human intent after the fact.

Fail if:
- The system upgrades advisory signals into action without authorization.
- The system treats correlation or trend as consent.

---

## III. Advisory First, Action Second, Commitment Always Explicit

A Value-Directed System is advisory by default.

- Observation precedes intervention.
- Suggestions precede experiments.
- Experiments precede commitment.
- Commitment is explicit, auditable, and rare.

Fail if:
- The system applies changes without a clear escalation path.
- The system collapses advice and action into a single step.

---

## IV. No Silent Optimization

The system MUST NOT continuously or silently optimize toward a goal.

- All adjustments MUST be bounded, rate-limited, and observable.
- Any behavior that changes system state MUST be attributable to a declared decision.
- “Always improving” loops without checkpoints are forbidden.

Fail if:
- The system drifts behavior over time without recorded intent.
- Optimization obscures accountability.

---

## V. One Decision, One Domain of Effect (Initial Constraint)

At any given time, a single decision MUST dominate a given domain of effect.

- Conflicting decisions MUST NOT be applied simultaneously.
- Resolution of conflicts is a human responsibility.
- This invariant may be relaxed only by explicit future revision.

Fail if:
- Multiple value rules compete over the same control surface.
- The system arbitrates value conflicts implicitly.

---

## VI. Systems Are Treated as Individuals, Not Clones

Each managed system instance MUST be observed and evaluated in its own context.

- Metrics are contextual, not universal.
- Health is relative to declared goals, not global norms.
- Federation MUST preserve individuality before aggregation.

Fail if:
- Decisions are blindly propagated without local observation.
- A system is penalized for behaving correctly in its own context.

---

## VII. Irreversibility Must Be Declared and Respected

Some decisions carry irreversible or high-cost consequences.

- Irreversibility MUST be explicitly marked.
- The system MUST respond with increased caution and reduced automation.
- Higher criticality implies slower change, not faster.

Fail if:
- High-impact changes are treated as routine.
- The system applies force where care is required.

---

## VIII. Experiments Are Limited, Isolated, and Non-Simultaneous

The system MUST limit experimentation by default.

- Experiments MUST be small, staged, and reversible where possible.
- Experiments MUST NOT be applied everywhere at once.
- Observation-only mode is the default state.

Fail if:
- Experiments resemble deployments.
- Learning is achieved by broad disruption.

---

## IX. Observation Is Not Judgment

Observations describe reality; they do not assign blame or intent.

- The system MUST report conditions neutrally.
- Unexpected outcomes are signals, not failures.
- Language and reporting MUST preserve psychological safety.

Fail if:
- Reporting implies fault, negligence, or correctness.
- The system pressures humans into action.

---

## X. History Is Preserved, Not Rewritten

All decisions, observations, experiments, and outcomes MUST remain auditable.

- Past intent is never reinterpreted.
- Corrections create new decisions, not revisions of history.
- Learning accrues by accumulation, not erasure.

Fail if:
- The system rewrites prior meaning.
- Outcomes obscure their originating decisions.

---

## XI. If No Decisions Exist, the System Is Silent

In the absence of declared value decisions:

- The system MUST observe only.
- The system MUST NOT suggest optimization.
- The system MUST NOT imply that something is wrong.

Fail if:
- The system creates urgency without mandate.
- The system pressures humans to define value prematurely.

---

## Closing Statement

A Value-Directed System exists to serve declared human values,
not to replace them.

When uncertainty is high, it must slow down.
When impact is high, it must be careful.
When value is unclear, it must remain silent.

Clarity is success.
Restraint is correctness.
Ownership is legitimacy.