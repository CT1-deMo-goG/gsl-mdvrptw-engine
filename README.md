[อ่านภาษาไทยที่นี่](README_TH.md)
# GSL Engine: MDVRPTW Module ⏱️
A high-performance deterministic optimization engine for the Multi-Depot Vehicle Routing Problem with Time Windows (MDVRPTW).

**Core Module:** `GSL_MDVRPTW_V38` (Academic) & `GSL_MDVRPTW_REAL_V29` (Real-World)

This repository represents the most complex routing architecture in the GSL framework. It handles multiple depots, strict 2D-capacity constraints (weight/volume), asymmetric distances (one-way streets), and rigid delivery time windows simultaneously, executed entirely on mobile architecture.

⚠️ **Disclaimer:** Source code is proprietary and not publicly available. This project is open for research collaboration and industrial applications.

## 🏆 Real-World Logistics Optimization (Bosnia Dataset)
To prove commercial viability, the engine was tested against a real-world logistics dataset from a major distribution company in Bosnia & Herzegovina. 

* **Legacy System Baseline (Company's Routing):** 537.43 KM
* **GSL Engine V29 Optimized Routing:** 368.35 KM
* **Business Impact:** **Saved 169.08 KM per delivery cycle (31.4% Cost Reduction)**
* **Compute Time:** **0.0078 Seconds**

## 📊 Academic Benchmark Portfolio
1. **Standard Cordeau Benchmark (pr01-pr20):** Achieved sub-second execution times with 100% feasibility.
2. **Large-Scale Vidal Benchmark (up to 960 nodes):** Established new mobile execution baselines for massive datasets.

👉 **See [RESULT_SUMMARY.md](./Benchmark_MDVRPTW/RESULT_SUMMARY.md) for full benchmark data and cost gaps.**
👉 **See [BENCHMARK_METHODOLOGY.md](./Docs/Benchmark_Methodology.md) for testing protocols.**
👉 **See [TECHNICAL_REPORT.md](./Docs/TECHNICAL_REPORT.md) for insights into the core logic.**

---

## GSL-Solver Platform

**The Enterprise Route Optimization Portal**
Access the production-ready deterministic engine here:  
[**https://gsl-solver.com**](https://gsl-solver.com)

---

## Professional Contact

**Independent Researcher:** Chonmapoohm Thamsuwan (CTSuwan)  
**Email:** [ctsuwan@proton.me](mailto:ctsuwan@proton.me)  

---

## Services & Collaboration

Open to professional engagement in the following areas:

- **Logistics-as-a-Service (LaaS):** Real-time route optimization for enterprise fleets.
- **High-Precision Modeling:** Custom algorithmic solutions for complex supply chain constraints.
- **Technical Consultancy:** Large-scale network stress-testing and optimization audits.
- 

