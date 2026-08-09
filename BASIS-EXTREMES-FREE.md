# Free basis extremes — mark–index process map (not arb)

**Exported:** 2026-08-07T06:19:51Z
**Board side:** `near_flat` · bar ±5.0 bps · n_premium=0 · n_discount=0
**Widest |basis|:** `SOLUSDT` -4.4372 bps
**Paper gate (funding axis):** any_candidate=False threshold=0.001

## Honesty (HARD)

- Basis = (mark − index) / index × 10 000 (bps). **Basis ≠ free arb.**
- Fees, latency, inventory risk kill naive spreads. Map only.
- Process map · no fake P&L · no entries · agents never live trade
- Cash product: Crypto Scan Pack ~$49 when listed (Wedge 4 full map inside paid pack)

## Rank by |basis_bps|

| rank | symbol | basis_bps | label | last_funding | hourly_call |
|-----:|--------|----------:|-------|-------------:|-------------|
| 1 | SOLUSDT | -4.4372 | near_flat | 1.567e-05 | quiet |
| 2 | ETHUSDT | -4.2912 | near_flat | 2.927e-05 | quiet |
| 3 | XRPUSDT | -3.8126 | near_flat | 1.478e-05 | quiet |
| 4 | BTCUSDT | -3.7296 | near_flat | 3.748e-05 | quiet |
| 5 | BNBUSDT | 3.6047 | near_flat | 0.0 | quiet |

## How to use (60s)

1. Sort by |bps| — who is stretched vs index?
2. Pair with free funding extremes CSV — **do not** size from basis alone.
3. Quiet funding + mild basis is valid weather (not a broken map).
4. Premium + high funding ≠ long; discount + soft funding ≠ short.

```bash
python3 ~/ops/bin/export-basis-extremes-free.py
```

Family: crypto_scan_product · treasure free TOF 2026-08-07 · **not dual SKU**
