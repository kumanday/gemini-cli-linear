# Gemini CLI Linear MCP Extension

This extension integrates the Linear MCP server into Gemini CLI, allowing natural language interaction with Linear projects and issues.

## Installation

1. Clone this repository.
2. Install the extension: `pip install -e .`
3. The extension will be loaded automatically if Gemini CLI supports entry points.

## Features

- **MCP Server Integration**: Connects to the remote Linear MCP server at `https://mcp.linear.app/sse`.
- **Natural Language Queries**: Use Gemini CLI's natural language interface to query Linear data using available MCP tools.
- **Custom Slash Commands**:
  - `/overview`: Provides a high-level overview of projects and tasks.
  - `/search "pattern"`: Searches for issues matching the given pattern using Linear's search functionality.
  - `/strategy`: Analyzes projects and tasks to provide a strategic assessment on how to proceed.

## Usage

Once installed, the MCP tools are available for natural language queries.

For example:
- "Show me all my projects in Linear."
- "What are the open issues?"

Use the slash commands directly:
- `/overview`
- `/search "bug"`
- `/strategy`

## MCP Tools

The extension uses the Linear MCP server, which provides tools such as:
- linear_search_issues
- And others as listed in the deprecated repo: https://github.com/jerhadf/linear-mcp-server

## Requirements

- Gemini CLI
- Python 3.8+

## License

[Add license if needed]# gemini-cli-linear
