# Ethics — TASMOTA

**Project:** TASMOTA  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/tasmota/Tasmota  
**Pinned commit:** `e63b9383da2e015dbda9f81bf9ee373b8dcb5cf1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f91d93d651ed41b163db0befb470f225dbcc44da4532a9b7bc3fefb8e75e3b04`  
**Date:** October 2026

## Position

TASMOTA is packaged for offline deployment with a verifiable audit trail. The
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
