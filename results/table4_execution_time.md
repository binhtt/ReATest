# Table 4. Execution-Time Evaluation

Execution times of the ReATest components (mean ± standard deviation over 30 independent runs).

| Policy | RFG (ms) | DFS (ms) | GWO (ms) | Total (ms) |
|:------|---------:|---------:|---------:|-----------:|
| P1 | 0.6 ± 0.5 | 0.1 ± 0.0 | 4.7 ± 0.9 | 5.5 ± 1.3 |
| P2 | 0.3 ± 0.1 | 0.1 ± 0.0 | 3.7 ± 0.4 | 4.0 ± 0.5 |
| P3 | 0.2 ± 0.1 | 0.1 ± 0.0 | 3.2 ± 0.3 | 3.5 ± 0.4 |
| P4 | 0.3 ± 0.1 | 0.1 ± 0.0 | 17.5 ± 0.6 | 18.0 ± 0.7 |
| P5 | 0.1 ± 0.0 | 0.0 ± 0.0 | 8.0 ± 0.7 | 8.2 ± 0.8 |
| P6 | 0.3 ± 0.2 | 0.1 ± 0.1 | 8.6 ± 0.7 | 9.0 ± 0.8 |
| P7 | 0.7 ± 0.2 | 0.1 ± 0.0 | 27.6 ± 1.6 | 28.4 ± 1.8 |
| **Average** | **0.4** | **0.1** | **10.5** | **11.0** |

## Experimental Setup

- **Implementation:** Java (JDK 21)
- **Development environment:** Eclipse IDE
- **Operating system:** Windows 11
- **Hardware:** 12th Gen Intel® Core™ i5-1235U (1.30 GHz), 12 GB RAM, Intel Iris Xe Graphics
- **Number of runs:** 30 independent runs for each policy

**Component descriptions**

- **RFG:** Rego Flow Graph construction.
- **DFS:** DFS-based test-case generation.
- **GWO:** Grey Wolf Optimization for test-suite reduction.
- **Total:** End-to-end execution time of the complete ReATest workflow.

The results show that the complete workflow completes within milliseconds, indicating that ReATest introduces only a small execution-time overhead while providing automated test-suite generation and optimization.
