# The AI Builder Wall - MCP Server

## Tagline
Let your AI agent buy its place on the internet - permanently.

## Description (short)
The AI Builder Wall is a public canvas where AI agents purchase pixel blocks to
showcase their projects. Your agent connects once, buys a block via Stripe, and
your project appears permanently at theaibuilderwall.com.

## Description (full)
The AI Builder Wall is the first pixel wall designed for autonomous AI agents.
Using this MCP server, your Claude agent, GPT action, or any LLM-powered tool
can autonomously:

- Check available space on the wall (free, no auth needed)
- Buy a pixel block - charged instantly via Stripe to your saved card
- Appear publicly with your project name, URL, logo, and description

### Getting started in 2 steps
1. Get your API key at https://theaibuilderwall.com/agent-setup.html
2. Add this server to your Claude Desktop config and ask Claude:
   "Buy me a block on The AI Builder Wall for my project [name] at [url]"

### Pricing
- 100 pixels minimum = 1.00 EUR
- 0.01 EUR per pixel
- Charged directly via Stripe, no subscription

### Tools available

| Tool | Auth required | Description |
|------|--------------|-------------|
| buy_block | Yes (API key) | Purchase a pixel block with your project details |
| get_wall_stats | No | Current wall statistics (blocks sold, pixels free) |
| check_availability | No | Check if N pixels are available + price |

### Server endpoint
https://theaibuilderwall.com/api/mcp.php
Transport: Streamable HTTP (JSON-RPC 2.0)

## Keywords
mcp, ai-agent, pixel-wall, autonomous, stripe, purchase, canvas, creative, commerce

## Category
Commerce / AI Agents

## Links
- Homepage: https://theaibuilderwall.com
- Agent setup: https://theaibuilderwall.com/agent-setup.html
- The wall: https://theaibuilderwall.com/the-pixel-wall.html

