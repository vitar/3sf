## Contextual Rules Catalog (CRC)

### Purpose

The **Contextual Rules Catalog (CRC)** translates the universal **Stable Rules (SRL)** into **context-specific playbooks**, enabling adaptive delivery under real-world conditions.<br/>
Where SRL defines *what must always remain true*, the CRC defines *how it can best be achieved* given the unique **Contextual Drivers (CDL)** of each project.

CRC is therefore the **pragmatic layer** of 3SF — connecting principles to practice, helping leaders adjust their delivery approach without compromising coherence or trust.<br/>
It is used when system rules need to flex within stable boundaries — for example, when working under fixed-bid contracts, co-delivery models, or continuous product operations.

### CRC in the 3SF Structure

| **Layer** | **Purpose** |
|------------|-------------|
| **CDL (Contextual Drivers)** | Describe external/internal forces shaping delivery. |
| **SRL (Stable Rules)** | Define non-negotiable systemic principles. |
| **RAC (Rule Audit Checklist)** | Measure adherence to rules in practice. |
| **CRC (Contextual Rules Catalog)** | Adapt and operationalize rules for specific delivery contexts. |

CRC allows organizations to move beyond “one-size-fits-all” process design — by **anchoring adaptability in principle, not preference**.

### CRC Design Philosophy

Every contextual rule is expressed as a **conditional mapping**:

> **If** (contextual driver X) and **if** (affected SDLC stage/dimension Y)<br/>
> **then** (apply strategy or configuration Z to maintain stability and maturity).

These mappings ensure that project-level adaptations stay consistent with system integrity —<br/>
**never violating SRL, only expressing it differently**.

### CRC Categories (Delivery Context Archetypes)

The CRC defines a small number of **delivery context archetypes** that represent typical real-world configurations of Client–Vendor collaboration.<br/>
Each archetype modifies how the 12 Stable Rules are implemented across the SDLC stages.

| **Archetype** | **Description** | **Typical CDL Signature** |
|----------------|-----------------|----------------------------|
| **A1. Fixed-Bid / Contractual Delivery** | Defined scope, fixed timeline and cost; low tolerance for change. | High commercial constraint, low flexibility, often transactional trust. |
| **A2. Co-Delivery Partnership** | Shared ownership between client and vendor; teams integrated across functions. | Balanced commercial model, aligned autonomy, medium-high trust. |
| **A3. Continuous Product Evolution** | Ongoing development and optimization of a live product. | Time & material, strong feedback loops, strategic partnership. |
| **A4. Rapid Discovery / Innovation Pilot** | Short, exploratory engagement with uncertain outcomes. | High uncertainty, high flexibility, fast iteration, trust critical. |
| **A5. Managed Service / Sustainment** | Vendor responsible for operations, monitoring, and continuous improvement. | Operational stability, predictable cadence, long-term accountability. |

Each archetype inherits all 12 Stable Rules — but expresses them differently depending on constraints and priorities.

### CRC Example Mappings

#### A1. Fixed-Bid / Contractual Delivery

| **Rule (SRL)** | **Implementation in Fixed-Bid Context** | **Reason / Effect** |
|----------------|------------------------------------------|----------------------|
| **R1 – Clarity before Commitment** | Discovery and Shape must be separate contracts or phases with exit criteria. | Ensures estimates and commitments are evidence-based. |
| **R3 – Decisions are Transparent and Reversible** | Changes logged formally via controlled governance (CRs), with impact tracking. | Reduces escalation risk while maintaining traceability. |
| **R5 – Quality is Built In** | Enforce automated regression testing from sprint one; no manual-only QA. | Compensates for limited change tolerance. |
| **R7 – Risk Shared is Risk Reduced** | Define shared risk buffer in the SOW for rework or unforeseen effort. | Protects both parties under rigid commercial terms. |
| **R10 – Governance Enables, not Controls** | Steering cadence fixed but focused on evidence-based progress, not reporting. | Keeps governance lean and trust-building. |

**Outcome:** Predictability and accountability strengthened without over-bureaucratization.

#### A2. Co-Delivery Partnership

| **Rule (SRL)** | **Implementation in Co-Delivery Context** | **Reason / Effect** |
|----------------|--------------------------------------------|----------------------|
| **R2 – One System of Truth** | Shared Jira/ADO boards and dashboards visible to both Client and Vendor. | Eliminates dual status versions. |
| **R4 – Progress is Measured by Outcomes** | Use shared OKRs tied to joint product roadmap milestones. | Aligns performance metrics across organizations. |
| **R6 – Flow Requires Limits** | Manage WIP jointly per epic, not per team. | Prevents overload in shared delivery responsibility. |
| **R8 – Change is a Continuous Signal** | Adjust backlog continuously based on data and stakeholder feedback. | Allows agility without renegotiation overhead. |
| **R11 – Transparency Scales Trust** | Open access to repositories, docs, and incident logs. | Reinforces partnership maturity through openness. |

**Outcome:** Collaboration operates as one delivery organism with shared visibility and accountability.

#### A3. Continuous Product Evolution

| **Rule (SRL)** | **Implementation in Continuous Product Context** | **Reason / Effect** |
|----------------|--------------------------------------------------|----------------------|
| **R1 – Clarity before Commitment** | Use rolling quarterly goals and flexible prioritization. | Keeps intent clear while allowing iteration. |
| **R5 – Quality is Built In** | CI/CD pipelines enforce automated testing and code quality gates. | Maintains delivery speed without degrading stability. |
| **R9 – Feedback Completes the Flow** | Integrate analytics and user feedback loops directly into backlog grooming. | Ensures real-world insights drive development. |
| **R10 – Governance Enables, not Controls** | Product councils decide direction based on evidence, not hierarchy. | Keeps governance adaptive and data-driven. |
| **R12 – Learning is the Only Sustainable Advantage** | Post-release reviews treated as mandatory; improvements prioritized in next sprint. | Ensures continuous evolution and innovation. |

