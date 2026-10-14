# Students — PYPSA

**Project:** PYPSA  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/PyPSA/PyPSA  
**Pinned commit:** `ae2ce7f73dea3c86502f64155af7859c213f9bf5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `009a8308f84f1dfc58a725c8ea24b2d0cd7a05ab36241bbd8985663f0d24f559`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ae2ce7f73dea3c86502f64155af7859c213f9bf5`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `009a8308f84f1dfc58a725c8ea24b2d0cd7a05ab36241bbd8985663f0d24f559`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
