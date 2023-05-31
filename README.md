# Monte-Carlo-Integration

Monte Carlo integration is a technique for numerical integration using random numbers and the Sampling method here is called Uniform Sampling. \
It is a particular Monte Carlo method that numerically computes a definite integral. \
While other algorithms usually evaluate the integrand at a regular grid, Monte Carlo randomly chooses points at which the integrand is evaluated and this method is particularly useful for higher-dimensional integrals.


### Note that the accuracy of the estimate improves as the value of  n increases.

There are different methods to perform a Monte Carlo integration, such as uniform sampling
Here we have computed the Integral of the function  $e^{x} cos(x)$


You can modify this integrad using this function and find the integral of any other funnction

```python
def integrand(x):
    return np.exp(x) * np.cos(x)
```
