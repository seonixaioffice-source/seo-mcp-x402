# SEO MCP x402 — SEO Tools & Token Verdict

Paid SEO tools and a Token Security & Verdict API for AI agents. Pay per call with USDC on Base via x402.

**Live URL:** https://seo-mcp-x402.abacusai.app

## Tools & Pricing

| Tool | Price | Description |
|------|-------|-------------|
| crawl_page | $0.01 | Crawl page and extract title, meta, headings, word count, internal links |
| audit_core_web_vitals | $0.02 | Core Web Vitals audit (LCP, INP, CLS, TTFB) via PageSpeed Insights |
| backlink_check | $0.03 | Referring domains sample, domain authority and trust score estimate |
| keyword_research | $0.05 | Search volume, difficulty and live top 10 results |
| competitor_analysis | $0.10 | Estimated traffic, top keywords, content gaps, indexed pages |

## Token Security & Verdict

POST /verdict — $0.02

Send {"address": "0x...", "chain": "base" | "ethereum"} and receive a risk score (0-100), flags, liquidity, holder concentration, honeypot indicators, top holders and a short summary.

## MCP Config

```json
{
  "mcpServers": {
    "seo-mcp-x402": {
      "url": "https://seo-mcp-x402.abacusai.app/mcp"
    }
  }
}
```

## Links

- Live service: https://seo-mcp-x402.abacusai.app
- x402scan: https://www.x402scan.com/server/6e8e6ee7-ebdc-4314-a726-bbcb0289e870
- OpenAPI: https://seo-mcp-x402.abacusai.app/openapi.json
- Manifest: https://seo-mcp-x402.abacusai.app/.well-known/x402
