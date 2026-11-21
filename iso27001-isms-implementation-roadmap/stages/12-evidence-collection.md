# Stage 12 · Evidence Collection

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · **12** · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 7.5, 9.1 |
| **PDCA phase** | Do |
| **Typical owner** | Control owners, ISMS Manager |
| **Feeds** | Stages 13, 14, 16 |

## Purpose
Prove each control operates over time. Auditors test evidence of operation, not design documents.

## What the standard requires
Retain documented information as evidence of results (7.5); determine what needs monitoring and measurement, methods, when, by whom, and evaluate performance and effectiveness (9.1). Documented information must be identified, adequately protected, controlled for access, distribution, retention and change.

## Inputs (from earlier stages)
Implemented controls, objectives, SoA.

## Activities
1. Define for each control what evidence proves operation and how often it is produced.
2. Prefer system-generated evidence (tickets, logs, reports) over screenshots.
3. Create an evidence register with source, owner, frequency and location.
4. Automate collection where possible and spot-check quality monthly.
5. Track objective metrics in a monthly ISMS scorecard.
6. Apply document control: version, owner, review date, retention.

## Deliverable
Evidence Register and monthly ISMS scorecard.

## Worked example: Orbitwise Cloud Ltd (fictional)
| Evidence ID | Control | Evidence | Source | Frequency | Owner |
|---|---|---|---|---|---|
| EV-001 | A.5.18 | Quarterly user access review with removals | IAM export plus ticket | Quarterly | CTO |
| EV-004 | A.8.8 | Vulnerability scan report and remediation SLA report | Scanner | Weekly | CISO |
| EV-007 | A.8.13 | Backup success logs and restore test record | Backup service | Daily / semiannual | Infra lead |
| EV-011 | A.6.3 | Training completion report and phishing simulation results | LMS | Monthly | Head of People |
| EV-015 | A.5.19 | Supplier risk assessment and contract security addendum | Supplier register | Per onboarding / annual | Head of Legal |
| EV-020 | A.5.26 | Incident ticket with timeline and closure review | Ticketing | Per incident | CISO |

Evidence rules: dated, attributable to a person or system, taken from the system of record, covers the full audit period, and shows the control working (not only configured).

## Exit criteria
- [ ] Each applicable control has at least one operating record covering several months.
- [ ] Evidence is retrievable within minutes during an audit.
- [ ] Metrics in the scorecard are calculated the same way each month.

## Common audit findings and how to avoid them
- Controls only evidenced by a policy document.
- Evidence gathered in a rush the week before the audit.
- Access review performed once with no removals followed up.

---
[← Control Implementation](11-control-implementation.md) · [Internal Audit →](13-internal-audit.md)
