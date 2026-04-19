# Model Contex Protocol

Model Context Protocol — an architecture for coordination AI agent with external tools

⚙️ How it works step by step:

- User: “What about the weather in France?”

*Model sees available tool: get_weather(city) and decides to call this intrument*

- client (claude desktop/cursor..) sends request on MCP server: get_weather("France")

- Server responds: { temperature: 18, condition: "cloudy" }

# Claude mcp

[Adding mcp to claude](/mcp/claude_mcp.md)

# Usefull mcp's

[Usefull set of MCP servers](/mcp/usefull_mcp.md)