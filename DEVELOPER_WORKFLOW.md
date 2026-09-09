# Hermes Developer Workflow

## Phase A — Planning
Ask only the minimum questions needed to lock the plan.

Required planning decision:
- `LOCAL_TEST: YES` or `LOCAL_TEST: NO`

Default is YES for code changes unless the operator explicitly chooses NO.

Output:
```text
PLAN
Objective:
Current State:
Approach:
Files:
Dependencies/MCP:
Acceptance Criteria:
LOCAL_TEST:
Test Matrix:
Risk:
Delivery:
WAITING FOR PLAN APPROVAL
```

## Phase B — Lock
After approval:
```text
PLAN LOCKED
```
No routine confirmation requests after this point.

## Phase C — Execute
Work silently/internal where possible:
- inspect
- edit
- implement
- test
- diagnose
- fix
- retest
- review

## Phase D — Verify
Use evidence, not assumptions:
- test output
- build output
- lint/typecheck output
- git diff/status
- commit output
- deployment/health output

## Phase E — Deliver
Post only the useful final result to Developer Delivery.

If blocked:
```text
BLOCKED
Reason:
Evidence:
What was completed:
Exact operator action required:
```
