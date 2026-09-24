# Risk Control Matrix (RCM)

## Purpose

The Risk Control Matrix (RCM) maps identified IT risks to IT General Controls (ITGCs) and defines the planned audit approach for evaluating whether controls are appropriately designed and operating effectively.

The RCM serves as the foundation for control testing by linking:

**Risk → Control Objective → Control Activity → Evidence → Testing Procedure**

---

# Risk Control Matrix

| Control ID | Process                      | Risk                                                            | Control Objective                                                         | Control Description                                                                                          | Frequency    | Control Owner                  | Key Evidence                                                       | Planned Test Procedure                                                                         |
| ---------- | ---------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ------------ | ------------------------------ | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| UAM-01     | User Access Management       | Unauthorized users retain access                                | Ensure only authorized users have appropriate access                      | Quarterly access reviews are performed by application owners to validate user access remains appropriate.    | Quarterly    | Application Owner              | Access review report, reviewer sign-off                            | Inspect access review documentation and verify reviews were completed and approved.            |
| UAM-02     | User Access Management            | Users receive unauthorized or excessive access                  | Ensure access is approved before provisioning                             | User access requests require documented manager approval before access is granted.                           | Per Request  | IT Administrator               | Access request ticket, manager approval, provisioning record       | Select a sample of new users and verify approvals were obtained before access assignment.      |
| UAM-03     | User Access Management          | Terminated users retain access                                  | Ensure access is removed promptly after termination                       | User accounts are disabled within the defined SLA following employee termination.                            | Daily        | IT Administrator               | HR termination report, Okta deactivation log                       | Compare termination dates with account deactivation dates to verify timely removal of access.  |
| UAM-04     | User Access Management | Excessive privileges may result in unauthorized activities      | Ensure privileged access is restricted and periodically reviewed          | Privileged user access is reviewed periodically to validate access remains appropriate.                      | Quarterly    | IAM Team / Application Owner   | Privileged access listing, access review report, reviewer approval | Review privileged access reviews and verify administrator access was approved and appropriate. |
| CHG-01     | Change Management            | Unauthorized production changes may impact system stability     | Ensure production changes are approved, tested, and authorized            | Production changes require documented approval and testing before deployment.                                | Per Change   | Change Manager                 | ServiceNow change ticket, approval record, testing evidence        | Review sample changes and verify approval, testing, and deployment evidence.                   |
| OPS-01     | Computer Operations            | Data loss due to failed backups                                 | Ensure backups complete successfully and failures are investigated        | Backup jobs are monitored daily and failures are investigated and resolved.                                  | Daily        | Infrastructure Operations Team | AWS backup reports, monitoring logs, incident records              | Review backup monitoring reports and verify failed backups were addressed.                     |
| OPS-02     | Computer Operations          | Failed scheduled jobs may impact business operations            | Ensure scheduled jobs execute successfully and failures are identified    | Batch job execution is monitored and failed jobs are investigated and remediated.                            | Daily        | Infrastructure Operations Team | Job monitoring reports, failure alerts, incident tickets           | Review job monitoring records and verify failed jobs were investigated and resolved.           |
| OPS-03     | Computer Operations           | IT incidents may not be identified, tracked, or resolved timely | Ensure incidents are recorded and managed according to defined procedures | IT incidents are logged, assigned, tracked, escalated, and resolved through the incident management process. | Per Incident | IT Operations Team             | Incident tickets, escalation records, resolution notes             | Sample incidents and verify documentation, ownership, escalation, and closure.                 |

---

# Control Testing Approach

For each control, the audit will:

* Evaluate the control design (Test of Design – TOD).
* Test whether the control operated effectively during the audit period (Test of Operating Effectiveness – TOE).
* Obtain and evaluate supporting audit evidence.
* Document any control exceptions identified during testing.
* Determine whether the control is operating effectively.

---

# Related Workpapers

The controls documented in this Risk Control Matrix will be tested through separate audit workpapers:

* **04-User-Access-Management**

  * UAM-01 Quarterly Access Reviews
  * UAM-02 User Provisioning
  * UAM-03 User Deprovisioning
  * UAM-04 Privileged Access Reviews

* **05-Change-Management**

  * CHG-01 Change Management

* **06-Computer-Operations**

  * OPS-01 Backup Monitoring
  * OPS-02 Batch Job Monitoring
  * OPS-03 Incident Management

Each workpaper will document:

* Test objective
* Population and sample selection
* Evidence reviewed
* Test results
* Exceptions identified
* Audit conclusion

---

## Disclaimer

All company names, systems, data, evidence, and scenarios in this portfolio are fictional and created only for learning and demonstration purposes. They do not represent any real organization or audit engagement.
