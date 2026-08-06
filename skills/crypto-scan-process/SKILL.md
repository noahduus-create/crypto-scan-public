---
name: crypto-scan-process
description: >
  Honest crypto funding/basis/OI process map ritual for agents. Read dual-clock
  board weather, enforce paper_gate, refuse live trade and fake P&L. Free TOF
  for Cursor / Claude / Grok — same family as Crypto Scan Pack ~$49 (not dual SKU).
---

# crypto-scan-process (free agent skill)

**SKU family:** `crypto_scan_pack` · process map only  
**Price:** free skill · paid full pack ~$49 **when listed** (never invent URL)  
**Hard refuse:** live orders · fake P&L · APR theater · “entries from weather”

---

## When to load

- User asks about funding rates, basis bps, OI concentration, “board weather”
- Building agents that consume crypto scan JSON (not trade bots)
- Dist / free-host / MCP attach work for this product family

---

## Ritual order (always)

1. **Dual clock first** — LIVE residual vs PACK stamp. If `live_vs_pack=diverged`, treat LIVE as residual weather only (do **not** re-export pack, do **not** claim edge).
2. **paper_gate** — if `any_paper_candidate=false` → journal/watch language only. Never invent entries.
3. **Symbol row** — funding abs, basis_bps, hourly_call (quiet|watch), OI share if present.
4. **Honesty laws** — process map · NFA · no fake P&L · agents never live trade.
5. **Free vs paid boundary** — free weather/skill/MCP stub ≠ full elevates pack.

---

## Free data paths (factory Mac mini / dogfood)

| Path | Use |
|------|-----|
| `~/ops/data/features/latest.json` | LIVE residual crypto board |
| `~/ops/data/product/public/board-weather-public.json` | Free dual-clock host file |
| `~/ops/data/product/scan-pack/board.json` | PACK stamp (paid attach snap) |
| `~/ops/data/product/public/WHY-PAID-PACK.md` | Elevates 7/7 free→paid map |
| `~/ops/bin/crypto-scan-weather` | CLI one-liner / `--pack-map` / `--export` |
| `~/ops/bin/crypto-scan-mcp-stub.py` | Offline MCP tools over board.json |

Public hosts (when online):

- Gist free sample (dual-clock): see `~/ops/data/product/listing/free-host-url.md`
- Repo: `https://github.com/noahduus-create/crypto-scan-public`

---

## Agent tool order (FUNDING-MCP-LITE)

If MCP stub available:

1. `get_board_weather`  
2. `get_paper_gate`  
3. `get_symbol_row` (optional)  
4. `list_honesty_laws`  

**Never** expose place/cancel/balance/stream order tools.

```bash
python3 ~/ops/bin/crypto-scan-mcp-stub.py --list
python3 ~/ops/bin/crypto-scan-mcp-stub.py call get_board_weather
python3 ~/ops/bin/crypto-scan-mcp-stub.py call get_paper_gate
```

---

## Language allowed

- quiet / watch · heating / cooling · basis premium/discount bps · OI leader share  
- dual clock diverged · residual weather · process map · paper candidate false  
- pack ~$49 when listed (no invented slug)

## Language forbidden

- guaranteed yield / fixed APR / “prints money” / recovery signals  
- live arb right now from pack-stamp numbers under attach freeze  
- dual paid Gumroad SKU invent · VIP signal channel hero

---

## Install (one-paste)

### Cursor

Copy this file to `.cursor/rules/crypto-scan-process.mdc` or project skills folder.  
Keep relative links to free weather JSON in repo/gist.

### Claude Desktop / projects

Paste skill body into project instructions. Attach `board-weather-public.json` or sample board as knowledge when offline.

### Grok

Optional: symlink or copy under `~/.grok/skills/crypto-scan-process/SKILL.md` for operator dogfood (factory already has `crypto-scan-pack` skill for export/list).

---

## Paid boundary (one family)

Free skill + free weather teach the **ritual**.  
Paid zip adds: full wedges, `board.csv`, elevates GATE-LADDER · COST-STACK · SETTLEMENT-CLOCK · PERSISTENCE-MAP · APR-THEATER-KILL · OI-STOCK-VS-CHURN · OI-WEIGHTED-FUND.

See `~/ops/data/product/public/WHY-PAID-PACK.md`.

---

## Success check

- Agent reads dual_clock before recommending any action  
- Agent refuses trade/size when paper_gate false  
- Agent never invents Gumroad URL or P&L  

_Treasure 2026-08-04 · skill-factory / product-saas Slice 2 · free TOF only_
