# Value-Directed Systems (VDS) — Core Invariants

Status: FOUNDATIONAL  
Intent: Conceptual Lock-In (Not Implementation)  
Scope: Any system that claims to operate as a Value-Directed System  

This document defines the **non-negotiable requirements** of a Value-Directed System (VDS).

These invariants describe what must always be true regardless of implementation,
architecture, scale, or tooling.

They exist to preserve **care, legitimacy, and human ownership** while allowing
systems to change deliberately without losing their reason for doing so.

---

## I. Value Must Be Explicit or the System Is Silent

A VDS MUST NOT act, suggest, or escalate in the name of “value” unless that value is explicitly declared.

- All value claims MUST originate from explicit decisions, goals, or commitments.
- Metrics, telemetry, and trends are inputs — never substitutes for value.
- If no value declarations exist, the VDS MUST remain observational only.

Fail if:
- The system implies importance, urgency, or correctness without a declared value.
- Value is inferred from optimization targets or historical behavior.

---

## II. Decisions Are Always Externally Owned

A VDS never owns decisions.

- Decisions originate from humans or accountable external systems.
- A VDS may observe, evaluate, summarize, and report.
- A VDS MUST NOT infer intent, reinterpret decisions, or upgrade signals into authority.

Fail if:
- Advisory signals are treated as commitments.
- Correlation, trends, or outcomes are interpreted as consent.

---

## III. Advisory First, Commitment Always Explicit

A VDS operates strictly as an advisory and caregiving layer.

- Observation precedes guidance.
- Guidance precedes experiments or treatment plans.
- Experiments precede commitment.
- Commitment is explicit, auditable, and external to the VDS.

A VDS never executes change.

Fail if:
- Advice and action collapse into a single step.
- Changes occur without a clear, explicit moment of commitment.

---

## IV. No Silent Optimization or Continuous Drift

A VDS MUST NOT silently optimize systems toward a goal.

- Any change in behavior MUST be attributable to an explicit decision.
- Continuous “always improving” loops are forbidden.
- Stability is the default state; change is deliberate.

Fail if:
- System behavior drifts without recorded intent.
- Optimization hides accountability or decision boundaries.

---

## V. Evaluation and Commitment Are Strictly Separated

A VDS distinguishes clearly between:

- **Evaluation:** What is being observed or measured
- **Commitment:** What has been consciously accepted or changed

Evaluation may be continuous.  
Commitment must be discrete, rare, and explicit.

Fail if:
- Observations are treated as de facto decisions.
- Reporting pressure substitutes for commitment.

---

## VI. Caretaking Is Contextual and Local

A VDS caretakes systems within a defined scope or identity.

- Health is assessed relative to declared goals and constraints.
- Metrics are contextual, not universal.
- Local systems are never judged against global norms by default.

Fail if:
- Systems are penalized for behaving correctly within their own context.
- Signals are propagated without preserving local meaning.

---

## VII. Telemetry Is Forgettable; Decisions Are Not

A VDS may summarize, age out, or discard raw telemetry.

- Telemetry exists to support care, not permanence.
- Decisions, commitments, and escalations MUST remain auditable.
- Long-term legitimacy does not depend on raw operational detail.

Fail if:
- Telemetry is treated as historical truth.
- Forgetting metrics is framed as loss of legitimacy.

---

## VIII. Experiments and Treatment Plans Are Descriptive, Not Executable

A VDS may record and track:

- **Treatment plans** (adjustments to how value is measured or interpreted)
- **Experiments** (time-bound observation periods around anticipated change)

A VDS never executes experiments or enforces plans.

Fail if:
- Experiments resemble deployments.
- The VDS becomes an execution coordinator.

---

## IX. Escalation Is Signal-Based and Upward Only

A VDS may escalate **signals**, never commands.

- Misalignment, persistent degradation, or unmet goals may be escalated.
- Silence is a valid and meaningful state.
- Escalation does not imply fault, urgency, or required action.

Fail if:
- Escalation pressures humans into action.
- Authority is implied across boundaries.

---

## X. Observation Is Never Judgment

A VDS describes conditions without assigning blame, intent, or correctness.

- Unexpected outcomes are signals, not failures.
- Language must preserve dignity and psychological safety.
- Care language is used for health; alignment language is used for intent.

Fail if:
- Reporting implies negligence or fault.
- Optimization language replaces care language.

---

## XI. History Is Additive, Not Rewritten

A VDS preserves meaning through accumulation.

- Past decisions are never reinterpreted.
- Corrections create new decisions.
- Learning occurs by addition, not erasure.

Fail if:
- History is edited to appear coherent after the fact.
- Outcomes obscure originating intent.

---

## XII. If Value Is Unclear, the System Must Slow Down

When value, intent, or scope is unclear:

- The VDS must reduce guidance.
- The VDS must favor observation over recommendation.
- The VDS must request clarification, not infer direction.

Fail if:
- The system creates urgency under uncertainty.
- Action is encouraged to resolve ambiguity.

---

## Closing Statement

A Value-Directed System exists to **care for declared value**, not to replace judgment or authority.

When uncertainty is high, it must slow down.  
When impact is high, it must be careful.  
When value is unclear, it must remain silent.

Clarity is success.  
Restraint is correctness.  
Ownership is legitimacy.