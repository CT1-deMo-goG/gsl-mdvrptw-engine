# Benchmark Methodology: MDVRPTW
**Core Module:** `GSL_MDVRPTW_V38`

## 1. Execution Environment
To demonstrate absolute algorithmic efficiency, all benchmarks were executed on highly constrained hardware rather than high-performance servers.
* **Platform:** Android Mobile Device
* **CPU:** Snapdragon Architecture
* **Interpreter:** Python via Pydroid 3

## 2. Zero-Tuning Policy
The GSL Engine operates under a strict "Zero-Tuning Policy". While separate architectural modules are deployed based on problem class (V38 for standard symmetric instances, V29 for asymmetric 2D-capacity real-world instances), no instance-specific parameter tuning is performed within any module.

## 3. Strict Verification Protocol
Every output is subjected to a deterministic verification layer. A solution is only considered feasible if it achieves 100% compliance across all constraints:
* **Node Integrity:** All customers must be visited exactly once.
* **Depot Consistency:** Vehicles must return to their exact origin depot.
* **Capacity (2D):** Combined weight and volume must not exceed fleet limits.
* **Chronological Validity:** Arrival times must strictly adhere to predefined Time Windows.
* **Asymmetric Routing:** Directional distance variations (e.g., one-way streets) are strictly enforced in real-world scenarios.
* 
