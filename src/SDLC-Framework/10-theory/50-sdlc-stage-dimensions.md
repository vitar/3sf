# SDLC Stage Dimentions

## Purpose

The **SDLC Stage Dimensions** define the configurable decision spaces within each stage of delivery.<br/>
They help Project Leads, Product Managers, and Architects **diagnose, design, and adjust** how each SDLC Stage operates in context — aligning delivery mechanics with project realities.

Each dimension represents a *set of variables* that influence how work flows through the system.<br/>
By understanding and tuning these dimensions, teams can balance speed, quality, and adaptability while maintaining system integrity.

## What Stage Dimensions Are

A **Stage Dimension** is a lens for examining *how a stage is executed* — not *what activities occur* within it.<br/>
Each dimension captures a set of interdependent conditions such as scope definition, estimation strategy, feedback loops, or risk handling.

Dimensions can be viewed as **levers**:

- When pulled in one direction, they improve stability or predictability.
- When pulled in another, they enable adaptability or speed.

The right balance depends on context, constraints, and maturity.

## The Role of Dimensions in 3SF

Within the 3SF structure:

| **Layer** | **Purpose** |
|------------|-------------|
| **SDLC Stages** | Define what happens across the lifecycle. |
| **SDLC Practices** | Define how quality and flow are sustained across all stages. |
| **SDLC Stage Dimensions** | Define *how each stage behaves* — the adjustable parameters and decision patterns. |

Dimensions translate abstract principles (like “governance clarity” or “learning loops”) into **practical, observable variables** that can be inspected or tuned.<br/>
They also serve as the **bridge between Contextual Drivers (CDL)** and **Stable Rules (SRL)** — the place where external conditions meet internal system design.

## Dimension Categories

Each stage has its own unique decision areas, but all Stage Dimensions fall under **five universal categories** that describe different aspects of delivery configuration:

| **Category** | **Definition** | **Typical Examples** |
|---------------|----------------|----------------------|
| **Strategic Alignment** | Ensures that stage activities connect to the project’s purpose, value, and goals. | Vision clarity, outcome definition, success metrics. |
| **Planning & Flow** | Defines how work is scoped, estimated, sequenced, and tracked. | Backlog depth, WIP limits, cadence of planning. |
| **Collaboration & Communication** | Governs information flow, stakeholder involvement, and decision-making transparency. | RACI, ceremony design, escalation paths. |
| **Quality & Risk Management** | Defines how uncertainty, testing, and verification are handled within the stage. | Definition of done, testing scope, approval criteria. |
| **Learning & Adaptation** | Enables reflection, improvement, and responsiveness to change. | Feedback cadence, review structure, continuous improvement loops. |

These categories apply to **every stage**, but the specific decisions and trade-offs within each depend on stage purpose and context.

## Example: How Dimensions Interconnect

For instance, in the **Shape** stage:

- *Strategic Alignment* defines outcomes and prioritization.
- *Planning & Flow* translates them into epics and estimates.
- *Collaboration* defines how client and vendor make trade-offs.
- *Quality & Risk* determines acceptance conditions and architectural feasibility.
- *Learning & Adaptation* captures feedback from early discovery or prototypes.

When these dimensions align, Shape provides a stable foundation for Build.<br/>
When they misalign, Build inherits ambiguity, rework, and unvalidated assumptions.

## Why Dimensions Matter

**Without dimensions, delivery tuning becomes guesswork.**<br/>
Projects often fail not because teams lack competence, but because their stages are configured incorrectly for the environment.

Common failure modes:

- Discovery too narrow → Shape inherits false assumptions.
- Build too rigid → Validation discovers issues too late.
- Run disconnected from Learn → No systemic improvement.

Stage Dimensions bring **diagnostic clarity** — enabling teams to identify not only *what’s broken*, but *why* it behaves that way.

## Relationship to Maturity

Maturity across the SDLC is visible through the **health of Stage Dimensions**:

- *Immature stages* show fragmented, reactive, or unowned dimensions.
- *Mature stages* show integrated, stable, and continuously improving dimensions.

When assessing maturity through the **RAC** or **CRC**, each rule and contextual archetype ultimately maps to one or more Stage Dimensions.<br/>
For example:

- **Stable Rule R3 – “Decisions are transparent and reversible”** → affects Collaboration and Quality dimensions.
- **Contextual Driver – “Fixed bid contract”** → constrains Planning & Flow, influencing estimation and governance.

## Applying Stage Dimensions

Use Stage Dimensions for:

1. **Design:** Before execution, define the configuration per stage (e.g., estimation depth, backlog readiness, governance model).
2. **Assessment:** During delivery, inspect dimension health through metrics, signals, and team reflection.
3. **Adaptation:** After retrospectives or milestones, adjust dimension design to improve flow and maturity.

Teams can document stage dimensions in simple templates or dashboards — linking them to risks, metrics, and improvement actions.

## Structure of Stage Dimension Files

Each stage has a dedicated section detailing:

- The stage’s **core purpose and outcomes**.
- Its **dimension breakdown** under the five categories.
- Typical **configuration options**, **failure patterns**, and **improvement strategies**.

| **Stage** | **Purpose** |
|-----------|-------------|
| [Discover](51-sdlc-stage-discovery-dimensions.md) | How to frame problems and align understanding before shaping. |
| [Shape](52-sdlc-stage-shape-dimensions.md) | How to define scope, feasibility, and delivery models. |
| [Build](53-sdlc-stage-build-dimensions.md) | How to structure flow, engineering quality, and visibility. |
| [Validate](54-sdlc-stage-validate-dimensions.md) | How to manage verification, acceptance, and joint confidence. |
| [Release](55-sdlc-stage-release-dimensions.md) | How to manage approvals, risk, and deployment readiness. |
| [Run & Evolve](56-sdlc-stage-run-evolve-dimensions.md) | How to sustain and improve systems post-launch. |

Each file builds upon this overview, creating a **consistent pattern** that allows readers to trace the evolution of alignment, flow, and learning across the SDLC.

## Summary

- **SDLC Stage Dimensions** describe how each stage functions in context — the levers and trade-offs teams must balance.  
- They provide **diagnostic visibility** and **design flexibility**, connecting strategy, delivery, and governance.  
- Dimensions bridge contextual forces (CDL) and systemic stability (SRL), serving as the *operational DNA* of the 3SF delivery system.  
- Mastering dimension design is the key to transforming projects from reactive execution into adaptive, learning systems.
