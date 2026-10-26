---
name: gisdb
displayName: GISDB
version: 0.4.2
author: Daniel Hallman
description: Source-backed county property records, owner-name portfolios and three Hamilton County lead packages.
keywords:
  - property-records
  - county-data
  - leads
  - saved-searches
  - mcp
mcpServers:
  gisdb:
    type: streamable-http
    url: https://gisdb.io/mcp
---

# GISDB Power (AWS Kiro)

Author: Daniel Hallman

Source-backed county property records, owner-name portfolios and three Hamilton County lead packages. Ask relevant questions, preview recorded facts, save a search, and review an available single-package or monthly offer before checkout. A separate GISDB account shows payment, subscription and account-inbox CSV delivery status. Prices and coverage come from current reviewed offers. Weekly source checks do not guarantee new records. Notice, delinquency and municipal enrichment, CAD exports and motivation scoring remain unavailable.

## Quick start

1. Visit [GISDB](https://gisdb.io) or connect Kiro to `https://gisdb.io/mcp`.

## MCP Server Configuration

```json
{
  "mcpServers": {
    "gisdb": {
      "type": "streamable-http",
      "url": "https://gisdb.io/mcp"
    }
  }
}
```

## Tools Available

- `gisdb_cancel_subscription`
- `gisdb_continue_search`
- `gisdb_create_checkout`
- `gisdb_get_lead_updates`
- `gisdb_get_metadata`
- `gisdb_get_order`
- `gisdb_get_search`
- `gisdb_guide_search`
- `gisdb_list_saved_searches`
- `gisdb_open_billing_portal`
- `gisdb_save_search`
- `gisdb_search_catalog`
- `gisdb_search_records`
- `gisdb_set_lead_updates`
- `gisdb_start_search`
