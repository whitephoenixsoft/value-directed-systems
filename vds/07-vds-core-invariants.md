# Value-Directed Systems (VDS) — Core Invariants

Status: FOUNDATIONAL  
Intent: Conceptual Lock-In (Not Implementation)  
Scope: Any system that claims to operate as a Value-Directed System  

This document defines the **non-negotiable invariants** of a Value-Directed System (VDS).

These invariants describe what must always be true, regardless of implementation,
architecture, scale, or tooling.

They exist to preserve **care, legitimacy, and human ownership** while allowing
systems to change deliberately without losing their reason for doing so.

---

## I. Value Must Be Explicit or the System Is Silent

A VDS MUST NOT act, suggest, prioritize, or escalate in the name of “value” unless that value is explicitly declared.

- All value originates from explicit decisions, goals, or commitments.
- Metrics, telemetry, and trends are inputs — never substitutes for value.
- In the absence of declared value, the VDS MUST remain observational only.

Fail if:
- The system implies importance, urgency, or correctness without a declared value.
- Value is inferred from optimization targets, historical behavior, or norms.

---

## II. Decisions Are Always Externally Owned

A VDS never owns decisions.

- Decisions originate from humans or accountable external systems.
- A VDS may observe, evaluate, summarize, and report.
- A VDS MUST NOT infer intent, reinterpret decisions, or elevate signals into authority.

Fail if:
- Advisory output is treated as commitment.
- Correlation, trends, or outcomes are interpreted as consent.

---

## III. Advisory First; Commitment Is Always Explicit

A VDS operates strictly as an advisory and caregiving layer.

- Observation precedes guidance.
- Guidance precedes experimentation or treatment planning.
- Experiments precede commitment.
- Commitment is explicit, auditable, and external to the VDS.

A VDS never executes change.

Fail if:
- Advice and action collapse into a single step.
- Changes occur without a clear, explicit moment of commitment.

---

## IV. No Silent Optimization or Continuous Drift

A VDS MUST NOT silently optimize systems toward a goal.

- Any behavioral change MUST be attributable to an explicit decision.
- Continuous “always improving” loops are forbidden.
- Stability is the default state; change is deliberate.

Fail if:
- System behavior drifts without recorded intent.
- Optimization obscures accountability or decision boundaries.

---

## V. Evaluation and Commitment Are Strictly Separated

A VDS maintains a hard boundary between:

- **Evaluation:** What is being observed or measured
- **Commitment:** What has been consciously accepted or changed

Evaluation may be continuous.  
Commitment must be discrete, rare, and explicit.

Fail if:
- Observations are treated as de facto decisions.
- Reporting pressure substitutes for commitment.

---

## VI. Caretaking Is Contextual and Scoped

A VDS caretakes systems within a defined identity and scope.

- Health is assessed relative to declared goals and constraints.
- Metrics are contextual, not universal.
- Systems are not judged against global norms by default.

Fail if:
- Systems are penalized for behaving correctly within their own context.
- Signals propagate without preserving local meaning.

---

## VII. Telemetry Is Forgettable; Decisions Are Not

A VDS may summarize, age out, or discard raw telemetry.

- Telemetry exists to support care, not permanence.
- Decisions, commitments, escalations, and declared intent MUST remain auditable.
- Long-term legitimacy does not depend on raw operational detail.

Fail if:
- Telemetry is treated as historical truth.
- Forgetting metrics is framed as loss of legitimacy.

---

## VIII. Experiments and Treatment Plans Are Descriptive, Not Executable

A VDS may record and track:

- **Treatment plans:** changes to how value is interpreted or monitored
- **Experiments:** time-bound observation windows around anticipated change

A VDS never executes experiments or enforces plans.

Fail if:
- Experiments resemble deployments.
- The VDS becomes an execution coordinator.

---

## IX. Escalation Is Signal-Based and Non-Coercive

A VDS may escalate **signals**, never commands.

- Persistent misalignment, degradation, or unmet commitments may be surfaced.
- Silence is a valid and meaningful state.
- Escalation never implies fault, urgency, or required action.

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
- Reporting implies negligence, fault, or moral judgment.
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

## XII. When Value Is Unclear, the System Must Slow Down

When value, intent, or scope is unclear:

- Guidance must be reduced.
- Observation must be favored over recommendation.
- Clarification must be requested, not inferred.

Fail if:
- Urgency is created under uncertainty.
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