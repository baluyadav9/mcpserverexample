# Installation steps

To Install the 'mymcpserver' MCP server, run the following command:

```json
{
  "mcpServers": {
    "my-mcpserver": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/baluyadav9/mcpserverexample.git",
        "mcp-server"
      ]
    }
  }
}
```

This will fetch and set up the 'mcp-server' from the specified GitHub respository.
