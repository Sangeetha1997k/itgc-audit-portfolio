# Statement of Applicability (SoA)

## Purpose

This folder contains the Statement of Applicability for the BlueSky Technologies
ISMS, prepared in line with ISO/IEC 27001:2022 Clause 6.1.3(d).

For each of the 93 Annex A controls, the SoA records whether the control is
applicable, who owns it, why it is included or excluded, its implementation status,
the risks it is linked to, and the supporting ITGC evidence where it exists.

---

## Contents

| File | Description |
|---|---|
| `SoA.xlsx` | Statement of Applicability covering all 93 Annex A controls |

---

## SoA Structure

| Column | Description |
|---|---|
| Control ID / Control Name | As listed in Table A.1 of ISO/IEC 27001:2022 |
| Theme | Organizational, People, Physical or Technological |
| Applicable | Yes or No |
| Control Owner | Current role or planned function accountable for the control; planned ownership is identified where the function has not yet been established. |
| Justification | Reason the control is included or excluded |
| Implementation Status | See status definitions below |
| Linked Risk(s) | Risks the control is mapped to in `10-ISO27001-Control-Mapping/` |
| ITGC Evidence | Reference to an ITGC workpaper or other supporting evidence where available. A reference does not by itself indicate that the control was tested or found effective; assessment scope and limitations are recorded in the other fields. |

---

## Implementation Status Definitions

| Status | Meaning |
|---|---|
| Implemented | The control is recorded as implemented, and available evidence supports its existence or operation within the scope tested. Evidence in this portfolio reflects Q1 2026 interim testing where applicable and does not establish full-year operating effectiveness. |
| Partially Implemented | Control exists but has design, implementation, or coverage limitations. |
| Planned | Control has been approved for implementation but is not yet implemented. |
| Not Assessed | The control is applicable, but its implementation or operating effectiveness was not assessed within this portfolio. The status does not indicate that the control is absent or ineffective. |
| Not Applicable | Control is excluded from the ISMS scope, with a documented justification. |

---

## Applicability Approach

All 93 Annex A controls were evaluated individually against the ISMS scope
(`08-ISO27001-Context/ISMS-Scope.md`), the risks in
`09-ISO27001-Risk-Assessment/ISO27001-Risk-Register.xlsx`, and BlueSky Technologies'
activities and responsibilities. A control may be excluded where it falls outside the
defined ISMS scope, is the responsibility of an external provider outside BlueSky's
assessed responsibilities, or does not apply to the activities currently described.
Each exclusion is supported by a documented justification.

- **Data center physical controls (7.1 to 7.6, 7.8, 7.11 to 7.13):** these controls
  are excluded from the current ISMS scope because production infrastructure is
  hosted in AWS facilities and physical data center security is managed by AWS.
  Corporate offices are also outside the defined ISMS scope. AWS assurance evidence
  was not reviewed as part of this portfolio, because vendor risk management is
  outside the audit scope. These exclusions should be reconsidered if the ISMS scope
  or the shared responsibility assessment changes.
- **Device-related physical controls (7.7, 7.9, 7.10, 7.14):** applicable, because
  staff devices are used to access production systems.
- **8.23 Web filtering:** applies to corporate internet access, which is outside the
  ISMS scope.
- **8.30 Outsourced development:** no outsourced development is described in the
  portfolio. To be reconsidered if development is outsourced.

If the ISMS scope changes, excluded controls must be re-evaluated.

---

## Evidence and Limitations

- **Interim testing:** ITGC evidence references reflect Q1 2026 interim testing only.
  They do not represent full-year operating effectiveness.
- **Linked Risk(s):** this column shows the risk-to-control mapping. It does not mean
  the control has been tested for every linked risk. Testing limits are stated in the
  Justification and ITGC Evidence columns.
- **Not Assessed:** the control is applicable, but its implementation or operating
  effectiveness was not assessed within this portfolio. Supporting information may
  exist, but it does not establish an assessment conclusion. The status does not mean
  that the control is absent or ineffective.
- **Control owners:** reflect the current operating model, except where a planned
  function is identified. Independent review (5.35) is assigned to a function that
  does not yet exist, as the planned treatment for R-004.

---

## Planned Controls

Controls marked Planned are the approved treatments for risks identified in the Risk
Register. The approvals are recorded in `13-Management-Review/`.

---

## Related Documents

- `08-ISO27001-Context/ISMS-Scope.md`
- `09-ISO27001-Risk-Assessment/ISO27001-Risk-Register.xlsx`
- `09-ISO27001-Risk-Assessment/Risk-Assessment-Methodology.md`
- `10-ISO27001-Control-Mapping/Annex-A-2022-Control-Mapping.xlsx`
- `07-Audit-Report/`
- `13-Management-Review/`
