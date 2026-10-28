---
name: gisdb
displayName: GISDB
version: 0.4.3
author: Daniel Hallman
description: Source-backed county property records, owner portfolios, and parcel datasets.
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

Author: Daniel Hallman ([Moosh Works](https://mooshworks.com))

Source-backed county property records, owner portfolios, and parcel datasets. Ask relevant questions, preview recorded facts, save search criteria, and check account-inbox CSV delivery status. Weekly source checks do not guarantee new records. Notice, delinquency and municipal enrichment, CAD exports, and motivation scoring remain unavailable. Built by Moosh Works (https://mooshworks.com).

## Quick start

1. Visit [GISDB](https://gisdb.io) or connect Kiro to `https://gisdb.io/mcp`.
2. Built and maintained by [Moosh Works](https://mooshworks.com).

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
