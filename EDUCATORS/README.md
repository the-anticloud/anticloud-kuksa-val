# Educators — KUKSA_VAL

**Project:** KUKSA_VAL  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/eclipse/kuksa.val  
**Pinned commit:** `f0e028bc2d29821233af7ff75be4ed57aa59e77a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `68200fd3399d0187789eb29ab156c5c26a5e12bfc11980e51247c9bacdb68300`  
**Date:** October 2026

## Teaching with KUKSA_VAL

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `68200fd3399d0187789eb29ab156c5c26a5e12bfc11980e51247c9bacdb68300` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
