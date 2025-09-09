### reader
paru -S foliate sigil mcomix

### mcp server
```json
{
  "mcpServers": {
    "deepwiki": {
      "url": "https://mcp.deepwiki.com/mcp"
    },
    "context7": {
      "url": "https://mcp.context7.com/mcp"
    },
    "playwright": {
      "command": "npx",
      "args": ["-y", "@playwright/mcp@latest"]
    }
  }
}

```

`claude mcp add -t http context7 https://mcp.context7.com/mcp`      
`claude mcp add -s user -t http deepwiki https://mcp.deepwiki.com/mcp`   
`claude mcp add playwright npx @playwright/mcp@latest`     

