# VDS for Software Teams  
## A Mental Model Shift: From Performance to Care

Most software teams already track metrics.

- Deployment frequency  
- Revenue  
- Error rate  
- User growth  
- Story points completed  

These are important.

But they are not the same as caring for the system.

Value-Directed Systems (VDS) introduces a different question:

> Is our system still capable of fulfilling its declared intent?

This is not a KPI question.  
It is a responsibility question.

---

# The Core Shift

Traditional thinking:

- Define goals
- Track performance
- Optimize output

VDS thinking:

- Declare intent
- Define what responsible care looks like
- Track structural health
- Surface capacity shifts without blame

KPIs measure results.  
VDS measures responsibility.

---

# What a VDS Decision Looks Like

A VDS decision is not:

- “Increase revenue by 15%.”
- “Ship weekly.”
- “Reduce latency below 100ms.”

Instead, it looks like:

- “To care for this system, we will monitor X, Y, and Z.”
- “If these degrade beyond defined thresholds, we declare capacity reduced.”

It defines what health means relative to declared intent.

---

# Example 1: E-Commerce Ordering System

## Declared Intent
Provide reliable and accurate order processing.

## VDS Care Decision
To maintain system integrity, we will monitor:
- Order processing success rate
- Inventory synchronization lag
- Checkout error rate
- Payment timeout frequency

If order failures exceed 2% for 48 hours, or inventory sync lag exceeds 5 minutes, capacity is considered reduced.

## Relatable Failure
Revenue increases during a holiday sale.  
Orders spike.  

Meanwhile:
- Inventory sync lags by 20 minutes.
- Customers purchase out-of-stock items.
- Refund volume increases.
- Support tickets surge.

KPI view: “Record-breaking revenue.”  
VDS view: “Capacity degraded. Intent misrepresented.”

---

# Example 2: SaaS Platform

## Declared Intent
Provide stable, dependable service for customer workflows.

## VDS Care Decision
To care for platform reliability, we monitor:
- 95th percentile response time
- Error rate by endpoint
- Rollbacks per release
- Open SLA-breaching support tickets

If response times exceed 2x baseline for sustained periods or rollback frequency increases release-over-release, capacity is reduced.

## Relatable Failure
Feature velocity increases.  
Marketing celebrates rapid releases.  

Meanwhile:
- Response times slowly climb.
- More hotfixes are required.
- Engineers burn out from incident load.

KPI view: “Fast innovation.”  
VDS view: “Stability debt accumulating.”

---

# Example 3: Internal IT Service Desk

## Declared Intent
Provide timely and effective technical support.

## VDS Care Decision
We monitor:
- Ticket aging beyond SLA
- Technician workload distribution
- Escalation frequency
- Repeat issue rate

If ticket aging exceeds SLA by 25% or workload imbalance persists for two cycles, capacity is reduced.

## Relatable Failure
Tickets closed per week increases.  

But:
- Senior technicians handle most escalations.
- Junior staff are underutilized.
- Repeat issues increase due to rushed fixes.

KPI view: “Higher throughput.”  
VDS view: “Support system strain emerging.”

---

# Example 4: API Platform

## Declared Intent
Provide stable, predictable integration contracts.

## VDS Care Decision
We monitor:
- Breaking changes per release
- Undocumented endpoint behavior
- Contract test failure rates
- Deprecations without transition period

If undocumented behavior increases or contract failures rise beyond baseline, capacity is reduced.

## Relatable Failure
API usage grows rapidly.  
Partners onboard quickly.

Meanwhile:
- Minor breaking changes slip through.
- Documentation lags behind implementation.
- Integration partners quietly build workarounds.

KPI view: “Adoption success.”  
VDS view: “Trust erosion beginning.”

---

# Why This Matters

Many system failures are not sudden.

They are slow drifts:

- Increasing incident frequency
- Rising rollback rates
- Growing support backlog
- Gradual performance degradation
- Silent dependency decay

These often occur while performance metrics look healthy.

VDS exists to surface these structural shifts early.

---

# What VDS Is Not

VDS does not:

- Replace KPIs
- Enforce performance targets
- Assign blame
- Judge team success

It simply answers:

> Is our system still structurally capable of fulfilling its declared intent?

---

# How Teams Can Start

1. Write a clear declared intent for your system.
2. Define 3–5 signals that represent structural health.
3. Define what constitutes “capacity reduced.”
4. Establish a cadence to review honestly.
5. Report shifts descriptively — not defensively.

---

# Final Thought

Software teams are excellent at tracking output.

But long-lived systems fail when care is assumed instead of defined.

VDS makes care explicit.

It shifts the conversation from:

“Are we winning?”

to

“Are we still capable of doing what we promised?”

That shift changes how systems age.

And it changes how teams feel inside them.