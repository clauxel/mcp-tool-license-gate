# MCP Tool License Gate

Check third-party tool rights before an agent calls them.

Paid remote MCP for MCP tool license checks, vendor policy review, allow/review/deny JSON, alternatives, and license receipts.

## Public Endpoints

- Website: https://mcptoollicense.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://mcptoollicense.clauxel.com/mcp
- Server card: https://mcptoollicense.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcptoollicense/mcptoollicense-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_tool_license`
- `validate_vendor_policy`
- `issue_license_receipt`
- `suggest_allowed_alternative`
- `export_license_audit`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://mcptoollicense.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://mcptoollicense.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://mcptoollicense.clauxel.com/server-card.json
- MCP endpoint: https://mcptoollicense.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
