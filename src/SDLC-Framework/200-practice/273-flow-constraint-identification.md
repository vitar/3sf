# Flow Constraint Identification

> *“Before improving speed, improve flow.”*

## Purpose

The **Flow Constraint Identification (FCI)** tool helps Client and Vendor teams jointly diagnose **systemic delivery constraints** that limit throughput, quality, or predictability.

It operationalizes the 3SF principle **“Flow before Speed”** by:

- Shifting attention from team velocity to **system flow**,
- Revealing **cross-boundary bottlenecks** caused by process friction, dependencies, or governance rules,
- Creating a shared improvement plan owned by both Client and Vendor.

This tool turns local optimization conversations into a **joint systems-thinking exercise**, ensuring both sides take accountability for improving delivery flow.

## Applies To

| Dimension | Scope |
|------------|-------|
| **SDLC Stages** | Discovery → Early Delivery → Continuous Delivery |
| **3SF Relationship Lines** | Engagement ↔ Delivery |
| **3SF Layers** | Contextual Drivers Layer (CDL) + Stable Rules Layer (SRL) |
| **Maturity Target** | From *Collaborative Confidence* → toward *Co-Creative Trust* |

## Actors / Roles

| Client Side | Vendor Side | Shared Purpose |
|--------------|--------------|----------------|
| **Delivery Facilitator (Client Project Manager)** | **Delivery Facilitator (Vendor Delivery Lead)** | Co-own system flow and constraints visibility. |
| **Technical Integrator** | **Engineering Specialist** | Identify environment or release bottlenecks. |
| **Product Leader** | **Requirements Analyst** | Validate alignment between backlog flow and business readiness. |
| **Governance Officer** | **Account Lead** | Approve systemic improvement actions and adjust control rules. |

## Steps / Routines

1. **Visualize End-to-End Flow**
   - Create a **Value Stream Map (VSM)** from idea to production.
   - Include all steps — discovery, prioritization, development, testing, approvals, deployment, and validation.
   - Capture ownership, handoffs, and typical cycle time per step.

2. **Identify Systemic Constraints**
   - Mark stages where work consistently queues or reworks occur.
   - Distinguish between:
     - **Internal constraints** – team capacity, skills, tooling gaps.
     - **External constraints** – approvals, governance, third-party dependencies.
   - List the top 3 recurring constraints.

3. **Quantify Impact**
   - For each constraint, define its measurable impact (e.g., delay days, quality degradation, rework).
   - Use data from ticket systems, release logs, or velocity trends.

4. **Analyze Causes and Ownership**
   - Discuss each constraint’s root cause and ownership domain (Client, Vendor, Shared).
   - Identify which **Stable Rules** (SRL) are ineffective or missing.

5. **Define Improvement Actions**
   - Co-create a 60-day action plan to relieve or mitigate the top 3 constraints.
   - Assign measurable targets (e.g., reduce deployment wait time from 3 days to 1 day).
   - Document agreed responsibilities in the **Delivery System Diagnostic** or **Quarterly Assessment** follow-up.

6. **Review Progress Regularly**
   - Track progress on each constraint during retrospectives and quarterly reviews.
   - Escalate systemic issues to portfolio level if not resolvable within the project.

## Inputs / Outputs

| Inputs | Outputs |
|---------|----------|
| Delivery metrics (lead time, WIP, cycle time), release logs, backlog board data | **Flow Constraint Map**, **Top 3 Systemic Constraints Report**, **Improvement Action Plan** |

## Metrics / Signals

| Category | Example Indicators |
|-----------|--------------------|
| **Flow Efficiency** | Percentage of active vs. waiting time improves by ≥15%. |
| **Dependency Visibility** | 100% of known dependencies tracked with owners and due dates. |
| **Constraint Resolution Rate** | ≥ 2 systemic constraints resolved per quarter. |
| **Engagement Maturity Signal** | Improved collaboration across organizational boundaries. |

## Common Pitfalls

- Treating flow mapping as a one-time activity.
- Blaming teams instead of addressing systemic constraints.
- Ignoring client-side process bottlenecks (approvals, security reviews).
- Optimizing for throughput without verifying downstream impact.
- Not revalidating constraints after process or team changes.

## Scaling Notes

| Maturity Stage | Evolution Focus |
|----------------|-----------------|
| **Collaborative → Co-Creative** | Automate flow metrics (cycle time, WIP) via dashboards. |
| **Co-Creative → Strategic Partner** | Integrate constraint data into organizational governance and KPI systems. |

At higher maturity, constraint analysis becomes part of quarterly relationship audits and portfolio optimization.

## Client-Side Application

**Objective:** Reveal and address client-originated constraints to enable smoother vendor delivery.

**Client actions**

1. Participate in value stream mapping sessions.
2. Identify and commit to resolving internal blockers (access, approvals, decision latency).
3. Authorize necessary process or policy adjustments.
4. Support transparent reporting of systemic issues without assigning blame.

## Vendor-Side Application

**Objective:** Demonstrate delivery system leadership and transparency.

**Vendor actions**

1. Facilitate the mapping workshop and gather supporting data.
2. Quantify constraint impact using available delivery metrics.
3. Co-develop and maintain the improvement action plan.
4. Report systemic risks early to prevent reoccurrence across engagements.

## Summary

The **Flow Constraint Identification** tool transforms efficiency discussions into system alignment.<br/>
It turns the 3SF principle **“Flow before Speed”** into a measurable improvement practice, ensuring that delivery optimization is driven by shared ownership rather than isolated performance targets.<br/>
Used consistently, FCI builds trust by proving that **transparency and flow** outperform speed and control.
