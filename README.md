Predicting Customer Acceptance of Bank Offers

Student Name: Py Elan Alsaeed
Instructor: Eng. Raghad Alshammari

1. Introduction

In this project, a machine learning model was developed to predict whether a client will accept a bank’s financial offer based on their personal and financial data. This type of prediction is important for banks to improve marketing strategies, target the right customers, and increase conversion rates.

2. Dataset Description

The dataset used in this project contains customer-related information such as age, income, account balance, and other financial attributes.

The target variable indicates whether the client accepted the bank’s offer (Yes/No).

Before training the models, the dataset was checked for missing values and cleaned to ensure data quality.

3. Models Used

In the first step, several machine learning models were trained to solve the classification problem, including:

Logistic Regression
Random Forest
K-Nearest Neighbors (KNN)

The models were evaluated using the following metrics:

Accuracy
Precision
Recall
F1-score

Among these models, Random Forest achieved the best performance, as it captured complex patterns in the data and provided the highest F1-score.

4. Neural Network

In the second step, a neural network was built using Keras. The model included:

Dense layers with ReLU activation
An output layer with Sigmoid activation for binary classification
A Dropout layer to reduce overfitting

The model was trained for more than 10 epochs using the same dataset. Training and validation performance were monitored to ensure the model was learning effectively without overfitting.

5. Results & Comparison

After evaluating the neural network on the test data, its performance was compared with the traditional machine learning models.

The neural network achieved competitive results and slightly improved the F1-score in some cases. However, it required more training time compared to other models.

Overall, Random Forest remained a strong baseline due to its simplicity and efficiency, while the neural network showed potential for handling more complex data.

6. What I Learned

From this project, I gained several important insights:

Data preprocessing plays a critical role in model performance
Simpler models can sometimes perform as well as complex models
Neural networks require careful tuning to avoid overfitting
Using multiple evaluation metrics (especially F1-score) is essential in classification problems

This project helped me understand the complete machine learning pipeline, from data preparation to model evaluation and comparison.
