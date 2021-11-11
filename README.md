# Undergraduate-project-Effect-of-Kernel-function

### Description
Effect of kernel functions on the accuracy of a linear model (A case study of the USD/GHS exchange rate price)


### Abstract
According to literature, the performance of a machine learning model depends mostly on parameter tuning. In a linear model such as support vector regres- sion, a good choice of kernel function is appropriate for the accuracy of the model. In this project we investigate the effect of three kernel functions of SVR i.e. “Linear kernel”, “Polynomial kernel” and the “Radial basis func- tion kernel” on the accuracy of exchange rate prices of the US dollar against the Ghana cedis. The results show a close Mean Square Error(MSE) in all the three kernels. Based on the results, the accuracy of the model improves when the choice of kernel is radial basis function. The effect of regularization param- eter C and epsilon is also investigated. The conclusion made was that, although kernel functions has an effect on the accuracy of the model, the choice of kernel should be chosen based on the behaviour of the dataset.

### Objective
The main objective of this project is to investigate the effect of kernel functions of support vector machine on the USD/GHS exchange rate.
The specific objectives are as follows:
  1. To investigate the variation of performance with respect to regularization
parameter C.
  2. To investigate the variation of performance with respect to the epsilon
parameter.

### Files Used
The data for this research contain daily exchange rates of the US dollar from January 2014 to April 2020. The data https://www.m.investing.com/currencies.

### Tools & Softwares Needed
 * Python
 * Numpy
 * Pandas
 * Matplotlib
 * Seaborn
 * Jupyter Notebook

### Conclusion
In this project we investigated the effect of kernel functions, the reguralization parameter, and epsilon on the accuracy of a linear-based model which is the support vector regression. The results show a close error(MAE, MSE, RMSE) of the linear, polynomial and radial basis function kernel. In all, the radial ba- sis function appeared to be the kernel with the least error. We conclude that although kernel functions have effect on the accuracy of the model, kernel func- tion should be chosen based on the behaviour of the dataset. The performance of the model is also affected by the choice of regularization parameter C and ε. The model produce high accuracy when C and ε are choosen as 100 and 0.01 respectively.
