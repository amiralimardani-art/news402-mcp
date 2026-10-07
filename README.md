# news402-mcp

Hacker News top/new stories and full-text search — paid via x402 micropayments (0.01 USDC/call on Base mainnet).

[![smithery badge](https://smithery.ai/badge/amir-alimardani/news402-mcp)](https://smithery.ai/servers/amir-alimardani/news402-mcp)

## Tools

| Tool | Description |
|------|-------------|
| `get_top_stories` | Current top HN stories (title, URL, score, comments, author) |
| `get_new_stories` | Newest HN stories |
| `search_stories` | Full-text search via Algolia HN API |

## Usage

```json
{"count": 5}
{"count": 10}
{"query": "AI agents", "count": 5}
```

## Pricing

0.01 USDC per call on Base mainnet via [x402](https://x402.org) protocol.

Endpoint: `https://news402.persikos.com`

## License

MIT
