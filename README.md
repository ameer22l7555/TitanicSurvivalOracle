# Titanic Survival Prediction

A machine learning project that predicts passenger survival on the Titanic using various classification algorithms.

## Project Overview

This project analyzes the famous Titanic dataset to build predictive models that determine which passengers were more likely to survive the disaster. The project showcases:

- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Model selection and training
- Model evaluation and accuracy measurement

## Dataset

The dataset contains information about Titanic passengers including:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger name
- **Sex**: Gender of passenger
- **Age**: Age of passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

- `Titanic-Class-with_Accuracy.ipynb`: Jupyter notebook with model implementation and accuracy measurement
- `Titanic classification.ipynb`: Detailed notebook with EDA and full model development
- `titanic classification train.csv`: Training dataset

## Key Insights

The analysis reveals several factors that influenced survival rates:

- Women had higher survival rates than men
- First-class passengers had better survival chances
- Young children were prioritized for rescue
- Family size played a role in survival probability

## Models Implemented

Various classification models were explored, including:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines

## Getting Started

1. Clone this repository
2. Install the required dependencies using `pip install -r requirements.txt`
3. Open and run the Jupyter notebooks

## Future Work

- Implement more advanced models (XGBoost, Neural Networks)
- Perform hyperparameter tuning to improve model performance
- Add more feature engineering
- Develop a web application for predictions