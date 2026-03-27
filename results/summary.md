# CI Benchmark Results

Last updated: 2026-03-27 04:13:40 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|-----------|-------|-----|
| circleci | m4pro.medium | 15114028.60 events/sec | ±67783.55 | 9414.79 MiB/sec | ±76.84 | 149648.70 | ±366.93 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| circleci | m4pro.large | 15071214.67 events/sec | ±53985.66 | 9490.30 MiB/sec | ±45.88 | 158775.87 | ±599.39 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| github-actions | macos-latest | 9891957.89 events/sec | ±83398.45 | 5866.40 MiB/sec | ±211.45 | 74234.98 | ±3150.47 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 9218837.25 events/sec | ±277763.27 | 6333.04 MiB/sec | ±47.75 | 100894.56 | ±1210.05 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3286358.25 events/sec | ±42562.19 | 2441.91 MiB/sec | ±59.15 | 45443.49 | ±1444.52 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.61 events/sec | ±0.29 | 5332.95 MiB/sec | ±2.14 | 686.95 | ±10.06 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1444.23 events/sec | ±0.15 | 6018.49 MiB/sec | ±5.73 | 2016.41 | ±11.98 | AMD EPYC 7763 64-Core Processor | 4 | 15991 MB |
| github-actions | ubuntu-24.04 | 1442.44 events/sec | ±0.96 | 6071.15 MiB/sec | ±1.73 | 1921.64 | ±11.25 | AMD EPYC 7763 64-Core Processor | 4 | 15990 MB |
| github-actions | ubuntu-latest | 1442.10 events/sec | ±0.69 | 6074.77 MiB/sec | ±3.16 | 1918.69 | ±9.11 | AMD EPYC 7763 64-Core Processor | 4 | 15990 MB |
| circleci | arm.medium | 1068.74 events/sec | ±0.46 | 3798.42 MiB/sec | ±11.68 | 5203.77 | ±134.79 | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.68 events/sec | ±1.29 | 3799.77 MiB/sec | ±6.80 | 5119.54 | ±309.40 | unknown | 32 | 16384 MB |
| circleci | xlarge | 445.61 events/sec | ±1.36 | 5090.85 MiB/sec | ±262.42 | 3558.92 | ±399.68 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | medium | 403.08 events/sec | ±13.24 | 5465.83 MiB/sec | ±324.59 | 3944.62 | ±633.64 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | large | 391.84 events/sec | ±11.21 | 5109.05 MiB/sec | ±51.39 | 4451.69 | ±282.79 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |

---
*58 total run(s) recorded.*
