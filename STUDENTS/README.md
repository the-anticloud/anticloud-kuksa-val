# Students — KUKSA_VAL

**Project:** KUKSA_VAL  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/eclipse/kuksa.val  
**Pinned commit:** `f0e028bc2d29821233af7ff75be4ed57aa59e77a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `68200fd3399d0187789eb29ab156c5c26a5e12bfc11980e51247c9bacdb68300`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f0e028bc2d29821233af7ff75be4ed57aa59e77a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `68200fd3399d0187789eb29ab156c5c26a5e12bfc11980e51247c9bacdb68300`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
