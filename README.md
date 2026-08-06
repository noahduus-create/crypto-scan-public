# crypto-scan-public (free TOF)

Free **process maps** for crypto funding / basis / OI weather — **not** trade signals.

| File | What |
|------|------|
| `board-weather-public.json` / `.md` / `.csv` | Dual-clock LIVE residual vs pack stamp |
| `settlement-clock-binance-8h.ics` | Typical Binance 8h funding windows (UTC) |
| `SETTLEMENT-CLOCK-FREE.md` | Human cadence notes + HL normalize tip |
| `skills/crypto-scan-process/SKILL.md` | Free agent skill (Cursor / Claude / Grok) |
| `AGENT-INSTALL-60S.md` | 60-second agent install card |
| `WHY-PAID-PACK.md` | What free weather is vs full pack (when listed) |

```bash
# Board weather
curl -sL https://raw.githubusercontent.com/noahduus-create/crypto-scan-public/main/board-weather-public.json | head

# Agent skill (Cursor)
mkdir -p .cursor/rules
curl -fsSL https://raw.githubusercontent.com/noahduus-create/crypto-scan-public/main/skills/crypto-scan-process/SKILL.md \
  -o .cursor/rules/crypto-scan-process.mdc
```

**skills.sh-class install:** put this repo on your agent skills path, or copy `skills/crypto-scan-process/`.

**Honesty:** process map only · no fake P&L · no entries · quiet boards valid · agents refuse live orders.  
**Paid family:** Crypto Scan Pack ~$49 (Gumroad **when listed**) — wedges + elevates + CSV board. Never invent storefront URL.  
**Gist mirror:** https://gist.github.com/noahduus-create/b0d0c74c161bbf3e450684700c3ca9dc

Not affiliated with any exchange. NFA.

_platform-gap treasure 2026-08-06 · skill mirror ship_
