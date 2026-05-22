#Titanic Survival Prediction
## project Overview
this project predicts whether a passenger survived the titanic disaster using machine learning
the model is trained using the titanic dataset and uses features likes
- Age
- Gender
- Passenger Class
- Fare
- Family member

---
#Technoloies Used
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- pycharm - for deployement
---
## Dataset
Dataset Used:
- Titanic Dataset ('titanic.csv')
Columns include:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- Fare
- Embarked
## Project Workflow

### 1. Data Collection
Loaded Titanic dataset using Pandas.

### 2. Data Cleaning
- Handled missing values
- Removed unnecessary columns
- Converted categorical data into numerical format

### 3. Exploratory Data Analysis (EDA)
Created charts and graphs to understand:
- Survival rate
- Gender distribution
- Passenger class analysis
- Age distribution

### 4. Model Building
Machine Learning algorithms used:
- Logistic Regression
- KNN Classifier
- Decision Tree

### 5. Model Evaluation
Checked:
- Accuracy Score
- Confusion Matrix

---

## Project Structure

text
Titanic-Survival-Prediction/
│
├── data/
│   └── titanic.csv
│
├── notebooks/
│   └── titanic_analysis.ipynb
│
├── scripts/
│   └── train_model.py
│
├── model/
│   └── model.pkl
│
├── app.py
├── requirements.txt
├── README.md
│
└── screenshots/
    └── dashboard.png
