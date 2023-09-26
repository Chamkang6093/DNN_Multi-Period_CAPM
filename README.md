# DNN Solution to Portfolio Selection with Serially-Dependent Returns

## Descriptions
* <font face='Times New Roman'>Put different multi-period portfolio optimization problems into the DNN framework to get the numerical solutions.</font>
* <font face='Times New Roman'>Compared the results of CALs (Capital Allocation Line) with those of single-period with and without constraints.</font>

## Notes
* The computation cost is high in the neural network of CCC-GARCH case, and it approximately takes 6 hours to get a CAL on my PC.
* The code of single-period with constraints case does not always guarantee satisfaction, which may be caused by some dependent libraries.

## Main Reference
* <a style='color: black;' href='https://epubs.siam.org/doi/abs/10.1137/19M1274924' target='_blank'>https://epubs.siam.org/doi/abs/10.1137/19M1274924</a>
