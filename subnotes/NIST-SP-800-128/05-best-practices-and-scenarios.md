# 05 - Best Practices and ISSMP Scenarios

## High-Value Practices
- Use standardized secure baselines (e.g., recognized checklists/benchmarks).
- Enforce least functionality (ports/protocols/services).
- Integrate patch management with formal change control.
- Restrict who can make configuration changes.
- Test before production and verify after deployment.
- Archive prior baselines for rollback and audit support.
- Use automated monitoring where possible (with validated tooling approaches).

## Typical ISSMP Scenarios

### Scenario 1: Emergency patch bypassed CCB
- Correct action: implement emergency process + retroactive review, impact analysis, and record updates.

### Scenario 2: Unauthorized wireless AP discovered
- Correct action: treat as unauthorized component, isolate, investigate, reconcile with inventory and change logs.

### Scenario 3: New app requires insecure config exception
- Correct action: document deviation, perform risk analysis, apply compensating controls, obtain approval.

### Scenario 4: Drift detected but no incident yet
- Correct action: remediate drift and investigate process/control failure before compromise occurs.

## Quick Memory Line
- **No baseline integrity -> no trustworthy security posture.**

Source: [NISTSP800128.pdf](NISTSP800128.pdf)
