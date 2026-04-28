📈 Stock Price Prediction using Regression Models

📌 Project Overview

This project focuses on predicting the closing price of a stock using historical market data.
Multiple regression models are implemented and compared to understand their performance on highly correlated financial features.

The project is designed to demonstrate:

Data preprocessing

Model selection

Proper evaluation

Clear result interpretation

Contains historical stock market data

Key columns include:

Date

Open

High

Low

Close

Adj Close

Volume

Used as the primary dataset for training and evaluation

Main Google Colab Notebook containing the complete workflow:

Importing libraries like : scikit learn , numpy

Data loading and exploration

Feature selection

Train–test split

Feature scaling (where required)

Model training

Model evaluation

Prediction visualization

Regression Models Implemented:

Linear Regression

Polynomial Regression

Decision Tree Regression

Random Forest Regression

Evaluation Metrics:

R² Score – Measures explained variance

RMSE – Measures prediction error

Actual vs Predicted plots are used to visualize model performance.

A presentation summarizing the project:

Project objective and dataset

Preprocessing steps and models used

Evaluation metrics

Results


🧠 Key Insight

Due to the strong correlation between stock price features such as Open, High, Low, and Adjusted Close with the closing price, all models achieved high predictive performance, resulting in similar prediction patterns.

🛠️ Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib

Google Colab

📊 Results

| Model | R² Score | RMSE |
|-------|----------|------|
| Linear Regression | 1.0000 | 0.00 |
| Polynomial Regression | 1.0000 | 0.00 |
| Decision Tree | 0.9946 | 6.05 |
| Random Forest | 0.9978 | 3.89 |

⚠️ Limitation
TNote: R² = 1.0 in Linear/Polynomial models indicates 
possible data leakage due to high feature correlation. 
This is acknowledged as a learning observation.his project provides a comparative study of different regression techniques on stock market data and highlights the importance of feature correlation, model selection, and evaluation metrics in predictive modeling.
