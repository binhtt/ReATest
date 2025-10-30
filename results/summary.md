# Experimental Results — ReATest

This folder contains the evaluation results reported in the paper.

| Metric | Value |
|:--|:--|
| Total policies tested | **7** |
| Avg. reduction in test suite size | **35.43%** |
| Avg. coverage retained | **64.57%** |
| Absolute deviation from published baselines | **−69.77%** |

ReATest achieves a balance between **completeness** (through DFS-based exploration) and **efficiency** (via GWO optimization), enabling reliable and scalable Rego policy testing for DevSecOps workflows.

Each row in `evaluation-summary.csv` corresponds to one of the OPA policies evaluated during the study:

- **privileged-containers**
- **host-namespaces**
- **restricted-volumes**
- **host-filesystem**
- **allow-privilege-escalation**
- **capabilities**
- **seccomp**

All experiments were executed on a controlled environment with reproducible datasets.  
Statistical analysis scripts and raw results are available in the supplementary material repository.
