# GISDB MCP & Agent Plugin (`v0.4.4`)

[![GISDB MCP server quality and maintenance on Glama](https://glama.ai/mcp/servers/mooshee/gisdb-mcp/badges/score.svg)](https://glama.ai/mcp/servers/mooshee/gisdb-mcp)

Browse county property records, save searches, and review available lead packages. Check purchased CSV files in your GISDB account inbox. Owner-name groups reflect recorded names and do not establish a person's identity or willingness to sell.

## Quick start

1. Follow the [GISDB setup guide](https://gisdb.io/integrations/0.4.1) to connect a supported assistant to `https://gisdb.io/mcp`.
2. Ask for records in a county and state. Public questions and record previews require no account or API key. Check the response for sources, dates, and missing information.
3. Sign in to save a search or manage an order. Before a purchase, review the exact offer and choose one dated package or monthly updates.
4. After checkout, check the same order. Confirm payment and CSV availability separately before downloading from your account inbox.

Version 0.4.4 updates package descriptions and instructions. Existing connections and account permissions are unchanged. Read the [release notes](https://github.com/mooshee/gisdb-mcp/releases/tag/v0.4.4) or [release history](https://github.com/mooshee/gisdb-mcp/releases).

## Connect your assistant

### Claude Code / Claude Desktop
```bash
/plugin marketplace add mooshee/gisdb-mcp
claude plugin install gisdb@gisdb-marketplace
claude mcp add --transport http gisdb https://gisdb.io/mcp
```

### VS Code / GitHub Copilot
- [1-Click Install in VS Code](https://insiders.vscode.dev/redirect/mcp/install?name=gisdb&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fgisdb.io%2Fmcp%22%7D)

### OpenAI Codex CLI / Desktop
```bash
codex mcp add gisdb --url https://gisdb.io/mcp
```

The downloadable package also includes the Codex plugin manifest, connection file, and both GISDB skills.

### Cursor
Uses `.cursor-plugin/plugin.json` and `.cursor/mcp.json` (`https://gisdb.io/mcp`).

### Gemini CLI
```bash
gemini extensions install https://github.com/mooshee/gisdb-mcp
```

### Devin CLI / Desktop
```bash
devin plugins install mooshee/gisdb-mcp
```

### AWS Kiro Powers
Import this repository into Kiro Powers (`POWER.md` at repository root).

### Vercel Skills (`skills.sh`) & ClawHub
```bash
npx -y skills add mooshee/gisdb-mcp
clawhub install gisdb-research
```

## Package and review status

The release archives install the existing skills and remote connection. The included OpenAI review draft still needs a verified recording and provider checks before submission. Installing this package does not submit it to a directory or change the hosted service.

## Links
- **Website:** https://gisdb.io
- **MCP Endpoint:** `https://gisdb.io/mcp`
- **Privacy Policy:** https://gisdb.io/privacy
- **Terms of Service:** https://gisdb.io/terms
- **Support:** https://gisdb.io/support


---

Built and maintained by **[Moosh Works](https://mooshworks.com)**.
