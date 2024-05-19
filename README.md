# Bank Churn Dataset EDA and Prediction
This repository contains an exploratory data analysis (EDA) and prediction project using the Bank Churn dataset. The goal of this project is to understand the factors that contribute to customer churn in the banking industry and build a model to predict whether a customer is likely to churn or not.

## **Dataset**
The Bank Churn dataset consists of various features related to bank customers and their churn status. The dataset contains the following columns:

- CustomerID: Unique identifier for each customer
- Surname: Customer's last name
- CreditScore: Customer's credit score
- Geography: Customer's country of residence
- Gender: Customer's gender
- Age: Customer's age
- Tenure: Number of years the customer has been with the bank
- Balance: Customer's account balance
- NumOfProducts: Number of bank products the customer uses
- HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
- IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
- EstimatedSalary: Estimated salary of the customer
- Exited: Whether the customer has churned (1 = yes, 0 = no)

- Project Structure

## **The project is organized as follows:**

data/: This directory contains the Bank Churn dataset file (bank_churn.csv).
notebooks/: This directory contains Jupyter notebooks:

1_**data_exploration.ipynb:** Notebook for performing EDA on the dataset.

2_**data_preprocessing.ipynb:** Notebook for preprocessing the data for model training.

3_**model_training.ipynb:** Notebook for training and evaluating the prediction model.

4_**models:** This directory will contain the trained prediction model(s).

5_**README.md:** This file, providing an overview of the project.

## **Getting Started**
To get started with this project, follow these steps:

- Clone this repository to your local machine.
- Install the required dependencies specified in requirements.txt.

- Open the Jupyter notebooks in the notebooks/ directory and run them in sequential order.

## **Conclusion**
The Bank Churn dataset EDA and prediction project aims to explore the factors influencing customer churn in the banking industry and build a predictive model. By analyzing the dataset and training a model, we can gain insights into customer behavior and develop strategies to reduce churn rates.
