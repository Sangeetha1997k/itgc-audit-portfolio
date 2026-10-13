# Management Review Minutes

## Meeting Details

| Item | Detail |
|---|---|
| Organization | BlueSky Technologies (Fictional) |
| Meeting | ISMS Management Review (first review), Clause 9.3 |
| Date | 12 June 2026 |
| Chair | Top Management |
| Minutes prepared by | IT Manager |
| Agenda | `Management-Review-Agenda.md` |

## Attendance (by role)

| Role | Present |
|---|---|
| Top Management (chair) | Yes |
| IT Manager | Yes |
| Application Owners | Yes |
| Engineering Manager | Yes |
| Infrastructure Operations | Yes |
| IAM Administrator | Yes |
| Internal Auditor (IT Audit) | Yes (presented audit results) |

## Evidence Cut-off

The internal audit report is dated 22 May 2026. The decisions below were made after
that date and are follow-up evidence. They do not change the audit conclusion as of
22 May 2026.

---

## 1. Discussion of Inputs (Clause 9.3.2)

| Agenda item | Input | Summary |
|---|---|---|
| 2 | Status of previous actions (a) | First review. No previous actions. |
| 3 | Changes in issues, interested parties and feedback (b, c, e) | No changes to external or internal issues, no changes to interested party requirements, and no interested party feedback were recorded. |
| 4 | ITGC interim results (d2, d3) | Eight ITGC controls were tested using Q1 2026 interim evidence. No operating exceptions were identified in the Q1 2026 populations tested. One design observation was raised concerning segregation of duties in privileged access review (UAM-04). The results are interim and do not establish full-year operating effectiveness. |
| 4 | Information security objectives (d4) | No documented information security objectives (Clause 6.2) were available for review, so fulfilment could not be evaluated. Top Management decided that objectives are to be established (see section 5). |
| 5 | Internal audit results (d1, d3) | 26 checks: 20 conform, 4 observations, 2 minor nonconformities (ISO-001, ISO-002). No major nonconformities. |
| 6 | Risk assessment results (f) | 12 risks. Inherent: 5 High, 7 Medium. Residual: 1 High (R-010), 7 Medium, 4 Low. |

---

## 2. Risk Owner Decisions (Agenda Item 7)

Decisions follow the acceptance rules in the Risk Assessment Methodology.

| Risk | Risk Owner | Residual | Rating | Treatment plan | Residual risk decision | Condition |
|---|---|---|---|---|---|---|
| R-001 | Application Owners | 8 | Medium | Approved | Accepted | Continue quarterly access reviews; extend testing to Q2 to Q4 (ACT-10) |
| R-002 | IT Manager | 8 | Medium | Approved | Accepted | Maintain the approval-before-provisioning workflow |
| R-003 | IT Manager | 5 | Low | Approved | Accepted | Routine monitoring of the deactivation SLA |
| R-004 | IT Manager | 10 | Medium | Approved | Accepted until the corrective action is implemented and verified | Independent Security/Compliance co-review (ACT-06; see section 3) |
| R-005 | Engineering Manager | 5 | Low | Approved | Accepted | Routine monitoring of the change workflow |
| R-006 | Infrastructure Operations | 5 | Low | Approved | Accepted | Routine monitoring; periodic restore testing to be added (ACT-11) |
| R-007 | Infrastructure Operations | 6 | Medium | Approved | Accepted | Maintain batch job monitoring |
| R-008 | IT Manager | 4 | Low | Approved | Accepted | Routine monitoring of the incident process |
| R-009 | IT Manager | 10 | Medium | Approved | Accepted until MFA enforcement testing is added to the next audit cycle | MFA enforcement test (ACT-12) |
| R-010 | Infrastructure Operations | 12 | High | Approved | **Not accepted** (Top Management decision) | Cloud configuration monitoring to be implemented (ACT-07; see section 3) |
| R-011 | Engineering Manager | 8 | Medium | Approved | Accepted until the control framework is implemented and assessed | Secure SDLC controls (ACT-08; see section 3) |
| R-012 | IAM Administrator | 6 | Medium | Approved | Accepted | Review the connected-application inventory annually (ACT-13) |

**R-010:** the residual risk is High, and Top Management directed that it is not
accepted, including on a temporary basis. Implementation of the treatment is required,
with the due date set in `Improvement-Action-Tracker.xlsx` (ACT-07).

