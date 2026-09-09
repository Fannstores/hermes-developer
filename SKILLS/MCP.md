# MCP Engineering

Use MCP as a controlled integration boundary when a project declares it.

## Rules
- Inspect the server's actual tools, schemas, transport, authentication, and lifecycle before integrating.
- Match the real protocol; do not assume an HTTP endpoint is equivalent to a JSON-RPC or session-based MCP transport.
- Validate inputs and outputs at the boundary.
- Handle timeouts, disconnects, malformed responses, and unavailable tools explicitly.
- Never invent tool names, parameters, permissions, or capabilities.
- Keep provider-specific behavior isolated behind a clear adapter when practical.
