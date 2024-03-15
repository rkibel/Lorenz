## The Lorenz Equations

The Lorenz equations concern a three-dimensional system of chaotic ODEs that help model fluid convective flow. The equations are as follows (LaTeX formatting):

$$\frac{dx}{dt} = \sigma(y-x)$$
$$\frac{dy}{dt} = x(\rho - z) - y$$
$$\frac{dz}{dt} = xy - \beta z$$

where sigma, rho, and beta are system parameters. The Lorenz system is an archetype of chaotic dynamics. 

In this repository, I conduct an analysis of the most common Lorenz problem using values sigma = 10, beta = 8/3, and rho = 28. The ODE approximation methods I use are Euler, Modified Euler, Runge Kutta 4th Order, Adams-Bashforth, and LSODA.