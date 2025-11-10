# Governance Contract

> *“Governance exists to enable autonomy, not to constrain it.”*

### Purpose

The **Governance Contract (GC)** establishes the **decision-making structure and escalation rules** that regulate day-to-day collaboration between Client and Vendor under the 3SF framework.<br/>
It defines *how decisions are made*, *who holds which authority*, and *how exceptions are handled* — ensuring that governance evolves with trust and maturity.

This contract translates the 3SF principle **“Trust before Control”** into an operational framework.<br/>
It aligns all governance mechanisms with the current **relationship maturity level**, preventing both micromanagement and unmanaged autonomy.

### Applies To

| Dimension | Scope |
|------------|-------|
| **SDLC Stages** | Design → Delivery → Governance |
| **3SF Relationship Lines** | Engagement ↔ Delivery |
| **3SF Layers** | Stable Rules Layer (SRL) + Rule Audit Checklist (RAC) |
| **Maturity Target** | From *Transactional Trust* → toward *Strategic Partnership* |

### Actors / Roles

| Client Side | Vendor Side | Shared Purpose |
|--------------|--------------|----------------|
| **Executive Sponsor** | **Account Lead** | Approve governance model and review quarterly. |
| **Governance Officer** | **Delivery Facilitator** | Maintain operational governance cadence. |
| **Product Leader (Client Product Owner)** | **Product Leader (Vendor Product Manager)** | Ensure product-level decisions align with autonomy level. |
| **Solution Architect** | **Solution Architect** | Manage architecture decisions and technical risk sign-offs. |

### Key Components of the Governance Contract

| Component | Description | Linked 3SF Artifacts |
|------------|--------------|----------------------|
| **Governance Structure Overview** | Defines key governance layers: executive, operational, and delivery. | [Autonomy & Control Boundary Charter](../200-practice/210-autonomy-control-charter.md) |
| **Decision Rights Matrix (RACI/DACI)** | Assigns authority and consultation rules across functions. | [3SF Functional Role Model](../200-practice/200-practice-architecture.md) |
| **Escalation Model** | Defines when and how to escalate issues across governance layers. | [Flow Constraint Identification](../200-practice/230-flow-constraint-identification.md) |
| **Governance Cadence** | Lists meeting frequency and objectives for steering committees and working groups. | [Engagement Contract](310-engagement-contract.md) |
| **Governance Health Indicators** | Defines how trust, transparency, and accountability are measured. | [Maturity Growth Contract](320-maturity-growth-contract.md), [Maturity Dashboard](../200-practice/215-maturity-dashboard.md) |

### Agreement Format

The Governance Contract is typically structured as a **governance annex** to the Delivery Charter or portfolio agreement.
It includes explicit mapping of decision domains, authority boundaries, and escalation paths.

**Example extract (decision authority matrix):**

| Governance Domain | Client Authority | Vendor Authority | Decision Rule |
|--------------------|------------------|------------------|----------------|
| Product Scope | Approve major scope changes >5 days | Adjust within iteration | Escalate if >10% effort variance |
| Architecture | Co-sign all critical NFR trade-offs | Co-sign all critical NFR trade-offs | Governed by [Architectural Trade-Off Contract](../200-practice/235-architectural-tradeoff-contract.md) |
| Delivery Planning | Approve release milestones | Self-manage sprint planning | Report weekly |
| Quality Standards | Define acceptance thresholds | Validate through DoD Matrix | Shared accountability |
| Incident Resolution | Approve workaround exceeding SLA | Lead resolution and report cause | Follow [Learning Before Blame Protocol](../200-practice/265-learning-before-blame-protocol.md) |

### Inputs / Outputs

| Inputs | Outputs |
|---------|----------|
| Engagement Contract, Delivery Charter, organizational governance policies | **Governance Structure Map**, **Decision Rights Matrix**, **Escalation Flow**, **Governance Review Record** |

### Metrics / Signals

| Category | Example Indicators |
|-----------|--------------------|
| **Decision Latency** | Average decision turnaround ≤ 48h for operational, ≤ 5 days for executive. |
| **Escalation Efficiency** | ≥ 80% of issues resolved within the defined governance tier. |
| **Transparency Signal** | Governance dashboards visible to both Client and Vendor. |
| **Trust Alignment** | Governance satisfaction ≥ 4/5 in quarterly reviews. |

### Common Pitfalls

- Creating governance models that reflect *organizational hierarchy*, not *relationship maturity*.
- Over-escalating small issues, leading to decision bottlenecks.
- Ignoring flow metrics (cycle time, WIP) when assessing governance performance.
- Keeping static authority models despite trust improvement.
- Failing to document exceptions and learning outcomes.

### Scaling Notes

| Maturity Stage | Evolution Focus |
|----------------|-----------------|
| **Transactional → Collaborative** | Replace one-sided approvals with shared steering. |
| **Collaborative → Co-Creative** | Simplify escalation paths and introduce delegated autonomy. |
| **Co-Creative → Strategic** | Integrate governance dashboards into enterprise portfolio management. |

At higher maturity, governance evolves into **co-leadership** — both organizations co-owning decision rights and accountability boundaries.

### Client-Side Application

**Objective:** Ensure governance provides oversight and alignment without stifling flow.

#### **Client actions**

1. Approve governance structure and cadence jointly with vendor.
2. Ensure governance decisions are based on data, not opinion.
3. Revisit autonomy levels quarterly as trust increases.
4. Participate in governance health assessments and dashboard reviews.

### Vendor-Side Application

**Objective:** Use governance to enhance delivery reliability and transparency.

#### **Vendor actions**

1. Maintain governance logs, meeting notes, and dashboards.
2. Propose improvements to reduce decision latency.
3. Ensure transparency of risks and dependencies before escalation.
4. Educate teams on governance maturity principles.

### Summary

The **Governance Contract** defines how two organizations **co-lead** a delivery system under 3SF principles.<br/>
It ensures that every decision, escalation, and control mechanism is aligned with maturity — enabling a shift from *management-by-approval* to *governance-by-trust*.

When executed properly, this contract becomes the **operating kernel** of the 3SF ecosystem — maintaining balance between autonomy, flow, and accountability across all layers of collaboration.
