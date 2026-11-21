# Stage 11 · Control Implementation

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · **11** · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 8.1, 8.3 |
| **PDCA phase** | Do |
| **Typical owner** | Control owners, CTO, CISO |
| **Feeds** | Stages 12, 13 |

## Purpose
Put the selected controls into production and make the treatment plan real. This is the longest stage; sequence it by risk.

## What the standard requires
Plan, implement and control the processes needed to meet requirements and implement the actions from 6.1; keep documented information to the extent necessary to have confidence processes were carried out as planned; control planned changes and outsourced processes (8.1). Implement the risk treatment plan and retain results (8.3).

## Inputs (from earlier stages)
Risk treatment plan, SoA, policies, RACI, budget.

## Activities
1. Group controls into waves by risk reduction and effort.
2. Write or update policies, standards and procedures for each control.
3. Configure technical controls and integrate them into existing workflows.
4. Assign a control owner and an operating frequency to each control.
5. Track delivery weekly and re-score residual risk as controls land.
6. Control changes and confirm outsourced processes are covered by contracts.

## Deliverable
Implemented controls, supporting policies and procedures, implementation tracker.

## Worked example: Orbitwise Cloud Ltd (fictional)
| Wave | Months | Focus | Example controls | Risks reduced |
|---|---|---|---|---|
| 1 Quick wins and high risk | 1-3 | Identity, cloud baseline, backups | A.8.5, A.8.2, A.8.9, A.8.13, A.8.15 | R-01, R-02, R-03 |
| 2 People and process | 3-6 | Awareness, onboarding, supplier, incident | A.6.1, A.6.3, A.5.19-5.22, A.5.24-5.27 | R-04, R-06, R-09 |
| 3 Engineering assurance | 4-8 | Secure SDLC, vulnerability management, change | A.8.8, A.8.25-A.8.29, A.8.32 | R-05, R-10 |
| 4 Physical and residual | 6-9 | Offices, endpoint, remaining policies | A.7.x, A.8.1, A.5.10-5.14 | R-08, R-11 |

Tracker fields: control ID, owner, policy/procedure link, status, go-live date, evidence ID, residual risk impact.

## Exit criteria
- [ ] Each control has a named owner, a description of how it operates and a frequency.
- [ ] Procedures match what staff actually do.
- [ ] Changes to the ISMS follow change control.

## Common audit findings and how to avoid them
- Policies exist but the technical configuration does not match.
- Controls implemented once and never operated again.
- Outsourced process not controlled by contract.

---
[← Statement of Applicability](10-statement-of-applicability.md) · [Evidence Collection →](12-evidence-collection.md)
