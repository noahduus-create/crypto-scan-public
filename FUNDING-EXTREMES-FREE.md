# Free funding extremes — process map CSV (not signals)

**Exported:** 2026-08-06T06:03:42Z
**Board:** `discount_led` · widest basis `SOLUSDT` -6.6693 bps · OI leader `BTCUSDT`
**Leader by |funding|:** `XRPUSDT` last=-0.00012634 abs=0.00012634 call=`watch`
**Paper gate:** any_candidate=False threshold=0.001

## Honesty (HARD)

- Process map only · no fake P&L · no entries
- Cash product: Crypto Scan Pack ~$49 when listed

| symbol | last_funding | abs | basis_bps | hourly_call |
|--------|-------------:|----:|----------:|-------------|
| XRPUSDT | -0.00012634 | 0.00012634 | -6.3011 | watch |
| SOLUSDT | -5.69e-05 | 5.69e-05 | -6.6693 | watch |
| BTCUSDT | 3.087e-05 | 3.087e-05 | -3.8258 | quiet |
| ETHUSDT | -7.16e-06 | 7.16e-06 | -4.3374 | quiet |
| BNBUSDT | 0.0 | 0.0 | 4.1926 | quiet |

```bash
python3 ~/ops/bin/export-funding-extremes-free.py
```

Family: crypto_scan_product · treasure free TOF · not dual SKU
