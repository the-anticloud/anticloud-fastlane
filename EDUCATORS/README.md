# Educators — FASTLANE

**Project:** FASTLANE  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `1912c0760355eebb5e90f643e6e77b74cf346e3b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e7080ffe7229a20baabff0e3131837f384348ebc4e01ec686db5d4206b1083a7`  
**Date:** October 2026

## Teaching with FASTLANE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `e7080ffe7229a20baabff0e3131837f384348ebc4e01ec686db5d4206b1083a7` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
