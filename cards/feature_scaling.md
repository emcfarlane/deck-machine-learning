---
title: Feature Scaling
---
What is feature scaling and why is it used?
<!--question-->
Feature scaling is a method used to normalize the range of independent variables or features of data.

We can speed up gradient descent by having each of our input values in roughly the same range. This is because θ will descend quickly on small ranges and slowly on large ranges, and so will oscillate inefficiently down to the optimum when the variables are very uneven.

### Methods

#### Rescaling (min-max normalization)
Also known as min-max scaling or min-max normalization, is the simplest method and consists in rescaling the range of features to scale the range in [0, 1] or [−1, 1]. 
$$$
x' = \frac{x - min(x)}{max(x) - min(x)}
$$$

#### Mean normalization
$$$
x' = \frac{x - average(x)}{max(x) - min(x)}
$$$
where $x$ is an original value,  $x'$ is the normalized value. There is another form of the means normalization which is when we divide by the standard deviation which is also called standardization.

#### Standardization  (Z-score Normalization)
In machine learning, we can handle various types of data, e.g. audio signals and pixel values for image data, and this data can include multiple dimensions. Feature standardization makes the values of each feature in the data have zero-mean (when subtracting the mean in the numerator) and unit-variance. This method is widely used for normalization in many machine learning algorithms.
$$$
x' = \frac{x - \bar{x}}{\sigma}
$$$

#### Scaling to unit length
Widely used in machine-learning is to scale the components of a feature vector such that the complete vector has length one. This usually means dividing each component by the Euclidean length of the vector:
$$$
x' = \frac{x}{||x||}
$$$
