# Risk Control Matrix (RCM)

## Purpose

The Risk Control Matrix (RCM) maps business risks to IT General Controls (ITGCs) and defines the planned audit approach for evaluating whether controls are appropriately designed and operating effectively.

---

## Risk Control Matrix

| Control ID | Process                | Risk                                           | Control Objective                                                  | Control Description                                                                   | Frequency   | Control Owner                  | Key Evidence                                                        | Planned Test Procedure                                                                                 |
| ---------- | ---------------------- | ---------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | ----------- | ------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| UAM-01     | User Access Management | Unauthorized users retain access               | Ensure only authorized users have appropriate access               | Quarterly access reviews are performed by application owners to validate user access. | Quarterly   | Application Owner              | Access review report, reviewer sign-off                             | Inspect access review documentation and verify reviews were completed and approved.                    |
| UAM-02     | User Provisioning      | Users receive unauthorized or excessive access | Ensure user access is approved before provisioning                 | Access requests require documented manager approval before accounts are created.      | Per Request | IT Administrator               | Access request ticket, manager approval, provisioning record        | Select a sample of new users and verify approvals were obtained before access was granted.             |
| UAM-03     | User Deprovisioning    | Terminated users retain access                 | Ensure user access is removed promptly after termination           | User accounts are disabled within the defined SLA following employee termination.     | Daily       | IT Administrator               | HR termination report, Okta deactivation log                        | Compare employee termination dates with account deactivation dates to verify timely removal of access. |
| CHG-01     | Change Management      | Unauthorized or untested production changes    | Ensure production changes are approved, tested, and authorized     | Production changes require documented approval and testing before deployment.         | Per Change  | Change Manager                 | ServiceNow change ticket, CAB approval, test evidence               | Review a sample of production changes and verify approvals, testing, and deployment documentation.     |
| OPS-01     | Backup Operations      | Data loss due to failed backups                | Ensure backups complete successfully and failures are investigated | Backup jobs are monitored daily and failures are investigated and resolved.           | Daily       | Infrastructure Operations Team | AWS backup report, monitoring logs, incident ticket (if applicable) | Review backup monitoring reports and verify failed backup jobs were investigated and resolved.         |

---

# Control Testing Approach

For each control, the audit will:

* Evaluate the control design (Test of Design – TOD).
* Test whether the control operated effectively during the audit period (Test of Operating Effectiveness – TOE).
* Obtain and evaluate supporting audit evidence.
* Document any control exceptions identified during testing.
* Conclude whether the control is operating effectively.

---

## Related Workpapers

The controls documented in this Risk Control Matrix will be tested in the following audit workpapers:

* 04-User-Access-Management
* 05-Change-Management
* 06-Computer-Operations

Each workpaper will document:

* Test objective
* Population and sample selection
* Evidence reviewed
* Test results
* Exceptions (if any)
* Audit conclusion
