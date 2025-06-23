Kaggle Notebook: https://www.kaggle.com/code/debanshu03/flight-price-prediction

Overview:
---------
The model predicts flight ticket prices using supervised machine learning. It analyzes features such as airline, source/destination cities, departure/arrival times, 
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

Results:
--------
- Best model: Random Forest Regressor
- Outcome: Model effectively predicts flight prices with good accuracy.


Predicted Price vs Actual Price Plot                 
--------------------
98.626% Accuracy Observed by r2_score using Random Forest Regressor

  ![image](https://github.com/user-attachments/assets/2a46846c-7e28-4e86-9df2-af6fa37c73cd)


Tools & Libraries:
------------------
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

