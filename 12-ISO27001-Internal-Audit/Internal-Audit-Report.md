# ISMS Internal Audit Report

**Organization:** BlueSky Technologies (Fictional)
**Audit title:** ISO/IEC 27001:2022 ISMS Internal Audit (Risk Management Focus)
**Audit type:** Internal audit (first party), Clause 9.2
**Period reviewed:** Q1 2026 (January to March 2026)
**Fieldwork:** 11 to 15 May 2026
**Report date:** 22 May 2026
**Prepared by:** Internal Auditor (IT Audit)
**Report recipient:** Top management
**Classification:** Training / Demonstration Document

---

## 1. Executive Summary

An internal audit of the BlueSky Technologies ISMS was performed against ISO/IEC
27001:2022 and the organization's own ISMS documentation.The audit covered selected 
requirements of Clauses 4, 6 and 8, and selected access control requirements in Annex A. 
Twenty-six checks were performed.

Twenty checks conformed (three of them in reliance on Q1 2026 interim ITGC testing),
four resulted in observations, and two resulted in minor nonconformities. No major
nonconformities were identified.

| Result | Checks |
|---|---:|
| Conforms | 20 |
| Observation | 4 |
| Minor nonconformity | 2 |
| **Total** | **26** |

The two minor nonconformities concern (1) the absence of evidence that risk owners
approved the treatment plan and that residual-risk decisions were made under Clause
6.1.3(f), and (2) the absence of evidence that the organization determined which
interested-party requirements would be addressed through the ISMS under Clause 4.2(c).
The corrective actions must ensure that the required approvals and determinations are
made where necessary and appropriately evidenced. Details are in Section 5.

---

## 2. Audit Objective and Criteria

**Objective:** to determine whether the ISMS conforms to the requirements of ISO/IEC
27001:2022 and the organization's own ISMS requirements within the audit scope, and is
effectively implemented and maintained.

**Criteria:**

- ISO/IEC 27001:2022 requirements relevant to the defined audit scope: Clauses 4.1 to
  4.3, 6.1.2, 6.1.3, 8.2 and 8.3, and selected Annex A controls from Table A.1
- Risk Assessment Methodology (`09-ISO27001-Risk-Assessment/`)
- ISMS Scope Statement (`08-ISO27001-Context/`)

---

## 3. Scope

| Area | Clause or Control |
|---|---|
| Context and scope | 4.1, 4.2, 4.3 |
| Risk assessment | 6.1.2 |
| Risk treatment | 6.1.3 |
| Operation | 8.2, 8.3 |
| Access control | Annex A 5.3, 5.15, 5.16, 5.18, 5.35, 8.2 |

Not audited in this cycle: requirements of Clauses 6.1.1, 6.2, 6.3 and 8.1; Clauses 5,
7 and 10; Clause 9.3, because the management review follows this audit; the remaining
Annex A controls (planned for later cycles); and the physical controls excluded in the
Statement of Applicability.

---

## 4. Approach and Limitations

**Methods:** document review, reconciliation, reliance on ITGC work, and
re-performance. Inherent and residual scores and ratings were recalculated for all 12
risks. The Risk Register, Control Mapping and Statement of Applicability were
reconciled (risk IDs, control IDs and owners). Interviews were not part of this
engagement.

**Objectivity:** the auditor is independent of the processes audited and did not
approve the risk treatment decisions.

**Limitations:**

- ITGC evidence reflects Q1 2026 interim testing only. Conclusions that rely on it do
  not extend to full-year operating effectiveness.
- Findings are based on documents and recalculation. No process was observed in
  operation.
- **Evidence cut-off:** findings reflect the evidence available during fieldwork and at
  the report date of 22 May 2026. Management review decisions documented in June 2026
  are subsequent follow-up evidence and do not retrospectively change the audit
  conclusion as of 22 May 2026.

Detailed checks are recorded in `Audit-Checklist.xlsx`.

---

## 5. Findings

### ISO-001: Risk treatment approval and residual risk acceptance not documented

| Item | Detail |
|---|---|
| Classification | Minor nonconformity |
| Clause | 6.1.3(f) |
| Checklist | CK-20; related observation CK-23 |
| Risk link | R-001 to R-012 |

**Requirement:** the organization shall obtain risk owners' approval of the risk
treatment plan and acceptance of the residual information security risks.

**Condition:** the Risk Register contains a treatment plan with planned actions and
owners. No record shows that risk owners approved the plan or accepted residual risks.
At the audit date, approval was scheduled for the management review.

**Effect:** the organization could not demonstrate the required risk owners' approval
of the treatment plan, or documented decisions on residual risks, at the audit date.
The "Planned" status of the four controls in the SoA (5.35, 8.9, 8.25 and 8.28), which
presumes approval, was therefore not supported by a documented approval. These controls
had not yet been implemented; their implementation is addressed separately under
Clause 8.3 in CK-23.

