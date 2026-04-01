# CI Benchmark Results

Last updated: 2026-04-01 17:11:40 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Network (median) | Net Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|------------------|------------|-----------|-------|-----|
| circleci | m4pro.large | 15353733.49 events/sec | ±57735.38 | 9489.18 MiB/sec | ±105.57 | 158626.00 | ±1139.46 | 83.37 MB/s | ±4.57 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 14659171.73 events/sec | ±520742.36 | 9037.67 MiB/sec | ±64.63 | 142438.78 | ±1369.14 | 64.51 MB/s | ±10.92 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-14 | 9095798.07 events/sec | ±69034.43 | 5807.72 MiB/sec | ±14.44 | 86243.75 | ±2572.34 | 151.97 MB/s | ±6.32 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-latest | 8399603.11 events/sec | ±209535.21 | 5330.58 MiB/sec | ±161.27 | 65680.71 | ±4933.65 | 84.14 MB/s | ±16.48 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3052153.23 events/sec | ±181880.66 | 2032.73 MiB/sec | ±51.03 | 39471.08 | ±2566.62 | 82.29 MB/s | ±21.10 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| circleci | gen2.2xlarge | 1647.13 events/sec | ±2.42 | 6985.52 MiB/sec | ±91.69 | 781.07 | ±3.18 | 127.12 MB/s | ±32.63 | AMD EPYC 9R14 | 16 | 62920 MB |
| circleci | gen2.medium | 1641.14 events/sec | ±0.68 | 7150.09 MiB/sec | ±3.51 | 779.45 | ±2.78 | 138.61 MB/s | ±23.56 | AMD EPYC 9R14 | 2 | 7736 MB |
| circleci | gen2.large | 1640.03 events/sec | ±0.96 | 7145.83 MiB/sec | ±2.00 | 777.71 | ±2.84 | 119.89 MB/s | ±24.47 | AMD EPYC 9R14 | 4 | 15620 MB |
| circleci | gen2.xlarge | 1639.97 events/sec | ±0.98 | 7148.18 MiB/sec | ±2.54 | 778.45 | ±41.49 | 111.69 MB/s | ±30.46 | AMD EPYC 9R14 | 8 | 31386 MB |
| circleci | gen2.2xlarge+ | 1639.54 events/sec | ±0.78 | 7146.15 MiB/sec | ±1.45 | 776.94 | ±3.28 | 140.54 MB/s | ±35.28 | AMD EPYC 9R14 | 32 | 126082 MB |
| github-actions | ubuntu-24.04-arm | 1499.30 events/sec | ±0.43 | 5331.85 MiB/sec | ±1.27 | 710.12 | ±27.19 | 98.20 MB/s | ±24.95 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1443.24 events/sec | ±6 | 6022.16 MiB/sec | ±8.82 | 2010.31 | ±48.29 | 70.23 MB/s | ±9.77 | AMD EPYC 7763 64-Core Processor | 4 | 15991 MB |
| github-actions | ubuntu-24.04 | 1442.88 events/sec | ±0.43 | 6029.70 MiB/sec | ±7.88 | 2026.47 | ±44.73 | 128.06 MB/s | ±16.27 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| github-actions | ubuntu-latest | 1442.52 events/sec | ±0.42 | 6036.97 MiB/sec | ±4.76 | 2040.45 | ±55.24 | 98.75 MB/s | ±14.41 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| circleci | machine.arm.medium | 1142.65 events/sec | ±0.38 | 4624.60 MiB/sec | ±3.68 | 784.68 | ±4.02 | 126.68 MB/s | ±6.41 | unknown | 2 | 7761 MB |
| circleci | machine.arm.large | 1142.35 events/sec | ±0.24 | 4623.26 MiB/sec | ±1.23 | 786.24 | ±3.35 | 102.92 MB/s | ±14.31 | unknown | 4 | 15671 MB |
| circleci | machine.xlarge | 1140.46 events/sec | ±3.50 | 6782.92 MiB/sec | ±3.05 | 760.38 | ±4.82 | 111.37 MB/s | ±23.17 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 8 | 31556 MB |
| circleci | machine.large | 1140.11 events/sec | ±0.46 | 6781.97 MiB/sec | ±2.85 | 775.71 | ±3.32 | 121.39 MB/s | ±42.22 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 4 | 15706 MB |
| circleci | machine.medium | 1139.15 events/sec | ±0.51 | 6835.14 MiB/sec | ±8.06 | 776.02 | ±3.13 | 99.55 MB/s | ±20.26 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 2 | 7780 MB |
| circleci | arm.medium | 1068.78 events/sec | ±0.46 | 3795.10 MiB/sec | ±9.87 | 5325.31 | ±202.94 | 119.09 MB/s | ±40.32 | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.18 events/sec | ±8.87 | 3799.94 MiB/sec | ±7.32 | 5395.36 | ±130.92 | 91.70 MB/s | ±24.30 | unknown | 32 | 16384 MB |
| circleci | medium | 450.44 events/sec | ±0.14 | 5840.64 MiB/sec | ±26.66 | 4418.41 | ±154.70 | 133.02 MB/s | ±15.55 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | xlarge | 438.88 events/sec | ±2.06 | 5512.97 MiB/sec | ±62.71 | 3853.58 | ±243.95 | 131.89 MB/s | ±19.77 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 16384 MB |
| circleci | large | 433.67 events/sec | ±6.07 | 5698.00 MiB/sec | ±18.77 | 2710.64 | ±589.99 | 114.22 MB/s | ±11.95 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |

---
*174 total run(s) recorded.*
