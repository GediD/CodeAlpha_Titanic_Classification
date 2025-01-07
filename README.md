![titanic](https://github.com/user-attachments/assets/082c27a8-6921-4b52-a053-f56f5858a262)
# Titanic Survival Prediction

This project analyzes the Titanic dataset to predict passenger survival using machine learning.

## Data Exploration and Visualization

Several visualizations were created to understand the relationships between different features and passenger survival:

* **Age vs. Survival:**
  
  ![age_vs_survival](https://github.com/user-attachments/assets/edd3a7b4-f136-4c94-90aa-cc3ad9b71a6c)
    * Shows the distribution of ages for both survivors and non-survivors.

* **Sex vs. Survival:**
  
  ![sex_vs_survival](https://github.com/user-attachments/assets/0753e9a4-c020-4a80-a98d-78c4a2d37903)
    * Illustrates the survival rates for males and females.

* **Family Category vs. Survival:**
  
 ![family_size_vs_survival](https://github.com/user-attachments/assets/140d1fa0-fe73-4206-9c93-05b1f568a873)
   
    * Illustrates survival rates categorized by family size groupings (Alone, Small, Medium, Large).

* **Ticket Class vs. Survival:**
  
  ![pclass_vs_survival](https://github.com/user-attachments/assets/bab029c6-fff9-4b93-a62a-55b2087c5343)
    * Shows the survival rates across different ticket classes (Pclass).

* **Port of Embarkation vs. Survival:**
  
  ![embarked_vs_survived](https://github.com/user-attachments/assets/574cf5cd-08a7-474b-b2a1-63da49baf1d1)
    * Displays the survival rates based on the port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

* **Fare Category vs. Survival:**

  ![fare_category_vs_survival](https://github.com/user-attachments/assets/6380537d-f67c-4b36-a70b-52f0691631d6)
     * Survival rates across different fare categories (Low, Medium-Low, Medium-High, High)

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

The results are summarized in a table displayed in the output when the code runs.
![model_performance](https://github.com/user-attachments/assets/990a97b9-fa70-4ce1-ad43-0dcad9911cc0)



## Further Improvements

* Explore more advanced feature engineering techniques.
* Experiment with other classification models and ensemble methods.
* Perform more rigorous hyperparameter tuning.
* Analyze the importance of features for better model interpretability.


## Dependencies

* pandas
* numpy
* seaborn
* matplotlib
* scikit-learn
* imblearn
* xgboost
