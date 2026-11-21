# Stage 09 · Risk Treatment and Security Objectives

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · **9** · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 6.1.3, 6.2, 6.3 |
| **PDCA phase** | Plan |
| **Typical owner** | Risk owners, CISO |
| **Feeds** | Stages 10, 11, 14 |

## Purpose
Decide what to do about each risk, select the controls that do it, and set measurable objectives that prove the ISMS works.

## What the standard requires
Select treatment options, determine all controls necessary, compare with Annex A to confirm none are omitted, produce a Statement of Applicability, formulate a risk treatment plan and obtain risk owner approval of the plan and residual risk acceptance (6.1.3). Establish measurable objectives with plans for what, resources, who, when and how evaluated (6.2). Plan changes to the ISMS in a controlled way (6.3, added by Amendment 1:2024).

## Inputs (from earlier stages)
Risk register, methodology, legal register, resource constraints.

## Activities
1. Choose a treatment for each risk: modify (add controls), avoid, share (transfer) or retain.
2. Select candidate controls from Annex A and any other source.
3. Estimate residual risk and check it meets the acceptance criteria.
4. Write the risk treatment plan with owners, dates and cost.
5. Obtain risk owner sign-off of the plan and residual risk.
6. Define SMART objectives tied to risks and approve them with leadership.

## Deliverable
Risk Treatment Plan and Information Security Objectives.

## Worked example: Orbitwise Cloud Ltd (fictional)
**Treatment extract**

| Risk | Treatment | Selected controls | Residual L x I | Residual level | Owner |
|---|---|---|---|---|---|
| R-01 | Modify | A.8.9, A.8.3, A.5.15, A.8.15 | 2 x 5 = 10 | Medium | CTO |
| R-02 | Modify | A.8.2, A.8.5, A.5.17, A.8.16 | 2 x 5 = 10 | Medium | CTO |
| R-04 | Modify | A.6.3, A.8.5, A.8.7, A.8.23 | 3 x 3 = 9 | Medium | CISO |
| R-06 | Modify, share | A.5.19-A.5.22, A.5.23, cyber insurance | 2 x 4 = 8 | Medium | Head of Legal |
| R-11 | Retain | None; monitored | 2 x 2 = 4 | Low | Head of People |

**Objectives (annual)**

| ID | Objective | Measure | Target | Linked risk |
|---|---|---|---|---|
| OBJ-1 | Protect privileged access | % privileged accounts with phishing-resistant MFA | 100% by month 9 | R-02 |
| OBJ-2 | Remediate vulnerabilities fast | Critical findings fixed within 7 days | at least 95% | R-05 |
| OBJ-3 | Build awareness | Training completion and phishing click rate | 95% complete, under 8% click | R-04 |
| OBJ-4 | Prove recoverability | Restore test meets RTO 4h and RPO 1h | 2 tests per year | R-03 |
| OBJ-5 | Respond promptly | Severity 1 incidents triaged within 1 hour | 100% | R-09 |
| OBJ-6 | Manage suppliers | Critical suppliers assessed before onboarding and yearly | 100% | R-06 |

## Exit criteria
- [ ] Residual risk is below the acceptance line or explicitly accepted by an authorized owner.
- [ ] Each objective is measurable, owned, dated and traceable to a risk or requirement.
- [ ] Treatment plan has budget and dates, not intent alone.

## Common audit findings and how to avoid them
- Treatment plan not approved by risk owners.
- Objectives are statements like 'improve security' with no metric.
- Controls chosen with no link to risks.

---
[← Risk Assessment](08-risk-assessment.md) · [Statement of Applicability →](10-statement-of-applicability.md)
