### Predicting Default of Credit Card Clients
#### Project Overview
This project aims to predict credit card defaults using machine learning models to assist financial institutions in risk assessment and credit management. Given the increasing issuance of credit cards and financial uncertainties, accurate prediction of potential defaulters is crucial for minimizing losses and maintaining financial stability.

#### Problem Statement
Financial institutions face challenges in identifying customers who may default on their credit card payments. This project builds predictive models using demographic, financial, and transactional data to classify customers as defaulters or non-defaulters.

#### Dataset
Size: 30,000 instances with 24 features
Target Variable: Default (1 = Default, 0 = No Default)
Type: Labeled classification dataset

#### Methodology
#### Data Preprocessing
1. Dropped unnecessary columns
2. Checked and ensured data consistency
3. Performed exploratory data analysis (EDA) to identify correlations and trends

#### Feature Selection
1. Applied Lasso regression for feature importance ranking
2. Used correlation analysis to identify influential variables

#### Modeling
1. Implemented multiple machine learning models:
2. Logistic Regression
3. K-Nearest Neighbors (KNN)
4. Decision Tree
5. Random Forest
6. Support Vector Machine (SVM)
7. XGBoost
8. Deep Learning (Neural Networks)
9. Ensemble modeling was employed to improve prediction accuracy

#### Performance Metrics
1. Accuracy Score
2. Precision, Recall, F1 Score
3. ROC-AUC Curve
   
#### Key Findings
1. Decision Tree showed the highest accuracy (90.9%) among individual models.
2. SVM with a non-linear kernel achieved 81.9% accuracy.
3. The Ensemble model (Random Forest, KNN, XGBoost) performed best on training data but showed overfitting tendencies.
4. Feature selection techniques significantly improved model interpretability and efficiency.

#### Future Improvements
1. Implement Explainable AI techniques like SHAP or LIME to enhance model transparency.
2. Conduct statistical tests (Cliff’s Delta, Cohen’s D Effect Size) to quantify variable impact.
3. Improve generalization by optimizing hyperparameter tuning and ensemble strategies.
