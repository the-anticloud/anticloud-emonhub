# Students — EMONHUB

**Project:** EMONHUB  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `7615a8f37359e16e4446b838852b6ecd631718ae`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d125184ff003286f8739cb949ff2a934f4bfcfc8d0ff0997c35b603cd5cdda96`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `7615a8f37359e16e4446b838852b6ecd631718ae`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `d125184ff003286f8739cb949ff2a934f4bfcfc8d0ff0997c35b603cd5cdda96`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
