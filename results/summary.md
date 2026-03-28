# CI Benchmark Results

Last updated: 2026-03-28 01:32:11 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Network (median) | Net Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|------------------|------------|-----------|-------|-----|
| circleci | m4pro.large | 15650686.48 events/sec | ±53099.22 | 9949.53 MiB/sec | ±72.15 | 167725.92 | ±1393.47 | 65.39 MB/s | ±16.85 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 15113735.46 events/sec | ±409768.48 | 9790.89 MiB/sec | ±90.88 | 151997.10 | ±4898.11 | 66.73 MB/s | ±5.65 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-14 | 10075763.45 events/sec | ±30680.67 | 6352.96 MiB/sec | ±76.06 | 101299.88 | ±1633.23 | 135.42 MB/s | ±12.45 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-latest | 7725152.19 events/sec | ±365615.91 | 4786.33 MiB/sec | ±152.72 | 58012.97 | ±2919.66 | 125.88 MB/s | ±25.70 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 2303509.81 events/sec | ±98371.87 | 1624.40 MiB/sec | ±66.73 | 37443.82 | ±3656.47 | 99.42 MB/s | ±30.49 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.40 events/sec | ±0.32 | 5330.16 MiB/sec | ±2.99 | 599.83 | ±3.26 | 114.32 MB/s | ±25.67 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1444.21 events/sec | ±0.76 | 6017.3 MiB/sec | ±4.93 | 2085.59 | ±50.23 | 117.23 MB/s | ±15.7 | AMD EPYC 7763 64-Core Processor | 4 | 15995 MB |
| github-actions | ubuntu-latest | 1442.30 events/sec | ±0.59 | 6032.67 MiB/sec | ±4.77 | 1967.63 | ±36.50 | 142.25 MB/s | ±40.58 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| github-actions | ubuntu-24.04 | 1430.10 events/sec | ±9.10 | 5976.03 MiB/sec | ±13.26 | 2074.33 | ±44.95 | 78.61 MB/s | ±27.42 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| circleci | machine.arm.medium | 1142.57 events/sec | ±0.22 | 4622.46 MiB/sec | ±1.57 | 783.21 | ±3.29 | 92.11 MB/s | ±27.27 | unknown | 2 | 7761 MB |
| circleci | machine.arm.large | 1142.36 events/sec | ±0.22 | 4621.98 MiB/sec | ±3.61 | 784.67 | ±9.04 | 128.39 MB/s | ±16.09 | unknown | 4 | 15671 MB |
| circleci | machine.medium | 1140.78 events/sec | ±1.21 | 6777.99 MiB/sec | ±8.93 | 780.80 | ±2.91 | 114.08 MB/s | ±18.89 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 2 | 7780 MB |
| circleci | machine.large | 1139.96 events/sec | ±0.82 | 6845.58 MiB/sec | ±3.16 | 774.14 | ±3.33 | 124.88 MB/s | ±20.37 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 4 | 15706 MB |
| circleci | machine.xlarge | 1138.87 events/sec | ±1.67 | 6783.80 MiB/sec | ±2.89 | 776.90 | ±3.25 | 133.87 MB/s | ±22.74 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 8 | 31556 MB |
| circleci | arm.large | 1069.57 events/sec | ±0.82 | 3801.65 MiB/sec | ±6.82 | 5286.51 | ±178.50 | 112.96 MB/s | ±15.77 | unknown | 32 | 16384 MB |
| circleci | arm.medium | 1069.29 events/sec | ±1.22 | 3805.93 MiB/sec | ±12.60 | 5690.22 | ±74.15 | 112.29 MB/s | ±23.65 | unknown | 32 | 8192 MB |
| circleci | large | 444.76 events/sec | ±3.71 | 5764.35 MiB/sec | ±107.48 | 4346.36 | ±351.57 | 92.17 MB/s | ±35.39 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | medium | 443.45 events/sec | ±5.35 | 5710.35 MiB/sec | ±60.46 | 4053.13 | ±303.20 | 124.46 MB/s | ±17.34 | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | xlarge | 443.01 events/sec | ±6.00 | 5707.92 MiB/sec | ±37.79 | 4724.38 | ±151.23 | 127.05 MB/s | ±37.09 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |

---
*129 total run(s) recorded.*
