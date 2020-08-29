* Repository github url : https://github.com/jai-mr/
* Assignment Repository : https://github.com/jai-mr/Assignment-6
* Submitted by : Jaideep Rangnekar
* Registered email id : jaideepmr@gmail.com

The model has been executed for 25 epochs for each of the following 5 scenarios :

1. with L1 + BN
2. with L2 + BN
3. with L1 and L2 with BN
4. with GBN
5. with L1 and L2 with GBN


# Jupyter Notebook File reference executed in Colab
[https://github.com/jai-mr/Assignment-6/blob/master/06_CodeFinal.ipynb](https://github.com/jai-mr/Assignment-6/blob/master/06_CodeFinal.ipynb)

# Validation Accuracy Curves
[https://github.com/jai-mr/Assignment-6/blob/master/images/testaccuracy.png](https://github.com/jai-mr/Assignment-6/blob/master/images/testaccuracy.png)

# Loss Change Curves
[https://github.com/jai-mr/Assignment-6/blob/master/images/validationloss.png](https://github.com/jai-mr/Assignment-6/blob/master/images/validationloss.png)

# The Mis-Classified Images for "With GBN" model

* NoL1_NoL2 with GhostBN

[https://github.com/jai-mr/Assignment-6/blob/master/images/NoL1_NoL2withGhostBN.png](https://github.com/jai-mr/Assignment-6/blob/master/images/NoL1_NoL2withGhostBN.png)

* WithL1_WithL2 with GhostBN

[https://github.com/jai-mr/Assignment-6/blob/master/images/WithL1_WithL2withGhostBN.png](https://github.com/jai-mr/Assignment-6/blob/master/images/WithL1_WithL2withGhostBN.png)

# Max Test Accuracy
* WithL1_NoL2 with BN       :  99.42
* NoL1_WithL2 with BN       :  99.41
* WithL1_WithL2 with BN     :  99.53
* NoL1_NoL2 with GhostBN    :  99.45
* WithL1_WithL2 with GhostBN:  99.41
* The overall max accuracy 99.53 is for WithL1_WithL2 with BN

## L1 & L2 performance in the regularization of your model.
## L1 Regularization(Lasso Regression)
* L1 penalizes the sum of the absolute value of weights.
* L1 has a sparse solution
* L1 generates a model that is simple and interpretable but cannot learn complex patterns
* L1 is robust to outliers

## L2 Regularization(Ridge regularization):
* L2 regularization penalizes the sum of square weights.
* L2 has a non-sparse solution
* L2 regularization is able to learn complex data patterns
* L2 has no feature selection
* L2 is not robust to outliers

* From a practical standpoint, L1 tends to shrink coefficients to zero whereas L2 tends to shrink coefficients evenly. 
* L1 is therefore useful for feature selection, as we can drop any variables associated with coefficients that go to zero. L2, on the other hand, is useful when you have collinear/codependent features


References:

[ https://explained.ai/regularization/L1vsL2.html#:~:text=From%20a%20practical%20standpoint%2C%20L1,you%20have%20collinear%2Fcodependent%20features]( https://explained.ai/regularization/L1vsL2.html#:~:text=From%20a%20practical%20standpoint%2C%20L1,you%20have%20collinear%2Fcodependent%20features)

[https://explained.ai/regularization/L1vsL2.html](https://explained.ai/regularization/L1vsL2.html)

