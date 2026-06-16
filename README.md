# Ramanujan Graph Rewiring with Non-Negative Resistance Curvature

**Hugo Attali, Rachid El Jouhri** — ECML PKDD 2026

Official implementation of **RNRP** (Ramanujan with Non-negative Resistance curvature Propagation), a graph rewiring strategy that leverages Ramanujan graphs to mitigate over-squashing in GNNs.

## Installation

```bash
pip install torch torch_geometric networkx scipy numpy matplotlib sympy
```

## Usage

Run `ECML_PKDD_2026_Ramanujan_propagation.ipynb`. The degree $d = \lceil 4(\log N)^{2/3} \rceil$ is set automatically from the graph size.

