# Free PERSISTENCE-MAP — funding sign hit-rate (process only)

**Exported:** 2026-08-08T06:36:52Z  
**Family:** crypto_scan_product free TOF · **not** dual paid SKU  
**Source:** factory `funding_hourly_*.jsonl` (hourly_jsonl_n_prints=1835) · lookback ≤ ~14d files  
**Honesty:** research map only · **no entries** · **no fake P&L** · **not** an edge claim  

---

## Why this card exists

Free heatmaps sell **snapshot APR** (“look how high the rate is *right now*”).  
A print that only appeared this hour is **not** a process signal.

This free card answers: **how often was the sign positive / negative / large across the lookback?**  
It kills snapshot theater. It does **not** invent size or guarantee carry.

## Ritual (60–90s)

1. Read **% pos / % neg** and **flip rate** first.  
2. Check **% |f| > 0.001** vs factory paper bar (need streak ≥3h for paper_candidate).  
3. Prefer **max same-sign run** over one loud hour.  
4. If |f|>0.001 share is ~0% over the window → board is **structurally quiet** — journal, don’t force.  
5. Only then think fees + clock (free FEE-BREAK-EVEN + SETTLEMENT-CLOCK).

**Rule:** high % pos with tiny mean |f| ≠ free money.

## Factory board (this free lookback)

Live paper_gate now: any_candidate=**False** · thr=0.001

| symbol | n_h | %pos | %neg | %|f|≥1e-4 | %|f|>0.001 | max run h | flip% | last f |
|--------|----:|-----:|-----:|----------:|-----------:|----------:|------:|-------:|
| BTCUSDT | 367 | 97.5 | 2.5 | 11.4 | 0.0 | 155 | 1.6 | 3.582e-05 |
| BNBUSDT | 367 | 80.1 | 0.0 | 13.9 | 0.0 | 113 | 0.0 | 6.23e-05 |
| XRPUSDT | 367 | 68.7 | 31.3 | 24.8 | 0.0 | 69 | 7.1 | 8.94e-05 |
| SOLUSDT | 367 | 71.9 | 28.1 | 21.5 | 0.0 | 67 | 7.7 | 0.0001 |
| ETHUSDT | 367 | 83.9 | 15.8 | 4.9 | 0.0 | 62 | 6.8 | 2.486e-05 |

### Read-outs (honest)

| Call | What the map shows |
|------|--------------------|
| **Most persistent same-sign** | `BTCUSDT` · max run **155h** · flip% **1.6** |
| **Most flippy** | `SOLUSDT` · flip% **7.7** |
| **Paper bar |f|>0.001 share (max symbol)** | **0.0%** of hours in free window |

## IF / THEN (process only)

| IF | THEN |
|----|------|
| Flip rate high + snapshot mild | Treat as **noise weather** · no size thought |
| % pos very high but % |f|>0.001 ≈ 0 | **Persistent micro-positive ≠ farm** |
| max same-sign run long + still quiet | Background regime label for journal · not entry |
| Any hour hits |f|>0.001 | Re-check streak rule (3 consecutive hours) before paper language |

## Free vs paid

| Free (this card) | Paid Crypto Scan Pack ~$49 |
|------------------|----------------------------|
| Rolling free lookback table + CSV | Full PERSISTENCE-MAP elevate + longer factory lookback + desk ritual |
| Snapshot-theater kill | COST-STACK · GATE-LADDER · SESSION-LOG full |
| Agent-readable JSON | board.csv + 7 elevates |

```bash
python3 ~/ops/bin/export-persistence-map-free.py
```

Cash #1 remains **list pack on Gumroad** when Noah is free.  
Treasure ship 2026-08-08 · free TOF · not dual SKU
