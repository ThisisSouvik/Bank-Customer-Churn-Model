# Bank-Customer-Churn-Model

Link of the Project: https://colab.research.google.com/drive/1Q4OImbVeLnE5y5R2C4UDmFHfx5QMwuy4?usp=sharing

Certainly! Here is a brief description of the Bank Customer Churn Model based on the provided project link and the attached file:

# Bank Customer Churn Model

The **Bank Customer Churn Model** is a machine learning project aimed at predicting whether a customer will leave the bank (churn) based on various features of their account and transaction history. This project utilizes a dataset containing information about bank customers, including features such as credit score, age, tenure, balance, number of products, and estimated salary.

#Key Components of the Project

1. **Data Preprocessing:**
   - **Loading the Data:** The dataset is loaded into a Pandas DataFrame.
   - **Handling Missing Values:** Any missing values are identified and handled appropriately.
   - **Encoding Categorical Variables:** Categorical features like gender and geography are encoded into numerical values using techniques such as one-hot encoding.
   - **Feature Scaling:** Numerical features are scaled to ensure that all features contribute equally to the model's performance.

2. **Exploratory Data Analysis (EDA):**
   - Various visualizations and statistical analyses are performed to understand the distribution of the data and the relationships between different features.
   - Insights from EDA help in selecting the most relevant features for the model.

3. **Model Building:**
   - Several machine learning algorithms are explored, including Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
   - The dataset is split into training and testing sets to evaluate the model's performance.
   - Hyperparameter tuning is performed to optimize the model's performance.

4. **Model Evaluation:**
   - The models are evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC score.
   - The best-performing model is selected based on these evaluation metrics.

5. **Prediction:**
   - The final model is used to predict customer churn on the test set.
   - Predictions are analyzed to understand the factors contributing to customer churn.

# Conclusion

The Bank Customer Churn Model helps in identifying customers who are likely to leave the bank. By understanding the key factors that influence customer churn, banks can implement targeted strategies to retain customers and improve overall customer satisfaction.


