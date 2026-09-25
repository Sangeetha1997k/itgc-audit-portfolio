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

## Expected Deliverables

- Change Management Test Workpaper
- Supporting Evidence
- Audit Conclusions
