## SDLC Stage Dimensions – Shape

### Purpose

The **Shape Stage** defines *how the vision becomes feasible* — transforming ideas and validated insights from Discovery into a **delivery-ready plan**.<br/>
It establishes **scope, architecture vision, delivery approach, and feasibility**, aligning all parties on what will be built, how, and under which constraints.

Shape is where **strategy meets execution**.<br/>
It converts the “why” and “what” discovered earlier into “how” — preparing teams, stakeholders, and systems for sustainable delivery flow.<br/>
When done well, Shape minimizes delivery risk, sets realistic expectations, and becomes the contract of shared understanding between Client and Vendor.

### Core Outcomes

| **Outcome** | **Description** |
|--------------|-----------------|
| **Delivery Vision** | A coherent, outcome-aligned vision that translates business goals into tangible delivery objectives. |
| **Scope Definition** | A prioritized backlog or roadmap describing what will be built, when, and why. |
| **Architecture Vision** | A documented target architecture and rationale aligned with scalability, security, and maintainability. |
| **Feasibility & Estimation** | Validated assumptions, complexity estimates, and resource forecasts. |
| **Delivery Model & Governance** | Clear engagement model, communication cadence, and decision-making process. |

### Shape Dimensions

#### 1. Strategic Alignment

Defines how well Shape connects the validated Discovery findings to actionable scope and measurable outcomes.

| **Aspect** | **Low Maturity (Reactive)** | **High Maturity (Proactive)** |
|-------------|-----------------------------|--------------------------------|
| **Goal Translation** | Discovery outputs not reflected in scope. | Goals translated into product outcomes and acceptance metrics. |
| **Prioritization Logic** | Everything is “must-have.” | Prioritization driven by value, risk, and effort balance. |
| **Outcome Traceability** | Delivery tasks disconnected from strategic goals. | Each backlog item traces to a defined business outcome. |
| **Vision Communication** | Technical or business bias dominates. | Shared, human-readable vision understood by all stakeholders. |

**Improvement Strategies**

- Use *VMOSA* (Vision, Mission, Objectives, Strategies, Actions) or *Impact Mapping*.
- Apply *Outcome-based Roadmapping* — link objectives to measurable impacts.
- Create a *single-page delivery vision* reviewed jointly with all key stakeholders.

#### 2. Planning & Flow

Defines how scope, estimation, and delivery model are structured to balance feasibility with adaptability.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Scope Definition** | Overly detailed or incomplete. | Balanced between high-level themes and well-shaped backlog. |
| **Estimation Method** | Based on assumptions, not validated data. | Multi-method estimation (PERT, T-shirt sizing, story points) with uncertainty range. |
| **Delivery Model Choice** | Model dictated by contract or inertia. | Model adapted to context (Fixed-Bid, Time & Material, Co-Delivery). |
| **Roadmap Structure** | Dates arbitrary, dependencies unclear. | Milestones based on value increments and dependency analysis. |

**Improvement Strategies**

- Introduce *progressive estimation* — refine scope iteratively.
- Use *Scenario Planning* for budget and timeline alignment.
- Align delivery model choice with Contextual Drivers (commercial, organizational, technical).

#### 3. Collaboration & Communication

Defines how decisions are co-created and communicated between client and vendor roles.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Decision-Making** | Centralized, delayed, or ambiguous. | Distributed decisions within defined RACI and escalation paths. |
| **Stakeholder Involvement** | Limited to approvals. | Stakeholders actively contribute to trade-offs and prioritization. |
| **Communication Flow** | Channel chaos, undocumented agreements. | Clear communication map, meeting cadences, and shared documentation. |
| **Cross-Discipline Integration** | Product, design, and engineering operate separately. | Joint shaping sessions, shared artifacts, and synchronized priorities. |

**Improvement Strategies**

- Define *Governance Cadence* — e.g., weekly sync, bi-weekly steering.
- Maintain a *Shape Log* capturing decisions, rationales, and risks.
- Use *Collaboration Maps* to visualize stakeholder engagement and information flow.

