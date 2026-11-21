# Stage 07 · Risk Assessment Methodology

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · **7** · [8](08-risk-assessment.md) · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 6.1.2 |
| **PDCA phase** | Plan |
| **Typical owner** | CISO |
| **Feeds** | Stages 8, 9 |

## Purpose
Fix the rules before assessing: scales, criteria, acceptance threshold and risk owners. A method defined after the results look suspiciously convenient.

## What the standard requires
Define and apply a risk assessment process that establishes and maintains risk acceptance criteria and criteria for performing assessments, ensures repeated assessments produce consistent, valid and comparable results, identifies risks of losing confidentiality, integrity and availability, identifies risk owners, analyses and evaluates risks. Retain documented information about the process.

## Inputs (from earlier stages)
Context, interested parties, scope, roles, risk appetite from leadership.

## Activities
1. Choose the approach (asset-based, scenario-based or hybrid).
2. Define likelihood and impact scales with concrete descriptors.
3. Define the risk matrix and risk levels.
4. Set the acceptance criteria and who may accept which level.
5. Define frequency and triggers for reassessment.
6. Pilot on two assets to test consistency, then approve the method.

## Deliverable
Risk Assessment and Treatment Methodology v1.0.

## Worked example: Orbitwise Cloud Ltd (fictional)
Approach: asset-based with threat and vulnerability scenarios. Risk score = Likelihood x Impact (each 1-5).

| Score | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| **Likelihood** | Rare (<1 in 5 yrs) | Unlikely (1 in 2-5 yrs) | Possible (yearly) | Likely (quarterly) | Almost certain (monthly) |
| **Impact** | Negligible | Minor: under 1 day disruption, no data exposure | Moderate: customer-visible outage, limited personal data | Major: multi-customer data exposure or regulatory notification | Severe: large-scale breach, loss of key banking customers |

| Risk level | Score | Acceptance authority | Action |
|---|---|---|---|
| Low | 1-5 | Risk owner | May accept; monitor |
| Medium | 6-11 | Risk owner with CISO | Treat or accept with written justification |
| High | 12-19 | CISO, reported to Steering Committee | Treatment plan mandatory |
| Critical | 20-25 | CEO | Immediate treatment; escalate |

Reassessment: annually, and after major change, incident or new threat.

## Exit criteria
- [ ] Two assessors scoring the same risk land within one level of each other.
- [ ] Acceptance criteria are approved by top management.
- [ ] Scales are tied to business facts such as customers, regulators and downtime.

## Common audit findings and how to avoid them
- No defined acceptance criteria.
- Methodology says one thing; the risk register does another.
- Risks owned by 'IT' rather than a named person.

---
[← Roles, Responsibilities and Authorities](06-roles-responsibilities.md) · [Risk Assessment →](08-risk-assessment.md)
