# Educators — TASMOTA

**Project:** TASMOTA  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/tasmota/Tasmota  
**Pinned commit:** `e63b9383da2e015dbda9f81bf9ee373b8dcb5cf1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f91d93d651ed41b163db0befb470f225dbcc44da4532a9b7bc3fefb8e75e3b04`  
**Date:** October 2026

## Teaching with TASMOTA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f91d93d651ed41b163db0befb470f225dbcc44da4532a9b7bc3fefb8e75e3b04` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
