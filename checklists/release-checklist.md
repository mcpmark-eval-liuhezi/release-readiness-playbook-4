# Release Checklist

- [ ] Confirm release criteria met (feature complete, no P0/P1 bugs open)
- [ ] Get release sign-off from product, engineering, and support leads
- [ ] Draft customer comms (release notes, expected timestamps, known issues)
- [ ] Verify metrics dashboard baselines are green pre-release
- [ ] Pre-stage the rollback plan and confirm rollback owner is on call
- [ ] Freeze scope: no new features after this point
- [ ] Run post-release smoke tests against staging
- [ ] Notify the war room channel when the deploy window is live
- [ ] Confirm success metrics are being reported (error rate, latency p95, conversion)
