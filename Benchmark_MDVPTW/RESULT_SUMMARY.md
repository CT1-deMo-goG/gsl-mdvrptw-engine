# GSL Engine: MDVRPTW Result Summary
**Core Module:** `GSL_MDVRPTW_V38` & `GSL_MDVRPTW_REAL_V29`

## 1. Real-World Commercial Application (Bosnia Dataset)
Proof of Concept for commercial deployment using actual asymmetric map coordinates, 2D capacity, and strict time windows.

* **Baseline (Company's Actual Routing):** 537.43 KM
* **GSL Engine Cost:** **368.35 KM**
* **Distance Saved:** 169.08 KM **(31.4% Improvement)**
* **Execution Time:** 0.0078 seconds
* **Fleet Deployed:** 7 Vehicles
* **Verification:** ✅ 100% Verified (Demand/2D-Capacity/Time-Windows/Asymmetric Routes)

## 2. Standard Cordeau Benchmark Performance
Evaluated against the standard academic MDVRPTW instances.

| Instance | Nodes | GSL Cost | Gap vs BKS (%) | Verification | Time (s) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| pr01 | 48 | 1120.88 | +3.40% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.037s |
| pr02 | 96 | 1808.43 | +2.57% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.108s |
| pr03 | 144 | 2669.05 | +10.82% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.199s |
| pr04 | 192 | 2984.56 | +0.89% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.469s |
| pr05 | 240 | 3441.44 | +9.81% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.730s |
| pr06 | 288 | 3946.04 | +1.08% | ✅ Verified (Nodes/Cap/TW/Depot) | 1.099s |
| pr07 | 72 | 1436.59 | +0.93% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.033s |
| pr08 | 144 | 2131.02 | -0.89% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.154s |
| pr09 | 216 | 2998.68 | +5.82% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.320s |
| pr10 | 288 | 3763.33 | +1.24% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.892s |
| pr11 | 48 | 967.98 | -6.16% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.017s |
| pr12 | 96 | 1638.08 | +9.17% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.131s |
| pr13 | 144 | 2308.49 | +14.25% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.252s |
| pr14 | 192 | 2779.85 | +23.67% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.530s |
| pr15 | 240 | 3001.72 | +19.60% | ✅ Verified (Nodes/Cap/TW/Depot) | 1.055s |
| pr16 | 288 | 3429.78 | +16.50% | ✅ Verified (Nodes/Cap/TW/Depot) | 1.177s |
| pr17 | 72 | 1314.41 | +5.14% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.031s |
| pr18 | 144 | 1951.11 | +7.83% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.159s |
| pr19 | 216 | 2900.23 | +25.50% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.369s |
| pr20 | 288 | 3366.98 | +7.51% | ✅ Verified (Nodes/Cap/TW/Depot) | 0.745s |

## 3. Vidal Large-Scale Benchmark (2013)
*Note: Due to the lack of unified BKS for this specific dataset variant, these results establish the GSL Mobile Execution Baseline.*

| Instance | Nodes | GSL Cost | Gap vs BKS (%) | Verification | Time (s) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| pr11a | 360 | 8463.73 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 1.672s |
| pr11b | 360 | 6067.23 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 2.325s |
| pr12a | 480 | 10169.22 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 2.965s |
| pr12b | 480 | 7622.15 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 4.309s |
| pr13a | 600 | 11816.16 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 4.835s |
| pr13b | 600 | 9058.30 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 6.774s |
| pr14a | 720 | 14150.10 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 6.656s |
| pr14b | 720 | 10531.78 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 10.033s |
| pr15a | 840 | 16180.39 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 9.436s |
| pr15b | 840 | 11769.73 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 14.162s |
| pr16a | 960 | 18635.75 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 12.540s |
| pr16b | 960 | 13535.32 | N/A (Baseline) | ✅ Verified (Nodes/Cap/TW/Depot) | 19.084s |
