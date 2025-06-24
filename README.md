# Titanic-Prediction
Machine learning notebooks for Titanic survival prediction.
# 🚢 Titanic Survival Prediction

This project builds a machine learning model to predict passenger survival from the Titanic disaster using data from the famous Kaggle competition: **Titanic - Machine Learning from Disaster**.

---

## 🧠 Objective

Predict whether a passenger survived the Titanic shipwreck based on features such as age, gender, class, and more.

This project is beginner-friendly and focuses on:
- Understanding real-world data preprocessing
- Feature engineering
- Model training and evaluation using classification algorithms

## ⚙️ Project Workflow

1. **Data Exploration**
   - Basic statistics
   - Null values and missing data analysis

2. **Data Cleaning**
   - Impute missing values (e.g., Age, Embarked)
   - Drop or encode irrelevant columns (e.g., Ticket, Cabin)

3. **Feature Engineering**
   - Title extraction from names
   - Family size from `SibSp` and `Parch`
   - Encoding categorical features (Sex, Embarked, Title)

4. **Modeling**
   - Algorithms used:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machine (SVM)
   - Cross-validation and grid search for hyperparameter tuning

5. **Evaluation**
   - Accuracy
   - Confusion matrix
   - Classification report
