# ReATest

**Enhancing Policy-as-Code Workflows through Automated Test Case Generation from Rego Policies**

---

## 📘 Overview

**ReATest** is a framework for automatically generating and optimizing test cases for **Rego** policies in *Policy-as-Code (PaC)* workflows.
It combines **graph-based policy modeling** with **metaheuristic optimization** to improve the effectiveness and efficiency of automated policy testing.

> 🔍 ReATest constructs a **Rego Flow Graph (RFG)** for each policy, systematically explores execution paths using **Depth-First Search (DFS)**, and applies the **Grey Wolf Optimization (GWO)** algorithm to eliminate redundant test cases while preserving **100% logical rule coverage**.

This repository contains:

- Complete implementation of ReATest
- Example Rego policies and generated test suites
- Experimental datasets
- Execution-time evaluation results (Table 4)
- Statistical analysis scripts used in the paper

---

## 🧩 Features

- ✅ Automatic **RFG construction** from Rego policies
- ✅ **Systematic DFS-based test case generation**
- ✅ **GWO-based test-suite optimization**
- ✅ **100% logical rule coverage** through coverage repair
- ✅ Execution-time evaluation for all framework components
- ✅ Interactive GUI for policy visualization and test-suite comparison

---

## 📊 Experimental Results

The experimental evaluation was conducted on **seven representative Kubernetes admission-control policies**.

| Metric | Value |
|:--|:--|
| Test-suite reduction (GWO) | **35.43%** |
| Test-case retention | **64.57%** |
| Logical rule coverage | **100%** |
| Average execution time | **11.0 ms** |
| Reduction compared with published baselines | **69.77% fewer tests** |

The complete workflow, including **RFG construction**, **DFS-based test generation**, and **GWO optimization**, completes within milliseconds while preserving complete logical rule coverage.

---

## 📂 Repository Structure

```text
src/            Java implementation of ReATest
examples/       Example Rego policies and generated test suites
results/        Experimental results and execution-time evaluation
README.md       Project documentation
LICENSE         MIT License
```

---

## 📄 Replication Package

This repository serves as the replication package accompanying the paper. It includes the source code, experimental datasets, execution-time evaluation, and statistical analysis scripts required to reproduce the reported results.
