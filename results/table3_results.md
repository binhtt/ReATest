# Table 3. Test-Suite Reduction and Retention after GWO Optimization

Test-suite reduction and retention after Grey Wolf Optimization (mean ± standard deviation over 30 independent runs).

| Policy | DFS | GWO | Reduction (%) | Retention (%) |
|:------|----:|----:|--------------:|--------------:|
| P1 | 4 | 2 ± 0 | 50.00 ± 0.0 | 50.00 ± 0.0 |
| P2 | 3 | 2 ± 0 | 33.33 ± 0.0 | 66.67 ± 0.0 |
| P3 | 3 | 3 ± 0 | 0.00 ± 0.0 | 100.00 ± 0.0 |
| P4 | 18 | 13 ± 0 | 27.78 ± 0.0 | 72.22 ± 0.0 |
| P5 | 7 | 4 ± 0 | 42.86 ± 0.0 | 57.14 ± 0.0 |
| P6 | 9 | 4 ± 0 | 55.56 ± 0.0 | 44.44 ± 0.0 |
| P7 | 26 | 16 ± 0 | 38.46 ± 0.0 | 61.54 ± 0.0 |
| **Average** | **70** | **44 ± 0** | **35.43 ± 0.0** | **64.57 ± 0.0** |

## Notes

- **P1–P7** correspond to the seven Rego policies evaluated in the paper.
- **Retention (%)** is computed as **|TGWO| / |TDFS| × 100**.
- Algorithm 3 guarantees **100% logical rule coverage** for all optimized test suites.
- Results are reported as **mean ± standard deviation** over **30 independent runs**.
