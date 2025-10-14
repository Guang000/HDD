# HDD: Hyperbolic Dataset Distillation (NeurIPS 2025)
[![arXiv](https://img.shields.io/badge/arXiv-2505.24623-b31b1b.svg)](https://arxiv.org/abs/2505.24623)
[![Project Page](https://img.shields.io/badge/Project-Page-blue.svg)](https://arxiv.org/abs/2505.24623)

The first dataset distillation framework that leverages hyperbolic geometry to preserve hierarchical data structures.
HDD provides a geometric foundation for efficient, interpretable, and generalizable dataset distillation.

<p align="center">
  <img src="figure/overview.jpg" alt="Overview of HDD" width="600">
</p>

- Code and Project Page will be released soon (Before Dec 2025).
- Sept 2025: Our paper has been accepted to NeurIPS 2025!
- May 2025: Release preprint on arXiv.

## 🎯 Key Contributions

- Hyperbolic Geometry for Dataset Distillation
Introduces the first dataset distillation framework in hyperbolic space, enabling natural modeling of hierarchical data structures.

- Centroid Alignment via Geodesic Distance
Minimizes the Lorentzian hyperbolic distance between Fréchet means of real and synthetic datasets, ensuring semantic and geometric consistency.

- Hierarchical Sample Weighting
Derives analytic weighting that prioritizes prototype-like (root-level) samples while attenuating noisy, peripheral ones.

- Efficient Hierarchical Pruning
Demonstrates that only 20% of the original data is sufficient to maintain comparable accuracy, highlighting hyperbolic redundancy reduction.

- Broad Compatibility & Superior Results
Integrates smoothly with DM and IDM, yielding consistent gains in classification accuracy and training stability across diverse datasets.
