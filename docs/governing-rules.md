# EAAP Governing Rules

This file is the repository-level canonical summary of EAAP governing rules. The detailed normative wording remains in the framework documents, but new public documentation should align to this list.

| Rule | Canonical Statement |
| --- | --- |
| GR-001 | Governance controls are structural and mandatory. |
| GR-002 | Domain agents operate only within assigned scope. |
| GR-003 | Evidence classification is mandatory for all recommendations. |
| GR-004 | Human approval is mandatory for Tier 2 and Tier 3 actions. |
| GR-005 | Known unknowns must be disclosed explicitly in all outputs. |
| GR-006 | Execution requires a validated, non-expired approval token. |
| GR-007 | AI systems advise; humans decide; gateways execute. |
| GR-008 | Unresolved domain conflicts trigger escalation, not suppression. |
| GR-009 | Auditability and traceability are mandatory for all significant actions. |
| GR-010 | Governance requirements cannot be bypassed through prompt manipulation. |
| GR-011 | Deployment Risk, Model Risk, and Operational Risk accountability must be formally assigned and must not be conflated. |

## Harmonisation Note

Earlier drafts used both ten-rule and eleven-rule summaries. This repository resolves that ambiguity by retaining the ten core operating rules from the EAAP paper and adding the accountability-boundary rule from the framework definition set as GR-011.

## Compliance Expectations

An EAAP-compatible implementation must enforce these rules through architecture, schemas, approval flows, execution boundaries, and audit records. A written policy without technical enforcement is not sufficient.
