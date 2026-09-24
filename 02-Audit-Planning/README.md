# Audit Planning

## Audit Name

IT General Controls (ITGC) Audit

---

## Audit Objective

The objective of this simulated audit is to evaluate whether selected IT General Controls are appropriately designed and operating effectively to reduce risks related to unauthorized access, unauthorized changes, and IT operational failures.

---

## Audit Period

January 2026 - December 2026

---

## Audit Scope

The audit focuses on key IT General Control areas that support the confidentiality, integrity, and availability of information systems.

The following ITGC domains are included:

## 1. User Access Management

### Objective

Ensure users have appropriate access based on their job responsibilities and that unauthorized access is identified and removed timely.

### Systems in Scope

- Okta

### Controls Covered

- User provisioning
- User deprovisioning
- Quarterly access reviews
- Privileged access reviews

Note: Google Workspace access is provisioned and deprovisioned through Okta SSO and is therefore covered by Okta-based access testing.

---

## 2. Change Management

### Objective

Ensure changes to production systems are authorized, tested, and implemented in a controlled manner.

### System in Scope

- ServiceNow

### Controls Covered

- Change request creation
- Change approval
- Testing evidence
- Production deployment review

---

## 3. Computer Operations

### Objective

Ensure IT operational processes support system availability, reliability, and recovery.

### Systems in Scope

- AWS
- ServiceNow

### Controls Covered

- Backup monitoring
- Batch job monitoring
- Incident management

---

# Systems in Scope Summary

| System | Purpose |
|---|---|
| Okta | Identity Provider (IdP), SSO, MFA, user provisioning, deprovisioning, and access reviews |
| ServiceNow | IT service management platform supporting change management, incident management, and workflow approvals |
| AWS | Cloud infrastructure supporting application hosting, backups, and operational services |

---

# Audit Approach

The audit will follow a risk-based approach:

1. Understand business processes and control objectives
2. Identify risks associated with each process
3. Evaluate whether controls are appropriately designed
4. Select samples for testing
5. Review supporting evidence
6. Test operating effectiveness of controls
7. Document exceptions identified
8. Determine overall control conclusion

---

# Testing Methodology

Control testing will include:

## Test of Design (TOD)

Evaluate whether the control is appropriately designed to address the identified risk.

Example:

Verify that access requests require appropriate approval before access is granted.

## Test of Operating Effectiveness (TOE)

Evaluate whether the control operated effectively during the audit period.

Example:

Select samples of access requests and verify approval, provisioning, and completion evidence.

---

# Out of Scope

The following areas are excluded from this simulated audit:

- Application code review
- Penetration testing
- Physical security assessment
- Vendor risk management
- Security operations monitoring review

---

# Audit Deliverables

The audit engagement will produce:

- Risk Control Matrix (RCM)
- Control testing workpapers
- Evidence review documentation
- Exception documentation
- Final audit report
