# DNN Solution to Portfolio Selection with Serially-Dependent Returns

## Descriptions
* Put multi-period portfolio optimization problems into DNN and MDP framework.
* Compared CALs (Capital Allocation Line) results with those of single-period with and without constraints.

## Notes
* The computation cost is high in the neural network of CCC-GARCH case, and it approximately took 6 hours to get a CAL on my PC.
* The code of single-period with constraints case does not always guarantee satisfaction, which might be caused by some dependent libraries.

## Main Reference
* <a href='https://epubs.siam.org/doi/abs/10.1137/19M1274924' target='_blank'>https://epubs.siam.org/doi/abs/10.1137/19M1274924</a>
