# Bitcoin Halving Oracle ⏰

---

*"History doesn't repeat itself, but it often rhymes."*

---

## The Thesis

Bitcoin moves in ~4 year cycles driven by halving events. Every cycle follows a pattern: accumulation → bull → distribution → crash → repeat. Knowing where you are is arguably the most valuable signal.

This contract tells you.

## Cycle Phases

| Phase | What's happening |
|-------|-----------------|
| ACCUMULATION | Smart money buying the fear |
| EARLY_BULL | Breaking above key levels |
| MID_BULL | Main trend, strongest momentum |
| LATE_BULL | Euphoria, everyone's a genius |
| DISTRIBUTION | Smart money exiting |
| BEAR | Pain. Max pain. |

## Output

```json
{
  "cycle_phase": "BEAR",
  "days_since_halving": "700",
  "historical_comparison": "Fear levels consistent with accumulation zone in previous cycles",
  "summary": "Current fear levels suggest late bear or early accumulation phase."
}
```

## Deploy

GenLayer Studio → paste contract → `param` = `test` → Deploy → `check_cycle`

## What makes this different

Not a website run by someone. It's on-chain, AI-powered, consensus-verified. No single human deciding "we're in a bull market."

MIT License | GenLayer Testnet Bradbury
