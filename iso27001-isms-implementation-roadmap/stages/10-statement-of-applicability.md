# Stage 10 · Statement of Applicability

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · **10** · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 6.1.3 d |
| **PDCA phase** | Plan |
| **Typical owner** | CISO |
| **Feeds** | Stages 11, 13, 16 |

## Purpose
Record the decision for every Annex A control: included or excluded, why, and whether it is implemented. The SoA is the audit's master checklist.

## What the standard requires
Produce a Statement of Applicability that contains the necessary controls, justification for their inclusion, whether they are implemented, and justification for excluding any Annex A controls. ISO 27001:2022 Annex A has 93 controls in four themes: Organizational (37), People (8), Physical (14), Technological (34).

## Inputs (from earlier stages)
Risk treatment plan, legal register, customer requirements, Annex A.

## Activities
1. List all 93 Annex A controls.
2. For each, record Applicable yes or no.
3. Give the basis for selection (risk, legal, contractual, good practice).
4. Record implementation status and link to the risk IDs and policy or procedure.
5. Justify each exclusion; challenge exclusions that look convenient.
6. Approve and version the SoA; any change goes through change control.

## Deliverable
Statement of Applicability v1.0 ([soa.csv](../docs/soa.csv)).

## Worked example: Orbitwise Cloud Ltd (fictional)
Summary of the Orbitwise SoA at approval: see [soa.csv](../docs/soa.csv) for all 93 rows.

| Theme | Controls | Applicable | Excluded |
|---|---|---|---|
| Organizational (5.x) | 37 | 37 | 0 |
| People (6.x) | 8 | 8 | 0 |
| Physical (7.x) | 14 | 13 | 1 (7.6) |
| Technological (8.x) | 34 | 33 | 1 (8.30) |
| **Total** | **93** | **91** | **2** |

**Exclusions:** 7.6 Working in secure areas: no secure areas exist in scope; sensitive work happens on managed endpoints and cloud. 8.30 Outsourced development: all development is in-house; reviewed if the policy changes.

## Exit criteria
- [ ] All 93 controls appear with a decision.
- [ ] Every exclusion has a reason an auditor can test.
- [ ] Each applicable control links to a risk, legal or contractual basis.
- [ ] SoA status matches what is truly implemented, not what is hoped.

## Common audit findings and how to avoid them
- SoA lists controls as implemented that are only planned.
- Exclusions without justification.
- SoA not updated after the risk treatment plan changed.

---
[← Risk Treatment and Security Objectives](09-risk-treatment-objectives.md) · [Control Implementation →](11-control-implementation.md)
