## SDLC Stage Dimensions – Build

### Purpose

The **Build Stage** is where ideas, designs, and plans turn into a working product.<br/>
Its purpose is to **design, develop, and integrate** software components with automation, quality, and shared ownership at the core.

Build is not only about coding — it’s about maintaining **flow, visibility, and alignment** across teams, ensuring each increment delivers measurable progress and validated value.<br/>
When executed maturely, Build becomes the engine of both **technical excellence** and **relationship trust** between Client and Vendor.

### Core Outcomes

| **Outcome** | **Description** |
|--------------|-----------------|
| **Working Product Increments** | Functional, testable software aligned with scope and goals. |
| **Predictable Delivery Flow** | Stable sprint or iteration cadence with transparent progress tracking. |
| **Quality Built In** | Testing, automation, and validation integrated into daily development. |
| **Visible Progress** | Delivery transparency through demos, metrics, and shared dashboards. |
| **Engineering Feedback Loops** | Continuous feedback on quality, velocity, and technical debt. |

### Build Dimensions

#### 1. Strategic Alignment

Ensures that Build execution remains connected to business outcomes and product intent.

| **Aspect** | **Low Maturity (Reactive)** | **High Maturity (Proactive)** |
|-------------|-----------------------------|--------------------------------|
| **Goal Visibility** | Teams focus on tickets, not outcomes. | Developers understand why features matter to users. |
| **Scope Discipline** | Frequent scope creep and unclear priorities. | Stable, prioritized backlog tied to objectives. |
| **Value Focus** | Progress measured by volume of work. | Progress measured by value delivered or validated. |
| **Decision Context** | Engineers disconnected from product strategy. | Engineers involved in trade-off and design discussions. |

**Improvement Strategies**

- Share *Product Vision Boards* and outcome maps with delivery teams.
- Use *Story Mapping* to link user flows to business goals.
- Include engineers in scope and backlog refinement sessions.

#### 2. Planning & Flow

Defines how work is decomposed, planned, and executed to maintain a sustainable pace and predictable outcomes.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Backlog Readiness** | Incomplete or unclear stories. | Clear DoR (Definition of Ready) and consistent backlog grooming. |
| **Iteration Planning** | Overcommitted or ad hoc scope. | Predictable velocity and adaptive capacity planning. |
| **Work in Progress (WIP)** | Too many parallel tasks, context switching. | Limited WIP and visible flow management (Kanban boards, flow metrics). |
| **Dependencies** | Managed reactively. | Dependencies identified, visualized, and mitigated early. |

**Improvement Strategies**

- Apply *Kanban* or *Scrum with Flow Metrics*.
- Use *Cumulative Flow Diagrams* to spot bottlenecks.
- Introduce *Sprint Capacity Planning* and WIP limits by team role.

#### 3. Collaboration & Communication

Defines how the team synchronizes, collaborates, and manages feedback during execution.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Team Communication** | Silos between roles; issues discussed too late. | Daily visibility, open problem-solving culture. |
| **Stakeholder Updates** | Irregular or one-way reporting. | Regular demos, transparent dashboards, two-way communication. |
| **Cross-Functional Collaboration** | Developers, designers, testers operate separately. | Integrated squads collaborating around features or epics. |
| **Decision Transparency** | Decisions undocumented or repeated. | Decisions visible and logged in shared tools (ADR, issue trackers). |

**Improvement Strategies**

- Encourage *pair programming*, *mob testing*, and *cross-role reviews*.
- Establish a *shared status dashboard* visible to Client and Vendor.
- Maintain a *Team Working Agreement* covering communication, review, and escalation norms.

#### 4. Quality & Risk Management

Ensures that the system remains stable and maintainable while progress accelerates.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Testing Approach** | Manual, end-stage QA only. | Continuous testing: unit, integration, end-to-end automated pipelines. |
| **Code Quality** | Inconsistent standards, unreviewed code. | Shared coding standards, code review culture, linters and static analysis. |
| **Defect Management** | Bugs found late or ignored. | Early detection, visible defect metrics, root cause analysis. |
| **Technical Debt Management** | Reactive firefighting, no refactoring time. | Debt logged, prioritized, and managed as part of delivery. |

**Improvement Strategies**

- Adopt *Test Automation Pyramid* and *Shift-Left Testing*.
- Use *SonarQube* or similar tools for code health tracking.
- Schedule *Tech Debt Sprints* or allocate engineering capacity for refactoring.

#### 5. Learning & Adaptation

Defines how the team inspects performance, learns, and improves during the Build cycle.

| **Aspect** | **Low Maturity** | **High Maturity** |
|-------------|-----------------|-------------------|
| **Retrospectives** | Irregular or unfocused. | Regular, data-informed retrospectives with actionable outcomes. |
| **Metrics Utilization** | Metrics collected but not used. | Metrics analyzed and drive measurable process adjustments. |
| **Knowledge Sharing** | Isolated expertise. | Knowledge documented and spread through pairing, wikis, and reviews. |
| **Continuous Improvement** | Process changes reactive to crises. | Improvement backlog prioritized and tracked continuously. |

**Improvement Strategies**

- Use *Team Health Checks* and *Agile Metrics Dashboards* (lead time, defects, predictability).
- Rotate responsibilities to spread system knowledge.
- Introduce *Learning Hours* or short technical demos during sprints.

### Common Failure Modes

| **Failure Mode** | **Root Cause** | **Correction** |
|------------------|----------------|----------------|
| **“Velocity fluctuates wildly.”** | Unclear backlog, overcommitment, or interruptions. | Limit WIP, improve backlog readiness, stabilize team focus. |
| **“Quality issues pile up near release.”** | Testing deferred or manual only. | Shift-left automation, enforce DoD with test coverage. |
| **“Developers disengaged from product goals.”** | Poor communication or siloed decision-making. | Include engineers in planning and stakeholder reviews. |
| **“Integration issues late in cycle.”** | Lack of CI/CD or shared environments. | Adopt trunk-based development and continuous integration. |

When flow metrics become performance targets, teams start optimizing numbers instead of outcomes. 3SF treats metrics as feedback, not judgment.

### Measuring Build Health

| **Signal** | **Description** |
|-------------|----------------|
| **Stable velocity and flow metrics across iterations.** | Predictable delivery pattern achieved. |
| **High automation coverage and quick CI/CD feedback cycles.** | Engineering efficiency increasing. |
| **Low defect escape rate between environments.** | Quality maturity improving. |
| **Transparent backlog and demo cadence maintained.** | Alignment and visibility ensured. |

Quantitative metrics may include:

- Lead time and cycle time stability.
- % of automated tests and deployment success rate.
- Ratio of refactoring vs. new feature work.
- Sprint predictability (committed vs. delivered).

### Build and Relationship Maturity

The Build stage matures the relationship from **Shared Ownership** to **Strategic Partnership**.<br/>
It’s where autonomy is proven through reliable delivery, and trust deepens through transparency and quality.

High-maturity Build means:

- Teams operate with **clarity and independence**, not isolation.
- Delivery decisions are **coordinated, not dictated**.
- Transparency builds confidence — enabling Client and Vendor to plan forward together.

### Summary

- The **Build Stage** is where structure meets execution — converting vision into reality with precision and accountability.
- Its five dimensions — Strategic Alignment, Planning & Flow, Collaboration, Quality & Risk, Learning & Adaptation — define the maturity and stability of delivery.
- Build maturity determines system reliability and organizational trust.
- Strong Build practices create a foundation for fast validation, smooth releases, and long-term partnership success.
