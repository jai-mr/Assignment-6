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
