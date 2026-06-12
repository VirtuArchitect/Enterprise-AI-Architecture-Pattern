# EAAP: Enterprise AI Architecture Pattern

[![DOI](https://zenodo.org/badge/DOI/10.XXXX/zenodo.XXXXXXX.svg)](https://doi.org/10.XXXX/zenodo.XXXXXXX)

> **Version 1.0 — May 2026**
> John Goulden — Independent Researcher, Germany
> ORCID: [0009-0000-5626-6535](https://orcid.org/0009-0000-5626-6535)

---

## The Problem

Most enterprise AI deployments lack the structural governance controls required for operational trustworthiness. Ad-hoc policy documents and post-hoc safeguards do not constitute governance they constitute risk transfer. The result is AI systems that behave non-deterministically in high-stakes environments, with no defined escalation path, no auditable evidence chain, and no bounded execution scope.

EAAP addresses the governance gap between AI capability and enterprise operational accountability.

---

## What EAAP Is

EAAP (Enterprise AI Architecture Pattern) is an architectural governance framework for deterministic enterprise AI systems. It defines the structural conditions under which AI-assisted decisions can be made, escalated, approved, executed, and audited in an enterprise context.

**Governance Determinism** the central principle of EAAP means that the conditions for proceed, escalate, and block are defined in advance and uniformly enforced by the architecture itself, not by individual judgement at runtime.

EAAP is not a policy document. It is an architectural specification. Compliance is structural.

---

## Architecture Layers

EAAP defines six architectural layers:

| Layer | Name | Responsibility |
|-------|------|----------------|
| 1 | Governance | Governing rules, human approval tiers, override conditions |
| 2 | Orchestration | Intent routing, domain dispatch, conflict arbitration, confidence gating |
| 3 | Domain Intelligence | Specialist domain agents with bounded scope |
| 4 | Knowledge and Evidence | Evidence classification, provenance, currency |
| 5 | Execution | Automation Gateway - sole execution interface; AI never directly touches infrastructure |
| 6 | Audit and Traceability | Immutable audit log, full decision chain capture |

The framework is governed by **GR-001 to GR-011** (Governing Rules), which are non-negotiable architectural requirements.

---

## Reference Implementation

The **EAAP Reference Implementation** demonstrates the full six-layer architecture in a containerised, platform-agnostic deployment, suitable for both cloud and air-gapped sovereign environments.

Reference implementation materials are in [`implementation/orchestrator/`](implementation/orchestrator/).

---

## Who It Is For

EAAP is intended for:

- **Enterprise architects** designing AI systems for regulated or high-stakes environments
- **AI governance leads** requiring structural (not merely policy-based) compliance controls
- **Platform engineers** building sovereign, air-gapped, or operationally critical AI deployments
- **Researchers and policymakers** working on AI governance frameworks, standards, or regulation

---

## Document Register

| Document ID | Title | Version | Status |
|-------------|-------|---------|--------|
| EAAP v1.0 | Enterprise AI Architecture Pattern (main paper) | 1.0 | Published preprint |
| EAAP-DEF-001 | Framework Definitions and Master Reference | 1.0 | Released |
| EAAP-DEF-001-AMD-001 | AI Trust Boundary Model | 1.3 | Released amendment |
| EAAP-CORE-001 | Core Architecture Definition (Layer 3 Pattern) | 1.0 | Released |
| EAAP-ARCH-001 | Domain Agent Model | 1.0 | Released |
| EAAP-ARCH-002 | Orchestration Logic | 1.0 | Released |
| EAAP-ARCH-002A | Orchestration Prompt Control | 1.0 | Released |
| EAAP-ARCH-003 | Orchestration Decision Model | 1.0 | Released |
| EAAP-ARCH-003A | Orchestration Decision Model Production Design | 1.0 | Released |
| EAAP-ARCH-004 | Functional Architecture Model | 1.0 | Released |
| EAAP-ARCH-005 | Functional Architecture HLD | 1.0 | Draft |
| EAAP-ARCH-006 | Deployment Model (Platform-Agnostic) | 1.0 | Released |
| EAAP-OPS-001 | AI Operational Risk Controls and Incident Escalation | 1.1 | Draft |
| EAAP-LGF | Lethal Systems Governance Framework | 1.1 | Published preprint (Zenodo) |

Documents will be added to [`papers/`](papers/) and [`docs/`](docs/) as they are released publicly.

---

## Published Papers

- **EAAP v1.0** - *Enterprise AI Architecture Pattern* (May 2026)
  > Goulden, J. (2026). *Enterprise AI Architecture Pattern*. Independent preprint.
  > DOI: [placeholder]

- **EAAP-LGF v1.1** - *Lethal Systems Governance Framework* (April 2026)
  > Goulden, J. (2026). *Lethal Systems Governance Framework*. Zenodo preprint.
  > DOI: [placeholder]

---

## Licence

This repository uses a dual-licence structure.

**Framework documentation** (`papers/`, `docs/`) is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - free to share and adapt with attribution.

**Reference implementation** (`implementation/`) is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) - free for non-commercial use with attribution. Commercial deployment requires a separate agreement: [research@johngoulden.de](mailto:research@johngoulden.de)

See [LICENSE](LICENSE) and [implementation/LICENSE.md](implementation/LICENSE.md) for full terms.

---

## Contact

**John Goulden**
Independent Researcher — Enterprise AI Governance and Architecture
Germany

- Email: [research@johngoulden.de](mailto:research@johngoulden.de)
- ORCID: [0009-0000-5626-6535](https://orcid.org/0009-0000-5626-6535)
- GitHub: [github.com/VirtuArchitect] (https://github.com/VirtuArchitect) 
