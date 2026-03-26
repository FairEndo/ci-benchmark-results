# CI Benchmark Results

Last updated: 2026-03-26 23:19:39 UTC

Showing the most recent run per provider/runner combination.
Full history is available in [`results/raw/`](raw/).

| Provider | Runner | CPU Score (median) | CPU Stddev | Memory (median) | Mem Stddev | Disk (composite) | Disk Stddev | Processor | vCPUs | RAM |
|----------|--------|--------------------|------------|-----------------|------------|-------------------|-------------|-----------|-------|-----|
| github-actions | macos-latest | 9430521.35 events/sec | ±462460.32 | 5755.72 MiB/sec | ±256.64 | — | — | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | macos-14 | 8028801.34 events/sec | ±438165.09 | 5369.47 MiB/sec | ±157.77 | — | — | Apple M1 (Virtual) | 3 | 7168 MB |
| github-actions | ubuntu-latest | 1444.02 events/sec | ±0.07 | 6074.94 MiB/sec | ±2.85 | — | — | AMD EPYC 7763 64-Core Processor | 4 | 15994 MB |
| github-actions | ubuntu-22.04 | 1147.3 events/sec | ±1.87 | 6942.52 MiB/sec | ±17.77 | — | — | Intel(R) Xeon(R) Platinum 8370C CPU @ 2.80GHz | 4 | 15994 MB |
| github-actions | ubuntu-24.04 | 1146.87 events/sec | ±1.98 | 7059.58 MiB/sec | ±3.91 | — | — | Intel(R) Xeon(R) Platinum 8370C CPU @ 2.80GHz | 4 | 15989 MB |
| circleci | arm.medium | 1069.29 events/sec | ±0.68 | 3787.74 MiB/sec | ±7.52 | — | — | unknown | 32 | 8192 MB |
| circleci | arm.large | 1068.40 events/sec | ±0.93 | 3799.70 MiB/sec | ±119.27 | — | — | unknown | 32 | 16384 MB |
| circleci | large | 446.99 events/sec | ±1.95 | 5777.50 MiB/sec | ±46.09 | — | — | Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz | 36 | 8192 MB |
| circleci | medium | 444.56 events/sec | ±6.17 | 5410.25 MiB/sec | ±286.38 | — | — | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 4096 MB |
| circleci | xlarge | 441.61 events/sec | ±6.06 | 5774.44 MiB/sec | ±8.01 | — | — | Intel(R) Xeon(R) Platinum 8223CL CPU @ 3.00GHz | 36 | 16384 MB |

---
*25 total run(s) recorded.*
