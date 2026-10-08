# ISO/IEC 27001:2022 Annex A Control Mapping

## Purpose

This folder documents the mapping between identified information security risks,
ISO/IEC 27001:2022 Annex A controls, and existing ITGC controls within the
BlueSky Technologies ISMS scope.

The mapping shows how identified risks are addressed through security controls and
how existing audit evidence provides assurance over selected control areas.

---

## Mapping Approach

Risks in the ISO 27001 Risk Register are mapped to relevant Annex A controls based on:

- The nature of the information security risk
- The objective of the Annex A control
- Existing security processes and operational controls
- Available ITGC control testing evidence

The mapping is not a certification assessment. It shows the relationship between
risks, controls, and available evidence within the portfolio environment.

Annex A control numbers and names follow Table A.1 of ISO/IEC 27001:2022.

---

## Mapping Relationship

```
Information Security Risk
        |
        v
ISO 27001:2022 Annex A Control
        |
        v
Existing ITGC Control
        |
        v
Audit Evidence / Testing Result
        |
        v
Coverage Assessment
```

Example (R-004):

```
Risk:     Privileged access review lacks independence

Annex A:  5.3 Segregation of duties
          5.35 Independent review of information security
          8.2 Privileged access rights
          5.18 Access rights

ITGC:     UAM-04 Privileged access review

Evidence: Q1 2026 interim testing; audit observation in 07-Audit-Report

Coverage: Tested (Q1 interim); design gap noted
```

---

## Coverage Interpretation

The Coverage column in `Annex-A-2022-Control-Mapping.xlsx` describes the level of
assurance available for the mapped control. The coverage value refers to the mapped
ITGC control. Where that control does not support every Annex A control on a row,
the exceptions are named in the Coverage column.

| Coverage | Meaning |
|---|---|
| Tested (Q1 interim) | The related ITGC control was tested during Q1 2026 interim procedures. This does not represent full-year operating effectiveness. |
| Partial | Existing controls cover part of the risk, but other areas are outside the testing scope. Example: Okta lifecycle is tested, but security within connected third-party applications is not. |
| Not tested | No ITGC testing evidence exists for the mapped control. The control may exist, but its implementation and operating effectiveness have not been assessed. |

Qualifiers added after the coverage value:

| Qualifier | Meaning |
|---|---|
| not directly tested: [controls] | The named Annex A controls are mapped to the risk, but the ITGC testing did not examine them. |
| design gap noted | The control operated as tested, but its design has a weakness (see `07-Audit-Report/`). |
| restore testing not covered | The control was tested, but a related activity is outside the ITGC scope. |
| third-party trust relationships not tested | Security within connected third-party applications was outside the testing scope. |
| control gap | No control within the current scope addresses the risk. |

---

## Limitations

Mapping a risk to an Annex A control does not confirm that:

- The control is fully implemented
- The control is operating effectively
- The organization is compliant with ISO/IEC 27001

A subset of the 93 Annex A controls is mapped to the risks identified in this
portfolio. Controls not mapped to a specific risk are evaluated in the Statement of
Applicability (SoA).

---

## ITGC Evidence References

| ITGC Area | Related Folder |
|---|---|
| User Access Management | `04-User-Access-Management/` |
| Change Management | `05-Change-Management/` |
| Computer Operations | `06-Computer-Operations/` |
| Audit Observations | `07-Audit-Report/` |

---

## Key Mapping Considerations

- **Multiple controls per risk:** one risk often needs several controls. Unauthorized
  access, for example, involves 5.15, 5.16, 5.18 and 8.5.
- **Multiple risks per control:** one control can treat several risks. Control 5.15
  Access control supports R-001, R-002 and R-009.

---

## Related Documents

- `09-ISO27001-Risk-Assessment/ISO27001-Risk-Register.xlsx`
- `09-ISO27001-Risk-Assessment/Risk-Assessment-Methodology.md`
- `11-ISO27001-Statement-of-Applicability/`
- `13-Management-Review/`