**Outcome:** Stable yet fast-moving system where learning drives value growth.

#### A4. Rapid Discovery / Innovation Pilot

| **Rule (SRL)** | **Implementation in Innovation Context** | **Reason / Effect** |
|----------------|-------------------------------------------|----------------------|
| **R1 – Clarity before Commitment** | Define problem statement and validation plan — not fixed deliverables. | Focuses effort on learning, not output. |
| **R4 – Progress is Measured by Outcomes** | Use hypothesis validation metrics (e.g., # validated assumptions). | Measures learning speed and quality. |
| **R6 – Flow Requires Limits** | Limit concurrent hypotheses to maintain focus. | Preserves discovery quality and prevents diffusion. |
| **R7 – Risk Shared is Risk Reduced** | Agree on fast feedback loops and shared decision checkpoints. | Enables safe experimentation within timebox. |
| **R9 – Feedback Completes the Flow** | Include early user feedback sessions before prototype completion. | Validates direction before full investment. |

**Outcome:** Maximized learning per time unit, reduced risk of building the wrong thing.

#### A5. Managed Service / Sustainment

| **Rule (SRL)** | **Implementation in Managed Service Context** | **Reason / Effect** |
|----------------|-----------------------------------------------|----------------------|
| **R2 – One System of Truth** | Operational dashboards shared across vendor and client. | Promotes shared situational awareness. |
| **R5 – Quality is Built In** | Automate monitoring, alerting, and compliance checks. | Ensures stability and efficiency. |
| **R7 – Risk Shared is Risk Reduced** | Shared SLA ownership and incident root-cause analysis. | Fosters continuous reliability improvements. |
| **R9 – Feedback Completes the Flow** | Weekly review of incidents and performance trends. | Turns operations data into learning. |
| **R12 – Learning is the Only Sustainable Advantage** | Continuous improvement backlog integrated with run operations. | Evolves service quality and relationship maturity. |

**Outcome:** Predictable, transparent operations aligned with continuous system evolution.

### CRC Mapping Template

To create new contextual playbooks, use this mapping format:

| **If CDL Condition...** | **and SDLC Stage/Dimension is...** | **then apply Practice(s)...** | **to uphold SRL Rule...** | **Effect / Outcome** |
|--------------------------|------------------------------------|------------------------------|---------------------------|----------------------|
| Fixed-bid contract limits flexibility | Shape – Planning & Flow | Progressive estimation, explicit risk buffer | R1, R7 | Predictable scope and shared risk mitigation |
| Low relationship trust | Discover – Collaboration | Transparent workshop cadence and visible notes | R2, R11 | Builds early transparency and trust |
| Highly regulated industry | Release – Governance | Automated compliance gates and audit trails | R5, R10 | Ensures quality and control within compliance |
| Continuous product delivery | Evolve – Learning & Adaptation | Ongoing telemetry and user research loops | R9, R12 | Maintains improvement momentum |

This table can be extended for organization-specific contexts and stored in a shared CRC knowledge base (e.g., Confluence, GitHub Wiki, or internal portal).

### CRC and Maturity

As maturity increases, projects move from **rule application** to **rule design**:

| **Maturity Level** | **CRC Usage Behavior** |
|---------------------|------------------------|
| **Level 1 – Reactive** | Teams rely on predefined CRC playbooks (Fixed-Bid, Co-Delivery). |
| **Level 2 – Structured** | Teams select and combine playbook elements consciously. |
| **Level 3 – Adaptive** | Teams co-create custom mappings based on real feedback. |
| **Level 4 – Evolutionary** | Organization continuously evolves CRC through lived experience and cross-project learning. |

### CRC Governance

To keep the catalog effective:

- **Review quarterly** to capture new lessons from projects.
- **Version control** CRC playbooks (v1.1, v1.2…) to track learning.
- **Link** CRC rules to RAC findings — improvement actions should modify or extend contextual mappings.
- **Integrate** CRC into onboarding and project kickoff processes.

### Adapting Without Excusing

The purpose of contextual adaptation is **to preserve system integrity under constraint**, not to justify underperformance.<br/>
A common misuse of CRC occurs when teams interpret flexibility as permission to ignore stable rules — turning context into an excuse rather than a design factor.<br/>
Healthy adaptation always traces back to **which Stable Rule it protects** and **what learning it generates**.<br/>
When a contextual rule cannot explain its stabilizing purpose, it signals adaptation drift — a warning that coherence is being traded for comfort.

### CRC and Relationship Maturity

CRC operationalizes relationship maturity:

- **Transactional projects** depend on structured CRC playbooks for predictability.
- **Aligned partnerships** use CRC dynamically to adjust governance.
- **Strategic partnerships** co-create new contextual rules, contributing back to the catalog.

Thus, CRC is not just documentation — it’s the **institutional memory of delivery intelligence**.

### Summary

- The **Contextual Rules Catalog (CRC)** translates stable system principles (SRL) into practical guidance for diverse delivery contexts (CDL).
- It ensures flexibility without chaos — adapting practices to context while preserving systemic integrity.
- CRC acts as the living knowledge base of 3SF — continuously evolving through audit (RAC) and experience.
- When mastered, CRC turns every project into a learning loop — where context refines rules, and rules sustain excellence.
