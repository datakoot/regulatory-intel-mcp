# Regulatory Intel MCP — by Datakoot

The US Federal Register for AI agents — as MCP tools your agent can call mid-task to search and track federal rules, notices and executive orders. No API keys.

## Tools

| Tool | What it does | Source |
|---|---|---|
| `search_documents` | Search rules, proposed rules, notices and presidential documents by term, agency and date | Federal Register |
| `document` | Full detail on one document: abstract, effective date, comment deadline, CFR refs, citation | Federal Register |
| `recent_documents` | The newest filings, filterable by type and agency, over a look-back window | Federal Register |
| `executive_orders` | Recent presidential executive orders | Federal Register |
| `agencies` | Look up federal agencies and their slugs (to filter the other tools) | Federal Register |

No API keys required.

## Quick start

```
claude mcp add --transport http regulatory-intel https://regulatory.datakoot.com/mcp
```

Or point any MCP client at `https://regulatory.datakoot.com/mcp`.

## Data & attribution

All data comes from the [Federal Register API](https://www.federalregister.gov/developers/documentation/api/v1) (Office of the Federal Register / GPO), which is US-government public domain. This is an informational lookup over the official public record — not legal advice. Always verify against [federalregister.gov](https://www.federalregister.gov) before relying on it.

Part of [Datakoot](https://datakoot.com) — keyless intelligence APIs for AI agents.
