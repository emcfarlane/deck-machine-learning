---
title: Normal Equation
---
What is the "Normal Equation" method?
<!--question-->
We minimize $J$ by explicitly taking its derivatives with respect to the $θ_j$’s, and setting them to zero.
$$$
\theta = (X^TX)^{-1}X^Ty
$$$
With the normal equation, computing the inversion has complexity $\mathcal{O}(n^3)$. So if we have a very large number of features, the normal equation will be slow. In practice, when n exceeds 10,000 it might be a good time to go from a normal solution to an iterative process.

