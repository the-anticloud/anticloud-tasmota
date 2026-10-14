# Onboarding — TASMOTA

**Project:** TASMOTA  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/tasmota/Tasmota  
**Pinned commit:** `e63b9383da2e015dbda9f81bf9ee373b8dcb5cf1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f91d93d651ed41b163db0befb470f225dbcc44da4532a9b7bc3fefb8e75e3b04`  
**Date:** October 2026

## First hour

1. Read `README.md` — what the project is and what it measures.
2. Read `ISOLATED_LAB_RESULTS/03_Result_Register.md` — the 16 checks and their
   evidence hashes.
3. Run the suite: `python tools/run_bench.py --out BENCH.json`.
4. Verify a hash: recompute SHA3-256 of a file in `04_Evidence/` and compare.

## First day

- `10_TECHNICAL_HANDOFF` — architecture and interfaces
- `11_TUTORIAL_DEVELOPERS` — build and test
- `18_COMMAND_LINE_INTERFACE` — CLI reference
- `27_DEPENDENCIES` — the offline dependency mirror

## Getting help

lois@0-1.gg · 0-1.gg
