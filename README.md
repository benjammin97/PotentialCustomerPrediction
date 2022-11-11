# Potential Customer Prediction
Data was preprocessed by populating missing age values to reduce the number of null values in the dataset, eliminating each row with a null value 
with it(not including zero claims), eliminating unneccessary columns, and scaling the data. Tested the knearest neighbors and decision tree algoritms extensively 
using itertools and predicted the number of claims and the cost of claims a potential customer test dataset would have based on the accuracy scores 
(F1 and mean absolute error used) of a 75/25 independent test split of the training dataset for machine learning models (k-nearest neighbors,decision trees) 
including both classification and regression. Balancing techniques such as undersampling, oversampling, and SMOTE were used to improve F1 scores.

## [Problem Statement](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/MSC550%20Fall%202021%20Final%20(6).pdf)
## [Findings & Presentation](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/Classifying%20Policyholders%20with%20Supervised%20Learning.pdf)
## [Code](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/auto_prediction_supervised_learning.ipynb)
## [Training Dataset](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/auto_policies_2020.csv)
## [Test Dataset](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/auto_potential_customers_2022.csv)
