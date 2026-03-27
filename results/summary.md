# CI Benchmark Results

Last updated: 2026-03-27 19:59:24 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Network (median) | Net Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|------------------|------------|-----------|-------|-----|
| circleci | m4pro.large | 15483043.39 events/sec | ±410596.18 | 9611.38 MiB/sec | ±25.76 | 159870.15 | ±1454.43 | — | — | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 13265894.68 events/sec | ±181793.68 | 8006.69 MiB/sec | ±427.09 | 149515.30 | ±4969.93 | — | — | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-latest | 8615396.88 events/sec | ±326137.82 | 4982.23 MiB/sec | ±475.61 | 57554.60 | ±6539.26 | 98.70 MB/s | ±16.47 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 8180800.30 events/sec | ±173591.70 | 5206.81 MiB/sec | ±243.34 | 78979.36 | ±2739.42 | 115.52 MB/s | ±7.60 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3427549.19 events/sec | ±140173.32 | 2670.19 MiB/sec | ±187.46 | 49146.78 | ±1379.13 | 131.12 MB/s | ±24.67 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.76 events/sec | ±0.05 | 5334.14 MiB/sec | ±1.71 | 668.54 | ±5.08 | 98.95 MB/s | ±16.18 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1444.7 events/sec | ±0.43 | 6020.92 MiB/sec | ±4.44 | 1668.65 | ±109.82 | 148.79 MB/s | ±38.99 | AMD EPYC 7763 64-Core Processor | 4 | 15995 MB |
| github-actions | ubuntu-24.04 | 1442.20 events/sec | ±0.70 | 6035.38 MiB/sec | ±9.35 | 1390.25 | ±113.27 | 99.93 MB/s | ±20.49 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| github-actions | ubuntu-latest | 1441.98 events/sec | ±0.80 | 6031.14 MiB/sec | ±31.26 | 2024.51 | ±18.13 | 70.31 MB/s | ±3.02 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| circleci | arm.large | 1068.32 events/sec | ±0.99 | 3812.96 MiB/sec | ±8.49 | 5081.49 | ±183.76 | — | — | unknown | 32 | 16384 MB |
| circleci | arm.medium | 1067.94 events/sec | ±1.16 | 3797.63 MiB/sec | ±11.58 | 5344.18 | ±31.39 | — | — | unknown | 32 | 8192 MB |
| circleci | medium | 440.69 events/sec | ±9.07 | 5573.76 MiB/sec | ±181.79 | 3412.16 | ±238.51 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | xlarge | 435.13 events/sec | ±4.54 | 5717.99 MiB/sec | ±50.83 | 4785.83 | ±503.34 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | large | 411.74 events/sec | ±19.51 | 5633.86 MiB/sec | ±144.57 | 4193.04 | ±322.78 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |

---
*79 total run(s) recorded.*
