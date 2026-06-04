# DAIS demo — Customer Data

Per-customer notes used by the DAIS AI-Governance breakout demo at Databricks.
Each `customers/<ACCOUNT-ID>.md` contains current open issues, escalation risk,
and renewal context for a single customer account.

Access is governed by the Unity Catalog MCP service `demos.dais.github-mcp-dais`:
- Reads under `pii/` are blocked by policy.
- `delete_file` is denied for everyone.
- Writes require a JIRA-* ticket id in the commit message.
