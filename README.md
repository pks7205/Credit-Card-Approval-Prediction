# Credit-Card-Approval-Prediction
https://colab.research.google.com/drive/1G6dRhZpkAfc89zHEi1bv9qxoMTrybhPy#scrollTo=UwOCXRyWLXiK

## Project Overview:
This project focuses on predicting credit card approval using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment. Below is an overview of the project.

## Table of Contents:
* Project Motivation
* Dataset
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Modeling
* Conclusion

## Project Motivation:
Credit card companies need to assess whether a customer is creditworthy before approving a credit card application. Automating this process using machine learning can save time and reduce human error. This project aims to build a predictive model that can accurately determine the approval status of credit card applications based on applicant information.

## Dataset:
The dataset used in this project is the "Credit Card Approval" dataset, which contains various features about the applicants, such as Gender, Annual income, employment status, and occupation so on ,

* Features name: (Credit_Card.csv)

* Ind_ID: Client ID

* Gender: Gender information

* Car_owner: Having car or not

* Propert_owner: Having property or not

* Children: Count of children

* Annual_income: Annual income

* Type_Income: Income type

* Education: Education level

* Marital_status: Marital_status

* Housing_type: Living style

* Birthday_count: Use backward count from current day (0), -1 means yesterday.

* Employed_days: Start date of employment. Use backward count from current day (0). Positive value means, individual is currently unemployed.

* Mobile_phone: Any mobile phone

* Work_phone: Any work phone

* Phone: Any phone number

* EMAIL_ID: Any email ID

* Type_Occupation: Occupation

* Family_Members: Family size

Another data set (Credit_card_label.csv) contains two key pieces of information

* ID: The joining key between application data and credit status data, same is Ind_ID

* Label: 0 is application approved and 1 is application rejected. 

## Data Preprocessing:
Data preprocessing involves the following steps:

* Handling Missing Values: Impute or remove missing values.
* Encoding Categorical Variables: Convert categorical variables into numerical format using techniques like one-hot encoding or label encoding.
* Feature Scaling: Standardize or normalize numerical features to bring them to a common scale.
* Splitting the Data: Split the dataset into training and testing sets.

## Exploratory Data Analysis (EDA):
EDA helps in understanding the data distribution, relationships between features, and identifying any patterns. This involves:

* Visualizing the distribution of numerical and categorical features.
* Analyzing correlations between features.
* Identifying any outliers or anomalies in the data.

## Modeling Building:
Various machine learning algorithms are used to build predictive models. The following models are considered:

* Logistic Regression
* Cross Validation
* Decision Tree
* XG Boost
* Random Forest

## Conclusion:
Hence we got accuracy on different classification

* logisitic regression got accuracy 88%

* DecisionTree got accuracy 85%

* xg boosting got accuracy 90%

* Random Forest got accuracy 92%

Random Forest is having the highest Cross Validation Score with 0.922 followed by XGBoost with 0.909.

Based on all the model evaluation techniques we can say that Random Forest is the best model for our project to predict credit card approval.

The project demonstrates the process of building a machine learning model to predict credit card approval status, starting from data preprocessing to model deployment. The deployed model can assist financial institutions in automating the credit card approval process.

