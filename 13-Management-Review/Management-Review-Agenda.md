# Management Review Agenda

## Meeting Details

| Item | Detail |
|---|---|
| Organization | BlueSky Technologies (Fictional) |
| Meeting | ISMS Management Review (first review), Clause 9.3 |
| Date | 12 June 2026 |
| Chair | Top Management |
| Prepared by | IT Manager |
| Purpose | Review the suitability, adequacy and effectiveness of the ISMS and record decisions on risk treatment and improvement |

## Attendees (by role)

| Role | Reason for attendance |
|---|---|
| Top Management (chair) | Clause 9.3.1: conducts the review |
| IT Manager | Risk owner: R-002, R-003, R-004, R-008, R-009 |
| Application Owners | Risk owner: R-001 |
| Engineering Manager | Risk owner: R-005, R-011 |
| Infrastructure Operations | Risk owner: R-006, R-007, R-010 |
| IAM Administrator | Risk owner: R-012 |
| Internal Auditor (IT Audit) | Presents the internal audit results |

The Security/Compliance function does not yet exist (see SoA control 5.35) and is
therefore not represented.

## Evidence Cut-off

The audit report is dated 22 May 2026. This meeting follows it, and decisions recorded
at this meeting are follow-up evidence that does not change the audit conclusion as of
22 May 2026.

---

## Clause 9.3.2 Inputs

| Ref | Required input | Source |
|---|---|---|
| a | Status of actions from previous management reviews | None. This is the first review. |
| b | Changes in external and internal issues | `08-ISO27001-Context/ISMS-Scope.md` |
| c | Changes in needs and expectations of interested parties | `08-ISO27001-Context/Interested-Parties-Register.xlsx` |
| d(1) | Trends in nonconformities and corrective actions | `12-ISO27001-Internal-Audit/Internal-Audit-Report.md` (ISO-001 to ISO-005) |
| d(2) | Monitoring and measurement results | `07-Audit-Report/` (ITGC interim testing, Q1 2026) |
| d(3) | Audit results | `12-ISO27001-Internal-Audit/` and `07-Audit-Report/` |
| d(4) | Fulfilment of information security objectives | No documented information security objectives (Clause 6.2) are held in the ISMS records. Status and management's decision are recorded in the minutes. |
| e | Feedback from interested parties | None recorded |
| f | Results of risk assessment and status of risk treatment plan | `09-ISO27001-Risk-Assessment/ISO27001-Risk-Register.xlsx`; `11-ISO27001-Statement-of-Applicability/SoA.xlsx` |
| g | Opportunities for continual improvement | Observations ISO-003 to ISO-005; recommendations in the audit reports |

---

## Agenda

| No. | Item | Presenter | Input |
|---|---|---|---|
| 1 | Opening, attendance, purpose and evidence cut-off | Chair | None |
| 2 | Status of previous actions | Chair | a |
| 3 | Changes in context and interested party requirements | IT Manager | b, c, e |
| 4 | Information security performance: ITGC interim results (Q1 2026) and status of information security objectives | IT Manager | d(2), d(3), d(4) |
| 5 | Internal audit results: 26 checks, 5 findings (ISO-001 to ISO-005) | Internal Auditor | d(1), d(3) |
| 6 | Risk assessment results: 12 risks, inherent and residual ratings | IT Manager | f |
| 7 | **Risk owner decisions on treatment and residual risk for all 12 risks** | Each risk owner | f |
| 8 | Controls marked Planned in the SoA: 5.35, 8.9, 8.25, 8.28 | IT Manager | f |
| 9 | Opportunities for improvement | All | g |
| 10 | Decisions on ISMS changes, actions and owners; interval for the next review | Chair | Clause 9.3.3 |

### Item 7: decisions required

Each risk owner states whether the treatment plan is approved and whether the residual
risk is accepted, using the acceptance rules in the Risk Assessment Methodology:

| Residual rating | Acceptance rule |
|---|---|
| Low (1-5) | Acceptable with routine monitoring |
| Medium (6-10) | Acceptable with Risk Owner approval and a planned action |
| High (11-19) | Treatment required; temporary acceptance only by top management with a time-bound plan |
| Critical (20-25) | Treatment required immediately; not acceptable |

Residual ratings for discussion: 4 Low, 7 Medium, 1 High (R-010).

---

## Pre-reading

- `12-ISO27001-Internal-Audit/Internal-Audit-Report.md`
- `07-Audit-Report/README.md`
- `09-ISO27001-Risk-Assessment/ISO27001-Risk-Register.xlsx`
- `11-ISO27001-Statement-of-Applicability/SoA.xlsx`

---

## Outputs

Decisions are recorded in `Management-Review-Minutes.md`, and actions are tracked in
`Improvement-Action-Tracker.xlsx`.

---

## Related Documents

- `Management-Review-Minutes.md`
- `Improvement-Action-Tracker.xlsx`
- `12-ISO27001-Internal-Audit/`
- `09-ISO27001-Risk-Assessment/`
- `11-ISO27001-Statement-of-Applicability/`
