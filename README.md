# Car price prediction

Description :-
Estimating a car's price based on its features. 

Dataset :- 
https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge

### Data Cleaning :- 
- Eliminating the duplicate columns, replacing a specific column that contains a special character with nan values
- The outliers were removed using the iqr approach.

### Feature Engineering :-
- Filling in a missing value with the KNN Imputer
- Instead of utilising ordinal encoding, because some of the columns contained more than 20 categorical variables. Target guided encoding that I utilised provides greater correlation with the dependent variable.

### Model Creation :- 
##### Decision Tree Regressor

### Model Evaluation :- 
- R2 Score :- 0.99
- Mean absolute error :- 17.79
- Mean absolute percentage error :- 0.005


### Conclusion :- 
Model provided good accuracy, thus I didn't even adjust the hyperparameters. Target directed encoding and mean encoding were used in place of label encoding, and they produced substantial correlations with the target variable.




