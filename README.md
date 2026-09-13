# House Price Prediction

A machine learning project for predicting house prices using the Kaggle House Prices: Advanced Regression Techniques dataset.

## 📌 Project Overview

The goal of this project is to build a machine learning model that predicts the sale price of residential properties based on various features such as living area, quality, location, garage, basement, and other property characteristics.

The project covers the complete machine learning workflow, from data exploration and preprocessing to model training, hyperparameter tuning, and evaluation.

## 📂 Dataset

The project uses the **House Prices: Advanced Regression Techniques** dataset from Kaggle.

The dataset contains:

- `train.csv` — Training data with house features and the target variable `SalePrice`
- `test.csv` — Test data used for generating predictions
- `data_description.txt` — Description of the dataset features

## 🔍 Project Workflow

1. Import required libraries
2. Load the dataset
3. Exploratory Data Analysis (EDA)
4. Analyze missing values
5. Handle missing data
6. Detect and handle outliers
7. Feature engineering
8. Separate features and target variable
9. Train-test split
10. Data preprocessing
11. Model training
12. Hyperparameter tuning
13. Model evaluation
14. Generate predictions

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 🤖 Machine Learning

The project uses regression techniques to predict `SalePrice`.

Model performance is evaluated using **Root Mean Squared Logarithmic Error (RMSLE)**.

## 📊 Evaluation

The model is evaluated on a validation dataset using RMSLE.

Lower RMSLE indicates better prediction performance.

## 📁 Repository Structure

```text
house-prices-advanced-regression/
│
├── data_description.txt
├── train.csv
├── test.csv
├── House_Price.ipynb
└── README.md
