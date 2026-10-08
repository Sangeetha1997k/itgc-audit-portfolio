# Information Security Risk Assessment Methodology

## Purpose

This document defines the methodology used by BlueSky Technologies to identify,
analyze, evaluate, and prioritize information security risks as part of the ISMS.

This methodology supports ISO/IEC 27001:2022 Clause 6.1.2 requirements for
information security risk assessment.

---

## Risk Criteria

BlueSky Technologies establishes information security risk criteria by defining:

- Likelihood scoring
- Impact scoring
- Risk evaluation thresholds
- Risk acceptance criteria

These criteria are applied consistently to all information security risk assessments
to support objective and repeatable risk evaluation. Applying a common methodology
ensures that risk assessments produce consistent, valid, and comparable results
across the ISMS.

---

## Risk Identification

Information security risks are identified by considering:

- Information assets
- Business processes
- Technology dependencies
- Internal and external context (see `08-ISO27001-Context/ISMS-Scope.md`)
- Interested party requirements (see `08-ISO27001-Context/Interested-Parties-Register.xlsx`)
- Legal, regulatory, and contractual requirements
- Existing ITGC control testing results and audit observations

Examples:

- User accounts
- Customer data
- AWS infrastructure
- Production systems
- Third-party integrations

---

## Risk Analysis Approach

Each identified risk is evaluated on Likelihood and Impact, each scored on a
1-5 scale.

### Likelihood

The probability that a threat could exploit a vulnerability.

| Score | Description |
|---|---|
| 1 | Rare |
| 2 | Unlikely |
| 3 | Possible |
| 4 | Likely |
| 5 | Almost Certain |

### Impact

The potential business impact if the risk occurs. Impact considers
confidentiality, integrity, availability, customer impact, and regulatory impact.

| Score | Description |
|---|---|
| 1 | Insignificant |
| 2 | Minor |
| 3 | Moderate |
| 4 | Major |
| 5 | Severe |

---

## Risk Calculation

**Inherent Risk Score = Likelihood × Impact**

**Residual Risk Score = Reassessed Likelihood × Reassessed Impact**, determined after
considering existing controls (see Residual Risk Assessment).

Example: Likelihood 3, Impact 5 → Inherent Risk Score = 15

---

## Risk Evaluation

Analyzed risks are compared against the thresholds below and prioritized for
treatment.

| Score | Rating |
|---|---|
| 1-5 | Low |
| 6-10 | Medium |
| 11-19 | High |
| 20-25 | Critical |

---

## Risk Acceptance Criteria

| Rating | Acceptance Rule |
|---|---|
| Low (1-5) | Acceptable with routine monitoring. |
| Medium (6-10) | Acceptable with Risk Owner approval and a planned action. |
| High (11-19) | Treatment required. Temporary acceptance only by top management, with a time-bound plan. |
| Critical (20-25) | Treatment required immediately. Not acceptable. |

Accepted risks remain subject to monitoring and review.

---

## Residual Risk Assessment

Residual risk is the risk remaining after existing controls are considered. The
following principles apply:

- Controls primarily reduce the likelihood of a risk occurring. Impact is reduced
  only where the control directly limits the business consequence if the event occurs.
- Credit is given only for controls with supporting evidence. Controls that exist
  but have not been tested, or that are outside the audit scope, do not reduce
  residual risk.
- Where no reduction can be justified, residual risk equals inherent risk and the
  rationale is documented in the Risk Register.
- Control evidence is referenced to the ITGC workpapers. Conclusions based on
  interim testing do not represent full-year operating effectiveness.

---

## Risk Treatment Approach

The selected treatment decision is documented in the Risk Register together with
the planned action, risk owner, and action owner. Implementation progress is tracked through
the Improvement Action Tracker (`Improvement-Action-Tracker.xlsx`) within the
`13-Management-Review/` folder.

For risks requiring treatment, BlueSky selects one of the following options:

### Reduce
Apply controls to decrease likelihood or impact.
Example: Implement MFA to reduce account compromise risk.

### Accept
Management accepts the remaining risk.
Example: Low-impact risk with disproportionate remediation cost.

### Avoid
Stop the activity creating the risk.
Example: Disable an unnecessary exposed service.

### Share
Transfer part of the risk.
Example: Cyber insurance or contractual transfer.

---

## Risk Ownership

Each risk is assigned a Risk Owner and, where treatment is required, an Action Owner.

**Risk Owner:** The individual accountable for managing and accepting the information
security risk within their area of responsibility.

**Action Owner:** The individual or function responsible for implementing and tracking
approved risk treatment actions. The Action Owner may differ from the Risk Owner where
independent oversight or segregation of duties is required.

---

## Risk Review Frequency

Risk assessments are reviewed:

- At planned intervals
- When significant changes to business processes, technology, or regulatory
  requirements are proposed or occur
- Following significant information security incidents

---

## Related Portfolio References

- ISMS Scope and Context: `08-ISO27001-Context/ISMS-Scope.md`
- Interested Parties: `08-ISO27001-Context/Interested-Parties-Register.xlsx`
- Risk Register: `09-ISO27001-Risk-Assessment/ISO27001-Risk-Register.xlsx`
- ITGC control testing: `04-User-Access-Management/`, `05-Change-Management/`,
  `06-Computer-Operations/`
- ITGC audit observations: `07-Audit-Report/`
- Management review and action tracking: `13-Management-Review/`
