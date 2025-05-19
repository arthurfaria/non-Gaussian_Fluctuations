## FT for EP and steady state using a combined Gaussian and non-Gaussian stochastic dynamics

This is a repository provides codes in `Python` to compute:
* The steady-state of generalized quantum master equation due to Gaussian + non-Gaussian noises: overdamped DLD model [1].
* The fluctuation theorem for the Entropy production of a Brownian particle subject to a Gaussian and Poisson noises [2].

### Repository content

1. generalized_FP.ipynb
	- We show that in the overdamped regime the position distribution obeys a classical Kramers-Moyal equation that involves an infinite number of higher derivatives, implying that the finite bath correlation length leads to non-Gaussian Markovian noise. We analytically solve the equation for a harmonically bound particle and analyze its non-Gaussian diffusion as well as its steady-state properties. Algorithm based on finite diference approach to compute derivatives.

2. EP_FT_non-Gaussian_noise.ipynb
	- Detailed and integral fluctuation relations for the nonequilibrium entropy production of these Markov processes in the regime of weak noise. As an application, we analyze the properties of driven objects that are locally coupled to a heat bath via a finite-range interaction, by considering an overdamped particle that is pulled by a moving harmonic potential. Algorithm based on the numerical integration of stochastic dynamics.
	
References:

[1] https://arxiv.org/abs/2502.20174

[2] https://arxiv.org/abs/2502.20179
