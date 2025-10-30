# ReATest

**Enhancing Policy-as-Code workflows through automated test case generation from Rego policies**

---

## 📘 Overview

**ReATest** is a framework that automates the generation and optimization of test cases for **Rego** policies in *Policy-as-Code (PaC)* workflows.  
It bridges *formal graph-based analysis* and *metaheuristic optimization* to improve the reliability and efficiency of Rego policy testing.

> 🔍 ReATest constructs a **Rego Flow Graph (RFG)** for each policy, systematically explores execution paths using **Depth-First Search (DFS)**, and applies the **Grey Wolf Optimization (GWO)** algorithm to minimize redundancy while preserving high coverage.

This repository contains:
- Complete implementation of ReATest
- Example Rego policies and test suites
- Experimental results and datasets
- Statistical analysis scripts used in the paper

---

## 🧩 Features

- ✅ Automatic **RFG construction** from Rego policies  
- ✅ **Systematic test case generation** ensuring path coverage  
- ✅ **Optimization using GWO** for compact, high-coverage test suites  
- ✅ Seamless integration into **DevSecOps pipelines**  
- ✅ Interactive GUI for policy visualization and coverage comparison

---

