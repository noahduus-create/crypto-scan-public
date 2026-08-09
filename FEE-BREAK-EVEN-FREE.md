# Free fee break-even worksheet — before any APR claim

**Treasure 2026-08-07 · free TOF · not dual SKU**  
**Honesty:** process map only · **no fake P&L** · **no entries** · agents never live trade  

Public APR posts skip the boring math. Fill this **before** treating funding as “yield.”

## Break-even checklist (journal)

| # | Cost / friction | Your note (fill) | Default if unknown |
|---|-----------------|------------------|--------------------|
| 1 | Settlement interval (1h / 8h / other) | | if unknown → **stop** (clock_unknown) |
| 2 | Round-trip taker fees (open+close) bps | | exchange fee schedule |
| 3 | Funding / maker rebate if any | | 0 |
| 4 | Basis at entry (mark−index bps) | | see free `basis-extremes-free.csv` |
| 5 | Slippage / spread bps (honest size) | | journal; never invent |
| 6 | Inventory / margin opportunity | | qualitative |
| 7 | Flip risk (sign change before settle) | | paid: PERSISTENCE-MAP |

## Naive inequality (theater kill)

Let `F` = funding print you hope to collect (per period).  
Let `C` = sum of fees + slippage + adverse basis in **same units**.

**IF** you cannot estimate `C` → output **watch/journal** only.  
**IF** `F` is a single quiet print (see free APR-THEATER-KILL) while `paper_gate=false` → do **not** annualize into a plan.

## Live desk stamp (research · not edge)

Regenerate companion free files:

```bash
python3 ~/ops/bin/export-apr-theater-kill-free.py
python3 ~/ops/bin/export-basis-extremes-free.py
python3 ~/ops/bin/export-funding-extremes-free.py
```

Quiet boards are valid weather. Break-even often **fails** on quiet funding — that is the product lesson, not a bug.

## Free vs paid

| Free | Paid Crypto Scan Pack ~$49 |
|------|----------------------------|
| This worksheet + APR theater table | Full **COST-STACK** elevate + session ritual |
| Basis / funding / OI free CSVs | board.csv + 4 wedges + 7 elevates |

Cash #1: list pack on Gumroad when Noah is free.  
Family: crypto_scan_product · treasure 2026-08-07
