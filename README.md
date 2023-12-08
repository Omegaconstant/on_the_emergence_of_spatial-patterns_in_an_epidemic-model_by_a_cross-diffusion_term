### On the emergence of spatial-patterns in an epidemic-model by a cross-diffusion term

<hr/>

We present a numerical analysis of a two-dimensional epidemic model featuring a nonlinear cross-diffusion term, capturing the spatial dynamics of susceptible and infected populations as discussed in [Berres and Ruiz-Baier, 2011](https://doi.org/10.1016/j.nonrwa.2011.04.014) and [Berres and Gonzalez-Marin, 2013](https://www.conferenceproceedings.com/abstract/20th-international-congress-on-modelling-and-simulation-0). 

The model incorporates non-linear self-diffusion and cross-diffusion terms to represent psychological and sociological responses of the population to the disease<sup>[1](#footnote1)</sup>. Utilizing a finite element method, we discretize the reaction-diffusion system and simulate both forward and backward Eulerian schemes. For the nonlinear systems, we simulate it through both Picard's iteration and the Newton-Raphson method.

A comprehensive analysis of the model was conducted to study the influence of different model parameters such as birth rate, carrying capacity, rate of disease transmission, recovery rate, etc. Our observations also highlight that nonlinear cross-diffusion results in the emergence of complex spatial structures, such as stripes, spots, and holes, influenced by initial conditions.

Additionally, we analyze the stability and convergence of the numerical scheme both in time and in space, providing relevant error estimates.

## References

- Stefan Berres and Ricardo Ruiz-Baier. "A fully adaptive numerical approximation for a two-dimensional epidemic model with nonlinear cross-diffusion." *Nonlinear Analysis: Real World Applications* 12.5 (2011): 2888-2903. [DOI: 10.1016/j.nonrwa.2011.04.014](https://doi.org/10.1016/j.nonrwa.2011.04.014)

- Stefan Berres and J. Gonzalez-Marin. "On epidemic models with nonlinear cross-diffusion." In *20th International Congress on Modelling and Simulation*, 2013. [Conference Proceedings](https://www.conferenceproceedings.com/abstract/20th-international-congress-on-modelling-and-simulation-0)

<hr/>

<span id="footnote1">1: There are two models. In the first one, the diffusion terms are independent of primary variables (essentially linear) and in model 2, the diffusion terms are non-linear.</span>
