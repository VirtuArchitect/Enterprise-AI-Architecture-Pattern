# EAAP Implementation Surface

This folder contains public schemas and worked examples for EAAP-compatible implementations. It is not a production reference implementation.

The goal is to make the expected governance interface concrete without implying that a particular orchestrator, model, vector database, identity provider, or automation platform is required.

## Contents

| Path | Purpose |
| --- | --- |
| [schemas/orchestration-output.schema.json](schemas/orchestration-output.schema.json) | Minimum structured recommendation output |
| [schemas/approval-token.schema.json](schemas/approval-token.schema.json) | Approval token contract for governed execution |
| [schemas/audit-event.schema.json](schemas/audit-event.schema.json) | Immutable audit event structure |
| [examples/worked-scenario.json](examples/worked-scenario.json) | Example request, output, approval, and audit event |

## Non-Goals

- No production security implementation is provided.
- No model, agent framework, or infrastructure vendor is prescribed.
- No certification claim is made.
- No executable gateway is included.

Production deployments should treat these schemas as a starting interface contract and validate their implementation through security review, operational testing, and audit review.
