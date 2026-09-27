# IT General Controls (ITGC) Interim Audit Report

**Company:** BlueSky Technologies (Fictional)
**Audit Period:** January 2026 – December 2026
**Testing Performed:** Q1 2026 (January – March 2026), interim testing
**Report Type:** Interim ITGC Audit Report — Portfolio Demonstration
**Prepared By:** IT Audit Portfolio Project
**Report Date:** April 2026
**Classification:** Training / Demonstration Document

---

## 1. Executive Summary

This report presents the results of interim IT General Controls (ITGC) testing performed over BlueSky Technologies' key IT processes supporting the confidentiality, integrity, and availability of its information systems. The full audit period is January 2026 – December 2026; this report reflects testing procedures completed during Q1 2026. Interim testing covered eight controls across three domains: User Access Management, Change Management, and Computer Operations. All eight controls tested were assessed as operating effectively based on procedures performed to date. One control design observation was identified related to segregation of duties in privileged access review, which is noted in Section 6 along with a corresponding recommendation. Remaining testing for Q2–Q4 2026 will be completed and reported separately to support the final annual audit conclusion.

| Area | Controls | Result (Q1 Testing) |
|------|---------:|--------|
| User Access Management | 4 | Effective |
| Change Management | 1 | Effective |
| Computer Operations | 3 | Effective |
| **Total** | **8** | **Effective** |

---

## 2. Audit Objective

The objective of this audit was to evaluate whether selected IT General Controls were appropriately designed and operating effectively for the period tested, and to assess whether controls were operating as intended to reduce the risk of unauthorized access, unauthorized changes, and IT operational failures.

---

## 3. Scope

The overall audit scope covers the following domains and controls for the January 2026 – December 2026 audit period:

| Domain | Controls | Systems in Scope |
|--------|----------|------------------|
| User Access Management | UAM-01 (Quarterly Access Reviews), UAM-02 (User Provisioning), UAM-03 (User Deprovisioning), UAM-04 (Privileged Access Reviews) | Okta |
| Change Management | CHG-01 (Production Change Management) | ServiceNow, AWS |
| Computer Operations | OPS-01 (Backup Monitoring), OPS-02 (Batch Job Monitoring), OPS-03 (Incident Management) | AWS, ServiceNow |

This interim report reflects testing performed during Q1 2026. Quarterly controls (UAM-01, UAM-04) were tested using their Q1 2026 review instances. User provisioning, deprovisioning, change management, and computer operations controls were tested using representative populations from Q1 2026 (e.g., changes, backups, batch jobs, and incidents occurring in January–March 2026). Full population testing was performed for each selected population. Testing for Q2–Q4 2026 remains outstanding and will be addressed in the final annual report.

**Out of scope:** Application code review, penetration testing, physical security assessment, vendor risk management, and security operations monitoring review.

---

## 4. Methodology

Testing followed a risk-based audit approach:

1. Understood the business process and control objective for each control
2. Identified the risk the control was designed to mitigate
3. Evaluated control design considerations and performed Test of Design procedures where applicable
4. Obtained the control population, performed completeness checks where applicable, and applied full population testing for each selected testing period
5. Reviewed supporting evidence for each item tested
6. Evaluated operating effectiveness (Test of Operating Effectiveness)
7. Documented exceptions and observations
8. Concluded on each control's operating effectiveness for the period tested

Each control's population, sample, evidence, and testing procedure are documented in its respective Test Details workpaper.

---

## 5. Summary of Results

| Domain | Controls Tested | Result (Q1 2026) |
|--------|-----------------|--------|
| User Access Management | UAM-01, UAM-02, UAM-03, UAM-04 | **Effective** |
| Change Management | CHG-01 | **Effective** |
| Computer Operations | OPS-01, OPS-02, OPS-03 | **Effective** |

**Overall result: All 8 controls tested were assessed as operating effectively during the Q1 2026 testing period.** No operating exceptions were identified in any control tested. These results reflect interim testing only; a final conclusion on operating effectiveness for the full audit period will be issued upon completion of Q2–Q4 testing.

---

## 6. Observations

**Observation 1 — Segregation of Duties (SoD), Privileged Access Review (UAM-04)**

**Risk Rating:** Medium

Certain privileged access provisioning activities are performed by the IAM Administrator, while periodic privileged access reviews are performed by personnel within the same IT reporting structure without independent oversight. The current control design does not include an independent review by a second-line function (e.g., Security or Compliance).

All privileged access reviewed during testing was supported by documented business justification and found appropriate — this is a **control design observation, not an operating exception**. The control operated as designed; the design itself has a gap in independent oversight.

**Impact:**

Lack of independent review may increase the risk that inappropriate privileged access remains undetected due to insufficient segregation of duties.

---

## 7. Conclusion

Based on the interim procedures performed, the IT General Controls tested across User Access Management, Change Management, and Computer Operations were found to be **appropriately designed and operating effectively** during the Q1 2026 period tested. One design-level observation was noted regarding segregation of duties in privileged access review (Section 6), which does not affect the interim conclusion of control effectiveness but is recommended for remediation to strengthen the control environment further. A final conclusion covering the full audit period will be issued following completion of remaining testing.

---

## 8. Recommendations

**Recommendation 1 (related to Observation 1):** Implement an independent secondary review of privileged access during periodic access certification activities by a Security, Compliance, or Governance function, separate from the IT team that provisions and manages that access. This would reduce the risk of inappropriate privileged access remaining undetected due to lack of independent challenge.

---

## Disclaimer

All company names, systems, data, evidence, and scenarios in this portfolio are fictional and created only for learning and demonstration purposes. They do not represent any real organization or audit engagement.
