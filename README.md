# braintorch

Implementation of the spectral graph model (SGM) in PyTorch and demonstration of slow-fast dynamics with ODE with SGM+Goodwin model. 

## Setup

### 1. Install Dependencies

1. install requirements:
`pip install -r requirements.txt`

2. for comparing to original SGM implementation, install original [spectrome](https://github.com/Raj-Lab-UCSF/spectrome)

## Contents

### Notebooks
- **braintorch_refractored_20240808.ipynb**: Compares NumPy and PyTorch implementations of the SGM.

- **20240430_torchdiffeq-v6b-Goodwin-Adjoint-burstSuppression_v20240430_updated20240808.ipynb**: Demonstrates SGM ODE system in modeling burst suppression. It uses TorchDiffEq and the Goodwin model as a foundation.

## Citation
Code citation: TBA
