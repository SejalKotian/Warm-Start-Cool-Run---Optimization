# Warm-Start-Cool-Run---Optimization
Hybrid Stochastic Gradient Hamiltonian Monte Carlo and Momentum Annealing Framework for Wide Minima Optimization
Experiments on wide vs sharp minima in deep neural network optimization

Dataset/model: FashionMNIST with a 2-layer MLP

Compare optimizers: SGD, SGD + Momentum, CoolMomentum, SGHMC, and Hybrid (SGHMC → CoolMomentum)

Study how stochastic exploration + annealed momentum affect convergence and generalization

Includes scripts for training, checkpointing, and test error vs iteration plots(will be added soon)

Explores multi-phase strategies for targeting wide, flat minima (explore with SGHMC, refine with CoolMomentum)
