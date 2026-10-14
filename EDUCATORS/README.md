# Educators — PYPSA

**Project:** PYPSA  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/PyPSA/PyPSA  
**Pinned commit:** `ae2ce7f73dea3c86502f64155af7859c213f9bf5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `009a8308f84f1dfc58a725c8ea24b2d0cd7a05ab36241bbd8985663f0d24f559`  
**Date:** October 2026

## Teaching with PYPSA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `009a8308f84f1dfc58a725c8ea24b2d0cd7a05ab36241bbd8985663f0d24f559` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
