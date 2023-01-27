# Potential Customer Prediction
#### Project Summary:
The company has asked the data analyst to determine which customers to take on from a new customer list. The company has given the analyst some historical data that he can use to make inferences on the new dataset. 
#### Desired Insights:
* Based on demographic data, how many accidents will the new customer have, and what will the costs be?
* Which customers should the company take on based on number of accidents/costs?
#### Skills:
##### Python
* Data population to reduce the number of rows lost in the dataset in both training and test dataset.
* Data binning/hot-encoding to extract relevant categories from the data.
* Use of 75/25 train-test split to evaluate the performance of the supervised machine learning model.
* Tuning parameters and tuning hyperparameters during exploratory analysis to find the optimal model, paramater, and hyperparamater combination.
## Preparing the Data
* Data was prepared in a similar manner to the Policyholder Identification project other than the population of date values, data binning for the age column, and one-hot-encoding the data. Populating the data from the date of birth reduced data loss (num of rows) by approximately 42% in both the training dataset and test dataset. If you want to see the full code click [here](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/auto_prediction_sl.ipynb)
## Implementing Machine Learning Classification and Regression Models

I had a few goals in mind when I implemented the Supervised Machine Learning models:
* Find the optimal clustering model between knn and decision tree by iterating through multiple paramaters and hyperparameters on both models.
* Determine the correct model using the appropriate accuracy metrics, in this case mean absolute error for regression and F1 for classification. 
  
## Balancing Methods
Oversampling and undersampling were both tested for the classification portion of the code to try to improve overall accuracy for the F1 score. The oversampling method won out by having a higher F1 score than undersampling and by fitting the project parameters better as will be explained in the next sentence. Only oversampling was used for the regression portion of the code because the problem outline stated that the worst possible outcome would be to underestimate claims' cost.

## [Problem Statement](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/AutoInsuranceCaseStudyPt2.pdf)
## [Findings & Presentation](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/Classifying%20Policyholders%20with%20Supervised%20Learning.pdf)
## [Code](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/auto_prediction_sl.ipynb)
## [Training Dataset](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/auto_policies_2020.csv)
## [Test Dataset](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/auto_potential_customers_2022.csv)
## [Outcomes](https://github.com/benjammin97/PotentialCustomerPrediction/blob/main/Outcomes)
