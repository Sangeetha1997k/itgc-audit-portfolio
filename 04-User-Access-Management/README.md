# User Access Management (UAM) Testing

## Objective

The objective of this testing is to evaluate whether user access controls are appropriately designed and operating effectively to prevent unauthorized access to company systems.

---

## Systems in Scope

- Okta (Primary Identity Provider managing authentication, SSO, MFA, user provisioning, and deprovisioning)
- Google Workspace (Downstream application integrated with Okta SSO; access lifecycle is managed through Okta)

---

### Evidence Source Note

Google Workspace access is provisioned and deprovisioned automatically through Okta SSO integration. Therefore, user lifecycle testing for Google Workspace is performed using Okta provisioning, deprovisioning, and access review evidence.

---

## Controls Tested

| Control ID | Control Description |
|---|---|
| UAM-01 | Quarterly access reviews |
| UAM-02 | User provisioning |
| UAM-03 | User deprovisioning |
| UAM-04 | Privileged access reviews |

---

## Testing Approach

Testing will evaluate:

- Control design effectiveness
- Operating effectiveness
- Evidence availability
- Exception identification
- Overall control conclusion

---

## Testing Activities

The audit testing will include:

- Obtaining control population
- Performing completeness checks
- Selecting risk-based samples
- Reviewing supporting evidence
- Evaluating whether controls operated as designed
- Documenting exceptions and conclusions# Coming Soon
