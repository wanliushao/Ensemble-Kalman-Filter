# Ensemble-Kalman-Filter
Dual state-parameter estimation in an ecosystem biogeochemical models using the Ensemble Kalman Filter.
The program aims at addressing the parameter temporal variability (maybe future spatial variability) in physical process based models.
We also incorporated the parameter stochastic properties (AR1) to improve model robustness.
This program uses the MPI procedure to accerlate the computation speed.
Maybe future we can try particle filter to constrain posterior parameter distribution, since Ensemble Kalman Filter is based on the assumption that model errors are from normal distribution.

