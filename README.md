# Task-6
:

🚢 Titanic Survival Prediction using KNN - README
📂 Project Overview
This project aims to predict passenger survival from the Titanic disaster using the K-Nearest Neighbors (KNN) classification algorithm. The dataset used for training and testing comes from the classic Titanic dataset, which includes demographic and passenger information.

The confusion matrix generated at the end of the classification process helps evaluate the performance of the model.

📁 Dataset
Filename: titanic dataset.csv

✅ Key Features (Columns):
PassengerId: Unique identifier for each passenger.

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).

Name: Name of the passenger.

Sex: Gender of the passenger.

Age: Age in years.

SibSp: Number of siblings/spouses aboard the Titanic.

Parch: Number of parents/children aboard the Titanic.

Ticket: Ticket number.

Fare: Passenger fare.

Cabin: Cabin number (can be missing).

Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

Survived: Survival (0 = No, 1 = Yes) → Target variable

🧠 Model Used
Algorithm: K-Nearest Neighbors (KNN)
Library: Scikit-learn

🔧 Key Steps:
Data Cleaning:

Handling missing values (especially in Age, Cabin, and Embarked).

Encoding categorical variables (Sex, Embarked) into numeric.

Feature Scaling:

Standardization/Normalization of numerical features for better KNN performance.

Splitting:

Dataset split into training and testing sets (e.g., 80/20).

Training:

Fitting KNN classifier on training data.

Evaluation:

Using a confusion matrix and accuracy score to assess the performance.

