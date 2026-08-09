# Cross-venue funding clock — free process map

**Treasure ship 2026-08-06 · NEW domain (HL 1h vs CEX 8h)**
**Exported:** 2026-08-06T06:03:42Z
**Honesty:** process map only · **no fake P&L** · **no entries** · not arb advice

## Why this exists

Competitors ship multi-exchange funding heatmaps and arb scanners. They rarely teach the **clock mismatch**:

| Venue class | Typical funding interval | APR-theater trap |
|-------------|--------------------------|------------------|
| Binance USDⓈ-M (most pairs) | **8 hours** (00/08/16 UTC) | Treating one print as daily yield |
| Hyperliquid perps | **1 hour** | Comparing raw hourly rate to CEX 8h without normalize |
| Free scanners on X | mixed | Annualize one snapshot → fake edge narrative |

Noah free TOF = **name the clocks → normalize units → paper_gate → refuse theater**.
Paid pack elevates (SETTLEMENT-CLOCK, APR-THEATER-KILL, COST-STACK) when listed ~$49.

## Process rungs (do in order)

1. **R0 — Name the clocks** — Write venue interval on the page before numbers.
2. **R1 — Normalize** — Order-of-magnitude: 8× HL hourly ≈ one typical CEX window (caps/formulas differ).
3. **R2 — Paper gate** — Factory: `|funding| > 0.001` for **≥3** consecutive hourly snapshots before paper candidate.
4. **R3 — Refuse APR theater** — No guaranteed income from one weather print.

## Next windows (UTC · typical)

### Binance-style 8h
- `2026-08-06 08:00Z`
- `2026-08-06 16:00Z`
- `2026-08-07 00:00Z`
- `2026-08-07 08:00Z`
- `2026-08-07 16:00Z`
- `2026-08-08 00:00Z`

### Hyperliquid-style 1h (next 6)
- `2026-08-06 07:00Z`
- `2026-08-06 08:00Z`
- `2026-08-06 09:00Z`
- `2026-08-06 10:00Z`
- `2026-08-06 11:00Z`
- `2026-08-06 12:00Z`

## Live factory residual (Binance-path collectors · not HL rates)

- Board: **discount_led** · funding leader: **XRPUSDT** abs=0.00012634 call=`watch`
- Paper any: **False**

HL live rates are **not** in this free file. This slice is the **clock process** agents and humans skip.

## Machine-readable

```bash
cat ~/ops/data/product/public/cross-venue-fund-clock.json
python3 ~/ops/bin/export-cross-venue-fund-clock.py
```

Related free: `SETTLEMENT-CLOCK-FREE.md` · `FUNDING-EXTREMES-FREE.md` · board weather.

## Cash ladder

| Free | Paid |
|------|------|
| Clock map + extremes CSV + weather | Crypto Scan Pack ~$49 (Gumroad when listed) |

Family: `crypto_scan_product` · **not** dual Gumroad SKU · treasure 2026-08-06
