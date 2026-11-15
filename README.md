# Pedal Manuals

PDF manuals, rebuilt by AI: an agentic Claude Code pipeline converts guitar gear manuals into styled, mobile-friendly HTML, indexed for AI agents via MCP.

## Add a manual

1. Add the device to `catalog.yaml` as `- name: <Brand> <Model>`.
2. Ask the AI agent to process it.

The agent downloads the official PDFs, builds the HTML page, adds it to `index.html`, and adds the page's `slug` to the entry in `catalog.yaml`.

## MCP

Changed manuals are indexed and pushed incrementally to the MCP server [[repo](https://github.com/kyxap1/pedals-mcp.kyxap.pro)] for AI agents:

    claude mcp add --transport http pedals https://pedals-mcp.kyxap.pro/mcp
