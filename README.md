# HDD: Hyperbolic Dataset Distillation (NeurIPS 2025)
[![arXiv](https://img.shields.io/badge/arXiv-2505.24623-b31b1b.svg)](https://arxiv.org/abs/2505.24623)
[![Project Page](https://img.shields.io/badge/Project-Page-blue.svg)](https://arxiv.org/abs/2505.24623)

The first dataset distillation framework that leverages hyperbolic geometry to preserve hierarchical data structures.
HDD provides a geometric foundation for efficient, interpretable, and generalizable dataset distillation.

<p align="center">
  <img src="figure/overview.jpg" alt="Overview of HDD" width="600">
</p>

- Code and Project Page will be released soon.
- Sept 2025: Our paper has been accepted to NeurIPS 2025!
- May 2025: Release preprint on arXiv.

<!-- ## 📖 Project Overview

Dataset Distillation aims to synthesize a compact dataset that retains the performance of the original large-scale data.
However, conventional Euclidean-based methods overlook the hierarchical and geometric nature of real-world data, treating all samples as independent points.

HDD (Hyperbolic Dataset Distillation) introduces Lorentz hyperbolic space to explicitly model these hierarchical structures.
By aligning the Fréchet means (centroids) of real and synthetic datasets via geodesic distance minimization, HDD captures both global semantics and prototype-level representations, enhancing information fidelity while reducing noise.

This geometric formulation enables hierarchical sample weighting and efficient pruning—retaining as little as 20% of the original data without significant performance degradation.

HDD integrates seamlessly with state-of-the-art distribution matching methods (DM, IDM, Dance), consistently improving accuracy, stability, and cross-architecture generalization across benchmarks such as Fashion-MNIST, SVHN, CIFAR-10/100, and TinyImageNet. -->

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
Integrates smoothly with DM, IDM, and Dance, yielding consistent gains in classification accuracy and training stability across diverse datasets.