#### 4. Quality & Risk Management

Defines how feasibility, architecture, and delivery risks are identified and controlled before Build starts.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Architecture Vision** | Implicit or over-engineered; lacks trade-offs. | Architecture designed collaboratively with rationale and constraints. |
| **Feasibility Testing** | Feasibility assumed, not validated. | Risk spikes and POCs used to confirm critical assumptions. |
| **Technical Debt Awareness** | None — “we’ll fix it later.” | Debt potential logged with mitigation options. |
| **Definition of Ready** | Missing or vague. | Agreed entry criteria for Build with clear acceptance boundaries. |

**Improvement Strategies**

- Apply *Architecture Decision Records (ADR)* and *Architecture Runway*.
- Create *Feasibility Register* — track technical risk, cost, and decisions.
- Align readiness checklist with Build expectations (DoR, environments, design assets).

#### 5. Learning & Adaptation

Defines how discovery insights, decisions, and risks evolve into an adaptive delivery mindset.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Feedback Integration** | Discovery learnings ignored. | Discovery insights explicitly embedded into scope and architecture. |
| **Reflection on Trade-offs** | Decisions made without review. | Retrospective held to assess shaping quality and stakeholder alignment. |
| **Adaptability to Change** | Contract or timeline blocks adjustments. | Scope change process defined and integrated into governance. |
| **Knowledge Continuity** | Handovers inconsistent or undocumented. | Shape artifacts consolidated in accessible, shared repositories. |

**Improvement Strategies**

- Conduct a *Shape Retrospective* after final sign-off.
- Maintain a *Decision Register* — track what changed, why, and impact.
- Use *Knowledge Handover Packages* (vision, architecture, roadmap) for Build readiness.

### Common Failure Modes

| **Failure Mode** | **Root Cause** | **Correction** |
|------------------|----------------|----------------|
| **“We’re shaping while building.”** | Discovery incomplete, Shape rushed. | Separate timeboxes and exit criteria for each stage. |
| **“The backlog is too vague to start.”** | Missing DoR and architecture clarity. | Enforce readiness validation and backlog refinement. |
| **“Estimates keep changing.”** | Scope or assumptions not validated. | Document estimation assumptions and uncertainty ranges. |
| **“Client expects more than planned.”** | Value and scope poorly communicated. | Present scope through outcomes, not features; revalidate alignment. |

The illusion of precision — detailed plans built on unvalidated inputs — is a recurring trap. Shape aims for confidence, not certainty.

### Measuring Shape Health

| **Signal** | **Description** |
|-------------|----------------|
| **Shared delivery vision and roadmap approved by both Client and Vendor.** | Alignment achieved. |
| **Architecture and feasibility validated via ADRs and POCs.** | Technical confidence established. |
| **Prioritization matrix links outcomes, effort, and risk.** | Informed decisions made. |
| **Definition of Ready checklist accepted by Build team.** | Clear transition into Build. |

Quantitative indicators:

- % of backlog items meeting DoR criteria.
- Estimation confidence range (± deviation vs. actual).
- Stakeholder alignment score (via feedback survey).

### Shape and Relationship Maturity

The Shape stage moves the relationship from **Aligned Autonomy** toward **Shared Ownership**.<br/>
Here, trust grows through *joint decision-making* and *transparent trade-offs*.

High-maturity shaping:

- Builds shared accountability for both outcomes and constraints.
- Replaces handovers with collaboration.
- Aligns product ambition with delivery feasibility.

### Summary

- The **Shape Stage** translates understanding into a feasible, outcome-driven delivery plan.
- Its five dimensions — Strategic Alignment, Planning & Flow, Collaboration, Quality & Risk, Learning & Adaptation — ensure scope, architecture, and delivery model coherence.
- Mature shaping ensures Build starts with confidence, autonomy, and transparency.
- When Shape fails, all later stages pay the cost — when it succeeds, the system flows.