**R-004:** the Risk Owner (IT Manager) accepts the residual risk on the condition that
independent review is introduced. The Action Owner is the Security/Compliance function
(see section 3).

---

## 3. Controls Marked Planned in the SoA (Agenda Item 8)

| Control | Related risk | Decision | Owner |
|---|---|---|---|
| 5.35 Independent review of information security | R-004; ISO-005 | Approved for implementation | Security/Compliance function (role to be assigned) |
| 8.9 Configuration management | R-010 | Approved for implementation | Infrastructure Operations |
| 8.25 Secure development life cycle | R-011 | Approved for implementation | Engineering Manager |
| 8.28 Secure coding | R-011 | Approved for implementation | Engineering Manager |

**Security/Compliance function:** this function does not yet exist. Top Management is
to assign its responsibility and authority, in line with Clause 5.3 (ACT-05). The
independent co-review (ACT-06) depends on this assignment. Until the assignment is
made, the acceptance of R-004 remains conditional.

---

## 4. Opportunities for Improvement (Agenda Item 9)

Based on the internal audit observations and the review inputs:

- **ISO-003:** record confidentiality, integrity and availability for each risk in the
  Risk Register.
- **ISO-004:** define a risk assessment interval and record the assessment date.
- **ISO-005:** introduce independent review of privileged access (section 3).
- **Information security objectives:** establish documented objectives (Clause 6.2).

---

## 5. Results of the Review (Clause 9.3.3)

**Decisions on continual improvement and ISMS changes:**

| Decision | Related item | Action |
|---|---|---|
| Risk owners' approval of the treatment plans and the residual risk decisions for all 12 risks are recorded in section 2 of these minutes | ISO-001 | ACT-01 |
| Determine which interested party requirements the ISMS addresses and record the determination in the Interested Parties Register | ISO-002 | ACT-02 |
| Add a confidentiality, integrity and availability field to the Risk Register | ISO-003 | ACT-03 |
| Set the risk assessment interval at annual and record the assessment date in the register; update the Risk Assessment Methodology | ISO-004 | ACT-04 |
| Assign responsibility and authority for the Security/Compliance function (owner: Top Management) | Clause 5.3; prerequisite for ISO-005 | ACT-05 |
| Introduce independent co-review of privileged access (control 5.35) | ISO-005 | ACT-06 |
| Implement cloud configuration monitoring (control 8.9) | R-010 | ACT-07 |
| Define and implement secure SDLC and secure coding controls (controls 8.25, 8.28) | R-011 | ACT-08 |
| Establish documented information security objectives consistent with the information security policy and the risk treatment results, with owners, measures and targets | Clause 6.2; not audited, so no finding raised | ACT-09 |
| Extend access review testing to Q2 to Q4 2026 | R-001 | ACT-10 |
| Add periodic restore testing for backups | R-006 | ACT-11 |
| Add MFA enforcement testing to the next audit cycle | R-009 | ACT-12 |
| Review the connected-application inventory annually | R-012 | ACT-13 |
| Review and report performance against the information security objectives at the next management review | Clause 9.3.2(d)(4) | ACT-14 |

**Next review:** management reviews will be held at planned intervals, at least
annually. The next review is due by June 2027, or earlier if significant changes occur.

**Conclusion:** the ISMS was found suitable and adequate for the scope reviewed, and
effective as far as the Q1 2026 evidence shows. The actions above address the audit
findings and the remaining gaps.

---

## 6. Actions

Actions, owners, due dates and closure evidence are in `Improvement-Action-Tracker.xlsx`
(ACT-01 to ACT-14).

---

## 7. Follow-up on ISO-001

These minutes record risk-owner approval of the treatment plans and the documented
residual-risk decision for each of the 12 risks. R-010 is explicitly not accepted and
remains subject to further treatment. Closure of ISO-001 is to be verified in a
follow-up audit, including verification of the recorded approvals and residual-risk
decisions.

---

## Related Documents

- `Management-Review-Agenda.md`
- `Improvement-Action-Tracker.xlsx`
- `12-ISO27001-Internal-Audit/Internal-Audit-Report.md`
- `09-ISO27001-Risk-Assessment/ISO27001-Risk-Register.xlsx`
- `11-ISO27001-Statement-of-Applicability/SoA.xlsx`
