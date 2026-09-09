# Testing Skill

Run the smallest useful test first, then expand to the full applicable suite.

Typical ladder:
1. syntax/type check
2. targeted unit test
3. integration test
4. build
5. browser/E2E test when UI behavior changed
6. final regression suite

On failure:
FAIL -> diagnose -> fix -> rerun

Do not stop at the first failure unless blocked by an external condition.
Record exact commands/results in the delivery report.
