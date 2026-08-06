# Agent install in 60 seconds — crypto scan process (free)

**ts:** 2026-08-05T05:55:00Z · treasure ship  
**Family:** Crypto Scan Pack process maps · **not** a dual paid SKU  
**Cash hero still:** Crypto Scan Pack **~$49** when listed on Gumroad (never invent URL)

Honest **funding / basis / OI process weather** for Cursor, Claude Code/Desktop, and Grok.  
**Refuses:** live orders · fake P&L · APR theater · “entries from weather.”

---

## What you get free

| Asset | Role |
|-------|------|
| **Skill** `crypto-scan-process` | Ritual: dual-clock → paper_gate → symbol row → honesty laws |
| **Public weather** | LIVE residual vs PACK stamp (JSON/MD/CSV) |
| **MCP-lite** (optional) | Local read-only board tools — no exchange HTTP |

Paid pack (~$49 when listed) adds elevates + full scan wedges + machine board — see `WHY-PAID-PACK.md`.

---

## A) Cursor (~20s)

```bash
mkdir -p .cursor/rules
# If you have the factory tree:
cp ~/ops/data/product/dist/agent-skills/crypto-scan-process/SKILL.md \
  .cursor/rules/crypto-scan-process.mdc
```

Or: Cursor → Project Rules → paste the body of `SKILL.md`.

**Dogfood weather (local):**

```bash
~/ops/bin/crypto-scan-weather
~/ops/bin/crypto-scan-weather --pack-map
```

---

## B) Claude Code / project (~30s)

1. Project instructions = full body of  
   `~/ops/data/product/dist/agent-skills/crypto-scan-process/SKILL.md`
2. Optional knowledge file:  
   `~/ops/data/product/public/board-weather-public.json`
3. Optional local MCP (Desktop or compatible host):

```json
{
  "mcpServers": {
    "funding-mcp-lite": {
      "command": "python3",
      "args": ["/Users/REPLACE/ops/bin/crypto-scan-mcp-stub.py", "--mcp"]
    }
  }
}
```

Replace `REPLACE` with your home directory. Restart host. Smoke:

```bash
python3 ~/ops/bin/crypto-scan-mcp-stub.py call get_paper_gate
python3 ~/ops/bin/crypto-scan-mcp-stub.py call list_honesty_laws
```

Full desktop note: `~/ops/data/product/mcp/INSTALL-DESKTOP.md`

---

## C) Grok Build (~20s)

```bash
mkdir -p ~/.grok/skills/crypto-scan-process
cp ~/ops/data/product/dist/agent-skills/crypto-scan-process/SKILL.md \
  ~/.grok/skills/crypto-scan-process/SKILL.md
```

Triggers: funding map, board weather, paper_gate, scan pack process.

---

## D) Public free host (no local factory)

Public gist / repo (refresh when factory exports):

- https://gist.github.com/noahduus-create/b0d0c74c161bbf3e450684700c3ca9dc  
- https://github.com/noahduus-create/crypto-scan-public  

Files: `board-weather-public.{json,md,csv}` · `WHY-PAID-PACK.md` · `CROSS-SETTLE-FREE.md` · this install note when mirrored.

---

## Ritual (agents must run in order)

1. **Dual clock** — LIVE residual vs PACK stamp. `diverged` ⇒ residual language only; **do not** re-export paid zip.  
2. **paper_gate** — if no candidate → journal/watch only. Never invent entries.  
3. **Symbol row** — abs funding, basis bps, hourly_call, OI share if present.  
4. **Honesty laws** — process map · NFA · no fake P&L · **agents never live trade**.  
5. **Free vs paid** — free weather/skill/MCP ≠ full elevates pack.

---

## Paid CTA (honest)

- Until Gumroad public URL exists: say **“Crypto Scan Pack ~$49 when listed.”**  
- After list: point to the **real** public product URL only.  
- Soft CTA max · never claim edge or historical P&L.

---

## Marketplace listing pointer

Listing copy for Claude / skills directories:  
`~/ops/data/product/dist/marketplace/claude-skill-listing.md`

_shipped treasure 2026-08-05 · AGENT-INSTALL-60S · same family · free TOF_
