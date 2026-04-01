# CI Benchmark Results

Last updated: 2026-04-01 17:14:35 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Network (median) | Net Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|------------------|------------|-----------|-------|-----|
| circleci | m4pro.large | 15525541.85 events/sec | ±94912.90 | 9654.88 MiB/sec | ±67.59 | 160422.08 | ±2224.43 | 74.73 MB/s | ±15.61 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 13564155.90 events/sec | ±278480.75 | 8113.10 MiB/sec | ±402.89 | 135827.36 | ±1876.99 | 76.90 MB/s | ±14.81 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-14 | 9095798.07 events/sec | ±69034.43 | 5807.72 MiB/sec | ±14.44 | 86243.75 | ±2572.34 | 151.97 MB/s | ±6.32 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-latest | 8399603.11 events/sec | ±209535.21 | 5330.58 MiB/sec | ±161.27 | 65680.71 | ±4933.65 | 84.14 MB/s | ±16.48 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3052153.23 events/sec | ±181880.66 | 2032.73 MiB/sec | ±51.03 | 39471.08 | ±2566.62 | 82.29 MB/s | ±21.10 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| circleci | gen2.2xlarge+ | 1640.91 events/sec | ±1.17 | 7146.65 MiB/sec | ±3.41 | 777.16 | ±36.51 | 118.44 MB/s | ±52.90 | AMD EPYC 9R14 | 32 | 126082 MB |
| circleci | gen2.xlarge | 1640.62 events/sec | ±0.57 | 7144.23 MiB/sec | ±7.04 | 777.82 | ±2.53 | 81.23 MB/s | ±26.34 | AMD EPYC 9R14 | 8 | 31386 MB |
| circleci | gen2.large | 1639.98 events/sec | ±0.37 | 7151.62 MiB/sec | ±8.59 | 777.83 | ±2.89 | 101.84 MB/s | ±39.68 | AMD EPYC 9R14 | 4 | 15620 MB |
| circleci | gen2.medium | 1639.78 events/sec | ±0.93 | 7147.42 MiB/sec | ±1.08 | 770.10 | ±5.68 | 79.55 MB/s | ±36.13 | AMD EPYC 9R14 | 2 | 7736 MB |
| circleci | gen2.2xlarge | 1637.81 events/sec | ±0.84 | 7139.86 MiB/sec | ±0.99 | 777.25 | ±3.20 | 116.98 MB/s | ±26.82 | AMD EPYC 9R14 | 16 | 62920 MB |
| github-actions | ubuntu-24.04-arm | 1499.30 events/sec | ±0.43 | 5331.85 MiB/sec | ±1.27 | 710.12 | ±27.19 | 98.20 MB/s | ±24.95 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1443.24 events/sec | ±6 | 6022.16 MiB/sec | ±8.82 | 2010.31 | ±48.29 | 70.23 MB/s | ±9.77 | AMD EPYC 7763 64-Core Processor | 4 | 15991 MB |
| github-actions | ubuntu-24.04 | 1442.88 events/sec | ±0.43 | 6029.70 MiB/sec | ±7.88 | 2026.47 | ±44.73 | 128.06 MB/s | ±16.27 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| github-actions | ubuntu-latest | 1442.52 events/sec | ±0.42 | 6036.97 MiB/sec | ±4.76 | 2040.45 | ±55.24 | 98.75 MB/s | ±14.41 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| circleci | machine.arm.medium | 1142.69 events/sec | ±0.15 | 4627.03 MiB/sec | ±3.51 | 780.31 | ±4.05 | 111.51 MB/s | ±38.45 | unknown | 2 | 7761 MB |
| circleci | machine.arm.large | 1142.43 events/sec | ±0.52 | 4622.34 MiB/sec | ±2.02 | 736.25 | ±12.80 | 66.73 MB/s | ±42.92 | unknown | 4 | 15671 MB |
| circleci | machine.large | 1141.76 events/sec | ±3.17 | 6784.84 MiB/sec | ±3.85 | 773.94 | ±4.02 | 82.69 MB/s | ±31.73 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 4 | 15706 MB |
| circleci | machine.xlarge | 1139.85 events/sec | ±1.05 | 6781.31 MiB/sec | ±4.58 | 775.86 | ±3.12 | 88.65 MB/s | ±43.81 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 8 | 31556 MB |
| circleci | machine.medium | 1139.22 events/sec | ±1.42 | 6801.54 MiB/sec | ±29.39 | 702.93 | ±30.47 | 95.63 MB/s | ±32.98 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 2 | 7780 MB |
| circleci | arm.medium | 1068.80 events/sec | ±1.16 | 3797.25 MiB/sec | ±6.04 | 5565.87 | ±101.01 | 91.91 MB/s | ±30.03 | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.27 events/sec | ±0.90 | 3801.52 MiB/sec | ±6.54 | 5674.96 | ±23.20 | 90.65 MB/s | ±9.68 | unknown | 32 | 16384 MB |
| circleci | xlarge | 444.50 events/sec | ±7.91 | 5397.36 MiB/sec | ±143.96 | 3842.23 | ±406.97 | 84.00 MB/s | ±19.36 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | large | 440.15 events/sec | ±3.44 | 5636.01 MiB/sec | ±325.97 | 3933.25 | ±580.21 | 87.84 MB/s | ±21.04 | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | medium | 423.51 events/sec | ±11.78 | 5640.89 MiB/sec | ±39.02 | 3528.35 | ±708.61 | 61.80 MB/s | ±35.64 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |

---
*191 total run(s) recorded.*
