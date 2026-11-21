# Dependency Map

**Navigate:** [README](../README.md) · [Traceability](traceability-matrix.md)

Each stage consumes the output of the stage before it. This table shows what each stage needs, what it produces, and what typically goes wrong when it is done out of order.

| Stage | Needs | Produces | Cost of skipping or reordering |
|---|---|---|---|
| [01 Context of the Organization](../stages/01-context.md) | Business plan, contracts | Issues register | Risk criteria not anchored to the business; findings on 4.1 |
| [02 Interested Parties and Their Requirements](../stages/02-interested-parties.md) | Issues register, contracts, law | Interested parties and legal register | Missed customer or legal duties surface late as control gaps |
| [03 ISMS Scope](../stages/03-scope.md) | Stages 1-2, architecture | Scope statement | Assessing the wrong assets, then redoing the risk work |
| [04 Leadership and Commitment](../stages/04-leadership.md) | Scope, business case | Mandate, budget, steering committee | Work stalls waiting for resources and decisions |
| [05 Information Security Policy](../stages/05-information-security-policy.md) | Stages 1-4 | Approved policy | Objectives and procedures have no authority to hang from |
| [06 Roles, Responsibilities and Authorities](../stages/06-roles-responsibilities.md) | Policy, scope | RACI, role authority | Risks and controls without owners; nobody accountable |
| [07 Risk Assessment Methodology](../stages/07-risk-methodology.md) | Stages 1-6 | Approved risk methodology | Results look manipulated if criteria are written after scoring |
| [08 Risk Assessment](../stages/08-risk-assessment.md) | Scope, methodology, assets | Risk register | Controls chosen by habit rather than by risk |
| [09 Risk Treatment and Security Objectives](../stages/09-risk-treatment-objectives.md) | Risk register | Treatment plan and objectives | No evidence controls are proportionate; unowned residual risk |
| [10 Statement of Applicability](../stages/10-statement-of-applicability.md) | Treatment plan, Annex A | Statement of Applicability | Controls without justification; unsupported exclusions |
| [11 Control Implementation](../stages/11-control-implementation.md) | Treatment plan, SoA | Operating controls | Documents describe controls that do not exist |
| [12 Evidence Collection](../stages/12-evidence-collection.md) | Operating controls | Evidence register, scorecard | Cannot prove operation; last-minute screenshots |
| [13 Internal Audit](../stages/13-internal-audit.md) | Evidence, SoA | Audit report | Certification body finds the issues instead of you |
| [14 Management Review](../stages/14-management-review.md) | Audit, scorecard, risks | Decisions and actions | Leadership has no recorded oversight; major finding on 9.3 |
| [15 Nonconformity and Corrective Action](../stages/15-corrective-action.md) | Findings, actions | Closed, verified fixes | Repeat findings; stage 2 majors |
| [16 Certification Readiness](../stages/16-certification-readiness.md) | All stages | Certification decision | Booking audits before evidence exists |

## Three sequences auditors will test

1. **Scope before risk.** Assets outside the scope boundary should not appear in the register, and in-scope assets must not be missing.
2. **Risk before controls.** Every Annex A decision in the SoA should trace to a risk, a legal requirement or a contractual requirement.
3. **Operate before audit.** Internal audit and management review need real operating evidence, and both should happen before the certification body arrives.

## Feedback loops

The roadmap is linear for first implementation but cyclical in operation: findings (stage 15) and management review decisions (stage 14) feed back into context (stage 1), risk assessment (stage 8) and the SoA (stage 10). Changes follow clause 6.3 planning of changes.
