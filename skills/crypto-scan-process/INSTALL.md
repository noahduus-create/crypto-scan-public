# Install — crypto-scan-process (free)

**1 file. No network. No trade tools. No dual SKU.**

## Cursor

```bash
mkdir -p .cursor/rules
cp ~/ops/data/product/dist/agent-skills/crypto-scan-process/SKILL.md \
  .cursor/rules/crypto-scan-process.mdc
```

Or paste SKILL body into Cursor project rules UI.

## Claude project

1. New project → instructions = SKILL.md body  
2. Optional knowledge: `~/ops/data/product/public/board-weather-public.json`  
3. Optional tools: run FUNDING-MCP-LITE stub locally (see host snippets under `~/ops/data/product/mcp/`)

## Claude Desktop MCP (local board)

```bash
# snippet: ~/ops/data/product/mcp/host-claude-desktop.snippet.json
python3 ~/ops/bin/crypto-scan-mcp-stub.py --mcp
```

## Quick dogfood

```bash
~/ops/bin/crypto-scan-weather
~/ops/bin/crypto-scan-weather --pack-map
python3 ~/ops/bin/crypto-scan-mcp-stub.py call get_paper_gate
```

## Marketplace / 60s install

| Surface | Path |
|---------|------|
| **60s multi-host (Cursor / Claude / Grok)** | `~/ops/data/product/public/AGENT-INSTALL-60S.md` |
| **Claude skill directory listing copy** | `~/ops/data/product/dist/marketplace/claude-skill-listing.md` |
| Free→paid boundary | `~/ops/data/product/public/WHY-PAID-PACK.md` |
| MCP Desktop | `~/ops/data/product/mcp/INSTALL-DESKTOP.md` |

Same family · **not** dual SKU. Listing copy for cryptoskills-style catalogs only.

## Paid CTA

Only after storefront listed — point to real public URL. Until then: “Crypto Scan Pack ~$49 when listed.”  
Never invent Gumroad URL. Process map only · no fake P&L · paper until Noah promotes live.
