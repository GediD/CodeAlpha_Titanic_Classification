# prompt: write a readme with the charts included

# Titanic Survival Prediction

This project analyzes the Titanic dataset to predict passenger survival using machine learning.

## Data Exploration and Visualization

Several visualizations were created to understand the relationships between different features and passenger survival:

* **Age vs. Survival:**  [age_vs_survival.png](age_vs_survival.png)
    * Shows the distribution of ages for both survivors and non-survivors.

* **Sex vs. Survival:** [sex_vs_survival.png](sex_vs_survival.png)
    * Illustrates the survival rates for males and females.

* **Fare vs. Survival:** [fare_vs_survival.png](fare_vs_survival.png)
    * Presents the distribution of fares for survivors and non-survivors.

* **Ticket Class vs. Survival:** [pclass_vs_survival.png](pclass_vs_survival.png)
    * Shows the survival rates across different ticket classes (Pclass).


* **Port of Embarkation vs. Survival:** [embarked_vs_survival.png](embarked_vs_survival.png)
    * Displays the survival rates based on the port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

* **Family Size vs. Survival:** [familysize_vs_survival.png](familysize_vs_survival.png)
    * Shows the survival rates based on family size.

* **Age Distribution of Female Survivors:** [female_survivors_age.png](female_survivors_age.png)
    * Shows the age distribution of female survivors.

* **Age Distribution of Male Survivors:** [male_survivors_age.png](male_survivors_age.png)
    * Shows the age distribution of male survivors.

* **Fare Category vs. Survival:** [fare_category_vs_survival.png](fare_category_vs_survival.png)
    * Survival rates across different fare categories (Low, Medium-Low, Medium-High, High)

* **Port of Embarkation vs. Survived:** [embarked_vs_survived.png](embarked_vs_survived.png)
    * Survival rates based on port of embarkation.  Clarified labels for better understanding.

* **Ticket Class vs. Survival:** [Ticket_class_vs_survival.png](Ticket_class_vs_survival.png)
     * Shows survival rates based on ticket class.

* **Family Category vs. Survival:**  [Family_Category_vs_Survived]()
    * Illustrates survival rates categorized by family size groupings (Alone, Small, Medium, Large).


* **Age vs. Survival (Detailed):** [Age_vs_Survival.png](Age_vs_Survival.png)
    * Provides a detailed look at the distribution of ages and their relation to survival.



## Data Preprocessing

The data undergoes several preprocessing steps:

1.  **Handling Missing Values:** Missing 'Age' values are filled with the mean age, and missing 'Embarked' values are filled with the mode.
2.  **Data Type Conversion:** Relevant columns are converted to appropriate data types (category, numeric).
3.  **Feature Engineering:** 'SibSp' and 'Parch' are combined into 'FamilySize'. Unnecessary columns like 'PassengerId', 'Name', 'Ticket', and 'Cabin' is dropped.
4.  **One-Hot Encoding:** Categorical features ('Embarked', 'Sex') are encoded using one-hot encoding.
5.  **Feature Scaling:** Features are scaled using StandardScaler to ensure that features with larger values do not unduly influence model training.

## Model Training and Evaluation


Multiple classification models are trained and evaluated using appropriate metrics:

* **Model Selection:** Logistic Regression, SVC, Decision Tree, KNN, Gaussian Naive Bayes, XGBoost, Random Forest, AdaBoost, Gradient Boosting, Extra Trees.
* **Performance Metrics:** Accuracy, Precision, Recall, F1-Score.

## Results

The results are summarized in a table which will be displayed in the output when the code runs.


## Further Improvements

* Explore more advanced feature engineering techniques.
* Experiment with other classification models and ensemble methods.
* Perform more rigorous hyperparameter tuning.
* Analyze feature importance for better model interpretability.


## Dependencies

* pandas
* numpy
* seaborn
* matplotlib
* scikit-learn
* imblearn
* xgboost
