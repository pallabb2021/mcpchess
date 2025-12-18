
# MCP Chess Server

A Model Context Protocol (MCP) server for chess operations.

## Installation

This server is installed via `uvx` directly from the GitHub repository.

## Configuration

Add the following to your MCP configuration file:

```json
{
    "mcpserverchess": {
        "command": "uvx",
        "args": [
            "--from",
            "git+https://github.com/pallabb2021/mcpchess.git",
            "chess"
        ]
    }
}
```

## Usage

Once configured, the MCP chess server will be available for chess-related operations through your MCP client.

## Repository

- **Source**: [pallabb2021/mcpchess](https://github.com/pallabb2021/mcpchess.git)
