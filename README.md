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
   - Impute missing values (e.g., Age, Embarked, Age)
   - Drop or encode irrelevant columns (e.g., Ticket, Cabin)

3. **Feature Engineering**
   - Encoding categorical features (Sex, Embarked)

4. **Modeling**
   - Algorithms used:
     - Random Forest

5. **Evaluation**
   - Accuracy
   - Confusion matrix
   - Classification report
   - 
## 📊 Exploratory Data Analysis (EDA)

The project includes several visualizations to understand the data:

- **Survival Count by Gender**: Bar plot showing male vs. female survival rates.
- **Age Distribution**: Histogram of passenger ages, with insights into which age groups survived more.
- **Survival by Passenger Class**: Bar plot showing survival rates by `Pclass`.
- **Fare Distribution**: Histogram of fare amounts paid by passengers.
- **Heatmap of Correlations**: Seaborn heatmap to visualize relationships between numerical features.
