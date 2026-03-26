# CI Benchmark Results

Last updated: 2026-03-26 23:59:36 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|-----------|-------|-----|
| github-actions | macos-latest | 9340562.65 events/sec | ±47218.95 | 5806.96 MiB/sec | ±52.00 | 87642.98 | ±1118.66 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 9207666.73 events/sec | ±72533.29 | 6063.38 MiB/sec | ±164.18 | 87238.78 | ±3703.00 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 2796608.12 events/sec | ±55275.55 | 2095.59 MiB/sec | ±43.06 | 36316.17 | ±395.30 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.43 events/sec | ±0.16 | 5331.85 MiB/sec | ±1.08 | 631.55 | ±13.81 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1443.62 events/sec | ±2 | 6014.07 MiB/sec | ±35.49 | 1981.4 | ±19.96 | AMD EPYC 7763 64-Core Processor | 4 | 15991 MB |
| github-actions | ubuntu-24.04 | 1443.57 events/sec | ±0.12 | 6074.95 MiB/sec | ±1.07 | 1414.52 | ±41.07 | AMD EPYC 7763 64-Core Processor | 4 | 15994 MB |
| github-actions | ubuntu-latest | 1442.13 events/sec | ±0.32 | 6029.65 MiB/sec | ±3.44 | 1965.96 | ±11.88 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| circleci | arm.large | 1068.93 events/sec | ±1.02 | 3803.70 MiB/sec | ±11.18 | — | — | unknown | 32 | 16384 MB |
| circleci | arm.medium | 1068.69 events/sec | ±0.95 | 3795.55 MiB/sec | ±3.90 | — | — | unknown | 32 | 8192 MB |
| circleci | medium | 449.60 events/sec | ±2.21 | 5767.68 MiB/sec | ±64.42 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | large | 443.53 events/sec | ±3.62 | 5479.80 MiB/sec | ±799.23 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | xlarge | 432.34 events/sec | ±10.96 | 5770.05 MiB/sec | ±83.25 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |

---
*37 total run(s) recorded.*
