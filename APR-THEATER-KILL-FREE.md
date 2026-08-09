# Free APR-THEATER-KILL — process honesty card

**Exported:** 2026-08-07T06:19:51Z  
**Family:** crypto_scan_product free TOF · **not** dual paid SKU  
**Honesty:** process map only · **no fake P&L** · **no entries** · agents never live trade  

---

## Why this card exists

Public feed noise sells **loud numbers**:

- Single-print funding annualized to hundreds/% APR  
- “Passive yield” screenshots without settlement clock or persistence  
- Anomaly heatmaps that look like entries  

This free card shows the **naive annualize math** on **today’s live board** so you can **kill** treating one print as edge.

## Live board (research stamp · not entries)

| Field | Value |
|-------|--------|
| Features ts | **2026-08-07T06:19:51Z** |
| Board side | `near_flat` · widest `SOLUSDT` -4.4372 bps |
| Funding leader | `BTCUSDT` abs=3.748e-05 · `quiet` |
| Paper gate | any_candidate=**False** · threshold=0.001 |
| Leader naive APR theater | **4.1040600000000005%** (print × 3 × 365 × 100) |

**Lesson:** social APR can look “interesting” while `paper_gate=false` and board is quiet. Quiet weather is valid product weather.

## Naive annualize table (theater · not edge)

Assumes Binance-style **3 settlements/day**. **Does not** net fees, basis, flips, or inventory.

| symbol | last_funding | naive APR theater % | hourly_call | streak≥0.001 |
|--------|-------------:|--------------------:|-------------|-------------:|
| BTCUSDT | 3.748e-05 | 4.1 | quiet | 0 |
| ETHUSDT | 2.927e-05 | 3.21 | quiet | 0 |
| SOLUSDT | 1.567e-05 | 1.72 | quiet | 0 |
| XRPUSDT | 1.478e-05 | 1.62 | quiet | 0 |
| BNBUSDT | 0.0 | 0.0 | quiet | 0 |

## IF / THEN (journal only · never size)

1. **IF** `paper_gate.any_paper_candidate=false` **AND** you saw a huge APR claim → log `apr_theater_noise` · no candidate from social proof.  
2. **IF** one symbol is “hot” for one hour → require multi-hour persistence (paid pack: PERSISTENCE-MAP) · no size.  
3. **IF** comparing venues → normalize settlement clock first (free: SETTLEMENT-CLOCK-FREE).  
4. **IF** you cannot fill fees + basis + slippage → output **watch/journal** only.

## Free vs paid

| Free (this card + public/) | Paid Crypto Scan Pack ~$49 |
|----------------------------|----------------------------|
| Live naive APR theater table | Full elevates 7/7 (APR kill + COST-STACK + PERSISTENCE-MAP + …) |
| Honesty kill list | Board.csv + 4 wedges + machine board |
| Process ritual | Portable desk ritual for every session |

```bash
python3 ~/ops/bin/export-apr-theater-kill-free.py
```

Cash #1 remains **list pack on Gumroad** when Noah is free.  
Treasure ship 2026-08-07 · free TOF · not dual SKU
