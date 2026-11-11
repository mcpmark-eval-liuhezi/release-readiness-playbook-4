# Rollback Plan

- [ ] Identify the last known-good release tag before the deploy window
- [ ] Confirm rollback owner is reachable before any production push
- [ ] Document the trigger criteria that would force a rollback (error rate > 2%, p95 latency > 500ms, customer escalations)
- [ ] Inventory the exact commands and traffic-shift steps to route traffic back to the previous version
- [ ] Verify database migrations are reversible or have a matching downgrade path
- [ ] Pre-stage the feature-flag toggle to disable the new version
- [ ] Run a table-top rollback rehearsal at least 24 hours before the release
- [ ] Assign a single incident commander for the rollback window
