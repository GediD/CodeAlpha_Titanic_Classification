![titanic](https://github.com/user-attachments/assets/082c27a8-6921-4b52-a053-f56f5858a262)
# [Titanic Survival Prediction](https://github.com/GediD/CodeAlpha_Titanic_Classification/)



This project aims to predict the survival of passengers on the Titanic using machine learning.  The analysis involves data cleaning, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

## Project Overview

The dataset contains information about Titanic passengers, including demographics, ticket details, and cabin information.  The goal is to build a model that accurately predicts survival based on these features.

## Data

The data used in this project is sourced from [Specify the data source, e.g., Kaggle].  The dataset consists of the following features:


* **PassengerId:** Unique identifier for each passenger.
* **Survived:** Survival status (0 = No, 1 = Yes).
* **Pclass:** Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).
* **Name:** Passenger name.
* **Sex:** Passenger gender.
* **Age:** Passenger age.
* **SibSp:** Number of siblings/spouses aboard.
* **Parch:** Number of parents/children aboard.
* **Ticket:** Ticket number.
* **Fare:** Passenger fare.
* **Cabin:** Cabin number.
* **Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Methodology

1. **Data Cleaning:** Handling missing values, and converting data types.
2. **Exploratory Data Analysis (EDA):** Examining data distributions, correlations, and relationships between features and survival.  Visualizations are used to gain insights into the data.
3. **Feature Engineering:** Creating new features from existing ones to improve model performance (e.g., family size, title from name).
4. **One-Hot Encoding:** Converting categorical variables into numerical representations suitable for machine learning models.
5. **Data Splitting:** Dividing the data into training and testing sets using a stratified parameter to preserve class imbalance.
6. **Feature Scaling:** Applying RobustScaler to handle features with varying scales.
7. **Addressing Class Imbalance:** Using SMOTE to oversample the minority class (non-survivors) to balance the training data.
8. **Model Training and Evaluation:** Several classification models (Logistic Regression, SVM, Decision Tree, KNN, Naive Bayes, XGBoost, Random Forest, AdaBoost, Gradient Boosting, Extra Trees) were trained and evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.
9. **Hyperparameter Tuning:**  Performing hyperparameter tuning on the best-performing model (Support Vector Classifier) using GridSearchCV.
![Titanic_Charts](https://github.com/user-attachments/assets/1d6ac3a6-224f-4337-b2a5-71822a92f087)

## Results

The Support Vector Classifier (SVC) achieved the highest accuracy of approximately 83.2%.  Hyperparameter tuning did not significantly improve these metrics. The model strongly predicts Titanic's survival, highlighting the importance of features like age group, passenger class, fare, and family size.

## Future Work

* Explore additional feature engineering techniques.
* Investigate other classification models.
* Perform more extensive hyperparameter tuning.
* Investigate the impact of different data preprocessing methods.

## Dependencies

* pandas
* numpy
* seaborn
* matplotlib
* scikit-learn
* imblearn
* xgboost

## Usage

1. Install the required dependencies.
2. Run the Jupyter Notebook or Python script.


## Contact

[Gedion Dereje/www.linkedin.com/in/gedion-dereje-woltedji]

## Kaggle Competition

I participated in the Kaggle challenge and achieved the accuracy shown below.
  ![Kaggle_Submission_2](https://github.com/user-attachments/assets/ef646f01-7a9e-442a-a18c-28d4b1dde4ab)


