# Stage 08 · Risk Assessment

**Navigate:** [README](../README.md) · [1](01-context.md) · [2](02-interested-parties.md) · [3](03-scope.md) · [4](04-leadership.md) · [5](05-information-security-policy.md) · [6](06-roles-responsibilities.md) · [7](07-risk-methodology.md) · **8** · [9](09-risk-treatment-objectives.md) · [10](10-statement-of-applicability.md) · [11](11-control-implementation.md) · [12](12-evidence-collection.md) · [13](13-internal-audit.md) · [14](14-management-review.md) · [15](15-corrective-action.md) · [16](16-certification-readiness.md)

| | |
|---|---|
| **ISO 27001:2022 clause** | 6.1.2, 8.2 |
| **PDCA phase** | Plan |
| **Typical owner** | Risk owners with CISO |
| **Feeds** | Stages 9, 10, 11 |

## Purpose
Identify, analyse and evaluate the information security risks to in-scope assets using the approved methodology.

## What the standard requires
Apply the risk assessment process at planned intervals or when significant changes occur and retain documented information of results (8.2).

## Inputs (from earlier stages)
Scope, asset inventory, methodology, context register, threat information, previous incidents.

## Activities
1. Build the asset inventory and assign owners.
2. Identify threats and vulnerabilities per asset or process.
3. Score likelihood and impact; compute inherent risk.
4. Evaluate against acceptance criteria and rank.
5. Review with risk owners and challenge outliers.
6. Approve the register and baseline it.

## Deliverable
Asset inventory and Risk Register v1.0 ([risk-register.csv](../docs/risk-register.csv)).

## Worked example: Orbitwise Cloud Ltd (fictional)
Top risks by inherent score (full list with treatment in [risk-register.csv](../docs/risk-register.csv)):

| ID | Risk | Asset | L | I | Score | Level |
|---|---|---|---|---|---|---|
| R-01 | Customer payroll data exposed through misconfigured cloud storage | Production data stores | 3 | 5 | 15 | High |
| R-02 | Compromise of privileged cloud credentials | AWS accounts | 3 | 5 | 15 | High |
| R-04 | Phishing leads to staff account takeover | Identity provider | 4 | 4 | 16 | High |
| R-05 | Vulnerable third-party dependency exploited | Application code | 4 | 4 | 16 | High |
| R-06 | Sub-processor breach exposes customer data | Supplier ecosystem | 3 | 4 | 12 | High |
| R-03 | Ransomware destroys production database | Database cluster | 2 | 5 | 10 | Medium |

Output: 12 risks, 5 High, 6 Medium, 1 Low. Each has an owner, scenario and linked asset.

## Exit criteria
- [ ] Every in-scope asset class has at least one risk or a reason for none.
- [ ] Scores trace to the methodology descriptors.
- [ ] Owners accepted the ownership.
- [ ] The register carries a version and date.

## Common audit findings and how to avoid them
- Risks are generic ('hacking') with no asset or scenario.
- Register unchanged for a year despite incidents.
- Ownership never confirmed by the named owner.

---
[← Risk Assessment Methodology](07-risk-methodology.md) · [Risk Treatment and Security Objectives →](09-risk-treatment-objectives.md)
