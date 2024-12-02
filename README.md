# MCP (Model Context Protocol) Servers

This repository contains implementations of various MCP servers.

## Servers

### Filesystem Server

Located in `MCP Servers/filesystems/server.py`, this server provides filesystem operations within a restricted directory:

- List directory contents
- Create directories
- Create files
- Modify files

All operations are restricted to the base directory for security.

## Setup

1. Install dependencies:
```bash
pip install mcp
```

2. Run a server:
```bash
python MCP\ Servers/filesystems/server.py
```

## Security

All filesystem operations are restricted to the configured base directory.