**Recommendation:** obtain and record each relevant risk owner's approval of the risk
treatment plan and the corresponding decision on residual risk. Record the decisions
at the management review and track the resulting actions in the Improvement Action
Tracker. For R-010, document that the high residual risk is not accepted and track the
required further treatment rather than recording it as accepted.

**Proposed action owner:** Top Management, with the IT Manager preparing the inputs.
The approvals themselves must be recorded for each risk by its risk owner.

---

### ISO-002: Interested party requirements addressed through the ISMS not identified

| Item | Detail |
|---|---|
| Classification | Minor nonconformity |
| Clause | 4.2(c) |
| Checklist | CK-03 |

**Requirement:** the organization shall determine which interested party requirements
will be addressed through the ISMS.

**Condition:** the Interested Parties Register lists parties and their requirements, but
does not state which requirements the ISMS addresses.

**Effect:** the link between interested party requirements and the ISMS scope and
controls cannot be traced.

**Recommendation:** determine which interested-party requirements the ISMS addresses
and record the determination, for example by adding an "Addressed through ISMS" column
to the register with a reference to the related scope item, risk or control.

**Proposed action owner:** IT Manager.

---

### ISO-003: Confidentiality, integrity and availability not recorded for each risk

| Item | Detail |
|---|---|
| Classification | Observation |
| Clause | 6.1.2(c)(1) |
| Checklist | CK-09 |

**Condition:** the 12 risks cover the ISMS scope, but the register does not record
which of confidentiality, integrity or availability each risk affects.

**Recommendation:** add a C/I/A column to the Risk Register.

**Proposed action owner:** IT Manager.

---

### ISO-004: No defined risk assessment interval or assessment date

| Item | Detail |
|---|---|
| Classification | Observation |
| Clause | 8.2 |
| Checklist | CK-21 |

**Condition:** the methodology requires reviews "at planned intervals" without stating
an interval, and the register carries no assessment date.

**Recommendation:** define an interval (for example, annual) in the methodology and
record the assessment date in the register.

**Proposed action owner:** IT Manager.

---

### ISO-005: Privileged access review lacks independence (carried forward)

| Item | Detail |
|---|---|
| Classification | Observation (carried forward from the ITGC audit) |
| Clause or control | Annex A 5.3, 5.35, 8.2 |
| Checklist | CK-26 |
| Risk link | R-004 |
| Source | `07-Audit-Report/`, Observation 1 |

**Condition:** privileged access provisioning and periodic review are performed within
the same IT reporting line, without independent oversight. ITGC testing (UAM-T004)
found that the access reviewed was supported by documented business justification. This
is a control design observation, not an operating exception. It is reported as an
observation, consistent with the ITGC audit report.

**Effect:** inappropriate privileged access may go undetected because the review lacks
independent challenge. Residual risk for R-004 remains Medium (10).

**Recommendation:** implement an independent co-review by a Security, Compliance or
Governance function (SoA control 5.35, status Planned).

**Proposed action owner:** Security/Compliance function (role to be assigned).

**Note:** the Planned status of 5.35 depends on the approval recorded under ISO-001.

---

## 6. Conclusion

Within the scope audited, the ISMS conforms to the requirements of ISO/IEC 27001:2022
in all areas except for two minor nonconformities (ISO-001 and ISO-002). The risk
assessment methodology, risk register, control mapping and Statement of Applicability
are consistent with one another, and the 29 mapped Annex A controls reconcile between
the mapping and the SoA.

Conclusions on access control rely on Q1 2026 interim ITGC testing and do not extend to
the full audit period.

---

## 7. Follow-up

| Finding | Type | Planned closure |
|---|---|---|
| ISO-001 | Minor nonconformity | Risk-owner approvals and residual-risk decisions documented at management review for all 12 risks (`13-Management-Review/`); further treatment for R-010 tracked |
| ISO-002 | Minor nonconformity | Interested Parties Register updated |
| ISO-003 | Observation | Risk Register updated |
| ISO-004 | Observation | Methodology and register updated |
| ISO-005 | Observation | Independent co-review implemented (SoA 5.35) |

Actions will be tracked in `13-Management-Review/Improvement-Action-Tracker.xlsx`.
Closure will be verified in a follow-up audit.

---

## Related Documents

- `Audit-Plan.md`
- `Audit-Checklist.xlsx`
- `07-Audit-Report/`
- `08-ISO27001-Context/`
- `09-ISO27001-Risk-Assessment/`
- `10-ISO27001-Control-Mapping/`
- `11-ISO27001-Statement-of-Applicability/`
- `13-Management-Review/`

---

## Disclaimer

All company names, systems, data, evidence, and scenarios in this portfolio are
fictional and created only for learning and demonstration purposes. They do not
represent any real organization or audit engagement.
