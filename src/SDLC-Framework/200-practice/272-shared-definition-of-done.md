# Shared Definition of Done (DoD) Matrix  

> *“Done isn’t done until it delivers value, operates safely, and is understood by all.”*

## Purpose  

The **Shared Definition of Done (DoD) Matrix** ensures that “done” means the same thing to everyone — Client, Vendor, and end users.<br/>
It extends beyond completion of features to include operational readiness, usability, and value validation.

This tool turns the 3SF principles **“Outcome before Output”** and **“Trust before Control”** into explicit, inspectable agreements.<br/>
It creates a single measurable artifact defining:

- What *quality* means across both sides,
- Who is responsible and accountable for verifying each aspect of “done,”
- How and when verification occurs in the SDLC flow.

## Applies To

| Dimension | Scope |
|------------|-------|
| **SDLC Stages** | Design → Delivery → Validation |
| **3SF Relationship Lines** | Delivery ↔ Value |
| **3SF Layers** | Stable Rules Layer (SRL) |
| **Maturity Target** | From *Collaborative Confidence* → toward *Co-Creative Trust* |

## Actors / Roles

| Client Side | Vendor Side | Shared Purpose |
|--------------|--------------|----------------|
| **Technical Integrator** | **Engineering Specialist** | Ensure build quality and deployment readiness. |
| **Product Leader (Client Product Owner)** | **Delivery Facilitator** | Define and validate acceptance criteria and usability. |
| **Governance Officer** | **Engineering Director** | Enforce regulatory, security, and operational standards. |
| **Experience Designer** | **Requirements Analyst** | Validate user experience and alignment with requirements. |

## Steps / Routines

1. **Define Quality Dimensions**
   - Identify 3 core dimensions of “done”:
     1. **Code Quality** – internal engineering standards, test coverage, peer review.
     2. **Operational Readiness** – deployment, observability, monitoring, rollback capability.
     3. **User Acceptance & Value Verification** – alignment with business outcomes and user expectations.

2. **Build the DoD Matrix**
   - Create a table where each quality dimension is a row and each column represents ownership and verification points:

     | Quality Dimension | Vendor Responsible | Client Accountable | Verification Timing | Evidence / Artifact |
     |------------------|--------------------|--------------------|--------------------|--------------------|
     | Code Quality | Engineering Specialist | – | Before merge | CI/CD test report, code review record |
     | Operational Readiness | Technical Integrator | Governance Officer | Before deployment | Deployment checklist, monitoring setup proof |
     | User Acceptance & Value Verification | Delivery Facilitator | Product Leader | After release | Outcome tracking, user feedback, KPI dashboard |

3. **Integrate into Workflow**
   - Add DoD checkpoints into definition-of-ready and release readiness reviews.
   - Enforce that a work item cannot close until all relevant DoD dimensions are verified.

4. **Review and Update**
   - Validate the DoD Matrix quarterly or whenever a new context (team, technology, or product) is introduced.
   - Record updates as part of the **Stable Rules Layer (SRL)**.

## Inputs / Outputs

| Inputs | Outputs |
|---------|----------|
| Quality standards, CI/CD data, release checklist, product KPIs | **Shared Definition of Done Matrix**, signed by Client and Vendor representatives |

## Metrics / Signals

| Category | Example Indicators |
|-----------|--------------------|
| **Alignment Signal** | No major disagreements about “done” definitions during retrospectives. |
| **Quality Consistency** | <5% of items re-opened post-release due to incomplete readiness. |
| **Accountability Clarity** | 100% of features include DoD traceability in backlog. |
| **Maturity Indicator** | Shared sign-off process applied across ≥ 2 cross-functional teams. |

## Common Pitfalls

- Treating DoD as a static document rather than a living agreement.
- Focusing only on development quality while ignoring operational or value readiness.
- Client expecting vendor to own all validation steps unilaterally.
- Vendor marking tasks as “done” without verification evidence.
- Updating DoD inconsistently across projects or releases.

## Scaling Notes

| Maturity Stage | Evolution Focus |
|----------------|-----------------|
| **Collaborative → Co-Creative** | Embed DoD verification into automation pipelines and dashboards. |
| **Co-Creative → Strategic Partner** | Integrate outcome validation into SLA / contract governance. |

As maturity rises, “done” becomes a joint performance metric, not a delivery milestone.

## Client-Side Application

**Objective:** Maintain control over business value realization and operational readiness.

**Client actions**

1. Approve DoD dimensions and assign accountable roles.
2. Validate operational readiness before approving production releases.
3. Track post-release outcomes to verify “done” equals value delivered.
4. Include DoD compliance in governance or audit checklists.

## Vendor-Side Application

**Objective:** Demonstrate engineering excellence and maturity through transparency.

**Vendor actions**

1. Define measurable quality gates and include them in the DoD Matrix.
2. Provide objective verification artifacts before requesting acceptance.
3. Collaborate with client on readiness and outcome validation steps.
4. Continuously refine automation and testing to meet DoD expectations.

## Summary

The **Shared Definition of Done Matrix** transforms “completion” into a **joint commitment**.<br/>
It replaces unilateral sign-offs with measurable, shared quality standards — ensuring that **trust is built through clarity, not control**.<br/>
When integrated into delivery systems, it becomes one of the most reliable indicators of relationship and delivery maturity.
