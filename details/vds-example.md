Example: Value-Directed Cloud Pricing Management
Observation, Intent, and Care Over Optimization

Purpose of This Example
This document demonstrates how a value-directed system behaves
when applied to a real, failure-prone domain: cloud pricing.

The goal is not to minimize cost.
The goal is to preserve declared cost intent over time,
despite variability, seasonality, and operational noise.

This example is illustrative.
It does not prescribe tooling, automation levels, or architecture.

Problem Statement
Cloud pricing decisions fail because:

- cost is contextual, not absolute
- acceptable behavior changes over time
- feedback is delayed and noisy
- humans are punished for being cautious or explicit

Most systems respond by:

- encoding brittle rules
- over-optimizing for short-term metrics
- reacting too late or too aggressively
- forcing architectural rewrites after trust is lost

A value-directed approach treats pricing as a long-lived decision space,
not a continuous optimization problem.

Declared Intent (Human-Owned)
A value-directed system begins with explicit intent.

Example intents may include:

- “Monthly infrastructure cost should remain predictable outside peak season.”
- “Temporary cost spikes are acceptable during declared peak periods.”
- “Cost reductions must not compromise system resilience or latency.”
- “Architectural changes affecting cost are high-risk and irreversible.”

These statements are not rules.
They are commitments that define what “acceptable” means.

They are recorded, annotated, and owned by humans.

Observation Over Reaction
The system continuously observes cost metrics relative to declared intent.

Observations include:

- absolute cost changes
- rate of change
- deviation from historical seasonal patterns
- correlation with known events (deployments, traffic shifts)

Observation does not imply action.

Most deviations result in:
- recorded observations
- annotations explaining likely causes
- continued monitoring

Silence is intentional.
Stability is not assumed to be correctness.

Seasonal Variability as First-Class Context
Seasonality is explicitly modeled, not worked around.

Examples:

- End-of-year traffic surges
- Quarterly reporting spikes
- Promotional campaigns
- Regional or industry-specific cycles

Seasonal periods may be declared as:

- relaxed cost tolerance windows
- observation-only periods
- deferred decision intervals

These declarations prevent panic reactions
and preserve institutional memory across years.

Gradual Adjustment and Experiments
When cost behavior consistently violates declared intent
outside acceptable contexts, the system may propose experiments.

Experiments are:

- small in scope
- rate-limited
- applied to a subset of services or environments
- reversible where possible

Examples:

- adjusting instance classes for a single service
- modifying autoscaling bounds within safe margins
- testing alternative storage tiers on non-critical data

Experiments are not global.
They are treated as clinical trials, not rollouts.

Each experiment produces observations, not conclusions.

Irreversibility Awareness
Some cost-related changes carry irreversible consequences.

Examples:

- architectural rewrites
- vendor lock-in
- data migration strategies
- long-term contract commitments

These actions are explicitly flagged as irreversible or high-risk.

The system must not perform them autonomously.

Instead, it:

- records accumulating evidence
- surfaces unresolved tradeoffs
- escalates decisions back to humans with context intact

Memory Across Time
A value-directed system remembers.

It records:

- prior cost deviations
- why they were tolerated or corrected
- what actions were attempted
- what outcomes followed

This allows future operators to say:

“This happened before.
Here is what we decided.
Here is why.”

This memory reduces fear-driven overcorrection
and prevents relearning the same lessons every year.

What This Example Is Not
This system is not:

- a cost optimizer
- a rules engine
- a budget enforcer
- an autoscaler for money

It does not:

- chase minimum spend
- assume lower cost is always better
- replace human judgment
- hide tradeoffs behind automation

Its role is to preserve intent,
surface drift,
and support careful, accountable decision-making.

Why This Matters
Cloud pricing failures are rarely technical.
They are failures of memory, ownership, and value clarity.

A value-directed approach makes cost behavior legible,
decisions defensible,
and change deliberate.

It treats systems not as machines to squeeze,
but as patients to care for over time.