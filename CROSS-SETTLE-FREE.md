# CROSS-SETTLE free map — multi-venue funding clocks (process only)

**ts:** 2026-08-04T05:55:00Z · treasure TOP3 #3  
**Family:** crypto_scan_pack free TOF · **not** dual paid SKU  
**Honesty:** clock mismatch ≠ free money · **no APR theater** · **no multi-ex arb P&L** · NFA

Full inventory draft: `~/ops/data/product/mcp/CROSS-SETTLE-MAP-v0.md`

---

## Why this is free (vs in-zip SETTLEMENT-CLOCK)

| Surface | Scope |
|---------|--------|
| **SETTLEMENT-CLOCK free ICS** | Typical Binance-style **8h** windows (calendar subscribe) |
| **SETTLEMENT-CLOCK elevate (paid zip)** | One-board normalize ritual |
| **CROSS-SETTLE free (this)** | Compare **venue class clocks** so 1h vs 8h is never treated as the same “rate” |

---

## Venue clock table (research baseline · verify before any claim)

| Venue class | Typical funding cadence (research) | Agent label |
|-------------|--------------------------------------|-------------|
| Binance USDT-M majors | Often **8h** historical; product can differ | `clock_binance_check_product` |
| Many perps DEXes / HL-class | Often **1h** or continuous-style | `clock_dex_hourly_or_unknown` |
| Other CEX | **1h / 4h / 8h** mix | `clock_verify_docs` |
| Unknown | — | **`clock_unknown` → stop inventing arb** |

**Law:** Never invent a venue interval from memory in buyer-facing claims.  
If interval not stamped in source → `clock_unknown`.

---

## Ritual (offline)

1. Stamp each row: `venue · symbol · funding_raw · interval · quality`  
2. Any side `clock_unknown` → journal only, no “edge”  
3. Differing intervals → normalize horizon **before** comparing magnitude  
4. Stack fees + basis + slippage (COST-STACK) **after** clocks match  
5. Quiet primary board → do not hunt multi-venue theater  

---

## Machine twin

See `cross-settle-public.json` in this folder.

## Related free

- `settlement-clock-binance-8h.ics` · `SETTLEMENT-CLOCK-FREE.md`  
- Dual-clock board weather · `WHY-PAID-PACK.md`  

## CTA

Process map only. Full elevates (incl. SETTLEMENT-CLOCK + COST-STACK) live in Crypto Scan Pack ~$49 **when listed** — never invent checkout URL.

_Treasure 2026-08-04 · no elevate-into-zip under attach freeze_
