# Framelink Figma MCP Server Extension for Zed

This extension integrates [Framelink Figma MCP Server](https://github.com/GLips/Figma-Context-MCP)
as a context server for Zed's Assistant.

You'll need to grab a Figma access token for your account.
Set the permissions `read-only` for _File Content_ and _Dev Resources_.

```
"context_servers": {
    "mcp-server-figma": {
      "settings": {
        "figma_api_key": "<FIGMA_API_KEY>"
      }
    }
  },
```
