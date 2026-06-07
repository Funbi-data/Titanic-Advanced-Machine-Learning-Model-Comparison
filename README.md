# Advanced Machine Learning Model Comparison on Titanic Survival Prediction

## Problem Statement

The objective of this project was to predict whether a passenger survived the Titanic disaster using machine learning classification algorithms. The project aimed to compare multiple advanced machine learning models and identify the best-performing model based on evaluation metrics.

## Dataset Used

The Titanic Survival Dataset was used for this project. The dataset contains passenger information such as:

* Passenger Class (Pclass)
* Sex
* Age
* Fare
* Survival Status (Target Variable)

The dataset was cleaned by handling missing values and encoding categorical variables before model training.

## Algorithms Used

The following machine learning algorithms were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Gradient Boosting Classifier

Additionally, GridSearchCV was used to perform hyperparameter tuning on the Random Forest model.

## Model Performance

### Logistic Regression

* Accuracy: 79.89%

### Decision Tree

* Accuracy: 74.86%

### Random Forest

* Accuracy: 80.45%

### Gradient Boosting

* Accuracy: 81.01%

### Tuned Random Forest

* Best Parameters:

  * max_depth = 10
  * n_estimators = 200
* Cross Validation Score: 83.29%

## Challenges Faced

* Handling missing values in the Age column.
* Converting categorical variables such as Sex into numerical values.
* Understanding the differences between multiple classification algorithms.
* Selecting appropriate hyperparameters for model optimization.

## Key Findings

* Decision Tree produced the lowest accuracy and was more prone to overfitting.
* Random Forest improved prediction performance by combining multiple decision trees.
* Gradient Boosting achieved the highest testing accuracy of 81.01%.
* Hyperparameter tuning further improved Random Forest performance.
* Ensemble learning methods generally performed better than a single Decision Tree model.

## Conclusion

The project demonstrated the effectiveness of advanced machine learning techniques for classification tasks. Gradient Boosting emerged as the best-performing model on the test dataset, while the tuned Random Forest achieved the strongest cross-validation performance. This highlights the importance of model selection and hyperparameter optimization in building accurate predictive systems.
