# Efficient estimation of the number of false positives in high-throughput screening 

## Abstract
This paper develops new methods to handle false positives in High-Throughput Screening experiments. The setting is very highly multiple testing problems where testing is done at extreme significance levels and with low degrees of freedom, and where the true null distribution may differ from the theoretical one. We answer the question 'How many of the positive test results are false?' by showing that the conditional distribution of the number of false positives, given that there is in all r positives, approximately has a binomial distribution, and find efficient estimators for its success probability parameter. Furthermore we provide efficient methods for estimation of the true null distribution resulting from a preprocessing method, and techniques to compare it with the theoretical null distribution. Analysis is based on a simple polynomial model for the tail of the distribution of p-values. We provide asymptotics which motivate this model, exhibit properties of estimators of the parameters of the model, and point to model checking tools. The methods are tried out on two large genomic studies and on an fMRI brain scan experiment.

## Supplementary materials
[**Main ﬁle**](https://github.com/OGCJN/Tail-estimation-for-window-censored-processes/blob/master/Supplementary%20Materials/Supplementary%20materials.pdf): Contains exact expressions for residual life for gamma and Weibull distributions, additional results on asymptotic normality, and a brief description of numerical routines used
throughout the analysis.

[**SmartTail**](https://github.com/OGCJN/Tail-estimation-for-window-censored-processes/blob/master/Supplementary%20Materials): Estimation algorithms, simulation study, analysis of 100-Car data, and numerical veriﬁcation of asymptotic normality. 

## Reference
Rootzen, H. and Zholud, D. (2015). [**Efficient estimation of the number of false positives in high-throughput screening**](http://www.zholud.com/articles/Efficient-estimation-of-the-number-of-false-positives-in-high-throughput-screening.pdf), *Biometrika*, Vol. 102, No. 3, pp. 695-704.

## BiBTeX

``` BiBTeX
@article{RootzenZholud2015,
  Author = {Rootz\`{e}n, H. and Zholud, D.},
  Year = {2015},
  Title = {Efficient estimation of the number of false positives in high-throughput screening},
  Journal = {Biometrika},
  Volume = {102},
  Number = {3},
  Pages = {695--704}
}
```

---
Update 2018
