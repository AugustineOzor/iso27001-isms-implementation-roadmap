# Stage 03 · ISMS Scope

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · **3** · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 4.3 (and 4.4) |
| **PDCA phase** | Plan |
| **Typical owner** | CISO, approved by CEO |
| **Feeds** | Stages 7, 8, 10, 16 |

## Purpose
Define the boundary of the ISMS. Scope fixes which assets, locations and processes you must assess, so getting it wrong inflates audit work or lets in claims you cannot support.

## What the standard requires
Determine the boundaries and applicability of the ISMS, considering context (4.1), requirements (4.2) and interfaces and dependencies with activities performed by other organizations. Scope must be available as documented information.

## Inputs (from earlier stages)
Stage 1 issues, stage 2 requirements, organization chart, system architecture, supplier list.

## Activities
1. Choose the products, services, sites, teams and technologies in scope.
2. Draw the boundary on an architecture diagram and mark every interface.
3. List exclusions with a written reason; exclusions must not undermine customer assurance.
4. Record dependencies on third parties (cloud, payment, support tools).
5. Write the scope statement and get CEO approval.
6. Establish the ISMS (4.4): confirm processes and interactions needed to operate it.

## Deliverable
ISMS Scope Statement with boundary diagram.

## Worked example: Orbitwise Cloud Ltd (fictional)
**Scope statement.** The ISMS covers the design, development, operation and support of the Orbitwise Payroll & HR SaaS platform, including its AWS production, staging and backup environments, the CI/CD pipeline, customer support tooling, and the people and processes at the Doha headquarters, Manchester office and remote staff, in accordance with the Statement of Applicability v1.0.

| Item | Decision | Reason |
|---|---|---|
| Production SaaS platform (AWS eu-west-2, me-south-1) | In | Core service |
| Corporate laptops and SSO | In | Access path to production |
| Marketing website (agency hosted) | Out | No customer data; separate hosting, no connection to platform |
| Legacy PayLite product | Out | Retiring in 6 months; no new customers; tracked as risk R-12 |
| AWS data centers | Interface | Covered by supplier management (A.5.23), AWS ISO 27001 certificate on file |

## Exit criteria
- [ ] Scope names assets, locations and processes explicitly.
- [ ] Every exclusion has a justification and the exclusion list is consistent with the certificate wording.
- [ ] Interfaces and dependencies are shown, not implied.
- [ ] Scope statement is word-for-word what will appear on the certificate.

## Common audit findings and how to avoid them
- Scope mentions 'the company' without a boundary.
- Shadow systems used by in-scope staff were left out.
- Scope statement differs between the policy, SoA and sales material.

---
[← Interested Parties and Their Requirements](02-interested-parties.md) · [Leadership and Commitment →](04-leadership.md)
