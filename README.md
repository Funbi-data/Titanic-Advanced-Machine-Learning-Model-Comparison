**Titanic Survival Prediction: Advanced Machine Learning Models
Project Overview**

This project was completed as part of the AnalystLab Africa Machine Learning Internship Program (Week 5 – Advanced Machine Learning).

The objective was to predict passenger survival on the Titanic using multiple machine learning algorithms and compare their performance to identify the best-performing model.
**
**Dataset**

Dataset: Titanic Survival Dataset
**Features Used**
Pclass (Passenger Class)
Sex
Age
Fare
Target Variable
Survived (0 = No, 1 = Yes)
**Project Workflow**
1. Data Preparation
Loaded Titanic dataset
Handled missing values
Encoded categorical variables
Selected relevant features
Split dataset into training and testing sets
2. Model Development

The following models were trained and evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Hyperparameter Tuning

Best Parameters
{
    'max_depth': 10,
    'n_estimators': 200
}
Best Cross Validation Score
83.29%
Model Performance
Model	Accuracy
Logistic Regression	79.89%
Decision Tree	74.86%
Random Forest	80.45%
Gradient Boosting	81.01%
Tuned Random Forest (CV Score)	83.29%
**Key Findings**
Decision Tree produced the lowest accuracy and showed signs of overfitting.
Random Forest improved performance by combining multiple decision trees.
Gradient Boosting achieved the highest test accuracy.
Hyperparameter tuning improved the Random Forest model further.
Challenges Encountered
Handling missing values in the Age column.
Converting categorical variables into numerical values.
Understanding model evaluation metrics.
Selecting optimal hyperparameters.
**Technologies Used**
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab
Evaluation Metrics

**The models were evaluated using:**

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Cross Validation Score
Conclusion

This project demonstrated how advanced machine learning algorithms can improve classification performance. Among the models tested, Gradient Boosting achieved the highest test accuracy, while the tuned Random Forest model achieved the strongest cross-validation score. The results highlight the importance of model comparison and hyperparameter tuning when building predictive machine learning systems.

Author

Funbi Opemipo Olowojesiku

GitHub: Funbi-data GitHub Profile

LinkedIn: https://www.linkedin.com/in/funbiolowojesiku
