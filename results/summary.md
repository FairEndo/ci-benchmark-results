# CI Benchmark Results

Last updated: 2026-03-28 01:29:13 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Network (median) | Net Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|------------------|------------|-----------|-------|-----|
| circleci | m4pro.large | 15354102.89 events/sec | ±160003.20 | 9272.01 MiB/sec | ±473.24 | 161362.24 | ±4357.70 | 82.19 MB/s | ±12.62 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 14312410.32 events/sec | ±75379.84 | 9011.52 MiB/sec | ±177.78 | 147474.52 | ±2232.03 | 81.08 MB/s | ±7.15 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-14 | 10075763.45 events/sec | ±30680.67 | 6352.96 MiB/sec | ±76.06 | 101299.88 | ±1633.23 | 135.42 MB/s | ±12.45 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-latest | 7725152.19 events/sec | ±365615.91 | 4786.33 MiB/sec | ±152.72 | 58012.97 | ±2919.66 | 125.88 MB/s | ±25.70 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 2303509.81 events/sec | ±98371.87 | 1624.40 MiB/sec | ±66.73 | 37443.82 | ±3656.47 | 99.42 MB/s | ±30.49 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.40 events/sec | ±0.32 | 5330.16 MiB/sec | ±2.99 | 599.83 | ±3.26 | 114.32 MB/s | ±25.67 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1444.21 events/sec | ±0.76 | 6017.3 MiB/sec | ±4.93 | 2085.59 | ±50.23 | 117.23 MB/s | ±15.7 | AMD EPYC 7763 64-Core Processor | 4 | 15995 MB |
| github-actions | ubuntu-latest | 1442.30 events/sec | ±0.59 | 6032.67 MiB/sec | ±4.77 | 1967.63 | ±36.50 | 142.25 MB/s | ±40.58 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| github-actions | ubuntu-24.04 | 1430.10 events/sec | ±9.10 | 5976.03 MiB/sec | ±13.26 | 2074.33 | ±44.95 | 78.61 MB/s | ±27.42 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| circleci | machine.arm.large | 1142.52 events/sec | ±0.26 | 4622.42 MiB/sec | ±3.45 | 783.56 | ±2.24 | 113.90 MB/s | ±29.92 | unknown | 4 | 15671 MB |
| circleci | machine.arm.medium | 1142.44 events/sec | ±0.24 | 4622.61 MiB/sec | ±2.39 | 781.26 | ±8.92 | 123.64 MB/s | ±18.48 | unknown | 2 | 7761 MB |
| circleci | machine.medium | 1139.89 events/sec | ±1.94 | 6779.10 MiB/sec | ±6.58 | 777.73 | ±4.81 | 112.39 MB/s | ±8.62 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 2 | 7780 MB |
| circleci | machine.large | 1139.14 events/sec | ±2.93 | 6778.62 MiB/sec | ±1.98 | 776.08 | ±3.11 | 90.14 MB/s | ±25.50 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 4 | 15706 MB |
| circleci | machine.xlarge | 1138.92 events/sec | ±1.10 | 6778.52 MiB/sec | ±5.17 | 773.99 | ±36.12 | 109.80 MB/s | ±9.85 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 8 | 31556 MB |
| circleci | arm.medium | 1069.12 events/sec | ±0.63 | 3818.19 MiB/sec | ±7.28 | 5744.10 | ±63.41 | 92.98 MB/s | ±19.60 | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.91 events/sec | ±0.81 | 3803.65 MiB/sec | ±9.85 | 5433.27 | ±37.45 | 110.96 MB/s | ±27.46 | unknown | 32 | 16384 MB |
| circleci | medium | 443.87 events/sec | ±9.49 | 5677.35 MiB/sec | ±49.50 | 2991.67 | ±548.23 | 106.78 MB/s | ±23.73 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | large | 442.37 events/sec | ±4.02 | 5706.14 MiB/sec | ±34.92 | 3354.89 | ±733.96 | 82.84 MB/s | ±28.74 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | xlarge | 438.06 events/sec | ±7.20 | 5616.93 MiB/sec | ±60.03 | 3263.04 | ±395.83 | 110.55 MB/s | ±28.46 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |

---
*117 total run(s) recorded.*
