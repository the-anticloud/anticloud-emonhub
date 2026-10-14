# Independent Insurance — EMONHUB

**Project:** EMONHUB  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `7615a8f37359e16e4446b838852b6ecd631718ae`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d125184ff003286f8739cb949ff2a934f4bfcfc8d0ff0997c35b603cd5cdda96`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | EMONHUB with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `d125184ff003286f8739cb949ff2a934f4bfcfc8d0ff0997c35b603cd5cdda96`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
