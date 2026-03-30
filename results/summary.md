# CI Benchmark Results

Last updated: 2026-03-30 18:25:33 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Network (median) | Net Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|------------------|------------|-----------|-------|-----|
| circleci | m4pro.large | 15548127.45 events/sec | ±53930.73 | 9930.78 MiB/sec | ±38.61 | 167999.20 | ±3345.52 | 67.39 MB/s | ±4.42 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 15301510.97 events/sec | ±147596.86 | 9634.75 MiB/sec | ±38.55 | 155407.68 | ±3667.83 | 72.99 MB/s | ±2.10 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-14 | 10075763.45 events/sec | ±30680.67 | 6352.96 MiB/sec | ±76.06 | 101299.88 | ±1633.23 | 135.42 MB/s | ±12.45 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-latest | 7725152.19 events/sec | ±365615.91 | 4786.33 MiB/sec | ±152.72 | 58012.97 | ±2919.66 | 125.88 MB/s | ±25.70 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 2303509.81 events/sec | ±98371.87 | 1624.40 MiB/sec | ±66.73 | 37443.82 | ±3656.47 | 99.42 MB/s | ±30.49 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.40 events/sec | ±0.32 | 5330.16 MiB/sec | ±2.99 | 599.83 | ±3.26 | 114.32 MB/s | ±25.67 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1444.21 events/sec | ±0.76 | 6017.3 MiB/sec | ±4.93 | 2085.59 | ±50.23 | 117.23 MB/s | ±15.7 | AMD EPYC 7763 64-Core Processor | 4 | 15995 MB |
| github-actions | ubuntu-latest | 1442.30 events/sec | ±0.59 | 6032.67 MiB/sec | ±4.77 | 1967.63 | ±36.50 | 142.25 MB/s | ±40.58 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| github-actions | ubuntu-24.04 | 1430.10 events/sec | ±9.10 | 5976.03 MiB/sec | ±13.26 | 2074.33 | ±44.95 | 78.61 MB/s | ±27.42 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| circleci | machine.arm.large | 1142.49 events/sec | ±0.57 | 4627.51 MiB/sec | ±2.21 | 739.10 | ±10.47 | 90.08 MB/s | ±14.28 | unknown | 4 | 15671 MB |
| circleci | machine.arm.medium | 1142.18 events/sec | ±0.32 | 4622.78 MiB/sec | ±2.23 | 784.32 | ±16.64 | 97.62 MB/s | ±20.16 | unknown | 2 | 7761 MB |
| circleci | machine.medium | 1141.18 events/sec | ±0.67 | 6783.91 MiB/sec | ±3.56 | 780.00 | ±3.19 | 77.69 MB/s | ±21.54 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 2 | 7780 MB |
| circleci | machine.xlarge | 1140.68 events/sec | ±0.15 | 6784.31 MiB/sec | ±1.71 | 775.40 | ±17.22 | 98.72 MB/s | ±20.31 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 8 | 31556 MB |
| circleci | machine.large | 1139.74 events/sec | ±0.38 | 6841.90 MiB/sec | ±6.13 | 775.90 | ±8.23 | 91.43 MB/s | ±24.84 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 4 | 15706 MB |
| circleci | arm.large | 1069.12 events/sec | ±0.45 | 3801.03 MiB/sec | ±10.36 | 4971.79 | ±383.20 | 82.16 MB/s | ±8.01 | unknown | 32 | 16384 MB |
| circleci | arm.medium | 1068.93 events/sec | ±1.09 | 3816.82 MiB/sec | ±13.90 | 5528.48 | ±280.84 | 62.89 MB/s | ±24.60 | unknown | 32 | 8192 MB |
| circleci | large | 445.90 events/sec | ±5.50 | 5687.94 MiB/sec | ±54.48 | 3986.48 | ±406.75 | 97.87 MB/s | ±14.72 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | xlarge | 438.31 events/sec | ±7.50 | 5534.98 MiB/sec | ±320.93 | 4228.87 | ±410.74 | 83.47 MB/s | ±23.53 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | medium | 355.27 events/sec | ±25.06 | 5112.40 MiB/sec | ±436.26 | 3928.67 | ±343.41 | 97.22 MB/s | ±16.55 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |

---
*136 total run(s) recorded.*
