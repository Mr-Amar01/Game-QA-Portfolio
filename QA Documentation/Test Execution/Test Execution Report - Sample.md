# Test Execution Report – Sample

> **Simulated portfolio data.** Numbers below are illustrative and do not represent production testing results.

## Execution Summary

| Metric | Result |
|---|---:|
| Planned | 100 |
| Executed | 95 |
| Passed | 78 |
| Failed | 12 |
| Blocked | 5 |
| Not Run | 5 |
| Pass Rate | 82.1% |

## Observations
- Core gameplay smoke checks passed.
- Several failures were concentrated around progression and recovery scenarios.
- Network-dependent cases were affected by controlled connectivity conditions.
- Blocked cases were dependent on unresolved upstream issues.

## Defect Handling
Failed cases should be linked to individual bug reports where possible. Blocked cases should identify the dependency preventing execution.

## Exit Recommendation
For portfolio demonstration, release readiness should be determined only after reviewing critical/high defects, regression results and agreed exit criteria.