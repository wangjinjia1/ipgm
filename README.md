# ipgm
Inertial proximal gradient method  for convolutional dictionary learning
Inspired by the recent success of the proximal gradient method (PGM) with inertial forces and recent efforts to develop a nonconvex optimization-based learning method, we propose an iner-tial PGM (IPGM) for nonconvex convolutional dictionary learning (CDL) by jointly optimizing both an  -norm fidelity term and a sparsity term that enforces an l0 penalty. Contrary to other convex CDL methods, in the proposed approach, the dictionary and needles are updated with an inertial force by the PGM. We obtain a novel derivative formula for the needles and dictionary with respect to the fidelity term in our approach. At the same time, a gradient descent step is designed to add an inertial term. The proximal operation uses hard thresholding for needles and maps the dictionary to a nonconvex unit-norm sphere. We prove the convergence property of the proposed nonconvex algorithm in a backtracking case. Simulation results show that the proposed IPGM achieves better performance than the PGM and slice-based methods that possess the same structure and are optimized using the alternating-direction method of multipliers (ADMM).
