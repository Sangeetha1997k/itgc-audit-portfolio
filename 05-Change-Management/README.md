# Change Management

## Purpose

This section demonstrates the testing of IT General Controls (ITGC) related to Change Management.

The objective is to evaluate whether production changes are appropriately authorized, tested, approved, and implemented to reduce the risk of unauthorized or unsuccessful changes affecting production systems.

---

## Control in Scope

| Control ID | Control |
|------------|---------|
| CHG-01 | Production changes are approved, tested, and authorized before implementation. |

---

## Risk

Unauthorized, untested, or improperly approved production changes may result in system outages, security vulnerabilities, data integrity issues, or disruption to business operations.

---

## Control Objective

Ensure production changes are:

- Formally requested
- Risk assessed
- Approved by appropriate personnel
- Tested before deployment
- Successfully implemented
- Supported by appropriate documentation

---

## Systems in Scope

- ServiceNow (Change Management)
- AWS (Production Infrastructure)

---

## Evidence

| Evidence ID | Description |
|-------------|-------------|
| E-011 | ServiceNow Change Register |
| E-012 | Change Approval Records |
| E-013 | User Acceptance Testing (UAT) Evidence |
| E-014 | Production Deployment Log |

---

## Audit Testing Approach

Testing will verify that:

- Change requests were formally documented.
- Appropriate approvals were obtained before implementation.
- Testing evidence was completed before production deployment.
- Production deployments matched approved change requests.
- Supporting evidence was available for each change tested.

---

## Test Results (Q1 2026 Interim)

| Test ID | Control | Population | Evidence | Exceptions | Result |
|---|---|---|---|---|---|
| CHG-T001 | CHG-01 Production change management | 12 production changes (full population) | E-011, E-012, E-013, E-014 | None | Pass |

Every change was traced from the ServiceNow register through approval, testing and deployment. The two security-sensitive changes (CHG-2005 and CHG-2010) also had a documented technical peer review.

## Files in this Folder

| File | View in browser |
|---|---|
| [`CHG-Test-Workpaper.xlsx`](CHG-Test-Workpaper.xlsx) | [PDF copy](CHG-Test-Workpaper.pdf) |
| Evidence E-011 to E-014 (`.xlsx` originals) | CSV copy of each, for example [`E-011`](E-011-ServiceNow-Change-Register.csv) |

---

## Expected Deliverables

- Change Management Test Workpaper
- Supporting Evidence
- Audit Conclusions
