# Experiment No. - 4 : Implement and explore performance evaluation metrics for Data Models (Supervised/Unsupervised Learning) 

## Performance evaluation metrics 
- used to measure the effectiveness of a machine learning model.
- Different metrics are used for different types of models (supervised/unsupervised) and for different types of problem statements.

### Common performance evaluation metrics for Supervised Learning:
1. Accuracy: It is the most commonly used metric for classification problems. It is the ratio of correct predictions to total predictions.
2. Precision: It is the ratio of true positive predictions to the sum of true positive and false positive predictions.
3. Recall: It is the ratio of true positive predictions to the sum of true positive and false negative predictions.
4. F1 Score: It is the harmonic mean of precision and recall.
5. ROC AUC: It is the receiver operating characteristic area under the curve. It measures the ability of the classifier to distinguish between positive and negative classes.
6. Mean Squared Error (MSE): It is used for regression problems. It measures the average of the squares of the differences between the predicted values and the actual values.
7. Mean Absolute Error (MAE): It is also used for regression problems. It measures the average of the absolute differences between the predicted values and the actual values.

### Common performance evaluation metrics for Unsupervised Learning:
1. Within-Cluster Sum Square
2. Silhouette Coefficient
3. Calinski-Harabasz Index
4. Davies-Bouldin Index
5. Cumulative Explained Variance
6. Trustworthiness
7. Sammon’s Mapping

## List of Problem Statements

### 1. Predicting Housing Prices:
A supervised learning algorithm can be  trained on a dataset of housing prices and various features such as location, size, etc. to predict the sale price of a house. This study was useful in helping home buyers and sellers make informed decisions.
* Algorithm: Decision Tree, Random Forest, Linear Regression, Support Vector Regression (SVR)
* Evaluation Parameters: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R-Squared (R2)
* Dataset Link: Kaggle https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

### 2. Predicting Sales:
A supervised learning algorithm can be trained on a dataset of sales data to predict future sales. This study was useful in making informed business decisions and improving sales forecasts.
* Algorithm: Time Series Forecasting (ARIMA, SARIMA), Random Forest, XGBoost, LightGBM
* Evaluation Parameters: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE)
* Dataset Link: Kaggle (https://www.kaggle.com/competitions/store-sales-time-series-forecasting)

### 3. Predicting Loan Default:
A supervised learning algorithm can be trained on a dataset of loan applicants to predict the likelihood of loan default. This study was useful in reducing the risk of loan default and improving the efficiency of loan approval processes.
* Algorithm: Logistic Regression, Random Forest, XGBoost, LightGBM
* Evaluation Parameters: Confusion Matrix, Precision, Recall, F1-Score, Area Under the Receiver Operating Characteristic Curve (AUC-ROC)
* Dataset Link: Kaggle (https://www.kaggle.com/c/loan-default-prediction)

### 4. Predicting Credit Card Fraud:
A supervised learning algorithm can be  trained on a dataset of credit card transactions to detect and classify fraudulent transactions. This study was useful in reducing the financial losses incurred by banks and other financial institutions due to credit card fraud.
* Algorithm: Logistic Regression, Random Forest, XGBoost, LightGBM, Isolation Forest
* Evaluation Parameters: Confusion Matrix, Precision, Recall, F1-Score, Area Under the Receiver Operating Characteristic Curve (AUC-ROC)
* Dataset Link: Kaggle (https://www.kaggle.com/mlg-ulb/creditcardfraud)

### 5. Predicting Customer Lifetime Value:
A supervised learning algorithm can be trained on a dataset of customer behavior and demographic information to predict the lifetime value of a customer. This study was useful in improving customer retention and maximizing the value of customer relationships.
* Algorithm: Random Forest, XGBoost, LightGBM, Gradient Boosting
* Evaluation Parameters: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R-Squared (R2)
* Dataset Link: Kaggle (https://www.kaggle.com/c/predicting-red-hat-business-value)

### 6. Predicting Employee Attrition:
A supervised learning algorithm can be trained on a dataset of employee information to predict the likelihood of employee attrition. This study was useful in reducing employee turnover and improving the efficiency of human resource management.
* Algorithm: Logistic Regression, Random Forest, XGBoost, LightGBM, Gradient Boosting
* Evaluation Parameters: Confusion Matrix, Precision, Recall, F1-Score, Area Under the Receiver Operating Characteristic Curve (AUC-ROC)
* Dataset Link: Kaggle (https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

### 7. Predicting Stock Market Trends:
A supervised learning algorithm can be trained on a dataset of stock market data to predict future stock market trends. This study was useful in making informed investment decisions and achieving higher returns.
* Algorithm: Time Series Forecasting (ARIMA, SARIMA), LSTM, GRU, Random Forest, XGBoost, LightGBM
* Evaluation Parameters: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE)
* Dataset Link: Kaggle (https://www.kaggle.com/c/

###8. Predicting Customer Segmentation: 
A supervised/unsupervised  learning algorithm can be trained on a dataset of customer behavior and demographic information to segment customers into different groups. This study is useful in improving marketing efforts and targeting the right customers with the right products
* Algorithm: K-Means Clustering
* Evaluation Parameters: Silhouette Score, Calinski-Harabasz Index, Davies-Bouldin Index
* Dataset Link: https://archive.ics.uci.edu/ml/datasets/Online+Retail.

### 9.Predicting Ad Click-Through Rate:
A supervised learning algorithm can be trained on a dataset of online advertising data to predict the likelihood of an ad being clicked. This study was useful in improving the efficiency of online advertising campaigns and maximizing ad revenue.
* Algorithm: Logistic Regression, Random Forest, Gradient Boosting
* Evaluation Parameters: Confusion Matrix, Accuracy, F1 Score, Precision, Recall, Area Under ROC Curve (AUC-ROC)
* Dataset Link: https://archive.ics.uci.edu/ml/datasets/Online+Ad+Click-Through+Rate

### 10. Predicting Customer Satisfaction:
A supervised learning algorithm can be trained on a dataset of customer feedback to predict customer satisfaction. This study was useful in improving customer service and satisfaction and reducing customer churn rates.   
* Algorithm: Logistic Regression, Random Forest
* Evaluation Parameters: Confusion Matrix, Accuracy, F1 Score, Precision, Recall
* Dataset Link: https://archive.ics.uci.edu/ml/datasets/

### 11. Enefit - Predict Energy Behavior of Prosumers
To create an energy prediction model of prosumers to reduce energy imbalance costs.
* Algorithm: Time Series Forecasting (ARIMA, SARIMA), LSTM, GRU, Random Forest, XGBoost, LightGBM
* Evaluation Parameters: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE)
*  Dataset : https://www.kaggle.com/competitions/predict-energy-behavior-of-prosumers

## Online Resources:
- [Pyhton Machine Learning Case STudies - Danish Harron](https://github.com/shahumar/Free-Machine-Learning-Books/blob/master/book/Python%20Machine%20Learning%20Case%20Studies.pdf)
- [Exploring Unsupervised Learning Metrics](https://www.kdnuggets.com/2023/04/exploring-unsupervised-learning-metrics.html)
