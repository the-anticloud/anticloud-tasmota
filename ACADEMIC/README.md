# Academic Use — TASMOTA

**Project:** TASMOTA  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/tasmota/Tasmota  
**Pinned commit:** `e63b9383da2e015dbda9f81bf9ee373b8dcb5cf1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f91d93d651ed41b163db0befb470f225dbcc44da4532a9b7bc3fefb8e75e3b04`  
**Date:** October 2026

## Scope

TASMOTA is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `e63b9383da2e015dbda9f81bf9ee373b8dcb5cf1`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
