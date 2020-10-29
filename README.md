# Calculating the Probability of Kepler-452b as a Rocky Planet in the Habitable Zone

Kepler-452b was announced as a super-Earth exoplanet in 2015. It became the first potentially rocky Earth-like world to be found orbiting within the habitable
zone of a Sun-like star.

This project shows that it is highly probable that Kepler-452b is indeed a rocky, habitable-zone planet. 
I assume the small planet approximation and circular orbit. I fix some of the transit and orbital parameters, including inclination, transit
duration, and orbital period, with the literature values (Jenkins et al. 2015)
when modeling the data. I generate samples for planetary radius and equilibrium temperature by using a Markov Chain Monte Carlo (MCMC) algorithm
and using an independent set of stellar posterior sample for stellar radius and
effective temperature. For my purposes here, I consider the planet to be in the habitable zone if its
equilibrium temperature is within the habitable zone temperature limits of 207.5
K and 320.4 K, and I consider the planet to be rocky if its radius is below
the rocky-gas divide (1.23 earth-radii).
