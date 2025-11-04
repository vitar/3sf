# Contextual Drivers Layer (CDL)

## Purpose

The **Contextual Drivers Layer (CDL)** defines the external and internal forces that shape how the SDLC system should operate in a given environment.<br/>
It recognizes that **no project exists in a vacuum** — every delivery model is influenced by commercial agreements, organizational structures, product maturity, technical landscape, and relationship context.

By identifying these drivers early, teams can **adapt the SDLC configuration consciously**, not reactively — selecting practices, rules, and decision patterns that best fit the project’s constraints and opportunities.

CDL is therefore the **adaptive intelligence layer** of the 3SF framework: it provides the situational awareness necessary to design, diagnose, and evolve any project context.

## CDL in the 3SF Structure

| **Layer** | **Purpose** |
|------------|-------------|
| **SDLC Stages** | Define the value flow (Discover → Evolve). |
| **SDLC Practices** | Ensure quality, automation, and governance throughout. |
| **SDLC Stage Dimensions** | Describe how each stage behaves in context. |
| **Contextual Drivers Layer (CDL)** | Explain *why* the system must behave that way — the conditions shaping delivery design. |
| **Stable Rules Layer (SRL)** | Define universal rules that keep the system coherent. |
| **Rule Audit Checklist (RAC)** | Measure adherence to those rules. |
| **Contextual Rules Catalog (CRC)** | Translate CDL + SRL into specific delivery playbooks. |

CDL thus acts as the **input layer** for delivery system configuration and as the **diagnostic layer** for understanding delivery friction.

## CDL Categories

The CDL organizes all contextual drivers into **six categories**, each representing a domain of influence.<br/>
These drivers can be viewed as *boundary conditions* or *design constraints* that determine how maturity, practices, and decisions should be applied.

| **Category** | **Definition** | **Examples of Drivers** |
|---------------|----------------|--------------------------|
| **1. Commercial Context** | Financial and contractual models defining risk, ownership, and incentives. | Fixed-Bid vs. Time & Material, shared risk, cost of delay, billing structure, vendor competition. |
| **2. Organizational Context** | Structure, processes, and decision hierarchy of both Client and Vendor organizations. | Centralized vs. distributed governance, number of stakeholders, matrix structures, delivery dependencies. |
| **3. Product Context** | Nature, maturity, and complexity of the product or service being delivered. | New build vs. modernization, MVP vs. enterprise system, technical debt level, release cadence expectations. |
| **4. Technical Context** | Technology stack, platform constraints, and delivery environment. | Cloud migration vs. on-prem, CI/CD maturity, legacy integrations, DevOps readiness. |
| **5. Relationship Context** | Trust, collaboration, and alignment level between Client and Vendor. | Transactional vs. strategic partnership, communication openness, feedback culture, autonomy. |
| **6. Environmental Context** | External or systemic forces beyond direct control. | Regulatory requirements, data privacy laws, time zone overlap, market dynamics, cultural or language barriers. |

Each project operates within a unique combination of these drivers.<br/>
Understanding them early allows the SDLC configuration (stages, practices, and rules) to adapt for stability and effectiveness.

## CDL as a Diagnostic Lens

Contextual Drivers can be analyzed from two perspectives:

1. **Influence:** How a driver *shapes or constrains* SDLC decisions.<br/>
   Example: A *Fixed-Bid* contract limits flexibility in Discovery and Shape — requiring stronger scope definition and risk buffers.
2. **Signal:** How a driver *manifests symptoms* of stress or misalignment.<br/>
   Example: Persistent *scope creep* under a *Fixed-Bid* contract indicates mismatch between commercial and delivery context.

By mapping drivers to affected SDLC Stages and Practices, teams can uncover **root causes** of delivery dysfunction rather than symptoms.

## CDL → SDLC Connection Map

| **CDL Category** | **Primary SDLC Stages Impacted** | **Key Practices Affected** | **Typical Constraints or Levers** |
|------------------|----------------------------------|-----------------------------|-----------------------------------|
| **Commercial Context** | Discover, Shape, Validate | Governance & Risk, Product Thinking | Budget model, risk allocation, scope flexibility. |
| **Organizational Context** | Shape, Build, Release | Collaboration, Architecture & Design | Decision speed, approvals, dependency management. |
| **Product Context** | Discover, Build, Run | Product Thinking, Engineering & Quality | Product maturity, architecture flexibility, tech debt. |
| **Technical Context** | Build, Validate, Release | DevOps & Delivery, Architecture & Design | Automation readiness, tooling, environment stability. |
| **Relationship Context** | Discover, Shape, Evolve | Feedback & Learning, Governance & Risk | Trust, autonomy, alignment maturity, transparency. |
| **Environmental Context** | Release, Run, Evolve | Governance & Risk, Feedback & Learning | Regulatory controls, operational risk, localization. |

This mapping becomes the foundation for contextual rule generation (CRC) and rule validation (RAC).

## CDL Assessment

A **Contextual Driver Assessment** can be done during Discovery or periodically during long-running projects.<br/>
Its purpose is to identify **which drivers are stable, volatile, or misaligned**.

Example checklist (simplified):

| **Category** | **Driver** | **Status** | **Impact** | **Action** |
|---------------|-------------|-------------|-------------|-------------|
| Commercial | Fixed-bid contract | Active | High constraint on flexibility | Define strict Shape governance and risk buffers. |
| Relationship | Low client trust | High risk | Blocks autonomy | Introduce transparency rituals and co-created planning. |
| Technical | Legacy system dependency | Persistent | Medium | Schedule feasibility spikes and rollback plans. |

Drivers with high impact should trigger configuration adjustments (via SRL or CRC).

## CDL in Practice

### 1. During Discovery:

- Identify contextual drivers and classify by category.
- Highlight those that constrain design or delivery models.
- Inform Shape decisions (architecture, governance, estimation).

### 2. During Delivery:

- Monitor changes in contextual drivers (e.g., contract renewal, new stakeholders, tool migrations).
- Adjust Stage Dimensions and Practices to maintain coherence.

### 3. During Retrospectives or Audits:

- Review contextual shifts to explain performance or relationship changes.
- Update RAC and CRC mappings to reflect new constraints or opportunities.

## CDL and Relationship Maturity

Contextual Drivers determine how much maturity a project can realistically achieve.<br/>
For example:

- A highly regulated environment may *limit autonomy* but *increase clarity* — maturity can grow in governance, not speed.
- A flexible, trusted relationship may *allow experimentation* — maturity can grow in feedback and learning loops.

Mature organizations don’t fight constraints; they **design within them**.<br/>
The CDL enables this by making constraints explicit and manageable.

## Summary

- The **Contextual Drivers Layer (CDL)** captures the forces that shape delivery — commercial, organizational, product, technical, relationship, and environmental.
- It acts as the **input lens** for tuning the SDLC system and explaining why projects behave as they do.
- CDL connects context (why) with system design (how) — forming the foundation for adaptive governance and contextual playbooks (CRC).
- Mastering CDL awareness allows leaders to make informed trade-offs and build delivery systems that thrive under real-world constraints.
