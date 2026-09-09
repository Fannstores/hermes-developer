# Quality Gates

A change is not done merely because it compiles or a single test passes.

## Gates
1. Requirement check
2. Static/type/lint checks when applicable
3. Targeted tests
4. Regression tests
5. Security/dependency review when relevant
6. Build/package verification
7. Runtime or browser verification when relevant
8. Final diff and scope review

Never weaken a gate simply to obtain a green result.
