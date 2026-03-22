<p align="center">
  <img src="https://raw.githubusercontent.com/mcpware/.github/main/logo-full-light.svg" width="400" alt="mcpware">
</p>

<p align="center">
  <strong>Open source MCP tools — bridging you and AI</strong>
</p>

<p align="center">
  <a href="https://www.npmjs.com/org/mcpware">npm</a> ·
  <a href="https://github.com/mcpware">GitHub</a>
</p>

---

### Our Tools

| Tool | What it does | Install |
|------|-------------|---------|
| 🔌 [Instagram MCP](https://github.com/mcpware/instagram-mcp) | 23 Instagram Graph API tools — posts, comments, DMs, stories, analytics | `npx @mcpware/instagram-mcp` |
| 📊 [Claude Code Organizer MCP](https://github.com/mcpware/claude-code-organizer) | Visual dashboard for Claude Code configs — memories, skills, MCP, hooks | `npx @mcpware/claude-code-organizer` |
| 🏷️ [UI Annotator](https://github.com/mcpware/ui-annotator-mcp) | Hover labels on any web page — AI references elements by name | `npx @mcpware/ui-annotator-mcp` |
| 🎬 [Pagecast MCP](https://github.com/mcpware/pagecast) | Record browser sessions as GIF/video via MCP | `npx @mcpware/pagecast` |
| 🎨 [LogoLoom MCP](https://github.com/mcpware/logoloom) | AI logo design → SVG → full brand kit export | `npx @mcpware/logoloom` |

### Quick Start

Every tool is one command away:

```bash
npx @mcpware/<tool-name>
```

Or add to your Claude Code / Cursor `.mcp.json`:

```json
{
  "mcpServers": {
    "tool-name": {
      "command": "npx",
      "args": ["-y", "@mcpware/tool-name"]
    }
  }
}
```

All tools are free, open source, and run locally.
