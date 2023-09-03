In operator theory, convolution refers to a mathematical operation that combines two functions to produce a third function. It is denoted by the symbol "*" and is defined as follows:

Given two functions f and g, the convolution of f and g, denoted by f * g, is defined as the integral of the product of the two functions after one of them is flipped and shifted:

(f * g)(t) = ∫[f(τ)g(t - τ)] dτ

Here, t is a parameter that represents time in many applications. The integral sums up the products of the function values at each point, where one function is shifted with respect to the other.

Convolution has several important properties in operator theory. It is associative and commutative, meaning that (f * g) * h = f * (g * h) and f * g = g * f. It also has an identity element called the Dirac delta function δ(t), which satisfies δ(t) * f(t) = f(t).

Convolution plays a crucial role in various areas, such as signal processing, image processing, probability theory, and linear systems analysis. It allows for the transformation of signals or functions through linear time-invariant systems or operators.

# References

[[@3blue1brownWhatConvolution2022]]

[[@3blue1brownConvolutionsWhyProbability2023]]