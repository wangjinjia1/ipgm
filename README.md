# ipgm
Inertial proximal gradient method  for convolutional dictionary learning
Inspired by the recent success of the proximal gradient method (PGM) with inertial forces and recent efforts to develop a nonconvex optimization-based learning method, we propose an iner-tial PGM (IPGM) for nonconvex convolutional dictionary learning (CDL) by jointly optimizing both an l2-norm fidelity term and a l1 or l0-sparsity term. Contrary to other convex CDL methods, in the proposed approach, the dictionary and needles are updated with an inertial force by the PGM. Simulation results show that the proposed IPGM achieves better performance than the PGM and slice-based methods that possess the same structure and are optimized using the alternating-direction method of multipliers (ADMM).
ipiano凸优化实验结果.zip include the experiments results of IPGM for convex convolutional dictionary learning (CDL).
ipiano非凸优化实验结果.zip include the experiments results of IPGM for nonconvex convolutional dictionary learning (CDL).
