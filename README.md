Titanic Survival Prediction
Overview

This project was completed as part of a Data Science internship to demonstrate the complete data analysis and machine learning workflow using the Titanic dataset.

The project includes data cleaning, exploratory data analysis (EDA), data visualization, and a predictive model to estimate passenger survival.

Project Objectives
Clean and preprocess the dataset
Handle missing values and data quality issues
Perform exploratory data analysis
Visualize important trends and patterns
Build a machine learning classification model
Generate meaningful insights from the data
Project Workflow

1. Data Cleaning and Processing
   Loaded training and testing datasets
   Handled missing values in Age, Embarked, and Fare
   Removed the Cabin column due to excessive missing data
   Removed unnecessary columns:
   PassengerId
   Name
   Ticket
   Checked and removed duplicate records
   Prepared the dataset for machine learning
2. Exploratory Data Analysis (EDA)
   Calculated descriptive statistics
   Analyzed passenger survival distribution
   Explored survival based on gender
   Explored survival based on passenger class
   Studied age and fare distributions
   Identified trends and outliers
3. Data Visualization

The project includes visualizations for:

Survival Count
Gender Distribution
Survival by Gender
Survival by Passenger Class
Age Distribution
Fare Distribution
Fare Outlier Detection 4. Predictive Modeling
Selected relevant features
Split the dataset into training and testing sets
Built a Logistic Regression classification model
Evaluated model performance
Key Insights
Approximately 41% of passengers survived.
Female passengers had a significantly higher survival rate than male passengers.
First-class passengers were more likely to survive than third-class passengers.
Most passengers were young adults between 21 and 36 years old.
Fare contains several high-value outliers.
Gender, passenger class, age, and fare are important features for predicting survival.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
Project Structure
Titanic_Survival_Prediction/
│
├── dataset/
│ ├── train.csv
│ └── test.csv
│
├── notebook/
│ └── titanic_survival_prediction.ipynb
│
├── README.md
├── .gitignore
└── venv/

Learning Outcomes

This project helped strengthen practical skills in:

Data Cleaning
Data Preprocessing
Exploratory Data Analysis
Data Visualization
Statistical Analysis
Machine Learning Fundamentals
Predictive Modeling
Future Improvements
Compare multiple machine learning models
Perform feature engineering
Hyperparameter tuning
Add confusion matrix and advanced evaluation metrics
Deploy the model as a web application
Author

Mahnoor Naseer

Data Science Intern

Dataset

The project uses the Titanic dataset, a widely used dataset for binary classification and machine learning practice.

Target Variable:

Survived
0 = Did Not Survive
1 = Survived
