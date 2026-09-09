# Debugging & Recovery

When something fails:
1. Reproduce.
2. Capture the actual error.
3. Localize the failing component.
4. Find the smallest safe fix.
5. Add or improve a regression test.
6. Re-run the failing test and relevant regression suite.

Do not repeatedly retry an operation with unknown side effects.
For external actions with uncertain status, reconcile state first.
