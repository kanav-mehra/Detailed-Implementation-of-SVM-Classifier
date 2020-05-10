# Detailed Implementation of SVM Classifier

Although a support vector machine model (binary classifier) is more commonly built by solving a quadratic programming problem in the dual space, it can be built fast by solving the primal optimization problem also. In this repo a Support Vector Machine implementation is described by solving the primal optimization problem with sub-gradient solver using batch gradient decent. The algorithm is called the Pegasos algorithm, as described by Shai Shalev-Shwartz et al, in their original [paper](https://www.cse.huji.ac.il/~shais/papers/ShalevSiSrCo10.pdf).

Covers:

* SVM implementation by minimizing the primal objective with hinge-loss using gradient descent with PEGASOS
* Visualization of data, decision boundary (Hyperplane) and hinge-loss function using Matplotlib
* Exploring and visualizing the effect of penalty parameter - C on the decision boundary
* Classification of linearly in-separable data using Kernel Trick and visualizing the Decision Boundary in 3D
