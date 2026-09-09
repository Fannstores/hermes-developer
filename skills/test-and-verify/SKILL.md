# Test & Verify

## Required loop
IMPLEMENT -> RUN TEST -> READ REAL OUTPUT -> FIX -> RUN AGAIN

Use the strongest practical local checks:
- syntax/compile checks
- unit tests
- integration tests
- lint/type checks when configured
- smoke tests
- deterministic CLI checks
- mocked external services when real services are unavailable

Never replace a failed test with a claim that it is probably fine.
Record exact commands and outcomes in the completion report.
