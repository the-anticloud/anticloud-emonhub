# Ethics — EMONHUB

**Project:** EMONHUB  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `7615a8f37359e16e4446b838852b6ecd631718ae`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d125184ff003286f8739cb949ff2a934f4bfcfc8d0ff0997c35b603cd5cdda96`  
**Date:** October 2026

## Position

EMONHUB is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
