# Gradient-free training of neural ODEs for system identification and control using ensemble Kalman inversion

This repository contains the code and materials related to the work on gradient-free training of neural ODEs.

Ensemble Kalman Inversion (EKI) is a gradient-free optimization method within a Bayesian framework, used to solve inverse problems. Unlike backpropagation, EKI does not require gradient computations and solely relies on forward passes through artificial neural networks. This study investigates the application of EKI for training neural ODEs in system identification and control tasks. To address optimal control problems, inverse problems are formulated with a Tikhonov-type regularization term. Numerical experiments demonstrate the efficiency of EKI in training neural ODEs, yielding competitive runtime and solution quality compared to commonly used gradient-based optimizers.

## Reference
*  L. Böttcher, Gradient-free training of neural ODEs for system identification and control using ensemble Kalman inversion, ICML Workshop on New Frontiers in Learning, Control, and Dynamical Systems at the International Conference on Machine Learning (ICML), Honolulu, Hawaii, USA (2023)

Please cite our work if you find the above implementations helpful for your own research projects.

```
@inproceedings{bottcher2023gradient,
  title={Gradient-free training of neural ODEs for system identification and control using ensemble Kalman inversion},
  author={B{\"o}ttcher, Lucas},
  booktitle={ICML Workshop on New Frontiers in Learning, Control, and Dynamical Systems},
  year={2023}
}
```
