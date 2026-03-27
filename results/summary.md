# CI Benchmark Results

Last updated: 2026-03-27 04:13:34 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|-----------|-------|-----|
| circleci | m4pro.medium | 15114028.60 events/sec | ±67783.55 | 9414.79 MiB/sec | ±76.84 | 149648.70 | ±366.93 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| circleci | m4pro.large | 15071214.67 events/sec | ±53985.66 | 9490.30 MiB/sec | ±45.88 | 158775.87 | ±599.39 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| github-actions | macos-latest | 9809339.70 events/sec | ±358465.11 | 6308.62 MiB/sec | ±46.30 | 81749.72 | ±4151.52 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 9103380.01 events/sec | ±260159.40 | 5403.71 MiB/sec | ±284.26 | 84857.38 | ±6438.11 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3171673.82 events/sec | ±57442.66 | 2142.25 MiB/sec | ±201.61 | 43686.42 | ±1812.09 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.45 events/sec | ±0.34 | 5331.77 MiB/sec | ±2.36 | 585.65 | ±16.49 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1444.62 events/sec | ±0.24 | 6020.64 MiB/sec | ±14.55 | 1591.49 | ±100.77 | AMD EPYC 7763 64-Core Processor | 4 | 15995 MB |
| github-actions | ubuntu-24.04 | 1442.47 events/sec | ±0.19 | 6035.59 MiB/sec | ±1.04 | 1998.72 | ±12.98 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| github-actions | ubuntu-latest | 1146.08 events/sec | ±0.90 | 7064.51 MiB/sec | ±5.85 | 2368.96 | ±15.94 | Intel(R) Xeon(R) Platinum 8370C CPU @ 2.80GHz | 4 | 15989 MB |
| circleci | arm.medium | 1068.74 events/sec | ±0.46 | 3798.42 MiB/sec | ±11.68 | 5203.77 | ±134.79 | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.68 events/sec | ±1.29 | 3799.77 MiB/sec | ±6.80 | 5119.54 | ±309.40 | unknown | 32 | 16384 MB |
| circleci | xlarge | 445.61 events/sec | ±1.36 | 5090.85 MiB/sec | ±262.42 | 3558.92 | ±399.68 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | medium | 403.08 events/sec | ±13.24 | 5465.83 MiB/sec | ±324.59 | 3944.62 | ±633.64 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | large | 391.84 events/sec | ±11.21 | 5109.05 MiB/sec | ±51.39 | 4451.69 | ±282.79 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |

---
*51 total run(s) recorded.*
