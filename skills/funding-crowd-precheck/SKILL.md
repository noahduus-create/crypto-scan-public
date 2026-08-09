---
name: funding-crowd-precheck
description: >
  Ticker-first funding crowd precheck before any size thought. Decode who pays
  whom, capital-weighted vs equal-weight heat, gate rung (quiet/watch/paper),
  persistence vs snapshot theater. Free TOF skill · same family as Crypto Scan
  Pack ~$49 (not dual SKU). Refuse live trade and fake P&L.
---

# funding-crowd-precheck (free agent skill)

**SKU family:** `crypto_scan_pack` · process map only  
**Price:** free skill · paid full pack ~$49 **when listed** (never invent URL)  
**Hard refuse:** live orders · fake P&L · APR theater · entries from weather  

Complements board-first `crypto-scan-process`. Use this when the user names a
**ticker** or asks “who pays / is funding crowded / check funding before enter.”

---

## When to load

- “Check funding on SOL/BTC before I enter”
- “Who pays whom on perps right now?”
- “Crowded long / funding rent / equal-weight heatmap FOMO”
- Pre-trade literacy (not signal generation)

---

## Ritual order (ticker-first · always)

1. **Name the symbol** — pull row from features or free public CSVs (never invent rates).
2. **Who pays** — sign of `last_funding`: longs pay shorts if positive (venue convention may vary — state factory convention: Binance-style positive = longs pay).
3. **Crowd label** — pair abs funding with OI share:
   - Prefer free **OI-WEIGHTED-FUND** ratio (capital vs equal-weight).
   - Loud light-share name + low capital contrib → **thin_name_noise**.
4. **Gate rung** — free **GATE-LADDER**: R0 quiet / R1 watch / R2 paper only if streak≥3 and |f|>0.001.
5. **Persistence kill** — free **PERSISTENCE-MAP**: one loud hour ≠ process signal; check flip% + max same-sign run.
6. **paper_gate** — if `any_paper_candidate=false` → journal/watch language only. **Never size.**
7. **Paid boundary** — point to WHY-PAID + pack ~$49 when listed (no invented Gumroad URL).

---

## Free data paths

| Path | Use |
|------|-----|
| `~/ops/data/features/latest.json` | LIVE residual board |
| `~/ops/data/product/public/oi-weighted-fund-free.json` | Capital-weighted funding |
| `~/ops/data/product/public/gate-ladder-free.json` | R0/R1/R2 rungs |
| `~/ops/data/product/public/persistence-map-free.json` | Sign hit-rate lookback |
| `~/ops/data/product/public/apr-theater-kill-free.json` | Naive APR theater kill |
| `~/ops/data/product/public/WHY-PAID-PACK.md` | Free vs paid elevates |

```bash
python3 ~/ops/bin/export-oi-weighted-fund-free.py
python3 ~/ops/bin/export-gate-ladder-free.py
python3 ~/ops/bin/export-persistence-map-free.py
```

---

## Language allowed

- who pays · funding rent · capital-weighted vs equal-weight  
- quiet / watch / paper ladder · streak n/3 · persistence · flip rate  
- process map · residual weather · pack ~$49 when listed  

## Language forbidden

- guaranteed yield · fixed APR · “prints money” · recovery signals  
- live arb from pack-stamp under attach freeze  
- dual paid Gumroad SKU invent  

---

## Success check

- Agent answers ticker funding without inventing a number  
- Agent refuses size when paper_gate false or rung < R2  
- Agent prefers capital-weighted read over equal-weight heatmap FOMO  

_Treasure 2026-08-08 · skill-factory free TOF · not dual SKU_
