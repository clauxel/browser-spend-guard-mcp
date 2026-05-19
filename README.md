# BrowserSpend Guard MCP

Approval receipts for AI browser purchases.

Paid remote MCP for AI browser purchase approval checks, spend thresholds, merchant evidence, risk notes, and audit receipts.

## Public Endpoints

- Website: https://browserspendguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://browserspendguard.clauxel.com/mcp
- Server card: https://browserspendguard.clauxel.com/server-card.json
- Registry name: `com.clauxel.browserspendguard/browserspendguard-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `evaluate_purchase`
- `record_approval`
- `list_budget_alerts`
- `export_purchase_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- [OpenHuman Online](https://openhuman.online/?utm_source=github&utm_medium=readme&utm_campaign=openhuman_public_repos&utm_content=browser_spend_guard_mcp) helps teams keep MCP rollout notes, source context, and approval memory inspectable for human-reviewed workflows.
- Product page: https://browserspendguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://browserspendguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://browserspendguard.clauxel.com/server-card.json
- MCP endpoint: https://browserspendguard.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
