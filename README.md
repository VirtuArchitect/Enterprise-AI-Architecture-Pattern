# EAAP: Enterprise AI Architecture Pattern

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20085547.svg)](https://doi.org/10.5281/zenodo.20085547)

> Version 1.0 - public framework release  
> John Goulden - Independent Researcher, Germany  
> ORCID: [0009-0000-5626-6535](https://orcid.org/0009-0000-5626-6535)

EAAP is an open architectural governance framework for deterministic enterprise AI systems. It defines the structural conditions under which AI-assisted recommendations can be made, escalated, approved, executed, and audited in high-trust enterprise environments.

The central principle is **governance determinism**: proceed, escalate, and block conditions are defined in advance and enforced by the architecture, not improvised by individual judgement at runtime.

## Architecture Layers

| Layer | Name | Responsibility |
| --- | --- | --- |
| 1 | Governance | Governing rules, human approval tiers, override conditions |
| 2 | Orchestration | Intent routing, domain dispatch, conflict arbitration, confidence gating |
| 3 | Domain Intelligence | Specialist domain agents with bounded scope |
| 4 | Knowledge and Evidence | Evidence classification, provenance, currency |
| 5 | Execution | Automation Gateway as the sole execution interface |
| 6 | Audit and Traceability | Immutable audit log and full decision-chain capture |

## Repository Map

| Path | Purpose |
| --- | --- |
| [docs/index.md](docs/index.md) | Public document register and reading order |
| [docs/governing-rules.md](docs/governing-rules.md) | Canonical governing rules |
| [docs/decision-model.md](docs/decision-model.md) | Proceed, escalate, and block decision model |
| [docs/framework/](docs/framework/) | Master reference and core framework documents |
| [docs/architecture/](docs/architecture/) | Architecture specifications |
| [docs/operations/](docs/operations/) | Operations and agent operating specifications |
| [docs/amendments/](docs/amendments/) | Released amendments |
| [papers/](papers/) | Published preprints and publication copies |
| [implementation/](implementation/) | Schemas and non-production reference examples |

## Published Papers

- Goulden, J. (2026). *EAAP - Enterprise AI Architecture Pattern - A Governance Architecture for Deterministic Enterprise AI Systems*. Zenodo. [https://doi.org/10.5281/zenodo.20085547](https://doi.org/10.5281/zenodo.20085547)
- Goulden, J. (2026). *EAAP-LGF A Governance Architecture for AI in Lethal Decision Support Systems*. Zenodo. [https://doi.org/10.5281/zenodo.20205544](https://doi.org/10.5281/zenodo.20205544)

## Implementation Status

This repository does **not** claim to contain a production reference implementation. The [implementation/](implementation/) folder contains public schemas and worked examples that show the expected governance surface for EAAP-compatible implementations.

Production deployments must implement their own security, approval, audit, calibration, and operational controls and validate them in their target environment.

## Licence

Framework documentation and papers are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Implementation schemas and examples are licensed under [Apache License 2.0](implementation/LICENSE).

See [LICENSE](LICENSE) for repository-level terms.

## Contact

John Goulden  
Independent Researcher - Enterprise AI Governance and Architecture  
Germany  

- Email: [research@johngoulden.de](mailto:research@johngoulden.de)
- ORCID: [0009-0000-5626-6535](https://orcid.org/0009-0000-5626-6535)
