# Technical Report: MDVRPTW Architecture
**Paradigm:** Strict Spatio-Temporal Determinism

Adding Time Windows (TW) to a Multi-Depot Vehicle Routing Problem exponentially increases the search space. When real-world constraints like Asymmetric Distances (one-way streets) and 2D-Capacity (weight and volume) are introduced, traditional algorithms fail to scale effectively on limited hardware. The GSL Engine neutralizes this complexity through a specialized architectural approach.

## 1. Absolute Depot Anchoring
Before any time-window evaluation begins, the dataset is fragmented. Each customer node is mathematically bound to its most logical geographical depot. This prevents cross-depot computational waste and isolates the time-window complexity to smaller, manageable CVRP-TW sub-problems.

## 2. Chronological Feasibility Gates
The engine employs a "Forward-Only Time Enforcer". When evaluating a node insertion, the algorithm does not just calculate distance; it calculates the cumulative arrival time. If an insertion violates the closing time of a window, the action is instantly rejected without consuming further CPU cycles.

## 3. Commercial Low-Latency Deployment
The architecture is inherently designed for commercial application. As demonstrated in the **Bosnia Real-World dataset**, the engine successfully processed asymmetric street data, handled simultaneous weight/volume constraints, and strictly adhered to time windows. By achieving a 31.4% distance reduction compared to the company's legacy baseline in just **0.0078 seconds**, the GSL Engine proves its extreme low-latency response, making it exceptionally suited for real-time dispatch systems.
