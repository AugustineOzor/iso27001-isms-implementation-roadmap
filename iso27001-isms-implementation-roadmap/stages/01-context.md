# Stage 01 · Context of the Organization

**Navigate:** [README](../README.md) · **1** · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 4.1 |
| **PDCA phase** | Plan |
| **Typical owner** | CISO with executive team |
| **Feeds** | Stages 2, 3, 7 |

## Purpose
Establish the internal and external issues that shape what the ISMS must achieve. Every later decision (scope, risk criteria, control choice) is justified against this context.

## What the standard requires
Determine external and internal issues relevant to the ISMS's purpose and that affect its ability to achieve intended outcomes. Amendment 1:2024 adds: determine whether climate change is a relevant issue.

## Inputs (from earlier stages)
Business plan, strategy, customer contracts, regulatory register, previous audit or incident reports.

## Activities
1. Interview executives on strategy, growth plans and what a security failure would cost.
2. List external issues (legal, market, threat landscape, technology, supply chain, climate) using PESTLE.
3. List internal issues (structure, culture, capability, legacy systems, tooling, resources) using SWOT.
4. Rate each issue by relevance to confidentiality, integrity and availability.
5. Record the climate change relevance decision with a reason, even if the answer is no.
6. Approve the register and set a review trigger (annual review or material change).

## Deliverable
Context and Issues Register (version-controlled document).

## Worked example: Orbitwise Cloud Ltd (fictional)
**Orbitwise Cloud Ltd** is a fictional B2B SaaS company (payroll and HR platform, 140 staff, HQ Doha, engineering hub Manchester, hosted on AWS) selling to banks and telecoms in the GCC and UK.

| ID | Type | Issue | Relevance to ISMS | Feeds |
|---|---|---|---|---|
| CTX-01 | External | Bank customers require ISO 27001 certification in tenders | Commercial driver; sets certification target | Stage 16 |
| CTX-02 | External | Qatar PDPPL (Law 13 of 2016) and UK GDPR apply to employee data we process | Legal obligations on personal data | Stage 2, 9 |
| CTX-03 | External | Ransomware and credential-theft campaigns targeting SaaS providers | Threat input to risk assessment | Stage 8 |
| CTX-04 | External | Climate change: AWS regions have resilience commitments; Doha office exposed to extreme heat | Assessed: low relevance for hosted service, medium for office power and cooling | Stage 8 |
| CTX-05 | Internal | Rapid hiring (40 staff in 12 months), uneven onboarding | Awareness and joiner controls | Stage 11 |
| CTX-06 | Internal | Engineering uses ad hoc scripts for infrastructure changes | Change and configuration risk | Stage 8 |
| CTX-07 | Internal | No dedicated security team; CISO plus two analysts | Resource constraint shaping control rollout | Stage 4, 11 |

## Exit criteria
- [ ] Each issue states why it matters to the ISMS, not just that it exists.
- [ ] Climate change decision is recorded.
- [ ] Executive sponsor has reviewed and approved.
- [ ] Issues are traceable into at least one later artifact (risk, objective or control).

## Common audit findings and how to avoid them
- Context is a generic SWOT copied from a template with no link to risks (clause 4.1 nonconformity).
- Climate change not considered after Amendment 1:2024.
- Register never reviewed after an acquisition or major product change.

---
[← README](../README.md) · [Interested Parties and Their Requirements →](02-interested-parties.md)
