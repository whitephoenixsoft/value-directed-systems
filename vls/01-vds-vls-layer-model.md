# VDS / VLS Layer Model

This document defines the foundational layers used in Value-Directed Systems (VDS) and Value Lineage Systems (VLS).  
Its purpose is to prevent category errors, authority creep, and conceptual collapse by making boundaries explicit.

These layers are complementary but **not interchangeable**.

---

## Overview of Layers

There are three primary layers:

1. Decision Ledger Layer  
2. Value-Directed System (VDS) Layer  
3. Value Lineage System (VLS) Layer  

Each layer has a distinct role, responsibility, and limitation.

---

## 1. Decision Ledger Layer

**Purpose:**  
To record explicit decisions, commitments, and legitimacy.

**What it observes:**  
- Human or system decisions
- Proposals, acceptances, rejections
- Authority, scope, and context

**What it records:**  
- Immutable decision records
- Rationale and annotations
- Temporal ordering of commitments

**What it may do:**  
- Validate authority and scope
- Preserve irreversible history
- Act as a source of truth for decisions

**What it may never do:**  
- Observe system behavior
- Evaluate outcomes or health
- Interpret value or alignment
- Suggest changes

This layer answers:  
“What was decided, by whom, and under what authority?”

---

## 2. Value-Directed System (VDS) Layer

**Purpose:**  
To care for systems by observing behavior relative to declared decisions and goals.

**What it observes:**  
- System behavior
- Telemetry and signals
- Outcomes relative to declared values

**What it records:**  
- Alignment and misalignment
- Stability, drift, and trends
- Deprecated or at-risk value contributions

**What it may do:**  
- Report observations with care
- Surface divergence and risk
- Request decision updates
- Request treatment plans or experiments
- Propagate alignment signals

**What it may never do:**  
- Make decisions
- Enforce behavior
- Change systems directly
- Assume intent or correctness

This layer answers:  
“How is the system behaving relative to what was decided?”

---

## 3. Value Lineage System (VLS) Layer

**Purpose:**  
To preserve identity, continuity, and coherence of intent over time.

**What it observes:**  
- Decisions and declared intent
- Identity evolution
- Deprecation, abandonment, and transition

**What it records:**  
- Value lineage and history
- Identity states and scope changes
- Conflicts and coherence signals

**What it may do:**  
- Represent continuity across time
- Surface identity drift
- Track deprecated or abandoned work
- Enable legitimacy through memory

**What it may never do:**  
- Observe system health
- Recommend actions
- Escalate urgency
- Enforce alignment

This layer answers:  
“Who are we, how did we get here, and what has changed in our intent?”

---

## Core Boundary Rule

No layer may assume the responsibilities of another.

- Decision ledgers do not observe behavior  
- VDS does not create legitimacy  
- VLS does not intervene or advise  

Together, these layers preserve value, care, and agency without coercion.