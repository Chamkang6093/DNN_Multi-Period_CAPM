# DNN Solution to Portfolio Selection with Serially-Dependent Returns

## Descriptions
* Put multi-period portfolio optimization problems into DNN and MDP framework.
* Compared CALs (Capital Allocation Line) results with those of single-period with and without constraints.

## Abstract
* Many mathematical finance problems have been recently solved using deep learning a nd m achine learning, such as prediction with limit-order information (Sirignano, 2019), analysis of least-squares Monte Carlo method for American option pricing (Zanger, 2018), stochastic control problems (Bachouch et al., 2021) and Portfolio Optimization (Ban et al., 2018).
* Tsang and Wong (2020) aims to propose a deep neutral network (DNN) architecture and numerical algorithm for multi-period portfolio optimization. Their deep learning solution is complementary to the literature as mentioned earlier by relaxing regularity conditions on the objective function and allowing for popular econometric models.
* Practical portfolio selection has to overcome the challenges arising from high-dimensionality, flexible modeling for risky asset returns and investment constraints. The literature has great success in developing theoretical results for models with serially-independent asset returns (Li and Ng, 2000).
* Tsang and Wong (2020) focuse on two classes of well-known time series models: autoregressive (AR) and the generalized autoregressive conditional heteroskedasticity (GARCH) models. The former describes serial-dependence through the drift terms of risky asset returns while the latter through the innovation terms. Their goal is to solve the high-dimensional multi-period portfolio problem in discrete time subject to the bounding constraints on the control.
* In our report, the main content includes the following:
  * Introduce the problem formulation and notations of feedforward neural network.
  * Details of the deep neutral network architecture for portfolio optimization.
  * Provide the numerical and empirical examples with their deep neutral network framework for a high-dimensional portfolio.

## Notes
* The computation cost is high in the neural network of CCC-GARCH case, and it approximately took 6 hours to get a CAL on my PC.
* The code of single-period with constraints case does not always guarantee satisfaction, which might be caused by some dependent libraries.

## Main Reference
* <a href='https://epubs.siam.org/doi/abs/10.1137/19M1274924' target='_blank'>https://epubs.siam.org/doi/abs/10.1137/19M1274924</a>
