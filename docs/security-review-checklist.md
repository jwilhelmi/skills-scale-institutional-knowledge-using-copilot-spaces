# Security Review Checklist

Purpose
- Ensure meaningful security review and mitigation are applied for changes that have security impact.

When to run
- Major changes to authentication, authorization, data storage, encryption, network boundaries, or third-party integrations.

Checklist
- [ ] Security Reviewer assigned
- [ ] Threat model updated for the change
- [ ] Sensitive data flows documented
- [ ] CI security scans and SAST/DAST results reviewed
- [ ] Dependency / supply-chain review completed
- [ ] Required compliance/legal checks completed or flagged
- [ ] Remediations assigned with owners and timelines

Outcomes
- Security Reviewer signs off or documents accepted risk and mitigation in the issue/PR.
