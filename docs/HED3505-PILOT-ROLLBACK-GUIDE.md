# HED3505 Pilot — Rollback Guide

## Trigger rollback when

- BLOCKER/HIGH defect affects learner workflow;
- privacy boundary is breached or at material risk;
- submission/feedback path becomes ambiguous or unavailable;
- live lab link is broken;
- course-hub navigation points to an unsafe or obsolete route.

## Rollback sequence

1. Stop new student onboarding.
2. Announce that the pilot is paused.
3. Preserve only the minimum non-sensitive evidence needed for diagnosis.
4. Revert the affected repository commit/merge to the last known-good state.
5. Run repository CI/Structure Check.
6. Verify Course Hub → HED3505 → Lab path.
7. Re-open pilot only after the defect is documented and acceptance criteria pass.

## Data rule

Do not copy student-specific content into a public issue, public repo, or troubleshooting document.

## Authority

Human academic and privacy judgment overrides automation.
