# GISDB MCP & Agent Plugin (`v0.4.2`)

[![GISDB MCP server quality and maintenance on Glama](https://glama.ai/mcp/servers/mooshee/gisdb-mcp/badges/score.svg)](https://glama.ai/mcp/servers/mooshee/gisdb-mcp)

Source-backed county property records, owner-name portfolios and three Hamilton County lead packages. Ask relevant questions, preview recorded facts, save a search, and review an available single-package or monthly offer before checkout.

## Quick start

1. Open [GISDB](https://gisdb.io) in your browser or connect your MCP client to `https://gisdb.io/mcp` (or `https://gisdb.io/api/v1/mcp`).
2. Public catalog discovery, guided search questions, and record previews require no account or API key.

## Install Across Agent Harnesses

### Claude Code / Claude Desktop
```bash
/plugin marketplace add mooshee/gisdb-mcp
claude plugin install gisdb@gisdb-marketplace
claude mcp add --transport http gisdb https://gisdb.io/mcp
```

### VS Code / GitHub Copilot
- [1-Click Install in VS Code](https://insiders.vscode.dev/redirect/mcp/install?name=gisdb&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fgisdb.io%2Fmcp%22%7D)

### OpenAI Codex CLI / Desktop
Add `.codex-plugin/plugin.json` or `.mcp.json` pointing to `https://gisdb.io/mcp`.

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

## Links
- **Website:** https://gisdb.io
- **MCP Endpoint:** `https://gisdb.io/mcp`
- **Privacy Policy:** https://gisdb.io/privacy
- **Terms of Service:** https://gisdb.io/terms
- **Support:** https://gisdb.io/support


---

Built and maintained by **[Moosh Works](https://mooshworks.com)**.
