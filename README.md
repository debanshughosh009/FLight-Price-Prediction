README.txt
===========

Project Title: Flight Price Prediction  
Author: Debanshu Ghosh                                              
Kaggle Notebook: https://www.kaggle.com/code/debanshu03/flight-price-prediction

Overview:
---------
This project predicts flight ticket prices using supervised machine learning. 
It analyzes features such as airline, source/destination cities, departure/arrival times, 
and duration to estimate ticket costs accurately.

Methods Used:
-------------
- Data preprocessing: feature engineering (date-time and duration),
  and encoding categorical variables.
- Exploratory Data Analysis (EDA): visualizing trends and feature correlations.
- Models applied:
  * Linear Regression
  * Decision Tree Regressor
  * Random Forest Regressor (performed best)

Dataset:
--------
- Source: Kaggle flight price dataset
- Key features: Airline, Date of Journey, Source, Destination, Route, Duration, Total Stops

Results:
--------
- Best model: Random Forest Regressor 
- Metrics used: R² Score and Mean Absolute Error (MAE)
- Outcome: Model effectively predicts flight prices with good accuracy.


Predicted Price vs Actual Price Plot                 
--------------------
- 98.626% Accuracy Observed by r2_score using Random Forest Regressor

  ![image](https://github.com/user-attachments/assets/2a46846c-7e28-4e86-9df2-af6fa37c73cd)


Tools & Libraries:
------------------
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

Future Improvements:
--------------------
- Hyperparameter tuning with GridSearchCV
- Deployment using Flask or Streamlit
- Including additional features like holiday calendars and demand indicators
