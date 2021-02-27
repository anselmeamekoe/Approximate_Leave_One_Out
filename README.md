# Approximate_Leave_One_Out

This repo contains the R codes and the report of the research internship I did for a period of 4 months for the validation of my Master 1 in Statistics and Data Sciences (SSD).
This internship was supervised: 
- Sana Louhichi : University Professor at Grenoble Alpes University and Researcher at the Jean Kuntzmann Laboratory (CNRS)
- Didier A. Girard : Senior Researcher at Laboratory Jean Kuntzmann (CNRS)
- Karim Benhenni : Associate Professor at Grenoble Alpes University and Researcher at the Jean Kuntzmann Laboratory (CNRS)

The theme of this internship is : CHOICE OF PENALISATION PARAMETER IN GENERALISED LINEAR MODELS  IN HIGH DIMENSION


##  Abstract
Model selection or validation in statistical learning is usually based on the ability to modeling for reasons of data interpretation or model prediction accuracy
in competition. With regard to prediction, it is important to make an error estimate for
future data. For penalized regressions such as LASSO, Ridge and Elastic-net, the estimation
of this error often involves the observation of its curve as a function of the smoothing parameter or
penalty generally noted. The method of cross-validation (which
consists in dividing the training sample into several parts called folds) is a technique
simple and intuitive to estimate the prediction error for new data. In large
dimension i.e. in the case where the number of explanatory variables (p) is of the same order or more
observations (n), this technique suffers from an enormous bias when the number of observations is greater
of folds is small. Thus motivated by the lowest bias of the most extreme form of validation
the Leave-One-Out (LO), the article "A scalable estimate of the extra-sample prediction error
via approximate leave-one-out" [RM18] offers the Approximate Leave-One-Out (ALO) for a wide range of
class of regularised estimators. This approximation considerably reduces time, resources and costs.
calculation and with some assumptions about the data, the results obtained converge with those of the
LO with a high probability when n, p become large. In this report we discuss the
results obtained in [RM18] and we redo a large part of their simulations, and then we
will make illustrations not included in [RM18] using the simulated data and we will end up with an
perspective on future work.


Our work and codes are based on :

[RM18] Kamiar Rahnama Rad and Arian Maleki. A scalable estimate of the extra-sample prediction
error via approximate leave-one-out. arXiv : Methodology, 2018.
