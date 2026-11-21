# Stage 13 · Internal Audit

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · **13** · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 9.2 |
| **PDCA phase** | Check |
| **Typical owner** | Independent auditor, audit programme by CISO |
| **Feeds** | Stages 14, 15, 16 |

## Purpose
Obtain an objective check that the ISMS conforms to the standard and to your own requirements, and find problems before the certification body does.

## What the standard requires
Conduct internal audits at planned intervals; define criteria and scope for each audit; select auditors to ensure objectivity and impartiality; report results to relevant management; retain documented information of the audit programme and results.

## Inputs (from earlier stages)
Evidence register, SoA, previous audit results, risk register.

## Activities
1. Approve an annual audit programme covering all clauses and applicable Annex A controls.
2. Choose independent auditors with ISO 27001 competence.
3. Prepare an audit plan, criteria and sampling approach per audit.
4. Fieldwork: interview, observe and sample records across the full period.
5. Grade findings (major, minor, opportunity for improvement) and agree them with auditees.
6. Issue the report and feed findings to corrective action and management review.

## Deliverable
Audit programme, audit plans, internal audit report and findings log.

## Worked example: Orbitwise Cloud Ltd (fictional)
**Audit 1 (month 9, external consultant, 4 days):** clauses 4-10 and a sample of 40 Annex A controls.

| Ref | Finding | Grade | Clause / control |
|---|---|---|---|
| IA-01 | Supplier annual reviews overdue for 3 of 9 critical suppliers | Minor | A.5.22 |
| IA-02 | Objectives measured but OBJ-4 restore test not yet performed | Major | 6.2, 9.1 |
| IA-03 | Management review not yet scheduled | Major | 9.3 |
| IA-04 | Access review evidence lacks removal confirmation | Minor | A.5.18 |
| IA-05 | Clear desk checks not recorded in Manchester | Minor | A.7.7 |
| OFI-1 | Automate evidence capture from IAM and ticketing | OFI | 9.1 |

Conclusion: not yet ready; two majors and three minors to close before management review and the certification stage 1.

## Exit criteria
- [ ] Auditor is independent of the areas audited.
- [ ] All clauses are audited at least once per cycle and high-risk controls more often.
- [ ] Findings cite the requirement and the evidence examined.
- [ ] Reports reach top management.

## Common audit findings and how to avoid them
- Internal audit done by the person who built the ISMS.
- Audit only checks documents, not operation.
- Findings not tracked to closure.

---
[← Evidence Collection](12-evidence-collection.md) · [Management Review →](14-management-review.md)
