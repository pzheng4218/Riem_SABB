# Riem_SABB
The official implement code of 《A Riemannian simulated annealing-based Barzilai-Borwein gradient method for manifold optimization》


#Abstract
We propose a novel Riemannian simulated annealing-based Barzilai-Borwein (RSABB) gradient method for optimization on manifolds. This hybrid approach combines the Barzilai-Borwein (BB) gradient method with a simulated annealing (SA) rule, tailored for optimization problems on the Stiefel manifold. The BB step size we utilize possesses a two-dimensional quadratic termination property. The proposed RSABB gradient method accepts the BB step according to simulated annealing rule, resulting in a new nonmonotone line search technique. If the BB step is not accepted, an Armijo line search is employed instead. Under some mild assumptions based on the geometric structural characteristics of the manifold, the global convergence analysis of the RSABB gradient method is established. Furthermore, the RSABB gradient method can be extended to other manifolds provided certain metrics are met.
Experimental results indicate that, the proposed algorithm is highly competitive in terms of computational performance on specific problems and outperforms several existing algorithms.
