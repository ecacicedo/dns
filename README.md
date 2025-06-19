# DNS
Python implementation of the Dynamic Nelson-Siegel (Diebol & Li, 2006) term structure model.

Three different variations of the model are presented:

1. The original application in two steps with OLS for yields dynamic and AR(1) for latent factors dynamic.

2. The yield and latent factor dynamics is estimated with a Kalman Filter.

3. An OLS for yields dynamic and VAR(1) with Metropolis-Hastings for latent factors dynamic.
