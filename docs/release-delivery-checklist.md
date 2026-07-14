# Release & Delivery Checklist

Purpose
- Provide a concise, repeatable checklist to ensure releases are coordinated, safe, and observable.

Before Release
- [ ] Confirm all PRs merged and CI is green
- [ ] Security scan results reviewed and resolved (or accepted with mitigation)
- [ ] Release / Delivery Lead assigned and notified
- [ ] Stakeholders notified of release window
- [ ] Backups/snapshots prepared if applicable
- [ ] Rollback plan documented and validated
- [ ] Smoke tests defined and automated where possible
- [ ] Monitoring and alerting dashboards ready for post-deploy

During Release
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (follow runbook)
- [ ] Run post-deploy smoke tests
- [ ] Monitor key signals for 15-60 minutes (as defined by the Release Lead)

After Release
- [ ] Announce completion to stakeholders and support
- [ ] Create short post-deploy verification summary
- [ ] Open follow-up items (bugs, telemetry gaps) and assign owners
- [ ] Schedule post-release review if any incidents occurred

Notes
- Reference the Release Lead in the PR description using @ (e.g., @release-lead) and include the issue number (e.g., Relates to #4) to link work.
