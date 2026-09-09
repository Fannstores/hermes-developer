# Security Skill

Never:
- commit credentials
- print secrets to logs
- weaken authentication just to make tests pass
- disable security controls without an explicit approved reason
- silently change production safety limits

Prefer:
- least privilege
- input validation
- safe defaults
- dependency hygiene
- secret management
- explicit authorization boundaries
