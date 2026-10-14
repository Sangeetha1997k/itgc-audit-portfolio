# itgc-audit-portfolio

A simulated IT General Controls (ITGC) audit portfolio demonstrating control testing, risk assessment, evidence evaluation and audit documentation, extended with an ISO/IEC 27001:2022 Information Security Management System (ISMS) layer covering risk assessment, control mapping, the Statement of Applicability, internal audit and management review.

All work is based on a fictional company, **BlueSky Technologies**, and is for learning and demonstration only.

---

## The Simulated Company

BlueSky Technologies is a fictional Software-as-a-Service (SaaS) company with approximately 600 employees, providing cloud-based business applications to enterprise customers. The environment in scope uses Okta for identity management, ServiceNow for IT service and change management, and AWS for cloud infrastructure.

---

## Portfolio Structure

### Part 1: ITGC Audit (folders 01 to 07)

| Folder | Content |
|---|---|
| [`01-Company-Profile/`](01-Company-Profile/) | Fictional company, business objectives and technology environment |
| [`02-Audit-Planning/`](02-Audit-Planning/) | Audit objective, scope, approach and testing methodology |
| [`03-Risk-Control-Matrix/`](03-Risk-Control-Matrix/) | Risk Control Matrix (RCM) mapping risks to eight ITGC controls |
| [`04-User-Access-Management/`](04-User-Access-Management/) | Testing of UAM-01 to UAM-04, with evidence E-001 to E-010 |
| [`05-Change-Management/`](05-Change-Management/) | Testing of CHG-01, with evidence E-011 to E-014 |
| [`06-Computer-Operations/`](06-Computer-Operations/) | Testing of OPS-01 to OPS-03, with evidence E-015 to E-020 |
| [`07-Audit-Report/`](07-Audit-Report/) | Interim ITGC audit report, results and one design observation |

### Part 2: ISO/IEC 27001:2022 ISMS Layer (folders 08 to 13)

| Folder | Content |
|---|---|
| [`08-ISO27001-Context/`](08-ISO27001-Context/) | ISMS scope and interested parties (Clauses 4.1 to 4.3) |
| [`09-ISO27001-Risk-Assessment/`](09-ISO27001-Risk-Assessment/) | Risk assessment methodology and a 12-risk register (Clause 6.1.2) |
| [`10-ISO27001-Control-Mapping/`](10-ISO27001-Control-Mapping/) | Mapping of risks to Annex A controls and related ITGC controls |
| [`11-ISO27001-Statement-of-Applicability/`](11-ISO27001-Statement-of-Applicability/) | Statement of Applicability covering all 93 Annex A controls (Clause 6.1.3) |
| [`12-ISO27001-Internal-Audit/`](12-ISO27001-Internal-Audit/) | Internal audit plan, 26-check checklist and report (Clause 9.2) |
| [`13-Management-Review/`](13-Management-Review/) | Management review agenda, minutes and improvement action tracker (Clause 9.3) |

---

## How the Two Parts Connect

The ISO 27001 layer builds on the ITGC audit rather than starting a separate exercise.

```text
ITGC testing (04 to 06)
        ↓
Evidence supporting risk assessment and SoA status decisions

ITGC audit report (07)
        ↓
Privileged-access design observation carried into the risk register,
control mapping and ISO internal audit

Risk register (09)
        ↓
Annex A control mapping (10)
        ↓
Statement of Applicability (11)

Internal audit (12)
        ↓
Management review (13)
        ↓
Improvement action tracker
```

The ISO documents reference the ITGC workpapers and evidence they rely on, rather than duplicating the underlying evidence.

**One finding followed through the portfolio:** the ITGC audit identified that privileged access provisioning and periodic review occur within the same IT reporting line, without independent oversight. This issue appears as risk R-004 in the risk register, is reflected in SoA controls 5.3 and 5.35, is reported as ISO-005 in the internal audit, and is tracked through actions ACT-05 and ACT-06 in the management review.

---

## Key Results

| Area | Result |
|---|---|
| ITGC controls tested | Eight controls tested using Q1 2026 interim evidence: UAM-01 to UAM-04, CHG-01 and OPS-01 to OPS-03 |
| ITGC operating results | No operating exceptions identified in the Q1 2026 populations tested |
| ITGC design observation | One observation concerning independence of the privileged access review (UAM-04) |
| ISO 27001 risk assessment | 12 risks. Inherent ratings: 5 High and 7 Medium. Residual ratings: 1 High, 7 Medium and 4 Low |
| Statement of Applicability | All 93 Annex A controls included in the SoA, with applicability and implementation status recorded |
| Risk-to-control mapping | 29 mapped Annex A controls reconciled between the Control Mapping and SoA |
| ISO internal audit | 26 checks: 20 Conforms, 4 Observations and 2 Minor nonconformities; no major nonconformities identified |
| Management review | Decisions recorded for all 12 risks. R-010's High residual risk is explicitly not accepted |
| Improvement actions | 14 actions (ACT-01 to ACT-14), including audit findings, planned controls, and additional management-review commitments |

---

## Audit Scope and Limitations

- **ITGC interim testing:** testing relates to Q1 2026. It does not establish full-year operating effectiveness.
- **ISO internal audit:** fieldwork took place from 11 to 15 May 2026, and the report was dated 22 May 2026. The audit covered selected requirements of Clauses 4, 6 and 8, plus selected Annex A access-control requirements; it was not a full ISMS audit.
- **Management review:** the first management review took place on 12 June 2026. Its decisions are follow-up evidence and do not retrospectively change the internal audit conclusion as of 22 May 2026.
- **Information security objectives:** Clause 6.2 was outside the internal audit scope. The management review recorded an action to establish documented information security objectives and report performance at the next review.
- **Statement of Applicability:** most applicable Annex A controls are marked Not Assessed, meaning they are applicable but were outside what this portfolio tested. The status does not mean a control is absent or ineffective.
- **Records and methods:** ownership, attendance and approvals are recorded by role, without personal names or signatures. Findings rest on documents, recalculation and ITGC evidence; no interviews were held.

The portfolio demonstrates how audit evidence, risk treatment decisions, control applicability, findings and improvement actions can be connected through a documented audit lifecycle. It does not represent a certification audit or independent assurance over a real organization.

---

## Disclaimer

BlueSky Technologies, its systems, users, risks, evidence and audit scenarios are fictional and were created for learning and demonstration purposes. No real organization or audit engagement is represented.
