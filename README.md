# Public board weather (free host surface)

**Treasure ship 2026-08-02 · PUBLIC-BOARD-WEATHER**  
**+ 2026-08-03 · CLI one-liner + public CSV** (same family · not dual SKU)

Dual-clock process weather for free host (GitHub gist/repo), agents, terminal, and spreadsheets.

| File | Role |
|------|------|
| `board-weather-public.json` | Machine-readable LIVE residual + PACK snap dual clock |
| `board-weather-latest.json` | Same bytes (stable name for scripts) |
| `board-weather-public.md` | Human table |
| `board-weather-public.csv` | Spreadsheet TOF (flat dual-clock + symbol rows) |

## CLI one-liner (NEW · 2026-08-03)

```bash
~/ops/bin/crypto-scan-weather                 # dual-clock one-liner
~/ops/bin/crypto-scan-weather --table         # short symbol table
~/ops/bin/crypto-scan-weather --export        # refresh public JSON/MD/CSV
~/ops/bin/crypto-scan-weather --refresh       # alias of --export
~/ops/bin/crypto-scan-weather --csv-path      # print CSV path
~/ops/bin/crypto-scan-weather --json          # full weather JSON stdout
```

Example (quiet board):

```
LIVE discount_led/ETHUSDT -5.42 bps | PACK mixed/XRPUSDT -6.21 bps | diverged | paper=false (watch) | fund BTCUSDT abs=0.0001 watch | process_map_only · pack~$49 when listed
```

## Regenerate (files only)

```bash
python3 ~/ops/bin/export-public-board-weather.py
# or
~/ops/bin/crypto-scan-weather --export
```

Reads `~/ops/data/features/latest.json` + pack `scan-pack/board.json`.  
**Does not** re-export paid zip (attach freeze safe).

## Honesty

- Process map only · no fake P&L · no entries  
- `live_vs_pack=diverged` = residual weather only — not re-export  
- Quiet / watch boards are valid product weather  
- Cash #1 remains Crypto Scan Pack ~$49 on Gumroad when Noah lists

## Free host (Noah ≤5m when ready)

1. Create public gist or `crypto-scan-public` repo  
2. Push `board-weather-public.{json,md,csv}` (+ optional settlement clock files)  
3. Optional: `python3 ~/ops/bin/refresh-crypto-scan-free-gist.py` (needs `gh` gist auth; not every residual tick)  
4. X pin after Gumroad list (publish_before_paste still holds for paid CTA)

_Not a dual paid SKU._

## Settlement clock (free · 2026-08-03)

| File | Role |
|------|------|
| `settlement-clock-binance-8h.ics` | Calendar subscribe — typical Binance 8h windows |
| `SETTLEMENT-CLOCK-FREE.md` | Human process map + HL normalize tip |
| `settlement-clock-meta.json` | Machine next windows |

```bash
python3 ~/ops/bin/export-settlement-clock-free.py
```

## Free→paid map (NEW · 2026-08-04 treasure)

| File | Role |
|------|------|
| `WHY-PAID-PACK.md` | Elevates 7/7 + free vs paid boundary (conversion wedge · not dual SKU) |

```bash
~/ops/bin/crypto-scan-weather --pack-map
```

## Agent process skill (NEW · 2026-08-04)

Portable free skill for Cursor / Claude / Grok:

`~/ops/data/product/dist/agent-skills/crypto-scan-process/SKILL.md`  
Install: same folder `INSTALL.md`

Ritual: dual_clock → paper_gate → honesty · refuse live trade.

## Agent install + poly paper free (NEW · 2026-08-05 treasure)

| File | Role |
|------|------|
| `AGENT-INSTALL-60S.md` | Cursor / Claude / Grok install in 60s (free skill + MCP pointer) |
| `POLY-PAPER-FREE.md` | Poly paper free process sample (not dual SKU) |
| `poly-paper-public.json` | Slim paper watchlist export |

Marketplace listing copy (dist tree): `../dist/marketplace/claude-skill-listing.md`

## MiCA venue map free (NEW · 2026-08-05 treasure)

| File | Role |
|------|------|
| `MICA-VENUE-MAP.md` | EU venue literacy process (not legal advice) |
| `mica/CASPS.csv` · `mica/NCASP.csv` · `mica/meta.json` | ESMA interim register snap + sha |

```bash
python3 ~/ops/bin/mica-venue-check.py "Bitpanda"
```

_Same firm scan/map DNA · free TOF · not dual SKU · cash hero still Crypto Scan Pack $49 when listed._

## Cross-venue fund clock (NEW · 2026-08-06 treasure)

Concrete **Hyperliquid-class hourly vs Binance-class 8h** dual next windows + normalize trap (fills gap left by abstract CROSS-SETTLE + BN-only ICS).

