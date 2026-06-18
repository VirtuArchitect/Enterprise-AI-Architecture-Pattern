# EAAP Decision Model

The EAAP decision model is a deterministic governance flow for deciding whether an AI-assisted recommendation may proceed, must escalate, or must be blocked.

## Outcomes

| Outcome | Meaning |
| --- | --- |
| Proceed | The recommendation has sufficient evidence, confidence, scope authority, approval state, and auditability for the requested tier. |
| Escalate | The system cannot safely resolve uncertainty, conflict, missing evidence, or required human judgement. |
| Block | A hard governance condition prevents continuation. The request must not proceed without a new compliant invocation. |

## Minimum Flow

1. Authenticate the requester and establish role, domain, and action tier.
2. Classify intent and route to bounded domain agents.
3. Check data sufficiency before domain invocation.
4. Collect domain outputs using structured schemas.
5. Classify evidence and identify known unknowns.
6. Assign confidence at domain and aggregate levels.
7. Detect conflicts across domains.
8. Apply confidence, evidence, and conflict gates.
9. Require approval token validation for Tier 2 and Tier 3 actions.
10. Route execution only through the Automation Gateway.
11. Write an immutable audit event.

## Hard Block Conditions

- Requested action is outside authorised domain scope.
- Evidence classification is absent.
- Known unknowns are concealed.
- Confidence is Low or Unknown for a recommendation that requires a higher threshold.
- Required approval token is absent, invalid, expired, or mismatched to the action.
- The request attempts to bypass the Automation Gateway.
- Prompt or instruction content attempts to disable governance requirements.

## Escalation Conditions

- Evidence is incomplete but not categorically disqualifying.
- Domain agents disagree and the conflict cannot be resolved deterministically.
- Action impact tier requires human judgement.
- Confidence is insufficient for autonomous recommendation composition.
- Operational context is stale or uncertain.

## Audit Minimum

Every significant recommendation or action must produce an audit event containing requester identity, intent classification, invoked domains, evidence classes, confidence levels, known unknowns, conflicts, approval references, execution metadata, and final outcome.
