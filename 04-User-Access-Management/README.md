# User Access Management

## Purpose

This section demonstrates the testing of IT General Controls (ITGC) related to User Access Management.

The objective is to evaluate whether user access controls are appropriately designed and operating effectively to prevent unauthorized access to company systems.

---

## Controls in Scope

| Control ID | Control |
|------------|---------|
| UAM-01 | User access is reviewed quarterly by appropriate reviewers to validate access remains appropriate. |
| UAM-02 | User access requests require documented manager approval before access is granted. |
| UAM-03 | User accounts are disabled within the defined SLA following employee termination. |
| UAM-04 | Privileged user access is reviewed quarterly to validate access remains appropriate. |

---

## Risk

Unauthorized users may retain access that is no longer appropriate for their role. Users may be granted access that was never approved or exceeds job requirements. Terminated employees may retain system access after leaving the organization. Excessive or unreviewed privileged access may result in unauthorized administrative activity.

---

## Control Objective

Ensure that:

- User access is periodically reviewed and remains appropriate for the user's role
- Access is approved by an appropriate manager before being provisioned
- Access is removed promptly after employee termination
- Privileged access is restricted and reviewed on a quarterly basis

---

## Systems in Scope

- Okta (Identity Provider managing authentication, SSO, MFA, user provisioning, deprovisioning, and access reviews)

---

## Evidence

| Evidence ID | Description |
|-------------|-------------|
| E-001 | Okta User Access Export |
| E-002 | Quarterly Access Review Report |
| E-003 | Access Review Sign-off Record |
| E-004 | Access Request Ticket |
| E-005 | Manager Approval Record |
| E-006 | User Provisioning Log |
| E-007 | Employee Termination Report |
| E-008 | Okta Deactivation Log |
| E-009 | Privileged User Access List |
| E-010 | Privileged Access Review Report |

---

## Audit Testing Approach

Testing will verify that:

- User access reviews were completed quarterly, and access certifications were appropriately evidenced.
- Access requests were approved by an appropriate manager before provisioning.
- Provisioned access matched the approved request.
- Terminated user accounts were disabled within the defined SLA.
- Privileged access was reviewed quarterly and remained supported by business justification.
- Supporting evidence was reviewed to confirm review, approval, provisioning, and deprovisioning activities were documented.

---

## Expected Deliverables

- User Access Management Test Workpaper
- Supporting Evidence
- Audit Conclusions
