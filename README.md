# Credit_Risk_Analysis

## Overview of the analysis

The puprpose of this analysis is to build and evaluate several machine learning algorithms to predict credit risk, as credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results:
For each trained model, we generate predictions from our testing data and calculate the balanced accuracy score, precision, and recall to compare the success of each and form a recommendation to predict credit risk from this data set.

**Naive Random Oversampling**

![pic1](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/naiverandombalancedacc.PNG)

![pic2](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/naive2.PNG)

-The balanced accuracy score is 65%.

-The high_risk precision is about 1% only with 70% sensitivity which makes a F1 of 2% only.

-Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 63%.

**SMOTE Oversampling**
![pic3](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/smotebalancedacc.PNG)

![pic4](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/smote2.PNG)

-The balanced accuracy score is 66%.

-The high_risk precision is about 1% only with 63% sensitivity which makes a F1 of 2% only.

-Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 69%.

**ClusterCentroids**

![pic5](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/cluster%20centroidbalancacc.PNG)

![pic6](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/clustercent2.PNG)

-The balanced accuracy score is down to about 54%.

-The high_risk precision is about 1% only with 69% sensitivity which makes a F1 of 1%.

-Due to the high number of false positives, the low_risk sensitivity is only 40%.


**SMOTEENN**

![pic7](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/smoteennbalaccscore.PNG)

![pic8](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/96d031bf2edfeccbbb5c028f35423bf76e6b7cca/Resources/smoteen2.PNG)

-The balanced accuracy score is about 64%

-The high_risk precision is about 1% only with 71% sensitivity which makes a F1 of 2%.

-Due to the high number of false positives, the low_risk sensitivity is only 58%.

**Balanced Random Forest Classifier**
![pic9](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/5ac541995b06bcb14f6e1813dd783a1e8e845823/Resources/balancedforestcalacc.PNG
![pic10](https://github.com/Klubbers0/Credit_Risk_Analysis/blob/5ac541995b06bcb14f6e1813dd783a1e8e845823/Resources/balancedforest2.PNG)

-The balanced accuracy score is about 68%

-The high_risk precision is about 88% only with 37% sensitivity which makes a F1 of 52%.

-The low_risk precision is 100% with a 100% sensitivity.

**EasyEnsembleClassifier model**

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
