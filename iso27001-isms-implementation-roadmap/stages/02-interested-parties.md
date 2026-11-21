# Stage 02 · Interested Parties and Their Requirements

**Navigate:** [README](../README.md) · [1](01-context.md) · **2** · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 4.2 |
| **PDCA phase** | Plan |
| **Typical owner** | CISO, Legal, Head of People |
| **Feeds** | Stages 3, 7, 9, 10 |

## Purpose
Identify who has security expectations of the organization and which of those become compliance obligations the ISMS must meet.

## What the standard requires
Determine interested parties relevant to the ISMS, their relevant requirements, and which of those requirements will be addressed through the ISMS. Amendment 1:2024 adds: whether climate change is addressed in those requirements.

## Inputs (from earlier stages)
Stage 1 context register, customer contracts, legal register, supplier list.

## Activities
1. Brainstorm parties: customers, regulators, employees, suppliers, owners, insurers, certification body.
2. Capture each party's expectations from contracts, law, questionnaires and interviews.
3. Separate requirements into legal, contractual and voluntary.
4. Decide which requirements the ISMS addresses and how.
5. Build the legal and contractual register that feeds Annex A 5.31.

## Deliverable
Interested Parties Register and Legal, Regulatory and Contractual Register.

## Worked example: Orbitwise Cloud Ltd (fictional)
| Party | Requirement | Type | Addressed by |
|---|---|---|---|
| Bank customers | ISO 27001 certificate, breach notice within 24 hours, annual audit rights | Contractual | Stage 16, A.5.26, A.5.35 |
| Qatar data protection authority | PDPPL controller/processor duties, breach notification | Legal | A.5.34, A.5.31 |
| UK ICO | UK GDPR/DPA 2018, 72-hour breach notice to regulator | Legal | A.5.34, A.5.26 |
| Employees | Fair handling of HR data, clear acceptable use rules | Voluntary and legal | A.6.2, A.5.10 |
| AWS | Shared responsibility model, acceptable use policy | Contractual | A.5.23 |
| Cyber insurer | Multi-factor authentication and backups for cover | Contractual | A.8.5, A.8.13 |
| Certification body | Access to evidence and staff during audits | Voluntary | Stage 16 |

## Exit criteria
- [ ] Every legal and contractual requirement has an owner and a mapped control or process.
- [ ] Customer contract clauses were read, not assumed.
- [ ] Register has a review date.

## Common audit findings and how to avoid them
- Customer notification deadlines in contracts conflict with the internal incident procedure.
- Legal register lists laws but not which controls satisfy them.

---
[← Context of the Organization](01-context.md) · [ISMS Scope →](03-scope.md)
