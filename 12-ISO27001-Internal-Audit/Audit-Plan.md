# ISMS Internal Audit Plan

## Audit Details

| Item | Detail |
|---|---|
| Organization | BlueSky Technologies (Fictional) |
| Audit title | ISO/IEC 27001:2022 ISMS Internal Audit (Risk Management Focus) |
| Audit type | Internal audit (first party), per Clause 9.2 |
| Audit period reviewed | Q1 2026 (January to March 2026) |
| Planned timeline | Planning: 4 May 2026. Fieldwork: 11 to 15 May 2026. Report: 22 May 2026 |
| Auditor | Internal Auditor (IT Audit), independent of the areas audited |
| Report recipient | Top management (see `13-Management-Review/`) |

---

## Audit Objective

To determine whether the BlueSky Technologies ISMS:

- Conforms to the requirements of ISO/IEC 27001:2022 within the audit scope
- Conforms to the organization's own ISMS requirements, as set out in
  `08-ISO27001-Context/` and `09-ISO27001-Risk-Assessment/`
- Is effectively implemented and maintained within the audit scope

---

## Audit Criteria

- ISO/IEC 27001:2022, Clauses 4 to 10 and Annex A (Table A.1)
- Risk Assessment Methodology (`09-ISO27001-Risk-Assessment/Risk-Assessment-Methodology.md`)
- ISMS Scope Statement (`08-ISO27001-Context/ISMS-Scope.md`)

---

## Audit Scope

| Area | Clause or Control | What will be audited |
|---|---|---|
| Context and scope | 4.1, 4.2, 4.3 | ISMS scope documented; interested parties and requirements identified |
| Risk assessment | 6.1.2 | Risk criteria defined; risks identified, analysed and evaluated; risk owners assigned |
| Risk treatment | 6.1.3 | Treatment options selected; Annex A comparison performed; SoA produced; treatment plan and risk owner approval |
| Operation | 8.2, 8.3 | Risk assessment performed at planned intervals; treatment plan implemented |
| Access control | Annex A 5.3, 5.15, 5.16, 5.18, 5.35, 8.2 | Reliance on ITGC testing (UAM-01 to UAM-04); follow-up of the UAM-04 observation |

This audit cycle focuses on Clauses 4, 6 and 8 and the selected Annex A controls
listed above. Clauses 5, 7 and 10, and the remaining Annex A controls, will be
covered in later audit cycles.

**Not audited in this cycle:**

- Clause 9.3 (management review): scheduled after this audit, so it cannot be audited
  yet. Audit results will be an input to it.
- Physical controls excluded in the SoA

---

## Audit Programme Considerations (Clause 9.2.2)

The scope above was selected using the importance of the processes concerned and the
results of previous audits:

- Risk assessment and treatment (Clause 6) are central to the ISMS.
- The ITGC interim audit (`07-Audit-Report/`) raised one design observation
  (segregation of duties in privileged access review, UAM-04), which is followed up here.
- Clauses 5, 7 and 10 are not audited this cycle. They should be covered in a later
  cycle, so that all ISMS requirements are audited within the programme.

---

## Audit Approach

| Method | Use |
|---|---|
| Document review | Scope, methodology, risk register, treatment decisions, control mapping, SoA |
| Reconciliation | Risk Register against Control Mapping and SoA (risk IDs, control IDs, owners) |
| Reliance on ITGC work | Evidence E-001 to E-020 and workpapers UAM, CHG, OPS |
| Re-performance | Recalculation of all inherent and residual risk scores and ratings |

Interviews are not part of this simulated engagement.

**Limitation on reliance:** ITGC evidence is based on Q1 2026 interim testing. Findings
about control effectiveness do not extend to the full audit period.

---

## Objectivity and Impartiality (Clause 9.2.2)

The auditor is independent of the processes audited and did not approve the risk
treatment decisions. Results will be reported to relevant management and retained as
documented information.

---

## Deliverables

| Deliverable | File | Content |
|---|---|---|
| Audit checklist | `Audit-Checklist.xlsx` | Audit questions, evidence examined, method, result and finding reference |
| Audit report | `Internal-Audit-Report.md` | Findings, conclusion, recommendations and follow-up actions |

---

## Related Documents

- `08-ISO27001-Context/`
- `09-ISO27001-Risk-Assessment/`
- `10-ISO27001-Control-Mapping/`
- `11-ISO27001-Statement-of-Applicability/`
- `07-Audit-Report/`
- `13-Management-Review/`
