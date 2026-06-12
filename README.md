# 🚢 Titanic Survival Prediction

## 📌 Project Overview

This project is part of a Data Science internship task. The goal is to analyze the Titanic dataset and build a machine learning model that predicts whether a passenger survived or not based on their features.

The project demonstrates a complete data science workflow including data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling.

---

## 🎯 Objective

To predict passenger survival on the Titanic using machine learning techniques based on features such as:

- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Fare
- Family size (SibSp, Parch)
- Embarked location

---

## 📂 Project Structure

```
Titanic_Survival_Prediction/
│
├── dataset/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── titanic_survival_prediction.ipynb
│
├── README.md
└── .gitignore
```

---

## 🧹 Data Cleaning & Preprocessing

The dataset was cleaned and prepared for modeling:

- Handled missing values in:
  - Age → filled with median
  - Embarked → filled with mode
  - Fare → filled with median

- Removed irrelevant columns:
  - Cabin (too many missing values)
  - Name
  - Ticket
  - PassengerId

- Converted categorical variables into numerical format:
  - Sex → 0 (Male), 1 (Female)
  - Embarked → encoded values

---

## 📊 Exploratory Data Analysis (EDA)

Key insights from the dataset:

- Survival rate was approximately **41%**
- Female passengers had a significantly higher survival rate than males
- First-class passengers had higher survival chances than lower classes
- Most passengers were between 21–36 years old
- Fare distribution was highly skewed with noticeable outliers

---

## 📈 Data Visualization

The following visualizations were created:

- Survival count plot
- Gender distribution
- Survival by gender
- Survival by passenger class
- Age distribution histogram
- Fare distribution histogram
- Boxplot for outlier detection

---

## 🤖 Machine Learning Model

A **Logistic Regression** model was used for classification.

### Steps:

- Defined features and target variable
- Split data into training and testing sets
- Trained Logistic Regression model
- Evaluated model performance

---

## 📊 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score

### Key Insight:

The model successfully learned patterns indicating that **gender, passenger class, age, and fare are strong predictors of survival**.

---

## 🧠 Key Learnings

- Data preprocessing is crucial for model performance
- EDA helps uncover hidden patterns in data
- Feature selection impacts prediction accuracy
- Logistic Regression is effective for binary classification problems

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Future Improvements

- Try advanced models (Random Forest, XGBoost)
- Perform hyperparameter tuning
- Add feature engineering (family size, title extraction)
- Deploy model using Streamlit or Flask

---

## 👩‍💻 Author

**Mahnoor Naseer**
Data Science Intern

---

## 📌 Note

This project is part of an internship assignment and demonstrates foundational skills in data science, machine learning, and data analysis.
