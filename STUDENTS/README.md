# Students — FASTLANE

**Project:** FASTLANE  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `1912c0760355eebb5e90f643e6e77b74cf346e3b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e7080ffe7229a20baabff0e3131837f384348ebc4e01ec686db5d4206b1083a7`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1912c0760355eebb5e90f643e6e77b74cf346e3b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `e7080ffe7229a20baabff0e3131837f384348ebc4e01ec686db5d4206b1083a7`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
