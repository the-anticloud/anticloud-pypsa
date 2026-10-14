# Ethics — PYPSA

**Project:** PYPSA  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/PyPSA/PyPSA  
**Pinned commit:** `ae2ce7f73dea3c86502f64155af7859c213f9bf5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `009a8308f84f1dfc58a725c8ea24b2d0cd7a05ab36241bbd8985663f0d24f559`  
**Date:** October 2026

## Position

PYPSA is packaged for offline deployment with a verifiable audit trail. The
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
