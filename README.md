# 🏠 House Price Prediction – Kaggle Competition

## 📌 Project Overview

This project focuses on predicting house sale prices using machine learning regression models.

It was developed as part of the **[Housing Prices Competition for Kaggle Learn Users](https://www.kaggle.com/competitions/home-data-for-ml-course)**.

The goal was to explore how different machine learning algorithms can learn patterns from housing data and predict the sale prices of houses.

This was my first hands-on machine learning competition, where I practised data preparation, model training, evaluation, and generating predictions for a Kaggle submission.

## 🎯 Objectives

- Understand the basics of supervised machine learning.
- Prepare training and testing datasets.
- Select numerical features for model training.
- Train and evaluate Decision Tree and Random Forest regression models.
- Compare model performance using Mean Absolute Error (MAE).
- Generate predictions and submit results to Kaggle.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Kaggle

## 📊 Project Workflow

### 1. Data Preparation

- Loaded the training and testing datasets using Pandas.
- Separated the target variable (`SalePrice`) from the input features.
- Selected numerical features by excluding columns with object data types.
- Split the training data into training and validation sets using `train_test_split` with `random_state=1`.

### 2. Machine Learning Models

Implemented and experimented with the following regression models:

**Decision Tree Regressor**
- Trained a default Decision Tree Regressor.
- Improved the model by setting `max_leaf_nodes=100`.
- Generated predictions on the validation dataset.

**Random Forest Regressor**
- Trained a default Random Forest Regressor.
- Experimented with `max_leaf_nodes=100`.
- Generated predictions on the validation dataset.

### 3. Model Evaluation

Used **Mean Absolute Error (MAE)** to evaluate the models.

MAE measures the average absolute difference between the actual house prices and the predicted house prices. A lower MAE indicates better prediction accuracy.

### 4. Kaggle Submission

- Generated predictions for the competition test dataset.
- Created submission CSV files in the required Kaggle format.
- Submitted predictions to the Kaggle competition.

## 🏆 Kaggle Result

Successfully submitted my predictions and received my first competition leaderboard score.

| Metric | Result |
|---|---|
| Competition | Housing Prices |
| Kaggle Score (MAE) | 17,683.98843 |
| Submission Status | Successful |

[View my Kaggle profile](https://www.kaggle.com/fahikader)

## 📁 Project Structure

```text
Housing-Price-Prediction/
│
├── Housing-Price-Prediction.ipynb
└── README.md
```

## 📚 What I Learned

Through this project, I gained practical experience in:

- Understanding supervised machine learning and regression.
- Preparing datasets for machine learning.
- Separating features (X) and target variables (y).
- Training Decision Tree and Random Forest models.
- Understanding model parameters such as `max_leaf_nodes`.
- Evaluating predictions using Mean Absolute Error.
- Generating prediction files for Kaggle competitions.

## 🚀 Future Improvements

- Explore missing value imputation.
- Handle categorical features instead of using only numerical features.
- Apply cross-validation for more reliable model evaluation.
- Experiment with feature engineering and hyperparameter tuning.
- Explore ensemble methods and improve prediction performance.

---

**This project is part of my journey into Machine Learning, Data Science, and Artificial Intelligence.**
