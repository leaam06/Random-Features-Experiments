# Random Features Experiments

This repository contains a notebook exploring the methods proposed in the paper *Random Features for Large-Scale Kernel Machines*.

## Description

Kernel machines, such as SVMs, are powerful but computationally expensive. This paper introduces an approach based on random projections to approximate kernels while accelerating training.

This project implements and tests these methods:

- **Fourier Features** : Uses sine and cosine functions to approximate RBF kernels.
- **Random Binning Features** : Randomly discretizes the space to approximate kernels based on the L1 distance.

## Contents

- `notebook.ipynb` : Experiments on random feature methods.
- `data/` : Contains potential data files.
- `results/` : Stores test results and visualizations.

## Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/leaam06/Random-Features-Experiments
   cd Random-Features-Experiments
