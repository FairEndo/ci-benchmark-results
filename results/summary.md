# CI Benchmark Results

Last updated: 2026-03-27 20:03:23 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Network (median) | Net Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|------------------|------------|-----------|-------|-----|
| circleci | m4pro.large | 14022326.15 events/sec | ±275381.19 | 8745.82 MiB/sec | ±60.11 | 157486.97 | ±3344.55 | 70.70 MB/s | ±4.45 | Apple M4 Pro (Virtual) | 12 | 57344 MB |
| circleci | m4pro.medium | 13973809.06 events/sec | ±58111.30 | 8944.59 MiB/sec | ±182.76 | 142719.96 | ±5566.92 | 56.85 MB/s | ±8.98 | Apple M4 Pro (Virtual) | 6 | 28672 MB |
| github-actions | macos-latest | 8615396.88 events/sec | ±326137.82 | 4982.23 MiB/sec | ±475.61 | 57554.60 | ±6539.26 | 98.70 MB/s | ±16.47 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 8180800.30 events/sec | ±173591.70 | 5206.81 MiB/sec | ±243.34 | 78979.36 | ±2739.42 | 115.52 MB/s | ±7.60 | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-15-intel | 3427549.19 events/sec | ±140173.32 | 2670.19 MiB/sec | ±187.46 | 49146.78 | ±1379.13 | 131.12 MB/s | ±24.67 | Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz | 4 | 14336 MB |
| github-actions | ubuntu-24.04-arm | 1499.76 events/sec | ±0.05 | 5334.14 MiB/sec | ±1.71 | 668.54 | ±5.08 | 98.95 MB/s | ±16.18 | unknown | 4 | 15950 MB |
| github-actions | ubuntu-22.04 | 1444.7 events/sec | ±0.43 | 6020.92 MiB/sec | ±4.44 | 1668.65 | ±109.82 | 148.79 MB/s | ±38.99 | AMD EPYC 7763 64-Core Processor | 4 | 15995 MB |
| github-actions | ubuntu-24.04 | 1442.20 events/sec | ±0.70 | 6035.38 MiB/sec | ±9.35 | 1390.25 | ±113.27 | 99.93 MB/s | ±20.49 | AMD EPYC 7763 64-Core Processor | 4 | 15993 MB |
| github-actions | ubuntu-latest | 1441.98 events/sec | ±0.80 | 6031.14 MiB/sec | ±31.26 | 2024.51 | ±18.13 | 70.31 MB/s | ±3.02 | AMD EPYC 7763 64-Core Processor | 4 | 15989 MB |
| circleci | machine.arm.large | 1142.62 events/sec | ±0.38 | 4621.18 MiB/sec | ±3.80 | 784.24 | ±1.23 | 88.44 MB/s | ±16.72 | unknown | 4 | 15671 MB |
| circleci | machine.arm.medium | 1142.55 events/sec | ±0.23 | 4626.21 MiB/sec | ±3.28 | 783.57 | ±3.24 | 85.76 MB/s | ±18.48 | unknown | 2 | 7761 MB |
| circleci | machine.xlarge | 1141.04 events/sec | ±0.36 | 6786.28 MiB/sec | ±3.25 | 776.68 | ±1.20 | 106.55 MB/s | ±21.03 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 8 | 31556 MB |
| circleci | machine.medium | 1140.31 events/sec | ±1.25 | 6770.56 MiB/sec | ±10.44 | 780.49 | ±0.40 | 91.53 MB/s | ±28.55 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 2 | 7780 MB |
| circleci | machine.large | 1139.70 events/sec | ±1.06 | 6781.25 MiB/sec | ±7.04 | 776.45 | ±0.64 | 98.38 MB/s | ±27.67 | Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz | 4 | 15706 MB |
| circleci | arm.large | 1070.28 events/sec | ±0.81 | 3816.26 MiB/sec | ±7.19 | 5337.90 | ±154.49 | 88.18 MB/s | ±30.73 | unknown | 32 | 16384 MB |
| circleci | arm.medium | 1068.17 events/sec | ±1.08 | 3796.82 MiB/sec | ±10.97 | 5100.92 | ±66.54 | 83.53 MB/s | ±14.17 | unknown | 32 | 8192 MB |
| circleci | medium | 450.01 events/sec | ±1.49 | 5786.59 MiB/sec | ±1.92 | 4071.42 | ±304.52 | 101.47 MB/s | ±4.85 | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | large | 441.95 events/sec | ±9.94 | 4844.68 MiB/sec | ±149.96 | 4148.91 | ±172.92 | 71.62 MB/s | ±16.51 | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | xlarge | 434.17 events/sec | ±5.58 | 5584.90 MiB/sec | ±169.03 | 4016.18 | ±300.79 | 87.35 MB/s | ±11.38 | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 16384 MB |

---
*91 total run(s) recorded.*
