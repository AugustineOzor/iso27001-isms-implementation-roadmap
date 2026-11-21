# Stage 06 · Roles, Responsibilities and Authorities

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · **6** · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 5.3 |
| **PDCA phase** | Plan |
| **Typical owner** | CISO and Head of People |
| **Feeds** | Stages 7, 9, 11, 13 |

## Purpose
Assign and communicate who does what in the ISMS so that risks, controls and corrective actions have named owners.

## What the standard requires
Top management shall ensure responsibilities and authorities for roles relevant to information security are assigned and communicated, including responsibility to ensure the ISMS conforms to the standard and to report ISMS performance to top management.

## Inputs (from earlier stages)
Organization chart, policy, scope, Annex A control themes.

## Activities
1. List ISMS activities (risk assessment, audits, incident handling, training, supplier review).
2. Assign Responsible, Accountable, Consulted, Informed roles in a RACI.
3. Name the ISMS Manager (CISO) and give written authority to report to top management.
4. Embed responsibilities in job descriptions and onboarding.
5. Check competence needs for each role (clause 7.2) and plan training.
6. Publish the RACI and review after any reorganization.

## Deliverable
ISMS RACI matrix, role descriptions and competence records.

## Worked example: Orbitwise Cloud Ltd (fictional)
R = Responsible, A = Accountable, C = Consulted, I = Informed.

| ISMS activity | CEO | CISO | CTO | Head of People | Legal | Risk owners |
|---|---|---|---|---|---|---|
| Approve policy and objectives | A | R | C | C | C | I |
| Risk assessment | I | A | C | I | C | R |
| Risk treatment plan approval | I | R | C | I | I | A |
| Control implementation (technical) | I | A | R | I | I | C |
| Joiner/leaver security | I | C | I | A/R | I | I |
| Incident response | I | A | R | C | C | I |
| Internal audit | I | A | I | I | I | C |
| Management review | A | R | C | C | C | I |

Internal audit independence: the CISO owns the programme but audits of CISO-run processes are performed by an external auditor.

## Exit criteria
- [ ] Each ISMS process has exactly one accountable person.
- [ ] No person audits their own work.
- [ ] Staff can name their security responsibilities when asked.

## Common audit findings and how to avoid them
- RACI exists but roles in practice differ.
- Risk owners are IT staff rather than business owners.
- Internal auditor reviews controls they implemented.

---
[← Information Security Policy](05-information-security-policy.md) · [Risk Assessment Methodology →](07-risk-methodology.md)
