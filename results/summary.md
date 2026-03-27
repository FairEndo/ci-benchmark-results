# CI Benchmark Results

Last updated: 2026-03-27 17:02:53 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|-----------|-------|-----|
| circleci | m4pro.large | 15483043.39 events/sec | ±410596.18 | 9611.38 MiB/sec | ±25.76 | 159870.15 | ±1454.43 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 13265894.68 events/sec | ±181793.68 | 8006.69 MiB/sec | ±427.09 | 149515.30 | ±4969.93 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-latest | 9476077.01 events/sec | ±61735.80 | 5954.74 MiB/sec | ±86.84 | 90431.18 | ±1378.48 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 9307766.10 events/sec | ±59575.31 | 5798.43 MiB/sec | ±120.86 | 84850.08 | ±644.51 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3453056.65 events/sec | ±32697.52 | 2613.91 MiB/sec | ±17.51 | 49830.15 | ±342.84 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.55 events/sec | ±0.22 | 5331.89 MiB/sec | ±0.97 | 722.43 | ±11.46 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-latest | 1442.88 events/sec | ±0.52 | 6036.30 MiB/sec | ±5.83 | 2026.42 | ±14.06 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| github-actions | ubuntu-24.04 | 1441.89 events/sec | ±2.09 | 6029.71 MiB/sec | ±9.14 | 1593.95 | ±31.57 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| github-actions | ubuntu-22.04 | 1289.8 events/sec | ±1.1 | 5534.88 MiB/sec | ±17.13 | 2217.95 | ±20.08 | AMD EPYC 9V74 80-Core Processor | 4 | 15991 MB |
| circleci | arm.large | 1068.32 events/sec | ±0.99 | 3812.96 MiB/sec | ±8.49 | 5081.49 | ±183.76 | unknown | 32 | 16384 MB |
| circleci | arm.medium | 1067.94 events/sec | ±1.16 | 3797.63 MiB/sec | ±11.58 | 5344.18 | ±31.39 | unknown | 32 | 8192 MB |
| circleci | medium | 440.69 events/sec | ±9.07 | 5573.76 MiB/sec | ±181.79 | 3412.16 | ±238.51 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | xlarge | 435.13 events/sec | ±4.54 | 5717.99 MiB/sec | ±50.83 | 4785.83 | ±503.34 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | large | 411.74 events/sec | ±19.51 | 5633.86 MiB/sec | ±144.57 | 4193.04 | ±322.78 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |

---
*72 total run(s) recorded.*
