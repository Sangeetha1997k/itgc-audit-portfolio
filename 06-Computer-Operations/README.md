# Computer Operations

## Purpose

This section demonstrates the testing of IT General Controls (ITGC) related to Computer Operations.

The objective is to evaluate whether routine IT operational processes — backup completion, batch job execution, and incident management — are appropriately monitored, and that failures or issues are identified and resolved in a timely manner.

---

## Controls in Scope

| Control ID | Control |
|------------|---------|
| OPS-01 | Backup jobs are monitored daily and failures are investigated and resolved. |
| OPS-02 | Batch job execution is monitored and failed jobs are investigated and remediated. |
| OPS-03 | IT incidents are logged, assigned, tracked, escalated, and resolved through the incident management process. |

---

## Risk

Backup failures may impact data recovery capability. Batch job failures may disrupt business operations or result in inaccurate processing. Incidents that are not identified, tracked, or resolved timely may result in prolonged service disruption or unresolved operational issues.

---

## Control Objective

Ensure that:

- Backup jobs are monitored daily, and failures are investigated and resolved
- Batch jobs are monitored, and failures are identified and remediated
- IT incidents are logged, tracked, escalated, and resolved according to defined procedures

---

## Systems in Scope

- AWS (Backup and Infrastructure Monitoring)
- ServiceNow (Incident Management)

---

## Evidence

| Evidence ID | Description |
|-------------|-------------|
| E-015 | Backup Job Monitoring Report |
| E-016 | Batch Job Monitoring Report |
| E-017 | Incident Register |
| E-018 | Backup Failure Investigation Records |
| E-019 | Batch Job Failure Investigation Records |
| E-020 | Incident Resolution Records |

---

## Audit Testing Approach

Testing will verify that:

- Backup jobs were monitored daily, and failures were identified.
- Failed backup jobs were investigated and resolved.
- Batch jobs were monitored, and failures were identified.
- Failed
