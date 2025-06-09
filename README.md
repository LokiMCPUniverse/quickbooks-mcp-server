# QuickBooks MCP Server

<div align="center">

# Quickbooks Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/quickbooks-mcp-server?style=social)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/quickbooks-mcp-server?style=social)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/quickbooks-mcp-server?style=social)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/quickbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/quickbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/quickbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/quickbooks-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/quickbooks-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/quickbooks-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/quickbooks-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/quickbooks-mcp-server/graphs/contributors)

</div>

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
