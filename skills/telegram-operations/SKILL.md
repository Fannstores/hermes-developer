# Telegram Operations

For Telegram room/topic management:
- inspect current state before changing it
- use the canonical 9-room mapping in the project docs
- never claim a topic was created/renamed unless the API confirms it
- if Telegram lacks an endpoint needed for complete reconciliation, report that limitation
  instead of pretending the state was verified
