# Internal Control Testing Plan (Simulated)

## Objective
For selected controls, check **design**, evidence availability, and **operating effectiveness** over a fictional nine-month examination period. A real SOC 2 Type II examination is completed by an independent qualified service auditor; this lab is a self-directed readiness exercise.

## Method
1. Define the control owner, frequency, expected artifact, and control population.
2. Request evidence and track owner, due date, status, and location.
3. Verify artifact provenance, applicable period, completeness, and approver sign-off.
4. Select a small illustrative sample. These samples are deliberately limited and **not statistically representative**; a real audit requires risk-based sampling.
5. Compare actual timestamps, approvals, and records to the **fictional internal policies**.
6. Classify: **Pass**, **Exception**, or **Not Tested** (missing evidence).
7. Record the finding, owner, corrective action, and target date.

## Detailed procedures
| ID | Procedure | Expected observation | Lab result |
|---|---|---|---|
| AC-01 | Check 3 access requests for approval before provisioning. | Authorization precedes new access. | Pass |
| AC-02 | Compare 3 exits with account deactivation timestamps. | All accounts disabled within fictional 24h target. | Exception: 1 late |
| AC-03 | Obtain signed Q3 privileged access review. | Timely review and documented follow-up. | Not Tested: missing |
| CH-01 | Inspect 3 production changes, approvals and timestamps. | Approval before deployment. | Pass |
| IR-01 | Inspect annual incident-response tabletop and actions. | Documented execution and assigned follow-up. | Pass |
| VM-01 | Check critical vulnerability closure against fictional 14-day target. | No critical item exceeds policy time. | Exception |
| BC-01 | Inspect quarterly restore tests. | Tests completed and successful. | Pass |
| VR-01 | Obtain critical vendor annual risk assessment and sign-off. | Current signed review for critical vendor. | Not Tested: missing |

## Auditor judgement
- Missing evidence does **not automatically establish a control failure**. It prevents sufficient testing and is treated as an evidence gap pending investigation.
- Document whether exceptions indicate an isolated issue or a systemic failure.
- In a real engagement, review the full population, assess reliability of system-generated reports, and calibrate sample size with the audit team.
- Never upload real PHI or employer confidential records to a public GitHub repo.
