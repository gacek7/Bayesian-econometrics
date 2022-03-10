# The program works similar to MCMCpack (Markov Chain Monte Carlo Package). Gibbs Sampling.
Contains functions to perform Bayesian inference using posterior simulation for a number of statistical models. Code allows: 
* load a set of data (you have to set y and X matrices; code works for any number of explanatory variables) - from an xlsx or csv file 
* determine any number of burn-in cycles (i.e. initial draws) and proper sample cycles determining any values of hyperparameters setting any starting point for Gibbs algorithm
* dump of estimation results graphs to pdf files
