# Sequential-analysis-codes
This is supplementary code for our paper, "Sequential analysis and its applications to neuromorphic engineering" (2025).
Authors: Shivaram Mani, Saeed Afshar and Travis Monk, ICNS, Western Sydney University.

The code released here focuses on:
  1. The core sequential-analysis algorithms
  2. Simulation routines for threshold-crossing dynamics
  3. Characteristic-function (CCF) computation
  4. Root-continuation solvers used in the theoretical predictions

The implementation is intentionally lightweight (NumPy + SciPy only) so that readers can experiment and adapt the algorithms for their own neuromorphic systems.

Reproducibility: All random-number generation uses NumPy’s default RNG.

Citation:
If you use this code, please cite the original paper.
