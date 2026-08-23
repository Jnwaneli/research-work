# Research Work

Research materials and manuscript drafts from my work in computer engineering and machine learning.

## Deep Mixture Density Networks for Wireless Channel Modeling

**Manuscript:** *Evaluating Distance-Range Compression and Robustness of Deep Mixture Density Networks for Wireless Channel Modeling*

**Authors:** Joshua Nwaneli, Micah Josiah Devaraj, Youngmin Lee, and Xiaomin Ma  
**Institution:** College of Science and Engineering, Oral Roberts University

This work evaluates Deep Mixture Density Networks (DMDNs) for probabilistic wireless-channel modeling under synthetic Nakagami-m fading. The study compares a full 10–300 m distance range with a compressed 297–303 m critical region and evaluates robustness as path-loss exponent and Gaussian-noise variance are jointly increased.

### Key results

- Reduced the modeled distance domain from **30 categories over 10–300 m** to **7 categories over 297–303 m**.
- Reduced observed training time from approximately **22 minutes to 2 minutes per run** in the tested Google Colab CPU environment, an approximately **90% reduction**.
- Achieved aggregate **OA = 0.982** for the compressed configuration compared with **OA = 0.971** for the full-range baseline.
- Successful robustness configurations produced OA values from **0.965 to 0.982**.
- Numerical instability was observed at the most severe tested configuration, **α = 2.9, vN = 0.17**.

### Tools and methods

Python · TensorFlow · Keras · Linux · SLURM · High-Performance Computing · Deep Learning · Mixture Density Networks · Kernel Density Estimation · Wireless Channel Modeling

## Manuscript file

The current manuscript draft is available in [`papers/`](papers/).

> **Status:** Research manuscript / current draft. This repository is intended to document the work and should not be interpreted as a publication record.
