**Name:** DURGA P

**Company:** CODTECH IT SOLUTIONS

**ID:** CT4ML3665

**Domain:** Machine Learning

**Duration:** July 1,2024 to August 1,2024

This project aims to predict fraudulent credit card transactions using machine learning models. We'll analyze customer-level data from a research collaboration between Worldline and the Machine Learning Group University Libre de Bruxelles.

## Problem Statement
The dataset, available on Kaggle, contains 284,807 transactions (September 2013, Europe) with only 492 marked as fraudulent. This significant imbalance requires special attention during model building.

## Business Problem Overview
For banks, retaining customers is paramount. Banking fraud, however, jeopardizes this goal by causing financial losses and damaging trust. The Nilson report estimates that banking frauds would reach $30 billion globally by 2020. As digital payments rise, so do fraudulent activities. Machine learning offers a powerful weapon for fraud detection, enabling proactive monitoring and prevention. It helps banks reduce manual review time, minimize chargebacks and fees, and avoid denying legitimate transactions.

## Understanding and Defining Fraud
Credit card fraud involves any unauthorized use of a cardholder's information for financial gain. Skimming, the most common method, duplicates magnetic strip data. Other forms of fraud include:

Manipulation/alteration of genuine cards
Creation of counterfeit cards
Stolen/lost credit card use
Fraudulent telemarketing

## Data Dictionary
The dataset contains credit card transactions made by European cardholders over two days in September 2013. With 492 fraudulent transactions out of 284,807, the data is highly imbalanced (positive class: 0.172%). Principal Component Analysis (PCA) has been applied to features (V1, V2, ..., V28) to preserve confidentiality. Only features 'time' (seconds elapsed from the first transaction) and 'amount' remain in their original form. The 'class' feature indicates fraud (1) or not (0).

## Project Pipeline
The project follows these four steps:

## Data Understanding:
Load and explore the data to identify relevant features for model building.
## Exploratory Data Analysis (EDA):
Perform univariate and bivariate analyses to understand data distribution and relationships. Feature transformations might be necessary, but due to Gaussian variables, Z-scaling may not be required. However, address any skewness to avoid issues during model building.
## Train/Test Split:
Split the data for training and testing to evaluate model performance on unseen data. K-fold cross-validation is recommended for balanced representation of the minority class in test folds. Choose an appropriate k value.
## Model Building/Hyperparameter Tuning: 
Experiment with different models and fine-tune their hyperparameters to achieve optimal performance. Explore various sampling techniques to potentially improve model results.
## Model Evaluation:
Evaluate models using appropriate metrics considering the imbalanced data. Since identifying fraudulent transactions is more crucial, choose metrics that reflect this business goal.


![Screenshot (104)](https://github.com/user-attachments/assets/46fcc31d-e01b-4700-9153-0dc12dd22c42)


![Screenshot (105)](https://github.com/user-attachments/assets/b7dff683-b127-4c13-908e-f173c44d857e)


![Screenshot (106)](https://github.com/user-attachments/assets/644923e9-6d9c-4bd2-a6a6-2cf6b3a6cb2a)


![Screenshot (107)](https://github.com/user-attachments/assets/0971e86e-37ee-4c9c-b3f0-8fbf1dd16d63)


![Screenshot (108)](https://github.com/user-attachments/assets/951a1576-c8a1-4fcb-87e8-f92ec28d28cf)


![Screenshot (109)](https://github.com/user-attachments/assets/87efd75a-79bb-4918-aedd-4bf6e6c84e03)


![Screenshot (110)](https://github.com/user-attachments/assets/e458c845-ccf4-4187-9b65-e3666c5a95f4)


![Screenshot (111)](https://github.com/user-attachments/assets/bf6730b1-710b-4f92-8773-dcd6bf76a655)


![Screenshot (112)](https://github.com/user-attachments/assets/a682e93d-b985-450b-82d6-3a04ded7fecf)


![Screenshot (113)](https://github.com/user-attachments/assets/160ead8e-fa25-4095-ad79-4532651cafcf)


![Screenshot (114)](https://github.com/user-attachments/assets/31be9a6b-67e9-427d-9bf8-8319c10e4589)


![Screenshot (115)](https://github.com/user-attachments/assets/0b9e89d4-ba9f-4562-a398-57180a676663)









