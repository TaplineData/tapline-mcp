# Security

## Report a vulnerability

Send reports to hello@tapline.sh. Put "Security" in the subject.

Include:

- The affected URL, tool or endpoint (for example `https://api.tapline.sh/mcp`).
- The steps to reproduce.
- The impact you expect.

Do not open a public issue for a vulnerability. Do not put API keys, tokens or personal data in a report. We reply to each report.

## Scope

- The remote MCP server at `https://api.tapline.sh/mcp`, including its OAuth flow.
- The Tapline REST API at `https://api.tapline.sh`.
- The website and dashboard at `https://tapline.sh`.

## Leaked API keys

If a Tapline API key is exposed, revoke it at once in the dashboard under API keys (https://tapline.sh/dashboard?tab=api-keys), then create a new key.
