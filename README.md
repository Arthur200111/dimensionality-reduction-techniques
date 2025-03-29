# Dimensionality Reduction Techniques : Kernel PCA, NMF, and SNE/t-SNE

This repository contains Python implementations of several dimensionality reduction algorithms:
- **Kernel PCA (kpca.ipynb)**: Implementation of the Kernel Principal Component Analysis (KPCA) algorithm.
- **NMF (NMF.ipynb)**: Implementation of three Non-negative Matrix Factorization (NMF) methods:
  - Multiplicative update method
  - Alternating Least Squares method
  - Gradient descent method
- **SNE and t-SNE (sne.ipynb)**:
  - Implementation and testing of the Stochastic Neighbor Embedding (SNE) and t-Distributed Stochastic Neighbor Embedding (t-SNE) algorithms.
  - Experiments on two datasets:
    - Gaussian Mixtures
    - digits from sklearn.datasets
  - Implementation and comparison of various gradient descent acceleration methods:
    - Momentum
    - Nesterov
    - AdaGrad
    - RMSprop
    - Adam

## Requirements

This project requires **Python 3.12.4** and the following libraries:

- `matplotlib` (3.8.4)
- `numpy` (1.26.4)
- `scipy` (1.13.1)
- `scikit-learn` (1.4.2)

You can install these dependencies using:

```bash
pip install matplotlib==3.8.4 numpy==1.26.4 scipy==1.13.1 scikit-learn==1.4.2
```
