## Start Here

- [HCOS™ Ecosystem Architecture](architecture/HCOS_Ecosystem_Architecture.md)  
  The highest-level architectural map of the HCOS™ ecosystem.

- [HCOS™ Knowledge Governance Framework](architecture/HCOS_Knowledge_Governance_Framework.md)  
  Defines how HCOS knowledge is evaluated, governed, and stewarded.

- [HCOS™ Knowledge Lifecycle](architecture/HCOS_Knowledge_Lifecycle.md)  
  Explains how evidence moves from observation through publication and continuous improvement.

# hcos-knowledge-governance
# governance/

The **governance/** directory contains the policies, frameworks, and processes that preserve the architectural integrity of the HCOS™ ecosystem. These documents define how knowledge is evaluated, approved, organized, versioned, and maintained to ensure the framework remains coherent, evidence-informed, transparent, and sustainable over time.

## Purpose

The governance layer establishes the rules by which HCOS itself is managed. It provides consistency across repositories, supports traceability of architectural decisions, and ensures that new knowledge is incorporated through a disciplined, repeatable process.

## Contents

* **Knowledge_Governance_Framework.md** — Defines the governance philosophy, principles, roles, and responsibilities for managing the HCOS body of knowledge.
* **Classification_Policy.md** — Establishes the criteria for classifying new work as Foundations, Disciplines, Standards, Methods, Instruments, Research, Learning Resources, Governance, or Stewardship.
* **Document_Lifecycle.md** — Describes how HCOS documents progress from proposal through review, publication, revision, and retirement.
* **REVIEW_STANDARD.md** — Defines the review process, quality expectations, and approval criteria for HCOS documentation.
* **RELEASE_PROCESS.md** — Documents the procedures for versioning, changelogs, Git tags, and official HCOS releases.

Together, these documents ensure that HCOS evolves intentionally while maintaining the quality, consistency, and long-term stewardship expected of a human-centered knowledge architecture.

# examples/

The **examples/** directory demonstrates how the HCOS™ Knowledge Architecture is applied in practice. These documents provide worked examples of the core instruments and governance processes, helping contributors understand how evidence moves through the HCOS knowledge lifecycle.

## Purpose

Examples translate architectural concepts into practical application. They illustrate how new information is evaluated, classified, synthesized, and used to evolve the HCOS framework while maintaining consistency with governance and stewardship principles.

## Contents

* **Discovery_Example.md** — Demonstrates how the HCOS™ AI Architecture Discovery Instrument extracts enduring systems principles from a single source or event.
* **Classification_Example.md** — Shows how new knowledge is evaluated and placed within the HCOS architecture using the Architecture Classification Instrument.
* **Synthesis_Example.md** — Illustrates how multiple insights are analyzed collectively to identify recurring themes, emerging architectural pillars, and evidence-supported principles.
* **Evolution_Example.md** — Demonstrates how accumulated evidence informs recommendations for new Foundations, Disciplines, Standards, Methods, Instruments, Governance, or Stewardship activities.

These examples serve as practical reference implementations, enabling contributors to apply the HCOS Knowledge Architecture consistently while reinforcing an evidence-informed, human-centered approach to continuous learning and improvement.

# GitHub Architecture — HCOS™ Organizational Readiness Stewardship

```text
HCOS-Knowledge-Governance/
│
├── README.md
├── CHANGELOG.md
├── VERSIONING.md
├── FILE_MANIFEST.md
│
├── architecture/
│   ├── README.md
│   ├── HCOS_Ecosystem_Architecture.md
│   ├── HCOS_Knowledge_Architecture.md
│   ├── HCOS_Knowledge_Lifecycle.md
│   ├── HCOS_Evidence_Maturity_Model.md
│   ├── HCOS_Architecture_Principles.md
│   │
│   └── organizational-readiness/
│       ├── README.md
│       ├── HCOS_Organizational_Readiness_Architecture.md
│       ├── HCOS_Organizational_Readiness_Core_Concepts.md
│       ├── Organizational_Decision_Uncertainty_as_a_Primary_Barrier_to_AI_Adoption.md
│       └── Organizational_AI_Readiness_Development_Roadmap.md
│
├── decisions/
│   ├── README.md
│   └── ADR-001_Organizational_Readiness_Stewardship.md
│
├── standards/
│   ├── README.md
│   └── HCOS_Organizational_AI_Readiness_Standard.md
│
├── methods/
│   ├── README.md
│   └── HCOS_Organizational_Decision_Readiness_Method.md
│
├── instruments/
│   ├── README.md
│   │
│   └── organizational-readiness/
│       ├── README.md
│       ├── HCOS-I-XXX_Organizational_AI_Readiness_and_Decision_Uncertainty_Assessment.md
│       ├── HCOS-I-XXX_Executive_Readiness_Screen.md
│       ├── HCOS-I-XXX_AI_Use_Case_Framing_Worksheet.md
│       ├── HCOS-I-XXX_Current_State_Workflow_Mapping_Guide.md
│       ├── HCOS-I-XXX_Decision_Ownership_and_Authority_Map.md
│       ├── HCOS-I-XXX_Human_Impact_and_Load_Review.md
│       ├── HCOS-I-XXX_Governance_and_Escalation_Checklist.md
│       ├── HCOS-I-XXX_Evidence_and_Baseline_Review.md
│       └── HCOS-I-XXX_Learning_and_Reassessment_Plan.md
│
├── assessment-architecture/
│   └── organizational-readiness/
│       ├── README.md
│       ├── HCOS_Organizational_AI_Readiness_Construct_Map.md
│       ├── HCOS_Organizational_AI_Readiness_Scoring_and_Interpretation_Framework.md
│       ├── HCOS_Organizational_AI_Readiness_Output_Specification.md
│       └── HCOS_Decision_Critical_Conditions.md
│
├── validation/
│   └── organizational-readiness/
│       ├── README.md
│       ├── HCOS_Organizational_AI_Readiness_Pilot_Protocol.md
│       ├── HCOS_Content_Validation_Guide.md
│       ├── HCOS_Cognitive_Testing_Guide.md
│       ├── HCOS_Inter_Rater_Review_Plan.md
│       ├── HCOS_Decision_Utility_Evaluation.md
│       └── HCOS_Outcome_Validation_Roadmap.md
│
├── stewardship/
│   └── organizational-readiness/
│       ├── README.md
│       ├── HCOS_Organizational_Readiness_Stewardship_Plan.md
│       ├── HCOS_Assessment_Review_Schedule.md
│       ├── HCOS_Evidence_Monitoring_Plan.md
│       └── HCOS_Revision_and_Deprecation_Guidance.md
│
├── templates/
│   └── organizational-readiness/
│       ├── Readiness_Assessment_Record_Template.md
│       ├── Decision_Uncertainty_Map_Template.md
│       ├── Human_System_Impact_Map_Template.md
│       ├── Readiness_Action_Plan_Template.md
│       └── Learning_and_Reassessment_Record_Template.md
│
└── examples/
    └── organizational-readiness/
        ├── README.md
        ├── Prior_Authorization_AI_Readiness_Example.md
        ├── Clinical_Message_Summarization_Readiness_Example.md
        ├── Employee_Knowledge_Search_Readiness_Example.md
        └── Organizational_Readiness_Worked_Synthesis.md
```

# Architectural Layers

## 1. Architecture

Explains the concept and why it belongs within HCOS.

```text
architecture/organizational-readiness/
```

Primary documents:

* Organizational Readiness Architecture
* Core Concepts
* Decision Uncertainty Synthesis
* Development Roadmap

---

## 2. Decision Record

Preserves why HCOS created the architecture.

```text
decisions/ADR-001_Organizational_Readiness_Stewardship.md
```

The ADR should remain the authoritative record of the architectural decision.

---

## 3. Standard

Defines the conditions that should exist before proceeding.

```text
standards/HCOS_Organizational_AI_Readiness_Standard.md
```

Core question:

> What does responsible organizational AI readiness require?

---

## 4. Method

Defines the repeatable review process.

```text
methods/HCOS_Organizational_Decision_Readiness_Method.md
```

Core question:

> How should an organization evaluate decision readiness?

---

## 5. Assessment Architecture

Defines the structure of the future assessment before questions are written.

```text
assessment-architecture/organizational-readiness/
```

This folder contains:

* domains and constructs
* scoring philosophy
* decision-critical conditions
* output requirements
* interpretation rules

---

## 6. Instruments

Contains the usable assessment and supporting tools.

```text
instruments/organizational-readiness/
```

The primary instrument should be:

```text
HCOS-I-XXX_Organizational_AI_Readiness_and_Decision_Uncertainty_Assessment.md
```

Supporting instruments should remain modular so organizations can use only the components appropriate to the use case.

---

## 7. Validation

Contains the evidence-development process for the assessment.

```text
validation/organizational-readiness/
```

This keeps instrument development separate from claims of reliability or validity.

Until validation is completed, the assessment should be described as:

> An evidence-informed organizational decision-support instrument.

---

## 8. Stewardship

Defines how the architecture and assessment are reviewed and improved.

```text
stewardship/organizational-readiness/
```

This includes:

* evidence monitoring
* periodic review
* change management
* deprecation
* future revisions

---

## 9. Templates

Contains reusable records generated during the assessment.

```text
templates/organizational-readiness/
```

These are outputs, not independent HCOS Methods or Standards.

---

## 10. Examples

Demonstrates how the architecture applies to bounded AI use cases.

```text
examples/organizational-readiness/
```

Start with concrete use cases rather than a universal enterprise-readiness example.

# Recommended Development Order

```text
1. architecture/organizational-readiness/
2. decisions/
3. standards/
4. methods/
5. assessment-architecture/
6. instruments/
7. templates/
8. examples/
9. validation/
10. stewardship/
```

# Minimum Initial Structure

You do not need to create every folder immediately.

Start with:

```text
HCOS-Knowledge-Governance/
│
├── architecture/
│   └── organizational-readiness/
│       ├── README.md
│       ├── HCOS_Organizational_Readiness_Architecture.md
│       ├── HCOS_Organizational_Readiness_Core_Concepts.md
│       ├── Organizational_Decision_Uncertainty_as_a_Primary_Barrier_to_AI_Adoption.md
│       └── Organizational_AI_Readiness_Development_Roadmap.md
│
├── decisions/
│   └── ADR-001_Organizational_Readiness_Stewardship.md
│
├── standards/
│   └── HCOS_Organizational_AI_Readiness_Standard.md
│
└── methods/
    └── HCOS_Organizational_Decision_Readiness_Method.md
```

Add `assessment-architecture/`, `instruments/`, `validation/`, and `examples/` as those documents are developed.

# Repository Principle

The architecture should remain:

```text
Enduring Principle
        ↓
Architecture
        ↓
Standard
        ↓
Method
        ↓
Assessment Architecture
        ↓
Instrument
        ↓
Validation
        ↓
Stewardship
```

This order preserves traceability and prevents the assessment from becoming a disconnected questionnaire.
