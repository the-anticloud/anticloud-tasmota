# Students — TASMOTA

**Project:** TASMOTA  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/tasmota/Tasmota  
**Pinned commit:** `e63b9383da2e015dbda9f81bf9ee373b8dcb5cf1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f91d93d651ed41b163db0befb470f225dbcc44da4532a9b7bc3fefb8e75e3b04`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e63b9383da2e015dbda9f81bf9ee373b8dcb5cf1`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f91d93d651ed41b163db0befb470f225dbcc44da4532a9b7bc3fefb8e75e3b04`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
