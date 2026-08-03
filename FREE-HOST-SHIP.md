# Free-host ship checklist (gist / GitHub)

**Goal:** Public dual-clock board weather discoverable without waiting for Gumroad checkout.  
**Law:** Free lead density only — paid zip still human Gumroad list #1. No invented sales.

## Files to publish (public)

From `~/ops/data/product/public/`:

- `board-weather-public.json`
- `board-weather-public.md`
- `board-weather-public.csv` (spreadsheet TOF · 2026-08-03)
- `README.md` (this folder)

Optional add:

- `~/ops/data/product/mcp/INSTALL-DESKTOP.md` (MCP local install)
- `~/ops/data/product/samples/board-public-sample.json` (pack-shaped sample)
- settlement clock free files (ICS/MD) if shipping calendar TOF

## Noah steps (≤5m)

```bash
# 1 refresh (CLI or exporter — no paid zip)
~/ops/bin/crypto-scan-weather --export
# or: python3 ~/ops/bin/export-public-board-weather.py

# 2 gist (example — requires gh auth)
gh gist create \
  ~/ops/data/product/public/board-weather-public.json \
  ~/ops/data/product/public/board-weather-public.md \
  ~/ops/data/product/public/board-weather-public.csv \
  ~/ops/data/product/public/README.md \
  --public \
  --desc "Crypto Scan Pack — free dual-clock board weather (process map, not signals)"
```

Or push a public repo `crypto-scan-public` with the same three files.

## CTA language (honest)

> Free dual-clock board weather: LIVE residual vs pack stamp. Process map only — not a trade signal. Full wedges + CSV + elevates = Crypto Scan Pack ~$49 (Gumroad when listed).

**Do not:** put Gumroad URL in public replies before listed.  
**Do not:** claim live edge or funding yield.

## After first stranger $

Automate: launchd/cron export + gist edit every 1–6h.  
Until then: manual refresh is enough; treasure already left the generator.

_treasure 2026-08-02_
