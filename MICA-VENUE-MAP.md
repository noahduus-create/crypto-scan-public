# MiCA venue register map (free process TOF)

**ts:** 2026-08-05T05:56:00Z · treasure  
**Domain:** EU crypto **venue literacy** scan (public ESMA interim register)  
**Family:** scan/map tools firm · **free TOF** · **not** dual Gumroad SKU  
**Cash #1 unchanged:** Crypto Scan Pack ~$49 when listed

---

## HARD disclaimers

- **Not legal advice.** Not a CASP service. Not a licence broker.  
- **Register row ≠ “safe / licensed forever.”** Status, end dates, and national notifications matter.  
- **Always re-download** from ESMA before decisions — this free host is a **snapshot**.  
- **Agents never** assert “X is MiCA licensed” as warranty.

Official source:  
https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica

---

## Why this exists

Post **1 Jul 2026** MiCA cliff, EU/EEA crypto venue literacy is a **public-data scan** problem:

| Surface | What people do | Gap we fill |
|---------|----------------|-------------|
| ESMA raw CSVs | Manual Ctrl-F weekly | Offline name match + process checklist |
| Enterprise CASP policy packs | €k/yr for firms | Trader/operator **buyer literacy** map |
| US heatmap SaaS | Funding/OI porn | DK/EU **venue register** honesty process |

Same DNA as Crypto Scan Pack: **honest process map over public data**, not signal theater.

---

## Free files (this wake)

| Path | Role |
|------|------|
| `mica/CASPS.csv` | ESMA CASP interim register snapshot |
| `mica/NCASP.csv` | Non-compliant entities snapshot |
| `mica/meta.json` | as_of · sha256 · bytes · laws |
| This MD | Human process map |

```bash
# Offline check (factory)
python3 ~/ops/bin/mica-venue-check.py "Bitpanda"
python3 ~/ops/bin/mica-venue-check.py "binance" --json
python3 ~/ops/bin/mica-venue-check.py --meta
```

---

## Process ritual (mid ≠ edge style)

1. **Download** official CSVs (or use dated free snap + sha).  
2. **Match** commercial / legal / domain string (fuzzy is OK; false friends exist).  
3. **Read fields** — home state, competent authority, auth date, **end date**.  
4. **Check NCASP** — hit ⇒ investigate; miss ⇒ not clearance.  
5. **Verify on ESMA page** — free tool is map, not oracle.  
6. **Language** — “appears on CASP snap as of DATE with score S” · never “licensed safe.”

---

## Free vs paid (firm ladder)

| Now (free) | Later (only after crypto pack listed or as lead into it) |
|------------|--------------------------------------------------------|
| Snap CSVs + offline checker + process MD | Optional $29–49 zip with multi-date diffs / DK Finanstilsynet notes |
| Soft CTA → Crypto Scan Pack weather/skill | **No** dual checkout invent pre-first $ |

---

## Refresh (factory)

```bash
# re-pull official CSVs into public/mica + meta sha
# then: python3 ~/ops/bin/mica-venue-check.py --meta
```

_shipped treasure 2026-08-05 · MICA-CASP-VENUE-REGISTER-MAP free slice · same firm · not dual SKU_