| File | Role |
|------|------|
| `CROSS-VENUE-FUND-CLOCK.md` | Human dual-clock process map |
| `cross-venue-fund-clock.json` | Machine twin (labels · next windows · normalize) |

**Honesty:** shared settle window ≠ same rate units · ×8/÷8 display only · no multi-ex arb · not dual SKU.

## Treasure free TOF index (2026-08-06)

| File | Domain | Tag |
|------|--------|-----|
| `CROSS-VENUE-FUND-CLOCK.md` + `.json` | HL 1h vs CEX 8h clock process | **NEW** |
| `FUNDING-EXTREMES-FREE.md` + `funding-extremes-free.csv` | Free extremes data ladder | **NEW** |
| `skills-marketplace` listing (dist) | LobeHub / skills.sh platform | **NEW** |
| Prior day-6: AGENT-INSTALL-60S · MICA-VENUE-MAP · POLY-PAPER-FREE | known | known |
| Prior: WHY-PAID · CROSS-SETTLE · SETTLEMENT-CLOCK · board weather | known | known |

Refresh:
```bash
python3 ~/ops/bin/export-cross-venue-fund-clock.py
python3 ~/ops/bin/export-funding-extremes-free.py
python3 ~/ops/bin/export-public-board-weather.py
```

Cash #1 still: list Crypto Scan Pack ~$49 (human Gumroad). Free TOF ≠ paid unlock.


## Treasure free TOF index (2026-08-07)

| File | Domain | Tag |
|------|--------|-----|
| `BASIS-EXTREMES-FREE.md` + `basis-extremes-free.csv` + `.json` | Mark–index basis ranked by \|bps\| (Wedge 4 public) | **NEW** |
| `APR-THEATER-KILL-FREE.md` + `apr-theater-kill-free.json` | Naive funding→APR theater kill on live board | **NEW** |
| `OI-SHARE-FREE.md` + `oi-share-free.csv` + `.json` | OI notional concentration map | **NEW** |
| `FEE-BREAK-EVEN-FREE.md` | Cost worksheet before APR claims | **NEW** |
| Prior day-7: CROSS-VENUE-FUND-CLOCK · FUNDING-EXTREMES · skills marketplace | known | known |
| Prior: AGENT-INSTALL · MICA · POLY-PAPER · WHY-PAID · CROSS-SETTLE · board weather | known | known |

```bash
python3 ~/ops/bin/export-basis-extremes-free.py
python3 ~/ops/bin/export-apr-theater-kill-free.py
python3 ~/ops/bin/export-oi-share-free.py
python3 ~/ops/bin/export-funding-extremes-free.py
python3 ~/ops/bin/export-public-board-weather.py
```

Cash #1 still: list Crypto Scan Pack ~$49 (human Gumroad). Free TOF ≠ paid unlock.


## Treasure free TOF index (2026-08-08)

| File | Domain | Tag |
|------|--------|-----|
| `OI-WEIGHTED-FUND-FREE.md` + `.csv` + `.json` | Capital-weighted vs equal-weight funding weather | **NEW** |
| `GATE-LADDER-FREE.md` + `.csv` + `.json` | Quiet → watch → paper rungs (paper_gate honesty) | **NEW** |
| `PERSISTENCE-MAP-FREE.md` + `.csv` + `.json` | Funding sign hit-rate · flip · max run (snapshot theater kill) | **NEW** |
| `POLY-UMA-DISPUTE-RISK-FREE.md` | Poly dispute/oracle process literacy (dogfood) | **NEW** firm-adjacent |
| Prior day-8: BASIS-EXTREMES · APR-THEATER-KILL · OI-SHARE · FEE-BREAK-EVEN | known | known |

```bash
python3 ~/ops/bin/export-oi-weighted-fund-free.py
python3 ~/ops/bin/export-gate-ladder-free.py
python3 ~/ops/bin/export-persistence-map-free.py
python3 ~/ops/bin/export-public-board-weather.py
```

Cash #1 still: list Crypto Scan Pack ~$49 (human Gumroad). Free TOF ≠ paid unlock.

## Agent skills (free · process map only)

Install via [skills.sh](https://skills.sh) / Cursor / Claude:

```bash
# list
npx skills add noahduus-create/crypto-scan-public --list

# board-first process ritual
npx skills add noahduus-create/crypto-scan-public@crypto-scan-process

# ticker-first crowd precheck
npx skills add noahduus-create/crypto-scan-public@funding-crowd-precheck
```

Manual: copy `skills/*/SKILL.md` into `~/.claude/skills/<name>/` or `.cursor/skills/<name>/`.

**Refuses:** live orders · fake P&L · APR theater. **NFA.**  
Paid Crypto Scan Pack ~$49 **when listed** — no checkout link while storefront offline.

