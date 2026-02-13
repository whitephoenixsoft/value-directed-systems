# VDS / VLS Layer Model

This document defines the foundational layers used in Value-Directed Systems (VDS), Value Lineage Systems (VLS), and the Commit-Legitimacy layer (Charter).

Its purpose is to prevent category errors, authority creep, and conceptual collapse by making boundaries explicit.

These layers are complementary but **not interchangeable**.

---

## Overview of Layers

There are three primary structural layers:

1. Commit-Legitimacy Layer (Charter / Decision Ledger)  
2. Value-Directed System (VDS) Layer  
3. Value Lineage System (VLS) Layer  

Deployment windows and instability posture are **cross-layer contextual protocols**, not independent layers.

Each layer has a distinct role, responsibility, and limitation.

---

## 1. Commit-Legitimacy Layer (Charter)

**Purpose:**  
To record explicit commitments and establish legitimacy.

This layer is commit-centric and append-only.

**What it observes:**
- Proposals
- Acceptances and rejections
- Authority declarations
- Scope declarations
- Context and session boundaries

**What it records:**
- Immutable commits
- Rationale and annotations
- Authority and scope validation
- Baseline reviews
- Temporal ordering of legitimacy events

**What it may do:**
- Validate authority and scope
- Preserve irreversible history
- Prove legitimacy mechanically
- Import and export commits

**What it may never do:**
- Observe system behavior
- Interpret alignment
- Evaluate outcomes
- Merge meaning
- Escalate urgency

This layer answers:  
**“What was explicitly committed, by whom, and under what authority?”**

Legitimacy is local and append-only.  
Interpretation happens elsewhere.

---

## 2. Value-Directed System (VDS) Layer

**Purpose:**  
To provide structural care by observing behavior relative to declared decisions.

VDS is a caregiving layer.

**What it observes:**
- System behavior
- Telemetry and signals
- Conditions relative to declared decisions
- Stability, drift, and degradation

**What it records:**
- Alignment and misalignment signals
- Check-ins
- Supportability degradation
- Experiment context
- Measurement adjustments

**What it may do:**
- Report observations neutrally
- Surface divergence relative to decisions
- Aggregate check-ins during instability
- Suggest experiments or deployment context
- Adjust interpretive posture during declared deployment windows

**What it may never do:**
- Make or approve decisions
- Modify identity
- Derive version numbers
- Enforce behavior
- Diagnose root cause
- Convert visibility into obligation

VDS does not declare work deprecated.  
It reflects behavioral alignment relative to intent.

This layer answers:  
**“How is the system behaving relative to what was committed?”**

Care is descriptive, not prescriptive.

---

## 3. Value Lineage System (VLS) Layer

**Purpose:**  
To preserve identity, structural continuity, and versioned intent over time.

VLS is a lineage layer.

**What it observes:**
- Declared identity
- Declared purpose
- Scope boundaries
- Structural changes to responsibility
- Version evolution
- Deprecation and abandonment states

**What it records:**
- Identity versions
- Mechanical version increments
- Identity coexistence
- Sunset declarations
- Lineage continuity
- Structural conflicts between declared intents

**What it may do:**
- Derive version increments mechanically
- Represent identity evolution
- Track deprecated alignment states
- Declare lifecycle transitions (e.g., Sunset)
- Preserve cross-version continuity

**What it may never do:**
- Observe system health
- Interpret telemetry
- Issue caregiving check-ins
- Escalate urgency
- Enforce alignment
- Modify decisions

Version numbers are mechanically derived from structural identity changes.  
Manual version mutation is prohibited after initialization.

This layer answers:  
**“Who are we structurally, how has that evolved, and what has changed in our declared intent?”**

VLS governs identity continuity — not performance.

---

## Deployment & Instability Protocol (Cross-Layer Context)

Deployment windows and instability posture:

- Do not form a separate authority layer
- Do not alter legitimacy
- Do not mutate identity
- Do not suppress observation

They modify **interpretive posture**, not structural truth.

Deployment windows primarily affect VDS interpretive sensitivity.  
Identity sunset and coexistence are governed by VLS.  
Legitimacy remains governed by the Commit-Legitimacy layer.

---

## Core Boundary Rules

No layer may assume the responsibilities of another.

- The Commit-Legitimacy layer does not observe behavior.  
- VDS does not create legitimacy or mutate identity.  
- VLS does not observe runtime behavior or intervene operationally.  
- Deployment posture does not alter legitimacy or lineage.  
- No layer may collapse or rewrite version history.  

Each layer preserves a different dimension of truth:

- **Legitimacy** (what was committed)  
- **Care** (how behavior relates to commitment)  
- **Lineage** (who the system declares itself to be over time)

Together, these layers preserve value, agency, and structural clarity without coercion.