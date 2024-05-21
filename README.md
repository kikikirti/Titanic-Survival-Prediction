# Titanic Survival Prediction

This project predicts passenger survival on the Titanic using machine learning techniques.

## Data Source

The data was obtained from the [Titanic Passenger List](https://www.kaggle.com/datasets/yasserh/titanic-dataset).

## Data Exploration

The dataset contains 891 rows (passengers) and 12 columns (features). Here's an overview:

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Whether the passenger survived (1) or not (0). (Target variable)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) (proxy for socioeconomic status)
- **Name**: Passenger name.
- **Sex**: Passenger sex (male or female).
- **Age**: Passenger age in years.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Missing Value Handling

Missing values in the "Age" feature will be addressed through appropriate techniques.

## Model Training

Two machine learning models were used to predict passenger survival:

1. **Logistic Regression**: A linear model that estimates the probability of a binary outcome (survived or not) based on the features.
2. **Random Forest Classifier**: An ensemble model that combines multiple decision trees for improved prediction accuracy.

## Evaluation

The performance of each model will be evaluated using metrics such as accuracy.

## Further Exploration

- **Feature Engineering**: Creating new features from existing ones.
- **Model Hyperparameter Tuning**: For better performance.
- **Feature Importance Analysis**: To identify the most influential features.
