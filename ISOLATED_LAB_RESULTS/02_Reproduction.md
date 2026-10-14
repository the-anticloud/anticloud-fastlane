# Reproduction — FASTLANE

1. Environment: Windows, Python 3.12.10, runner version 1.0.0
2. `cd anticloud/`
3. `python tools\run_bench.py --quiet`  (exit 0 = all 16 PASS)
4. Compare `anticloud/BENCH.json` SHA3-256: `d9830ec8b43e1bdf696729ddbcc0391f9e2fc0bf6c885e8d0537c02577e9b769`

The `anticloud/` overlay is a standalone copy of the anticloud_reference tree; the 16 checks run against it via `tools/run_bench.py`.
