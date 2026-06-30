# Chapter 46: Motion Estimation

This chapter notebook lives in [index.ipynb](./index.ipynb).

It is designed as a beginner-friendly walkthrough of motion estimation with:

- synthetic frame pairs with known ground-truth translation,
- readable SSD-based patch matching,
- single-point and sparse-field motion demos,
- quantitative validation with endpoint error and match ratios,
- parameter sweeps for patch size, search radius, and noise,
- failure-case illustrations for repetitive texture and oversized motion.

Local assets for the explanatory figures are stored in [`assets/`](./assets/).

The notebook code assumes a standard scientific Python environment with `numpy` and `matplotlib`.
