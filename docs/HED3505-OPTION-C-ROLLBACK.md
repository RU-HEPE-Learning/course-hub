# HED3505 Option C — Rollback & Removal Procedure

## Trigger
Use rollback if:
- student-specific work is exposed publicly;
- private-channel access is misconfigured;
- submission/feedback path fails;
- HIGH/BLOCKER defect appears.

## Procedure
1. Pause new pilot activity.
2. Stop further submission through the affected path.
3. Restrict/remove unintended access where the private platform permits.
4. Preserve only minimum non-sensitive diagnostic evidence.
5. Correct the access/workflow defect.
6. Re-verify privacy, submission, feedback, and revision paths.
7. Resume only after PASS.

## Public GitHub rollback
If the public learning layer itself regresses:
- revert affected commit to last known-good state;
- run Structure Check/CI;
- verify Course Hub → HED3505 → Lab.

## Rule
Never copy exposed private student content into a public issue or repository.
