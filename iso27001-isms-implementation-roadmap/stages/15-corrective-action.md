# Stage 15 · Nonconformity and Corrective Action

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · **15** · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 10.1, 10.2 |
| **PDCA phase** | Act |
| **Typical owner** | Finding owners, CISO |
| **Feeds** | Stages 13, 14, 16 |

## Purpose
Fix findings properly (cause, not symptom), confirm the fix works and improve the ISMS.

## What the standard requires
When a nonconformity occurs, react to it and take action to control and correct it; evaluate the need for action to eliminate causes; implement actions; review effectiveness; update risks and opportunities and change the ISMS if necessary. Retain documented information of the nature of nonconformities, actions taken and results (10.2). Continually improve suitability, adequacy and effectiveness (10.1).

## Inputs (from earlier stages)
Audit findings, incidents, management review actions, customer complaints.

## Activities
1. Log every finding with severity, owner and due date.
2. Contain and correct the immediate issue.
3. Run root cause analysis (5 Whys or fishbone) and document it.
4. Define corrective actions that remove the cause, and implement them.
5. Verify effectiveness after a set period.
6. Update the risk register, SoA and procedures if needed, then close.

## Deliverable
Corrective Action Register with root cause and effectiveness checks.

## Worked example: Orbitwise Cloud Ltd (fictional)
**CAR-02 (from IA-02, major): Restore test not performed**

| Field | Record |
|---|---|
| Correction | Restore test executed within 2 weeks in staging |
| Root cause | No named owner or calendar trigger for the test; backup monitoring checked success only |
| Corrective action | Owner assigned; semiannual test added to ISMS calendar; backup runbook updated with test steps |
| Effectiveness check | Second test passed RTO 3h 10m, RPO 40m; evidence EV-007 updated |
| Closed | Month 11, approved by CISO |

Metrics tracked: open findings by age, repeat findings, average closure time.

## Exit criteria
- [ ] Root cause, not restatement of the finding.
- [ ] Effectiveness reviewed, not assumed.
- [ ] Closed items link to evidence.
- [ ] Nothing open past its due date without an approved extension.

## Common audit findings and how to avoid them
- Corrections without root cause analysis.
- Findings closed on paper, not verified.
- Same finding recurs across audits.

---
[← Management Review](14-management-review.md) · [Certification Readiness →](16-certification-readiness.md)
