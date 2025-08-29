# read
foliate sigil
mcomix

# mcp server
gemini  mcp add --transport http context7 https://mcp.context7.com/mcp
gemini mcp add  -t http deepwiki https://mcp.deepwiki.com/mcp
claude mcp add --transport http context7 https://mcp.context7.com/mcp --header "CONTEXT7_API_KEY: YOUR_API_KEY"
claude mcp add -s user -t http deepwiki https://mcp.deepwiki.com/mcp
claude mcp add playwright npx @playwright/mcp@latest
