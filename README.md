# read
foliate sigil
mcomix

# mcp server
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": ["@upstash/context7-mcp"]
    },
    "deepwiki": {
      "httpUrl": "https://mcp.deepwiki.com/mcp"
    },
    "playwright": {
      "command": "npx",
      "args": ["@playwright/mcp@latest"]
    }
  },
  "selectedAuthType": "oauth-personal"
}

`claude mcp add --transport http context7 https://mcp.context7.com/mcp --header "CONTEXT7_API_KEY: YOUR_API_KEY"  `
claude mcp add context7 -- npx -y @upstash/context7-mcp --api-key YOUR_API_KEY  
claude mcp add -s user -t http deepwiki https://mcp.deepwiki.com/mcp  
claude mcp add playwright npx @playwright/mcp@latest   

