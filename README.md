
# Titanic Survival Prediction
This project aims to predict whether a passenger would have survived the Titanic disaster using machine learning models. The dataset used is the famous Titanic dataset from Kaggle.

## Table of Contents
- Project Overview
- Dataset
- Descriptive Statistis
- Data Visualization
- Features
- Data Preprocessing
- Modeling
- Evaluation
- Usage
- Results
- Contributing
- License
- Contact Information

## Project Overview
The goal of this project is to build a model that predicts the survival of passengers on the Titanic. The dataset includes various features such as age, sex, passenger class, fare, and more.

## Dataset
The dataset used in this project is the Titanic dataset, which is available on Kaggle. It includes information about the passengers aboard the Titanic.

## Descripitive statistics
Descriptive statistics were performed to understand the data better, focusing on numerical variables like Fare. Detailed analysis can be found in the notebook.

## Data Visualization
This project includes data visualization using Python to provide insightful visualizations of the dataset, helping to identify patterns and trends.

## Features
The features used for prediction are:

- Pclass: Passenger class (1st, 2nd, 3rd)
- Sex: Gender of the passenger (male, female)
- Age: Age of the passenger
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Fare: Passenger fare
- Embarked: Port of embarkation (Queenstown, Southampton, Cherbourg)
- The target variable is Survived (0 = No, 1 = Yes).


## Data Preprocessing
The following preprocessing steps were applied:

- Mapping Categorical Variables: The Sex and Embarked features were converted to numerical values.
- Handling Missing Values: Missing values in the Age and Fare columns were filled with the median of each column.

## Modeling
Several machine learning models were trained and evaluated, including:

- Logistic Regression
- Decision Trees
- Random Forests
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)
- Evaluation

The models were evaluated using accuracy, precision, recall, and F1-score. The best model was selected based on its performance on the validation set.

## Usage
This project allows users to predict whether a passenger would have survived the Titanic disaster. The best performing model achieved an accuracy of 100% on the validation set. Detailed performance metrics for each model can be found in the notebook.

The best performing model achieved an accuracy of 100% on the validation set. Detailed performance metrics for each model can be found in the notebook.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.

## Contact Information

For any questions or inquiries, please contact Geofrey Njoroge at njorogeofrey73@gmail.com
