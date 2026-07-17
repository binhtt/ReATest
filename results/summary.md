# Experimental Results — ReATest

This folder contains the experimental results reported in the paper.

## Summary

| Metric | Value |
|:--|:--|
| Total policies evaluated | **7** |
| Avg. test-suite reduction (GWO) | **35.43%** |
| Avg. test-case retention | **64.57%** |
| Logical rule coverage | **100%** |
| Avg. execution time | **11.0 ms** |
| Reduction compared with published baselines | **69.77% fewer tests** |

ReATest combines exhaustive DFS-based test generation with Grey Wolf Optimization (GWO) to eliminate redundant test cases while preserving complete logical rule coverage. The execution-time evaluation shows that the complete workflow finishes within milliseconds, demonstrating the efficiency of the proposed implementation.

## Evaluated Policies

The experimental evaluation was conducted on the following seven Kubernetes admission-control policies:

- privileged-containers
- host-namespaces
- restricted-volumes
- host-filesystem
- allow-privilege-escalation
- capabilities
- seccomp

## Execution-Time Evaluation (Table 4)

Execution times were measured over **30 independent runs** for each policy.

| Component | Average Time (ms) |
|:--|--:|
| RFG construction | **0.4** |
| DFS-based test generation | **0.1** |
| GWO optimization | **10.5** |
| **Total workflow** | **11.0** |

The complete workflow includes Rego Flow Graph (RFG) construction, DFS-based test generation, and Grey Wolf Optimization (GWO).

## Reproducibility

All experiments were performed using reproducible datasets.

This repository contains:

- Complete ReATest implementation
- Example Rego policies and generated test suites
- Experimental results (Tables 3 and 4)
- Execution-time evaluation data
- Statistical analysis scripts used in the paper
