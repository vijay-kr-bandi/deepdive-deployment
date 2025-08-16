# DeepDive Deployment

A Model Context Protocol (MCP) server implementation for DeepDive deployments.

## Installation

You can install this package using `uvx`:

```bash
uvx --from git+https://github.com/vijay-kr-bandi/deepdive-deployment.git mcp-server
```

This command will install the MCP server directly from the GitHub repository.

## Configuration

Add the following configuration to your Model Context Protocol (MCP) settings:

```json
{
  "Addition": {
    "command": "uvx",
    "args": [
      "--from",
      "git+https://github.com/vijay-kr-bandi/deepdive-deployment.git",
      "mcp-server"
    ]
  }
}
```

### Usage

1. First, install the package using the installation command above
2. Add the configuration to your MCP settings
3. The server will be available for deployment operations through your MCP client
