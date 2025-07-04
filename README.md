# Titanic Survival Prediction 🚢

This repository contains a machine learning project focused on supervised classification modelling using the Titanic dataset from Kaggle. The objective is to predict passenger survival based on personal and travel information.

## 🎯 Objective

The goal of this project is to develop a **binary classification model** that predicts whether a passenger survived the Titanic disaster. The notebook includes exploratory data analysis, data preprocessing, feature selection, model training, hyperparameter tuning, evaluation, and prediction.

## 📂 Dataset

- **Name:** `train.csv`, `test.csv`
- **Origin:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/)
- **Entries:** 891 rows (train), 418 rows (test)
- **Format:** CSV (tabular data)
- **Main variables:** `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

## ⚙️ Project Scope

All steps were implemented in a single Jupyter Notebook (`TITANIC.ipynb`) and include:

- **Exploratory Data Analysis & Preprocessing:**
  - Handling missing values (`Age`, `Cabin`, `Embarked`, `Fare`)
  - Feature engineering and data cleaning
  - Outlier and duplicate detection
  - Categorical variable encoding
- **Feature Selection:**
  - Removing highly correlated features
  - Variance threshold filtering
  - Feature importance evaluation
- **Modeling:**
  - Model selection and evaluation with Logistic Regression, Random Forest, and XGBoost
  - Hyperparameter tuning
  - Final model selection and prediction generation

## 📊 Results Summary

The final deliverables include:

- A trained classification model evaluated using accuracy, F1-score, and feature importance
- A submission file achieving a **public Kaggle score of 0.75837**
- `Titanic_submission.csv` ready for Kaggle submission

All transformations and modelling decisions are thoroughly documented to ensure reproducibility.

## 📄 Repository Contents

- `TITANIC.ipynb`  
  Complete notebook with business understanding, EDA, preprocessing, modelling and prediction steps.

- `Titanic_submission.csv`  
  Final Kaggle submission file.

- `DataDictionary.png`  
  Image describing dataset variables.

- `requirements.txt`  
  Python dependencies used in the project.

- `LICENSE`  
  License information for the project.

- `.gitignore`  
  Specifies files and folders to be ignored by Git.

- `README.md`  
  This file.

## 🚀 How to Run

1. Install dependencies:  
   ```bash
   pip install -r requirements.txt

2. Launch the notebook: TITANIC.ipynb.
