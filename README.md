# Regression

# Objective
To apply the models learnt from the Udemy course "Python for Machine Learning and Data Science Bootcamp".

# Dataset
The dataset is available on kaggle - "House Price Prediction Challenge".  
Link to the website - https://www.kaggle.com/datasets/anmolkumar/house-price-prediction-challenge?select=train.csv
## Description of Dataset
This dataset has been collected across various property aggregators across India. The buyers are just not concerned about the size(square feet) of the house and there are various other factors that play a key role to decide the price of a house/property.  
The dataset contains the following features:
* Coordinates of the house.
* Condition of the house like resale, under construction.
* Area of house in square feet

# Solution
To develop a suitable model to predict the price of a house, given the requisite information. R2 score from sklearn was used to compare the efficiency of the models. For KNN Regressor, SVM and Neural Networks, the data was scaled using Standard Scaler.

# Models
Given below are the models that were applied alongwith their accuracy scores:
* Linear Regression : 0.29
* Decision Tree Regressor : 0.92
* Random Forest Regressor : 0.95
* K Nearest Neighbour Regressor : 0.65 (after parameter tuning)
* Support Vector Machines : 0.52 (after parameter tuning)
* Neural Networks : 0.88

# Conclusion
Random Forest Regressor gave predictions with the highest accuracy among the applied models.  
Based on my learning, scaling the data with Standard Scaler and then applying Random Forest Regressor model would be recommended to solve this problem.
This model is used to predict the price of houses as described by the 'test.csv' dataset.
