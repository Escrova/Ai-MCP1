# MCP Starter Dependencies

This repository includes the core Python dependencies needed to build an MCP (Model Context Protocol) server.

## Installed dependencies

- `mcp`: Official Python SDK for MCP servers and clients.
- `httpx`: Useful for calling external HTTP APIs from MCP tools.
- `pydantic`: Data validation for tool inputs and structured schemas.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Next step

Start implementing your MCP server using the `mcp` package.
