---
title: Sigmoid Function
---
What is the sigmoid function?
<!--question-->
A sigmoid function is a mathematical function having a characteristic "S"-shaped curve or sigmoid curve. Also called the "Logistic Function".
$$$
\theta (x) = g ( \theta^T x ) \\ 
z = \theta^T x \\
g(z) = \frac{1}{1 + e^{-z}} = \frac{e^x}{e^x + 1}
$$$
![Image of sigmoid function](images/640px-Logistic-curve.svg.png)
The function g(z), shown here, maps any real number to the (0, 1) interval, making it useful for transforming an arbitrary-valued function into a function better suited for classification.
