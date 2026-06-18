# EAAP: Positioning Statement
**Version 1.1 | John Goulden | May 2026**

---

## The Problem

Enterprise AI has a governance gap. Organisations are deploying AI systems into high-trust, high-impact operational environments, but the architecture surrounding those deployments has not kept pace. Governance is implemented as policy rather than structural control. AI outputs lack evidence provenance. Confidence is uncalibrated. Human approval is advisory, not enforced. AI systems are granted direct access to operational infrastructure.

The result is AI that is capable but not trustworthy, at least not in the way that regulated enterprises, critical infrastructure operators, and sovereign governments need it to be.

More capable models do not solve this. The problem is architectural.

---

## What EAAP Is

The **Enterprise AI Architecture Pattern (EAAP)** is a governance-oriented architectural control framework for enterprise AI systems operating in high-trust and high-impact environments.

EAAP is not a model, a product, or a software platform. It is an architectural pattern: a structured, vendor-neutral, model-agnostic framework that defines how enterprise AI systems should be designed, constrained, and governed.

EAAP positions the large language model as a replaceable reasoning component operating within a larger governed architecture. The framework enforces governance through structural mechanisms: bounded domain agents, deterministic orchestration, evidence classification, calibrated confidence gates, human approval boundaries, and execution isolation through controlled automation gateways.

---

## Who It Is For

EAAP is designed for:

- **Enterprise architects and platform teams** building or evaluating AI systems in regulated or operationally sensitive environments
- **CIOs, CISOs, and AI governance leads** in defence, critical infrastructure, financial services, healthcare, and government
- **Organisations operating air-gapped or sovereign AI environments**, where external API connectivity is prohibited or operationally unacceptable
- **Policy and standards bodies** seeking implementable governance architecture to complement compliance frameworks such as NIST AI RMF and ISO/IEC 42001

EAAP-LGF, the Lethal Systems Governance Framework derived from EAAP, addresses organisations with AI involvement in high-stakes and lethal decision support contexts, including defence contractors, NATO-aligned agencies, and dual-use AI vendors.

---

## What EAAP Does

EAAP defines six architectural layers with clearly bounded responsibilities:

- **Governance Layer:** Defines operational constraints and approval requirements as structural controls, not policy
- **Orchestration Layer:** Coordinates, arbitrates, and validates cross-domain reasoning through deterministic lifecycle phases
- **Domain Intelligence Layer:** Performs isolated, bounded domain reasoning through specialised agents
- **Knowledge and Evidence Layer:** Supplies validated reference material and enforces evidence provenance
- **Execution Layer:** Isolates AI from direct infrastructure access through a controlled Automation Gateway
- **Audit and Traceability Layer:** Maintains immutable operational records across every governance action

Every output is evidence-classified. Every high-impact action requires structured human approval. Every confidence gap triggers escalation, not autonomous continuation.

### Reference Implementation

EAAP ships with a working reference implementation: a governance-deterministic orchestrator system prompt (v6.0) that operationalises the full framework as executable control logic. The reference implementation enforces the 11-phase orchestration workflow, the tiered action risk model, the Data Sufficiency Gate, the Conditional Override, and the Final Decision Gate as runtime constraints, not documentation. It is validated against a specific air-gapped deployment stack: Nutanix AHV, RHEL, Docker, LLaMA, and OpenWebUI.

This means EAAP is not a framework organisations must interpret and implement from scratch. The reference implementation demonstrates how EAAP governance translates directly into operational AI system behaviour.

---

## Key Differentiators

**Governance as structure, not policy.** Most enterprise AI governance frameworks define what organisations should do. EAAP defines how the architecture must enforce it. Controls are built in, not bolted on.

**Vendor-neutral and model-agnostic.** EAAP defines architectural principles independent of any specific vendor, orchestration platform, or model provider. Any compliant implementation using different tooling remains architecturally valid.

**Designed for sovereign and air-gapped environments.** EAAP explicitly minimises external dependencies, making it suitable for defence, classified, and data-sovereign deployments where external API connectivity is unacceptable.

**Formally defined and publicly documented.** EAAP is not a whitepaper or a set of principles. It is a structured framework with a maintained document register covering core architecture, orchestration models, domain agent specifications, confidence thresholds, deployment models, and governance definitions.

**Validated through implementation.** Most governance frameworks remain theoretical. EAAP has been iterated to a working reference implementation (orchestrator v6.0), demonstrating that the architectural principles are operationally coherent, not just conceptually sound.

**Lethal systems extension.** EAAP-LGF is the only publicly available governance architecture framework specifically designed for AI in lethal decision support contexts, grounded in international humanitarian law and implementing a non-overridable prohibition layer, compound assessment gates, and mandatory multi-authoriser human approval.

---

## Credibility Anchors

- Published preprint: *EAAP: A Governance Architecture for Deterministic Enterprise AI Systems* (Zenodo, May 2026)
- Published preprint: *EAAP-LGF: A Governance Architecture for AI in Lethal Decision Support Systems* (Zenodo, April 2026)
- Structured document register: nine architectural documents covering core architecture, orchestration, domain agents, functional architecture, deployment, and confidence modelling
- Working reference implementation: governance-deterministic orchestrator at v6.0, validated on an air-gapped Nutanix/RHEL/LLaMA stack
- Independent research: no vendor affiliation, no product interest

---

## In One Sentence

EAAP is a vendor-neutral governance architecture framework, backed by two published papers, a nine-document architecture register, and a working reference implementation, that defines how enterprise AI systems should be structurally constrained, orchestrated, and audited in high-trust and high-impact environments, including sovereign and air-gapped deployments.

---

*EAAP is an open framework. Enquiries: research@johngoulden.de*
