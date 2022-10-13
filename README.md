# PotentialCustomerPrediction
This project uses auto insurance data to find the best segment of new customers.
Purpose:
		The purpose of the Customer Prediction project was to select future clients with the lowest claim cost based on the historical data 
    determined by the best machine learning models.
	Process: 
Data was preprocessed by populating missing age values to reduce the number of null values in the dataset, eliminating each row with a null value 
with it(not including zero claims), eliminating unneccessary columns, and scaling the data. Tested the knearest neighbors and decision tree algoritms extensively 
using itertools and predicted the number of claims and the cost of claims a potential customer test dataset would have based on the accuracy scores 
(F1 and mean absolute error used) of a 75/25 independent test split of the training dataset for machine learning models (k-nearest neighbors,decision trees) 
including both classification and regression. Balancing techniques such as undersampling, oversampling, and SMOTE were used to improve F1 scores.
