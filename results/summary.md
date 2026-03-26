# CI Benchmark Results

Last updated: 2026-03-26 23:23:35 UTC

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
| circleci | arm.medium | 1069.29 events/sec | ±0.68 | 3787.74 MiB/sec | ±7.52 | — | — | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.40 events/sec | ±0.93 | 3799.70 MiB/sec | ±119.27 | — | — | unknown | 32 | 16384 MB |
| circleci | large | 446.99 events/sec | ±1.95 | 5777.50 MiB/sec | ±46.09 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | medium | 444.56 events/sec | ±6.17 | 5410.25 MiB/sec | ±286.38 | — | — | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | xlarge | 441.61 events/sec | ±6.06 | 5774.44 MiB/sec | ±8.01 | — | — | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 16384 MB |

---
*32 total run(s) recorded.*
