# Comparative-Analysis
To build and compare Machine Learning and Deep Learning models for predicting customer churn and analyze their performance using standard evaluation metrics.

# Comparative Analysis of Machine Learning and Deep Learning Models for Customer Churn Prediction

## Objective
The primary objective of this project is to build, evaluate, and compare standard Machine Learning algorithms (Logistic Regression, Decision Tree, Random Forest, SVM) alongside a Deep Neural Network implemented in TensorFlow to identify churn-prone customers using the IBM Telco Churn dataset.

## Approach Followed
1. **Data Preprocessing & EDA:** Handled missing values in `TotalCharges`, applied `OneHotEncoder` for categorical feature encoding, and scaled numerical features using `StandardScaler`. Split dataset into an 80:20 train-test split with stratification.
2. **Model Training:** Trained four Machine Learning baselines and designed a 4-layer Deep Neural Network with Dropout regularization and Early Stopping to avoid overfitting.
3. **Evaluation:** Evaluated performance metrics across Accuracy, Precision, Recall, F1-Score, and ROC-AUC along with execution time profiling and Confusion Matrix plotting.

## Outcomes
- **Logistic Regression & Deep Neural Network** yielded the highest stability and top ROC-AUC scores (~0.84 - 0.85).
- Deep Neural Network achieved competitive predictive power, though Logistic Regression offered faster inference and lower computational footprint.


## Future Scope
- Incorporating hyperparameter tuning (e.g., Optuna, KerasTuner).
- Implementing Class Weighting or SMOTE techniques to handle dataset class imbalance.
- Model deployment as a REST API using FastAPI / Flask.

## Author Information
Author Name: Yogananda Reddy 
Author Email: yoganandareddy866@gmail.com  
