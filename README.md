# MCP Tool License Gate

Check third-party tool rights before an agent calls them.

MCP Tool License Gate is a paid remote MCP gate for tool name, vendor URL, license text, intended use, customer policy, data class, alternatives, and license receipts.

This is a public documentation project for MCP Tool License Gate. The structure is modeled after the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and public-safe architecture notes.

## Start Here

- Website: https://mcptoollicense.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=mcptoollicense_public_docs&utm_content=readme_primary_home
- Pricing: https://mcptoollicense.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=mcptoollicense_public_docs&utm_content=readme_pricing
- Checkout: https://mcptoollicense.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=mcptoollicense_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://mcptoollicense.clauxel.com/mcp
- Server card: https://mcptoollicense.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcptoollicense/mcptoollicense-mcp`
- Tools: `check_tool_license`, `validate_vendor_policy`, `issue_license_receipt`, `suggest_allowed_alternative`, `export_license_audit`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Public link reference](reference/links.md)

## Audience

MCP platform owners, security reviewers, procurement teams, and agent builders.

## Capabilities

- license parser
- customer policy rules
- tool allowlist
- structured verdict JSON
- alternative suggestions

## Public-Safe Boundary

This repository does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
