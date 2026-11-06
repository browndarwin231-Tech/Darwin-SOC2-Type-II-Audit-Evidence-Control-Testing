# SOC 2 Type II Audit Evidence Collection & Control Testing
**Portfolio lab | Fictional healthcare SaaS company | Simulated records only**

## Executive summary
I performed a **simulated internal audit readiness assessment**, collecting illustrative evidence, mapping eight selected controls to candidate AICPA Trust Services Criteria, testing samples, and documenting exceptions/remediation. This is **not** a SOC 2 report, independent audit, certification, or a claim of real-world compliance.

## Scope and assumptions
- Scenario: imaginary healthcare software provider **Nova Care Cloud** (not a real client).
- Simulated review period: **January 1–September 30, 2026**.
- In-scope: illustrative **Security** controls plus one **Availability** control.
- Out-of-scope: full SOC 2 population, full criteria assessment, third-party systems, actual PHI, and external auditor attestation.
- Internal performance thresholds (24-hour deprovisioning; 14-day critical remediation) are **fictional company policy**, not universal SOC 2 requirements.
- Criterion identifiers are **illustrative mappings** requiring independent verification against official AICPA Trust Services Criteria.

## Project deliverables
1. `SOC2_Audit_Evidence_Tracker.xlsx` — dashboard, control register, evidence status, test workpapers, findings and sources.
2. `sample_evidence/` — synthetic CSV records to inspect.
3. `CONTROL_TESTING_PLAN.md` — reproducible procedures and sampling approach.
4. `AUDIT_READINESS_REPORT.md` — executive summary, limitations, findings and proposed remediation.

## Summary of simulated results
| Metric | Result |
|---|---:|
| Selected controls | 8 |
| Evidence marked complete | 5 |
| Evidence partial | 1 |
| Evidence missing | 2 |
| Passing control tests | 4 |
| Exceptions identified | 2 |
| Not tested due to missing evidence | 2 |
| Open findings | 4 |

**Observation:** A control can have an artifact marked **Complete** and still **fail its test**. Completeness means the requested file arrived; the test checks whether the control operated as expected.

## How to reproduce
1. Open the workbook and review `Control Register` and `Evidence Tracker`.
2. Inspect synthetic source files in `sample_evidence/`.
3. Follow each test in `CONTROL_TESTING_PLAN.md`; record a result and evidence reference.
4. Review `Findings` and the `AUDIT_READINESS_REPORT.md`.
5. Experiment: change evidence status or finding status, then check Dashboard metrics.

## Safe portfolio language
"Built a simulated SOC 2 Type II audit-readiness lab covering eight selected security/availability controls; created an evidence tracker, performed sample-based internal control tests, and documented four findings with owners and remediation timelines."

## References
- AICPA SOC suite: https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services/
- AICPA Trust Services Criteria: https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022
- AICPA description criteria: https://www.aicpa-cima.com/resources/download/get-description-criteria-for-your-organizations-soc-2-r-report

No real employee, vendor or patient information is included.
