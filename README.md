# [Titanic Survival Prediction](https://github.com/GediD/CodeAlpha_Titanic_Classification/)

This project aims to predict the survival of passengers on the Titanic using machine learning.  The dataset is analyzed and preprocessed to improve model performance.  Various classification models are trained and evaluated, and results are compared to identify the best-performing model.

## Data Analysis and Preprocessing

The project includes exploratory data analysis (EDA) to understand the relationships between features and survival rates. Key steps include:

* **Summary Statistics:** Calculation of mean, median, mode, and other descriptive statistics for numerical features.
* **Correlation Analysis:** Identification of correlations between numerical features using a heatmap.
* **Encoding Categorical Features:** Conversion of categorical variables into numerical representations using OneHotEncoding.
* **Feature Scaling:** Standardization or normalization of numerical features to improve model performance.
* **Addressing Class Imbalance:** Employing techniques like SMOTE and RandomOverSampler to handle the imbalance in the target variable.


## Model Training and Evaluation

Multiple classification models are trained on the preprocessed dataset:

* Logistic Regression
* Support Vector Classifier (SVC)
* Decision Tree Classifier
* K-Nearest Neighbors Classifier
* Gaussian Naive Bayes Classifier
* XGBoost Classifier
* Random Forest Classifier
* AdaBoost Classifier
* Gradient Boosting Classifier
* Extra Trees Classifier

Each model's performance is evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Hyperparameter tuning is performed using GridSearchCV to optimize the SVC model.

## Results

A table summarizing the performance of each model across the evaluation metrics is provided.  The confusion matrix for each model is also visualized to understand the types of errors made by the classifiers.


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
