# Goal Prediction Model
Predicting the number of goals a player will make in an upcoming game, given current statistics.
This is a basic prediction model built on a dataset of Premier League Football players. The aim is to use five different regression models to predict the number of goals a player scores, and evaluate their performance. The models tested are:
1. Simple Linear Regression
2. Polynomial Regression
3. Support Vector Regression
4. Decision Tree Regression
5. Random Forest Regression

## Dataset
The dataset is taken from Kaggle at:

## Preprocessing:
- Data is analysed externally
- NaN values are handled using 'mode'
- Required columns are encoded (Label Encoder)
- Correlation matrix used to drop irrelevant columns

## Result:
It is observed that of all implemented models, Random Forest Regression had the best performance and highest accuracy (99.03%).  
This high performance can be attributed to the ensemble nature of the model, and it's ability to gauge non-linear, complex relations between attributes while being robust to outliers and less prone to the sensitivity issues like overfitting that can plague models like SVR or Decision Tree without extensive fine-tuning.
