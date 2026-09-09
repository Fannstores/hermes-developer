# Hermes Telegram Room Operating Mode

## Operator setup
The operator should only be asked for the **Telegram Group/Chat ID**.

The Hermes Telegram bot token is treated as part of the Hermes installation/package configuration
and must NOT be requested from the operator again if it is already provisioned by the installation.

Never print, echo, or expose the token.

## Room model

Telegram is split into two functional layers:

### A. Developer Workspace
These rooms are for Hermes' engineering work:
- Planning / Discussion
- Workspace / Execution
- Delivery / Completed

The operator mainly discusses and approves plans in Planning.
After approval, Hermes works autonomously in Workspace.
Completed projects/results are posted to Delivery.

