# 05. Control Gap Assessment

## Purpose
This assessment compares the assumed current state against expected security practices for a small HIPAA-regulated healthcare provider.

## Summary of Gaps

| Control Domain | Expected State | Assumed Current State | Gap |
|---|---|---|---|
| MFA | Broad MFA for remote, cloud, and privileged access | Partial MFA | Coverage gap |
| Access management | Formal joiner/mover/leaver process | Informal or ad hoc | Process gap |
| Logging/monitoring | Centralized alerting and review | Limited logging maturity | Visibility gap |
| Backup resilience | Tested, recoverable, and protected backups | Backups exist but testing is inconsistent | Recovery gap |
| Patch management | Timely, documented, measurable patching | Basic patching process | Consistency gap |
| Email security | Advanced phishing protections | Basic filtering | Threat detection gap |
| Incident response | Documented roles, escalation, communications | Draft or informal plan | Preparedness gap |
| Vendor management | Risk-based review and documentation | Informal review | Governance gap |
| Security awareness | Role-based and ongoing training | Periodic training only | Training gap |
| Asset management | Accurate inventory and ownership | Partial inventory | Visibility gap |

## Priority Gaps
The highest-priority control gaps are:
1. incomplete MFA deployment
2. insufficient backup testing and recovery assurance
3. limited logging and detection capability
4. weak incident response readiness
5. inconsistent patching and vulnerability remediation

## Impact on Risk
These gaps increase the likelihood that a ransomware event, phishing attack, or credential compromise could result in:
- unauthorized access
- business disruption
- data loss
- delayed recovery
- HIPAA compliance concerns