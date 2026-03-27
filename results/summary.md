# CI Benchmark Results

Last updated: 2026-03-27 16:58:34 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|-----------|-------|-----|
| circleci | m4pro.medium | 15114028.60 events/sec | ±67783.55 | 9414.79 MiB/sec | ±76.84 | 149648.70 | ±366.93 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| circleci | m4pro.large | 15071214.67 events/sec | ±53985.66 | 9490.30 MiB/sec | ±45.88 | 158775.87 | ±599.39 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| github-actions | macos-latest | 9476077.01 events/sec | ±61735.80 | 5954.74 MiB/sec | ±86.84 | 90431.18 | ±1378.48 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 9307766.10 events/sec | ±59575.31 | 5798.43 MiB/sec | ±120.86 | 84850.08 | ±644.51 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3453056.65 events/sec | ±32697.52 | 2613.91 MiB/sec | ±17.51 | 49830.15 | ±342.84 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.55 events/sec | ±0.22 | 5331.89 MiB/sec | ±0.97 | 722.43 | ±11.46 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-latest | 1442.88 events/sec | ±0.52 | 6036.30 MiB/sec | ±5.83 | 2026.42 | ±14.06 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| github-actions | ubuntu-24.04 | 1441.89 events/sec | ±2.09 | 6029.71 MiB/sec | ±9.14 | 1593.95 | ±31.57 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| github-actions | ubuntu-22.04 | 1289.8 events/sec | ±1.1 | 5534.88 MiB/sec | ±17.13 | 2217.95 | ±20.08 | AMD EPYC 9V74 80-Core Processor | 4 | 15991 MB |
| circleci | arm.medium | 1068.74 events/sec | ±0.46 | 3798.42 MiB/sec | ±11.68 | 5203.77 | ±134.79 | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.68 events/sec | ±1.29 | 3799.77 MiB/sec | ±6.80 | 5119.54 | ±309.40 | unknown | 32 | 16384 MB |
| circleci | xlarge | 445.61 events/sec | ±1.36 | 5090.85 MiB/sec | ±262.42 | 3558.92 | ±399.68 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | medium | 403.08 events/sec | ±13.24 | 5465.83 MiB/sec | ±324.59 | 3944.62 | ±633.64 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | large | 391.84 events/sec | ±11.21 | 5109.05 MiB/sec | ±51.39 | 4451.69 | ±282.79 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |

---
*65 total run(s) recorded.*
