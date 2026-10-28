---
name: gisdb
displayName: GISDB
version: 0.4.4
author: Daniel Hallman
description: Browse county records and group parcels by recorded owner name.
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

# GISDB for Kiro

Author: Daniel Hallman ([Moosh Works](https://mooshworks.com))

Browse county property records, group parcels by recorded owner name, and find available datasets. Preview records, save a search, and check whether your purchased CSV is ready in your account inbox. Weekly checks may find no new records. Added notice, delinquency and municipal data, CAD exports, and estimates of an owner's willingness to sell are unavailable. Built by Moosh Works (https://mooshworks.com).

## Quick start

1. Open [GISDB](https://gisdb.io) for county records and setup instructions.
2. Add `https://gisdb.io/mcp` as an MCP server in Kiro using the configuration below. Complete any required sign-in.
3. Check that the connection lists the tools before starting a task.

## Server configuration

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

## Available tools

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
