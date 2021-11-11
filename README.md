# Undergraduate-project-Effect-of-Kernel-function

### Description
Effect of kernel functions on the accuracy of a linear model (A case study of the USD/GHS exchange rate price)


### Abstract
Moving average indicators serve as one of the most commonly used input feature for modeling financial time
series problems. In the world of machine learning, the choice of moving average used as feature engineer 
can improve your prediction accuracy. Aside from these indicators, other parameters of a model can also
affect the accuracy of your prediction. In support vector regression, the choice of kernel,
the value of the hyperparameter C and epsilon(ε) can determine the accuracy of your predic- tion.
With all these variables contributing to the increase or decrease of prediction accuracy, 
this paper tend to investigate the effect of tuning parameter of support vector regression on three 
different moving average namely simple, exponential and weighted moving average. 
The result obtained indicated that some moving average increases their prediction rate as C increases
and vice versa. The prediction accuracy depending on the value of epsilon(ε) increases with respect
to the kernel type and vice versa. Among all three moving average, exponential moving average emerge 
as the best feature engineering for the data.

### Files Used
The data for this research contain daily exchange rates of the Ghana cedis to the US dollar from January 2014 
to April 2020. The data was obtained from https://www.m.investing.com/currencies. In general 1641 daily
exchange rate was considered.

### Conclusion
Among the three moving average used, the exponential moving average perform best with a high accuracy of 
0.967793 when the kernel is rbf, the choice of C = 1000 and epislon(ε = 0.01). The radial basis perform 
well when C is large, this we observed might be due to the value of the gamma. Although we can be certain 
that exponential moving average is a good feature engineering, we cannot be certain with the choice of the
hyparameter, whether setting the parameters to 1 or 10 will improve the accuracy, but researchers are
advice to try different parameters for better prediction.
