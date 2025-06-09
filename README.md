# QuickBooks MCP Server

A Model Context Protocol (MCP) server for integrating QuickBooks with GenAI applications.

## Overview

Accounting and financial management integration

## Features

- Comprehensive QuickBooks API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install quickbooks-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/quickbooks-mcp-server.git
cd quickbooks-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to QuickBooks API requirements.

## Quick Start

```python
from quickbooks_mcp import QuickbooksMCPServer

# Initialize the server
server = QuickbooksMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
