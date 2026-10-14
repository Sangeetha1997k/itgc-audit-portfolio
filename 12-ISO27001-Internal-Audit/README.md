# ISMS Internal Audit

## Purpose

This folder contains the internal audit of the BlueSky Technologies ISMS, performed
in line with ISO/IEC 27001:2022 Clause 9.2.

The audit tests whether the ISMS conforms to ISO/IEC 27001:2022 and to the
organization's own ISMS documentation within a defined scope, and whether the risk
assessment, risk treatment and Statement of Applicability are consistent with one
another.

---

## Contents

| File | Description |
|---|---|
| [`Audit-Plan.md`](Audit-Plan.md) | Audit objective, criteria, scope, approach, timeline and objectivity |
| [`Audit-Checklist.xlsx`](Audit-Checklist.xlsx) | 26 audit checks with evidence examined, method, result and finding reference; includes a Result Key and result totals |
| [`Internal-Audit-Report.md`](Internal-Audit-Report.md) | Findings, conclusion, recommendations and follow-up |

---

## Audit Summary

| Item | Detail |
|---|---|
| Audit type | Internal audit (first party), Clause 9.2 |
| Period reviewed | Q1 2026 (January to March 2026) |
| Fieldwork | 11 to 15 May 2026 |
| Report date | 22 May 2026 |
| Scope | Clauses 4.1 to 4.3, 6.1.2, 6.1.3, 8.2 and 8.3, and selected Annex A access controls (5.3, 5.15, 5.16, 5.18, 5.35, 8.2) |

---

## Results

| Result | Checks |
|---|---:|
| Conforms | 20 |
| Observation | 4 |
| Minor nonconformity | 2 |
| **Total** | **26** |

Three of the 20 conforming checks rely on Q1 2026 interim ITGC testing. No major
nonconformities were identified.

---

## Findings

| Ref | Type | Clause or Control | Summary |
|---|---|---|---|
| ISO-001 | Minor nonconformity | 6.1.3(f) | Risk owners' approval of the treatment plan and acceptance of residual risks not documented |
| ISO-002 | Minor nonconformity | 4.2(c) | Interested party requirements addressed through the ISMS not identified |
| ISO-003 | Observation | 6.1.2(c)(1) | Confidentiality, integrity and availability not recorded for each risk |
| ISO-004 | Observation | 8.2 | No defined risk assessment interval or assessment date |
| ISO-005 | Observation (carried forward) | 5.3, 5.35, 8.2 | Privileged access review lacks independence from IT (UAM-04) |

Full conditions, effects and recommendations are in [`Internal-Audit-Report.md`](Internal-Audit-Report.md).

---

## Audit Approach

Methods used: document review, reconciliation, reliance on ITGC work, and
re-performance. Inherent and residual risk scores were recalculated for all 12 risks,
and the Risk Register, Control Mapping and Statement of Applicability were reconciled.

Interviews were not part of this engagement.

---

## Limitations

- **Interim ITGC evidence:** reliance on ITGC work reflects Q1 2026 interim testing
  only and does not represent full-year operating effectiveness.
- **Evidence cut-off:** findings reflect the evidence available at the report date of
  22 May 2026. Management review decisions recorded in June 2026 are follow-up
  evidence and do not change the audit conclusion as of that date.
- **Scope:** requirements of Clauses 6.1.1, 6.2, 6.3 and 8.1, Clauses 5, 7 and 10,
  Clause 9.3, and the remaining Annex A controls were not audited in this cycle.
- **Documents and recalculation:** no process was observed in operation.

---

## Follow-up

Corrective actions are tracked in [`13-Management-Review/Improvement-Action-Tracker.xlsx`](../13-Management-Review/Improvement-Action-Tracker.xlsx).
The follow-up to ISO-001 depends on the risk-owner decisions recorded at the
management review. Closure is to be verified in a later audit.

---

## Related Documents

- [`08-ISO27001-Context/`](../08-ISO27001-Context/)
- [`09-ISO27001-Risk-Assessment/`](../09-ISO27001-Risk-Assessment/)
- [`10-ISO27001-Control-Mapping/`](../10-ISO27001-Control-Mapping/)
- [`11-ISO27001-Statement-of-Applicability/`](../11-ISO27001-Statement-of-Applicability/)
- [`07-Audit-Report/`](../07-Audit-Report/)
- [`13-Management-Review/`](../13-Management-Review/)
