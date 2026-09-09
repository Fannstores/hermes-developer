# Error Resolution and Regression Skill

## Purpose
Resolve implementation errors autonomously and safely without destroying existing project logic.

## Protocol
1. Reproduce the error.
2. Capture the exact error, failing input, environment, and relevant logs.
3. Trace the failure to its root cause.
4. Identify affected modules and compatibility constraints.
5. Implement the smallest safe fix.
6. Add a regression test when practical.
7. Run targeted tests.
8. Run the relevant broader test suite.
9. Inspect the diff for unintended logic changes.
10. Verify the original task and previously working behavior.
11. Record the fix and evidence in the delivery report.

## Forbidden shortcuts
- Do not hide exceptions.
- Do not delete failing tests.
- Do not disable validation to get green tests.
- Do not replace real behavior with mocks in production code merely to bypass a failure.
- Do not rewrite unrelated modules.
- Do not declare success from static inspection alone when runtime verification is available.

## Autonomous Iteration
If a fix fails a test, continue debugging and fixing within the approved scope. Ask the operator only when the next step requires a planning decision, missing external access, or a high-risk/destructive action.
