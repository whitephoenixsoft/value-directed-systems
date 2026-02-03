# Caregiving & Alignment Vocabulary — Guidance Layer Draft
## Vocabulary and Usage Guide (Draft)

This document captures the current shared understanding of system behavior, modes, and language usage.  
It is intended as a handoff reference for collaborators while preserving the original design intent.

---

## 1. Process Map

### A. Two Mutually Exclusive Modes

At any given decision scope, the system operates in exactly one mode.

#### 1. Caregiving Mode
- Intent is accepted as valid
- Goals are stable
- The system provides care, observation, and reporting
- No redefinition of purpose occurs in this mode

#### 2. Alignment Mode
- Intent is under review or changing
- Goals may be revised
- The system supports learning, coordination, and deliberate change
- Stability is secondary to clarity and legitimacy

**Invariant:**  
A decision scope may never be in both Caregiving Mode and Alignment Mode simultaneously.

---

### B. Mode Responsibilities

#### Caregiving Mode Responsibilities
- Monitor signals relevant to declared goals
- Detect divergence from declared bounds
- Record and report observations without blame
- Express urgency only as defined by the decision itself
- Suggest reconsideration when goals appear improbable under stated constraints
- Preserve dignity and psychological safety

#### Alignment Mode Responsibilities
- Support explicit changes to decisions and intent
- Allow experimentation with strict limits
- Enforce one-decision-at-a-time experimentation per scope
- Limit system-wide concurrent experiments
- Preserve interpretability and learning
- Provide intent-level signals to federation
- Coordinate meaning, not behavior

---

### C. Federation Boundary

- Federation receives alignment signals, not raw health telemetry
- Clinical (caregiving) data remains local and contextual
- Intent may propagate across systems
- Authority does not propagate

---

## 2. Vocabulary by Mode and Situation

Language is treated as a first-class design concern.  
Vocabulary selection determines whether systems heal, learn, or harden.

---

## A. Clinical / Caregiving Vocabulary (Ray 2)

**Used when:**  
Caring for an existing goal, system, or component.

**Tone:**  
Observational, non-judgmental, dignity-preserving.

### Divergence
Use when observed behavior differs from declared bounds.

Example:  
“Observed divergence from the target latency range over the past 12 hours.”

---

### Decompensation
Use when a system can no longer maintain stability under current conditions.

Example:  
“The service experienced decompensation under sustained load.”

---

### Stress Response
Use when behavior changes under pressure but may be adaptive.

Example:  
“This pattern appears to be a stress response rather than a defect.”

---

### Trend
Use when change is gradual and time-based.

Example:  
“We are seeing a gradual trend toward increased error rates.”

---

### Stability / Instability
Use to describe overall health relative to declared tolerances.

Example:  
“The subsystem remains stable within declared bounds.”

---

### Care Recommendation
Use to suggest supportive action without obligation.

Example:  
“Additional monitoring may be beneficial given recent variance.”

---

### Impact on Goal
Use to explain why a clinical signal matters.

Example:  
“This instability may affect the system’s ability to meet the reliability goal.”

**Rule:**  
Health describes impact on goals, not purpose itself.

---

## B. Team / Alignment Vocabulary (Ray 9)

**Used when:**  
Intent, goals, or meaning are under review or being coordinated.

**Tone:**  
Collaborative, reflective, responsibility-sharing.

---

### Alignment
Use when intent and behavior support each other.

Example:  
“The system appears aligned with the declared objective.”

---

### Misalignment
Use when behavior and intent no longer support each other.

Example:  
“There is a misalignment between current behavior and the stated goal.”

---

### Purpose Drift
Use when intent erodes gradually over time.

Example:  
“We may be experiencing purpose drift as requirements evolve.”

---

### Unmet Assumption
Use when a decision relied on conditions that no longer hold.

Example:  
“An underlying assumption about traffic patterns appears unmet.”

---

### Experiment
Use for time-bound, limited tests intended to learn.

Example:  
“We propose a limited experiment to evaluate an alternative approach.”

---

### Commitment
Use when a change becomes durable and updates intent.

Example:  
“This change represents a commitment and updates the system’s declared intent.”

---

### Coordination
Use when multiple parts must move together.

Example:  
“This change requires coordination across services to preserve intent.”

---

### Alignment Signal (Federation)
Use when sharing intent-level information externally.

Example:  
“We are currently prioritizing reliability over throughput.”

**Not Shared:**  
Clinical details, raw health metrics, or enforcement rules.

---

## C. Language Boundary Rule

A guiding principle for collaborators:

**If we are caring for an existing goal, we speak clinically.  
If we are deciding or revising a goal, we speak collaboratively.**

If interactions feel coercive, judgmental, or optimizing by default, the wrong vocabulary is being used.

---

## Closing Perspective

This vocabulary is not cosmetic.

It is a structural mechanism that:
- Prevents silent authority
- Preserves dignity and agency
- Enables learning without coercion
- Sustains trust over time

Correct language shapes system behavior as much as code or policy.